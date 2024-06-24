<!DOCTYPE html>
<html>
<head>
    <title>Background Color Changer</title>
    <script>
        // Prompt for user's name
        var userName = prompt("Please enter your name:");
        document.write("Hello, " + userName + "!");

        // Prompt for user's age and check if adult
        var userAge = prompt("Please enter your age:");
        var isAdult = (userAge >= 18) ? "an adult" : "not an adult";
        alert("You are " + isAdult);

        // Function to change background color based on user input
        function changeBackgroundColor() {
            var color = prompt("Enter a color name or hex value:");
            document.body.style.backgroundColor = color;
        }
    </script>
</head>
<body>
    <button onclick="changeBackgroundColor()">Change Background Color</button>
</body>
</html>
