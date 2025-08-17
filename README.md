
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sanjey Trading Platform</title>
  <style>
    /* Global */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #fff;
      color: #333;
    }

    a {
      text-decoration: none;
      color: #b8860b; /* gold */
    }

    header {
      background: white;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 2px solid #b8860b;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    header h1 {
      color: #b8860b;
      font-size: 28px;
    }

    nav a {
      margin: 0 15px;
      font-size: 18px;
      font-weight: 600;
      transition: 0.3s;
    }

    nav a:hover {
      color: #daa520;
    }

    /* Hero Section */
    .hero {
      height: 70vh;
      background: linear-gradient(to right, #fff, #fdf5e6);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .hero h2 {
      font-size: 50px;
      color: #b8860b;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 20px;
      color: #555;
    }

    .hero button {
      padding: 15px 40px;
      font-size: 18px;
      background: #b8860b;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 20px;
      transition: 0.3s;
    }

    .hero button:hover {
      background: #daa520;
    }

    /* Dashboard / Market Cards */
    .dashboard {
      padding: 50px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .card {
      background: #fff;
      border: 2px solid #b8860b;
      border-radius: 15px;
      padding: 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.03);
      box-shadow: 0 10px 25px rgba(184,134,11,0.3);
    }

    .card h3 {
      color: #b8860b;
      margin-bottom: 10px;
    }

    .card p {
      color: #555;
    }

    /* Market Table */
    .market {
      padding: 50px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    th, td {
      padding: 15px;
      border: 1px solid #b8860b;
      text-align: center;
    }

    th {
      background: #b8860b;
      color: white;
    }

    td button {
      padding: 8px 20px;
      background: #b8860b;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: 0.3s;
    }

    td button:hover {
      background: #daa520;
    }

    /* Footer */
    footer {
      background: #f8f8f8;
      text-align: center;
      padding: 20px;
      border-top: 2px solid #b8860b;
      margin-top: 50px;
      color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sanjey Trading</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#markets">Markets</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Trade Smart • Trade Gold</h2>
    <p>Experience premium trading with Sanjey AI Trading Platform</p>
    <a href="#markets"><button>Explore Markets</button></a>
  </section>

  <section class="dashboard">
    <div class="card">
      <h3>Live Stocks</h3>
      <p>Track Tata Steel, Aditya Birla, Reliance & more in real-time.</p>
    </div>
    <div class="card">
      <h3>AI Insights</h3>
      <p>Get AI-powered predictions to guide your investments.</p>
    </div>
    <div class="card">
      <h3>Secure Transactions</h3>
      <p>Trade confidently with our safe and secure payment gateway.</p>
    </div>
  </section>

  <section class="market" id="markets">
    <h2 style="color:#b8860b; text-align:center;">Live Market Prices</h2>
    <table>
      <tr>
        <th>Company</th>
        <th>Price</th>
        <th>Change</th>
        <th>Action</th>
      </tr>
      <tr>
        <td>Tata Steel</td>
        <td>₹145.50</td>
        <td style="color:green;">+1.2%</td>
        <td><button>Buy</button></td>
      </tr>
      <tr>
        <td>Aditya Birla</td>
        <td>₹220.75</td>
        <td style="color:red;">-0.8%</td>
        <td><button>Buy</button></td>
      </tr>
      <tr>
        <td>Reliance</td>
        <td>₹2,345.90</td>
        <td style="color:green;">+0.5%</td>
        <td><button>Buy</button></td>
      </tr>
      <tr>
        <td>Infosys</td>
        <td>₹1,480.60</td>
        <td style="color:green;">+2.1%</td>
        <td><button>Buy</button></td>
      </tr>
    </table>
  </section>

  <section id="about" style="padding:50px; text-align:center;">
    <h2 style="color:#b8860b;">About Us</h2>
    <p style="max-width:800px; margin:auto; font-size:18px; color:#555;">
      Sanjey Trading Platform is designed for smart investors. 
      With AI-powered insights and real-time stock tracking, 
      we make trading easy, secure, and profitable.
    </p>
  </section>

  <section id="contact" style="padding:50px; text-align:center;">
    <h2 style="color:#b8860b;">Contact Us</h2>
    <p>Email: support@sanjeytrading.com | Phone: +91 98765 43210</p>
  </section>

  <footer>
    <p>© 2025 Sanjey Trading | All Rights Reserved</p>
  </footer>
</body>
</html>
