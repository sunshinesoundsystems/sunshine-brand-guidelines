# RSVP Confirmation Email Copy

---

## Email Metadata

**EMAIL TYPE:**
RSVP Confirmation (Free Event Registration)

**SUBJECT LINE:**
Hey ${contact.name.first} - ${eventTitle} RSVP Confirmed ☀️🌙

**PREVIEW TEXT:**
Hey ${contact.name.first}! You're officially on the list for ${eventTitle}.

**TRIGGER:**
Free event RSVP completed (no payment)

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

## Element 3: Headline

**Text:**
YOU'RE ON THE LIST!

**Format:**
All caps, yellow (#FCF766), Fjalla One

---

## Element 4: Greeting

**Text:**
Hey ${contact.name.first} !

**Dynamic Field:**
`${contact.name.first}` – First name from RSVP form

**Fallback:**
"Hey there!" (if name not provided)

---

## Element 5: Main Message

**Text:**
Your registration ${eventTitle} is official. We're pumped to party with you at ${eventLocation}.

**Dynamic Fields:**
- `${eventTitle}` – Event name from Wix Events
- `${eventLocation}` – Event location from Wix Events

---

## Element 6: CTA Button

**Text:**
SEE EVENT DETAILS

**Link:**
Event details page URL (dynamic)

**Style:**
Yellow button (#FCF766), black text, bold, uppercase

---

## Element 7: Sign-off

**Text:**
Stay Golden,
Sunshine Sound Systems

**Format:**
Two lines, simple signature

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
For more sunny events check out our website.

**Link:**
Homepage or events page URL

**Icon:**
→ arrow symbol in circle

---

## Full Email Copy

**Subject:** Hey ${contact.name.first} - ${eventTitle} RSVP Confirmed ☀️🌙

**Preview:** Hey ${contact.name.first}! You're officially on the list for ${eventTitle}.

---

[SSS LOGO]

[EVENT PHOTO]

**YOU'RE ON THE LIST!**

Hey ${contact.name.first} !

Your registration ${eventTitle} is official. We're pumped to party with you at ${eventLocation}.

[${eventLinkText} - YELLOW BUTTON]

Stay Golden,
Sunshine Sound Systems

Questions? Drop us a line at sunshinesoundsystems@gmail.com

---

**Share on social**
[Facebook] [X] [Pinterest]

**For more sunny events check out our website.** →

---

## Dynamic Content Fields

**${contact.name.first}**
- Source: RSVP form, First Name field
- Fallback: "there" (as in "Hey there!")
- Example: "Jamie"

**${eventTitle}**
- Source: Wix Events Module, Event Name
- Example: "Sunrise Sessions Vol. 5"

**${eventLocation}**
- Source: Wix Events Module, Event Location
- Format: Venue name or address
- Example: "The Beach House" or "Xàbia"

**${eventLinkText}**
- Auto-generated button text for event link
- Typically: "See Event Details" or similar
- Dynamic based on Wix configuration

**Event Details Link**
- Auto-generated URL to event page
- Example: sunshinesoundsystems.com/events/sunrise-sessions-vol-5

---

## Usage Notes

**When to Use This Email:**
- Free event RSVPs
- No-charge registrations
- Guest list confirmations
- Events without ticket purchase

**Do NOT Use For:**
- Paid ticket purchases (use Ticket Confirmation email)
- Waitlist notifications (use Waitlist email)
- Event reminders (use Reminder email)

**Brand Voice:**
- Casual and welcoming
- Excited and energetic
- Community-focused
- Music/vibe-oriented

**Tone Elements:**
- "You're on the list!" – Exclusive, VIP feel
- "We're pumped to party with you" – Excited, personal
- "Hey [Name] !" – Casual, friendly greeting (note the space before !)
- Location mention – Makes it feel real and tangible
- "Stay Golden" – Signature sign-off

---

## Copy Differences from Other Emails

**vs Ticket Confirmation:**
- "You're on the list" vs "Your tickets are ready"
- No ticket download button
- Mentions location in main message
- More welcoming, less transactional

**vs Waitlist Email:**
- Confirmation vs opportunity
- "Official" vs "claim your spot"
- Less urgent, more celebratory

---

## Testing Checklist

Before activating automation:
- [ ] Test with free RSVP registration
- [ ] Verify ${contact.name.first} populates correctly
- [ ] Verify ${eventTitle} displays event name
- [ ] Verify ${eventLocation} shows correctly
- [ ] Check ${eventLinkText} button displays properly
- [ ] Test event details link works
- [ ] Test on mobile (iOS/Android)
- [ ] Test in Gmail, Outlook, Apple Mail
- [ ] Verify social share links work
- [ ] Confirm instant delivery after RSVP
- [ ] Check event photo displays correctly
- [ ] Verify no payment/ticket language appears

---

## Alternative Subject Lines

1. Hey ${contact.name.first} - ${eventTitle} RSVP Confirmed ☀️🌙 *(current)*
2. You're In – ${eventTitle} RSVP Confirmed ✨
3. See You There – ${eventTitle} RSVP Confirmed 🎵
4. ${contact.name.first}, You're On The List for ${eventTitle} ☀️

---

## Related Emails

- **Ticket Confirmation** – For paid events (with ticket download)
- **Reminder Email** – 2-3 days before event
- **Waitlist Email** – When spots open
- **Cancellation Email** – If event canceled

---

**Last Updated:** February 2026  
**Version:** 1.0  
**Contact:** sunshinesoundsystems@gmail.com
