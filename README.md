<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Untuk Nazwa Nazlia Fawaza</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Poppins:wght@300;400;600&display=swap');
        
        :root {
            --pink-light: #ffcce6;
            --pink-medium: #ff99cc;
            --pink-dark: #ff6699;
            --pink-deep: #ff3385;
            --text-primary: #4a4a4a;
            --text-secondary: #ffffff;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fff5f9;
            color: var(--text-primary);
            overflow-x: hidden;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--pink-medium), var(--pink-deep));
            color: var(--text-secondary);
            text-align: center;
            padding: 40px 0;
            position: relative;
            overflow: hidden;
        }
        
        header h1 {
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 10px;
            font-family: 'Dancing Script', cursive;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
            animation: fadeIn 1.5s ease-in-out;
        }
        
        header p {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 600px;
            margin: 0 auto;
        }
        
        /* Heart Animation */
        .hearts {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            pointer-events: none;
            z-index: 1;
        }
        
        .heart {
            position: absolute;
            color: rgba(255, 255, 255, 0.8);
            animation: float 6s ease-in infinite;
            font-size: 20px;
        }
        
        /* Main Content */
        .main-content {
            padding: 60px 0;
        }
        
        .memory-card {
            background: white;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(255, 102, 153, 0.1);
            padding: 30px;
            margin-bottom: 40px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .memory-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 35px rgba(255, 102, 153, 0.2);
        }
        
        .memory-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 5px;
            height: 100%;
            background: linear-gradient(to bottom, var(--pink-medium), var(--pink-deep));
        }
        
        .memory-card h2 {
            color: var(--pink-deep);
            margin-bottom: 20px;
            font-size: 1.8rem;
            position: relative;
            display: inline-block;
        }
        
        .memory-card h2::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 50px;
            height: 3px;
            background: var(--pink-medium);
        }
        
        .memory-card p {
            margin-bottom: 15px;
            font-size: 1.1rem;
        }
        
        /* Photo Section */
        .photo-section {
            text-align: center;
            margin: 40px 0;
        }
        
        .photo-frame {
            width: 250px;
            height: 250px;
            margin: 0 auto 30px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--pink-light), var(--pink-medium));
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 10px 25px rgba(255, 102, 153, 0.3);
            overflow: hidden;
            border: 8px solid white;
            position: relative;
        }
        
        .photo-frame img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .photo-frame:hover img {
            transform: scale(1.05);
        }
        
        /* Message Box */
        .message-box {
            background: linear-gradient(135deg, var(--pink-light), #ffb3d9);
            padding: 30px;
            border-radius: 15px;
            color: #4a4a4a;
            text-align: center;
            margin: 40px 0;
            box-shadow: 0 10px 30px rgba(255, 102, 153, 0.2);
            position: relative;
        }
        
        .message-box::before {
            content: '';
            position: absolute;
            top: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 0;
            height: 0;
            border-left: 15px solid transparent;
            border-right: 15px solid transparent;
            border-bottom: 15px solid var(--pink-light);
        }
        
        .message-box p {
            font-size: 1.1rem;
            line-height: 1.8;
            margin-bottom: 20px;
        }
        
        /* Button */
        .love-btn {
            display: inline-block;
            background: linear-gradient(to right, var(--pink-medium), var(--pink-deep));
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 20px;
            cursor: pointer;
            border: none;
            font-size: 1.1rem;
            box-shadow: 0 5px 15px rgba(255, 102, 153, 0.4);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .love-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(255, 102, 153, 0.6);
        }
        
        .love-btn:active {
            transform: translateY(1px);
        }
        
        .love-btn::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to right, var(--pink-deep), #ff3385);
            z-index: -1;
            transition: opacity 0.3s ease;
            opacity: 0;
        }
        
        .love-btn:hover::after {
            opacity: 1;
        }
        
        /* Footer */
        footer {
            background: linear-gradient(135deg, var(--pink-medium), var(--pink-deep));
            color: var(--text-secondary);
            text-align: center;
            padding: 30px 0;
            margin-top: 60px;
        }
        
        footer p {
            opacity: 0.8;
            font-size: 0.9rem;
        }
        
        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        @keyframes float {
            0% { transform: translateY(0) rotate(0deg); opacity: 1; }
            100% { transform: translateY(-100vh) rotate(360deg); opacity: 0; }
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5rem;
            }
            
            .memory-card {
                padding: 20px;
            }
            
            .photo-frame {
                width: 200px;
                height: 200px;
            }
        }
        
        /* Secret Message */
        .secret-message {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(255, 204, 230, 0.95);
            z-index: 1000;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            text-align: center;
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.5s ease;
        }
        
        .secret-message.active {
            opacity: 1;
            pointer-events: all;
        }
        
        .secret-message h2 {
            color: var(--pink-deep);
            font-size: 2.5rem;
            margin-bottom: 20px;
            font-family: 'Dancing Script', cursive;
        }
        
        .secret-message p {
            max-width: 600px;
            margin: 0 auto 30px;
            font-size: 1.2rem;
        }
        
        .close-btn {
            background: var(--pink-deep);
            color: white;
            border: none;
            padding: 10px 25px;
            border-radius: 50px;
            cursor: pointer;
            font-size: 1rem;
            transition: background 0.3s ease;
        }
        
        .close-btn:hover {
            background: #e60073;
        }
    </style>
</head>
<body>
    <header>
        <div class="hearts" id="hearts"></div>
        <div class="container">
            <h1>for cayangku Nazwa Nazlia Fawaza</h1>
            <p>dibaca yaaa cantikkuu sayanggg ❤️ </p>
        </div>
    </header>

    <div class="main-content">
        <div class="container">
            <div class="photo-section">
                <div class="photo-frame">
                    <img src = "wawa bika.jpg" width = "500" height = "500" style="outline: rgb(0, 0, 0) dotted 3px; outline-offset: 1px;"> />
                </div>
                <h2>Kata-Kata Buat Wawa ❤️</h2>
            </div>

            <div class="memory-card">
                <h2>Tentang Aku dan kamu </h2>
                <p>Terima ya hadiah dari aku ini , aku tau mungkin ini belum seberapa dibanding pemberian dari mantan-mantan kamu sebelumnya , tapi aku yakin hal sekecil apapun bisa buat seseorang bahagia tergantung dari cara mereka menghargainya.</p>
                <p>Aku tahu mungkin kamu masih butuh waktu buat nerima aku dalam waktu dekat, tapi maaf ya kalo aku selalu bertanya-tanya hal yang sama ke kamu "kayak kapan kita bisa pacaran". tapi aku bakal selalu menunggu kok kapan kamu bisa buka hati sepenuhnya buat aku ❤️</p>
            </div>

            <div class="memory-card">
                <h2>Hal-Hal yang selalu aku suka dari kamu</h2>
                <p>1. Cara kamu memperhatikan hal-hal kecil yang membuat kamu bahagia </p>
                <p>2. Selalu mengerti gimana cara kamu ngebuat aku semangat</p>
                <p>3. tingkah kamu yang lucu dan pemalu , kadang ngebuat aku jadi makin tertantang untuk ngebuat kamu merasa bebas</p>
                <p>4. Cara kamu ngebuat aku merasa berarti dengan cara-cara kamu yang sederhana</p>
                <p>5. Setiap waktu yang aku habisin sama kamu terasa spesial tiap detiknya dan cara kamu mendengarkan cerita-ceritaku yang ngebuat aku makin sayang sama kamu.</p>
            </div>

            <div class="message-box">
                <h2>Dengarkan Hatiku</h2>
                <p>Jujur sebenernya aku mau secepet itu jadian sama kamu, karna aku butuh kepastian yang jelas tentang kamu. tapi balik lagi seperti yang wawa bilang kamu tau waktu yang tepat buat kita bareng nantinya.</p>
                <p>Aku akan selalu nantikan wa, momen bahagia kita nantinya. yang bakal ngebuat kita selalu bisa bersama dan belajar dari apa yang telah kita lewati sebelumnya.</p>
                
                <button class="love-btn" id="loveBtn">Tekan Jika Kamu Penasaran</button>
            </div>
        </div>
    </div>

    <footer>
        <div class="container">
            <p>Dibuat dengan ❤️ khusus untuk Nazwa Nazlia Fawaza</p>
        </div>
    </footer>

    <div class="secret-message" id="secretMessage">
        <div class="container">
            <h2>Untuk Nazwa Tercinta</h2>
            <p>Sayang, mungkin didalam diriku masih banyak kekurangan yang harus aku perbaiki. Tapi aku lebih senang jika bisa memperbaiki kekurangan dengan wawa, senangnya aku bisa kenal kamu lebih dekat bahkan sampai bisa manggil sayang dan jadi tempat cerita ternyaman yang pernah aku temuin. </p>
            <button class="close-btn" id="closeBtn">Tutup</button>
        </div>
    </div>

    <script>
        // Heart animation
        function createHearts() {
            const heartsContainer = document.getElementById('hearts');
            const heartCount = 20;
            
            for (let i = 0; i < heartCount; i++) {
                setTimeout(() => {
                    const heart = document.createElement('div');
                    heart.innerHTML = '❤️';
                    heart.classList.add('heart');
                    
                    // Random position
                    heart.style.left = Math.random() * 100 + 'vw';
                    heart.style.top = Math.random() * 100 + 'vh';
                    
                    // Random animation duration
                    heart.style.animationDuration = 3 + Math.random() * 5 + 's';
                    
                    heartsContainer.appendChild(heart);
                    
                    // Remove heart after animation
                    setTimeout(() => {
                        heart.remove();
                    }, 6000);
                }, i * 300);
            }
        }
        
        // Repeat heart animation
        setInterval(createHearts, 3000);
        
        // Initial heart creation
        createHearts();
        
        // Love button interaction
        const loveBtn = document.getElementById('loveBtn');
        const secretMessage = document.getElementById('secretMessage');
        const closeBtn = document.getElementById('closeBtn');
        
        loveBtn.addEventListener('click', () => {
            secretMessage.classList.add('active');
        });
        
        closeBtn.addEventListener('click', () => {
            secretMessage.classList.remove('active');
        });
        
        // Typewriter effect for the first paragraph
        const typeWriterText = "Setiap kali melihatmu, hatiku selalu berdebar dengan cara yang berbeda. Senyummu yang manis, tawamu yang menular, dan sikapmu yang hangat membuatku merasa istimewa.";
        const typeWriterElement = document.querySelector('.memory-card p:first-child');
        
        if (typeWriterElement) {
            typeWriterElement.textContent = '';
            let i = 0;
            
            function typeWriter() {
                if (i < typeWriterText.length) {
                    typeWriterElement.textContent += typeWriterText.charAt(i);
                    i++;
                    setTimeout(typeWriter, 40);
                }
            }
            
            setTimeout(typeWriter, 1000);
        }
        
        // Scroll animations
        const memoryCards = document.querySelectorAll('.memory-card');
        
        function checkScroll() {
            memoryCards.forEach((card, index) => {
                const cardPosition = card.getBoundingClientRect().top;
                const screenPosition = window.innerHeight / 1.3;
                
                if (cardPosition < screenPosition) {
                    setTimeout(() => {
                        card.style.opacity = '1';
                        card.style.transform = 'translateY(0)';
                    }, index * 200);
                }
            });
        }
        
        // Initialize cards
        memoryCards.forEach(card => {
            card.style.opacity = '0';
            card.style.transform = 'translateY(50px)';
            card.style.transition = 'all 0.5s ease';
        });
        
        window.addEventListener('scroll', checkScroll);
        window.addEventListener('load', checkScroll);
    </script>
</body>
</html>
