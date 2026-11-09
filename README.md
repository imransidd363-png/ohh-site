# Operation House Hack, production site files

Seven standalone HTML files. Each one is self contained (fonts, CSS, and JavaScript are all inline), so you paste the contents of each file into a GoHighLevel page or funnel step as Custom Code.

## Files and where they go

1. `1-home.html` — Home
2. `2-how-it-works.html` — How It Works, watch the VSL then book a call, calendar embed goes here
3. `3-properties-calculator.html` — Properties and the house hack calculator
4. `4-confirmed.html` — Confirmed, the booking thank you page
5. `5-legal.html` — Terms and Privacy, combined
6. `6-sell-a-property.html` — Sell a Property, the full seller funnel, one page
7. `7-resources.html` — Resources, the educational long form content

## Only two things left for you to paste in

- **How It Works**: the hero video is a placeholder, marked `GHL VIDEO EMBED SLOT`. Swap it for your GoHighLevel video embed, or YouTube or Vimeo.
- **How It Works**: the calendar box right below it is a placeholder, marked `GHL CALENDAR EMBED SLOT`. Swap it for your GoHighLevel calendar widget embed.

Everything else is finished, real content, no other placeholders anywhere in the site.

## What changed in this build

- The quiz is gone entirely. How It Works and the old Get Started page are merged into one page: watch the video, then book straight off the calendar. No qualifying questions.
- "See If You Qualify" is gone everywhere, replaced with "Book a Call."
- The scroll driven house construction animation is removed from Home, you said it didn't look good and it's out.
- The gold dust drift now runs on every page, not just Home, as a fixed background layer.
- The house hack calculator on the Properties page is rebuilt properly: enter total units and it generates a rent field for each unit you do not occupy, then shows down payment needed, monthly income, a full expense breakdown (mortgage, tax, insurance, HOA, reserve), monthly cash flow, estimated annual depreciation on the standard 27.5 year IRS schedule, and the projected value in 5 years based on an editable appreciation rate.
- IDX is out of this build entirely, by your call. The three property cards are real, good looking example listings with real photos, not a live feed. If IDX Broker ever gets approved later, its widget snippet can drop into that same grid.
- SEO is built into every page: real title tags, meta descriptions, Open Graph tags, canonical URLs, and Organization/RealEstateAgent JSON-LD schema, all in the page head.
- A new Resources page covers five real questions in long form: what house hacking is, how VA loans actually work on a 2 to 4 unit property, the real numbers, renting vs house hacking over 5 years, and what happens after year one. Linked in the main nav.
- The seller funnel (your HTML) is restyled into the site's current Fraunces and ink gold look, merged into one page, with your real webhook submission wired in exactly as you built it, posting straight to your GoHighLevel inbound trigger. The form fields match what you sent: name, phone, email, address, property type, timeline, notes.
- A simple "I'm a Seller" link now sits in the main nav and next to the primary buttons on Home, pointing at the seller page.
- Real testimonials, real property photos, and Tim's real portrait, all from the previous revision, are still in place.

## Design tokens

Background `#0B0C0F`, panel `#121318`, gold `#C9A66B`, bright gold `#E8CB8E`, warm text `#EDEAE2`. Headline font is Fraunces (serif, used italic for emphasis), body font is Manrope. Both load from Google Fonts in the head of every file.
