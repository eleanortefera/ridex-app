# RideX

RideX is a ride-hailing platform designed to connect passengers, drivers, and platform administrators through a complete transportation management ecosystem.

This repository/package is currently being shared for **testing and evaluation purposes**.

---

## Test Version

The APK included here is a **testing build** of the RideX mobile application.

It is intended for:

- Functional testing
- User interface testing
- Ride flow testing
- Passenger and driver feature testing
- API integration testing
- Bug identification
- General application evaluation

> **Important:** This is not a production release. Some features, data, pricing, locations, accounts, or services may be configured specifically for testing.

---

## RideX Platform

The RideX ecosystem may include:

### Passenger Application

Used by passengers to:

- Register and sign in
- Manage their profile
- Select a ride category
- Enter pickup and destination locations
- Request rides
- View estimated ride information
- Track ride progress
- View trip details and history
- Manage wallet/payment-related features
- View receipts
- Rate completed trips

### Driver Application

Used by drivers to:

- Access their driver account
- Manage availability
- Receive ride requests
- Accept or reject requests
- Navigate through the ride workflow
- View trip information
- Complete rides
- Review earnings and financial information

### RideX Control Center

The web-based administration platform is used by authorized staff to manage areas such as:

- Users
- Staff
- Driver verification
- Vehicle categories
- Pricing and currency
- Driver finance
- Roles and permissions
- Platform operations

Available functionality depends on the permissions assigned to each administrator.

---

# Installing the Test APK

## Android

1. Download the provided `.apk` file.
2. Open the downloaded APK on your Android device.
3. Android may ask you to allow installation from the browser or file manager you used.
4. Allow installation when prompted.
5. Select **Install**.
6. After installation completes, open **RideX**.
7. Sign in using the test credentials provided separately.

Because this is a testing APK and may not be distributed through Google Play, Android may display an installation or security warning.

Only install the APK provided through the authorized RideX testing channel.

---

# Before Testing

For the best testing experience:

- Use an Android device with internet access.
- Enable location services.
- Allow location permission when requested.
- Allow notification permission when requested.
- Make sure you are using the latest APK shared.

Some RideX functions depend on backend services being available.

---

# Recommended Testing Flow

Testers are encouraged to check the application in a realistic sequence:

1. Install the APK.
2. Launch RideX.
3. Sign in or register as instructed.
4. Review profile information.
5. Confirm location access.
6. Select a vehicle/ride category.
7. Set pickup and destination.
8. Review the estimated ride information.
9. Request a ride.
10. Follow the ride through its available stages.
11. Complete the ride.
12. Review trip details and receipt.
13. Review trip history.
14. Report any issue found during the process.

---

# Reporting an Issue

When reporting a bug, please provide as much information as possible.

Include:

**Issue:**  
Brief description of the problem.

**Application:**  
Passenger / Driver / Control Center

**Device:**  
Example: Samsung Galaxy S23

**Android Version:**  
Example: Android 15

**App Version:**  
Version of the APK being tested.

**Steps to Reproduce:**

1. Open...
2. Select...
3. Enter...
4. The issue occurs...

**Expected Result:**  
What you expected the application to do.

**Actual Result:**  
What actually happened.

**Screenshot / Screen Recording:**  
Attach one whenever possible.

---

# Example Bug Report

**Issue:** Ride request does not proceed after selecting a vehicle category.

**Application:** Passenger App

**Steps to Reproduce:**

1. Sign in.
2. Select pickup location.
3. Select destination.
4. Select a vehicle category.
5. Tap the ride request button.

**Expected Result:**  
The ride request should be submitted.

**Actual Result:**  
The application remains on the same screen.

**Evidence:**  
Screenshot or screen recording attached.

---

# Test Data

Please treat accounts, trips, wallet balances, prices, vehicles, drivers, and other information displayed in the testing environment as **test data unless explicitly stated otherwise**.

Do not use real sensitive personal, financial, or confidential information while testing.

---

# Important Testing Notes

- This APK is provided for testing purposes.
- Features may change between builds.
- Test data may be reset.
- Some functions may depend on server/API availability.
- A newer APK may replace an earlier testing version.
- Do not redistribute the APK outside the authorized testing group.
- Do not use the test environment for real transportation transactions unless specifically authorized.

---

# Languages

RideX is designed to support a multilingual user experience.

Depending on the current build and configuration, available languages may include:

- English
- Amharic (አማርኛ)
- Afaan Oromoo
- Arabic (العربية)

Translation coverage may continue to be improved during testing.

---

# Security

Please do not publish or share:

- Test passwords
- API credentials
- Access tokens
- Private API URLs
- Database credentials
- Administrative credentials
- Production secrets

Test login credentials should be distributed separately through an authorized channel.

---

# Feedback

Tester feedback is important during this stage.

Please report:

- Functional bugs
- Incorrect calculations
- Translation issues
- UI/UX problems
- Performance issues
- Location/map problems
- Ride workflow problems
- Payment or wallet issues
- Incorrect receipts
- Permission/access problems
- Unexpected crashes or errors

Screenshots and screen recordings are especially helpful when reporting visual or workflow issues.

---

## Project Status

**Status:** Testing / Development  
**Distribution:** Authorized testing only

RideX is under active development. Functionality, interfaces, pricing rules, and workflows may change as testing continues.