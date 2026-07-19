<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xylo — Hollow Knight Discord Bot</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --void-black: #050508;
            --deep-blue: #0a0e1a;
            --pale-ghost: #d4dae6;
            --faded-blue: #6b7c9e;
            --hollow-gold: #c9a84c;
            --hollow-gold-dim: #8a7340;
            --infection-orange: #b85c38;
            --mask-white: #e8e8e8;
            --glass: rgba(15, 20, 35, 0.65);
            --glass-border: rgba(201, 168, 76, 0.15);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Inter', sans-serif;
            background: var(--void-black);
            color: var(--pale-ghost);
            overflow-x: hidden;
            line-height: 1.6;
        }

        /* ─── Animated Background ─── */
        .bg-void {
            position: fixed;
            inset: 0;
            z-index: -2;
            background: radial-gradient(ellipse at bottom, var(--deep-blue) 0%, var(--void-black) 70%);
        }

        .particles {
            position: fixed;
            inset: 0;
            z-index: -1;
            overflow: hidden;
            pointer-events: none;
        }

        .particle {
            position: absolute;
            width: 2px;
            height: 2px;
            background: var(--hollow-gold);
            border-radius: 50%;
            opacity: 0;
            animation: floatUp linear infinite;
            box-shadow: 0 0 6px var(--hollow-gold);
        }

        @keyframes floatUp {
            0% { transform: translateY(100vh) scale(0); opacity: 0; }
            10% { opacity: 0.6; }
            90% { opacity: 0.6; }
            100% { transform: translateY(-10vh) scale(1.2); opacity: 0; }
        }

        /* ─── Navigation ─── */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            padding: 1.2rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: linear-gradient(to bottom, rgba(5,5,8,0.9), transparent);
            z-index: 1000;
            backdrop-filter: blur(8px);
        }

        .logo {
            font-family: 'Cinzel', serif;
            font-size: 1.5rem;
            color: var(--hollow-gold);
            text-decoration: none;
            letter-spacing: 2px;
            transition: all 0.3s ease;
            text-shadow: 0 0 20px rgba(201,168,76,0.3);
        }

        .logo:hover {
            text-shadow: 0 0 30px rgba(201,168,76,0.6);
            transform: translateY(-2px);
        }

        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
        }

        .nav-links a {
            color: var(--faded-blue);
            text-decoration: none;
            font-size: 0.9rem;
            font-weight: 500;
            letter-spacing: 1px;
            text-transform: uppercase;
            position: relative;
            transition: color 0.3s;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -4px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--hollow-gold);
            transition: width 0.3s ease;
            box-shadow: 0 0 8px var(--hollow-gold);
        }

        .nav-links a:hover {
            color: var(--pale-ghost);
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        /* ─── Hero Section ─── */
        .hero {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 2rem;
            position: relative;
        }

        .hero h1 {
            font-family: 'Cinzel', serif;
            font-size: clamp(3rem, 8vw, 6rem);
            color: var(--mask-white);
            text-shadow: 0 0 40px rgba(201,168,76,0.2);
            margin-bottom: 1rem;
            animation: fadeInUp 1s ease;
            letter-spacing: 4px;
        }

        .hero p {
            font-size: 1.2rem;
            color: var(--faded-blue);
            max-width: 600px;
            margin-bottom: 2.5rem;
            animation: fadeInUp 1s ease 0.2s both;
        }

        .btn-group {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
            justify-content: center;
            animation: fadeInUp 1s ease 0.4s both;
        }

        .btn {
            padding: 0.9rem 2.2rem;
            border: 1px solid var(--glass-border);
            background: var(--glass);
            color: var(--pale-ghost);
            text-decoration: none;
            font-family: 'Cinzel', serif;
            font-size: 0.95rem;
            letter-spacing: 2px;
            cursor: pointer;
            position: relative;
            overflow: hidden;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            backdrop-filter: blur(10px);
        }

        .btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(201,168,76,0.2), transparent);
            transition: left 0.6s;
        }

        .btn:hover {
            border-color: var(--hollow-gold);
            box-shadow: 0 0 30px rgba(201,168,76,0.2), inset 0 0 20px rgba(201,168,76,0.05);
            transform: translateY(-3px) scale(1.02);
            color: var(--hollow-gold);
        }

        .btn:hover::before {
            left: 100%;
        }

        .btn-primary {
            background: rgba(201,168,76,0.1);
            border-color: var(--hollow-gold-dim);
        }

        /* ─── Section Styles ─── */
        section {
            padding: 6rem 5%;
            max-width: 1200px;
            margin: 0 auto;
            position: relative;
        }

        .section-title {
            font-family: 'Cinzel', serif;
            font-size: 2.5rem;
            color: var(--hollow-gold);
            margin-bottom: 1rem;
            text-align: center;
            position: relative;
            display: inline-block;
            left: 50%;
            transform: translateX(-50%);
        }

        .section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 2px;
            background: var(--hollow-gold);
            margin: 0.5rem auto 0;
            box-shadow: 0 0 10px var(--hollow-gold);
            transition: width 0.4s;
        }

        .section-title:hover::after {
            width: 100px;
        }

        .section-sub {
            text-align: center;
            color: var(--faded-blue);
            margin-bottom: 3rem;
            font-size: 1.05rem;
        }

        /* ─── Feature Cards ─── */
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .feature-card {
            background: var(--glass);
            border: 1px solid var(--glass-border);
            padding: 2rem;
            position: relative;
            overflow: hidden;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            backdrop-filter: blur(8px);
            cursor: default;
        }

        .feature-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--hollow-gold), transparent);
            transform: translateX(-100%);
            transition: transform 0.6s;
        }

        .feature-card:hover {
            transform: translateY(-8px) rotateX(2deg);
            border-color: rgba(201,168,76,0.4);
            box-shadow: 0 20px 40px rgba(0,0,0,0.4), 0 0 30px rgba(201,168,76,0.1);
        }

        .feature-card:hover::before {
            transform: translateX(100%);
        }

        .feature-icon {
            font-size: 2rem;
            margin-bottom: 1rem;
            display: block;
            transition: transform 0.3s;
        }

        .feature-card:hover .feature-icon {
            transform: scale(1.2) rotate(-5deg);
        }

        .feature-card h3 {
            font-family: 'Cinzel', serif;
            color: var(--pale-ghost);
            margin-bottom: 0.5rem;
            font-size: 1.2rem;
        }

        .feature-card p {
            color: var(--faded-blue);
            font-size: 0.95rem;
        }

        /* ─── Commands Section ─── */
        .cmd-search {
            width: 100%;
            max-width: 500px;
            margin: 0 auto 2rem;
            position: relative;
        }

        .cmd-search input {
            width: 100%;
            padding: 1rem 1.5rem;
            background: var(--glass);
            border: 1px solid var(--glass-border);
            color: var(--pale-ghost);
            font-family: 'Inter', sans-serif;
            font-size: 1rem;
            outline: none;
            transition: all 0.3s;
            backdrop-filter: blur(8px);
        }

        .cmd-search input:focus {
            border-color: var(--hollow-gold);
            box-shadow: 0 0 20px rgba(201,168,76,0.15);
        }

        .cmd-search input::placeholder {
            color: var(--faded-blue);
        }

        .cmd-categories {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            justify-content: center;
            margin-bottom: 2rem;
        }

        .cat-btn {
            padding: 0.5rem 1.2rem;
            background: transparent;
            border: 1px solid var(--glass-border);
            color: var(--faded-blue);
            cursor: pointer;
            font-family: 'Inter', sans-serif;
            font-size: 0.85rem;
            letter-spacing: 1px;
            text-transform: uppercase;
            transition: all 0.3s;
        }

        .cat-btn:hover, .cat-btn.active {
            border-color: var(--hollow-gold);
            color: var(--hollow-gold);
            box-shadow: 0 0 15px rgba(201,168,76,0.15);
            transform: translateY(-2px);
        }

        .commands-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1rem;
        }

        .cmd-item {
            background: var(--glass);
            border: 1px solid var(--glass-border);
            padding: 1.2rem;
            transition: all 0.35s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
            backdrop-filter: blur(6px);
        }

        .cmd-item::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 1px;
            background: var(--hollow-gold);
            transition: width 0.4s;
            box-shadow: 0 0 8px var(--hollow-gold);
        }

        .cmd-item:hover {
            transform: translateX(6px) scale(1.01);
            border-color: rgba(201,168,76,0.3);
            background: rgba(201,168,76,0.03);
        }

        .cmd-item:hover::after {
            width: 100%;
        }

        .cmd-name {
            font-family: 'Cinzel', serif;
            color: var(--hollow-gold);
            font-size: 1rem;
            margin-bottom: 0.3rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .cmd-aliases {
            font-size: 0.75rem;
            color: var(--faded-blue);
            opacity: 0.7;
        }

        .cmd-desc {
            font-size: 0.9rem;
            color: var(--pale-ghost);
            opacity: 0.8;
            margin-top: 0.3rem;
        }

        .hidden-cmd {
            display: none;
        }

        /* ─── Legal Pages ─── */
        .legal-container {
            background: var(--glass);
            border: 1px solid var(--glass-border);
            padding: 3rem;
            max-width: 900px;
            margin: 0 auto;
            backdrop-filter: blur(8px);
            position: relative;
            overflow: hidden;
        }

        .legal-container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 1px;
            background: linear-gradient(90deg, transparent, var(--hollow-gold), transparent);
        }

        .legal-container h2 {
            font-family: 'Cinzel', serif;
            color: var(--hollow-gold);
            margin: 2rem 0 1rem;
            font-size: 1.5rem;
        }

        .legal-container h2:first-child {
            margin-top: 0;
        }

        .legal-container p {
            color: var(--pale-ghost);
            opacity: 0.85;
            margin-bottom: 1rem;
            text-align: justify;
        }

        .legal-container ul {
            margin-left: 1.5rem;
            margin-bottom: 1rem;
            color: var(--pale-ghost);
            opacity: 0.85;
        }

        .legal-container li {
            margin-bottom: 0.5rem;
        }

        .placeholder-notice {
            background: rgba(184, 92, 56, 0.1);
            border-left: 3px solid var(--infection-orange);
            padding: 1rem;
            margin: 1.5rem 0;
            color: var(--infection-orange);
            font-size: 0.9rem;
            font-style: italic;
        }

        /* ─── Footer ─── */
        footer {
            text-align: center;
            padding: 3rem 2rem;
            border-top: 1px solid var(--glass-border);
            color: var(--faded-blue);
            font-size: 0.9rem;
            margin-top: 4rem;
        }

        footer a {
            color: var(--hollow-gold);
            text-decoration: none;
            transition: all 0.3s;
        }

        footer a:hover {
            text-shadow: 0 0 10px rgba(201,168,76,0.4);
        }

        /* ─── Scroll Animations ─── */
        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* ─── Responsive ─── */
        @media (max-width: 768px) {
            .nav-links { display: none; }
            .hero h1 { font-size: 2.5rem; }
            .legal-container { padding: 1.5rem; }
            section { padding: 4rem 1.5rem; }
        }

        /* ─── Custom Scrollbar ─── */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: var(--void-black); }
        ::-webkit-scrollbar-thumb { background: var(--hollow-gold-dim); border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: var(--hollow-gold); }
    </style>
</head>
<body>

    <div class="bg-void"></div>
    <div class="particles" id="particles"></div>

    <nav>
        <a href="#" class="logo">XYLO</a>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#features">Features</a></li>
            <li><a href="#commands">Commands</a></li>
            <li><a href="#terms">Terms</a></li>
            <li><a href="#privacy">Privacy</a></li>
        </ul>
    </nav>

    <!-- HOME / HERO -->
    <section class="hero" id="home">
        <h1>XYLO</h1>
        <p>A Hollow Knight inspired Discord bot forged for moderation, utility, voice channels, and fun. No cost, no bloat — just a reliable vessel for your server.</p>
        <div class="btn-group">
            <a href="https://discord.com/oauth2/authorize?client_id=1524730372087091311&permissions=8&scope=bot%20applications.commands" class="btn btn-primary" target="_blank">Invite to Server</a>
            <a href="#commands" class="btn">View Commands</a>
            <a href="https://discord.gg/HPPX5ar68n" class="btn" target="_blank">Support Server</a>
        </div>
    </section>

    <!-- FEATURES -->
    <section id="features">
        <h2 class="section-title reveal">Vessel Abilities</h2>
        <p class="section-sub reveal">Everything you need to rule your Hallownest.</p>
        
        <div class="features">
            <div class="feature-card reveal">
                <span class="feature-icon">🛡️</span>
                <h3>Moderation</h3>
                <p>Ban, kick, mute, warn, jail, purge, and lockdown with hierarchical checks and clean embed logging.</p>
            </div>
            <div class="feature-card reveal">
                <span class="feature-icon">🎭</span>
                <h3>Role & Channel Tools</h3>
                <p>Create, rename, color, and mass-assign roles. Manage channels and categories with ease.</p>
            </div>
            <div class="feature-card reveal">
                <span class="feature-icon">🔊</span>
                <h3>VoiceMaster</h3>
                <p>Hub-based temporary voice channels users can rename, lock, permit, deny, kick, and claim.</p>
            </div>
            <div class="feature-card reveal">
                <span class="feature-icon">🎯</span>
                <h3>Snipe & Utility</h3>
                <p>Recover deleted messages, removed reactions, and edits. AFK system, timezones, and user info.</p>
            </div>
            <div class="feature-card reveal">
                <span class="feature-icon">🎨</span>
                <h3>Image & Quotes</h3>
                <p>Convert images to GIFs and generate beautiful quote cards from message replies with live customization.</p>
            </div>
            <div class="feature-card reveal">
                <span class="feature-icon">✨</span>
                <h3>Fun Ratings</h3>
                <p>Rate your members on how goated, cringe, sigma, delulu, gyat, or mewing they are.</p>
            </div>
        </div>
    </section>

    <!-- COMMANDS -->
    <section id="commands">
        <h2 class="section-title reveal">Command Nail Arts</h2>
        <p class="section-sub reveal">Search or filter by category. Hover over a command to see it awaken.</p>

        <div class="cmd-search reveal">
            <input type="text" id="cmdInput" placeholder="Search commands... (e.g. 'ban', 'voice', 'role')">
        </div>

        <div class="cmd-categories reveal" id="catFilters">
            <button class="cat-btn active" data-cat="all">All</button>
            <button class="cat-btn" data-cat="moderation">Moderation</button>
            <button class="cat-btn" data-cat="roles">Roles</button>
            <button class="cat-btn" data-cat="channels">Channels</button>
            <button class="cat-btn" data-cat="utility">Utility</button>
            <button class="cat-btn" data-cat="voicemaster">VoiceMaster</button>
            <button class="cat-btn" data-cat="fun">Fun</button>
        </div>

        <div class="commands-grid" id="commandsGrid">
            <!-- Moderation -->
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">ban <span class="cmd-aliases">b</span></div>
                <div class="cmd-desc">Ban a member from the server with optional reason.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">kick <span class="cmd-aliases">k</span></div>
                <div class="cmd-desc">Kick a member from the server.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">unban</div>
                <div class="cmd-desc">Unban a user by their ID.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">mute <span class="cmd-aliases">to, timeout</span></div>
                <div class="cmd-desc">Timeout a member for a duration (e.g. 10m, 1h, 1d).</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">unmute <span class="cmd-aliases">uto, untimeout</span></div>
                <div class="cmd-desc">Remove a member's timeout.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">warn <span class="cmd-aliases">w</span></div>
                <div class="cmd-desc">Warn a member with a reason.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">warns</div>
                <div class="cmd-desc">View a member's warning count and latest warning.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">warnhistory</div>
                <div class="cmd-desc">View a member's full warning history.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">removewarn <span class="cmd-aliases">rw</span></div>
                <div class="cmd-desc">Remove the oldest warning from a member.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">jail <span class="cmd-aliases">j</span></div>
                <div class="cmd-desc">Restrict a member to a single jail channel. Subcommands: setup, channel, role, remove, list, reset.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">unjail</div>
                <div class="cmd-desc">Remove a member from jail.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">lock <span class="cmd-aliases">lockchannel, lc</span></div>
                <div class="cmd-desc">Lock the current channel from sending messages.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">unlock <span class="cmd-aliases">unlockchannel, ulc</span></div>
                <div class="cmd-desc">Unlock the current channel.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">lockdown <span class="cmd-aliases">serverlock</span></div>
                <div class="cmd-desc">Lock every text channel in the server.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">unlockdown <span class="cmd-aliases">serverunlock</span></div>
                <div class="cmd-desc">Unlock every text channel in the server.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">slowmode <span class="cmd-aliases">slow</span></div>
                <div class="cmd-desc">Set slowmode using preset levels 1-14.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">nickname <span class="cmd-aliases">nick, n</span></div>
                <div class="cmd-desc">Change a member's nickname.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">forcenickname <span class="cmd-aliases">forcenick, fn</span></div>
                <div class="cmd-desc">Force a nickname that persists even if the user changes it.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">purge <span class="cmd-aliases">p</span></div>
                <div class="cmd-desc">Delete messages by amount, user, time, or reactions.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">cleanup <span class="cmd-aliases">cu</span></div>
                <div class="cmd-desc">Bulk-delete bot commands and bot messages within a duration.</div>
            </div>
            <div class="cmd-item" data-cat="moderation">
                <div class="cmd-name">clearsnipes <span class="cmd-aliases">cs</span></div>
                <div class="cmd-desc">Clear the snipe history for the current channel.</div>
            </div>

            <!-- Roles -->
            <div class="cmd-item" data-cat="roles">
                <div class="cmd-name">roles <span class="cmd-aliases">rolelist</span></div>
                <div class="cmd-desc">List all server roles with member counts.</div>
            </div>
            <div class="cmd-item" data-cat="roles">
                <div class="cmd-name">role <span class="cmd-aliases">r</span></div>
                <div class="cmd-desc">Give/remove a role, or use subcommands: create, rename, color, delete, info, all.</div>
            </div>
            <div class="cmd-item" data-cat="roles">
                <div class="cmd-name">joinrole <span class="cmd-aliases">joinroles</span></div>
                <div class="cmd-desc">Manage roles automatically assigned to new members.</div>
            </div>

            <!-- Channels -->
            <div class="cmd-item" data-cat="channels">
                <div class="cmd-name">channel <span class="cmd-aliases">ch</span></div>
                <div class="cmd-desc">Manage text channels: create, delete, rename, clone.</div>
            </div>
            <div class="cmd-item" data-cat="channels">
                <div class="cmd-name">category <span class="cmd-aliases">cat</span></div>
                <div class="cmd-desc">Manage categories: create, delete, rename, clone.</div>
            </div>

            <!-- Utility -->
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">prefix</div>
                <div class="cmd-desc">Change the server's command prefix.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">selfprefix <span class="cmd-aliases">sprefix</span></div>
                <div class="cmd-desc">Set or remove your personal prefix.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">timezone <span class="cmd-aliases">tz</span></div>
                <div class="cmd-desc">Show or set your timezone by city or GMT offset.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">snipe <span class="cmd-aliases">s</span></div>
                <div class="cmd-desc">View recently deleted messages.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">reactionsnipe <span class="cmd-aliases">rs</span></div>
                <div class="cmd-desc">View recently removed reactions.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">editsnipe <span class="cmd-aliases">es</span></div>
                <div class="cmd-desc">View recently edited messages.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">afk <span class="cmd-aliases">a</span></div>
                <div class="cmd-desc">Set an AFK status with an optional reason.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">userinfo <span class="cmd-aliases">ui</span></div>
                <div class="cmd-desc">Show user info: avatar, banner, join date, roles, and more.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">avatar <span class="cmd-aliases">pfp</span></div>
                <div class="cmd-desc">Display a user's avatar in full resolution.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">banner <span class="cmd-aliases">bn</span></div>
                <div class="cmd-desc">Display a user's profile banner.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">serveravatar <span class="cmd-aliases">spfp</span></div>
                <div class="cmd-desc">Display a user's server-specific avatar.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">serverbanner <span class="cmd-aliases">sbn</span></div>
                <div class="cmd-desc">Display a user's server-specific banner.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">owner <span class="cmd-aliases">own</span></div>
                <div class="cmd-desc">Show the server owner.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">servericon <span class="cmd-aliases">sicon</span></div>
                <div class="cmd-desc">Show the server's icon.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">guildbanner <span class="cmd-aliases">gbn</span></div>
                <div class="cmd-desc">Show the server's banner.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">gif <span class="cmd-aliases">img2gif</span></div>
                <div class="cmd-desc">Convert an attached/replied image into a GIF.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">quote</div>
                <div class="cmd-desc">Reply to a message to generate a styled quote image.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">help <span class="cmd-aliases">h</span></div>
                <div class="cmd-desc">Show the interactive help menu or details on a command.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">commands <span class="cmd-aliases">cmds</span></div>
                <div class="cmd-desc">Paginated list of all available commands.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">describe <span class="cmd-aliases">desc</span></div>
                <div class="cmd-desc">Show detailed syntax and usage for a specific command.</div>
            </div>
            <div class="cmd-item" data-cat="utility">
                <div class="cmd-name">alias</div>
                <div class="cmd-desc">Create per-server custom command aliases. Subcommands: add, remove, list.</div>
            </div>

            <!-- VoiceMaster -->
            <div class="cmd-item" data-cat="voicemaster">
                <div class="cmd-name">voicemaster <span class="cmd-aliases">vm</span></div>
                <div class="cmd-desc">Set the hub voice channel for temporary channels.</div>
            </div>
            <div class="cmd-item" data-cat="voicemaster">
                <div class="cmd-name">vmrename</div>
                <div class="cmd-desc">Rename your temporary voice channel.</div>
            </div>
            <div class="cmd-item" data-cat="voicemaster">
                <div class="cmd-name">vmlock</div>
                <div class="cmd-desc">Lock your temporary voice channel.</div>
            </div>
            <div class="cmd-item" data-cat="voicemaster">
                <div class="cmd-name">vmunlock</div>
                <div class="cmd-desc">Unlock your temporary voice channel.</div>
            </div>
            <div class="cmd-item" data-cat="voicemaster">
                <div class="cmd-name">vmpermit</div>
                <div class="cmd-desc">Allow a user to join your locked voice channel.</div>
            </div>
            <div class="cmd-item" data-cat="voicemaster">
                <div class="cmd-name">vmdeny</div>
                <div class="cmd-desc">Remove a user's permission to join your locked channel.</div>
            </div>
            <div class="cmd-item" data-cat="voicemaster">
                <div class="cmd-name">vmkick</div>
                <div class="cmd-desc">Kick a user from your temporary voice channel.</div>
            </div>
            <div class="cmd-item" data-cat="voicemaster">
                <div class="cmd-name">vmclaim</div>
                <div class="cmd-desc">Claim ownership of a temporary channel if the owner left.</div>
            </div>

            <!-- Fun -->
            <div class="cmd-item" data-cat="fun">
                <div class="cmd-name">simp, rizz, cringe, sus, sigma, based</div>
                <div class="cmd-desc">Rate a user on a random 0-100 scale.</div>
            </div>
            <div class="cmd-item" data-cat="fun">
                <div class="cmd-name">cracked, goated, mid, cursed, blessed</div>
                <div class="cmd-desc">Rate a user on a random 0-100 scale.</div>
            </div>
            <div class="cmd-item" data-cat="fun">
                <div class="cmd-name">unhinged, feral, chaotic, wholesome, menace</div>
                <div class="cmd-desc">Rate a user on a random 0-100 scale.</div>
            </div>
            <div class="cmd-item" data-cat="fun">
                <div class="cmd-name">gremlin, delulu, broke, unemployed, npc</div>
                <div class="cmd-desc">Rate a user on a random 0-100 scale.</div>
            </div>
            <div class="cmd-item" data-cat="fun">
                <div class="cmd-name">gigachad, touchgrass, gamer, salty, petty</div>
                <div class="cmd-desc">Rate a user on a random 0-100 scale.</div>
            </div>
            <div class="cmd-item" data-cat="fun">
                <div class="cmd-name">extra, clown, cooked, valid, goblin</div>
                <div class="cmd-desc">Rate a user on a random 0-100 scale.</div>
            </div>
            <div class="cmd-item" data-cat="fun">
                <div class="cmd-name">unserious, boomer, gyat, mewing</div>
                <div class="cmd-desc">Rate a user on a random 0-100 scale.</div>
            </div>
        </div>
    </section>

    <!-- TERMS OF SERVICE -->
    <section id="terms">
        <h2 class="section-title reveal">Terms of Service</h2>
        <p class="section-sub reveal">Rules of the Hunt</p>
        
        <div class="legal-container reveal">
            <div class="placeholder-notice">
                ⚠️ IMPORTANT: The text below is placeholder content. Replace everything inside this container with your actual Terms of Service.
            </div>

            <!-- ═══════════════════════════════════════════════════════════════ -->
            <!-- PASTE YOUR TERMS OF SERVICE BELOW THIS LINE                   -->
            <!-- Remove the placeholder paragraphs and replace with your text  -->
            <!-- ═══════════════════════════════════════════════════════════════ -->

            <h2>1. Acceptance of Terms</h2>
            <p>By inviting or using Xylo ("the Bot"), you agree to be bound by these Terms of Service. If you do not agree, you may not use the Bot.</p>

            <h2>2. Description of Service</h2>
            <p>Xylo is a Discord bot providing moderation, utility, VoiceMaster, and entertainment features. Features may change or be removed at any time without notice.</p>

            <h2>3. User Conduct</h2>
            <p>You agree not to use the Bot to violate Discord's Terms of Service or Community Guidelines. This includes harassment, spam, illegal activity, or attempting to exploit bugs.</p>

            <h2>4. Data Collection</h2>
            <p>The Bot stores minimal data necessary for operation, including server configuration (prefixes, jail settings, join roles) and user preferences (timezones, self-prefixes). Message content is temporarily cached for snipe features and is not permanently stored.</p>

            <h2>5. Limitation of Liability</h2>
            <p>The Bot is provided "as is." We are not liable for any damages, data loss, or server issues arising from use of the Bot. Always ensure the Bot has appropriate permissions and role hierarchy.</p>

            <h2>6. Termination</h2>
            <p>We reserve the right to block any server or user from using the Bot at our discretion, with or without cause.</p>

            <h2>7. Changes to Terms</h2>
            <p>These terms may be updated at any time. Continued use after changes constitutes acceptance.</p>

            <h2>8. Contact</h2>
            <p>For questions or reports, contact us via the Support Server linked on this page.</p>

            <!-- ═══════════════════════════════════════════════════════════════ -->
            <!-- END TERMS OF SERVICE                                          -->
            <!-- ═══════════════════════════════════════════════════════════════ -->
        </div>
    </section>

    <!-- PRIVACY POLICY -->
    <section id="privacy">
        <h2 class="section-title reveal">Privacy Policy</h2>
        <p class="section-sub reveal">Protection of the Vessel</p>
        
        <div class="legal-container reveal">
            <div class="placeholder-notice">
                ⚠️ IMPORTANT: The text below is placeholder content. Replace everything inside this container with your actual Privacy Policy.
            </div>

            <!-- ═══════════════════════════════════════════════════════════════ -->
            <!-- PASTE YOUR PRIVACY POLICY BELOW THIS LINE                     -->
            <!-- Remove the placeholder paragraphs and replace with your text  -->
            <!-- ═══════════════════════════════════════════════════════════════ -->

            <h2>1. Information We Collect</h2>
            <p>We collect only the data necessary for the Bot to function:</p>
            <ul>
                <li><strong>Server Configuration:</strong> Prefixes, jail settings, join roles, VoiceMaster hub channels.</li>
                <li><strong>User Preferences:</strong> Self-prefixes, timezone settings.</li>
                <li><strong>Ephemeral Data:</strong> Recently deleted messages, edits, and reactions are held in temporary memory (RAM) for snipe commands and are lost on restart. They are not written to persistent storage.</li>
            </ul>

            <h2>2. How We Use Information</h2>
            <p>Data is used solely to provide Bot functionality. We do not sell, trade, or share your data with third parties.</p>

            <h2>3. Data Storage</h2>
            <p>Persistent data is stored in local JSON files on the Bot's host server. No data is transmitted to external analytics or advertising services.</p>

            <h2>4. Data Retention & Deletion</h2>
            <p>Server and user data persists until manually removed or the Bot is removed from the server. To request deletion of your data, contact us through the Support Server.</p>

            <h2>5. Security</h2>
            <p>We take reasonable measures to protect stored data. However, no internet transmission is 100% secure.</p>

            <h2>6. Children's Privacy</h2>
            <p>The Bot is not intended for users under the age of 13 (or the minimum age of digital consent in your jurisdiction).</p>

            <h2>7. Changes to This Policy</h2>
            <p>We may update this Privacy Policy at any time. Changes will be posted on this page.</p>

            <h2>8. Contact</h2>
            <p>For privacy concerns or data deletion requests, contact us via the Support Server.</p>

            <!-- ═══════════════════════════════════════════════════════════════ -->
            <!-- END PRIVACY POLICY                                            -->
            <!-- ═══════════════════════════════════════════════════════════════ -->
        </div>
    </section>

    <footer>
        <p>Xylo Bot &copy; 2026 — Not affiliated with Team Cherry.</p>
        <p style="margin-top: 0.5rem; font-size: 0.8rem;">Hollow Knight is a trademark of Team Cherry Pty Ltd.</p>
    </footer>

    <script>
        // ─── Floating Particles ───
        const particlesContainer = document.getElementById('particles');
        for (let i = 0; i < 40; i++) {
            const p = document.createElement('div');
            p.className = 'particle';
            p.style.left = Math.random() * 100 + '%';
            p.style.animationDuration = (Math.random() * 10 + 10) + 's';
            p.style.animationDelay = (Math.random() * 10) + 's';
            p.style.width = (Math.random() * 3 + 1) + 'px';
            p.style.height = p.style.width;
            particlesContainer.appendChild(p);
        }

        // ─── Scroll Reveal ───
        const reveals = document.querySelectorAll('.reveal');
        const revealObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('active');
                }
            });
        }, { threshold: 0.1 });

        reveals.forEach(r => revealObserver.observe(r));

        // ─── Command Search & Filter ───
        const cmdInput = document.getElementById('cmdInput');
        const cmdItems = document.querySelectorAll('.cmd-item');
        const catBtns = document.querySelectorAll('.cat-btn');
        let currentCat = 'all';

        function filterCommands() {
            const query = cmdInput.value.toLowerCase();
            cmdItems.forEach(item => {
                const cat = item.dataset.cat;
                const text = item.textContent.toLowerCase();
                const matchesCat = currentCat === 'all' || cat === currentCat;
                const matchesSearch = text.includes(query);
                if (matchesCat && matchesSearch) {
                    item.classList.remove('hidden-cmd');
                } else {
                    item.classList.add('hidden-cmd');
                }
            });
        }

        cmdInput.addEventListener('input', filterCommands);

        catBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                catBtns.forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                currentCat = btn.dataset.cat;
                filterCommands();
            });
        });

        // ─── Smooth Parallax on Mouse Move for Hero ───
        document.addEventListener('mousemove', (e) => {
            const x = (e.clientX / window.innerWidth - 0.5) * 20;
            const y = (e.clientY / window.innerHeight - 0.5) * 20;
            document.querySelector('.hero h1').style.transform = `translate(${x}px, ${y}px)`;
        });
    </script>
</body>
</html>
