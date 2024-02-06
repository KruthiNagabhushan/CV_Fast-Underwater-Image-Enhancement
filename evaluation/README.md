# Official Evaluation

For fair comparison, official evaluation scipts are adopted. Please refer to [here](https://github.com/xahidbuffon/FUnIE-GAN/tree/master/Evaluation).

The only retouch is in `uqim_utils.py` line 64, 65, 153, and 154. Add `int` to take the integer widths and heights for the block size. In `imqual_utils.py` line 21, replace `xrange` with `range` because `Python 3.7` is used.

|                     | PSNR          | SSIM         | UIQM         |
|---------------------|---------------|--------------|--------------|
| Input               | 27.623(2.875) | 0.785(0.064) | 2.571(0.550) |
| Ground Truths       | -             | -            | 2.877(0.541) |

## Paired Model: FUnIE-GAN-V1

|                     | PSNR          | SSIM         | UIQM         | Model Weights |
|---------------------|---------------|--------------|--------------|---------------|
| Underwater Imagenet | 26.146(2.466) | 0.797(0.065) | 3.022(0.426) | [link](https://drive.google.com/file/d/1haLnHPDAVMLazyNecUbSOD5InrOCVoPE/view?usp=sharing) |
| Underwater Dark     | 26.593(3.443) | 0.751(0.082) | 2.736(0.548) | [link](https://drive.google.com/file/d/1DIDMQNmuy11znSlesF38UgBslomsPBVh/view?usp=sharing) |
| Underwater Scenes   | 27.685(2.885) | 0.805(0.075) | 2.971(0.513) | [link](https://drive.google.com/file/d/19j3kn-l8L91xRGl6dHocS8VBN0wKKpd5/view?usp=sharing) |

## Paired Model: FUnIE-GAN-V2

|                     | PSNR          | SSIM         | UIQM         | Model Weights |
|---------------------|---------------|--------------|--------------|---------------|
| Underwater Imagenet | 27.241(3.121) | 0.802(0.072) | 3.056(0.454) | [link](https://drive.google.com/file/d/105F5VUHVlqToML1kkgJkLq0q7AKwp1kx/view?usp=sharing) |
| Underwater Dark     | 26.746(3.629) | 0.787(0.068) | 2.934(0.445) | [link](https://drive.google.com/file/d/10GzWP30d_VSvUedw7S1IIgTfsUnNEMci/view?usp=sharing) |
| Underwater Scenes   | 28.056(3.119) | 0.824(0.066) | 3.056(0.453) | [link](https://drive.google.com/file/d/10KlmEbRMNLjme1ZMi5tOW04k_nr_EBBJ/view?usp=sharing) |

## Unpaired Model: FUnIE-GAN-UP

| PSNR          | SSIM         | UIQM         | Model Weights |
|---------------|--------------|--------------|---------------|
| 24.548(2.212) | 0.708(0.068) | 2.780(0.541) | [link](https://drive.google.com/file/d/103XUuzoMMeGkCv9h2xC8BTm8L-YyYlq8/view?usp=sharing) |