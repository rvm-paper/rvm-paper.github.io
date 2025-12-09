We present qualitative results on 5 randomly selected videos from the DAVIS-2017 dataset using KMeans clustering to illustrate how each model decomposes visual structure in a video. KMeans is applied directly to the raw feature maps without any additional processing, using K = 5 clusters. The resulting clusters are visualized as RGB images.

We compare RVM with several strong video-model baselines: VideoMAE, VideoMAE-v2, VJEPA, VJEPA-2, DINO, DINO-v2, and 4DS. All models use a ViT-L backbone with matched feature-map dimensions and a 16×16 patch size, except DINO-v2, which uses a 14×14 patch size. All baseline checkpoints are obtained from their official GitHub repositories.

Each video is presented as a 3×3 qualitative comparison grid in the following order (row by row, left to right):

Row 1: input video, videomae, videomae_v2
Row 2: vjepa, vjepa2, dino
Row 3: dino_v2, 4ds, rvm
