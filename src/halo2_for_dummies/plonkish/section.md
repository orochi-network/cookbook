# PLONKish Arithemetization
We recommend readers who are not familiar with PlonK's arithmetization to read the article [PlonK's Arithmetization](./../../plonk/arithmetization/section.md). In this chapter, we further discuss a more customized version of PlonK's arithmetization, namely, [PLONKish arithmetization](https://zcash.github.io/halo2/). Customization aims to handle more general gates with more complicated structures rather than employing only multiplication, addition, multiplication with constants and addition with constants gates. 

PLONKish arithmetization can be pictured as a table of the following types of columns:
- Constant columns for putting constants,
- Instant columns for putting public inputs,
- Advice columns for putting private inputs, literally known as witnesses,
- Selector columns for putting selectors.

For simplicity, in this section, we present a transformation from a program, represented by an arithmetic circuit to the form of PLONKish arithmetization. <span style="color:red">continue here</span>