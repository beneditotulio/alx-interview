# 0x04. UTF-8 Validation

## Description

For the “0x04. UTF-8 Validation” project, you will need to apply your knowledge in bitwise operations, understanding of the UTF-8 encoding scheme, and Python programming skills to validate whether a given dataset represents a valid UTF-8 encoding.

## Concepts Needed

### Bitwise Operations in Python

Understanding how to manipulate bits in Python, including operations like AND (&), OR (|), XOR (^), NOT (~), shifts (<<, >>).

- [Python Bitwise Operators](https://realpython.com/python-bitwise-operators/)

### UTF-8 Encoding Scheme

Familiarity with the UTF-8 encoding rules, including how characters are encoded into one or more bytes. Understanding the patterns that represent a valid UTF-8 encoded character.

- [UTF-8 Wikipedia](https://en.wikipedia.org/wiki/UTF-8)
- [Characters, Symbols, and the Unicode Miracle](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

### Data Representation

How to represent and work with data at the byte level. Handling the least significant bits (LSB) of integers to simulate byte data.

### List Manipulation in Python

Iterating through lists, accessing list elements, and understanding list comprehensions.

- [Python Lists](https://docs.python.org/3/tutorial/datastructures.html)

### Boolean Logic

Applying logical operations to make decisions within the program.

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should use the PEP 8 style (version 1.7.x)
- All your files must be executable

## Additional Resource

- [Mock Technical Interview](https://www.pramp.com/)

## Usage

To validate a dataset for UTF-8 encoding, use the `validUTF8` function defined in `0-validate_utf8.py`.

### Example

```python
#!/usr/bin/python3
"""
Main file for testing
"""

validUTF8 = __import__('0-validate_utf8').validUTF8

data = [65]
print(validUTF8(data))  # True

data = [80, 121, 116, 104, 111, 110, 32, 105, 115, 32, 99, 111, 111, 108, 33]
print(validUTF8(data))  # True

data = [229, 65, 127, 256]
print(validUTF8(data))  # False



### Steps to Create the README.md File

1. Open your terminal.
2. Navigate to the [`0x04-utf8_validation`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FD%3A%2FGitHub%2Falx-interview%2F0x04-utf8_validation%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "d:\GitHub\alx-interview\0x04-utf8_validation") directory in your repository.
3. Create a new file named `README.md`.
4. Copy and paste the above content into the file.
5. Save the file.

### Commands

```sh
cd alx-interview/0x04-utf8_validation
echo "# 0x04. UTF-8 Validation

## Description

For the “0x04. UTF-8 Validation” project, you will need to apply your knowledge in bitwise operations, understanding of the UTF-8 encoding scheme, and Python programming skills to validate whether a given dataset represents a valid UTF-8 encoding.

## Concepts Needed

### Bitwise Operations in Python

Understanding how to manipulate bits in Python, including operations like AND (&), OR (|), XOR (^), NOT (~), shifts (<<, >>).

- [Python Bitwise Operators](https://realpython.com/python-bitwise-operators/)

### UTF-8 Encoding Scheme

Familiarity with the UTF-8 encoding rules, including how characters are encoded into one or more bytes. Understanding the patterns that represent a valid UTF-8 encoded character.

- [UTF-8 Wikipedia](https://en.wikipedia.org/wiki/UTF-8)
- [Characters, Symbols, and the Unicode Miracle](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

### Data Representation

How to represent and work with data at the byte level. Handling the least significant bits (LSB) of integers to simulate byte data.

### List Manipulation in Python

Iterating through lists, accessing list elements, and understanding list comprehensions.

- [Python Lists](https://docs.python.org/3/tutorial/datastructures.html)

### Boolean Logic

Applying logical operations to make decisions within the program.

## Requirements

- Allowed editors: \`vi\`, \`vim\`, \`emacs\`
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
- All your files should end with a new line
- The first line of all your files should be exactly \`#!/usr/bin/python3\`
- A \`README.md\` file, at the root of the folder of the project, is mandatory
- Your code should use the PEP 8 style (version 1.7.x)
- All your files must be executable

## Additional Resource

- [Mock Technical Interview](https://www.pramp.com/)

## Usage

To validate a dataset for UTF-8 encoding, use the \`validUTF8\` function defined in \`0-validate_utf8.py\`.

### Example

\`\`\`python
#!/usr/bin/python3
\"""
Main file for testing
\"""

validUTF8 = __import__('0-validate_utf8').validUTF8

data = [65]
print(validUTF8(data))  # True

data = [80, 121, 116, 104, 111, 110, 32, 105, 115, 32, 99, 111, 111, 108, 33]
print(validUTF8(data))  # True

data = [229, 65, 127, 256]
print(validUTF8(data))  # False
\`\`\`

## Author

- Túlio Benedito Nhantumbo
" > README.md