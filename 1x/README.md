# 1x April 13, 1999

* What is Forth?
   * Highly factored code
   * Definitions
   * Stacks (required to support definitions)
* What is a definition?
   * : SOME .... ;
   * an abbreviation
   * should never have more than 1-2 arguments
   * stack should never be more than 3-4 deep
* Current incarnation of a definition is to make it red
   * SOME ....
   * MORE .... ;
* Colors
   * black means execute
   * red means define
   * green means compile
* Words to manipulate stack
   * DUP
   * DROP
   * OVER
   * SWAP
* People who draw stack diagrams are doing something wrong
* Conditionals
   * IF ELSE THEN (classic forth)
   * Else isn't worth the complexity
   * IF ... ; THEN
* Loops
   * DO .. LOOP  ( 2 parameters and just too complicated )
   * FOR .. NEXT  ( 1 parameter, good for hardware implementation )
   * BEGIN .. UNTIL  ( variable num params )
   * WORD: ... IF ... WORD ; THEN ... ;  ( seems to be adequate )
      * Needs recursive definitions, no smudge
      * Tail recursion
* Block
   * Used to access a region of disk
   * Now accesses a region of memory
   * BLOCK   1024 * ;
* More than the formalism
   * Every application out there has ten times as much code as necessary
   * How large should the TCP/IP stack be?
* How to make programs small
   * No hooks
   * Don't complexify
   * 10x code = 10x cost = 10x bugs = 10x maintenance
* 1x - factor factor factor
   * Find the hundred words that can solve the problem
   * Write a one line solution
   * E.g. Files
      * Open
      * Close
      * Read
      * Write
      * Don't need the complexity
   * General solution isn't required
* Lose patience with small characters
   * Only put so much on each slide
   * 20x14 that's enough
   * Formatted end up with a wall of red on the left
* Machine Forth
   * IF ( leaves argument on the stack, avoid ?dup )
   * -IF ( tests for the sign bit )
   * @+ ( increment fetch )
   * - ( one's complement )
* DO..LOOP vs @+
   * A acts like a local variable
   * Don't use local variables
* If you run out of things to do, write a web browser
