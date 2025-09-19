<!DOCTYPE html>
<html>
<body>

<div align="center">
  <h1>AdGenius - Smarter Way to Read Ads Data</h1>
</div>

<p><b>AdGenius</b> is a lightweight automation tool designed to guide marketers through the entire reporting journey—from pulling campaign data directly from Google Ads to creating analysis-ready Excel sheets without manual effort. The core of the project is a "One-Click Report Generator" that delivers fresh, clean data into Excel dashboards.</p>

<hr>

<h2>🎯 Problem Statement</h2>
<p>To solve the challenge of <strong>automating the workflow from Google Ads to Excel reports for analysis</strong>. Our goal is to replace manual, repetitive report downloads with a single, flexible, and automated system.</p>

<hr>

<h2>✨ Core Features</h2>
<ul>
  <li><strong>Automated Data Fetch:</strong> Eliminates manual downloads by using a Python engine to connect directly to the Google Ads API (GAQL) and fetch key metrics like clicks, impressions, cost, and conversions.</li>
  <li><strong>Smart Data Processing:</strong> Ensures data is clean and structured. The Pandas module handles missing values, cleans raw data, and calculates essential KPIs such as CTR, CPC, and ROI.</li>
  <li><strong>Historical Data Storage & Trends:</strong> Enables long-term reporting by saving processed datasets into SQLite or CSV files, preserving historical performance for trend analysis.</li>
  <li><strong>Excel Report Generator:</strong> Provides visually rich, ready-to-use reports. An Excel Reporting Layer automatically fills pre-designed templates with tables, charts, and dashboards.</li>
  <li><strong>Scheduled Automation & Sharing:</strong> Saves time and improves collaboration by using a scheduler (like Cron) to automatically refresh reports and distribute them via email or shared drives.</li>
</ul>

<hr>

<h2>⚙️ System Architecture</h2>
<p>The tool runs on two main components that work together to create a seamless flow:</p>
<ol>
  <li><strong>Data Engine (API + Processing):</strong> This engine connects to the Google Ads API to fetch campaign metrics. It then uses Pandas to process the raw data into clean, usable datasets.</li>
  <li><strong>Report Engine (Excel Automation):</strong> This engine takes the clean data and automatically populates pre-designed Excel templates with tables, KPIs, and charts. Reports can be refreshed on a schedule or on-demand.</li>
</ol>



<hr>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li><strong>Core Engine:</strong> Python</li>
  <li><strong>Data Source:</strong> Google Ads API (GAQL)</li>
  <li><strong>Data Processing:</strong> Pandas</li>
  <li><strong>Data Storage:</strong> SQLite / CSV</li>
  <li><strong>Reporting Layer:</strong> OpenPyXL / XlsxWriter</li>
  <li><strong>Automation & Scheduling:</strong> Cron jobs / Task Scheduler</li>
</ul>

<hr>

<h2>🏆 Key Benefits</h2>
<ul>
  <li><strong>Time Savings:</strong> Reduces hours of manual copy-pasting into seconds.</li>
  <li><strong>Error-Free Reports:</strong> Delivers consistent, accurate, and up-to-date data.</li>
  <li><strong>Instant Insights:</strong> Provides fresh data in ready-to-use Excel dashboards for smarter campaign decisions.</li>
  <li><strong>End-to-End Automation:</strong> Handles the entire process from data fetching to report formatting in one flow.</li>
  <li><strong>Scalability & Collaboration:</strong> Works for individuals, agencies, or large enterprises and makes sharing reports easy.</li>
</ul>

<hr>

<h2>🧑‍💻 The Team: TriFusion</h2>
<ul>
    <li>Nisha</li>
    <li>Swapnil</li>
    <li>Aditya</li>
</ul>

<hr>
<div>
<b>License</b>
  <br>
This project is licensed under the MIT License - see the LICENSE file for details.
</div>
<hr>
<div align="center">
  <p><em>Project for the CODE VERSE HACKATHON 2025</em></p>
</div>

</body>
</html>
