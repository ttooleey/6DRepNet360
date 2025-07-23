# Examples

This directory contains example notebooks and scripts demonstrating how to use 6DRepNet360.

## Available Examples

### `example.ipynb`
A comprehensive Jupyter notebook that demonstrates:
- Loading the pre-trained 6DRepNet360 model
- Running inference on a single image
- Visualizing head pose estimation results
- Converting rotation matrices to Euler angles

#### Usage
1. Ensure you have activated the virtual environment and installed dependencies:
   ```bash
   source 6drepnet_env/bin/activate
   pip install -r requirements.txt
   ```

2. Run the notebook OR click Running a cell repeatedly:
   ```bash
   jupyter notebook examples/example.ipynb
   ```

#### Expected Output
- Yaw, Pitch, and Roll angles in degrees
- Visualization of the input image with pose axes overlaid

## Requirements
- See `../requirements.txt` for full dependency list
- CUDA-capable GPU recommended but not required
