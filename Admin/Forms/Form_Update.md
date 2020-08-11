# ASPeN Form Update Page (/ASPeN/Admin/Forms/Form_Update.aspx)

## Input Variables

* New = true
  * Displays a success message

## Usage

Update an existing form.

## Fields

### Primary fields

* `About`
  * Header
  * `ID`
    * Integer
    * assigned
  * `Name`
    * String
    * Value shown in management console list
  * `Title`
    * String
    * Value shown at the top of the form
  * `Database`
    * String
    * Set at INSERT
  * `Status`
    * Integer
    * Visibility and lifecycle
  * `Description`
    * String
    * Value shown at top of the form
  * `Introduction`
    * String
    * Value Shown at top of the form
  * `Department`
    * Integer
  * `Fiscal Year`
    * Integer
  * `Fiscal Year Begin Date`
    * Date
  * `Fiscal Year End Date`
    * Date
  * `Grant Year`
    * Integer
  * `Grant Year Begin Date`
    * Date
  * `Grant Year End Date`
    * Date
  * `Form Identification Type`
    * Integer
    * Service
      * Stores Service ID in results
    * Service Participation
      * Stores Service Participation ID in results
  * `Confidential Identifier`
    * Boolean
    * ***DO NOT USE.  ASPeN HAS NO CONFIDENTIALITY FOR RESPONSES!*** ASPeN has unique identifiers for all responses.
  * `Allow Notes By Field`
    * Boolean
    * Add notes icon.  ***KNOWN TO FAIL SPECTACULARLY ON MULTI PAGE FORMS (2020.08.11)***
  * `Related Form Identification Text`
* `Form Availability`
  * Header
  * `Who can see/submit the form?`
    * Header
    * `Display Type`
      * Integer
    * `Admin Responsibility Type`
      * Integer
      * Set at INSERT
    * `Required`
      * Boolean
      * Shows RED Required flag to users
    * Form type dependant
      * Service Type Form
        * `Services`
      * Service Participation Type Form
        * `Service Participation Services`
        * `Service Participations`
  * `When will aspects of the form be available?`
    * Header
    * `Release Date`
    * `Collection Open Date`
    * `Collection Closed Date`
    * `Completed Date`
    * `Inactive Date`
  * `When and to whom will the summary and results be available?`
    * Header
    * `Summary Available Date`
    * `Summary Display Type`
    * `Results Available Date`
    * `Results Display Type`
    * `Download Results Display Type`
* `Form Processing`
  * Header
  * `What process will be used after form submission?`
    * Header
    * `Form Submission Type`
    * `Registration Event`
    * `Enrollment Service`
    * `Continuing Education Program Track Participation (Certification) Continuing Education Program`
    * `Requires Admin Approval`
  * `What will the user see after they submit?`
    * Header
    * `Completed Message`
    * `Completed URL`
    * `User Can Edit On Submitted`
    * `User Can Delete On Submitted`
    * `User Can Edit On Completed`
    * `User Can Delete On Completed`
  * `Email handling`
    * Header
    * `Email Admin Insert`
    * `Email Admin Update`
    * `Email Admin Delete`
    * `Form Response Email Not Submitted Text`
    * `Form Response Email Submitted Text`
    * `Form Response Email Completed Text`
    * `Form Response Email Excluded Text`
* `Record Information`
  * Header
  * `Date Entered`
  * `Created By`
  * `Last Updated`
  * `Last Updated By`

### Secondary Fields

* `Related Items`
  * Header
  * `Form Admins`
  * `Contact Positions`
  * `Form Logo`
  * `Form Pages`
  * `Form Fields`
  * `Child Forms`
  * `Form Tags`
  * `Form Management`
    * Header
    * `Delete Responses`
    * `Create Form`
    * `Copy Form`
  * `Form Responses`
    * Header
    * `Create New Form Response (Select XXXX from dropdown list)`
    * `Form Response - Bulk Excel (.xlsx) Insert/Update`
      * `Upload Spreadsheet`

## Stored Procedures

## Expected outcome
