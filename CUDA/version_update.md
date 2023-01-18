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

In case of depencency issues, try these:
https://askubuntu.com/questions/940582/upgrade-or-uninstall-cuda-to-allow-apt-get-to-work
https://askubuntu.com/questions/1152357/uninstall-broken-cuda-installation


## Install the new version:

Go to:

https://developer.nvidia.com/cuda-downloads

Choose a configuration & follow the instructions.

This video can also be useful: https://www.youtube.com/watch?v=4LuHiMvBMGY
