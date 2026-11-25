**Approach (Using Stack)**
Push -1 initially into the stack.
Traverse the string:
  If '(', push its index.
  If ')', pop the top.
  If stack becomes empty, push the current index.
Otherwise, calculate valid length as i - stack.peek() and update maximum.
