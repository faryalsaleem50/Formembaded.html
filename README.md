# Formembaded.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
   
</head>
<body>

<div class="container">
    <h2>Our Location</h2>
   
    <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d243647.1945838766!2d-74.25987368747902!3d40.697149409254754!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c2f6df0f14b5f3%3A0xf739e9d1bf6e5f93!2sNew%20York%2C%20NY!5e0!3m2!1sen!2sus!4v1642686200536!5m2!1sen!2sus"
        allowfullscreen="" loading="lazy">
    </iframe>

    <h2>Contact Us</h2>
    <form action="submit_form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea><br><br>

        <button type="submit">Submit</button>
    </form>
</div>
   <audio id="alarmSound" controls>
    <source src="https://actions.google.com/sounds/v1/alarms/digital_watch_alarm_long.ogg" type="audio/ogg">
</audio>

</body>
</html>
