Implement a simple stack that accepts the following commands:

- `push k` : Push integer k to the top of the stack
- `pop` : Pop the top element
- `inc e k` : Add k to teach of the bottom e elements of the stack.

Complete the function superStack. The function must create an empty stack and perform each
of the operations in order. After each operation, print the value of the stack's top element on a new line.
If the stack is empty, print EMPTY.
```
static void superStack(String[] operations) {
    MySuperStack stack = new MySuperStack();
    for (String operation : operations){
        String[] input = operation.split(" ");
        if (input.length == 1) { // pop
            stack.pop();
        } else if (input.length == 2) { // push
            stack.push(Integer.valueOf(input[1]));
        } else if (input.length == 3) { // inc
            stack.inc(Integer.valueOf(input[1]),
                    Integer.valueOf(input[2]));
        }
    }
}
```
