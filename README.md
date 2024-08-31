/* Global Styles */

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Open Sans', sans-serif;
  font-size: 14px;
  line-height: 1.5;
  color: #333;
  background-color: #f9f9f9;
}

h1, h2, h3, h4, h5, h6 {
  font-weight: bold;
  color: #333;
  margin-bottom: 10px;
}

h1 {
  font-size: 24px;
  margin-top: 20px;
}

h2 {
  font-size: 18px;
  margin-top: 15px;
}

h3 {
  font-size: 16px;
  margin-top: 10px;
}

p {
  margin-bottom: 15px;
}

a {
  text-decoration: none;
  color: #337ab7;
}

a:hover {
  color: #23527c;
}

/* Dashboard Styles */

.dashboard {
  max-width: 1200px;
  margin: 40px auto;
  padding: 20px;
  background-color: #fff;
  border: 1px solid #ddd;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.dashboard-header {
  background-color: #333;
  color: #fff;
  padding: 10px;
  border-bottom: 1px solid #333;
}

.dashboard-header h1 {
  font-size: 18px;
  margin: 0;
}

.dashboard-content {
  padding: 20px;
}

.dashboard-content h2 {
  font-size: 16px;
  margin-top: 10px;
}

.dashboard-content p {
  margin-bottom: 10px;
}

/* Card Styles */

.card {
  background-color: #fff;
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  margin-bottom: 20px;
}

.card-header {
  background-color: #333;
  color: #fff;
  padding: 10px;
  border-bottom: 1px solid #333;
}

.card-header h2 {
  font-size: 16px;
  margin: 0;
}

.card-content {
  padding: 20px;
}

.card-content p {
  margin-bottom: 10px;
}

/* Button Styles */

.button {
  background-color: #337ab7;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 10px;
  cursor: pointer;
}

.button:hover {
  background-color: #23527c;
}

/* Table Styles */

table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  border: 1px solid #ddd;
  padding: 10px;
  text-align: left;
}

th {
  background-color: #333;
  color: #fff;
}

/* Chart Styles */

.chart {
  width: 100%;
  height: 300px;
  margin-bottom: 20px;
}

.chart canvas {
  width: 100%;
  height: 100%;
}

/* Responsive Styles */

@media (max-width: 768px) {
  .dashboard {
    margin: 20px auto;
  }
  .card {
    margin-bottom: 10px;
  }
}

@media (max-width: 480px) {
  .dashboard {
    margin: 10px auto;
  }
  .card {
    margin-bottom: 5px;
  }
}
