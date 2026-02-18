# Cancellation Email Copy

---

## Email Metadata

**EMAIL TYPE:**
Event Cancellation Notification

**SUBJECT LINE:**
⚠️ Change of Plans – ${eventTitle} Canceled ⚠️

**PREVIEW TEXT:**
We're sorry to say that due to unforeseen circumstances, we have to cancel ${eventTitle}.

**TRIGGER:**
Event canceled by organizer

**PLATFORM:**
Wix Email Automations

---

## Element 1: Logo

**Image:**
Sunshine Sound Systems logo (gold/yellow version)

**Alt Text:**
Sunshine Sound Systems

**Link:**
Homepage URL

---

## Element 2: Event Photo

**Image:**
Event featured image from Wix Events

**Alt Text:**
${eventTitle}

**Dynamic:**
Event image from Wix Events Module

---

## Element 3: Greeting

**Text:**
Hey ${contact.name.first},

**Dynamic Field:**
`${contact.name.first}` – First name from registration/purchase

**Fallback:**
"Hey," (if name not provided)

---

## Element 4: Main Message - Part 1

**Text:**
We're sorry to say that due to unforeseen circumstances, we have to cancel ${eventTitle}.

**Dynamic Field:**
`${eventTitle}` – Event name from Wix Events

---

## Element 5: Main Message - Part 2

**Text:**
You'll receive a full refund within 5–7 business days. If we reschedule, you'll be the first to hear.

---

## Element 6: Main Message - Part 3

**Text:**
Thanks for understanding—we'll be back soon with something special.

---

## Element 7: Sign-off

**Text:**
Sunshine Sound Systems

**Format:**
Single line (no "Stay Golden,")

---

## Element 8: Contact Information

**Text:**
Questions? Drop us a line at sunshinesoundsystems@gmail.com

**Email Link:**
mailto:sunshinesoundsystems@gmail.com

**Format:**
White text with blue linked email

---

## Element 9: Social Share

**Label:**
Share on social

**Icons:**
- Facebook
- X (Twitter)
- Pinterest

**Functionality:**
Links to social share for each platform

---

## Element 10: Website Link

**Text:**
For more sunny events check out our website

**Link:**
Homepage or events page URL

**Icon:**
→ arrow symbol in circle

---

## Full Email Copy

**Subject:** ⚠️ Change of Plans – ${eventTitle} Canceled ⚠️

**Preview:** We're sorry to say that due to unforeseen circumstances, we have to cancel ${eventTitle}.

---

[SSS LOGO]

[EVENT PHOTO]

Hey ${contact.name.first},

We're sorry to say that due to unforeseen circumstances, we have to cancel ${eventTitle}.

You'll receive a full refund within 5–7 business days. If we reschedule, you'll be the first to hear.

Thanks for understanding—we'll be back soon with something special.

Sunshine Sound Systems

Questions? Drop us a line at sunshinesoundsystems@gmail.com

---

**Share on social**
[Facebook] [X] [Pinterest]

**For more sunny events check out our website** →

---

## Dynamic Content Fields

**${contact.name.first}**
- Source: Registration/purchase form, First Name field
- Fallback: "" (just "Hey,")
- Example: "Jamie"

**${eventTitle}**
- Source: Wix Events Module, Event Name
- Example: "Sunrise Sessions Vol. 5"

---

## Usage Notes

**When to Use This Email:**
- Event must be canceled
- After cancellation decision is made
- For both free and paid events
- Send as soon as possible after cancellation

**Do NOT Use For:**
- Event postponements (if rescheduling, use different messaging)
- Venue changes (use update email)
- Regular event reminders

**Brand Voice:**
- Apologetic but not overly dramatic
- Honest and direct
- Reassuring
- Forward-looking

**Tone Elements:**
- "We're sorry to say" – Apologetic opening
- "Unforeseen circumstances" – Professional, not overly specific
- "You'll be the first to hear" – Reassuring, maintains connection
- "Thanks for understanding" – Appreciative
- "We'll be back soon with something special" – Hopeful, forward-looking
- No "Stay Golden," – More serious/respectful tone

---

## Key Differences from Other Emails

**vs Confirmation Emails:**
- No headline/title
- No CTA button
- No "Stay Golden," sign-off
- Apologetic tone vs celebratory
- Focus on refund and next steps

**Unique Elements:**
- Warning emoji in subject (⚠️)
- Refund information (5–7 business days)
- Promise to notify if rescheduled
- Simpler sign-off (just company name)

---

## Refund Information

**For Paid Events:**
- Full refund within 5–7 business days
- Automatic processing
- No action required from user

**For Free Events:**
- No refund information needed
- Focus on apology and future events

---

## Testing Checklist

Before activating automation:
- [ ] Test cancellation trigger
- [ ] Verify ${contact.name.first} populates correctly
- [ ] Verify ${eventTitle} displays event name
- [ ] Check subject line displays warning emoji correctly
- [ ] Test on mobile (iOS/Android)
- [ ] Test in Gmail, Outlook, Apple Mail
- [ ] Verify social share links work
- [ ] Confirm sends immediately after cancellation
- [ ] Check event photo displays correctly
- [ ] Verify email link works

---

## Alternative Subject Lines

1. ⚠️ Change of Plans – ${eventTitle} Canceled ⚠️ *(current)*
2. ${eventTitle} Has Been Canceled ⚠️
3. Important: ${eventTitle} Cancellation Notice
4. We Have to Cancel ${eventTitle} ⚠️

---

## Related Emails

- **Order Confirmation** – Original purchase confirmation
- **Ticket Confirmation** – Original ticket delivery
- **RSVP Confirmation** – Original RSVP confirmation
- **Reminder Email** – May have been sent before cancellation

---

## Legal/Policy Notes

- Refund policy: Full refund within 5–7 business days
- From SSS Event Policy document
- Automatic refund processing
- User will be first to know if rescheduled

---

**Last Updated:** February 2026  
**Version:** 1.0  
**Contact:** sunshinesoundsystems@gmail.com
