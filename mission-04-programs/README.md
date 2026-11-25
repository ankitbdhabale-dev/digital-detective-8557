# Mission 4 — How programs run

> Draft based on the assignment. Replace observation and reflection prompts with your own verified work and rewrite explanations in your own words before submission. Do not claim GitHub actions until they are actually visible.

## 1. Task / objective
Complete the tasks listed in this mission of the Digital Detective assignment.

## 2. Work completed and answer notes

## 4.1 `hello.py`

```python
print("Hello from Python")
```

Run from the mission folder with `python3 hello.py`. **Observed output:** [RUN IT AND CONFIRM THE MESSAGE APPEARS].

## 4.2 Compiler and interpreter

| Point | Compiler | Interpreter |
|---|---|---|
| When translation/execution happens | Translates source code before execution, often producing a separate executable or intermediate form. | Reads and executes instructions at runtime, often as the program runs. |
| Typical output | An executable or compiled/bytecode form. | Program results, without necessarily creating a standalone executable. |
| Example | C compiler such as GCC | Python interpreter (CPython) |
| One advantage | The resulting program can run without recompiling source each time on a compatible system. | Quick to try and change code during development. |

A compiler usually translates a program before it runs, while an interpreter handles instructions during execution. Compilers commonly produce an executable or intermediate code; an interpreter commonly runs the code through a runtime. C is a familiar compiled-language example, while Python is commonly run through an interpreter. Real language implementations can combine compilation and interpretation techniques.

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

### Program run actually performed

Running `python3 mission-04-programs/hello.py` displayed `Hello from Python`.
