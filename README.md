# 6to14DecoderLogisim
A circuit that takes a 6-bit input and outputs 14 signals to control two 7-segment displays

# How To Use
Import `6to14Decoder.circ` into your Logisim circuit. You can do this via `Project>Load Library>Logisim Library...`). 

Your sidebar should now look similar to this:  ![screenshot of logisim](https://raw.githubusercontent.com/hodgeswt/6to14DecoderLogisim/master/Photos/Screen%20Shot%202016-08-22%20at%202.33.05%20PM.png)

Drag a 6to14Decoder instance into your circuit. The inputs are the blue dots labeled A-F, and the outputs are the red dots labelled A-G and A1-G1. The inputs A-F are a binary number, where F is the least significant bit and A is the most significant bit.The outputs A-G are the inputs for the leftmost 7 Segment Display. The names correspond to conventional pin names for the 7 seg display. A1-G1 are for the rightmost 7 Seg Display. 

Conventional Pin Names: 

![conventional pin names diagram](https://qph.ec.quoracdn.net/main-qimg-07bec404d36e7d3812d8c3db69c23739?convert_to_webp=true) 

Example Images:

![6 displayed](https://raw.githubusercontent.com/hodgeswt/6to14DecoderLogisim/master/Photos/Screen%20Shot%202016-08-22%20at%202.43.36%20PM.png)

![22 displayed](https://raw.githubusercontent.com/hodgeswt/6to14DecoderLogisim/master/Photos/Screen%20Shot%202016-08-22%20at%202.44.34%20PM.png)
