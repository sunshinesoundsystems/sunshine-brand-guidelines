# Booking & Contact Lightbox Copy

---

## Left Side Hero Text

**Line 1 (Yellow):** LET'S  
**Line 2 (Pink):** GROOVE  
**Line 3 (Cyan):** TONIGHT

---

## Form Header

**Main Heading (Yellow):**
EPIC EVENTS NEED EPIC TUNES!

**Subheading (White):**
Hit us up and let's rock this party.

---

## Form Fields

### Row 1: Name Fields (Side by Side)

**Field 1a: First Name**  
**Label:** FIRST NAME *  
**Placeholder:** First name  
**Type:** Text input  
**Required:** Yes

**Field 1b: Last Name**  
**Label:** LAST NAME *  
**Placeholder:** Last name  
**Type:** Text input  
**Required:** Yes

---

### Row 2: Contact Fields (Side by Side)

**Field 2a: Email**  
**Label:** EMAIL *  
**Placeholder:** Email  
**Type:** Email input  
**Required:** Yes

**Field 2b: Phone**  
**Label:** PHONE  
**Placeholder:** Phone  
**Type:** Tel input with country selector  
**Required:** No  
**Note:** Include Spain flag/country code selector

---

### Field 3: Inquiry Type

**Label:** WHAT WOULD YOU LIKE TO INQUIRE ABOUT? *  
**Placeholder:** Select your topic or event type.  
**Type:** Dropdown select  
**Required:** Yes

**Dropdown Options:**
- Select your topic or event type...
- Event DJ Services
- In-House DJ Solutions
- Co-Hosted Events
- Private Events (Wedding, Corporate, etc.)
- Sound System Rental
- General Inquiry

---

### Field 4: Event Date

**Label:** EVENT DATE  
**Placeholder:** [Date picker icon]  
**Type:** Date picker  
**Required:** No

---

### Field 5: Message

**Label:** MESSAGE *  
**Placeholder:** Write your message.  
**Type:** Textarea  
**Required:** Yes  
**Min Height:** 100px

---

## Privacy & Consent Section

### Privacy Notice Header

We respect your inbox and your privacy. **Here's the deal:**

### Privacy Policy Text

When you send us a message, we'll only use your info (like your name and email) to get back to you about your enquiry. No spam, no funny business. For the full scoop, check out our **Privacy Policy**.

**Let us know what works for you:**

---

### Checkbox 1 (Required - Pre-checked)

☑ **Yes, use my details to reply to my enquiry.** (This one's a must!) *

---

### Checkbox 2 (Optional)

☐ **Sure, keep me in the loop with updates, offers, and news from Sunshine Sound Systems.**

---

### Checkbox 3 (Optional)

☐ **Add me to the Sunshine Sound Systems WhatsApp group - I'm all in for event updates and exclusive vibes!** (This only works if you leave your phone number)

---

### Bottom Disclaimer

By hitting submit, you're cool with how we handle things. You can change your mind anytime - just drop us a line.

---

## Submit Button

**Button Text (Normal):** SEND MESSAGE  
**Button Text (Loading):** SENDING...  
**Button Style:** Full-width, yellow background, black text, no border-radius

---

## Success State

**Success Heading:**
MESSAGE SENT!

**Success Message:**
Thanks for reaching out! We'll get back to you within 24 hours to discuss your event.

**Close Button:**
CLOSE

**Visual:** Yellow circle with white checkmark icon

---

## Close Button

**Symbol:** ✕  
**Color:** Pink (#FA5281)  
**Position:** Top-right corner of form area  
**Size:** 2rem  
**Hover:** Rotate 90deg

---

## Validation Messages

**Required Field Error:**
This field is required

**Invalid Email Error:**
Please enter a valid email address

**Message Too Short Error:**
Please provide more details

**General Form Error:**
Oops! Something went wrong. Please try again.

---

## Email Notifications

### Admin Notification Email

**To:** sunshinesoundsystems@gmail.com

**Subject:**
New Booking Inquiry from [First Name] [Last Name]

**Email Body:**
New booking inquiry received:

**Name:** [First Name] [Last Name]  
**Email:** [Email]  
**Phone:** [Phone]  
**Inquiry About:** [Topic/Event Type]  
**Event Date:** [Date]  
**Message:**  
[Message]

**Marketing Opt-ins:**
- Updates & News: [Yes/No]
- WhatsApp Group: [Yes/No]

**Submitted:** [Timestamp]  
**Source:** [Page/Button that triggered form]

---

### User Confirmation Email (Optional)

**Subject:**
We received your message - Sunshine Sound Systems

**Email Body:**
Hey [First Name],

Thanks for reaching out! We've received your inquiry about [Topic/Event Type] and we're excited to help make your event unforgettable.

Our team will review your message and get back to you within 24 hours to discuss the details.

In the meantime, feel free to check out our Instagram [@sunshinesoundsystems] for recent events and inspiration.

Let's make it legendary,  
Sunshine Sound Systems

**Email:** sunshinesoundsystems@gmail.com  
**Instagram:** [@sunshinesoundsystems]

---

## Technical Notes

- Form submits to: sunshinesoundsystems@gmail.com
- Anti-spam: reCAPTCHA v3 (invisible) or honeypot field
- Validation: Client-side (HTML5 + JS) + Server-side
- Success: Auto-close after 5 seconds or manual close
- Error handling: Show inline errors below fields
- Modal layout: Split screen (40% hero text | 60% form)
- Background: DJ/event photo with dark overlay
- Mobile: Stack vertically (hero text above form, full-screen modal)

---

## Accessibility

- All form fields have associated labels in uppercase
- Error messages announced to screen readers
- Focus management: trap focus within modal when open
- ESC key closes modal
- Close button has aria-label="Close"
- Required fields marked with asterisk and aria-required="true"
- Checkbox labels are clickable (expand hit area)
- Color contrast meets WCAG AA standards
