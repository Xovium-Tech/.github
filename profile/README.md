# Xovium Tech

We work on UAV simulation and navigation, helping teams test autonomous vehicles.

We build custom environments, models, and plugins around PX4 and ArduPilot, using MAVLink/MAVSDK/ROS/ROS 2 in a variety of modern simulators.

Here you can find our open-source plugins, which solve unique problems or improve the performance of existing open-source plugins:

- [Dynamic Terrain](https://github.com/Xovium-Tech/gz-dynamic-terrain-plugin) - a real-world terrain plugin for Gazebo. Loads satellite imagery tiles onto terrain generated from elevation data and renders it directly for simulated cameras. Uses level of detail (LOD) and camera visibility to reduce rendering overhead.
- [Camera Streaming](https://github.com/Xovium-Tech/gz-gstreamer-enhanced-camera-plugin) - a simulated camera plugin that streams frames through GStreamer with low latency. Supports multiple camera feeds on separate UDP ports.
- [Real GPS](https://github.com/Xovium-Tech/gz-real-gps-plugin) - a GPS simulation plugin for testing drones in environments with poor or unavailable GPS reception. Can use satellite orbit data from CelesTrak’s Yuma almanacs to estimate satellite visibility. Supports spoofing, signal loss, and configurable reception quality, antenna offsets, and elevation masks.

[Find out more about us or contact us if you have special requests](https://xovium.tech/).
