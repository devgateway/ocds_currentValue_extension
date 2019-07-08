# Current Value

We need a local extension for Direccion Nacional de Vialidad Argentina (DNV) to adjust values to current date due to inflation:

* Current Value

This extension will allow DNV to show more precise information about the different values of the contracting implementation.

## Worked example
The "currentValue" extension will be a field that could be added in several places to show the updated value, the coefficient used to calculate it and the currency.

```json
{
	"currentValue" : {
		"amount" : 434418021.61,
		"coefficient" : 2.20,
		"currency" : "ARS"
	}
}

```
