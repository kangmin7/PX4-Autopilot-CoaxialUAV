# PX4-Autopilot for CoaxialUAV

Custom [PX4-Autopilot](https://github.com/PX4/PX4-Autopilot) with a coaxial UAV model for SITL simulation in Gazebo.

**Demo**:
[![Demo](https://img.youtube.com/vi/AR0IHh4ygxA/maxresdefault.jpg)](https://www.youtube.com/watch?v=AR0IHh4ygxA)

---

## Changes

- Added coaxial top-tilt UAV model (`coaxial_top_tilt`) to Gazebo simulation
- Added airframe configurations for coaxial tilt variants
- Tuned gains to stabilize pendulum-like movement

---

## Running

```bash
cd ~/PX4-Autopilot-CoaxialUAV
make px4_sitl gz_coaxial_top_tilt
```
