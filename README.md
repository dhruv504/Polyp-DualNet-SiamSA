# Polyp-DualNet-SiamSA
This project is a Dual-Encoder TransUNet framework for automated polyp segmentation using the Kvasir-SEG dataset. It fuses a pre-trained ResNet34 CNN encoder with a Vision Transformer bottleneck and an ASPP layer to capture multi-scale, global features while a Tversky-Focal loss minimizes missing lesions. It hits 0.85 Dice on unseen data.
