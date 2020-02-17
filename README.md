# SuccOS
 A hobby Operating System developed from scratch using i8086 assembly.

## Documentation 
Please see [`Function Index`](https://github.com/Joshua-Riek/SuccOS/wiki/Function-Index) for some work in progress documentation.

## Building source
Using both Nasm & GCC Cross-Compiler:
```sh
make
```

Using only Nasm:
```sh
nasm -f bin src/kernel.asm -o obj/kernel.bin
```

## Release History
For a full list of changes and updates please see `changelog.org`.

## License
Distributed under the GNU General Public License. See `LICENSE` for more information.

## Acknowledgements
* [GCC Cross-Compiler]
* [imdisk]
* [OSDev]
* [Nasm]
* [QEMU]


[NASM]:   http://www.nasm.us/index.php
[GCC Cross-Compiler]: https://wiki.osdev.org/GCC_Cross-Compiler

[QEMU]:   http://www.qemu.org/
[imdisk]: http://www.ltr-data.se/opencode.html/
[OSDev]:  http://wiki.osdev.org/Main_Page
