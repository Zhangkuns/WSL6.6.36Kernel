### How to use
- cd WSL2-Linux-Kernel
- download config-wsl-full
- make -j$(nproc) KCONFIG_CONFIG=config-wsl-full
- sudo make modules_install headers_install
- Finished!
