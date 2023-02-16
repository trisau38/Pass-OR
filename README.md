# Pass-OR
Pass transistor is used to reduce the number of transistors to implement an OR gate. In this
circuit, if the B input is high the right NMOS is turned ON and copies logic 1 to F and this
operation does not get affected by ’A’ input. When B is low the left NMOS is turned ON the
logic of ’A’ is copied to the output o/p.
Boolean expression: Y = A+B

## Circuit Diagram:
![pass_or_cir](https://user-images.githubusercontent.com/108890713/219370455-1602976c-a6cd-4c32-9b71-f909ccf13377.jpeg)

## Euler's Path:
Since Euler’s path is defined for complementry mosfet gates, so we cannot find the Euler’s
path for pass transistor logic.

## Stick Diagram:
Stick Diagram is constructed from the knowledge of traversal of Euler’s path. Since Euler’s
path is not defined for the pass transistor logic, so we cannot design its stick diagram.

## Magic Layout:
![pass_or_mag](https://user-images.githubusercontent.com/108890713/219370852-3b48fba5-bbec-41e2-8326-795308150af5.png)

## AC Analysis Output:
![pass_or_out](https://user-images.githubusercontent.com/108890713/219371004-37011509-9a87-4d64-a559-a23bfe45fc7f.png)

## Calculations:
rise time = 3.0ns
fall time = 1.4ns
Here, rise time comes out to be nearly the double of the fall time.

## Observation:
It is observed that the output is OR of the two inputs and the rise time obtained is almost the
double of the fall time. This happens because of the delay of inverter also gets added during
the rise time. Also, we observe that the output obtained has lower voltage than the input
voltage. The reason is because the threshold voltage gets subtracted from the input.
