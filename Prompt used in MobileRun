1. Open Microsoft Outlook.

2. Scan all emails received on 15/01/2026.

3. Filter emails where:
   a. The sender’s domain contains "tpc.com", OR
   b. The sender’s name contains "TPC COM" (case-insensitive).

4. For each matching email:
   a. Read the email subject.
   b. Read the email body.

5. Detect deadlines expressed in any form, including:
   a. Explicit dates (e.g., "March 10", "10/03/2026").
   b. Date and time combinations (e.g., "March 10 at 2 PM", "10/03 by 14:00").
   c. Action phrases followed by date or time, such as:
      - fill by
      - submit by
      - respond by
      - complete by
      - due by
      - before
      - no later than
      - deadline is
   d. Time-only phrases, such as:
      - by 2 PM
      - by EOD
      - by end of day
      - by COB
      - by close of business

6. Interpret time expressions using these rules:
   a. "EOD" or "end of day" means 5:00 PM local time.
   b. "COB" or "close of business" means 5:00 PM local time.
   c. If only a time is mentioned, use the date referenced in the email.
   d. If no date is referenced, use the email received date (15/01/2026).

7. If a valid deadline (date or date with time) is identified:
   a. Create a Google Calendar event.
   b. Event title: "TPC Deadline – [Condensed Email Subject]".
   c. Event date and time: use the extracted deadline exactly.
   d. Event description must include:
      - Email subject
      - Sender
      - Exact deadline phrase extracted from the email
   e. Add a reminder notification 30 minutes before the event.

8. If a date is found without a time:
   a. Create an all-day calendar event for that date.

9. Do not create duplicate calendar events for the same email or the same deadline.

10. If no deadline is detected:
    a. Take no action.

11. Execute all steps automatically without asking for any user confirmation.
