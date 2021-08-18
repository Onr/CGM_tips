# Tips collected by our lab graduate students


## Youtube Channles 

**[[Yannic Kilcher](https://www.youtube.com/c/YannicKilcher/)] [[Machine Learning Street Talk](https://www.youtube.com/channel/UCMLtBahI5DMrt0NPvDSoIRQ)]**

**[[Two Minute Papers](https://www.youtube.com/user/keeroyz)]**

## Twitter

**[[Liu Mingyu](https://twitter.com/liu_mingyu)]**

## Websites

**[[Papers With Code](https://paperswithcode.com/)]**

**[[Kaggle](https://www.kaggle.com/)]**

**[[Connected papers](https://www.connectedpapers.com/)]**


## Programs

**[[global-speed-chrom](https://chrome.google.com/webstore/detail/global-speed/jpbjcnkcffbooppibceonlgknpkniiff?authuser=1)]** Watch all videos and audio in the browser at whatever speed you like, using this extension or **[[global-speed-edge](https://microsoftedge.microsoft.com/addons/detail/global-speed/mjhlabbcmjflkpjknnicihkfnmbdfced)]**

# Bugs

* **Free cuda memory** - Occasionally the gpu memory does not get freed, and when using nvidia-smi there is no program using it.
  With this command, you can see what programs use the GPU cache ```sudo fuser -v /dev/nvidia``` it is most likely that you will need to kill the Python named programs with ```kill -9 PID-of-python-command-name```

## Tips:

Use **[[comet.ml](https://www.comet.ml/)]**  to track your experiments

Try **[[pytorch lightning](https://www.pytorchlightning.ai/)]**

Run mulitiple experiments with **[[test-tube](https://github.com/williamFalcon/test-tube)]** for example

You can connect a python output as a vitual camera using OBS Studio **[[OBS-Studio](https://obsproject.com/)]**

dance

![dence_dog](/success_dog.gif)
