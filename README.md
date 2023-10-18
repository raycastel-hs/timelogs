## October 18, 2023 - Wednesday
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


## October 17, 2023 - Tuesday
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


## October 16, 2023 - Monday
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


## October 13, 2023 - Friday
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


## October 12, 2023 - Thursday
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