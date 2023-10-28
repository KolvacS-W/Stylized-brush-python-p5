# Stylized-brush-python-p5
A stylized brush application allowing brush stylization using [python p5](https://pypi.org/project/p5/) and [dreamstudio](https://beta.dreamstudio.ai/membership) stable diffusion (SD) api

## Demo:

https://github.com/KolvacS-W/Stylized-brush-python-p5/assets/55591358/5234060a-62b6-416d-a298-dcac2c95416c

https://github.com/KolvacS-W/Stylized-brush-python-p5/assets/55591358/0a11c534-8c52-4a84-9491-2ca6a24bedad

## Usage:

Firstly, [get dreamstudio api](https://beta.dreamstudio.ai/membership): 

Directly run any code:
```
python example1_fish.py
```
input api key
```
input your dreamstudio api:
```
paint with mouse

<img width="300" alt="Screen Shot 2023-10-28 at 4 28 26 PM" src="https://github.com/KolvacS-W/Stylized-brush-python-p5/assets/55591358/958fa5e0-913d-4349-94d9-988bb82100e5">


press any keyboard button to stylize and save current canvas

<img width="300" alt="Screen Shot 2023-10-28 at 4 28 44 PM" src="https://github.com/KolvacS-W/Stylized-brush-python-p5/assets/55591358/7345e3f6-dab4-4af5-8ac3-55396db30e3a">

preceed to paint .....

<img width="300" alt="Screen Shot 2023-10-28 at 4 29 04 PM" src="https://github.com/KolvacS-W/Stylized-brush-python-p5/assets/55591358/56ef4cbc-c273-42b0-a243-bdb403480a3a">


Change these parts of the code to customize paint brush:

stylize_prompt: prompt for stylization
```
seed: seed for SD generation
start_schedule: controls the "strength" of the prompt relative to the init image
fill(): brush color
circle_size: brush size
```
Reference for more advanced development in [p5](https://pypi.org/project/p5/)!

