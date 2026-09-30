# Robot Video QA & Anomaly Annotation Pipeline

Automated quality assurance tool for evaluating recorded robot manipulation trials, quantifying gripper trajectory drift, and generating auditable failure event logs.

## Features
- **Trajectory Error Detection:** Evaluates pixel and spatial drift between target coordinates and end-effector paths.
- **Incident Categorization:** Classifies slip, excessive deviation, and tracking dropouts.
- **Standardized Reporting:** Exports machine-readable JSON logs for distributed robotics teams.

## Quick Start
```bash
git clone [https://github.com/izzypizzy11/robot-video-qa-annotation.git](https://github.com/izzypizzy11/robot-video-qa-annotation.git)
cd robot-video-qa-annotation
python3 video_qa_evaluator.py
