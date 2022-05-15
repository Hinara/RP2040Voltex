# RP2040Voltex

Work in progress !! The PCB nor the schematics have been tested for now !! It is just a proof of concept !

It is a mini controller for games such as Sound Voltex, and clones.

This model is based on [Pocket-SDVX-Pico](https://github.com/speedypotato/Pocket-SDVX-Pico-v4)
The Lower PCB should be compatible [Pocket-SDVX-Pico](https://github.com/speedypotato/Pocket-SDVX-Pico-v4)

It's main difference is using directly a RP2040 processor to be able to meet the height constraints on the upper face. This was designed like that to prevent ripping of some Pico's component while putting the Pocket SDVX Pico in a bag without a case.

## Firmware

For now the firmware as not been updated to math the RP2040 pin layout, but you should be able to have a working firmware by compiling the [Pocket-SDVX-Pico](https://github.com/speedypotato/Pico-Game-Controller) firmware and change the pin layout.

## License

As it is derived work from [Pocket-SDVX-Pico](https://github.com/speedypotato/Pocket-SDVX-Pico-v4) it inherits the same [license](https://github.com/speedypotato/Pocket-SDVX-Pico-v4/blob/main/LICENSE).