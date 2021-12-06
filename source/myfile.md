# CA Mobile Athenticator Soft Token

### - [Enrollment Process](#Enrollment-Process)

### - [Self Service CA Soft Token](#Self-Service-CA-Soft-Token)

> - [Self-Reset CA Soft Token](#Self-Reset-CA-Soft-Token)
> - [Self-Unlock CA Soft Token]()



### <span style="color:red"> IMPORTANT NOTES:

The 8 digit code of the CA Mobile Authenticator will appears regardless of correct/wrong unlock pin entered. This is a security feature to prevent malicious person from guessing your unlock pin.

<u>Scenario as below:</u>

- Wrong unlock PIN + 8 digit code = failed login into System.
- Correct unlock PIN + 8 digit code = successful login

Therefore, <span style="color:red">**PLEASE REMEMBER YOUR UNLOCK PIN.**

If you have any further enquiry with the CA Soft Token, kindly contact Maybank Helpdesk at

- Malaysia : **1800-88-1008**
- Singapore : **800-6011-304**
- Email : ***maybankhelpdesk@maybank.com.my***

### Enrollment Process

1. Download **"CA Mobile Authenticator"** App from either [**Google Play Store**](https://play.google.com/store/apps/details?id=com.ca.sec.aa.authenticator&hl=en&gl=US) or [**Apple App Store**](https://apps.apple.com/us/app/ca-mobile-authenticator/id1180629016)

2. Access to [**Maybank Enrollment**](https://softtoker.maybank.com/enroll) or [172.31.172.219](https://172.31.172.219:8433/enroll) with you Maybank laptop (via Internal Maybak Network)

3. Enter you Windows ID (PF Number) & Windows Password, select "Enroll Soft Token" options, and click "Submit"

4. An One Time Pin (OTP) will be sent to your Maybank mailbox. The 8 digit OTP code is
   valid for 5 minutes.

5. Enter the OTP code to the OTP field and click “Submit”

6. A QR code will be generated. The QR code is **valid for 120s (2 mins)**.

7. Open the CA Mobile Authenticator App from your mobile phone and select “Scan QR
   Code”.

8. Scan the QR code appears on your Web browser and wait for system to enrol you.

9. Upon successfully enrolled, user is required to Enter a 6 digit Pin. This Unlock PIN will be
   used to unlock the CA Mobile Authenticator App.

10. Message of Account successfully added will appear once the Unlock PIN is set.

---

### Self Service CA Soft Token

#### Prerequisite / Method of Access

- CA Soft Token ([CA Mobile Authenticator])
- Active AD ID and password (Domain: Maybank-MY/Maybank-GM/Etiqa-MY/Global)
- Setup Secret Question in Access Management Portal.

#### Self-Reset CA Soft Token

1. Open Google Chrome browser and login to [**Access Management Portal**](https://access.maybank.com)

2. Key in your 8 digits PF number and select **“Secret Question”** as authentication method then click **“Submit”**

3. Answer your secret questions appear on screen then **“Submit”**.

4. Below 2<sup>nd</sup> level logon screen will be loaded if you successfully passed the authentication. Login with your AD ID and Password

5. After login, select “Self Service CA Soft Token” module.

6. Select “Reset OTP Step 1 – Reset Mobile OTP PIN” at the left panel then read the Note carefully to understand the details then check your ID details show on screen then Click “Submit”

7. After click “Submit”, system will generate a request ID for your future references then click “OK” and proceed to next step.

8. Select “Reset OTP Step 2 - View Activation Code” and confirm the “Activation Code Status” is show Active and the “Activation Code Expiration Date” should be showing the future date(next 48 hours) and Activation Code show 8 digits numeric.

9. Launch “CA Mobile Authenticator” app and click “Back” arrow on left top corner then click on “Add Account” and then select “No QR

10. Enter the require details accordingly from the screen into the “CA Mobile ```

```Authenticator” app
Provisioning URL : https://access.maybank.com/motpn
User Identifier : -Your PF Number
Activation Code : -Refer above Activation Code field-
```

11. You will be prompt to set your 6 digits numeric Unlock PIN twice then select "Submit" to complete the reset process.

12. Message of Account added successfully will appear once the Unlock PIN is set and you had completed the self-reset CA Soft Token process.

---

### Self Service CA Soft Token

1. Open Google Chrome browser and login to [**Access Management Portal**](https://access.maybank.com)

2. Key in your 8 digits PF number and select **“Secret Question”** as authentication method then click **“Submit”**

3. Answer your secret questions appear on screen then **“Submit”**.

4. Below 2<sup>nd</sup> level logon screen will be loaded if you successfully passed the authentication. Login with your AD ID and Password

5. After login, select “Self Service CA Soft Token” module.

6. Select “Unlock CA Soft Token Only” then check CA Soft Token ID and CA Soft Token Status.

   <u>Note:</u>

   - No action/option to unlock your CA Soft Token if your CA Soft Token Status is show “Active”
   - The option to unlock your CA Soft Token will be available to submit if your CA Soft Token Status is show “Locked or Inactive”

   <u>Sample:</u>

   **CA Soft Token Status is show “Active”**
   **CA Soft Token Status is show “Locked or Inactive”.**

7. Check/Tick the option “Unlock your CA Soft Token” then click submit to unlock your CA Soft Token

8. After click “Submit”, system will generate a request ID for your future references then click “OK” to complete the unlock process.

9. Return back to “Unlock CA Soft Token Only” to check your CA Soft Token Status should be showing “Active”.
