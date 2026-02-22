# Cricket Batsman Weight Balance Analysis using Pose Estimation

This project analyzes the weight balance of a cricket batsman from a
side-view batting video using a pretrained pose estimation yolo11s-pose model.

It calculates the Center of Mass (COM) of the batsman and shows the
weight distribution between the left and right foot. The result is
visualized directly on the output video with a heatmap at the bottom,
making it easy to understand the balance during batting.

------------------------------------------------------------------------

# Features

-   Pose estimation using pretrained YOLO Pose model
-   Center of Mass (COM) calculation
-   Left and right foot weight distribution (%)
-   Weight balance heatmap visualization
-   COM point visualization on the body
-   Output video with full analytics overlay
-   No training required (uses pretrained model)

------------------------------------------------------------------------

# How it works

Pipeline:

    Input Video
       ↓
    Pose Estimation
       ↓
    Extract Body Keypoints
       ↓
    Compute Center of Mass
       ↓
    Calculate Weight Distribution
       ↓
    Generate Heatmap
       ↓
    Output Video with Visualization

------------------------------------------------------------------------

# Output

Output video contains:

-   Pose skeleton
-   Center of Mass point
-   Left and right weight percentage
-   Weight balance heatmap at bottom

------------------------------------------------------------------------

# Example use cases

-   Cricket performance analysis
-   Biomechanics analysis
-   Player balance evaluation
-   Coaching and training support
-   Sports analytics projects

------------------------------------------------------------------------

# Requirements

-   Python 3.9+
-   ultralytics
-   opencv-python
-   numpy
-   pandas
-   tqdm

------------------------------------------------------------------------

# Model used

Ultralytics YOLO Pose (yolo11s-pose.pt)

No custom training required.

------------------------------------------------------------------------

# Future improvements

-   Shot classification
-   Swing speed analysis
-   Balance score tracking
-   Real-time analysis
-   Bat trajectory tracking

------------------------------------------------------------------------

# License

This project is open-source and available under the MIT License.
