# feather-power-wing
a wing to turn on and off a feather board with a signal voltage

This is useful for battery powered applications where you don't wanna waste your mAh on sleep mode or voltage regulators or what have you.

The battery is connected to the VIN and GND pins, and if a voltage applied to the VON pin for a period of time set by R7 (up to 1.5 sec with given values of C1 and R7) then the feather will turn on.

If pin 12 on the feather goes high, the feather will turn itself off. The onboard regulator works with supply voltages up to 15V.
