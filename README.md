<h1 style="text-align: center;">Credit Card Financial Dashboard</h1>

<p>This project involves building an insightful and dynamic <strong>Credit Card Financial Dashboard</strong> using <strong>Power BI</strong>. The dashboard offers a comprehensive overview of credit card transactions, customer profiles, and weekly financial reports, making it an invaluable tool for financial analysts and business decision-makers.</p>

<h2>Project Overview</h2>

<p>The <strong>Credit Card Financial Dashboard</strong> is designed to analyze credit card transaction data and customer demographics, providing users with deep insights into financial behavior and trends. Using Power BI, the project visualizes the data in an intuitive and interactive way, enabling users to explore the data across multiple dimensions.</p>

<h3>Key Features</h3>

<ul>
  <li><strong>Transaction Analysis</strong>: Visualize and drill down into individual credit card transactions over time.</li>
  <li><strong>Customer Segmentation</strong>: Analyze customer demographics, such as age, gender, and location, to identify patterns in credit card usage.</li>
  <li><strong>Weekly Financial Overview</strong>: A summary of credit card usage trends over weekly intervals, highlighting key metrics such as total spending, average transaction value, and active customers.</li>
  <li><strong>Dynamic Filtering</strong>: Ability to filter data dynamically by time periods, customer segments, transaction types, and other key variables.</li>
  <li><strong>SQL Query Integration</strong>: Predefined SQL queries that help with data extraction, transformation, and analysis before importing into Power BI.</li>
</ul>

<h2>Dataset Information</h2>

<p>The project utilizes multiple datasets, each serving a unique purpose in the dashboard:</p>
<ul>
  <li><code>credit_card.csv</code>: Contains detailed credit card transaction information, including transaction amounts, dates, and transaction types.</li>
  <li><code>customer.csv</code>: Provides key customer demographic data, such as age, gender, and occupation, which is useful for customer segmentation.</li>
  <li><code>cust_add.csv</code>: Includes additional customer-related data, such as geographic location and relationship length with the credit card company.</li>
  <li><code>cc_add.csv</code>: Additional transaction data, such as transaction category and merchant details, that enriches the insights provided in the dashboard.</li>
</ul>

<h2>Installation and Setup</h2>

<ol>
  <li><strong>Install Power BI Desktop</strong>: Download and install Power BI from the official <a href="https://powerbi.microsoft.com/">Power BI website</a>.</li>
  <li><strong>Clone the repository</strong>: Download this repository to your local machine.
    <pre><code>git clone &lt;repository-url&gt;</code></pre>
  </li>
  <li><strong>Open Power BI</strong>: Launch Power BI Desktop and load the datasets provided in the repository (<code>credit_card.csv</code>, <code>customer.csv</code>, <code>cust_add.csv</code>, <code>cc_add.csv</code>).</li>
  <li><strong>Connect the datasets</strong>: Use the Power BI interface to link the datasets, creating relationships between them to facilitate analysis.</li>
  <li><strong>Customize the dashboard</strong> (Optional): You can modify or extend the dashboard to include additional visualizations or adapt it to other data sources.</li>
</ol>

<h2>SQL Queries</h2>

<p>Included in the project is an SQL file that helps in preprocessing the data before it is loaded into Power BI:</p>

<ul>
  <li><code>SQL Query - Financial Dashboard Data.sql</code>: This file contains SQL queries that can be used to:
    <ul>
      <li>Extract data from larger databases.</li>
      <li>Clean the data by removing duplicates, handling null values, or formatting the data properly.</li>
      <li>Create summary tables or views that can be imported into Power BI for faster querying and visualization.</li>
    </ul>
  </li>
</ul>

<h2>Usage Instructions</h2>

<ol>
  <li><strong>Open Power BI Desktop</strong>: Launch the software and load the <code>.pbix</code> dashboard file if it is included, or start a new Power BI project.</li>
  <li><strong>Load the datasets</strong>: Import the CSV files into Power BI using the "Get Data" option.</li>
  <li><strong>Explore the Dashboard</strong>: Use the interactive filters to view specific transaction types, customer segments, or time periods.</li>
  <li><strong>Customize if needed</strong>: Modify the visualizations, add new data fields, or create additional measures to fit your specific analytical needs.</li>
  <li><strong>Run SQL Queries</strong> (Optional): Use the provided SQL scripts to manage or clean data before loading it into Power BI. This is especially useful if working with large datasets or needing pre-aggregated views.</li>
</ol>

<h2>Contributing</h2>

<p>Contributions are highly welcome! If you find any bugs, have ideas for improvements, or want to contribute new features, feel free to:</p>

<ol>
  <li>Fork the repository.</li>
  <li>Create a new branch (<code>git checkout -b feature-branch</code>).</li>
  <li>Commit your changes (<code>git commit -m 'Add new feature'</code>).</li>
  <li>Push to the branch (<code>git push origin feature-branch</code>).</li>
  <li>Open a pull request.</li>
</ol>

<h2>License</h2>

<p>This project is licensed under the MIT License, meaning you are free to use, modify, and distribute it. See the <code>LICENSE</code> file for more details.</p>
