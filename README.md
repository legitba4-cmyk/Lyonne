<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lyonne’s Lending Services</title>
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      color: #222;
      background: #f4f4f4;
    }
    section {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 40px;
      transition: background 1s ease;
    }
    /* Hero Section */
    .hero {
      background: url('E9940F5B-3E3D-477A-8E6A-FF25B9EBFCF1.jpeg') no-repeat center center/cover;
      color: white;
      position: relative;
    }
    .hero::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0, 0, 0, 0.4);
      z-index: 0;
    }
    .hero-content {
      position: relative;
      z-index: 1;
    }
    .hero h1 {
      font-size: 2.8em;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2em;
      margin-bottom: 25px;
    }
    .btn {
      background: #007bff;
      color: white;
      padding: 12px 25px;
      border: none;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }
    .btn:hover {
      background: #0056b3;
    }
    /* Other Sections */
    .about { background: #fff; }
    .terms { background: #e3f2fd; }
    .apply { background: #fce4ec; }
    .contact { background: #ede7f6; }
    .footer {
      background: #212121;
      color: white;
      font-size: 0.9em;
      height: 50vh;
    }
    h2 {
      margin-bottom: 15px;
    }
    p {
      max-width: 700px;
      line-height: 1.6;
    }
  </style>
</head>
<body>

  <!-- Section 1: Hero -->
  <section class="hero" id="home">
    <div class="hero-content">
      <h1>🏛️ Lyonne’s Lending Services</h1>
      <p>Reliable and transparent lending designed to support your financial needs.</p>
      <a href="#" class="btn">🔹 Apply for a Loan</a>
    </div>
  </section>

  <!-- Section 2: About -->
  <section class="about" id="about">
    <h2>About Lyonne’s Lending Services</h2>
    <p>
      We provide short-term, transparent lending options tailored to your financial goals.
      Our service is built on trust, respect, and accountability — ensuring every client
      experiences a smooth and professional lending process.
    </p>
  </section>

  <!-- Section 3: Terms -->
  <section class="terms" id="terms">
    <h2>📜 Terms & Conditions</h2>
    <p>
      1. Eligibility – All borrower information must be accurate and verified.<br>
      2. Repayment – Payments must be made on or before the Date of Payment (DOP).<br>
      3. Extensions – Only 1-day extension allowed with a 15% fee, 24-hour notice before DOP.<br>
      4. Late Fees – ₱100/hour after due date until fully paid.<br>
      5. Refunds – No refunds or cancellations once funds are released.<br>
      6. Privacy – All borrower details remain confidential unless required for legal reasons.<br>
      7. Conduct – Rude communication results in immediate blacklisting.<br>
      8. Agreement – Proceeding with a loan means full acceptance of these terms.
    </p>
  </section>

  <!-- Section 4: How to Apply -->
  <section class="apply" id="apply">
    <h2>💼 How to Apply</h2>
    <p>
      1️⃣ Message us on Facebook or Messenger.<br>
      2️⃣ Provide your full name, requested amount, and reason for the loan.<br>
      3️⃣ Wait for verification and approval.<br>
      4️⃣ Receive your funds via GCash or bank transfer.<br><br>
      Note: Processing times may vary depending on verification.
    </p>
  </section>

  <!-- Section 5: Contact -->
  <section class="contact" id="contact">
    <h2>📩 Contact Information</h2>
    <p>
      For inquiries or applications:<br>
      📱 Message us on Messenger<br>
      📧 Email: your@email.com<br>
      📍 Service Area: Philippines
    </p>
  </section>

  <!-- Section 6: Footer -->
  <section class="footer">
    <p>© 2025 Lyonne’s Lending Services — All Rights Reserved.</p>
  </section>

</body>
</html>
