# Python Selenium Framework

## Overview
This repository contains a Python-based Selenium testing framework designed for automated testing of web applications. The framework is modular, scalable, and easy to use, enabling effective test automation for various web projects.

<h2>Features</h2>
<ul>
  <li><b>Cross-Browser Testing:</b> Supports multiple browsers like Chrome, Firefox, and Edge.</li>
  <li><b>Page Object Model (POM):</b> Implements POM to organize test scripts and improve maintainability.</li>
  <li><b>Test Reporting:</b> Generates detailed test execution reports.</li>
  <li><b>Data-Driven Testing:</b> Uses external data sources like Excel or CSV for test input.</li>
  <li><b>Reusable Components:</b> Contains reusable functions for common actions like login, form submissions, etc.</li>
  <li><b>Parallel Testing:</b> Supports running tests in parallel for faster execution.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li><b>Programming Language:</b> Python</li>
  <li><b>Testing Framework:</b> Selenium</li>
  <li><b>Test Runner:</b> Pytest</li>
  <li><b>Libraries:</b> pytest-html (for reporting), openpyxl (for Excel data), etc.</li>
</ul>

<h2>Getting Started</h2>
<h3>Prerequisites</h3>
<ul>
  <li>Python 3.x installed</li>
  <li>Google Chrome, Firefox, or Edge installed</li>
  <li>WebDriver for the corresponding browser installed</li>
  <li>Virtual environment setup (recommended)</li>
</ul>

<h3>Installation</h3>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/li-deepa/PythonSelFramework.git</code></pre>
  </li>
  <li>Navigate to the project directory:
    <pre><code>cd PythonSelFramework</code></pre>
  </li>
  <li>Install required dependencies:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
</ol>

<h3>Running the Tests</h3>
<ol>
  <li>Update test configurations in the <code>config</code> file (e.g., browser type, URLs).</li>
  <li>Run the test suite:
    <pre><code>pytest --html=report.html</code></pre>
  </li>
  <li>View the test report in the generated <code>report.html</code> file.</li>
</ol>
