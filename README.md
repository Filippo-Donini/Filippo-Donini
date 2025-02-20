<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/js/all.min.js"></script>
    <style>
        :root {
            --primary-color: #0366d6;
            --text-color: #24292e;
            --bg-color: #ffffff;
            --card-bg: #f6f8fa;
            --border-color: #e1e4e8;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: var(--bg-color);
        }

        .header {
            margin-bottom: 2rem;
        }

        .intro {
            font-size: 1.1rem;
            margin-bottom: 2rem;
        }

        h1, h2 {
            color: var(--primary-color);
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 0.5rem;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-bottom: 2rem;
        }

        .project-card {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 6px;
            padding: 1.5rem;
            transition: transform 0.2s;
        }

        .project-card:hover {
            transform: translateY(-4px);
        }

        .project-title {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            margin-bottom: 1rem;
            color: var(--primary-color);
            font-size: 1.2rem;
            font-weight: 600;
        }

        .tech-stack {
            margin-top: 1rem;
            font-size: 0.9rem;
            color: #586069;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-bottom: 2rem;
        }

        .skill-category {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 6px;
            padding: 1rem;
            flex: 1;
            min-width: 200px;
        }

        .skill-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .learning {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 6px;
            padding: 1.5rem;
        }

        .learning ul {
            list-style: none;
            padding: 0;
        }

        .learning li {
            margin-bottom: 0.5rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        a {
            color: var(--primary-color);
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Hi there! 👋</h1>
        <p class="intro">I'm a software developer passionate about building data-driven applications and tools that make complex analysis accessible. My work spans across bioinformatics, sports analytics, and financial technology.</p>
    </div>

    <h2>🚀 Featured Projects</h2>
    <div class="projects">
        <div class="project-card">
            <div class="project-title">
                <i class="fas fa-dna"></i>
                Mitochondrial DNA Analysis Tool
            </div>
            <p>A comprehensive web application for analyzing DNA and aminoacids sequences, built with Python and Streamlit.</p>
            <ul>
                <li>Supports FASTA file parsing and visualization</li>
                <li>Performs sequence analysis and motif identification</li>
                <li>Features interactive visualizations and alignment tools</li>
            </ul>
            <div class="tech-stack">
                <strong>Tech stack:</strong> Python, Streamlit, BioPython, Pandas
            </div>
            <p><a href="https://dna-analysis-tool.streamlit.app/" target="_blank">View Project →</a></p>
        </div>

        <div class="project-card">
            <div class="project-title">
                <i class="fas fa-tennis-ball"></i>
                Tennis Stats Explorer
            </div>
            <p>A FastAPI-powered web application for tennis statistics and analysis.</p>
            <ul>
                <li>Real-time ATP/WTA rankings</li>
                <li>Head-to-head player comparisons</li>
                <li>Comprehensive match statistics</li>
            </ul>
            <div class="tech-stack">
                <strong>Tech stack:</strong> FastAPI, AWS EC2, RDS, PostgreSQL
            </div>
            <p><a href="http://44.201.186.157:8000" target="_blank">Live Demo →</a></p>
        </div>

        <div class="project-card">
            <div class="project-title">
                <i class="fab fa-bitcoin"></i>
                Crypto Trading Simulator
            </div>
            <p>A real-time cryptocurrency trading simulator with multiple strategy implementations.</p>
            <ul>
                <li>Live BTC/USDT price tracking</li>
                <li>Implementation of various trading strategies (MA, RSI, MACD)</li>
                <li>Performance metrics and backtesting</li>
            </ul>
            <div class="tech-stack">
                <strong>Tech stack:</strong> Python, Streamlit, Plotly, binance API
            </div>
            <p><a href="https://github.com/lebondon/bot_trading_binance" target="_blank">View on GitHub →</a></p>
        </div>
    </div>

    <h2>💻 Technical Skills</h2>
    <div class="skills">
        <div class="skill-category">
            <h3>Languages</h3>
            <ul class="skill-list">
                <li>Python</li>
                <li>SQL</li>
            </ul>
        </div>
        <div class="skill-category">
            <h3>Web Frameworks</h3>
            <ul class="skill-list">
                <li>FastAPI</li>
                <li>Streamlit</li>
                <li>jinja2</li>
            </ul>
        </div>
        <div class="skill-category">
            <h3>Data Analysis</h3>
            <ul class="skill-list">
                <li>Pandas</li>
                <li>Polars</li>
                <li>NumPy</li>
                <li>Plotly</li>
                <li>sklearn</li>
            </ul>
        </div>
        <div class="skill-category">
            <h3>Cloud & Database</h3>
            <ul class="skill-list">
                <li>PostgreSQL</li>
                <li>AWS (EC2, RDS, S3)</li>
            </ul>
        </div>
    </div>

    <h2>🌱 Currently Learning</h2>
    <div class="learning">
        <ul>
            <li><i class="fas fa-cloud"></i> Advanced AWS Services</li>
            <li><i class="fas fa-brain"></i> Machine Learning Applications</li>
            <li><i class="fas fa-chart-line"></i> Algorithmic Trading Strategies</li>
        </ul>
    </div>
</body>
</html>
