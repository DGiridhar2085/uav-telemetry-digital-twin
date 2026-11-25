# UAV Telemetry Digital Twin

> **Status:** Active reconstruction - telemetry acquisition and transfer are the current implementation focus.

A real-time UAV monitoring project built around a PX4-compatible architecture, MAVLink telemetry, and a Python gateway. The goal is to create a reliable data path from a flight controller to software that can support future visualisation and health-monitoring work.

## What this project explores

- MAVLink-based telemetry communication
- Python telemetry acquisition and decoding
- Flight-state data handling, including GPS/IMU, battery, and motor/ESC telemetry
- A foundation for future dashboard, fault-diagnosis, and predictive-maintenance work

## Current scope

The verified implementation focus is **telemetry acquisition and transfer**. 3D visualisation, machine-learning diagnosis, and predictive maintenance are planned extensions, not completed claims.

## Planned structure

```text
├── telemetry/       # Python MAVLink gateway
├── docs/            # Architecture, setup notes, and test evidence
├── tests/           # Reproducible telemetry checks
└── assets/          # Verified screenshots, logs, and hardware photographs
```

## Reconstruction roadmap

- [ ] Document the flight-controller model and connection method
- [ ] Recreate the Python telemetry gateway
- [ ] Record a verified MAVLink test session
- [ ] Add only measured update-rate, latency, and packet-loss results
- [ ] Build dashboard and diagnostics modules as separate milestones

## Author

**D. Giridhar**  
[LinkedIn](https://www.linkedin.com/in/duddekunta-giridhar-799b88302/) · [GitHub](https://github.com/DGiridhar2085)

## License

This repository will use the MIT License once recreated source code is added.
