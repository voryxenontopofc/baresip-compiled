# baresip-compiled (Windows x64)

pre-compiled `baresip.exe` for 64-bit windows with TLS/OpenSSL support.

built automatically from source using github actions so you don't have to deal with msys2/compiling.

### how to get it
1. go to the **Releases** tab.
2. click the **Baresip v4.11.0** release.
3. scroll down to **Assets** and download `baresip-windows-x64.zip`.
4. extract the `.exe` and the `.dll` files into your project folder.

### workflow
the build script is located in `code.yml` (made with ai).

### credits / upstream
original repo and docs: https://github.com/baresip/baresip

### i get smartscreen warning, is this a virus?
no. smartscreen is telling you that the .exe is a virus because the .exe is not digitally signed. as i said, you can inspect the code.yml file to see that it uses the official baresip repo to compile the file.
