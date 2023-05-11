BCG_Capstone_AIGC


# MoviePy 
import MoviePy library then make simple edits to videos, such as adding a line or cut a 20s video to 10s.

```
from moviepy import *
```
[MoviePy](https://zulko.github.io/moviepy/)

MoviePy is developed by MIT from image generation models for 2 years, and utilizes 5-layer conluvtional network as well as color histogram normalization. The developers are working on more layers to create higher resolution videos and more functions.
![MoviePy](https://user-images.githubusercontent.com/99071588/237564636-4536fccd-f155-4456-b48e-e281026d4cf7.png)

# Movio 
requests to Movio website upload and download the videos.

```
!pip install requests
import requests
```
[Movio](https://www.heygen.com/?from=moviola)

# Speech-to-text
import library and make requests after setting up the configuration.

```
import io
import os
```
[Google Cloud](https://cloud.google.com/?hl=zh-cn)

# Image generation
train and output images from prompts with wild imagination. 

```
!pip install stability-sdk -q
!pip install python-libmagic
```
Our team spent 3 months exploring stable diffusion. We trained models after uploading our own sets of images and then inputed prompts across all models in order to compare the results. We find out that **styles of the input and the output we want should be aligned**, such as rich input will generate rich output, and single-colored input will create single-colored output. We also find out that users should actively input negative prompts to generate better images.

[stable diffusion](https://stablediffusionweb.com/)



![image example](https://user-images.githubusercontent.com/99071588/236778233-8e8a697f-b95f-4a8a-b880-4afc179e92c0.png)



# Text generation
workable API to chatgpt with chatbox with two ways: library and endpoints.

```
!pip install openai
```

ChatGPT has been a super hot topic everywhere, and such as **relatively simple API and endpoint connections** could help users to build more complex websites with GPT. We heard that GPT has helped one user to find her cat---she listened to GPT's advice. To name one of the millions of usages of GPT, we also learned that users could generate code to process more than 100 excel files in one go. We hope that more users could benefit from one of the best LLMs in the world, and the code of GPT is also worth exploring in order to build better AI models.

[chatgpt](https://openai.com/blog/chatgpt)
