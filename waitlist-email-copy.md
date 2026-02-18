# Waitlist Email Copy

---

## Email Metadata

**EMAIL TYPE:**
Waitlist Spot Available Notification

**SUBJECT LINE:**
Spots have opened up for ${eventTitle}

**PREVIEW TEXT:**
Great News! A few spots have become available for ${eventTitle}

**TRIGGER:**
Ticket becomes available for waitlisted registrant

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
${eventImageUrl}

---

## Element 3: Headline

**Text:**
GREAT NEWS!

**Format:**
All caps, yellow (#FCF766), Fjalla One

---

## Element 4: Subheadline

**Text:**
A Few Spots Just Opened for ${eventTitle}.

**Dynamic Field:**
`${eventTitle}` – Event name from Wix Events

**Format:**
Large body text, white

---

## Element 5: Main Message - Part 1

**Text:**
Space has opened up for the next ${eventTitle}.

**Dynamic Field:**
`${eventTitle}` – Event name from Wix Events

---

## Element 6: Main Message - Part 2

**Text:**
We wanted to give our waitlist crew the first chance to claim a spot before it goes public. If you're still up for a great time filled with beats, dancing, and excellent people, now's your moment.

---

## Element 7: Event Details

**${eventTitle}**
Event name from Wix Events

**${eventDate}**
Event date from Wix Events

**${eventLocation}**
Event location from Wix Events

**Format:**
Three lines, white text, simple list

---

## Element 8: Call-to-Action Message

**Text:**
Claim your spot to secure your place.

---

## Element 9: Sign-off

**Text:**
Stay Golden,
Sunshine Sound Systems

**Format:**
Two lines, simple signature

---

## Element 10: CTA Button

**Text:**
GRAB YOUR TICKETS

**Link:**
Event ticketing/registration page URL (dynamic)

**Style:**
Yellow button (#FCF766), black text, bold, uppercase

---

## Element 11: Calendar Link

**${calendarLinkUrl}**

**Format:**
Underlined link or button, below main CTA

---

## Element 12: Social Share

**Label:**
Share on social

**Icons:**
- Facebook
- X (Twitter)
- Pinterest

**Functionality:**
Links to social share for each platform

---

## Element 13: Website Link

**Text:**
For more sunny events check out our website

**Link:**
Homepage or events page URL

**Icon:**
→ arrow symbol

---

## Full Email Copy

**Subject:** Spots have opened up for ${eventTitle}

**Preview:** Great News! A few spots have become available for ${eventTitle}

---

[SSS LOGO]

[EVENT PHOTO]

**GREAT NEWS!**

A Few Spots Just Opened for ${eventTitle}.

Space has opened up for the next ${eventTitle}.

We wanted to give our waitlist crew the first chance to claim a spot before it goes public. If you're still up for a great time filled with beats, dancing, and excellent people, now's your moment.

${eventTitle}
${eventDate}
${eventLocation}

Claim your spot to secure your place.

Stay Golden,
Sunshine Sound Systems

[GRAB YOUR TICKETS - YELLOW BUTTON]

${calendarLinkUrl}

---

**Share on social**
[Facebook] [X] [Pinterest]

**For more sunny events check out our website** →

---

## Dynamic Content Fields

**${eventTitle}**
- Source: Wix Events Module, Event Name
- Example: "Sunrise Sessions Vol. 5"

**${eventDate}**
- Source: Wix Events Module, Event Date
- Format: Full date display

**${eventLocation}**
- Source: Wix Events Module, Event Location
- Format: Venue/address

**${eventImageUrl}**
- Source: Wix Events Module, Featured Image
- Used for event photo display

**${calendarLinkUrl}**
- Auto-generated calendar add link
- Allows users to add event to their calendar

**Ticket Link**
- Auto-generated URL to ticket purchase page
- Dynamic based on event

---

## Usage Notes

**When to Use This Email:**
- When a ticket/spot becomes available for a waitlisted person
- Triggered automatically when capacity opens
- Time-sensitive notification

**Do NOT Use For:**
- Initial event announcements
- Regular ticket confirmations
- Event reminders

**Brand Voice:**
- Exciting and urgent (but friendly)
- Exclusive/VIP feel ("waitlist crew")
- Warm and welcoming
- Action-oriented

**Tone Elements:**
- "Great news!" – Positive, exciting opening
- "Waitlist crew" – Community language, VIP treatment
- "First chance" – Exclusivity, urgency
- "Now's your moment" – Call to action, seize the opportunity
- "Great time filled with beats, dancing, and excellent people" – SSS vibe

---

## Urgency & Timing

**Timing:**
Send immediately when spot becomes available

**Urgency Notes:**
- Emphasize limited availability
- "First chance before it goes public"
- Creates FOMO appropriately
- Encourages quick action

---

## Testing Checklist

Before activating automation:
- [ ] Test waitlist trigger mechanism
- [ ] Verify ${eventTitle} populates correctly
- [ ] Verify ${eventDate} displays properly
- [ ] Verify ${eventLocation} shows correctly
- [ ] Check event photo displays
- [ ] Test "GRAB YOUR TICKETS" link works
- [ ] Test calendar link functionality
- [ ] Verify only waitlisted people receive email
- [ ] Test on mobile (iOS/Android)
- [ ] Test in Gmail, Outlook, Apple Mail
- [ ] Confirm social share links work
- [ ] Check immediate delivery timing

---

## Related Emails

- **Ticket Confirmation** – After they claim their spot
- **Registration Confirmation** – For free events
- **Reminder Email** – 2-3 days before event
- **Cancellation Email** – If event canceled

---

**Last Updated:** February 2026  
**Version:** 1.0  
**Contact:** sunshinesoundsystems@gmail.com
