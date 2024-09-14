# Motor Math - Voron Trident

RSENSE = 110Ohm

## X + Y Motors

### Specs

Holding Torque: 45 Ncm (63.7 oz in)
Step Angle: 1.8 deg
Rated current: 2A
Resistance: 1.1 Ohm
Inductance: 2.6 mH

### Math

Max Current (RMS): 2A * 0.707 = 1.414
Rounded: 1.4 A
Run Current: 1.4 * 0.7 = 0.9 A

VREF = I * 8 * Rsense
VREF = (2 * 0.9) * 8 * 0.11 = 1.584

## Z Motors (Old)

### Specs

Holding Torque: 400 mNm
Step Angle: 1.8 deg
Rated current: 1.2A
Resistance: 2.2 Ohm

### Math

Max Current (RMS): 1.2A * 0.707 = 0.848
Rounded: 0.8 A
Run Current: 0.8 * 0.7 = 0.5 A

VREF = (1.2 * 0.9) * 8 * 0.11 = 0.95

## Z Motors (New)

Holding Torque: 400 mNm
Step Angle: 1.8 deg
Rated current: 1.5A

### Math

Max Current (RMS): 1.5A * 0.707 = 1.0605
Rounded: 1.0 A
Run Current: 1.0 * 0.7 = 0.7 A

VREF = (1.5 * 0.9) * 8 * 0.11 = 1.188

Home spot: X: 168, Y: 295