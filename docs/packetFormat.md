Please be aware these are guesses. I provide no guarantee.

* 0-1 = Signature "01 00"
* 4-5 = Packet Type
 * 01 3c - Data
 * 04 0b - Periodic
* 5-8 = Packet Number
* 9+  = Big ol bitfield (see below)

```
Y                       = 100000
B                       = 200000
X                       = 400000
A                       = 800000
Right low trig          = 010000
Left low trig           = 020000
Right Bumper            = 040000
Left Bumper             = 080000
Select                  = 001000
Steam Button            = 002000
Start                   = 004000
Left Back Trigger       = 008000
????                    = 000100
????                    = 000200
????                    = 000400
????                    = 000800
Right haptic in use     = 000010
Right Back Trigger      = 000001
Left Joystick click     = 000002
Left haptic in use      = 000008
Left trig intensity     = 000000XX
Right trig intensity    = 00000000XX
```
