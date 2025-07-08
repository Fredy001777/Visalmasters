<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Visal Masters - YouTube & TikTok Training</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, #6e48aa, #9d50bb);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        .logo {
            font-size: 2.5rem;
            font-weight: bold;
            margin-bottom: 1rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        .hero {
            text-align: center;
            padding: 3rem 0;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: #6e48aa;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 2rem;
        }
        
        .pricing {
            display: flex;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
            margin: 3rem 0;
        }
        
        .pricing-card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            padding: 2rem;
            width: 300px;
            text-align: center;
            transition: transform 0.3s;
        }
        
        .pricing-card:hover {
            transform: translateY(-10px);
        }
        
        .pricing-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #6e48aa;
        }
        
        .price {
            font-size: 2.5rem;
            font-weight: bold;
            margin: 1rem 0;
            color: #333;
        }
        
        .price span {
            font-size: 1rem;
            color: #777;
        }
        
        .features {
            list-style: none;
            margin: 1.5rem 0;
        }
        
        .features li {
            padding: 0.5rem 0;
            border-bottom: 1px solid #eee;
        }
        
        .btn {
            display: inline-block;
            background: #6e48aa;
            color: white;
            padding: 0.8rem 2rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s;
        }
        
        .btn:hover {
            background: #9d50bb;
        }
        
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 3rem;
        }
        
        @media (max-width: 768px) {
            .pricing {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">Visal Masters</div>
            <div class="tagline">Master YouTube & TikTok Like a Pro</div>
        </div>
    </header>
    
    <section class="hero">
        <div class="container">
            <h1>Start Growing Your Audience Today</h1>
            <p>Join thousands of creators who have transformed their channels with our proven strategies. Whether you're a beginner or an advanced creator, we have the perfect plan for you.</p>
        </div>
    </section>
    
    <section class="pricing">
        <div class="pricing-card">
            <h3>Starter</h3>
            <div class="price">$59.99 <span>/ one-time</span></div>
            <ul class="features">
<li>Basic YouTube & TikTok strategies</li>
                <li>5 video templates</li>
                <li>Email support</li>
                <li>Access to private Discord</li>
            </ul>
            <a href="#" class="btn">Get Started</a>
        </div>
        
        <div class="pricing-card">
            <h3>Pro</h3>
            <div class="price">$109.99 <span>/ one-time</span></div>
            <ul class="features">
                <li>Advanced growth techniques</li>
                <li>15 video templates</li>
                <li>Priority email support</li>
                <li>1-on-1 coaching call</li>
            </ul>
            <a href="#" class="btn">Get Pro</a>
        </div>
        
        <div class="pricing-card">
            <h3>Master</h3>
            <div class="price">$159.99 <span>/ one-time</span></div>
            <ul class="features">
                <li>VIP YouTube & TikTok strategies</li>
                <li>30+ video templates</li>
                <li>24/7 priority support</li>
                <li>3 coaching calls</li>
                <li>Personalized content review</li>
            </ul>
            <a href="#" class="btn">Become a Master</a>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <p>&copy; 2024 Visal Masters. All rights reserved.</p>
        </div>
    </footer>
    
    <script>
        // Можно добавить обработчики для кнопок оплаты (Stripe, PayPal, крипто)
        document.querySelectorAll('.btn').forEach(btn => {
            btn.addEventListener('click', (e) => {
                e.preventDefault();
                const plan = e.target.closest('.pricing-card').querySelector('h3').textContent;
                alert(`You selected the ${plan} plan! Payment gateway would open here.`);
            });
        });
    </script>
</body>
</html>
