pass1:
Extracts all symbols and sections.

pass2:
Each instruction is converted to machine code.
The programs again reads the symbol table to get address and size associated with each symbol.
Other Functions:

dec_to_bin(int) : Converts the given decimal number to the Binary String
search_MOT(string) : It searchers the MOT for the Machine Operation Code and returns the index.
search_symbol_table(string) : It searches the symbol_table and returns the address of the symbol.
get_size(string) : It returns the size of the symbol/operation.
get_data(string) : It extracts data from string and converts it into its binary equivalent.


Structures:
mnemonics : Machine Operation Table
symbol : Symbol Table
section: Section Table

Data Structures:
Vector
File Stream