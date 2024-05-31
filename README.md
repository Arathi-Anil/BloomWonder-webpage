<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flower Shop</title>
    <style>
        body {
            font-family: Georgia, 'Times New Roman', Times, serif;
            background-color: #f7f7f7;
            color: #a21a6a;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            position: relative;
            background-color: #ffebee;
            padding: 20px 0;
            text-align: center;
        }

        header .banner {
            position: relative;
            height: 300px;
            max-width: 1200px;
            margin: 0 auto;
            overflow: hidden;
        }

        header .banner img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        header .banner div {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: #fff;
            padding: 10px 20px;
            border-radius: 10px;
        }

        header h1 {
            font-size: 50px;
            color: #2e0309;
            font-weight: bolder;
            font-style: oblique;
            margin: 0;
        }

        header p {
            margin: 10px 0;
            font-family: 'Times New Roman', Times, serif;
            font-size: 18px;
            color: #d32f2f;
        }

        nav {
            background-color: #b0717b;
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 20px auto 0 auto;
            padding: 0 20px;
        }

        nav .logo {
            display: flex;
            align-items: center;
        }

        nav .logo img {
            width: 50px;
            height: 50px;
            margin-right: 10px;
        }

        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav li {
            margin-left: 20px;
        }

        nav a {
            text-decoration: none;
            color: #670a18;
            font-weight: bold;
        }

        main {
            padding: 20px;
            max-width: 1200px;
            margin: 20px auto;
        }

        main h2 {
            color: #af1a3d;
            margin-bottom: 10px;
        }

        main ul {
            list-style: none;
            padding: 0;
        }

        main ul li {
            margin-bottom: 10px;
        }

        footer {
            background-color: #ffebee;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        @media (max-width: 768px) {
            header .banner {
                height: 200px;
            }

            header h1 {
                font-size: 35px;
            }

            header p {
                font-size: 16px;
            }

            nav {
                flex-direction: column;
                padding: 10px;
            }

            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav li {
                margin-left: 0;
                margin-bottom: 10px;
            }

            main {
                padding: 10px;
                margin: 10px auto;
            }

            main h2 {
                font-size: 24px;
            }

            footer {
                padding: 10px;
                font-size: 14px;
            }
        }

        @media (max-width: 480px) {
            header .banner {
                height: 150px;
            }

            header h1 {
                font-size: 28px;
            }

            header p {
                font-size: 14px;
            }

            nav .logo img {
                width: 40px;
                height: 40px;
            }

            main h2 {
                font-size: 20px;
            }

            footer {
                font-size: 12px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="banner">
            <img src="https://images.pexels.com/photos/70330/pexels-photo-70330.jpeg?cs=srgb&dl=flowers-colorful-colourful-70330.jpg&fm=jpg" alt="Flower Banner">
            <div>
                <h1>Bloom Wonder</h1>
            </div>
        </div>
        <p>Fresh Flowers Delivered Daily</p>
    </header>
    <nav>
        <div class="logo">
            <img src="https://images.creativemarket.com/0.1.0/ps/6661855/1820/1214/m1/fpnw/wm1/flower-shop-preview-1-.jpg?1562874959&s=9f2c1c843c941fad56a4bf0adee03827" alt="Flower Shop Logo">
        </div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Welcome to Bloom Wonder</h2>
            <p>At Bloom Wonder, we believe in the power of flowers to bring joy and beauty into your life. Our expert florists create stunning arrangements for every occasion.</p>
        </section>
        <section id="about">
            <h2>About Us</h2>
            <p>Bloom Wonder has been delivering fresh flowers to our community for over 20 years. We pride ourselves on our commitment to quality and customer satisfaction.</p>
        </section>
        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Customised Floral Arrangements</li>
                <li>Wedding Bouquets</li>
                <li>Event Decorations</li>
                <li>Weekly Subscriptions</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or would like to place an order, please get in touch with us:</p>
            <p>Email: <a href="mailto:info@bloomwonder.com" style="color: #d32f2f;">info@bloomwonder.com</a></p>
            <p>Phone: <a href="tel:+1234567890" style="color: #d32f2f;">+1 234 567 890</a></p>
            <p>Address: 123 Flower Lane, Blossom City, FL</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Bloom Wonder. All rights reserved.</p>
    </footer>
</body>
</html>
