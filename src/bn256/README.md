# BN256

This is an implementation of the BN256 pairing-friendly elliptic curve construction.

## BN256 Parameterization

Follows go-ethereum parametrization.

## Notes

- I couldn't find an easy wat of getting rand G2 for BN256 curve (also have no idea why just scaling by cofactor works for BLS12), so don't use it. Make rand scalar and multiply by generator.
- For this reason tests had to be copied and modified for some cases.


