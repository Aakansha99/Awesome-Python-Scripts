# Auto Birthday Wisher

One forgets to send birthday wishes to friends many times. At such times an automatic birthday wisher comes handy. An automatic birthday wisher via email makes one's life easy. It will send the birthday wishes to friends via email automatically via a server and using an excel sheet to store the data of friends and their birthdays along with email id. It'll send the wishes to friends for all the upcoming years untill we stop the server.

## Setup instructions
## Modules Used
- Pandas
- Datetime
- smtplib

## Configuration
1. Assign the Gmail Id of sender to the GMAIL_ID variable in *line 10* of **"Auto B'Day Wisher.py"** file. (e.g. 'xyz@gmail.com')
2. Similar to first step assign the Gmail password of sender to the GMAIL_PSWD variable in *line 11* of **"Auto B'Day Wisher.py"** file. (e.g. '1234')
3. In **"data.xlsx"** file insert the name of the receiver in second column under *Name*. Similarly update the **Birthday** field with the birth date of receiver in the given format*("%dd-%mm-%YYYY")*. Update the **Dailogue** field with a short message you want to send and the **Email** field with the email of the receiver.
4. Make sure to give permission to your google account from which you're sending email to **Allow less secure apps**. Just turn this *"ON"* from [here](https://support.google.com/accounts/answer/6010255?hl=en#zippy=%2Cif-less-secure-app-access-is-off-for-your-account).
5. Run the command
```bash
python "Auto B'Day Wisher.py"
```
