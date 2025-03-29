# arch_install

To be run in `archiso`. `arch_install` takes one argument, the device name of the disk on which to install Arch (danger!).

e.g.

```
pacman -Sy git
git clone https://github.com/reentim/arch-install.git
```

If you're not me, definitely don't install my keys:

```
PUBLIC_KEYS_URL="https://example.com/your-own-keys" ./arch-install/arch_install /dev/sda
```
