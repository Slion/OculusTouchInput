# Oculus Touch Input

We hope to find the time to develop this project into something that will allow use of Oculus Touch controllers to emulate mouse, keyboard and gamepad.
We have a prototype implemented in [Slion/SharpLibHid](https://github.com/) using raw HID.
However as we would like to use the Touch controllers [IMU](https://en.wikipedia.org/wiki/Inertial_measurement_unit), for air mouse, and vibrator capabilities we figure it would be easier to use the Oculus SDK rather than reverse engineer the raw HID protocol.

# Gamepad emulation

See [ViGEm](https://github.com/ViGEm/ViGEmClient).
Their Discord channel is very helpful.

# Keyboard emulation

[InputSimulatorStandard](https://github.com/GregsStack/InputSimulatorStandard) worked well for our raw HID demo.

# Mouse emulation

I think [InputSimulatorStandard](https://github.com/GregsStack/InputSimulatorStandard) does that too.
