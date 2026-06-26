# Gaussian Splat PLY

This folder contains real GraphDECO-style Gaussian Splat PLY samples for loaders.gl and deck.gl examples. The original sample was split into two valid PLY files so each file stays below GitHub's 100 MB file limit.

## Files

- train-iteration-7000-part-00.ply
  - Vertices: 370,941
  - Size: 91,994,899 bytes.
  - Contains the first half of the original train/iteration_7000 splats.
- train-iteration-7000-part-01.ply
  - Vertices: 370,942
  - Size: 91,995,147 bytes.
  - Contains the second half of the original train/iteration_7000 splats.

Both files preserve the original binary little-endian PLY property layout and only rewrite the element vertex count in the header.

## Source

Original file: FO_dataset/train/point_cloud/iteration_7000/point_cloud.ply from Voxel51/gaussian_splatting on Hugging Face.

Download URL: https://huggingface.co/datasets/Voxel51/gaussian_splatting/resolve/main/FO_dataset/train/point_cloud/iteration_7000/point_cloud.ply

Original size: 183,988,515 bytes.
Original PLY vertex count: 741,883.

## Attribution

Dataset: Voxel51 Gaussian Splats Dataset
Dataset URL: https://huggingface.co/datasets/Voxel51/gaussian_splatting
Dataset author listed by the dataset card: Paula Ramos
Created using: 3D Gaussian Splatting for Real-Time Radiance Field Rendering
Original method/code repository: https://github.com/graphdeco-inria/gaussian-splatting

## License

The Hugging Face dataset card declares the dataset license as Apache-2.0.

Use these files for visual examples and manual integration tests. Keep smaller synthetic or truncated fixtures in source repositories when CI only needs schema or parser coverage.
