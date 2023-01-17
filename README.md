# Stable Diffusion WebUI Tagger

This is a small extension for AUTOMATIC's webui. It adds a tab for tagging images from a dataset.

![Screenshot of user interface](showcase/screenshot.png)

## Getting Started

Just install the extension through the extensions tab or git clone into your extensions folder.

## Usage

### Dataset

Provide the dataset path and it will **recursively** find matching images and captions pairs *(e.g. example.txt / example.png)*. 
It **does not** support captions in the filename yet.

### Tags.txt

For tagging you can provide a tags file with each tag on a new line.

```
from above
from side
from below
1boy
1girl
text
hallway
masterpiece
best quality
high quality
...
```

### Cropping

To crop an image just left-click and drag on the image. The cropped photo will be saved in
the /crops/ folder. By default, it snaps to a 64 pixel grid, you can change this in the settings.

![Screenshot of cropping](showcase/screenshot-2.png)

### Interrogate

You can interrogate an image using DeepDanbooru by clicking the interrogate button.

![Screenshot of interrogate](showcase/screenshot-3.png)

## Planned Features

- Faster loading
- More interrogators
- Tag pagination
- Cropping modes (Brush)
- ...