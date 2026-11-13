# Mission 5 - Numbers and Data

## Work Completed

### Manual Number Conversions

I practised converting numbers between decimal, binary and hexadecimal systems.

| Conversion | Answer |
|---|---|
| Decimal 13 to Binary | 1101 |
| Decimal 25 to Binary | 11001 |
| Binary 1010 to Decimal | 10 |
| Binary 1101 to Decimal | 13 |
| Hexadecimal A to Decimal | 10 |
| Hexadecimal 1F to Decimal | 31 |
| Binary 1111 to Hexadecimal | F |

### Python Verification

I used Python functions to verify my manual answers.

| Python Expression | Result |
|---|---|
| `bin(13)` | `0b1101` |
| `bin(25)` | `0b11001` |
| `int('1010', 2)` | `10` |
| `int('1101', 2)` | `13` |
| `int('A', 16)` | `10` |
| `int('1F', 16)` | `31` |
| `hex(int('1111', 2))` | `0xf` |

### Number Converter Program

I created a Python program called `number_converter.py`.

The program takes a decimal number from the user and displays its binary and hexadecimal forms.

I tested the program with these numbers:

| Decimal Number | Binary | Hexadecimal |
|---|---|---|
| 10 | 1010 | A |
| 25 | 11001 | 19 |
| 100 | 1100100 | 64 |

### ASCII and UTF-8

ASCII assigns numerical values to characters.

- Uppercase `A` = 65
- Lowercase `a` = 97

UTF-8 is a character encoding standard that supports many languages and symbols.

A computer stores data as numbers, so encoding standards help represent characters correctly.

## Commands and Tools Used

- `python3`
- `python3 number_converter.py`
- `bin()`
- `hex()`
- `int()`
- `ord()`

## My Understanding

I learned how decimal, binary and hexadecimal number systems work. I also understood how Python can be used to convert numbers and how computers represent text using character encoding.

## Difficulties Faced

I initially found it difficult to understand the conversion process and the output of Python functions such as `bin()` and `hex()`.

## How I Resolved Them

I practised manual conversions and checked the answers using Python until I understood the results.

## Evidence

The `number_converter.py` program and this README file contain the work for this mission.

## Commit Details

The number conversion work and Python program were committed and pushed to GitHub.