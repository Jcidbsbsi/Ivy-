<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Graduation Congrats!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background: #f9f7f6;
            padding: 50px;
            color: #333;
        }
        .card {
            background: #ADD8E6;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            padding: 20px;
            max-width: 600px;
            margin: 0 auto;
        }
        h1 {
            color: purple;
            font-size: 2.5em;
            margin-bottom: 0.5em;
        }
        p {
            font-size: 1.2em;
            margin: 1em 0;
        }
        .photo {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .hidden {
            display: none;
        }
        .btn {
            padding: 10px 20px;
            font-size: 1em;
            background-color: #ff6f61;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 1em;
        }
        .btn:hover {
            background-color: #e65a50;
        }
        .signature {
            margin-top: 2em;
            font-style: italic;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Congratulations on Your Graduation!</h1>
        <p>Click the button below for a message.</p>
        <button class="btn" onclick="showMessage()">Show Message</button>
        <p id="hiddenMessage" class="hidden">
            Congratulations Ivy for graduating senior high school. I just want to say even though lately we've only become close, I have so much fun every time we're together. From the simple greetings when we see each other to our simple hangouts whenever we have time, those simple memories made my year a lot more fun than it should have been. I had thought about college throughout grade 12, but now it's something I'm not looking forward to as much as I did because I don't want to lose these simple activities we do together.
            <br><br>
            Here we are, graduation day. I know it's not the last time we'll see each other, but something will change. I don't know what it will be, but I have a feeling something will and I'm scared that whatever it is will cause us to move apart. I always say whatever happens, happens, but I hope and pray that won't happen because I want to know you better. Why? Because you make me feel something so rare and that is being wanted and not needed. I always see people coming to me because they need something from me, but you're different. You came even though I have nothing to offer and that is so impactful to me because very few people actually do that, and it might be selfish of me but I don't want that to go away.
            <br><br>
            So whenever you have troubles, tell me. I will do what I can to ease them. If you ever find something you don't like about me, tell me. I want to do everything I can to be a help to you even though I can't do much. I will give my best to help you. I'm writing this just to show you how much I cherish those moments we spend together and just want to again congratulate both of us for graduating. I hope and pray that this won't be goodbye but a simple see you later.
            <br><span class="signature"><br>[IAN]</span>
        </p>
    </div>
    <script>
        function showMessage() {
            document.getElementById('hiddenMessage').classList.toggle('hidden');
        }
    </script>
</body>
</html>

