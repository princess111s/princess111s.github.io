<!DOCTYPE html>
<html lang="ka">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saba's Space</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            background-color: #0d0b18;
            /* კოსმიური, ვარსკვლავებიანი ფონი */
            background-image: 
                radial-gradient(white, rgba(255,255,255,.2) 2px, transparent 40px),
                radial-gradient(white, rgba(255,255,255,.15) 1px, transparent 30px),
                radial-gradient(white, rgba(255,255,255,.1) 2px, transparent 40px),
                radial-gradient(circle at 50% 50%, #161233 0%, #0d0b18 100%);
            background-size: 550px 550px, 350px 350px, 250px 250px, 100% 100%;
            background-position: 0 0, 40px 60px, 130px 270px, 0 0;
            min-height: 100vh;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            overflow-x: hidden;
            overflow-y: hidden; /* იხსნება მხოლოდ ყუთზე დაჭერისას */
        }

        /* სექცია 1: საიდუმლო ყუთი */
        .welcome-screen {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
            perspective: 1200px;
        }

        .gift-box {
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        /* თავსახური */
        .gift-top {
            width: 210px;
            height: 45px;
            background: #007aff; /* ლურჯი ნეონის ტონი დაბადების დღის წითლის ნაცვლად */
            border-radius: 4px;
            position: relative;
            z-index: 10;
            box-shadow: 0 8px 15px rgba(0,0,0,0.4);
            transform-origin: bottom right;
            transition: transform 1.2s cubic-bezier(0.68, -0.55, 0.27, 1.55), opacity 0.8s ease;
        }

        /* ბაფთის ნაცვლად ელეგანტური ზოლი */
        .top-stripe {
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            width: 35px;
            height: 100%;
            background: #00ffcc;
        }

        /* ყუთის ქვედა ნაწილი */
        .gift-bottom {
            width: 190px;
            height: 180px;
            background: #1c1936;
            position: relative;
            z-index: 5;
            border-bottom-left-radius: 6px;
            border-bottom-right-radius: 6px;
            border: 1px solid rgba(0, 255, 204, 0.3);
            box-shadow: 0 15px 30px rgba(0,0,0,0.5);
            transition: transform 1s ease;
        }

        .bottom-stripe {
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            width: 35px;
            height: 100%;
            background: #00ffcc;
        }

        /* პირველი მთავარი ფოტო ყუთიდან ამოსვლისას */
        .photo-reveal-container {
            position: absolute;
            width: 160px;
            height: 160px;
            z-index: 2;
            opacity: 0;
            transform: scale(0.1);
            transition: transform 1.8s cubic-bezier(0.175, 0.885, 0.32, 1.275), opacity 0.7s ease;
        }

        .photo-reveal-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 50%;
            border: 4px solid #00ffcc;
            box-shadow: 0 0 30px rgba(0, 255, 204, 0.6);
        }

        /* პირველი გვერდის ტექსტი */
        .main-title {
            position: absolute;
            bottom: -80px;
            color: #ffffff;
            font-size: 2.5rem;
            font-weight: bold;
            text-align: center;
            opacity: 0;
            transform: scale(0.5);
            transition: all 1.2s cubic-bezier(0.175, 0.885, 0.32, 1.275) 0.8s;
            text-shadow: 0 0 15px #00ffcc;
            white-space: nowrap;
            letter-spacing: 2px;
        }

        /* ყუთის გახსნის ეფექტები */
        .gift-box.opened .gift-top {
            transform: translateY(-200px) rotate(55deg);
            opacity: 0;
        }

        .gift-box.opened .photo-reveal-container {
            opacity: 1;
            transform: translateY(-210px) scale(1.4);
        }

        .gift-box.opened .main-title {
            opacity: 1;
            transform: scale(1);
            bottom: -130px;
        }

        /* სქროლის მინიშნება */
        .scroll-indicator {
            position: absolute;
            bottom: 25px;
            color: #00ffcc;
            font-size: 1.1rem;
            font-weight: bold;
            opacity: 0;
            transform: translateY(15px);
            transition: all 1s ease 2.5s;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }

        /* სექცია 2: გალერეის ეკრანი */
        .content-screen {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            padding: 60px 20px;
            opacity: 0;
            transition: opacity 1.5s ease 1s;
        }

        body.show-all .content-screen {
            opacity: 1;
        }

        .intro-wishes {
            text-align: center;
            margin-bottom: 50px;
            color: white;
        }

        .intro-wishes h1 {
            font-size: 3.5rem;
            background: linear-gradient(45deg, #00ffcc, #007aff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-family: 'Georgia', serif;
            margin-bottom: 10px;
        }

        .intro-wishes .subtitle-name {
            font-size: 4rem;
            letter-spacing: 12px;
            font-weight: 300;
            margin-bottom: 20px;
            display: block;
        }

        .intro-wishes p {
            font-size: 1.2rem;
            opacity: 0.7;
            letter-spacing: 1px;
        }

        /* ასიმეტრიული ფოტო გალერეა */
        .grid-gallery {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            grid-gap: 20px;
            max-width: 750px;
            width: 100%;
            margin-bottom: 60px;
        }

        .grid-gallery .card-box {
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(0, 255, 204, 0.2);
            border-radius: 24px;
            overflow: hidden;
            position: relative;
            box-shadow: 0 10px 30px rgba(0,0,0,0.4);
            transition: transform 0.4s ease, border-color 0.4s ease, box-shadow 0.4s ease;
        }

        .grid-gallery .card-box:nth-child(1) { height: 280px; }
        .grid-gallery .card-box:nth-child(2) { height: 420px; grid-row: span 2; }
        .grid-gallery .card-box:nth-child(3) { height: 280px; }
        .grid-gallery .card-box:nth-child(4) { height: 260px; grid-column: span 2; }

        .grid-gallery .card-box:hover {
            transform: translateY(-5px);
            border-color: #00ffcc;
            box-shadow: 0 15px 35px rgba(0, 255, 204, 0.2);
        }

        .grid-gallery img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* ქვედა საინფორმაციო ბარათი */
        .final-card {
            background: rgba(20, 18, 38, 0.75);
            border: 1px solid rgba(0, 255, 204, 0.2);
            padding: 50px 40px;
            border-radius: 28px;
            max-width: 580px;
            width: 100%;
            text-align: center;
            backdrop-filter: blur(15px);
            box-shadow: 0 20px 50px rgba(0,0,0,0.6);
            color: #ffffff;
            margin-bottom: 50px;
        }

        .final-card p {
            font-size: 1.4rem;
            line-height: 2;
            margin-bottom: 15px;
            font-weight: 300;
            opacity: 0.9;
        }

        .final-card .signature {
            color: #00ffcc;
            font-size: 1.1rem;
            letter-spacing: 4px;
            margin-top: 35px;
            font-weight: bold;
        }

        /* ნაპერწკლების ეფექტი ყუთის გახსნისას */
        .sparkle-element {
            position: absolute;
            width: 6px;
            height: 6px;
            background: #00ffcc;
            border-radius: 50%;
            z-index: 6;
            pointer-events: none;
            opacity: 0;
        }

        @keyframes explodeOut {
            0% { transform: translate(0, 0) scale(0.3); opacity: 0; }
            20% { opacity: 1; }
            100% { transform: translate(var(--x), var(--y)) scale(1); opacity: 0; }
        }
    </style>
</head>
<body>

    <div class="welcome-screen">
        <div class="gift-box" id="clickBox" onclick="openPresent()">
            <div class="gift-top"><div class="top-stripe"></div></div>
            <div class="gift-bottom"><div class="bottom-stripe"></div></div>
            
            <div class="photo-reveal-container">
                <img src="saba1.jpg" alt="Saba">
            </div>

            <div class="main-title">SABA'S SPACE</div>
        </div>

        <div class="scroll-indicator" id="scrollTag">⬇ ჩამოისქროლე დაბლა ⬇</div>
    </div>

    <div class="content-screen" id="mainContent">
        <div class="intro-wishes">
            <h1>WELCOME TO</h1>
            <span class="subtitle-name">SABA</span>
            <p>პერსონალური ფოტო გალერეა</p>
        </div>

        <div class="grid-gallery">
            <div class="card-box"><img src="saba1.jpg" alt="Saba 1"></div>
            <div class="card-box"><img src="saba2.jpg" alt="Saba 2"></div>
            <div class="card-box"><img src="saba3.jpg" alt="Saba 3"></div>
            <div class="card-box"><img src="saba4.jpg" alt="Saba 4"></div>
        </div>

        <div class="final-card">
            <p>კეთილი იყოს თქვენი მობრძანება ციფრულ სივრცეში.</p>
            <p>აქ განთავსებულია საუკეთესო მომენტების კრებული.</p>
            <div class="signature">SABA © 2026</div>
        </div>
    </div>

    <script>
        function openPresent() {
            const box = document.getElementById('clickBox');
            const scrollTag = document.getElementById('scrollTag');
            
            if (box.classList.contains('opened')) return;

            box.classList.add('opened');
            
            // სქროლის აქტივაცია
            document.body.style.overflowY = 'auto';
            document.body.classList.add('show-all');
            
            scrollTag.style.opacity = '1';
            scrollTag.style.transform = 'translateY(0)';

            spawnSparkles();

            // 3.5 წამში ავტომატურად ჩაისქროლებს მეორე გვერდზე
            setTimeout(() => {
                document.getElementById('mainContent').scrollIntoView({ behavior: 'smooth' });
            }, 3500);
        }

        // ნეონის ნაპერწკლების ეფექტი გახსნისას
        function spawnSparkles() {
            const box = document.getElementById('clickBox');
            const colors = ['#00ffcc', '#007aff', '#ffffff', '#5856d6'];
            
            for (let i = 0; i < 50; i++) {
                const s = document.createElement('div');
                s.classList.add('sparkle-element');
                
                const randColor = colors[Math.floor(Math.random() * colors.length)];
                s.style.backgroundColor = randColor;
                s.style.boxShadow = `0 0 10px ${randColor}`;

                const angle = Math.random() * Math.PI * 2; 
                const distance = Math.random() * 250 + 100;
                const x = Math.cos(angle) * distance;
                const y = Math.sin(angle) * distance - 50;

                s.style.setProperty('--x', `${x}px`);
                s.style.setProperty('--y', `${y}px`);

                s.style.left = '95px';
                s.style.top = '90px';
                
                s.style.animation = `explodeOut ${Math.random() * 1 + 1}s cubic-bezier(0.1, 0.8, 0.3, 1) forwards`;

                box.appendChild(s);
                setTimeout(() => { s.remove(); }, 2000);
            }
        }
    </script>
</body>
</html>
