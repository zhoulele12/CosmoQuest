# Verilog

- `initial` starts a block that is executed only once
- `begin` `end` behave just like `{}`. They are needed when the block contains more than one statement
- `$finish` terminates current simulation
- every block is a thread that executes independently and simultaneously. \
within every block, code (including delay) is processed sequentially.
- single `&`, `|`  are bitwise operators, double `&&`, `||` are logical operators.
- `assign out = select ? in1:in2;` If `select` is true, output `in1`, else output `in0`
- `{ }` is concatenation. e.g. `assign {Cin,A,B} = i[4:0]`
- datatypes include wires, registers,etc.
- compile all files together eliminates the need to import in each module.
- `iverilog [-Wimplicit] -o output_name.vvp file1.v file2.v file2_tb.v`
- use `$dumpfile("filename.vcd")` and `$dumpvars(0,current_module_name)`. 0 means all vars. 
- when declaring `input`, `output`, `wire`, it's very important to declare the bits too. e.g. `reg[4:0]`
- array of registers `reg[4:0] array[0:3]` -> an 4-element array of 5-bit registers
- `always` block executes multiple times. -> either use delays or sensitivity lists(`always @()`). else it's an infinite loop with 0 delay.