What This Project Does
Accepts real data or generates sample data — the interactive notebook lets you upload your own performance CSV; if none is provided (or the columns don't match), it automatically falls back to a generated sample dataset so the tool never breaks
Calculates KPIs automatically — on-time completion rate and a weighted performance score, computed directly from raw task and feedback numbers using Pandas
Builds a monthly report — ranks all interns by performance score, flags anyone falling below a completion or performance threshold as needing mentor attention
Rolls up by department — average KPIs per department, useful for spotting which team/workflow is performing best
Tracks trends over time — month-over-month view of average performance across the whole internship program
Generates supervisor-ready charts — performance trend line, department comparison bar chart, and a top-10 performers chart
Packages results for download — at the end, all reports and charts are zipped into one folder, ready to hand to a supervisor or attach to a presentation


Tools Used
Python
Pandas — KPI calculation and data aggregation
NumPy — sample data generation
Matplotlib — charts and visualizations
