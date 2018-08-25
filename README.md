# nv 304.137 patch

NVIDIA 304.137 driver patch for linux kernel 4.15.x.


## Install on Ubuntu Linux 18.04.1

    sh ./NVIDIA-Linux-x86_64-304.137.run -x
    cd ./NVIDIA-Linux-x86_64-304.137
    git clone 'https://github.com/chmyaf/nv-304.137-patch.git'
    patch -p0 < nv-304.137-patch/linux-4.15.patch
    ./nvidia-installer
