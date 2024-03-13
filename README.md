# AnKaS

The official repository for "AnKaS", [INTERSPEECH 2024](https://interspeech2024.org/) (submitted)

## Abstract

This paper presents a new Livvi-Karelian corpus, addressing challenges encountered in low-resource language research. The main research goal was to collect and annotate new speech data, as well as to create a transcription dictionary. The corpus includes transcripts from radio broadcasts, featuring samples from 17 speakers (7 males and 10 females). Covering about 4.5 hours of audio recordings, it contains 32037 words, thus being a valuable tool for linguistic research. Among the peculiarities of the presented corpus are instances of code-switching between Livvi-Karelian and Russian. The baseline experiments were carried out with the Kaldi toolkit. Hybrid DNN/HMMs with factorized time-delay neural networks were utilized for acoustic modeling, while trigram and LSTM-based models were used for language modeling. The proposed model allowed achieving the Word Error Rate (WER) of 26%.

## Acknowledgments

Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
