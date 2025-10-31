# raviteja_unitree
H1-2 ROS2 Humble + Unitree SDK Docker Environment

# raviteja_unitree:humble

A ROS 2 Humble desktop environment with Unitree robotics support (H1-2, Go2, etc.) and preinstalled development tools.

## 🧩 Features
- ROS 2 Humble pre-installed
- Unitree SDK and ROS 2 packages
- VNC support for remote GUI access
- Preconfigured for development and simulation
- Includes tools: RViz2, Gazebo, rqt, colcon, and ROS2 CLI tools

## 🖥️ How to Run
```bash
docker run -d \
  --name ros2_unitree_vnc \
  -p 5902:5902 -p 6081:80 \
  ghcr.io/raviteja-t/raviteja_unitree:humble
```

## Desktop Access
http://localhost:6081

# Maintainer
Raviteja Tirumalapudi
t.raviteja@gmail.com
