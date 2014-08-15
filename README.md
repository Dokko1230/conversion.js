[[![MIT License][license-image]][license-url]]

A lightweight javascript conversion library for translating temperature, speed, mass and length values.

Note: The numbers are rounded up to the nearest 4th decimal point

## Usage
```js
convert(1, 'mps').toKph();
convert(2, 'kilograms').toMetricTons()
convert(2, 'yards').toCentimeters()
```
## Api

```js
// Temperature
.toCelsius
.toFahrenheit
.toKelvin

// Length
.toKilometers
.toMeters
.toCentimeters
.toMillimeters
.toMiles
.toYards
.toInches
.toFeet
.toNauticalMiles

// Mass
.toMetricTons
.toKilograms
.toGrams
.toMilligrams
.toMcgs
.toLongTons
.toShortTons
.toStones
.toPounds
.toOunces

// Speed
.toMph // Miles per hour
.toFps // Feet per second
.toMps // Meters per second
.toKph // To kilometers per hour
.toKnot // To Knot

```

## License

Conversion.js is freely distributable under the terms of the [MIT license](LICENSE).

[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE
