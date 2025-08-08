# moveit_pro_clipseg

ROS package containing CLIPSeg ONNX models for image segmentation.

## Contents

This package contains the following ONNX models:

- `models/clip.onnx` - CLIP model for text and image encoding
- `models/clipseg.onnx` - CLIPSeg model for semantic segmentation

## Usage

Submodule this repo into a user_workspace to make the models available in the `moveit_pro_clipseg` package for use by MoveIt Pro Behaviors.