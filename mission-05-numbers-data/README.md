# Mission 5 — Numbers and data

> Draft based on the assignment. Replace observation and reflection prompts with your own verified work and rewrite explanations in your own words before submission. Do not claim GitHub actions until they are actually visible.

## 1. Task / objective
Complete the tasks listed in this mission of the Digital Detective assignment.

## 2. Work completed and answer notes

## 5.1 Manual conversions

| Question | Working and answer |
|---|---|
| Decimal 13 to binary | 13 = 8 + 4 + 1 = 2³ + 2² + 2⁰, so **1101₂**. |
| Decimal 25 to binary | 25 = 16 + 8 + 1 = 2⁴ + 2³ + 2⁰, so **11001₂**. |
| Binary 1010 to decimal | 1×2³ + 0×2² + 1×2¹ + 0×2⁰ = 8 + 2 = **10₁₀**. |
| Binary 1101 to decimal | 1×2³ + 1×2² + 0×2¹ + 1×2⁰ = 8 + 4 + 1 = **13₁₀**. |
| Hexadecimal A to decimal | A is digit value **10**. |
| Hexadecimal 1F to decimal | 1×16 + F(15) = 16 + 15 = **31₁₀**. |
| Binary 1111 to hexadecimal | 1111₂ = 15₁₀ = **F₁₆**. |

## 5.2 Python verification

Python expressions: `bin(13)` → `'0b1101'`; `int('1010', 2)` → `10`; `hex(31)` → `'0x1f'`; `int('1F', 16)` → `31`. These match the manual conversions above.

## 5.3 `number_converter.py`

```python
number = int(input("Enter a non-negative decimal integer: "))
print("Binary:", bin(number)[2:])
print("Hexadecimal:", hex(number)[2:].upper())
```

Run it using `python3 number_converter.py`. Example checks (you must run and record your own test results):

| Input | Binary | Hexadecimal |
|---:|---:|---:|
| 10 | 1010 | A |
| 25 | 11001 | 19 |
| 31 | 11111 | 1F |

`bin()` returns a binary representation with a `0b` prefix; `hex()` returns hexadecimal with a `0x` prefix. The slices remove those prefixes, and `.upper()` formats the hexadecimal letters in uppercase. This small program expects a non-negative whole number.

## 5.4 Text encoding

Uppercase **A** has ASCII decimal code **65**; lowercase **a** has code **97**. An encoding assigns numbers to characters so computers can store, transmit, and reproduce text consistently. A character outside basic ASCII is an example of a character that needs a broader encoding, such as UTF-8: **é**.

---

## 3. Commands / tools used
[Add the commands and applications you personally used, and explain their purpose.]

## 4. My understanding
[Rewrite the notes above in your own words and include what you observed.]

## 5. Difficulties faced
[Record actual difficulties, or “No major difficulties.”]

## 6. How I resolved them
[Record actual resolutions, or “Not applicable.”]

## 7. Evidence / files
[Add files and privacy-safe evidence actually included.]

## 8. Commit details
[Add the actual commit message and confirm that it was pushed.]

### Converter runs actually performed

The converter was run with inputs 10, 25, and 31 and produced respectively `(1010, A)`, `(11001, 19)`, and `(11111, 1F)` for binary and hexadecimal. The output matches the manual conversions.
