# decoding stage

What this stage should do is :

> OUT pulses true **iff** we have counted *exactly* 3 pulses of length $\Delta_{pulse}$ in the time $\Delta_{signal}$

We use a signal with the following properties

*  $\Delta_{signal} = 3ms$
*  $\Delta_{pulse} = 0.5ms$

So using $1\mu F$ capacitors we need $R_{signal} = 0.5k\Omega$ and $R_{pulse} = 3k\Omega$ to properly tune the HEF4538 monostable vibrators we use to controll the timing                                                                                   

