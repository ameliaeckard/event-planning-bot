# **Event Planning Bot**

A Discord bot for organizing and planning events efficiently. The bot helps gather attendance, track contributions, and ensures no duplicate selections for event items.

---

## **Features**

- **Attendance Tracking**:
  - Users can confirm if they will attend the event.
  - Logs responses along with their Discord usernames to an Excel sheet.

- **Contribution Selection**:
  - Allows users to select items they will bring to the event.
  - Ensures each item can only be selected by one person.

- **Excel Integration**:
  - Automatically logs attendance and contribution data to an Excel file for easy review.

---

## **Setup Instructions**

### **Prerequisites**

- Python 3.8 or higher installed on your system.
- Discord bot token from the [Discord Developer Portal](https://discord.com/developers/applications).
- Required Python libraries:
  ```bash
  pip install discord.py
  pip install openpyxl
  ```

---

### **Installation**

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/event-planning-bot.git
   cd event-planning-bot
   ```

2. Add your bot token to the script:
   - Open the `event_bot.py` file.
   - Replace `YOUR_DISCORD_BOT_TOKEN` with your actual token.

3. Run the bot:
   ```bash
   python event_bot.py
   ```

4. Invite your bot to your server using the OAuth2 link from the Developer Portal.

---

## **Commands**

| Command         | Description                                          |
|------------------|------------------------------------------------------|
| `!start_event`   | Starts an event, prompting users to RSVP and select items to bring. |

---

## **Contributing**

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your fork and submit a pull request.

---

## **License**

This project is licensed under the [MIT License](LICENSE).

---

## **Acknowledgments**

Special thanks to:
- The developers of [discord.py](https://github.com/Rapptz/discord.py) for their amazing library.
- The Discord community for feedback and ideas.
