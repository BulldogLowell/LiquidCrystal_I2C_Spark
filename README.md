# LiquidCrystal_I2C
LiquidCrystal_I2C library for Spark Core

I had a lot of difficulty getting the I2C library:

https://gist.github.com/anonymous/dc7ecc5e6574105b4fbd


for Spark Core working without corrupting the display...


I modified the library, adding a few delays following the writes and it works for me, now.
