# Sensor Fusion 3D Object Detection on KITTI Dataset

This project implements a sensor fusion approach to 3D object detection using the KITTI dataset. The primary steps involve detecting objects in camera images, 
projecting 3D LiDAR point clouds to 2D image space, and associating LiDAR depth with each detected object.

## Project Structure

- `SensorFusion_3D_kitti_object_detection_lidar.ipynb`: Main Jupyter Notebook containing the implementation.
- `kitti_utils.py`: Helper functions for processing KITTI dataset.

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/VarunBiyyala/RGB_LiDAR_SensorFusion.git
    cd RGB_LiDAR_SensorFusion
    ```

## Description

The project performs the following main steps:

1. **Object Detection in Camera Images**: Detect objects in the 2D image using a pre-trained neural network.
2. **Projection of 3D LiDAR Point Clouds**: Project 3D LiDAR points to the 2D image plane.
3. **Depth Association**: Fuse the detected 2D objects with LiDAR data to associate depth information.

## Results

### RGB Image & 3D LiDAR Point Clouds on 2D Image Space
![Projected LiDAR Points](path/to/projected_lidar_image.jpg)

### Final Sensor Fusion Output (LiDAR Point CLoud Projected on RGB Image)
![Sensor Fusion Output](path/to/sensor_fusion_output_image.jpg)
