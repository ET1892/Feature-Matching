### Feature Matching & Stereo Vision

This project implements a stereo vision pipeline for feature detection, matching, and depth estimation. Using OpenCV and Python, the project explores how visual features can be detected and matched across stereo image pairs to reconstruct 3D information.

**Key Features:**
- **Implemented SIFT** to detect and describe keypoints invariant to scale, rotation, and illumination changes.
- Visualised feature matches between stereo images using OpenCV’s feature matching algorithms.
- Computed the fundamental matrix and drew epipolar lines to represent geometric relationships between corresponding points.
- Generated disparity maps to estimate relative depth from stereo image pairs.
- Created a 2.5D visualisation of the scene, illustrating how disparity translates to perceived depth.

**Technical Stack:**
- **Language:** Python
- **Libraries:** OpenCV, NumPy, Matplotlib, Jupyter Notebooks
- **Environment:** Conda

**Project Highlights:**
- Demonstrated the full stereo vision pipeline, from SIFT keypoint extraction to depth reconstruction.
- Used matched features to compute geometric constraints and visualise epipolar geometry.
- Produced a depth map highlighting variations in distance across the scene, validated through 2.5D plotting.
- Provided visual examples using a motorbike image pair, showing keypoints, matches, and disparity estimation.
