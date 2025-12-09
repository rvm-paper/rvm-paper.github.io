We present qualitative results on 5 randomly selected videos from the DAVIS-2017 dataset using principal component analysis (PCA) to illustrate what each model primarily captures in a video. The PCA is applied directly to the raw feature maps without any additional processing (unlike the PCA visualization used in DINOv2). We extract the first three principal components and visualize them as RGB images.

We compare RVM with several strong video-model baselines: VideoMAE, VideoMAE-v2, VJEPA, VJEPA-2, DINO, DINO-v2, and 4DS. All models use a ViT-L backbone with matched feature-map dimensions and a 16×16 patch size, except DINO-v2, which uses a 14×14 patch size. All baseline checkpoints are obtained from their official GitHub repositories.

Each video is displayed as a 3×3 qualitative comparison grid in the following order (row by row, left to right):

Row 1: input video, videomae, videomae_v2
Row 2: vjepa, vjepa2, dino
Row 3: dino_v2, 4ds, rvm
