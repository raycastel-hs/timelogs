## November 10, 2023 - Friday
- **Time Logs:**
	- Bug fix - Registration data index points to null - 1h
	- Profile specific fields vanish when editing, happens on copy as well - 4h
	- No QR code generated when profile auth method is - 1h
	- Dropdown overflow on small screens - 1h
	- [WIP] save (button) doesn’t work - 1h
- **Task breakdown:**
	- Vainshing fields - Find commit that causes the issue - 1h
	- Vainshing fields - bug tracing - 2h
	- Vainshing fields - bug fix - 1h
	- Registration data index points to null - 1h
- **To do:**
	- [WIP] save (button) doesn’t work - on change username

## November 9, 2023 - Thursday
- **Time Logs:**
	- Tablet view - different sizes on MU device configuration screen - .5h
	- Incorrect color on multiselect - .5
	- Delete profile MU for TDA account should not be disabled (check with old app) - 1h
	- Buttons have no actions - 1h
	- Floating button position when - Portrait/Landscape + Mobile/Tablet + Show/Hide keyboard - 2.5h
	- Save (button) blocks access to last fields - add responsive padding for Floating buttons - 2.5h
- **Task breakdown:**
	- Adjusted `SettingsTileCard` widget
	- Resolved a branch that was not included in a supposed merge
	- Fixed delete account/profile functionality
	- Created wrapper widget for floating buttons to adjust positions with respect to: device orientation, screen size, & keyboard visibility
	- Created responsive padding so contents behind floating buttons can be accessible
- **To do**
	- tone dropdown overflow on small screens
	- [WIP] save (button) doesn’t work - on change username


## November 8, 2023 - Wednesday [LOGGED]
- **Time Logs:**
	- Feedback v2.4.1 - Missing padding on second Privacy Policy - .5h
	- Feedback v2.4.1 - Nationality label is light, licence plate is darker, old color - .5
	- Feedback v2.4.1 - New ranslations, reuse old texts - 1.5h
	- Feedback v2.4.1 - Delete fav data confirmation (check with old app) - 1h
	- Feedback v2.4.1 - Cant change password & change password validation - 1.5h
	- Feedback v2.4.1 - Untranslated texts (Nationality in master data and in vehicle add flow) - 1h
	- Feedback v2.4.1 - On MU on TDA driver the phone setting is nowhere to be found - 1h
	- Feedback v2.4.1 - Save doesn’t work - change username - 1h
	- Other bugs: investigation & reporting - time spent 2h
	- Localization tool - time spent .5h

## November 7, 2023 - Tuesday [LOGGED]
- **Time Logs:**
	- [WIP] Feedback v2.4.1 - no error message when current password is incorrect - .5
	- [WIP] Feedback v2.4.1 - No QR code generated when profile auth method is password - .5
	- Feedback v2.4.1 - No back option - low level - 1h
	- Feedback v2.4.1 - Update localizations, tool - 3h
	- Feedback v2.4.1 - button should be disabled when TAN is empty & invalid - 1h
	- Feedback v2.4.1 - New bugs, Fix Typo, alignments, icons, colors, - 1h
	- Login Problems Screen overflow fix, translation fixes - 1h
- **Task breakdown:**
	- updated tool
	- Create New Page Route for Setup SMS-TAN when navigating from Settings


## November 6, 2023 - Monday [LOGGED]
- **Task breakdown:**
- **Time Logs:**
	- Redesign - Notification Tone Selection Dropdown - 2h
	- Redesign - User information - .5h
	- Redesign - Save button - .5h
	- MU Feedback - Change Driver Name - 1h
	- MU Feedback - New UI, Validation, Change Telephone Number for SMS-TAN UI - 1h
	- Bottom sheet responsive padding - 1h
- **Issues:**
	- No rounded border badius for dropdown menus
- **To do:**
	- Account details save button - dynamic placement/sizes when mobile or tablet
	- Bottom sheet - dynamic padding when mobile / tablet - vehicle component, settings
- **Notes:**

## November 3, 2023 - Friday [LOGGED]
- **Time Logs:**
- **Task breakdown:**
	- CTC - Feedback
		- Adjust new UI colors - .5h
		- Input field behavior - .5h
		- Vehicle card & details - 2h
	- CTC - New UI - Settings Screen
		- [WIP] Notification tone selection - 2h
		- Sound settings, New Dropdown Input, Vibration type - 3h
- **Issues:**
- **To do:**
- **Notes:**

## October 31, 2023 - Monday [LOGGED]
- **Time Logs:**
	- CTC Settings Screen
		- Account Settings - New layout - 1h
		- Sound & notification settings - New layout - 1h
		- Biometrics settings - New UI - 2h
		- New widgets - 4h
- **Task breakdown:**
	- Auth Settings - Biometrics Order - New UI - 2h
	- Account Settings - new layout - 1h
	- Other settings - new layout - 1h
	- New Widgets
		- New dropdown UI - 1h
		- Save Button - .5h
		- Modal sections - 1h
- **To do:**
	- Use updated input fields
- **Notes:**
	- CTC - Settings screen - Replaced auth order `ListTile` with `Container` to enforce padding from Figma


## October 30, 2023 - Monday [LOGGED]
	- Feedback - updated UI - 6h
	- Change username & password validation - 2h
	- Bug: Change username not working - time spent .5h
- **Time Logs:**
	- Change username not working - time spent .5h
	- [WIP] Change username - validation - 1h
	- [WIP] Change password validation - 1h
	- Text Field Inputs - 3h
	- Password Input - 3h
- **Issues:**
- **To do:**
	- Use updated input fields

## October 27, 2023 - Friday [LOGGED]
- **Time Logs:**
	- Settings screen - UI - 3h
	- `ModalDrawerComponent` - UI & localizations - 5h
- **Task breakdown:**
- **To do:**
	- check other widgets using the `ModalDrawerComponent` widget
	- Localizations:
		- other settings
			- settings card - title
			- settings card - description
		- delete account / profile
			- settings card - title
			- settings card - description
			- settings modal - title
		- delete account
			- settings modal - title
			- settings modal - section title
			- settings modal - description
			- settings card - title
			- settings card - description
		- delete profile
			- settings modal - title
			- settings modal - section title
			- settings modal - description
			- settings card - title
			- settings card - description
		- authentication settings
			- settings modal title
			- settings card title
			- settings card description - change_password_and_authentication
		- authentication method
			- settings modal title
			- settings card title
			- settings card description
		- search modal
			- 'There are no items.'
			- 'No results for "$searchKey"'
			- 'Please use a different term.'
		- account_settings - settings card title
		- custom_name_in_list - account settings 
		- delete_account_description - delete account/profile modal descriptio
		- delete_profile_description - delete profile modal description
- **Questions:**
- **Issues:**
	- Change username not working
- **Notes:**
- **Blocked:**
	- CTC Settings Screen Rework - Auth Settings - Change Password - Test


## October 26, 2023 - Tuesday [LOGGED]
- **Time Logs:**
	- CTC Profile-specific form - 4h
	- CTC Setting screen rework - 4h
- **Task breakdown:**
	- CTC Setting screen rework - separation of settings
	- CTC Setting screen rework - conditionally hide/show based on user types
	- CTC Setting screen rework - UI
	- 
- **To do:**
- **Questions:**
- **Issues:**
	- Change username not working [LOGGED]
- **Notes:**
- **Blocked:**
	- CTC Settings Screen Rework - Auth Settings - Change Password - Test

## October 25, 2023 - Tuesday [LOGGED]
- **Time Logs:**
	- CTC Menu Screen rework - 1h
	- CTC Location Screen - [WIP] Bug: Profile-specific form - 1h
	- CTC Setting screen rework;
		- Usecases for UI; sync & tests - 3h
		- Settings form UI - 4h
- **Task breakdown:**
		- Settings form UI - remove unused elements
		- Settings form UI - create reusable elements
	- CTC Menu Screen - footer
	- CTC Menu Screen - prep for responsiveness
- **To do:**
- **Questions:**
- **Issues:**
	- Change username not working
- **Notes:**
- **Blocked:**
	- CTC Settings Screen Rework - Auth Settings - Change Password - Test


## October 24, 2023 - Tuesday [LOGGED]
- **Time Logs:**
- **Task breakdown:**
	- CTC Setting screen rework
		- Auth Setting - Biometrics - 1h
		- Data storage setting - 1h
		- Favorites setting - 1.5h
		- Modal Dropdowns - 1h
		- Hide/Show settings based on user state - 3h
		- [WIP] Usecases for UI sync + test - 1h
- **To do:**
	- Other Settings Modal - Data Storage
	- Other Settings Modal - Vibration
	- Consult biometrics error message UI - password must be selected
	- Make delete favorites setting work
	- Localizations:
		- authentication_method
- **Questions:**
- **Notes:**


## October 23, 2023 - Monday [LOGGED]
- **Time Logs:**
	- CTC Settings Rework - Delete Account/Profile Settings - `1.25h`
	- CTC Settings Rework - Other Settings - Modal - `1.5h`
	- CTC Settings Rework - Other Settings - UI `2h`
	- CTC `ModalDrawerComponent` class - `1.75h`
	- CTC Setting Rework Screen - Manage button, Modal Header Title, Menu Screen - `1h`
	- CTC Menu Screen - `.5h`
- **Task breakdown:**
	- CTC Setting Rework Screen - Other Settings - Update UI
	- CTC Setting Rework Screen - Other Settings - Sound - Move implementation
	- CTC Setting Rework Screen - Other Settings - Vibrate - Move implementation
	- CTC Setting Rework Screen - Other Settings - High Priority Notifications
	- CTC Setting Rework Screen - Other Settings - Data Storage
	- CTC Setting Rework Screen - Other Settings - Connectivity
	- CTC Setting Rework Screen - Delete Account Settings
	- CTC Setting Rework Screen - Delete Profile Settings - New UI
	- CTC `ModalDrawerComponent` - [WIP] Fix spacing between options
	- CTC `ModalDrawerComponent` - UI Spacing
	- CTC `ModalDrawerComponent` - Update conditions to show delete options
	- CTC `ModalDrawerComponent` - Update conditions to show usename and ID
	- CTC Setting Rework Screen - `Manage button`
	- CTC Setting Rework Screen - `Modal Header Title`
	- CTC Setting Rework Screen - Update Menu Screen
- **To do:**
	- CTC Settings Screen Rework - Log on Redmine
	- CTC Settings Screen Rework - ask Marius/Claudiu about `Modal Header Title` UI
	- CTC Settings Screen Rework - ask Marius/Claudiu about data privacy/version number UI
	- CTC Settings Screen Rework - Remove unused cards
	- CTC Settings Screen Rework - Localization - Delete setting header, delete account/profile - copy & title, auth setting header, other setting header
	- CTC Settings Screen Rework - Ensure Authentication Method is Single User only
	- CTC Settings Screen Rework - Auth Settings - Change Password - Test
	- CTC Settings Screen Rework - Account Settings - Change Username - Test
	- CTC Settings Screen Rework - Account Settings - Change Name - Test
	- CTC Settings Screen Rework - Account Settings - Change Telephone - Test
	- CTC Settings Screen Rework - Auth Settings - [WIP] Auth Order View
- **Questions:**
    - Do hints disappear on focus or only when there is input?
- **Notes:**
    - CTC UI: Master data input fields default to `InputFieldStaus.Disabled` - currently overriding to look enabled
	- CTC UI: Not ignoring touch events on disabled state due to existing issue.
	- CTC UI: No focus border for non-text fields
	- CTC UI: Slight movement on text input when focused
	- CTC UI: Input Fields - Figma uses 500 font weight, app uses 600 font weight to match


## October 21-22, 2023 - Saturday/Sunday [LOGGED]
- **Time Logs:**
	- CTC Setting Screen Rework - Delete Account Setting `.5h`
	- CTC Setting Screen Rework - Authentication Setting - `2h`
	- CTC Setting Screen Rework - Authentication Setting View BLoC - `.5h`
	- CTC Setting Screen Rework - Account Settings - `2.5h`
	- CTC Setting Screen Rework - Language Selection - `2h`
	- CTC : Adjust `ModalDrawerComponent` - `1h`
- **Task breakdown:**
	- CTC Setting Rework Screen - Delete Account Card - .5
	- CTC Setting Rework Screen - Authentication Settings - [WIP] Auth Order View Bloc - .5
	- CTC Setting Rework Screen - Authentication Settings - Biometrics and Auth Order - .5
	- CTC Setting Rework Screen - Authentication Settings - Change password - Move implementation - 1h
	- CTC Setting Rework Screen - Authentication Settings Card - .5
	- CTC Setting Rework Screen - Account Settings - Change Telephone - Reuse existing - .5
	- CTC Setting Rework Screen - Account Settings - Change Name - Reuse existing - .5h
	- CTC Setting Rework Screen - Account Settings - Change Username - Implement inside account settings modal - 1.5
	- CTC Setting Rework Screen - Language Selection - Reuse setting implementation - 1.5
	- CTC Setting Rework Screen - Language Selection - Create empty selection input .5
	- CTC Setting Rework Screen - `ModalDrawerComponent` - Update input field order - .5
	- CTC Setting Rework Screen - `ModalDrawerComponent` - Enable add custom children - .5
- **To do:**
	- CTC Settings Screen Rework - Log on Redmine
	- CTC Settings Screen Rework - Other Settings
	- CTC Settings Screen Rework - Delete Account - Delete Account
	- CTC Settings Screen Rework - Delete Account - Delete Profile
	- CTC Settings Screen Rework - Auth Settings - Biometrics - Change Order - resolve nested modals
	- CTC Settings Screen Rework - Auth Settings - Change Password - Test
	- CTC Settings Screen Rework - Account Settings - Change Username - Test
	- CTC Settings Screen Rework - Account Settings - Change Name - Test
	- CTC Settings Screen Rework - Account Settings - Change Telephone - Test
	- CTC Settings Screen Rework - Create Modal Header Text
	- CTC Settings Screen Rework - Auth Settings - [WIP] Auth Order View
- **Issues:**
	- CTC Setting Screen Rework - Account Settings Change username does not ask for password
	- CTC Setting Screen Rework - Other Settings Card - localization
	- CTC Setting Screen Rework - Authentication Settings Card - localization
	- CTC Setting Screen Rework - Authentication Settings Card - localization
	- CTC Setting Screen Rework - Account Settings - Username management - localization
	- CTC Setting Screen Rework - Account Settings - Name management - localization
	- CTC Setting Screen Rework - Account Settings - Telephone management - localization
	- CTC UI: Loading states are not tested on server data - Master Data doesnt have async inputs.
	- CTC UI: Flag margin on phone input exceeds spacing used in Figma
- **Questions:**
    - Do hints disappear on focus or only when there is input?
- **Notes:**
    - CTC UI: Master data input fields default to `InputFieldStaus.Disabled` - currently overriding to look enabled
	- CTC UI: Not ignoring touch events on disabled state due to existing issue.
	- CTC UI: No focus border for non-text fields
	- CTC UI: Slight movement on text input when focused
	- CTC UI: Input Fields - Figma uses 500 font weight, app uses 600 font weight to match


## October 19, 2023 - Thursday [LOGGED]
- **Time Logs:**
	- CTC Redesign: DateTime input `1h`
	- CTC Redesign: Input Fields: Disabled & Loading States `5h`
	- CTC Redesign: Input Fields: TextFieldUtils `2.5h`
	- HSS Okta - Onboarding, Pigeon Docs, Okta Android Docs
- **Task breakdown:**
	- CTC Meeting: Settings Screen - feedback discussion
	- HSS Okta: Onboarding / Pigeon Docs / Okta Android Docs
	- HSS Okta: Getting started on Flutter plugins on Android-specific code
	- CTC Redesign: Implement new UI to DateTime Input
	- CTC Redesign: Input Fields: Loading State (UI & testing)
	- CTC Redesign: Input Fields: Disabled State (UI & testing)
	- CTC Redesign: TextFieldUtils (updated to handle new states)
	- CTC Redesign: Input Fields: Conditionally show/hide loading indicator in place of the clear/dropdown icon
	- CTC Redesign: Input Fields: Conditionally disable touch events on loading/disabled states
	- CTC Redesign: Fix mandatory validation state applied to optional inputs
- **To do:**
	- Settings Screen - Feedback
- **Issues:**
	- CTC UI: Clearing inputs for mandatory fields give valid state. On Master Data, user is allowed to save after clearing inputs.
    - CTC UI: Master data input fields default to `InputFieldStaus.Disabled` - currently overriding to look enabled
	- CTC UI: Not ignoring touch events on disabled state due to existing issue.
	- CTC UI: Loading states are not tested on server data - Master Data doesnt have async inputs.
	- CTC UI: Flag margin on phone input exceeds spacing used in Figma
- **Questions:**
    - Do hints disappear on focus or only when there is input?
- **Notes:**
	- CTC UI: No focus border for non-text fields
	- CTC UI: Slight movement on text input when focused
	- CTC UI: Input Fields - Figma uses 500 font weight, app uses 600 font weight to match


## October 18, 2023 - Wednesday [LOGGED]
- **Time Logs:**
	- CTC Redesign: Create builder to contain new input field design `2h`
	- CTC Redesign: Resolve bugs and minor issues `5h`
	- HSS-Okta: Scan through Okta docs and `HssOktaFlutter` - `1h`
- **Task breakdown:**
	- CTC Consultation
	- CTC Redesign: Fix resetting input fields
	- CTC Redesign: Fix mismatch validations states
	- CTC Redesign: Separate builder for new input field widget
	- Okta: get the app running locally
	- Okta: Okta docs, HSS-Okta-Flutter scan repo
- **Issues:**
    - Master data input fields default to `InputFieldState.disabled` - currently overriding InputFieldStatus.Disabled UI to look like enabled
	- No focus border for non-text fields
	- Slight movement on text input when focused
	- Cant test loading indicator - no loading states for Master Data input fields
	- Flag margin on phone input exceeds spacing used in Figma
	- Figma uses 500 font weight, app uses 600 font weight to match
- **Questions:**
    - Do hints disappear on focus or only when there is input?


## October 17, 2023 - Tuesday [LOGGED]
- **Time Logs:**
	- CTC Redesign: Master Data Input fields - Disabled state `1h`
	- CTC Redesign: Master Data Input fields - Loading State `.5h`
	- CTC Redesign: Master Data Input fields - Error Message Widget `.5h`
	- CTC Redesign: Master Data Input fields - workaround on InputFieldStatus.Disabled issue `1h`
	- CTC Redesign: Master Data Input - Bug & issues: investigation & tests `2h`
	- CTC Redesign: `TextFieldUtils` class UI updates  `4h`
- **Task breakdown:**
	- CTC Redesign: Input Field UI - Added ui design for disabled & loading states
	- CTC Redesign: Input Text Field - Workaround on issue: unable to edit given name and family name
	- CTC Redesign: Input fields - Move error text widget to stack
	- CTC Redesign: Master Data Widget - Issues investigation, tests
	- CTC Redesign: `TextFieldUtils` - Temporary override on InputFieldStatus.Disabled issue
	- CTC Redesign: `TextFieldUtils` - updated Input Text color by state
	- CTC Redesign: `TextFieldUtils` - updated Hint Text color by state
	- CTC Redesign: `TextFieldUtils` - updated label widget by state
	- CTC Redesign: `TextFieldUtils` - updated Background color by state
	- CTC Redesign: `TextFieldUtils` - updated Border color by state
	- CTC Redesign: `TextFieldUtils` - Fixed issue where input Field State & Error message not matching
- **Issues:**
	- Phone Input reloads previous value after tap outside then tapping the input area again if the new value has not been changed after editing.
    - Master Data: Workaround currently in effect - Having initial registration data does not allow Given name & Family name to be edited.
    - Master data input fields default to `InputFieldState.disabled` - currently overriding InputFieldStatus.Disabled UI to look like enabled
	- No focus border for non-text fields
	- Slight movement on text input when focused
	- Cant test loading indicator - no loading states for Master Data input fields
	- Flag margin on phone input exceeds spacing used in Figma
	- Figma uses 500 font weight, app uses 600 font weight to match
- **Questions:**
    - Do hints disappear on focus or only when there is input?
    - Master Data Widget: given name, family name, birth date, nationality does not turn to success state after tapping "save button"
    - Master Data Widget: "Value has changed" validation message only for Given Name, Family Name, Birth Date, & Nationality


## October 16, 2023 - Monday [LOGGED]
- **Time Logs:**
    - New input field designs: bugfix, validation, field states `8h`
- **Task breakdown:**
	- Phone Input Field - validation - 1.5h
	- Date Input Field - Structure & Validation - 2h
	- Search Input Field - set to only focus state, search button - 1h
	- TextfieldUtils - 1
	- Input field label - 1
	- Phone, Text, Date, Multi Select - Read-Only state - .5
	- Bug fix: removing phone number still marks valid input - 1
- **To Dos:**
	- Disabled states
	- Loading States
- **Issues:**
	- input field states are disabled by default
	- flag margin on phone input
	- slight movement on text input when focused
	- remove label controllers and other init state stuff
	- Figma uses 500 font weight, app uses 600 font weight
	- no focus border for non-text fields
	- loading indicator
- **Notes:**
	- No input fields with loading states yet
	- No date & time input yet


## October 13, 2023 - Friday [LOGGED]
- **Time Logs:**
    - Edit form field structure - clear button, error message, label `2h`
	- State to input decoration conversion `1h`
	- Single Select Input `1h`
	- Multi Select Input `2h`
	- Text Input `1h`
	- Phone Input `1h`
- **Task breakdown:**
    - n/a
- **To Dos:**
    - error message, move to stack
    - font is a little thin compared to UI
    - test validations
    - focus border for non-text fields
    - flag margin on phone input
    - slight movement on text input when focused
    - loading indicator
    - test on tablet view


## October 12, 2023 - Thursday [LOGGED]
- **Time Logs:**
    - CTC UI - New Input Fields `8h`
- **Task breakdown:**
    - new input decorations
    - input borders state
    - wrapped the whole thing with container for border styles
    - using stack for validation messages
- **To Dos:**
    - input Prefix icons
    - label icons
    - label - listen to state
    - log time & date
    - move `_validationResult` to textfield utils


## October 11, 2023 - Wednesday
- **Time Logs:**
    - CTC UI: Selection Modal States `2h`
    - CTC UI: Bottom Sheet Implementations `7h`


## October 10, 2023 - Tuesday
- **Time Logs:**
    - CTC UI: Multi-select Input - 2h
    - CTC UI: Master Data Additional languages `1h`
    - CTC UI: Create controllable bottom sheet `3h`
    - CTC Bug Fix: Add Certificate Bottom Sheet `2h`


## October 9, 2023 - Monday
- **Time Logs:**
    - CTC Result `0.5h`
    - Add Component Button `0.5h`
    - Add Vehicle from Favorites List `1h`
    - Primary Button `1.5h`
    - CTC UI - Components `3.5`
    - CTC - Remove warnings `2h`
    - CTC Bug Fix - Add Certificate Bottom Sheet `2.5h`