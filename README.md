# TUCA Assembly Language Support

Visual Studio Code extension providing syntax highlighting and language support for TUCA-5.1 Assembly Language.

## About TUCA

TUCA-5.1 (TTU Computer Architecture) is an educational assembly language developed by Dr. Juan Carlos Rojas at Texas Tech University. It is designed to teach computer architecture and assembly programming concepts through a simplified, yet practical instruction set.

### Architecture Features

- 8-bit machine with GPR load-store architecture
- 16 general purpose registers (r0-r15)
- 8-bit ALU
- 256-byte programmable data memory (0x00-0xFF)
- 4096-byte instruction memory
- Fixed-length 2-byte instruction encoding

## Extension Features

This extension enhances your TUCA assembly programming experience with:

### Syntax Highlighting

- Instructions (ld, st, add, etc.) in purple/magenta
- Registers (r0-r15) in blue
- Labels (ending with :) in yellow/gold
- Definitions (def statements) in purple
- Numbers (hex and decimal) in light green
- Comments (# lines) in green
- Special variables (op1, op2, result, etc.) in light blue

### Code Organization

- Comment support (# for line comments)
- Code folding for labeled sections
- Macro definition highlighting
- Support for both hex (0x) and decimal numbers

## Usage

1. Install the extension
2. Open any .txt file containing TUCA assembly code
3. The syntax highlighting will automatically activate

## Instruction Set

TUCA-5.1 supports various instruction types:

- Load/Store (ld, ldr, ldi, st, str)
- Arithmetic & Logic (add, and, or, not, neg)
- Bit Manipulation (shl, shr)
- Comparison (eq, gt)
- Control Flow (if, skipif, jmp, jmpr)
- Program Control (halt)

## Credits

- TUCA-5.1 Architecture and Design: Dr. Juan Carlos Rojas (Texas Tech University)
- Extension Development: Andres Antillon

## License

This extension is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Feedback and Contributions

This extension is maintained by Andres Antillon. For issues, suggestions, or contributions:

- File an issue on [GitHub](https://github.com/axantillon/tuca-assembly)
- Contact the publisher through the VS Code Marketplace
