We present qualitative results on 7 randomly selected videos from the DAVIS-2017 dataset for the video object segmentation task (first-frame ground-truth provided). The task is to propagate the ground-truth object segmentation from the first frame to all subsequent frames.

We compare RVM with several strong video-model baselines: VideoMAE, VideoMAE-v2, VJEPA, VJEPA-2, DINO, DINO-v2, and 4DS. All models use a ViT-L backbone with matched feature-map dimensions and a 16×16 patch size, except DINO-v2, which uses a 14×14 patch size. All baseline model checkpoints are obtained from their official GitHub repositories.

Each video is shown as a 3x3 qualitative comparison grid, in the following order (row by row, left to right):

Row 1: groundtruth, videomae, videomae_v2
Row 2: vjepa, vjepa2, dino
Row 3: dino_v2, 4ds, rvm
