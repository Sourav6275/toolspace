<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="TimeSpace - A collection of powerful AI and non-AI tools accessible in one click.">
    <title>TimeSpace - All-in-One Tools</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1>TimeSpace</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#tools">Tools</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to TimeSpace, your go-to hub for powerful AI and non-AI tools. Experience seamless, one-click access to productivity-enhancing utilities.</p>
    </section>
    
    <section id="tools">
        <h2>Tools</h2>
        <div class="tool-grid">
            <button onclick="generateQR()">QR Code Generator</button>
            <button onclick="convertPDF()">PDF Converter</button>
            <button onclick="textToSpeech()">Text to Speech</button>
            <button onclick="aiImageGenerator()">AI Image Generator</button>
            <button onclick="passwordGenerator()">Password Generator</button>
            <button onclick="bmiCalculator()">BMI Calculator</button>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 TimeSpace. All rights reserved.</p>
    </footer>
    
    <script>
        function generateQR() { alert("QR Code Generator Activated"); }
        function convertPDF() { alert("PDF Converter Activated"); }
        function textToSpeech() { alert("Text to Speech Activated"); }
        function aiImageGenerator() { alert("AI Image Generator Activated"); }
        function passwordGenerator() { alert("Password Generator Activated"); }
        function bmiCalculator() { alert("BMI Calculator Activated"); }
    </script>
</body>
</html>
