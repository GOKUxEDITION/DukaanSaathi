# DukaanSaathi
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DukaanSaathi - Modern Retail Management Solution</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --accent-color: #38bdf8;
            --text-color: #f8fafc;
            --text-muted: #94a3b8;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
        }
        .header {
            text-align: center;
            padding: 40px 0;
            border-bottom: 1px solid #334155;
        }
        .header h1 {
            font-size: 2.5rem;
            color: var(--accent-color);
            margin-bottom: 10px;
        }
        .badges {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-top: 15px;
            flex-wrap: wrap;
        }
        .badge {
            background: #334155;
            padding: 5px 12px;
            border-radius: 15px;
            font-size: 0.85rem;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        .card {
            background: var(--card-bg);
            padding: 20px;
            border-radius: 10px;
            border: 1px solid #334155;
        }
        .card h3 {
            color: var(--accent-color);
            margin-top: 0;
        }
        .btn {
            display: inline-block;
            background: var(--accent-color);
            color: #0f172a;
            font-weight: bold;
            padding: 10px 20px;
            border-radius: 6px;
            text-decoration: none;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🛒 DukaanSaathi</h1>
            <p>Smart Business & Store Management Solution</p>
            <div class="badges">
                <span class="badge">🚀 Fast Performance</span>
                <span class="badge">🔒 Secure</span>
                <span class="badge">⚡ 99.9% Uptime</span>
            </div>
        </div>

        <div class="grid">
            <div class="card">
                <h3>📦 Inventory Tracker</h3>
                <p>Real-time stock management and automated stock alerts for local vendors.</p>
            </div>
            <div class="card">
                <h3>📊 Sales Analytics</h3>
                <p>Detailed insight reports on daily transactions and top-selling items.</p>
            </div>
            <div class="card">
                <h3>💬 Customer Ledger</h3>
                <p>Digital Udhar/Khata tracking with automated SMS reminders.</p>
            </div>
        </div>

        <div class="card" style="text-align: center;">
            <h3>Quick Deployment</h3>
            <p>Deploy your DukaanSaathi instance with one click.</p>
            <a href="#" class="btn">Deploy to Heroku</a>
        </div>
    </div>
</body>
</html>
