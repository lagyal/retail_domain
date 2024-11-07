<h1>Retail and Warehouse Sales Forecasting</h1>

<h2>Project Overview</h2>
<p>This project focuses on analyzing and predicting sales and inventory transfers for a retail and warehouse business. Using machine learning techniques, the goal is to improve demand forecasting, optimize inventory management, and analyze supplier and item-specific sales trends.</p>

<h3>Key Objectives</h3>
<ul>
  <li><strong>Sales Forecasting:</strong> Predict future retail and warehouse sales based on historical data. This is modeled as a <em>Time Series Forecasting</em> problem.</li>
  <li><strong>Demand Prediction:</strong> Estimate the demand for items to optimize inventory levels using the available sales and transfer data.</li>
  <li><strong>Supplier-Item Analysis:</strong> Identify trends in supplier performance, specific item sales, and warehouse transfers to inform logistics and retail strategies.</li>
  <li><strong>Sales Transfer Prediction:</strong> Predict how items are transferred between retail and warehouse locations to maintain balanced inventory levels.</li>
</ul>

<h2>Dataset Details</h2>
<p>The dataset contains sales, transfer, and item information across multiple suppliers, items, and time periods. The key variables used in the analysis are:</p>

<ul>
  <li><strong>YEAR:</strong> Year in which the data was recorded (Categorical or Continuous).</li>
  <li><strong>MONTH:</strong> Month in which the data was recorded (Categorical).</li>
  <li><strong>SUPPLIER:</strong> Supplier providing the product (Categorical).</li>
  <li><strong>ITEM CODE:</strong> Unique identifier for each item/product (Categorical).</li>
  <li><strong>ITEM DESCRIPTION:</strong> Descriptive name of the item (Categorical).</li>
  <li><strong>ITEM TYPE:</strong> Category of the item (e.g., electronics, clothing, food) (Categorical).</li>
  <li><strong>RETAIL SALES (RETAIL SA):</strong> Total retail sales for the item (Continuous).</li>
  <li><strong>RETAIL TRANSFERS (RETAIL TR):</strong> Number of items transferred between retail locations (Continuous).</li>
  <li><strong>WAREHOUSE SALES:</strong> Total sales from the warehouse inventory (Continuous).</li>
</ul>

<h2>Machine Learning Tasks</h2>
<p>The dataset allows for solving multiple machine learning problems, including:</p>

<ul>
  <li><strong>Time Series Forecasting:</strong> Predicting future sales for retail or warehouse items.</li>
  <li><strong>Classification:</strong> Identifying items with high transfer rates or other characteristics to optimize inventory.</li>
  <li><strong>Clustering:</strong> Grouping similar items or suppliers for business insights.</li>
  <li><strong>Regression:</strong> Modeling continuous sales figures for retail and warehouse locations.</li>
  <li><strong>Association Rule Mining (Market Basket Analysis):</strong> Recommending related items based on past sales.</li>
</ul>

<h2>Methodology</h2>
<p>The project workflow follows standard machine learning steps:</p>

<ol>
  <li><strong>Exploratory Data Analysis (EDA):</strong> Data inspection, visualization, and summary statistics to understand trends and patterns.</li>
  <li><strong>Feature Engineering:</strong> Transforming and preparing features for modeling.</li>
  <li><strong>Modeling Pipeline:</strong></li>
  <ul>
    <li>Time Series Forecasting for <em>Inventory Management</em>.</li>
    <li>Regression models for predicting <em>retail sales</em> and <em>warehouse sales</em>.</li>
    <li><em>Clustering</em> techniques to group items/suppliers for analysis.</li>
    <li><em>Principal Component Analysis (PCA)</em> for dimensionality reduction.</li>
    <li>Deep Neural Networks using <em>Multilayer Perceptron (DNN)</em> for prediction tasks.</li>
  </ul>
  <li><strong>Association Rule Mining:</strong> Implementing a recommendation system through Market Basket Analysis.</li>
</ol>

<h2>Results</h2>
<ul>
  <li><strong>Time Series Forecasting:</strong> Completed for inventory management to forecast retail and warehouse sales.</li>
  <li><strong>Regression Models:</strong> Developed to predict sales based on historical data.</li>
  <li><strong>Clustering:</strong> Performed for item and supplier analysis.</li>
  <li><strong>PCA:</strong> Applied for dimensionality reduction to simplify the data.</li>
  <li><strong>Market Basket Analysis:</strong> Recommendations for related products based on transaction data.</li>
</ul>

<h2>License</h2>
<p>This project is licensed under the MIT License - see the <a href="https://opensource.org/license/MIT" target='_blank'>LICENSE</a> file for details.</p>
