# Post-Exam Proctoring Report Simulation Tool

This Python project simulates and generates a comprehensive **post-exam analysis report**, aimed at evaluating student behavior and the exam environment using randomly generated data. It is designed to serve as a prototype for future **intelligent exam monitoring systems**.

---

## Features

- Simulates the exam environment for a given number of students  
- Randomly assigns warnings to students and simulates cancelled exam papers  
- Simulates noise levels to assess environmental quality  
- Generates a detailed report with:
  - Total students  
  - Number of warnings issued  
  - Cancelled papers  
  - Average noise levels  
  - Environment classification (Calm / Moderate / Disruptive)  
- Saves the report as a JSON file  
- Visualizes the results using Matplotlib  

---

##  How It Works

1. **Simulation**  
   Randomly generates warning data, cancelled papers, and noise levels.

2. **Analysis**  
   Processes this data to create a structured report.

3. **Visualization**  
   Uses `matplotlib` to create a horizontal bar chart summarizing the report.

---

## Output Files

- `simulateddata.json`  
  Contains the structured report for future use or integration.

---

##  Requirements

Make sure you have Python 3 installed. Then, install the required library:

```bash
pip install matplotlib

▶️ Usage
Run the script using any Python IDE or from the terminal:

python exam_report_simulation.py

📌 Sample Output

Total Students Appeared in the exam: 50
Out of 50 students, 18 students received warnings...
Average noise level recorded during the exam was 2340.5 decibels.
Environment classified as: Moderate Noise, Minor Disruptions
A horizontal bar chart will also be displayed summarizing the findings.
Potential Improvements
Replace simulated data with real inputs (e.g., from facial detection, microphone sensors)

Connect with a live database or exam monitoring system

Add GUI for real-time dashboard display

🤝 Contribution
Feel free to fork this repo and contribute by submitting pull requests.
Ideas for real-time input integration or improving visualization are most welcome!

📧 Contact
For collaboration or queries, connect with me on LinkedIn.

📄 License
This project is licensed under the MIT License.
