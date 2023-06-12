## REYD: Reading Electronic Yiddish Documents

A project to develop text-to-speech (TTS) support for Yiddish

**Authors:** [Jacob J. Webber](https://github.com/jacobjwebber), [Samuel Lo](https://github.com/vatnid), [Isaac L. Bleaman](https://github.com/ibleaman)

### Papers[^1]

* Webber, Jacob J., Samuel K. Lo, and Isaac L. Bleaman. 2022. REYD – The first Yiddish text-to-speech dataset and system. *Proceedings of Interspeech 2022*, 2363-2367. [doi: 10.21437/Interspeech.2022-789](https://doi.org/10.21437/Interspeech.2022-789)
* Bleaman, Isaac L., Jacob J. Webber, and Samuel K. Lo. 2023. Speech synthesis in the "mother tongue": Designing, training, and evaluating a text-to-speech system for Yiddish. *Journal of Jewish Languages* 11(1), 15-43. [doi: 10.1163/22134638-bja10034](https://doi.org/10.1163/22134638-bja10034)

[^1]: To cite the REYD project, please refer to one of our papers.   
**Acknowledgments** (for Bleaman, Webber, & Lo 2023): We express our gratitude to the Yiddish speakers whose recordings were used for the current project: Perec Zylberberg ז"ל, a great believer in the future of Yiddish; Sara Blacher-Retter ז"ל, a dedicated Israeli nurse; and Leib Rubinov ז"ל, a lifelong Jewish educator. Their recordings were already available to the public online, but we have additionally communicated with their surviving relatives and been given informed consent to publish a TTS data set and synthetic voices. The source texts of all the material in the data set are in the public domain.   
We thank Madeleine (Mindl) Cohen and Amber Kanner Clooney of the Yiddish Book Center, who recommended source material and were helpful throughout. Eliezer Niborski provided a digital list of *loshn-koydesh* respellings and was the independent expert evaluator for the listening test described in section 3. Aidan Pine advised us on adapting FastSpeech 2 to a new language. We also thank Dafna Sheinwald, who connected us with the family of Sara Blacher-Retter, and Raphael (Refoyl) Finkel, for facilitating the correction of Sholem Aleichem's texts and providing additional assistance with OCR.

### Dataset

* [Download](https://datashare.ed.ac.uk/bitstream/handle/10283/4383/reyd-dataset.zip)

### Demo

* [Audio samples](https://reyd-tts.github.io/audio-samples/) of ground-truth and synthesized utterances
* [Interactive demo](https://colab.research.google.com/drive/1xv0I_auaZ9rdNMMyrBpJHvOotH9w_BHa?usp=sharing), if you'd like to synthesize your own texts

### Other resources

* [yiddish-tts-texts](https://github.com/REYD-TTS/yiddish-tts-texts): Code to download and segment Yiddish audiobooks and hand-corrected texts; reproduces the REYD dataset linked above
* [REYD-textgrids](https://github.com/REYD-TTS/REYD-textgrids): Praat TextGrid files to accompany the REYD dataset, produced by the [Montreal Forced Aligner](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner); used by FastSpeech2 (see [our fork](https://github.com/REYD-TTS/FastSpeech2) or the interactive demo linked above)
* [yiddish](https://github.com/ibleaman/yiddish): A Python library for processing Yiddish text
