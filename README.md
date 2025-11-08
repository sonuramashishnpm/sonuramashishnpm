<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sonu Kumar - Tech Prodigy from Bihar</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: #333; line-height: 1.6; }
        .container { max-width: 1200px; margin: 0 auto; padding: 20px; }
        header { text-align: center; padding: 40px 0; background: rgba(255,255,255,0.1); border-radius: 20px; margin-bottom: 30px; backdrop-filter: blur(10px); }
        h1 { font-size: 3em; margin: 0; color: #fff; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); }
        .subtitle { font-size: 1.2em; color: #ffd700; margin: 10px 0; }
        .typewriter { border-right: 2px solid #ffd700; white-space: nowrap; overflow: hidden; animation: typing 3s steps(40, end), blink-caret .75s step-end infinite; font-size: 1.5em; color: #fff; }
        @keyframes typing { from { width: 0; } to { width: 100%; } }
        @keyframes blink-caret { from, to { border-color: transparent; } 50% { border-color: #ffd700; } }
        .tabs { display: flex; justify-content: center; margin: 20px 0; flex-wrap: wrap; }
        .tab-button { background: rgba(255,255,255,0.2); color: #fff; border: none; padding: 12px 24px; margin: 5px; border-radius: 25px; cursor: pointer; transition: all 0.3s; font-weight: bold; }
        .tab-button:hover, .tab-button.active { background: #ffd700; color: #333; transform: scale(1.05); }
        .tab-content { display: none; background: rgba(255,255,255,0.95); padding: 30px; border-radius: 15px; margin: 20px 0; box-shadow: 0 10px 30px rgba(0,0,0,0.2); backdrop-filter: blur(5px); }
        .tab-content.active { display: block; animation: fadeIn 0.5s; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 15px; margin: 20px 0; }
        .skill { background: linear-gradient(45deg, #667eea, #764ba2); color: #fff; padding: 15px; border-radius: 10px; text-align: center; transition: transform 0.3s; }
        .skill:hover { transform: rotate(5deg) scale(1.1); }
        .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
        .project-card { background: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); transition: box-shadow 0.3s; }
        .project-card:hover { box-shadow: 0 10px 25px rgba(0,0,0,0.2); }
        .project-link { color: #667eea; text-decoration: none; font-weight: bold; }
        .project-link:hover { text-decoration: underline; }
        .achievements { list-style: none; padding: 0; }
        .achievement { background: #ffd700; margin: 10px 0; padding: 15px; border-radius: 10px; display: flex; align-items: center; transition: background 0.3s; }
        .achievement:hover { background: #ffed4e; }
        .achievement::before { content: "🌟"; margin-right: 10px; font-size: 1.5em; }
        footer { text-align: center; padding: 20px; color: #fff; margin-top: 40px; }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Sonu Kumar</h1>
            <p class="subtitle">Bihar Viral Boy | 14yo Tech Prodigy & Changemaker 🚀</p>
            <div class="typewriter">Building the future, one code at a time – from Bihar to the world!</div>
        </header>

     <div class="tabs">
            <button class="tab-button active" onclick="openTab('about')">About Me</button>
            <button class="tab-button" onclick="openTab('skills')">Tech Stack</button>
            <button class="tab-button" onclick="openTab('projects')">Projects</button>
            <button class="tab-button" onclick="openTab('achievements')">Achievements</button>
            <button class="tab-button" onclick="openTab('connect')">Connect</button>
        </div>

        <div id="about" class="tab-content active">
            <h2>👋 Hey, I'm Sonu!</h2>
            <p>From a small town in Bihar, I've turned curiosity into code. At 14, I'm a self-taught dev passionate about AI, automation, and making education free for all. Viral for my TEDx talk at 13, I've built tools that hack APIs (without keys!), analyze data, and automate the web. Studying on full scholarships at Allen Kota & DDPS Kota, while grinding 10+ hours on projects. Let's collab to build a better world! 💻✨</p>
            <p><strong>Fun Fact:</strong> Summarize Bihar politics in one line: "Stability in political instability" 🗳️</p>
        </div>

        <div id="skills" class="tab-content">
            <h2>🛠️ My Tech Arsenal</h2>
            <div class="skills-grid">
                <div class="skill">Python (Master: OOP, Async, LangChain)</div>
                <div class="skill">Selenium & BeautifulSoup</div>
                <div class="skill">Flask & Streamlit</div>
                <div class="skill">HTML/CSS/JS (DOM Magic)</div>
                <div class="skill">NumPy/Pandas/Matplotlib</div>
                <div class="skill">Solidity Basics (Web3)</div>
                <div class="skill">N8N Automation</div>
                <div class="skill">AI Workflows (No-API Hacks)</div>
            </div>
        </div>

        <div id="projects" class="tab-content">
            <h2>🚀 Featured Projects</h2>
            <div class="projects">
                <div class="project-card">
                    <h3><a href="https://npmexplorer.netlify.app" class="project-link" target="_blank">NPMexplorer</a></h3>
                    <p>Edutainment hub: Free notes, live news, stocks with AI tips, social chats. Built with HTML/CSS/JS.</p>
                    <p><em>1 ⭐ | HTML</em></p>
                </div>
                <div class="project-card">
                    <h3><a href="https://npmdata.streamlit.app" class="project-link" target="_blank">NPM-Analytics</a></h3>
                    <p>Data viz dashboard for analytics—CSV handling, charts with Pandas/Streamlit.</p>
                    <p><em>1 ⭐ | Python</em></p>
                </div>
                <div class="project-card">
                    <h3><a href="https://github.com/sonuramashishnpm/NPMWebAutomation" class="project-link" target="_blank">NPMWebAutomation</a></h3>
                    <p>Selenium-powered Gemini AI queries—no APIs, just web magic for unlimited access.</p>
                    <p><em>1 ⭐ | Python</em></p>
                </div>
                <div class="project-card">
                    <h3><a href="https://github.com/sonuramashishnpm/NPMVoiceAI" class="project-link" target="_blank">NPMVoiceAI</h3>
                    <p>Voice-to-text AI prompts with unlimited tokens—response in voice/text. Pure Python innovation.</p>
                    <p><em>1 ⭐ | Python</em></p>
                </div>
                <div class="project-card">
                    <h3><a href="https://npmexplorer-flask.onrender.com" class="project-link" target="_blank">NPMexplorer-Flask</a></h3>
                    <p>Backend-powered explorer with query handling—Flask routes for dynamic content.</p>
                    <p><em>HTML</em></p>
                </div>
            </div>
            <p><em>More in <a href="https://github.com/sonuramashishnpm?tab=repositories" class="project-link">my repos</a> – npmai lib coming to PyPI soon!</em></p>
        </div>

        <div id="achievements" class="tab-content">
            <h2>🏆 Milestones</h2>
            <ul class="achievements">
                <li>TEDx Speaker at 13: Talked dreams & change – viral inspiration!</li>
                <li>100% Scholarships: Allen Kota + DDPS Kota – from 62% to 75% grades.</li>
                <li>Social Impact: Raised education/liquor ban issues with CM Nitish Kumar.</li>
                <li>398K+ FB Followers: Monetizing tech & social content as "Bihar Viral Boy".</li>
                <li>AI Prodigy: Built no-API LLM chains (ChatGPT/Gemini/Grok) in 6 months.</li>
                <li>Deployed 5+ Apps: From Netlify to Render – shipping daily.</li>
            </ul>
        </div>

        <div id="connect" class="tab-content">
            <h2>🤝 Let's Build Together</h2>
            <p>Got an idea? Collab on AI automations or Bihar edtech? Hit me up!</p>
            <p><strong>Email:</strong> npmdev@explorer.com</p>
            <p><strong>FB:</strong> <a href="https://facebook.com/sonukumar" class="project-link" target="_blank">398K+ Community</a></p>
            <p><strong>LinkedIn/Twitter:</strong> Search "Sonu Kumar Bihar Viral Boy"</p>
            <p><em>Pro Tip: Fork a repo & PR – let's code!</em></p>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Sonu Kumar | Coding my way to the stars 🌟</p>
    </footer>

    <script>
        function openTab(tabName) {
            // Hide all tabs
            var tabContents = document.getElementsByClassName("tab-content");
            for (var i = 0; i < tabContents.length; i++) {
                tabContents[i].classList.remove("active");
            }
            // Remove active from buttons
            var tabButtons = document.getElementsByClassName("tab-button");
            for (var i = 0; i < tabButtons.length; i++) {
                tabButtons[i].classList.remove("active");
            }
            // Show selected
            document.getElementById(tabName).classList.add("active");
            event.currentTarget.classList.add("active");
        }
    </script>
</body>
</html>
