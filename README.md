🌍 World Clock Widget — Java Swing

A lightweight, always-on-top World Clock Desktop Widget built using Java Swing.
It displays real-time clocks for multiple countries, supports dark/light themes, and includes system tray minimization functionality.

✨ Features
🕒 Real-Time Clocks

Displays current date and current time of a selected country.

Automatically converts and shows other countries' times.

Updates every 1 second using a Swing Timer.

🌙 Dark / Light Theme Toggle

Switch instantly between Dark Mode and Light Mode.

Smooth UI color updates.

📌 Always-On-Top Widget

Stays above all windows.

Draggable — move anywhere on your desktop.

Undecorated window for a clean widget appearance.

🖥️ System Tray Support

Minimize widget to the system tray.

Tray menu:
✔️ Open
✔️ Exit

Auto-generated mini clock icon.

🌐 Supported Countries
Country	Time Zone ID
India	Asia/Kolkata
USA	America/New_York
UK	Europe/London
Australia	Australia/Sydney
Japan	Asia/Tokyo
Dubai	Asia/Dubai
📦 Technologies Used

Java 8+

Swing

ZonedDateTime, ZoneId

SystemTray, TrayIcon

Custom draggable window & UI


🖼️ Screenshots 
![WhatsApp Image 2025-12-03 at 7 04 13 PM](https://github.com/user-attachments/assets/ed53ef96-96cc-4b8a-9d51-a3a421de0805)

![WhatsApp Image 2025-12-03 at 7 04 50 PM](https://github.com/user-attachments/assets/c1b99f90-ca60-4237-8b90-d9203e2b7775)


🧩 How It Works
Time Conversion
ZonedDateTime inputTime = ZonedDateTime.now(ZoneId.of(selectedZone));
ZonedDateTime converted = inputTime.withZoneSameInstant(ZoneId.of(targetZone));

Theme Switching

Dark/Light colors update UI components dynamically.

Tray Support

Automatically generates a 16×16 clock icon and supports restore/exit actions.

🛠️ Future Enhancements (Optional)

Add more time zones

Add alarms or reminders

Add custom user-added countries

Add modern UI with JavaFX

📄 License

This project is open-source. You may modify or reuse freely.
