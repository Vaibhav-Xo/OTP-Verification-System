# OTP-Verification-System
![Screenshot 2024-07-06 095305](https://github.com/Vaibhav-Xo/OTP-Verification-System/assets/172389348/a828ca3a-a8aa-499b-bebd-7e20ba9b5172)

# Project Objective:
Create a system that takes user input in the form of email and sends the user a one time password for verification, providing a simple yet
comprehensive authentication solution. This project can be integrated into a wide range of web applications, mobile apps, and enterprise systems that require robust user authentication.

# Incorporated Libraries:
### 1] SMTP: 
This Python module provides a simple interface for sending email messages from your Python scripts. It allows you to connect to an SMTP server, authenticate, and send email messages programmatically.
  
### 2] RANDOM: 
The Python random module provides a set of functions for generating random numbers. In the context of this project, it is used to generate a unique 6-digit OTP (One-Time Password) that can be sent to the user via email.
  
### 3] EmailMessage: 
This is a class within the email module in Python that provides a convenient way to create and manipulate email messages. It allows you to specify the sender, recipient, subject, body, and other email headers, making it easier to construct and send email messages programmatically.

# Functions Created:
###  1] Connection:
This function connect to the SMTP  server by using SMTP() method and  starts Transport Layer Security(TLS) protocol which facilitate privacy and data security for communication between user and sender. Through login() method  server access the senders email.
![Screenshot 2024-07-06 104745](https://github.com/Vaibhav-Xo/OTP-Verification-System/assets/172389348/839bd89f-963c-476b-98d7-fdd94886ac59)


### 2] Enter Email:
This function allow user to provide input in the form of email and at the same time it validates if the given input is syntactically correct or not and store input inside receiver email.
![Screenshot 2024-07-06 105735](https://github.com/Vaibhav-Xo/OTP-Verification-System/assets/172389348/47e553a7-4dee-423f-9c8d-b5bcee69a9e4)


### 3] Generate & Send Otp:
The first function generates 6 digit OTP with the help of random module and second function creates template of the OTP email by using class EmailMessage   and send it to the user with the help of SMTP's send_message() method.
![Screenshot 2024-07-06 110002](https://github.com/Vaibhav-Xo/OTP-Verification-System/assets/172389348/982da2fa-2289-4d9d-8762-4dcc18274296)


 ### 4] Verify Otp:
 This function allow the user to enter the OTP received via mail and grants access by validating the entered OTP with actual generated OTP.
 ![Screenshot 2024-07-06 110630](https://github.com/Vaibhav-Xo/OTP-Verification-System/assets/172389348/87f4a180-cf45-4551-a50b-d528aa64c9c1)

### 5] Otp Verification:
This method will hold all of the above function inside it.
![Screenshot 2024-07-06 111605](https://github.com/Vaibhav-Xo/OTP-Verification-System/assets/172389348/4eaf6cd7-8090-4f2d-a636-12b30c9a1ad9)

# Results:
![image](https://github.com/Vaibhav-Xo/OTP-Verification-System/assets/172389348/366118d5-58b3-40ab-98a0-2533b4405c87)

# Conclusion:
The Python-based OTP verification program through email provides a sophisticated and secure authentication solution for a wide range of applications like startups, small business, industries etc.

# Future Enhansement:
Potential improvements include mobile app integration, multi-language support, and advanced analytics for user behavior patterns.

### Feel free to add your own magical touches while creating this program...Happy Learning!!! Happy Coding!!! 🙌🌟🔮


