We present qualitative results on a random noise video using PCA and KMeans clustering to evaluate whether each model’s representations can capture motion independent of semantic content. Both PCA and KMeans are applied directly to the raw feature maps without additional processing, with K = 5 clusters for KMeans.

We compare RVM with several strong video-model baselines: VideoMAE, VideoMAE-v2, VJEPA, VJEPA-2, DINO, DINO-v2, and 4DS. All models use a ViT-L backbone with matched feature-map dimensions and a 16×16 patch size, except DINO-v2, which uses a 14×14 patch size. All baseline checkpoints are obtained from their official GitHub repositories.

Each video is presented as a 3×3 qualitative comparison grid in the following order (row by row, left to right):

Row 1: input video, videomae, videomae_v2
Row 2: vjepa, vjepa2, dino
Row 3: dino_v2, 4ds, rvm
