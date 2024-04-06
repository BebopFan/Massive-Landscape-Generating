# Generating Massive Landscape through Multi-layer Texture Mapping using Differentiable Rendering


### The experimental results on 512×1024 images

 Results of proposed stitching models, and image stitching methods. The first column is the texture with seam. The red box in the lower right corner is the magnified view for specific areas.

![Long Bar Experiment](./pic/stitch.png)

Results of the proposed method, inpainting and outpainting methods. The first column is the sample texture, while
the second column is the target terrain.

![Long Bar Experiment](./pic/1.png)

Ablation experiments for weight map synthesis model, including different loss functions, decoder branches, and
discriminator inputs. The red box in the lower right corner is a magnified view of a specific area.

![Long Bar Experiment](./pic/2.png)

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
