The Dataset Query Chatbot is a Python-based interactive tool that simplifies dataset exploration and preprocessing. Built using Gradio, it provides a user-friendly interface for querying datasets, handling missing values, and generating insightful visualizations. Users can upload custom CSV files and interact with their datasets through conversational queries like:

"How many rows and columns?"
"Are there any missing values?"
"Handle missing values with mean/median/mode."
"Auto visualize the dataset."

The chatbot supports dynamic handling of missing values by filling them with statistical measures (mean, median, mode) or custom values, depending on the column type. Additionally, it generates plots such as boxplots, heatmaps, and categorical distribution graphs to help users understand their data better.

Key Features:

-Upload Dataset: Users can upload their own CSV files for analysis.
-Handle Missing Values: Automatically identifies and fills missing values based on the column type.
-Data Visualization: Creates automatic visualizations for numeric and categorical columns, including: Boxplots, Correlation heatmaps ,Bar charts for categorical data
-Dynamic Queries: Responds to user input for exploring dataset details, handling missing values, and visualization.

Technologies Used:

-Python Libraries: pandas, matplotlib, seaborn
-Gradio: For building the interactive UI
-CSV File Support: Dynamic dataset upload and analysis
