# ClockDivider_PLL
A frequency divider can be constructed by cascading flip-flops, effectively creating an asynchronous binary counter. This circuit is essential in PLLs used for frequency synthesis. By utilizing cascaded flip-flops, it forms an asynchronous binary counter, where the high-frequency output from the DCO is fed as input. The resulting lower frequency is directed to one input of the PFD, with the divider ratio N determining the output frequency. The configuration allows adaptation to a programmable frequency divider.


![ClockDivider](ClockDivider.png)

![CLKDivider](CLKDivider.png)
