# VoIP-Steganalysis


# Fast Steganalysis Method for VoIP Streams


**[[paper (IEEE)](https://ieeexplore.ieee.org/abstract/document/8943350)]**
**[[paper (pdf)](https://arxiv.org/pdf/1910.14571.pdf)]**
**[[code](https://github.com/YangzlTHU/VoIP-Steganalysis/blob/master/FM.py)]**
**[[dataset](https://github.com/fjxmlzn/RNN-SM#steganalysis-speech-dataset)]**
**[[website](https://github.com/YangzlTHU/VoIP-Steganalysis)]**


**Abstract:** In this letter, we present a novel and extremely fast steganalysis method of Voice over IP (VoIP) streams, driven by the need for a quick and accurate detection of possible steganography in VoIP streams. We firstly analyzed the correlations in carriers. To better exploit the correlation in code-words, we mapped vector quantization code-words into a semantic space. In order to achieve high detection efficiency, only one hidden layer is utilized to extract the correlations between these code-words. Finally, based on the extracted correlation features, we used the softmax classifier to categorize the input stream carriers. To boost the performance of this proposed model, we incorporate a simple knowledge distillation framework into the training process. Experimental results show that the proposed method achieves state-of-the-art performance both in detection accuracy and efficiency. In particular, the processing time of this method on average is only about 0.05\% when sample length is as short as 0.1s, attaching strong practical value to online serving of steganography monitor.

## Cite it 

This paper was published as a journal paper in IEEE Signal Process Letter

```bash
@article{yang2019fast,
  title={Fast Steganalysis Method for VoIP Streams},
  author={Yang, Hao and Yang, ZhongLiang and Bao, YongJian and Liu, Sheng and Huang, YongFeng},
  journal={IEEE Signal Processing Letters},
  year={2019},
  publisher={IEEE}
}
```
