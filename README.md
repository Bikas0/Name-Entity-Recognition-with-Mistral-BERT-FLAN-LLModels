```ini
Name Entity Recognition of Bengali as well English Texts
```
```baash
# LLModel's
google-bert/bert-base-uncased # For English
sagorsarker/bangla-bert-base # For Benglai
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Current Time</title>
    <style>
        .container {
            text-align: center;
            margin-top: 50px;
        }
        
        #clock {
            font-size: 36px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Current Time:</h1>
        <div id="clock"></div>
    </div>
    <script>
        function updateClock() {
            var now = new Date();
            var hours = now.getHours();
            var minutes = now.getMinutes();
            var seconds = now.getSeconds();
            var timeString = hours.toString().padStart(2, '0') + ':' +
                             minutes.toString().padStart(2, '0') + ':' +
                             seconds.toString().padStart(2, '0');
            document.getElementById('clock').textContent = timeString;
        }

        // Update the clock every second
        setInterval(updateClock, 1000);

        // Initial call to display the clock immediately
        updateClock();
    </script>
</body>
</html>

