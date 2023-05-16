# Super-Resolution
Hyperspectral Image Super-Resolution via Deep Spatiospectral Attention Convolutional Neural Networks

Conventional multispectral images (MSIs), such as RGB images, typically have a limited number of spectral bands, providing limited spectral information. In contrast, hyperspectral imaging (HSI) captures more spectral bands, enabling the acquisition of richer spectral information. However, due to the physical limitations of imaging sensors, there is a trade-off between spatial resolution and spectral resolution in HSI. Obtaining HSI with high spatial resolution becomes challenging.

To address this issue, researchers have explored hyperspectral image (HSI) super-resolution techniques, which involve fusing a low-resolution hyperspectral image (LR-HSI) with a high-resolution multispectral image (HR-MSI). Many algorithms have been proposed to increase the spatial resolution of LR-HSI using a linear model. The model includes matrices representing LR-HSI (Y), HR-MSI (Z), and the latent high-resolution hyperspectral image (HR-HSI) (X). The dimensions of these matrices correspond to the height and width of LR-HSI (h and w), the height and width of HR-MSI (H and W), and the spectral band numbers of HR-MSI and LR-HSI (s and S), respectively. The blur matrix (B), downsampling matrix (S), and spectral response matrix (R) are also involved in the model.

GROUND TRUTH:
![Screenshot from 2023-05-14 18-06-54](https://github.com/talhaty/Super-Resolution/assets/73438667/5d60d6aa-1ea0-4bca-a42f-d9a4054b6cd6)


PREDICTED IMAGES:
![Screenshot from 2023-05-14 18-06-49](https://github.com/talhaty/Super-Resolution/assets/73438667/5a748f35-ae35-4441-be02-d9c96f0e7852)

