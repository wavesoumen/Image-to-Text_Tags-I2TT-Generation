
# Image to Text & Tags Generation:
Image-to-text generation is a widely-adopted way for deep understanding of cross-modal data, and has received increasing interest from computer vision (CV) and natural language processing (NLP) communities.
- Optical Character Recognition (OCR) is the process that converts an image of text into a machine-readable text format.
Google Colab is here [Image-to-text-tags](https://github.com/wavesoumen/Image-to-Text_Tags-I2TT-Generation/blob/main/Image_to_Text_Tags_Title.ipynb) for referance.

- ### Complete Example:
![Image3](https://github.com/wavesoumen/Image-to-Text_Tags-I2TT-Generation/blob/main/example2.png)
- Output Text and Tags:
```
a photography of a wooden block spelling trivia on a table
arafed wooden blocks spelling trivia on a wooden surface
['Photography', 'Creativity', 'Storytelling', 'a Photography', 'Documentary', 'a Storytelling', 'Creative']
```

## Explanation:
### Let's split this in 2 parts:
- Image to Text Generation.
- Tags Generation.
- ## Text to Image Generation:
For generating or extracting Text from any Image, there are some ML models prefernces below:
- [Salesforce/blip-image-captioning-base](https://github.com/wavesoumen/Image-to-Text_Tags-I2TT-Generation/blob/main/blip_base_Image-to-text.py)
- [Salesforce/blip-image-captioning-large](https://github.com/wavesoumen/Image-to-Text_Tags-I2TT-Generation/blob/main/blip_large_Image-to-text.py)
- [Microsoft/kosmos-2-patch14-224](https://github.com/wavesoumen/Image-to-Text_Tags-I2TT-Generation/blob/main/ms_kosmos_Image-to-text.py)

These are some models that uses CPU also the GPU(cuda).
- We can use Locally uploaded images and also the online image link for generating out result output.
#### Example1 (Local Image):
![Image1](https://github.com/wavesoumen/Image-to-Text_Tags-I2TT-Generation/blob/main/human1.png)
- Output Text:
```
a woman with a white shirt and a black background
```

#### Example2 (Online Image Link):
- Link: https://www.signupgenius.com/cms/images/groups/100-Random-Trivia-Questions-1260x630.png 
![Image2](https://github.com/wavesoumen/Image-to-Text_Tags-I2TT-Generation/blob/main/example1.jpg)
- Output Text:
```
a photography of a human head with a digital interface in the background
a robot head with a circuit in the background
```
- ## Tags Generation:
In this part I used the Fabiochiu/t5-base-tag-generation.

#### 
For any further queries or Explanation, contact me.
#
## - [Soumen Kayal.](https://github.com/wavesoumen)
