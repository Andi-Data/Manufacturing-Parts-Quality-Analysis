**Project Overview:** Manufacturing Parts Quality Analysis

 

**Objective:** The primary goal of this project was to evaluate a dataset of manufacturing parts to derive insights about operator performance and its impact on product quality, with a specific focus on the acceptable height range of the parts.

 

**Scope:**

Data Preprocessing: Conducted data profiling to understand the dataset comprehensively. The data was already cleaned.

Height Range Analysis: Calculated the upper control limit (UCL) and lower control limit (LCL) to define the acceptable height range for the parts.

Operator Performance: Analyzed operator performance to identify those linked to the highest number of parts falling outside the acceptable height range.
 

**Methodology:**

Data Processing: Imported and processed the data using Python libraries.

Statistical Analysis: Calculated UCL and LCL to determine the acceptable height range and identified parts falling outside this range.

Visualization: Created visualizations using matplotlib to analyze operator performance and the distribution of part heights.
 

**Key Findings:**

Height Range Violations: Identified 57 instances where the height of manufactured parts exceeded the acceptable range, accounting for 11.4% of all manufactured parts.

Operator Alerts: Every operator produced at least one part outside the acceptable height range. Operator 5 had the highest number of instances with 6 unacceptable parts, while operators 18, 1, 12, and 6 each had only 1 unacceptable part.

Average Non-Conformance: Each operator produced approximately 2.85 parts on average that did not meet the height criteria, indicating a widespread issue across the team.
 

**Recommendations:**

Investigate High-Alert Operators: Conduct a thorough review of the operators with the highest alert counts to identify the root causes. This may involve observing their work processes, checking the calibration of their equipment, and reviewing their training records.

Process Adjustments: Based on the findings, consider implementing targeted training programs, equipment maintenance schedules, or process adjustments to reduce the number of parts falling outside the acceptable height range.
 

**Conclusion:** This project provided valuable insights into operator performance and its impact on product quality. By addressing the identified issues, we can enhance the consistency and quality of the manufacturing process, ultimately reducing the number of alerts and improving overall product quality.
