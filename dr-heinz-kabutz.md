[GitHub Profile](https://github.com/kabutz)

### Thread Safety with Phaser, StampedLock and VarHandle

Every major Java version introduces a new and better way of managing state.  Java 7 gave us Phaser as a replacement for CountDownLatch and CyclicBarrier.  Hardly any programmers know how it works, even though we are now on Java 11.  Java 8 gave us StampedLock, useful as a lighter read "lock" when building concurrent classes.  Again, not very widely known, but lots of use cases.  Java 9/10/11 introduced VarHandle as an escape latch for the Unsafe addicts.  In this talk we will show all three concepts and explain when each should be used. 
