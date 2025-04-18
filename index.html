<!DOCTYPE html><html>
<head>
  <title>TempMail Inbox</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 20px;
      text-align: center;
    }
    .container {
      max-width: 600px;
      margin: auto;
      background-color: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    input {
      width: 80%;
      padding: 10px;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 5px;
      margin-bottom: 10px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      border: none;
      background-color: #4CAF50;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
    .emails {
      text-align: left;
      margin-top: 20px;
    }
    .email-item {
      padding: 10px;
      border-bottom: 1px solid #ccc;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>TempMail Inbox</h1>
    <input type="text" id="emailAddress" readonly />
    <br>
    <button onclick="generateEmail()">Generate Email</button>
    <div class="emails" id="inbox">
      <p><strong>Inbox will show up here...</strong></p>
    </div>
  </div>  <script>
    function generateEmail() {
      const name = Math.random().toString(36).substring(2, 10);
      const email = `${name}@1secmail.com`;
      document.getElementById("emailAddress").value = email;
      getInbox(name);
    }

    function getInbox(login) {
      const domain = "1secmail.com";
      fetch(`https://www.1secmail.com/api/v1/?action=getMessages&login=${login}&domain=${domain}`)
        .then(response => response.json())
        .then(data => {
          const inbox = document.getElementById("inbox");
          inbox.innerHTML = "";
          if (data.length === 0) {
            inbox.innerHTML = "<p>No emails yet.</p>";
          } else {
            data.forEach(mail => {
              const item = document.createElement("div");
              item.className = "email-item";
              item.innerHTML = `<strong>From:</strong> ${mail.from}<br><strong>Subject:</strong> ${mail.subject}`;
              inbox.appendChild(item);
            });
          }
        });
    }
  </script></body>
</html>
