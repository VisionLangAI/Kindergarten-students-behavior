# Dataset: Academic Performance and Unsafe Behavior Detection in Kindergarten Students

## Overview
This dataset combines academic performance indicators and behavior observations to support research on forecasting academic outcomes and detecting unsafe behaviors in kindergarten-aged children. It is designed to facilitate the development and evaluation of machine learning models, particularly deep learning frameworks, that aim to improve early childhood education outcomes and safety monitoring.

## Dataset Composition
The dataset contains **5000 unique records**, each corresponding to an observation instance for an individual student at a specific timestamp. The data integrates both academic and behavioral aspects along with contextual information.

## Attributes

| Attribute Name           | Description                                              | Data Type         |
|-------------------------|----------------------------------------------------------|-------------------|
| `timestamp`             | Date and time when the observation or record was made    | String (YYYY-MM-DD HH:MM:SS) |
| `child_id`              | Unique anonymized identifier for each student            | String            |
| `academic_score`        | Numeric score representing academic performance (0-100) | Float             |
| `attendance_rate`       | Percentage of days attended by the student (%)           | Float             |
| `homework_completion_rate` | Percentage of homework assignments completed (%)       | Float             |
| `behavior_label`        | Observed behavior category (e.g., running, falling, safe)| Categorical String|
| `environment_location`  | Location where the behavior or observation was recorded  | Categorical String|
| `alarm_triggered`       | Indicates if an unsafe behavior alarm was triggered      | Boolean           |
| `risk_score`            | Numerical score (0-1) estimating severity of unsafe behavior | Float             |

## Potential Use Cases
- Forecasting academic performance and identifying key contributing factors.
- Early detection of unsafe or risky behaviors in kindergarten settings.
- Multi-modal learning combining behavioral and academic data.
- Development of real-time monitoring and early warning systems in educational environments.

## Data Format
The dataset is provided in CSV format for ease of use with common data analysis and machine learning tools.

## Ethical Considerations
- All child identifiers are anonymized to protect privacy.
- The dataset is intended for research and development purposes.
- When using real-world data, ensure compliance with relevant data protection and ethical standards.

