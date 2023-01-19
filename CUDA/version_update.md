## Uninstall previous versions:

To remove CUDA Toolkit:
```
sudo apt-get --purge remove "*cublas*" "*cufft*" "*curand*" "*cusolver*" "*cusparse*" "*npp*" "*nvjpeg*" "cuda*" "nsight*"
```

To remove NVIDIA Drivers:
```
sudo apt-get --purge remove "*nvidia*"
```

To clean up the uninstall:
```
sudo apt-get autoremove
```

In case of depencency issues, try these useful threads:
1. https://askubuntu.com/questions/940582/upgrade-or-uninstall-cuda-to-allow-apt-get-to-work
2. https://askubuntu.com/questions/1152357/uninstall-broken-cuda-installation


## Install the new version:

Go to:

https://developer.nvidia.com/cuda-downloads
(note that it links to the most updated cuda vesrion)

Choose a configuration & follow the instructions.

This video can also be useful: https://www.youtube.com/watch?v=4LuHiMvBMGY

## Add nvcc to path

```
vim ~/.bashrc
```

Add the line:

```
export PATH="/usr/local/cuda-XX.X/bin:$PATH"
```

change XX.X according to the installed version.
