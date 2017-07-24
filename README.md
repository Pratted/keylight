# keylight
Change the backlit keyboard on a MacBook Pro from the command line

## Instructions
This is a simple wrapper script I'm running on linux. Just place keylight somewhere in $PATH.

## Usage
#### Toggle back light by supplying no command line args:

`$ keylight`

If the back light is off this will turn it on and vice versa. The default intensity level is 200.

#### Or provide an intensity for the back light:

`$ keylight 50`

50 is a dim intensity. Intensity should be between 0 and 500.
