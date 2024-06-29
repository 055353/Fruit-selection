# Fruit-selection
This Python script allows a user to select a fruit from a predefined list by entering an index value.
# Functionality

The script defines a list of fruits (`['apple', 'orange', 'mango']`) and a function `selection(index)` that returns the fruit at the specified index. If the user provides an invalid index or a non-integer input, appropriate error messages are displayed.

## Usage

1. Run the script.
2. Enter an integer value between 0 and 2 when prompted.
3. The script will print the corresponding fruit or an error message if the input is invalid.
   
### `selection(index)`

Selects a fruit from the list based on the given index.

#### Parameters:
- `index` (int): The index of the fruit in the list.

#### Returns:
- `str`: The fruit at the given index. If the index is out of range or not an integer, an appropriate message is returned.

### Error Handling

- If the input is not an integer, the message "The input is not a number" is returned.
- If the input is an integer but out of the range 0-2, the message "Please enter a number within 0 - 2" is returned.
