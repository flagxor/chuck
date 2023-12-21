# Talks by Chuck Moore

My attempt to gather information about and links to Chuck Moore's Various Talks
over the years, particularly the annual Fireside Chat.

## Forth Presentation 1993

* [Part 1 of 2 video](https://www.youtube.com/watch?v=B_cf8n58Ews)
* [Part 2 of 2 video](https://www.youtube.com/watch?v=Dbd7Xu0ibJM)

* Complexity of early Forth board vs ShBoom (I think)
   * Comparison to complexity in IBM PC
* Simplest possible hardware + software as a combination
* [screens](presentation_1993/README.md)

## Forth Day 1994-1997

* Seems to be no video around of these.
* Anyone recall what was presented?

## Forth Day 1998

* [video](https://www.youtube.com/watch?v=40ZIKHJ1H5E)
* [slides](forth_day_1998/README.md)

## 1x Forth

* [video](https://www.youtube.com/watch?v=NK0NwqF8F0k)
* Video camera date says April 13, 1999
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

## Forth Day 1999

* [video](https://www.youtube.com/watch?v=N1FUY6g5crA)

## Forth Day 2000

* [video](https://www.youtube.com/watch?v=FL8RsCLvsHE)

## Forth Day 2001-2004

* Seems to be no video around of these.
* Anyone recall what was presented?

## Forth Day 2005

* [video](https://www.youtube.com/watch?v=Z3M8f-9NpsE)

## Forth Day 2006-2007

* Seems to be no video around of these.
* Anyone recall what was presented?

## Forth Day 2008

* [video](https://www.youtube.com/watch?v=ydeMNRxJ3Y8)

## Forth Day 2009

* [video](https://www.youtube.com/watch?v=1HuRUcz0icM)

## Forth Day 2010

* [video](https://www.youtube.com/watch?v=GYW335T6upo)

## Forth Day 2011

* [video](https://www.youtube.com/watch?v=dSVCuGCB0R4)
* [alt video 1](https://www.youtube.com/watch?v=odBjuSCX8jE)
* [alt video 2](https://www.youtube.com/watch?v=NK1zlz67MjU)

## Forth Day 2012

* [video](https://www.youtube.com/watch?v=bB4pbjgvZoo)
* [slides](forth_day_2012/README.md)

## Programming a 144-computer chip to minimize power (2013)

* Strange Loop Conference 
* [video](https://www.youtube.com/watch?v=0PclgBd6_Zs)

## Forth Day 2013

* [video](https://youtu.be/UkjQLjpyqgs?t=9911)

## Forth Day 2014

* [video](https://youtu.be/NjX9acIN7RA?t=11085)

## Forth Day 2015

* [video](https://youtu.be/_4zZsHmhTPY?t=8714)

## Forth Day 2016

* [video](https://youtu.be/FeZ-40fxY48?t=8458)

## Forth Day 2017

* [video](https://youtu.be/nJ6WBI0Z_s4?t=11091)

## Interview with Chuck Moore 2018

* [video](https://www.youtube.com/watch?v=SX3kXbLmwn4)

## Software -- past and future 2018

* [video](https://www.youtube.com/watch?v=tb0_V7Tc5MU)
* TEDx Talk

## Forth Day 2018

* [video](https://youtu.be/xYWa2C2_7H0?t=7690)

## Chuck Moore - 50 Years of Forth - 2019

* [video](https://www.youtube.com/watch?v=SASQMl0rvYg)

## Forth Day 2019

* [video](https://www.youtube.com/watch?v=3ML-pJFa8lY)

## Chat with Chuck Moore 2020

* [video](https://www.youtube.com/watch?v=dI0soDMg28Q)

## Forth Day 2020

* [video](https://www.youtube.com/watch?v=81bkIqPpe0g)

## Chuck Moore and Dutch FIG 2021

* [video](https://www.youtube.com/watch?v=xoyDNIcnpgc)

## Forth Day 2021

* [video](https://www.youtube.com/watch?v=BpsXyB2WsUw)

## Chat with Chuck Moore 2022

* [video](https://www.youtube.com/watch?v=crMZ5j8XSRQ)

## Forth Day 2022

* [video](https://www.youtube.com/watch?v=YjTDfYAPCbo)

## Chat with Chuck Moore 2023

* [video](https://youtu.be/M14tCZiEPkg?t=11670)

## Forth Day 2023

* [video](https://www.youtube.com/watch?v=3jJkyc-raJQ)
