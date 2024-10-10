**Title**: Work Focus Notifications

**Description**: This shortcut sends hourly notifications counting the number of emails and phone calls received while in Work Focus mode. It displays the counts on the Lock Screen.

**Inputs**:
- None (runs automatically based on Focus mode)

**Actions**:
1. If [Focus Mode is Work]
   - True:
     1. Get Number of Emails
     2. Get Number of Phone Calls
     3. Set Variable
        - Name: Email Count
        - Value: [Number of Emails]
     4. Set Variable
        - Name: Call Count
        - Value: [Number of Phone Calls]
     5. Notify
        - Title: "Work Notifications"
        - Body: "You have [Email Count] new emails and [Call Count] phone calls."
        - Show on Lock Screen: Yes
     6. Wait
        - Duration: 1 hour
     7. Repeat from Action 1

**Outputs**:
- Hourly notifications on the Lock Screen showing the counts of emails and phone calls.
