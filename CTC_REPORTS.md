# Known Bugs

## Can't change password
- Description: Unable to change password from the settings screen
- Findings:
    - Correct values are being passed to the bloc
    - Logic level / BLoC or API-call problem 
- Steps done: Debug messages are ready for further investigations

## Registration data throws "Does not exist error"
- Description: Some registration data throws "Does not exist error" when edited
- Findings:
    - Not all registration data has this error
    - Only to a specific registration

## [Intermittent] Profiles not fetched from the server
- Description: When selecting a destination on registration screen, profiles are sometimes not fetched from the server

## [Intermittent] Async Suspension on `CreateRegistrationBloc`
- Description: Might be connected to issue: Profiles not fetched from the server

## CDA Login failure 
- Description: Cant login again after going back from privacy policy
- Steps to reproduce:
    1. Must be on MU
    2. Navigate to list of drivers
    3. Add valid CDA credentials - first time login on device
    4. Login
    5. Press back on privacy policy sceeen
    6. Try to login again
- Expected: CDA must be able to login again
- Actual: CDA cannot login with the error: `put error message here`
- Findings: Login successful but is flagged as invalid driver on the carrier.

# Unimplemented
- New input field UIs do not have loading states yet

# Minor Issues
- BG Color after Deleting account is off
- I can pre-set the device name with less than 4 characters.
- Switch widgets have extra vertical padding
- No rounded border badius for dropdown menu items
- Telephone input flag icon has unremovable margins