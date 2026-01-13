# doordash-driver-app-bugs-part6
When accepting **two combined (stacked) orders**, tapping the **“Directions”** button for the **first pickup location** opens the navigation screen briefly, but it immediately navigates back to the previous screen. As a result, navigation cannot be used to reach the store from within the DoorDash Driver (Dasher) app.

# Bug Report
**Title:** Navigation opens briefly then immediately closes when tapping “Directions” for first pickup in combined orders


---

## Steps to Reproduce
1. Open the **DoorDash Driver (Dasher)** app.
2. Accept **two combined (stacked) orders**.
3. Go to the pickup screen for the **first order**.
4. Tap the **“Directions”** button.

---

## Expected Behavior
- Tapping **“Directions”** should open navigation and remain on the navigation screen.
- The driver should be able to use navigation to reach the pickup location.

---

## Actual Behavior
- Navigation screen opens briefly.
- The app immediately returns to the previous pickup screen.
- Navigation cannot be used from within the app.

---

## Frequency
- Occurs once.

---

## Environment
- **Application:** DoorDash Driver (Dasher) app  
- **Platform:** Android 
- **App Version:** 8.61.6
- **Date Observed:** Dec 24, 2025
- **Network:** Mobile data

---

## Impact
- Prevents drivers from using in-app navigation for order pickup.
- Forces drivers to manually open a navigation app.
- Slows down the pickup process during combined deliveries.
---

