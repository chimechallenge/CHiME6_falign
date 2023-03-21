# CHiME-6 Forced Alignment Annotation for CHiME-7 DASR Challenge


## [CHiME-7 DASR Challenge](https://www.chimechallenge.org/current/task1/index) 
### Distant Automatic Speech Transcription with Multiple Devices in Diverse Scenarios

[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/chimechallenge.svg?style=social&label=Follow%20%40chimechallenge)](https://twitter.com/chimechallenge)
[![Slack][slack-badge]][slack-invite]


Baseline and dataset generation are in [ESPNet2 chime7_dasr recipe](https://github.com/espnet/espnet/tree/master/egs2/chime7_task1/asr1)

---
This repository contains forced alignment segmentation for the CHiME-6 dataset, 
produced as in https://github.com/nateanl/chime6_rttm (details are in the CHiME-6 challenge description paper [1]).

**Important** <br>
Here we extend the forced alignment annotation also for the training set, and provide it also in the form of 
JSON files (along with .rttm).

We also provide a script for re-segmenting the CHiME-7 DASR annotation using this new
segmentation. 

[1] Watanabe, S., Mandel, M., Barker, J., Vincent, E., Arora, A., Chang, X., et al. CHiME-6 challenge: Tackling multispeaker speech recognition for unsegmented recordings. <https://arxiv.org/abs/2004.09249> <br>

[slack-badge]: https://img.shields.io/badge/slack-chat-green.svg?logo=slack
[slack-invite]: https://join.slack.com/t/chime-fey5388/shared_invite/zt-1oha0gedv-JEUr1mSztR7~iK9AxM4HOA
[twitter]: https://twitter.com/chimechallenge<h2>References</h2>


