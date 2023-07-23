# Awlang - Proof of concept

This repository was created to develop a minimal working awlang compiler.

## Syntax

The syntax should include:
- 32-bit integer numbers definition
- if-else conditions with the ability to compare 32-bit integer numbers
- reserved command to output 32-bit integer number

Example program:
```
int x = 10;
int y = 8;

if (x > y)
{
  WriteLine(x - y);
}
else
{
  WriteLine(x + y)
}
```

## Compilation

For this POC I want to create a simple AOT compiler for x86-64 that should be able to compile a single `.aw` file to a working `.exe` file.

## License

This repo is licensed under the [MIT](./LICENSE) license.
