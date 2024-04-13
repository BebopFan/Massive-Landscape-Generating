# Landscape Appearance Construction via Differentiable Rendering Based Terrain Weight Map Synthesis


### The 3D terrain scenes using our method

Results of the 3D terrain scenes we constructed. As can be seen, there is a significant difference in texture resolution before and after using the weight map.
[![Watch the video](./pic/demo/11.png)](https://www.youtube.com/watch?v=MK9H9dE12g4)  [![Watch the video](./pic/demo/33.png)](https://www.youtube.com/watch?v=FPN3bum9Cyc)

### The texture splatting technique for Large-Scale Terrain Rendering

To inherit the advantage of deep leaning based methods, and provide more surface details close to observer with acceptable hardware overhead, we introduce the texture splatting.

[![Watch the video](./pic/demo/22.png)](https://youtu.be/YbXISMrOThU)
<table align="center" width="55%">
  <tr>
    <td align="left">w/ Texture Splatting</td>
    <td align="right">w/o Texture Splatting</td>
  </tr>
</table>


### The experimental results on 512×1024 images

 Results of proposed stitching models, and image stitching methods. The first column is the texture with seam. The red box in the lower right corner is the magnified view for specific areas.

![Long Bar Experiment](./pic/stitch.png)


### The experimental results on 1024×2048 images

Pictures below present the qualitative experimental results on 1024×2048 images. The 512×1024 images presented above are cropped from these 1024×2048 images for demonstration purposes.

| Model |Image1|
|:--------:|:--------:|
| S        | ![S1](./pic/S/1.png) |
| GC       | ![GC1](./pic/GC/1.png) |
| EC       | ![EC1](./pic/EC/1.png) |
| GraphCut | ![GraphCut1](./pic/graphcut/1.png) |
| Seam2Cont | ![Seam2Cont1](./pic/seamcon2/1.png) |
| Ours     | ![Ours1](./pic/ours/1.png) |

| Model |Image2|
|:--------:|:--------:|
| S        | ![S2](./pic/S/0.png) |
| GC       | ![GC2](./pic/GC/0.png) |
| EC       | ![EC2](./pic/EC/0.png) |
| GraphCut | ![GraphCut2](./pic/graphcut/0.png) |
| Seam2Cont | ![Seam2Cont2](./pic/seamcon2/0.png) |
| Ours     | ![Ours2](./pic/ours/0.png) |

| Model |Image3|
|:--------:|:--------:|
| S        | ![S3](./pic/S/2.png) |
| GC       | ![GC3](./pic/GC/2.png) |
| EC       | ![EC3](./pic/EC/2.png) |
| GraphCut | ![GraphCut3](./pic/graphcut/2.png) |
| Seam2Cont | ![Seam2Cont3](./pic/seamcon2/2.png) |
| Ours     | ![Ours3](./pic/ours/2.png) |

### Comparative Overview of Image Processing Results

Results of the proposed method, inpainting and outpainting methods. The first column is the sample texture, while the second column is the target terrain.

![Long Bar Experiment](./pic/1.png)

### Detailed Visual Overview of Image Processing Results

The following images provide a detailed visual overview of the aforementioned images. The comparison images from the ReGo experiment have a resolution of 1024x512, while the resolutions of the other images being compared are 1024x1024.
| Model |Image1|
|:--------:|:--------:|
| GC       | ![GC1](./pic/in-out/gated-new/1.png) |
| EC       | ![EC1](./pic/in-out/edge-new/-29.0217112,21.9509659_600_300_0.png) |
| ReGo | ![GraphCut1](./pic/in-out/rego-new/-29.0217112,21.9509659_600_300_0.png)|
| Ours     | ![Ours1](./pic/in-out/ours/-29.0217112,21.9509659_600_300_0.png) |

| Model |Image2|
|:--------:|:--------:|
| GC       | ![GC1](./pic/in-out/gated-new/3.png) |
| EC       | ![EC1](./pic/in-out/edge-new/-7.470070_-77.208714_1500_0_0.png) |
| ReGo | ![GraphCut1](./pic/in-out/rego-new/-7.470070_-77.208714_1500_0_0.png) |
| Ours     | ![Ours1](./pic/in-out/ours/5_1500_0_0.png) |

| Model |Image3|
|:--------:|:--------:|
| GC       | ![GC1](./pic/in-out/gated-new/5.png) |
| EC       | ![EC1](./pic/in-out/edge-new/37.1961732_28.711534_300_0_0.png) |
| ReGo | ![GraphCut1](./pic/in-out/rego-new/37.1961732_28.711534_300_0_0.png) |
| Ours     | ![Ours1](./pic/in-out/ours/37.1961732_28.711534_300_0_0.png) |

| Model |Image4|
|:--------:|:--------:|
| GC       | ![GC1](./pic/in-out/gated-new/4.png) |
| EC       | ![EC1](./pic/in-out/edge-new/1.png) |
| ReGo | ![GraphCut1](./pic/in-out/rego-new/-12.6154685,18.9466741_900_300_0.png) |
| Ours     | ![Ours1](./pic/in-out/ours/-12.6154685,18.9466741_900_300_0.png) |

| Model |Image5|
|:--------:|:--------:|
| GC       | ![GC1](./pic/in-out/gated-new/0.png) |
| EC       | ![EC1](./pic/in-out/edge-new/-13.866279_-75.084183_0_0_3.png) |
| ReGo | ![GraphCut1](./pic/in-out/rego-new/_0_0_0.png) |
| Ours     | ![Ours1](./pic/in-out/ours/-13.866279_-75.084183_0_0_0.png) |

| Model |Image6|
|:--------:|:--------:|
| GC       | ![GC1](./pic/in-out/gated-new/2.png) |
| EC       | ![EC1](./pic/in-out/edge-new/-32.8313955,21.7528659_1200_300_0.png) |
| ReGo | ![GraphCut1](./pic/in-out/rego-new/-32.8313955,21.7528659_1200_300_0.png) |
| Ours     | ![Ours1](./pic/in-out/ours/-32.8313955,21.7528659_1200_300_0.png) |
