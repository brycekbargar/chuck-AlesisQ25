# Alesis Q25 #
A component for the [chuck-flux-synth](https://www.npmjs.com/package/chuck-flux-synth) based on the dirt-cheap [Alesis Q25 Keyboard](http://alesis.com/products/legacy/q25).

### Usage ###
```ChucK
AlesisQ25 input;
spork ~ input.Start();

// Wait for end of input
InputBase.Closed => now;
```
