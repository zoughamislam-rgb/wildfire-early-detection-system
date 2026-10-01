# Wildfire Early Detection System

A multidisciplinary engineering project exploring distributed, autonomous, low-power sensing for earlier wildfire detection in remote environments.

## Vision

The long-term system may combine environmental sensing, embedded electronics, low-power communications, autonomous solar power, data analysis, and decision-support tools. The project is intentionally being developed from validated subsystems rather than from an overclaimed end-to-end concept.

## Current technical focus

- Define measurable wildfire-detection requirements.
- Study candidate sensor combinations and failure modes.
- Design a distributed sensor-node architecture.
- Estimate node power consumption and autonomy.
- Explore solar + MPPT power options.
- Compare communication technologies for remote deployment.
- Build simulations and small experiments to test key assumptions.

## Repository structure

```text
docs/          Project context, architecture, research notes, roadmap
firmware/      Sensor-node and embedded code
hardware/      Schematics, power electronics, PCB and wiring files
simulation/    Energy, coverage, communication and detection models
experiments/   Bench tests and prototype measurements
data/          Small reproducible datasets only
assets/        Diagrams and documentation images
```

## Development philosophy

This repository is an engineering research log. Planned features are kept separate from demonstrated capabilities. Every important subsystem should eventually have a documented assumption, calculation, simulation, or experiment behind it.

## Current status

Research and system-architecture phase. Initial work focuses on sensor-node design, energy autonomy, communications, and detection strategy.

## Author

Nour El Islam Zougham — nanoelectronics engineering student.
