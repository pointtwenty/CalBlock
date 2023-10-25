# CalBlock
import from one Gmail calendar to a second gmail calendar - for people that maintain two or more google calendars

The "blockCalendar" script is a Google Apps Script that helps manage calendar availability by blocking time slots in one Google Calendar based on events from another calendar. Specifically, it retrieves events from an "other calendar" and checks if those events overlap with existing events in the "target calendar." If an event with the same title and timeslot does not already exist in the target calendar, the script creates a new event to block that time slot. This script is useful for individuals or teams who want to sync and manage their availability across different calendars, ensuring that conflicting events are blocked and preventing double bookings.

Requirements and Deployment
Prerequisites

    You need a Google account to use Google Calendar and Google Apps Script. You need to have imported your "other calendar" from any other source (eg. secondary Gmail account)

Setup

    Open Google Apps Script in your web browser.
    Create a new project and name it as desired.
    In the Apps Script editor, replace the existing code with the content of the script file from this repository.
    Customize the script by updating the values for otherCalendarId and targetCalendarId with your actual calendar IDs or URLs.

Deployment

    Click on the Deploy button in the Apps Script editor.
    Choose the desired deployment type (e.g., Web app, Add-on).
    Configure the deployment settings as needed, such as access permissions and execution options.
    Click Deploy to deploy the script.
    After successful deployment, copy the provided URL (if applicable) to trigger the script manually.

Execution

    To execute the script manually, open the provided URL or click the Run button in the Apps Script editor.
    
    The best would be to set-up a trigger to automatically run the script at a specific interval or based on a specific event. Refer to the Apps Script documentation for instructions on setting up triggers.

Please make sure that the Google account used for deployment has appropriate permissions to read events from the "other calendar" and write events to the "target calendar."

If you encounter any issues during setup or deployment, refer to the Apps Script documentation for troubleshooting or reach out for further assistance.
