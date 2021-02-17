Runs image matting demo without GPU.

### Environment 
Python : 3.6.9 <br>
Pytorch : 1.7.1

### To Run 
1. Download pretrained weights from [here](https://drive.google.com/drive/folders/1umYmlCulvIFNaqPjwod1SayFmSRHziyR?usp=sharing) and put it inside MODNet/pretrained.
2. Then run the following command <br>
python -m demo.image_matting.colab.inference \
        --input-path < PATH TO INPUT FOLDER > \
        --output-path < PATH TO OUTPUT FOLDER > \
        --ckpt-path ./pretrained/modnet_photographic_portrait_matting.ckpt

## Demos

### Image Matting
We provide an [online Colab demo](https://colab.research.google.com/drive/1GANpbKT06aEFiW-Ssx0DQnnEADcXwQG6?usp=sharing) for portrait image matting.  
It allows you to upload portrait images and predict/visualize/download the alpha mattes. 

<img src="doc/gif/image_matting_demo.gif" width='40%'>


- **WebGUI for Image Matting**  
You can try [this WebGUI](https://gradio.app/g/modnet) (hosted on [Gradio](https://www.gradio.app/)) for portrait matting from your browser without any code! 
<!-- <img src="https://i.ibb.co/9gLxFXF/modnet.gif" width='40%'> -->


