# TOTP project

<p>The project adds two-factor authentication with the django Two-Factor Authentication library using the django-otp framework to implement a TOTP device. It allows a user to enable 2FA using a QR code with a token generator app. </p>

Based on the [Django-Poll-App](https://github.com/devmahmud/Django-Poll-App)

<h3>Login Page</h3>
<img width="1430" alt="Screen Shot 2022-09-12 at 2 19 11 AM" src="https://user-images.githubusercontent.com/56483334/189586108-0cafa948-9033-407f-97b9-6560f432a9f4.png">

<h4>Page following the Login Page when 2FA is activated</h4>
<img width="1439" alt="Screen Shot 2022-09-12 at 2 13 29 AM" src="https://user-images.githubusercontent.com/56483334/189585392-76082201-e1ad-4778-b2fd-91866cf16785.png">

<h3>Enable 2FA Page</h3>
<img width="1435" alt="Screen Shot 2022-09-12 at 2 16 32 AM" src="https://user-images.githubusercontent.com/56483334/189585856-ecc097ff-a523-4535-9122-c3d0900abd1a.png">

<h3>Setup 2FA Page</h3>
<img width="1440" alt="Screen Shot 2022-09-12 at 1 41 00 AM" src="https://user-images.githubusercontent.com/56483334/189583352-7e729ba4-34fe-4070-a927-b5cd74fac951.png">

<h3>Disable 2FA Page</h3>
<img width="1437" alt="Screen Shot 2022-09-12 at 2 17 03 AM" src="https://user-images.githubusercontent.com/56483334/189585909-54fb02c4-1875-48a1-8b4f-6a5eb9e7823c.png">

<h3>OTP code in /admin</h3>
<img width="1435" alt="Screen Shot 2022-09-12 at 2 06 57 AM" src="https://user-images.githubusercontent.com/56483334/189584611-4563a843-e88b-4c81-b1dc-54545a017cbb.png">
<img width="717" alt="Screen Shot 2022-09-12 at 2 07 15 AM" src="https://user-images.githubusercontent.com/56483334/189584605-2a1e56a1-a2ee-41fc-875c-deb4847da19e.png">

<h3>Error Handling</h3>
<img width="1433" alt="Screen Shot 2022-09-12 at 11 32 29 AM" src="https://user-images.githubusercontent.com/56483334/189696103-240ff708-107d-4789-8783-5a5cfd7ea39a.png">

<img width="1434" alt="Screen Shot 2022-09-12 at 11 32 52 AM" src="https://user-images.githubusercontent.com/56483334/189695867-4c281ed9-f986-4a02-9ca0-3f103f1845c7.png">


<br /><br />
*The url login has been change for /account/login because the Django Two-Factor Authentication library that I used generate that url to handle 2FA login.
