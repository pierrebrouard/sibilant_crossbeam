# sibilant_crossbeam
Technical Exercise in Functional Programming Lisp-like project

## Solution explanation

As I wanted to solve this exercise I ran into some troubles mostly because of the syntax of the language and the low amount of resources I could use (very basic tools)

At first I wanted to write a solution in an Iterative way, then remembered I had to solve it using Functional principles.

I began to explode as much as I could the code and considered I could use the "rest" keeword to make a recursive check on every time schedules.

After finding out the good overlapping time schedule function and incrementing the appropriate variable plus using the correct stopping condition I was able to pass Test 1.

Regarding Test 2 it was all ok too.

When reaching Test 3 I was faced with wrong answer "2" rooms required instead of "3". I forgot about the "first" room required to have at least 1 meeting.

I had to rethink the count of overlapping and add the edge case of "0" count to be incremented to "1".

## Additional tests

The additional tests are other possible edge cases met.