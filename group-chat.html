<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Group Chat</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f0f0f0;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            text-align: center;
        }
        #login, #chat {
            text-align: center;
        }
        input {
            padding: 8px;
            width: 70%;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            padding: 8px 16px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
        #chatBox {
            height: 300px;
            border: 1px solid #ccc;
            border-radius: 4px;
            overflow-y: auto;
            padding: 10px;
            margin: 10px 0;
            background-color: #f9f9f9;
        }
        .message {
            margin: 5px;
            padding: 8px;
            border-radius: 4px;
        }
        .message.sent {
            background-color: #007bff;
            color: white;
            margin-left: 20%;
            margin-right: 5%;
        }
        .message.received {
            background-color: #e0e0e0;
            margin-right: 20%;
            margin-left: 5%;
        }
        .message span {
            font-weight: bold;
        }
        .copy-btn {
            margin-left: 5px;
            padding: 2px 8px;
            font-size: 12px;
            background-color: #007bff;
        }
        .copy-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <div id="login">
            <h2>Join Group Chat</h2>
            <input type="text" id="username" placeholder="Enter username (e.g., Admin, Member1)" required>
            <br>
            <button onclick="joinChat()">Join</button>
        </div>
        <div id="chat" style="display: none;">
            <h2>Group Chat</h2>
            <div id="chatBox"></div>
            <input type="text" id="messageInput" placeholder="Type your message...">
            <button onclick="sendMessage()">Send</button>
        </div>
    </div>

    <script>
        let username = '';
        let messages = [];

        function joinChat() {
            username = document.getElementById('username').value.trim();
            if (username) {
                document.getElementById('login').style.display = 'none';
                document.getElementById('chat').style.display = 'block';
                showMessages();
            } else {
                alert('Please enter a username!');
            }
        }

        function sendMessage() {
            const input = document.getElementById('messageInput');
            const text = input.value.trim();
            if (text) {
                messages.push({ sender: username, text: text });
                input.value = '';
                showMessages();
            }
        }

        function showMessages() {
            const chatBox = document.getElementById('chatBox');
            chatBox.innerHTML = '';
            messages.forEach((msg, index) => {
                const div = document.createElement('div');
                div.className = `message ${msg.sender === username ? 'sent' : 'received'}`;
                div.innerHTML = `<span>${msg.sender}:</span> ${msg.text} <button class="copy-btn" onclick="copyMessage(${index})">Copy</button>`;
                chatBox.appendChild(div);
            });
            chatBox.scrollTop = chatBox.scrollHeight;
        }

        function copyMessage(index) {
            const msg = messages[index];
            const text = `${msg.sender}: ${msg.text}`;
            navigator.clipboard.writeText(text).then(() => {
                alert('Message copied!');
            }).catch(() => {
                alert('Failed to copy message.');
            });
        }

        // Send message with Enter key
        document.getElementById('messageInput').addEventListener('keypress', (e) => {
            if (e.key === 'Enter') sendMessage();
        });
    </script>
</body>
</html>
