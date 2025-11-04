<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lyonne’s Lending Services</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Montserrat", sans-serif;
    }

    body {
      overflow: hidden;
    }

    .container {
      display: flex;
      height: 100vh;
      width: 100vw;
      transition: background 0.6s ease;
      color: white;
    }

    /* Sidebar */
    .sidebar {
      position: absolute;
      right: 0;
      top: 0;
      height: 100vh;
      width: 250px;
      background: rgba(0, 0, 0, 0.6);
      backdrop-filter: blur(8px);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 20px;
    }

    .sidebar button {
      width: 80%;
      padding: 12px;
      background: #ffffff22;
      border: 1px solid white;
      color: white;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
      transition: 0.3s;
    }

    .sidebar button:hover {
      background: white;
      color: black;
    }

    /* Content sections */
    .content {
      flex: 1;
      padding: 60px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      transition: opacity 0.5s ease;
    }

    h1 {
      font-size: 40px;
      margin-bottom: 20px;
    }

    p {
      font-size: 18px;
      line-height: 1.6;
      max-width: 700px;
    }

    .hidden {
      display: none;
    }

    a.btn {
      margin-top: 20px;
      display: inline-block;
      background: white;
      color: black;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      transition: 0.3s;
    }

    a.btn:hover {
      background: #ddd;
    }

    /* Backgrounds */
    #home {
      background: url('YOUR_IMAGE.jpeg') no-repeat center center/cover;
    }

    #inquiry, #terms, #rates, #extension, #proofs {
      background: #444;
    }
  </style>
</head>
<body>
  <div class="container" id="home">
    <div class="content" id="page-content">
      <h1>🏛️ Lyonne’s Lending Services</h1>
      <p>Reliable and transparent lending designed to support your financial needs.</p>
    </div>

    <div class="sidebar">
      <button onclick="showPage('home')">Lyonne’s Lending</button>
      <button onclick="showPage('inquiry')">Inquiry Form</button>
      <button onclick="showPage('terms')">Terms & Conditions</button>
      <button onclick="showPage('rates')">Rates</button>
      <button onclick="showPage('extension')">Extension Policy</button>
      <button onclick="showPage('proofs')">Proofs</button>
    </div>
  </div>

  <script>
    const pages = {
      home: {
        title: "🏛️ Lyonne’s Lending Services",
        text: "Reliable and transparent lending designed to support your financial needs.",
        bg: "url('YOUR_IMAGE.jpeg') no-repeat center center/cover",
      },
      inquiry: {
        title: "🪶 Inquiry Form",
        text: `
          ⚠️ No Inquiry Form = No Transaction<br><br>
          Full Name:<br>
          Age:<br>
          Address:<br>
          Amount to Borrow:<br>
          Date of Payment:<br>
          Reason for Borrowing:<br>
          Source of Income:<br>
          X/Twitter Account:<br>
          Facebook Account Link:<br>
          Pendings: (Lender’s username, amount & date of payment)<br>
          Past Lending Transactions: (List lenders’ names — must have previous transactions)<br>
          <br>
          <a href="https://www.facebook.com/share/17Nt6XBHrS/?mibextid=wwXIfr" class="btn" target="_blank">📩 Send Here</a>
        `,
        bg: "#555",
      },
      terms: {
        title: "📁 Terms & Conditions",
        text: `
        • Only transact with public and active accounts — no new or inactive ones.<br>
        • Strictly no minors.<br>
        • No Inquiry Form = No Transaction.<br>
        • Be honest about pendings (1–2 only).<br>
        • Unresponsive Clients:<br>
        – 12 hours no reply → contact person will be messaged.<br>
        – 24 hours no reply → full exposure.<br>
        • LPF continues until fully paid.<br>
        • Rates are fixed.<br>
        • No transactions for clients with bad records.<br>
        • Submitting the form = agreeing to all terms.<br>
        • Must provide all required details.
        `,
        bg: "#555",
      },
      rates: {
        title: "⚖️ Rates",
        text: `
        💸 Interest Rates:<br>
        • New Clients: 15% / day<br>
        • Regular Clients: 12% / day<br>
        • Trusted Clients: 8% / day (10+ transactions with no delays)<br><br>
        💰 Loan Amount Limits:<br>
        • New Clients: ₱200 max<br>
        • Regular Clients: ₱2,000 max<br>
        • Trusted Clients: ₱10,000 max<br><br>
        🕰️ Duration:<br>
        • New Clients: 1–2 days<br>
        • Regular Clients: 5–7 days<br>
        • Trusted Clients: 7–15 days
        `,
        bg: "#555",
      },
      extension: {
        title: "📜 Extension Policy (Strict Enforcement)",
        text: `
        Extensions are strictly limited to 1 day only and will incur an additional 15% of the total amount.<br><br>
        You must inform me at least 24 hours before your DOP (Date of Payment) if you wish to request an extension.<br><br>
        Failure to do so will automatically result in a ₱100 per hour penalty after your DOP until full payment is made.<br><br>
        No exceptions. No excuses.
        `,
        bg: "#555",
      },
      proofs: {
        title: "📸 Proofs",
        text: `
        Upload or show verified proof of transactions, screenshots, or receipts here.<br><br>
        (You can later add images or links manually.)
        `,
        bg: "#555",
      },
    };

    function showPage(page) {
      const container = document.querySelector('.container');
      const content = document.getElementById('page-content');
      container.style.background = pages[page].bg;
      content.innerHTML = `<h1>${pages[page].title}</h1><p>${pages[page].text}</p>`;
    }
  </script>
</body>
</html>
