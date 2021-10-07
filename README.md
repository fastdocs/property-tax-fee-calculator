# property-tax-fee-calculator

Open Source calculator for property tax fees based on Steuerberatervergütungsverordnung

## Usage

The `calculateFee()` function expexts to variables `averagePropertyValue` and `amountOfDeclarations`.It returns an object with three different values. A maximum fee, a minimum fee and a avarage fee.

### Example

`calculateFee(10000, 1)`

This will return 40,30 € as the minimum fee, 382,85 € as the avarage fee and 725,40 € as the maximum fee.`

_Take a look at the `example.html` file in the `dist` folder._
