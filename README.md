<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Appointment Scheduler</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Schedule Your Appointment</h1>
  </header>
  <main>
    <section id="calendar">
      <h2>Select a Date</h2>
      <input type="date" id="appointment-date">
    </section>
    <section id="form">
      <h2>Book Your Slot</h2>
      <form id="appointment-form">
        <label for="time-slot">Time:</label>
        <select id="time-slot" required>
          <option value="9:00 AM">9:00 AM</option>
          <option value="10:00 AM">10:00 AM</option>
          <option value="11:00 AM">11:00 AM</option>
          <option value="2:00 PM">2:00 PM</option>
          <option value="3:00 PM">3:00 PM</option>
          <option value="4:00 PM">4:00 PM</option>
        </select>
        <label for="name">Your Name:</label>
        <input type="text" id="name" placeholder="Enter your name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" placeholder="Enter your email" required>
        <button type="submit">Book Appointment</button>
      </form>
    </section>
    <section id="confirmation">
      <h2>Confirmation</h2>
      <p id="confirmation-message"></p>
    </section>
  </main>
  <script src="script.js"></script>
</body>
</html>
