<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lyonne’s Lending Services</title>
  <style>
    body {
      margin: 0;
      font-family: "Montserrat", sans-serif;
      background-color: #0e0e0e;
      color: #f9f9f9;
      line-height: 1.6;
    }

    h1, h2 {
      font-family: "Playfair Display", serif;
      color: #f5c542;
      text-align: center;
    }

    p, li {
      color: #ddd;
      font-size: 1.05em;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }

    /* Hero Section */
    .hero {
      background: url('https://i.ibb.co/s5J8TQt/cover.jpg') center/cover no-repeat;
      position: relative;
      color: white;
      text-align: center;
      padding: 140px 20px;
    }

    .hero::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0, 0, 0, 0.5);
      z-index: 0;
    }

    .hero-content {
      position: relative;
      z-index: 1;
    }

    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2em;
      margin-bottom: 25px;
    }

    .hero a {
      display: inline-block;
      background-color: #f5c542;
      color: #000;
      padding: 12px 28px;
      border-radius: 6px;
      font-weight: 600;
      transition: 0.3s;
      text-decoration: none;
    }

    .hero a:hover {
      background-color: #fff;
    }

    /* Section Titles */
    h2 {
      border-bottom: 2px solid #f5c542;
      display: inline-block;
      margin-bottom: 20px;
      padding-bottom: 8px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      margin: 8px 0;
    }

    /* Footer */
    footer {
      background: #1a1a1a;
      color: #aaa;
      text-align: center;
      padding: 25px 10px;
      font-size: 0.9em;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 1.8em;
      }
    }
  </style>
</head>
<body>

  <!-- Section 1: Hero -->
  <section class="hero">
    <div class="hero-content">
      <h1>🏛️ Lyonne’s Lending Services</h1>
      <p>Reliable and transparent lending designed to support your financial needs.</p>
      <a href="https://www.facebook.com/" target="_blank">🔹 Apply for a Loan →</a>
    </div>
  </section>

  <!-- Section 2: About Us -->
  <section>
    <h2>About Lyonne’s Lending Services</h2>
    <p>
      We provide short-term, transparent lending options tailored to your financial goals.
      Our service is built on trust, respect, and accountability — ensuring every client
      experiences a smooth and professional lending process.
    </p>
  </section>

  <!-- Section 3: Terms & Conditions -->
  <section>
    <h2>📜 Terms & Conditions</h2>
    <ol>
      <li>1. Eligibility – All borrower information must be accurate and verified.</li>
      <li>2. Repayment – Payments must be made on or before the Date of Payment (DOP).</li>
      <li>3. Extensions – Only 1-day extension allowed with an added 15% fee. Must inform 24 hours before DOP.</li>
      <li>4. Late Fees – ₱100 per hour after the due date until fully paid.</li>
      <li>5. Refunds – No refunds or cancellations once funds are released.</li>
      <li>6. Privacy – All borrower details remain confidential unless required for legal or collection purposes.</li>
      <li>7. Conduct – Rude or disrespectful communication will result in immediate blacklisting.</li>
      <li>8. Agreement – Proceeding with a loan means full acceptance of these terms.</li>
    </ol>
  </section>

  <!-- Section 4: How to Apply -->
  <section>
    <h2>💼 How to Apply</h2>
    <ul>
      <li>1️⃣ Message us on Facebook or Messenger.</li>
      <li>2️⃣ Provide your full name, requested amount, and reason for the loan.</li>
      <li>3️⃣ Wait for verification and approval.</li>
      <li>4️⃣ Receive your funds via GCash or bank transfer.</li>
    </ul>
    <p><i>Note: Processing times may vary depending on verification.</i></p>
  </section>

  <!-- Section 5: Contact Us -->
  <section>
    <h2>📩 Contact Information</h2>
    <p>
      For inquiries or applications:<br>
      📱 Message us on <a href="https://www.facebook.com/" target="_blank">Messenger</a><br>
      📧 Email: <a href="mailto:yourname@email.com">yourname@email.com</a><br>
      📍 Service Area: Philippines
    </p>
  </section>

  <!-- Section 6: Footer -->
  <footer>
    © 2025 Lyonne’s Lending Services — All Rights Reserved.
  </footer>

</body>
</html>
