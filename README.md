# Tips collected by our lab graduate students


## Youtube Channles / Podcasts

**[Yannic Kilcher](https://www.youtube.com/c/YannicKilcher/)**

**[Machine Learning Street Talk](https://www.youtube.com/channel/UCMLtBahI5DMrt0NPvDSoIRQ)**

**[Practical AI](https://changelog.com/practicalai)**

**[Two Minute Papers](https://www.youtube.com/user/keeroyz)**

**[3 Blue 1 Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw)**

**[Talking Papers](https://talking.papers.podcast.itzikbs.com/)**

**[Medallion Data Science](https://www.youtube.com/channel/UCxladMszXan-jfgzyeIMyvw)**

**[DevOps Toolbox](https://www.youtube.com/@devopstoolbox)**

### Youtube Lecture Sereis 

**[TUM AI - Guest Lecture Series](https://www.youtube.com/playlist?list=PLQ8Y4kIIbzy8kMlz7cRqz-BjbdyWsfLXt)**

**[3DGV Seminar](https://www.youtube.com/channel/UCpCQ8tjahrTPMsBiyPg2H7Q)**

**[Deep Unsupervised Learning -- Berkeley Spring 2020](https://youtube.com/playlist?list=PLwRJQ4m4UJjPiJP3691u-qWwPGVKzSlNP)**

**[Missing Semester](https://youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)**

**[LaTeX tutorial](https://youtu.be/Jp0lPj2-DQA)**



### Blogs

**[Tuning Playbook](https://github.com/google-research/tuning_playbook)**


## Twitter

**[Liu Mingyu](https://twitter.com/liu_mingyu)** 

**[Google AI](https://twitter.com/GoogleAI)**

**[Ayellet Tal](https://twitter.com/Ayellet4)**

**[Facebook AI](https://twitter.com/facebookai)**

**[Yizhak Ben-Shabat](https://twitter.com/sitzikbs)**

**[Talking Papers](https://twitter.com/talking_papers)**


## Websites

**[Papers With Code](https://paperswithcode.com/)** 

**[Kaggle](https://www.kaggle.com/)**

**[Connected papers](https://www.connectedpapers.com/)**


## Programs

**[global-speed-chrom](https://chrome.google.com/webstore/detail/global-speed/jpbjcnkcffbooppibceonlgknpkniiff?authuser=1)** Watch all videos and audio in the browser at whatever speed you like, using this extension or **[global-speed-edge](https://microsoftedge.microsoft.com/addons/detail/global-speed/mjhlabbcmjflkpjknnicihkfnmbdfced)**

## Server

[**Wiki**](https://github.com/Onr/CGM_tips/wiki)

Pycharm **[ssh_guide](/ssh_cgm_guide.pdf)**

Fuzzy Finder [fzf](https://github.com/junegunn/fzf)

Better cd [z](https://github.com/ajeetdsouza/zoxide)

# Bugs
* **Slow Pycharm** - PyCharm can sometimes become slow or unresponsive due to its indexing process. To prevent this, you can right-click on a folder, such as logs, that doesn't need to be indexed and mark it as excluded.
```right-click -> mark directory as -> excluded```
* **Free cuda memory** - Occasionally the gpu memory does not get freed, and when using nvidia-smi there is no program using it.
  With this command, you can see what programs use the GPU cache ```sudo fuser -v /dev/nvidia*``` it is most likely that you will need to kill the Python named programs with ```kill -9 PID-of-python-command-name```

## Tips:


Use **[comet.ml](https://www.comet.ml/) or [wandb](https://wandb.ai/site)**  to track your experiments

Try out virtual environment.\
**create** enviroment folder by typing: 
```python<optional: python version, eg: python3.9> -m venv <env_name>```\
**activate**: 
```source <env_name>/bin/activate```.

Try **[pytorch lightning](https://www.pytorchlightning.ai/)**

Run mulitiple experiments with **[test-tube](https://github.com/williamFalcon/test-tube)** or **[wandb sweep](https://docs.wandb.ai/guides/sweeps)**

You can connect a python output as a vitual camera using OBS Studio **[OBS-Studio](https://obsproject.com/)**

You can convert Panda DataFrame to latex **[DataFrame_to_Latex](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_latex.html)**

Dance

![dence_dog](/success_dog.gif)
