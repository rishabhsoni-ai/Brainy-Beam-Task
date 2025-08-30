📘 NumPy & Pandas Visualization and Linear Algebra – Tutorial

This repository contains Google Colab–ready Python code demonstrating advanced use of NumPy, Pandas, Matplotlib, and Plotly for data manipulation, visualization, and solving mathematical problems.

🚀 Contents
1️⃣ Data Reshaping with Pandas

Using pivot() and pivot_table() for restructuring data.

Handling duplicates with aggregation functions.

Reversing (unpivoting) with melt().

🔑 Key Functions:
pd.pivot(), pd.pivot_table(), pd.melt()

2️⃣ Custom Colormaps in Matplotlib

Creating gradient colormaps with LinearSegmentedColormap.

Creating discrete colormaps with ListedColormap.

Using normalization (TwoSlopeNorm) to center data around zero.

🔑 Key Functions:
LinearSegmentedColormap.from_list(), ListedColormap(), imshow(), contourf()

3️⃣ Custom NumPy Data Types

Defining structured dtypes using np.dtype().

Creating arrays with multiple named fields.

Accessing fields individually (array['field']).

Performing operations (e.g., average marks, filtering).

Nested dtypes for hierarchical structures.

🔑 Key Functions:
np.dtype(), structured arrays, nested dtype access

4️⃣ Solving Systems of Linear Equations

Representing systems in matrix form A·X = B.

Solving with np.linalg.solve().

Verifying solutions using matrix multiplication.

Handling overdetermined systems with least squares (np.linalg.lstsq).

Visualizing 2-variable systems with Matplotlib.

🔑 Key Functions:
np.linalg.solve(), np.linalg.lstsq(), matplotlib line plots

5️⃣ Parallel Coordinates Plot

Visualizing high-dimensional data.

Using pandas.plotting.parallel_coordinates (static).

Using plotly.express.parallel_coordinates (interactive).

🔑 Key Functions:
parallel_coordinates(), plotly.express.parallel_coordinates()

🛠️ Requirements

This project uses Python with the following libraries:

pip install numpy pandas matplotlib plotly

▶️ Running in Google Colab

Open Google Colab
.

Upload the .ipynb file or copy-paste the provided code cells.

Run each cell step by step to explore reshaping, custom visualization, dtypes, and linear algebra.

📊 Example Outputs

Pivot Table: Rearranges rows & columns with aggregation.

Custom Colormap: Beautiful gradient & discrete colormaps.

Structured NumPy Arrays: Store heterogeneous data like students or employees.

Linear Equations: Solve & verify systems (2D, 3D, least squares).

Parallel Coordinates: Visualize multi-dimensional datasets.

✨ Author

Created by Rishabh Soni — for practicing Python, NumPy, Pandas, and Visualization concepts.

📬 Connect with Me

💼 LinkedIn: [https://www.linkedin.com/in/rishabh-soni-11dec2004/]

🐙 GitHub: [https://github.com/RishabhSoni11]

📧 Email: [rahulsoninke786@gmail.com]

🌐 Portfolio: [https://rishabhsoni11.github.io/My_Portfolio.github.io/]
