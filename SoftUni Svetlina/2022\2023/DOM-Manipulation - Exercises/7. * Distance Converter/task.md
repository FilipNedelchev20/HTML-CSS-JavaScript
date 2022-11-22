Your task is to convert from one distance unit to another by adding a click event listener to a button.
When it is clicked, read the value in the input field, get the selected option from the input and output units
drop downs and calculate and display the converted value in the disabled output field.
Multiply the incoming distance by the following conversion rates to convert to meters. Divide to convert
from meters to the required output unit.
1 km = 1000 m
1 m = 1 m
1 cm = 0.01 m
1 mm = 0.001 m
1 mi = 1609.34 m
1 yrd = 0.9144 m
1 ft = 0.3048 m
1 in = 0.0254 m

Hint:
To see which option is selected, read the properties of its parent: value gives you the value of the
selected option (as displayed in the HTML), selectedIndex gives you the 0‐based index of the selected
option. E.g. if miles are selected, #inputUnits.value is "mi", #inputUnits.selectedIndex is 4.
Option text is irrelevant.
