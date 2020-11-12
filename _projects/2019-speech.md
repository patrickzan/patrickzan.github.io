---
title: "Speech and Acoustics"
collection: projects
permalink: /projects/2019-speech
venue: "Starkey Labs, Starkey Hearing Technologies"
date: 2019-05-27
location: "Eden Prairie, MN"
---

The human brain processes speech on a routine basis. However, the ability of extracting information from noise or a competing speaker deteriorates as we age. Hearing aids may become a necessity in this case. In the summer of 2019, I joined Starkey Hearing Technologies as an intern, and participated in two projects that could potentially benefit the current or future hearing aid design. One was to test out an DNN-based speech enhancement algorithm implemented in a hearning App which could stream enhanced speech to the hearing aids. The other was more futuristic, that is, to design a beamforming-based speech enhancement system using auditory attention inferred by electroencephalography (EEG) observations. 

* DNN-based Speech Enhancement
<br>
<img src="/projects/p4-se.png" width="400">

I designed and conducted experiments to test out the Mixture of Deep Experts (<a href="https://arxiv.org/pdf/1703.09302.pdf" style="text-decoration: none">MoDE</a>) model, and provided suggestions to modify the algorithm for it to become product. 


* Joint-approach of auditory attention detection and speech enhancement
<img src="/projects/p4-joint.png" width="400">
<br>
This figure shows the structure of the joint appraoch. The auditory attention inferred by EEG is used as input to guide beamformer, as it learns weights to assign to speakers.

Abstract
------
Beamforming is a common technique used to improve speech intelligibility and listening comfort of hearing aids users in a noisy environment. Traditional hearing aids beamforming algorithms require the a priori knowledge of the auditory of the listener, which may not be available in real applications. Recent advances in electroencephalography (EEG) offer a potential non-invasive solution to this problem. The listener's auditory is derived from the EEG signals through auditory decoding algorithms and can be used as an input to the beamforming algorithms. In [1], a joint auditory decoding and adaptive beamforming algorithm framework by correlating the envelope of beamforming output and the EEG signal was proposed to improve the beamformer's robustness against decoding error. Consistent performance improvement was demonstrated on an EEG database recorded on listeners with fixed . In this study, we present the evaluation results of this joint formulation on a new EEG dataset collected on subjects with dynamic switch. We demonstrate not only the joint framework's performance improvement against decoding errors, but also its ability to capture listener's dynamic switch.

Publications
------
<ol>
  <li>Wenqiang Pu, <strong>Peng Zan</strong>, Jinjun Xiao, Tao Zhang, Zhi-Quan Luo. <a href="https://ieeexplore.ieee.org/document/9054592" style="text-decoration: none">Evaluation of Joint Auditory Attention Decoding and Adaptive Binaural Beamforming Approach for Hearing Devices with Attention Switching</a>. <i>IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Barcelona, Spain, pp. 8728-8732, doi: 10.1109/ICASSP40776.2020.9054592, 2020</i>.</li>
</ol>