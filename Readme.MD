docker build -t ros_image .
docker run -v $(pwd)/bag_files:/bag_files -v $(pwd)/output_bag_files:/output_bag_files -it ros_image