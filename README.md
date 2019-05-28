## LibriSpeech (960h)

90 epochs (\alpha 0.9, \beta 0.3 \width 512)

|      | test-clean %WER | test-others %WER | 
|:-------|-------:|:------:|
| Facebook's ConvNet + 4-gram LM  | 4.8 	| 14.5 |
| | | |
| SpecAugment + CTC + greedy   |   6.2   |   18.4    |
| SpecAugment + CTC + 4-gram LM    |   4.2    |   12.6    |
| SpecAugment + CTC + transformer LM    |   ?    |   ?    |
| SpecAugment + RNN-T + greedy   |   ?    |   ?   |
| SpecAugment + RNN-T + 4-gram LM  |   ?    |   ?    |
| SpecAugment + RNN-T + transformer LM  |   ?    |   ?    |
