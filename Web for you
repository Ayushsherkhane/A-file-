<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Best Place for You</title>
    <!-- Add the Chart.js library -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        body {
            background-color: #fff; /* White background */
            color: #000; /* Black text */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <h1>Best Place for You</h1>

    <!-- Chart for Brand Names -->
    <canvas id="brandNamesChart" width="400" height="200"></canvas>

    <!-- Chart for Bios -->
    <canvas id="biosChart" width="400" height="200"></canvas>

    <script>
        // Sample data for charts
        var brandNamesData = {
            labels: ["Brand1", "Brand2", "Brand3", "Brand4"],
            datasets: [{
                label: 'Brand Names',
                data: [30, 50, 20, 25],
                backgroundColor: ['rgba(255, 99, 132, 0.2)', 'rgba(54, 162, 235, 0.2)', 'rgba(255, 206, 86, 0.2)', 'rgba(75, 192, 192, 0.2)'],
                borderColor: ['rgba(255, 99, 132, 1)', 'rgba(54, 162, 235, 1)', 'rgba(255, 206, 86, 1)', 'rgba(75, 192, 192, 1)'],
                borderWidth: 1
            }]
        };

        var biosData = {
            labels: ["Brand1", "Brand2", "Brand3", "Brand4"],
            datasets: [{
                label: 'Bios',
                data: [10, 25, 15, 30],
                backgroundColor: ['rgba(255, 99, 132, 0.2)', 'rgba(54, 162, 235, 0.2)', 'rgba(255, 206, 86, 0.2)', 'rgba(75, 192, 192, 0.2)'],
                borderColor: ['rgba(255, 99, 132, 1)', 'rgba(54, 162, 235, 1)', 'rgba(255, 206, 86, 1)', 'rgba(75, 192, 192, 1)'],
                borderWidth: 1
            }]
        };

        // Create charts
        var brandNamesChart = new Chart(document.getElementById('brandNamesChart').getContext('2d'), {
            type: 'bar',
            data: brandNamesData
        });

        var biosChart = new Chart(document.getElementById('biosChart').getContext('2d'), {
            type: 'bar',
            data: biosData
        });
    </script>
</body>
</html>
￼Enter
