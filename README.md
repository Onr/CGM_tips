# Tips collected by our lab graduate students


## Youtube Channles / Podcasts

**[[Yannic Kilcher](https://www.youtube.com/c/YannicKilcher/)] [[Machine Learning Street Talk](https://www.youtube.com/channel/UCMLtBahI5DMrt0NPvDSoIRQ)] [[Practical AI](https://changelog.com/practicalai)]**

**[[Two Minute Papers](https://www.youtube.com/user/keeroyz)]**

**[[3 Blue 1 Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw)]**

### Youtube Lecture Sereis 
**[[TUM AI - Guest Lecture Series](https://www.youtube.com/playlist?list=PLQ8Y4kIIbzy8kMlz7cRqz-BjbdyWsfLXt)]**

**[[3DGV Seminar](https://www.youtube.com/channel/UCpCQ8tjahrTPMsBiyPg2H7Q)]**

**[[Deep Unsupervised Learning -- Berkeley Spring 2020](https://youtube.com/playlist?list=PLwRJQ4m4UJjPiJP3691u-qWwPGVKzSlNP)]**

**[[Missing Semester](https://youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)]**


## Twitter

**[[Liu Mingyu](https://twitter.com/liu_mingyu)]** , **[[Google AI](https://twitter.com/GoogleAI)]**, **[[Ayellet Tal](https://twitter.com/Ayellet4)]**, **[[Facebook AI](https://twitter.com/facebookai)]**

## Websites

**[[Papers With Code](https://paperswithcode.com/)]** 

**[[Kaggle](https://www.kaggle.com/)]**

**[[Connected papers](https://www.connectedpapers.com/)]**


## Programs

**[[global-speed-chrom](https://chrome.google.com/webstore/detail/global-speed/jpbjcnkcffbooppibceonlgknpkniiff?authuser=1)]** Watch all videos and audio in the browser at whatever speed you like, using this extension or **[[global-speed-edge](https://microsoftedge.microsoft.com/addons/detail/global-speed/mjhlabbcmjflkpjknnicihkfnmbdfced)]**

# Bugs

* **Free cuda memory** - Occasionally the gpu memory does not get freed, and when using nvidia-smi there is no program using it.
  With this command, you can see what programs use the GPU cache ```sudo fuser -v /dev/nvidia*``` it is most likely that you will need to kill the Python named programs with ```kill -9 PID-of-python-command-name```

## Tips:

Pycharm [ssh_guide](/ssh_cgm_guide.pdf)

Use **[[comet.ml](https://www.comet.ml/)] or [[wandb](https://wandb.ai/site)]**  to track your experiments

Try out virtual environment.
**create** enviroment folder by typing: python<optional: python version, eg: 3.9> -m venv <env_name>
**activate**: source <env_name>/bin/activate.

Try **[[pytorch lightning](https://www.pytorchlightning.ai/)]**

Run mulitiple experiments with **[[test-tube](https://github.com/williamFalcon/test-tube)]** for example

You can connect a python output as a vitual camera using OBS Studio **[[OBS-Studio](https://obsproject.com/)]**

Dance

![dence_dog](/success_dog.gif)
