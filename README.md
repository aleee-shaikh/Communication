# Communication
Communication Sample project architecture having only the communication classes (Email, SMS, Whatsapp, Chat)

# Supported .Net Version
This project supports .NET applications that utilize .NET Framework 3.5+ or higher

# Dependencies
- Nuget package Newtonsoft
- System.IO
- System.Net 

# Sample Usage
The examples below show how to use the communication(SMS,Email) classes

# Code
```
//Send Email
Communication.Email.sendEmail("fromEmail@test.com","ToEmail1@test.com;ToEmail2@test.com","Test Subject","Test Message");

//Send SMS via Twilio Library
Communication.SMS.Twilio_SMS.SendSMS("121121", "test sms message", "132222332", "332223232323");

//Send SMS via TheTexting Library
Communication.SMS.TheTexting_SMS.SendSMS("54454544545", "test sms message");
```
