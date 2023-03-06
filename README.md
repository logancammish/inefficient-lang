Concept, not complete.

# inefficient-lang
An intentionally inefficiently, and horribly designed programming language which should never be used.

Syntax example:
```infe
function MAIN() RETURNING INTGER_BIT32 [
  arr array = { [1] = STRING "one", [2] = STRING "two" };
  for INTEGER_BIT32 i in read_array(array) do { 
    lib::standard::print_functions::println(i); // yes, you *always* have to type *all* of this
    lib::standard::garbage_collector::initialize(); // garbage collector that runs automatically? why would you ever want that! 
  }
  
  return 0; 
]
return 0; // serves no use, just made it a requirement
```
