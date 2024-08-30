# WishWork---automatically-wish-birthday
The script automates sending birthday emails based on data from a CSV file. It uses random templates for personalization and Gmail’s SMTP server for sending emails.


**CSV Data Handling**

  Input: birthdays.csv with columns for month, day, name, and email.
  Data Storage: Reads data into a dictionary for quick lookup by date.
  Date Matching

Check: Compares today’s date with the dates in the dictionary to find matches.
**Template Selection**

  Templates: Randomly selects a letter template from letters_template folder.
  Email Sending

**SMTP Server**: Connects to Gmail, logs in, and sends the email with the personalized template.

**Clone the Repository**

git clone https://github.com/yourusername/birthday-email-reminder.git
cd birthday-email-reminder


**Install Libraries**

pip install pandas smtplib

**Prepare Files**

Create birthdays.csv with the required columns.
Add letter templates to letters_template folder.
Update email credentials in main.py.

**Run the Script**

python main.py
This script checks today’s date against the CSV data and sends personalized birthday emails using randomly selected templates.







