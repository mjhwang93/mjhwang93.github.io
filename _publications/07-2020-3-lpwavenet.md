---
title: "LP-WaveNet: Linear Prediction-based WaveNet Speech Synthesis"
collection: publications
permalink: /publication/2020/12/07-2020-3-lpwavenet
authors: **<U>Min-Jae Hwang</U>**, Frank Soong, Eunwoo Song, Xi Wang, Hyeonjoo Kang, Hong-Goo Kang
date: 2020/12/07
venue: 'APSIPA ASC 2020'
paperurl: 'https://arxiv.org/abs/1811.11913'
---
We propose a linear prediction (LP)-based waveform generation method via WaveNet vocoding framework. A WaveNet-based neural vocoder has significantly improved the quality of parametric text-to-speech (TTS) systems. However, it is challenging to effectively train the neural vocoder when the target database contains massive amount of acoustical information such as prosody, style or expressiveness. As a solution, the approaches that only generate the vocal source component by a neural vocoder have been proposed. However, they tend to generate synthetic noise because the vocal source component is independently handled without considering the entire speech production process; where it is inevitable to come up with a mismatch between vocal source and vocal tract filter. To address this problem, we propose an LP-WaveNet vocoder, where the complicated interactions between vocal source and vocal tract components are jointly trained within a mixture density network-based WaveNet model. The experimental results verify that the proposed system outperforms the conventional WaveNet vocoders both objectively and subjectively. In particular, the proposed method achieves 4.47 MOS within the TTS framework.