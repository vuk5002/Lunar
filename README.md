
# Lunar 1.0
### Pre Release 10




## Contributing

DM me on discord to get the source code\
Discord: vuledjk


## Authors

- [@Vuk5001](https://github.com/Vuk5001)


## Roadmap

- TODO WHEN RELEASED



## Running Lunar

To run the OS in a Virtual Machine (QEMU) use these params

```bash
  {qemu-version} -net nic,model=pcnet -drive file=CustomOS.img -m 256M -machine q35 -cpu max -drive if=pflash,format=raw,unit=0,file=CODE.fd,readonly=on -drive if=pflash,format=raw,unit=1,file=VARS.fd -display sdl
```

To run it on real hardware, its a bit harder, I recommend using RUFUS and make a bootable USB\
Keep in mind your test machine NEEDS to support (U)EFI Boot!

For VBox, VMWare, these do not work (for now).
     

![Static Badge](https://img.shields.io/badge/Latest%20Build:-PASS-green)

