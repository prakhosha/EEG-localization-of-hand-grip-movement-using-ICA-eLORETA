---
layout: post
title: EEG localization of hand grip movement using ICA-eLORETA
permalink: /
---

This project is my undergraduate thesis with a full title:

"Studi Pencitraan 3D Broadmann Area Berbasis Sinyal EEG untuk Aktivitas Tangan Menggenggam dengan Metode ICA-eLORETA"

or if translated to english:

"Study on 3D Imaging of Broadmann Area for Hand Gripping Activity Based on EEG Signal using ICA-eLORETA"

The full work can be found [here](https://github.com/prakhosha/EEG-localization-of-hand-grip-movement-using-ICA-eLORETA/blob/main/Laporan%20Tugas%20Akhir.pdf)

The work is done in Bahasa Indonesia. However, there is an english translation of the abstract which can be read below:

## Abstract

Stroke rehabilitation is a method that can be taken by stroke patients to restore their motoric ability. During stroke rehabilitation, direct feedback from the patient’s brain is needed to know how the patient recovered over time. To obtain direct feedback from the patient’s brain, some measurement instruments can be used.

Some examples of those instruments are electroencephalogram (EEG), functional Magnetic Resonance Imaging (fMRI), Magnetoencephalogram (MEG), etc. In many of those instruments, EEG has the potential in a manner of mobility and affordability to measure brain activity. However, the main drawback of EEG is that it can only measure brain activity until a certain level of thickness from the surface. So, a method to localize brain activity is needed to improve stroke rehabilitation.

ICA-eLORETA is a method to map brain activity in 3D format. ICA is an algorithm that can be used to obtain the most independent component of a measured signal. eLORETA is an algorithm to localize brain activity based on the volume conduction effect.

In this final project, ICA-eLORETA is used to localize hand grip movement EEG activity of a normal person. The subject was told to do certain hand grip movement alternately between his right hand and left hand. In every session, there are five right-hand movements and five left-hand movements. After the signal is obtained, we then preprocessed the signal using several techniques such as segementing, filtering, re-
referencing, and applying principal component analysis . ICA is then applied to the signal to obtain several independent components that made up the measured signal. Among those independent components, we choose certain components that have the potential to be a hand-grip movement activity. Lastly, we performed eLORETA to acquire EEG 3D mapping.

The result of ICA-eLORETA is a current density mapping which we then compared it to the baseline signal. ICA-eLORETA was shown successfully localize hand-grip movement according to the Wilcoxon signed-rank test.
