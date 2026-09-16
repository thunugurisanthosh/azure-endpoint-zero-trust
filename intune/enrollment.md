# Intune Enrollment

## Goal
Enroll a Windows 11 test endpoint into Microsoft Intune.

## Device
WIN11-01

## High-Level Procedure
1. Open Microsoft Intune admin center.
2. Configure Windows enrollment for test users.
3. On the Windows 11 endpoint, connect the work/school account.
4. Authenticate with the test Entra user.
5. Confirm the device appears in Intune → Devices → All devices.
6. Trigger Sync.
7. Verify the last check-in time.

## Validation
Expected device:
WIN11-01

Expected management state:
Managed by Intune

## Screenshot
screenshots/02-intune-device.png
