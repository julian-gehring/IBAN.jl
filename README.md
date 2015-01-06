# IBAN

[![Build Status](https://travis-ci.org/julian-gehring/IBAN.jl.svg?branch=master)](https://travis-ci.org/julian-gehring/IBAN.jl)

## Usage

```julia
using IBAN

## correct IBAN
test_iban1 = "GB82 WEST 1234 5698 7654 32"
## incorrect IBAN
test_wban4 = "GEXX WEST 1234 5698 7654 32"

is_valid_iban(test_iban1)
is_valid_iban(test_iban4)

split_iban(test_iban1)
```

## References

http://en.wikipedia.org/wiki/International_Bank_Account_Number
