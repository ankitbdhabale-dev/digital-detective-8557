# Mission 5 — Numbers and data

> AI-assisted answer notes. Manual conversions and program outputs were checked in this session.

## Manual conversions

- 13 decimal = 8 + 4 + 1 = 1101 binary.
- 25 decimal = 16 + 8 + 1 = 11001 binary.
- 1010 binary = 8 + 2 = 10 decimal.
- 1101 binary = 8 + 4 + 1 = 13 decimal.
- A hexadecimal = 10 decimal.
- 1F hexadecimal = 1×16 + 15 = 31 decimal.
- 1111 binary = 15 decimal = F hexadecimal.

## Program results

number_converter.py was run with these inputs:

| Decimal input | Binary | Hexadecimal |
|---:|---:|---:|
| 10 | 1010 | A |
| 25 | 11001 | 19 |
| 31 | 11111 | 1F |

The output matches the manual conversions. bin() and hex() add 0b and 0x prefixes; slicing removes those prefixes. upper() makes hexadecimal letters uppercase.

## Text encoding

ASCII assigns uppercase A the value 65 and lowercase a the value 97. Character encodings map characters to numbers. UTF-8 can represent characters outside basic ASCII, such as é.

## AI-assisted learning note

Binary uses powers of two; hexadecimal uses powers of sixteen. Character encoding lets computers represent written text as numbers.

## Commit and evidence

The converter file and this README are in mission-05-numbers-data. Original commit: “Build number converter and practise data representation.”
