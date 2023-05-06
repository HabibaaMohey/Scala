# Scala
A huge retail store wants a rule engine that qualifies orders’ transactions to discounts based  on a set of qualifying rules.And automatically calculates the proper discount based on some calculation rules.



#Technical considerations:
• We can have wrappers of impure functions to interact with the outside world. 
However, the core logic must be written in a pure functional manner. 
In the core functional logic:
• Use only vals, no vars allowed.
• No mutable data structures allowed.
• No loops allowed.
• No Null values.
• Make sure all your functions are pure:
o Output depends solely on input.
o Input to the function doesn’t get mutated.
o Has a predictable behavior.
