## property-tax-fee-calculator

Open Source calculator for property tax fees based on [Steuerberatervergütungsverordnung](https://www.gesetze-im-internet.de/stbgebv/BJNR014420981.html).

### Usage

The `calculateFee()` function expects to variables `averagePropertyValue` and `amountOfDeclarations`. The Result returns an object with three different values. A maximum fee, a minimum fee and an avarage fee.

#### Example

```js
calculateFee(10000, 1).minFee; // returns '40,30 €'
calculateFee(10000, 1).averageFee; // returns '382,85 €'
calculateFee(10000, 1).maxFee; // returns '725,40 €'
```

_Take a look at the `index.html` file in the `dist` folder or check https://fastdocs.github.io/property-tax-fee-calculator._
