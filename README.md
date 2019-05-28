## LibriSpeech (960h)

90 epochs (\alpha 0.9, \beta 0.3 \width 512)

|      | test-clean %WER | test-others %WER | 
|:-------|-------:|:------:|
| SpecAugment + CTC + greedy   |   6.29   |   18.45    |
| SpecAugment + CTC + 4gram LM    |   4.27    |   12.60    |
| SpecAugment + CTC + transformer LM    |   ?    |   ?    |
| SpecAugment + RNN-T + greedy   |   ?    |   ?   |
| SpecAugment + RNN-T + 4gram LM  |   ?    |   ?    |
| SpecAugment + RNN-T + transformer LM  |   ?    |   ?    |
