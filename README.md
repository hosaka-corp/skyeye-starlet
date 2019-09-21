# skyeye-starlet

See [the original readme](SKYEYE_README) for more information.

## Configuration
Emulating some IOS on Starlet requires the following:

- A dump of your NAND; the default `skyeye.conf` looks for `./nand.bin`
- A dump of your SEEPROM and OTP memory (`./seeprom.bin` and `./otp.bin`)
- A dump of the boot ROM (`./boot0.bin`)

PPC IPC is exposed over `/tmp/starlet.sock`.
