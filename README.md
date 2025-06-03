# M3SFormer

## Project Profile

This repository is prepared for presenting the results of the M3SFormer model. Here, we have uploaded 30 mural images from the MuralVerse dataset along with the corresponding degradation masks.

## M3SFormer: Multi-Stage Semantic and Style-Fused Transformer for Mural Image Inpainting

With the growing advancement of deep learning techniques, high-quality restoration of historical murals remains a challenging task. Issues such as complex texture patterns, semantic inconsistency, and artistic style preservation present major obstacles. Existing inpainting methods often struggle to balance structural completeness with visual authenticity in large missing regions.

To address these challenges, we propose **M3SFormer**, a Multi-Stage Semantic and Style-Fused Transformer architecture designed for mural image inpainting. The framework consists of two key stages: the first is a **global restoration module** guided by semantic cues for structure reconstruction; the second is a **refinement module** based on flow-guided semantic enhancement for detailed texture and style restoration.

M3SFormer integrates a pre-trained semantic segmentation model (e.g., Mask2Former) to ensure spatial semantic alignment. Additionally, we incorporate a combination of progressive Gram loss and semantic-aware local style loss to maintain the fine brushstroke details and regional style consistency found in mural artworks.

Our method is evaluated on the custom-built MuralVerse dataset, which includes mural samples from various regions of China. All images are paired with degradation masks extracted from real mural damage patterns such as paint peeling, oxidation, and cracks.

## Code

We will release the training code, testing scripts, and related components at an appropriate time.
