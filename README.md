# 🐢 Turtle Catcher ROS2 Project

## 📌 Overview

This is a ROS2 multi-package robotics simulation project using `turtlesim`.

The system simulates a simple autonomous behavior where:
- One turtle is spawned at random positions
- Another turtle is controlled to chase and catch it
- Communication is handled using ROS2 topics, services, and custom interfaces

---

## 🧠 Concept

The project follows a basic robotics loop:

**Sense → Decide → Act**

- Sense: Read turtle positions from turtlesim
- Decide: Compute direction toward target turtle
- Act: Publish velocity commands to move the turtle

---

## 🚀 Features

- 🐢 Turtle simulation using turtlesim
- 🎯 Random turtle spawner node
- 🤖 Turtle controller node (chasing logic)
- 📡 Custom ROS2 messages and services
- ⚙️ Launch file to start full system
- 🧪 ROS2 test structure included

---

## 🧠 ROS2 Concepts Used

- Nodes (Publisher / Subscriber / Server / Client)
- Custom Messages (.msg)
- Custom Services (.srv)
- Launch files (XML)
- Parameters (YAML)
- Multi-package workspace design

---

## ⚙️ Build Instructions

```bash
colcon build
source install/setup.bash
```
---

## ▶️ Run the Project

```bash
ros2 launch my_robot_bringup turtle_catch_them_all.launch.xml
```
