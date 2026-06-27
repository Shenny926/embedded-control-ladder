# Embedded Control Ladder

A single evolving embedded/control-engineering project, built as a ladder of bounded "rungs." Each rung ends in a working artifact: hardware + a git commit + a README entry. Goal: fuse decaying control theory (digital control, state estimation) with hands-on embedded skill.

Hardware: Arduino starter kit, Raspberry Pi 5.

## Rungs
- [x] Rung 0 — Toolchain + first GitHub push
- [ ] Rung 1 — Blink → sense → react (GPIO, analog read, the embedded loop)
- [ ] Rung 2 — Closed-loop digital PID on one motor/servo
- [ ] Rung 3 — IMU + sensor fusion / state estimation (observer design, made physical)
- [ ] Rung 4 — Raspberry Pi ↔ Arduino serial link (two-processor architecture)
- [ ] Rung 5 — (stretch) put it on something that moves / control GUI / ROS2

## Log
### Rung 0 — Toolchain + first GitHub push
- Installed Git + Arduino IDE 2.3.8.
- Verified the IDE compiles a bare sketch (rung0_toolchain_check/).
- Initialized this repo and pushed the first commit.
