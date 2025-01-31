## FixedPoint64

Implements fixed point numbers in Move language using the Q number format.

Use u128 as underlying data storage. High 64 bits for integer part, Low 64 bits for fractional part.

Similar one used in [Uniswap](https://github.com/Uniswap/v2-core/blob/master/contracts/libraries/UQ112x112.sol) v2 core.
