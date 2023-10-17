## October 17, 2023 - Tuesday
- **Time Logs:**
	- CTC Redesign: Master Data Input fields - Disabled states `1.5h`
	- CTC Redesign: Master Data Input fields - Loading States `.5h`
	- CTC Redesign: Master Data Input fields - Disabled states `1.5h`
	- CTC Redesign: Master Data Input - Tests: bug investigation, input & tests `1.5h`
	- CTC Redesign: Master Data Input fields - workaround on InputFieldStatus.Disabled issue `1h`
- **Task breakdown:**
	- CTC Redesign: Text Field - Added ui design for disabled state - .25
	- CTC Redesign: Master Data Widget - Bugs, issues investigation, tests - 1.5h
	- CTC Redesign: `TextFieldUtils` - Temporary override on InputFieldStatus.Disabled issue - 1
	- CTC Redesign: `TextFieldUtils` - updated Input Text color by state - .5
	- CTC Redesign: `TextFieldUtils` - updated Hint Text color by state - .5
	- CTC Redesign: `TextFieldUtils` - updated label color by state - .5
	- CTC Redesign: `TextFieldUtils` - updated Background color by state - .5
	- CTC Redesign: `TextFieldUtils` - updated Border color by state - .5
	- CTC Redesign: `TextFieldUtils` - Workaround - Input Field State & Error message not matching - 1h
- **To Dos:**
	- Error Widget
- **Bugs:**
    - Having initial registration data does not allow Given name & Family name to be edited - intermittent
- **Issues:**
    - Master Data Widget: given name, family name, birth date, nationality does not turn to success state after tapping "save button"
    - Master Data Widget: Adding a location gives "Value has changed" validation message to mandatory textfields
    - Master Data Widget: "Value has changed" validation message does not show up when changing primary language
    - Master data input fields default to `InputFieldState.disabled`
	- Master Data input fields are disabled - currently overriding InputFieldStatus.Disabled UI
	- flag margin on phone input exceeds spacing used in Figma
	- slight movement on text input when focused
	- Figma uses 500 font weight, app uses 600 font weight to match
	- no focus border for non-text fields
	- cant test loading indicator

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
    - move _validationResult to textfield utils


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