# python_expenseDash
A clean, interactive expense tracker and budgeting tool built with Python and Streamlit

💰 Personal Finance Dashboard
A clean, interactive expense tracker and budgeting tool built with Python and Streamlit. This dashboard allows users to log daily expenses, visualize spending habits through dynamic charts, and track progress against a monthly budget goal.

🚀 Key Features
Expense Logging: Add transactions easily via the sidebar form (Date, Item, Category, Amount).

Persistent Session Data: Uses st.session_state to keep track of added expenses during your session without losing data on reload.

Smart Budgeting: Interactive slider to set your "Monthly Budget Goal" with real-time metrics showing Total Spent and Remaining Budget.

Visual Analytics:

Spending Trends: Line chart visualizing daily spending spikes.

Category Breakdown: Matplotlib pie chart showing where your money goes (Food, Transport, Entertainment, etc.).

Transaction History: View all logged expenses in a sortable, interactive dataframe.

Bank Import (Demo): Functionality to upload and preview CSV bank statements.

🛠️ Tech Stack
Streamlit: For the interactive web interface.

Pandas: For data manipulation and storage.

Matplotlib: For generating the category pie chart.

📦 Installation & Usage
Clone the repository:

Bash

git clone https://github.com/yourusername/finance-dashboard.git
cd finance-dashboard
Install dependencies:

Bash

pip install streamlit pandas matplotlib
Run the application:

Bash

streamlit run dash.py
View the Dashboard: Open your browser and navigate to the local URL provided in the terminal (usually http://localhost:8501).

📂 File Structure
dash.py: The main application script containing the UI layout, logic, and visualization code.
