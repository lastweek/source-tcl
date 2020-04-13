# NOTE

Why TCL? Because I use TCL in FPGA development, i.e., Xilinx Vivado.
It's funny that TCL is used extensively across hardware development community.
I once read a post about why companies used TCL in the first place, it seems
that TCL was free by then (released by Prof. John Ousterhoud).

TCL compiler is written in C.

## Code

- `compat/` some portable headers across different OS.
- `library/` has TCL scripts, seems for post-compilation?
- OS Specific, looks like
	- `win/`
	- `unix/`
	- `macosx/`
- `generic/` is the main source code
	- The core is actually quite neat
	- No wonder that TCL can be easily integrated into applications


### Coding Style

It uses CamelCase coding style. typedef is used extensively (ugh).
The code is very clean though.
