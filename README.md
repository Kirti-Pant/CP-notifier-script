# Competitive Programming Notifier Script

### Short Description
The **Competitive Programming Notifier Script** is a Python tool designed to keep users informed about upcoming coding competitions from selected websites through desktop notifications, email alerts, and SMS messages.

### Functionalities
- **Desktop Notifications**: Sends instant alerts to the user’s computer.
- **Email Notifications**: Sends detailed emails with competition details.
- **SMS Notifications**: Sends text alerts directly to the user's mobile phone.
- **Competition Monitoring**: Fetches and monitors upcoming competitions from specified websites.
- **Configurable Settings**: Users can enable or disable notification methods and set up their credentials easily.

### Setup Instructions
1. **Install Required Libraries**: Use the following command to install necessary libraries:
   ```bash
   pip install plyer twilio
   ```

2. **Configure Email and SMS Settings**:
   - Update the email credentials (your email and password) in the script.
   - Set up Twilio API credentials (Account SID, Auth Token, and phone numbers).

3. **Run the Script**: Execute the script using Python:
   ```bash
   python notifier_script.py
   ```

### Detailed Explanation of Script
The script operates by checking for upcoming competitive programming events at regular intervals (daily by default). It utilizes:
- `plyer` for sending desktop notifications.
- `smtplib` for sending emails.
- `twilio` for SMS alerts.

In the `check_competitions` function, the user can customize the logic to fetch data from chosen websites (this part is currently a placeholder).

### Output
The script provides notifications in the following forms:
- **Desktop Notification**: A pop-up alert on your computer screen.
- **Email Notification**: An email detailing the competition information.
- **SMS Notification**: A text message sent to your mobile device.



### Author(s)
- Kirti Pant

### Disclaimers
- Ensure that your email account allows less secure apps if using Gmail. Consider using an app password for enhanced security.
- The Twilio service may incur charges based on your usage; ensure you are aware of their pricing.
