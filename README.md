# CARA-UPDATE-CCMINER-2024

1. Uninstall dulu ccminer versi lawasnya, ketik : rm -r ccminer
2. Buka github ccminernya https://github.com/monkins1010/ccminer/releases/tag/v3.8.3a
3. sudo apt-get install libcurl4-openssl-dev libssl-dev libjansson-dev automake autotools-dev build-essential
4. git clone --single-branch -b ARM https://github.com/monkins1010/ccminer.git
5. Setelah berhasil terdownload, bisa di cek ketik ls, maka akan terlihat folder ccminer berwarna biru.
6. Selanjutnya ketik cd ccminer, untuk masuk ke dalam folder ccminernya.
7. chmod +x build.sh
8. chmod +x configure.sh
9. chmod +x autogen.sh
10. ./build.sh
