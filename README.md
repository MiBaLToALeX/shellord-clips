# ShellOrd Clips

shellordclips.exe file2clipboard.txt

Paste the content into: https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true)Gunzip()

Magic!

## Build

### Linux 

On Linux you need the x11 library, install it with something like:
```bash
sudo apt-get install xorg-dev
cargo build --release
```

### Windows

```powershell
cargo build --release
```

