# PharmaPort

Requirements consists of all the required libraries that are used in the project.
## Overview
- The website provides the facility to store all the medical records like prescriptions given by doctors and connect connect doctors with patients via a authentication mechanism through which the appointment visit gets updated in patient's account and internal feedback mechanism is also available to rate the experience.
## Features
- Authentication service is handled by Google authenticator API which involves OTP Authentication.
- For Payment we use stripe API which doesn’t share the card details with the website and helps through data breach.
- For Storage of uploaded files we are using Amazon s3 bucket which is a cloud service and a cost efficient way of storing files as the cost depends on the usage and not fixed. Provides more flexibility.
