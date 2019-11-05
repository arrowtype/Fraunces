Fraunces goofy and opsz axis explorations:

Here are the formulas used to generate OpMax GoofyMax (i.e., low contrast) and OpMin GoofyMin (i.e., high contrast) masters with ScaleAndInterpolate.py in ~/documentation/scripts/. Please note that the functionality in that script that allows you to drop in a UFO and see how it was generated might not work at the moment because we re-arranged the designspace, which involved swapping masters.

## ROMAN ##

# Black OpMax GoofyMax = Light OpMin GoofyMax + Black OpMin GoofyMax

Caps
Scale Horizontal: 93
Scale Vertical: 100
Interpolate Horizontal: 100
Interpolate Vertical: 95
Units of Tracking: -30

Lowercase
Scale Horizontal: 85
Scale Vertical: 92
Interpolate Horizontal: 106
Interpolate Vertical: 103
Units of Tracking: -20

# Light OpMax GoofyMax = Light OpMin GoofyMax + Black OpMin GoofyMax

Caps
Scale Horizontal: 93
Scale Vertical: 100
Interpolate Horizontal: -2
Interpolate Vertical: -4
Units of Tracking: -40

Lowercase
Scale Horizontal: 85
Scale Vertical: 92
Interpolate Horizontal: 2
Interpolate Vertical: 0
Units of Tracking: -30

# Black OpMin GoofyMin = Black OpMax + Black OpMin GoofyMax

Caps
Scale Horizontal: 100
Scale Vertical: 100
Interpolate Horizontal: 50
Interpolate Vertical: 50
Units of Tracking: 0

Lowercase
Scale Horizontal: 103.6 _(based on height of /x)_
Scale Vertical: 103.6 _(based on height of /x)_
Interpolate Horizontal: 50
Interpolate Vertical: 50
Units of Tracking: 0

# Light OpMin GoofyMin = Light OpMax + Light OpMin GoofyMax

Caps
Scale Horizontal: 100
Scale Vertical: 100
Interpolate Horizontal: 70
Interpolate Vertical: 70
Units of Tracking: 0

Lowercase
Scale Horizontal: 102.5 _(based on height of /x)_
Scale Vertical: 102.5 _(based on height of /x)_
Interpolate Horizontal: 70
Interpolate Vertical: 70
Units of Tracking: 0


## Italic ##

# Black OpMax GoofyMax = Light OpMin GoofyMax + Black OpMin GoofyMax

Caps
Scale Horizontal: 93
Scale Vertical: 100
Interpolate Horizontal: 100
Interpolate Vertical: 95
Units of Tracking: -30

Lowercase
Scale Horizontal: 85
Scale Vertical: 92
Interpolate Horizontal: 110
Interpolate Vertical: 103
Units of Tracking: -20

Skew: 2°

# Light OpMax GoofyMax = Light OpMin GoofyMax + Black OpMin GoofyMax

Caps
Scale Horizontal: 93
Scale Vertical: 100
Interpolate Horizontal: -2
Interpolate Vertical: -4
Units of Tracking: -40

Lowercase
Scale Horizontal: 85
Scale Vertical: 92
Interpolate Horizontal: 2
Interpolate Vertical: 0
Units of Tracking: -30

Skew: 2°

# Black OpMin GoofyMin = Black OpMax + Black OpMin GoofyMax

Caps
Scale Horizontal: 100
Scale Vertical: 100
Interpolate Horizontal: 50
Interpolate Vertical: 50
Units of Tracking: 0

Lowercase
Scale Horizontal: 103.6 _(based on height of roman /x)_
Scale Vertical: 103.6 _(based on height of roman /x)_
Interpolate Horizontal: 50
Interpolate Vertical: 50
Units of Tracking: 0

Skew: 0°

# Light OpMin GoofyMin = Light OpMax + Light OpMin GoofyMax

Caps
Scale Horizontal: 100
Scale Vertical: 100
Interpolate Horizontal: 70
Interpolate Vertical: 70
Units of Tracking: 0

Lowercase
Scale Horizontal: 102.5 _(based on height of roman /x)_
Scale Vertical: 102.5 _(based on height of roman /x)_
Interpolate Horizontal: 70
Interpolate Vertical: 70
Units of Tracking: 0

Skew: 0°