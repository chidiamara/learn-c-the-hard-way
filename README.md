# Learn C The Hard Way

## This is not really about c

The most important lesson is rigorous defensive programming. Learning how to create software that defends itself from malicious activity and defects. However, C is the most difficult language to write securely.

The purpose of learning C from Zed Shaw is to become a better, stronger programmer.

### Two Reasons Why C is an Excellent Choice

- C's lack of nearly every modern safety feature means i have to be more vigilant and more aware of what's going on. If i can write secure, solid C code, i can write secure, solid code in any programming language.

- Learning C gives me direct access to a mountain of legacy code, and teaches me the base syntax of a large number of descendant languages.

## The Undefined Behaviourists

For a bit of background, C defines strings as blocks of memory that end in a `NUL` byte, or a `0` byte. When a C program receives a string without this `NUL` byte, the C program attempts to read past the end of this string and into the memory of the computer, causing the program to crash.

Every other language developed after C attempts to prevent this, but not C.

# What will be contained in this repository
- The basics of C syntax and idioms
- Compilation, `make` files, linkers
- Finding bugs and preventing them
- Defensive coding practices
- Breaking C code
- Writing basic UNIX systems software

I wish myself Goodluck 
