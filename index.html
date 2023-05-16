<!DOCTYPE html>
<html>
<head>
    <title>ChatGPT Demo</title>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
</head>
<body>
    <h1>ChatGPT Demo</h1>
    <div id="chat-container">
        <div id="chat-log"></div>
        <div id="user-input">
            <input type="text" id="user-message" />
            <button onclick="sendMessage()">Send</button>
        </div>
    </div>

    <script>
        // Your OpenAI API Key
        const apiKey = "YOUR_OPENAI_API_KEY";

        // Base API URL for OpenAI
        const apiUrl = "https://api.openai.com/v1/engines/davinci-codex/completions";

        // Function to send a message to ChatGPT
        function sendMessage() {
            const userInput = document.getElementById("user-message").value;
            if (userInput.trim() === "") return;

            const messageContainer = document.createElement("div");
            messageContainer.className = "message-container";

            const userMessage = document.createElement("div");
            userMessage.className = "user-message";
            userMessage.textContent = userInput;
            messageContainer.appendChild(userMessage);

            document.getElementById("chat-log").appendChild(messageContainer);

            // Prepare the data to send to OpenAI
            const requestData = {
                prompt: userInput,
                max_tokens: 50
            };

            $.ajax({
                url: apiUrl,
                type: "POST",
                headers: {
                    "Content-Type": "application/json",
                    "Authorization": `Bearer ${apiKey}`
                },
                data: JSON.stringify(requestData),
                success: function (response) {
                    const botMessage = document.createElement("div");
                    botMessage.className = "bot-message";
                    botMessage.textContent = response.choices[0].text.trim();
                    messageContainer.appendChild(botMessage);
                },
                error: function (error) {
                    console.log(error);
                }
            });

            document.getElementById("user-message").value = "";
        }
    </script>

    <style>
        #chat-container {
            width: 400px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        #user-input {
            margin-top: 10px;
        }

        .message-container {
            margin-bottom: 10px;
        }

        .user-message {
            background-color: #eee;
            padding: 10px;
            border-radius: 5px;
        }

        .bot-message {
            background-color: #f1f1f1;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</body>
</html>
