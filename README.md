# PayMyBill

A quiet, premium landing page where billionaires can adopt everyday bills.

## Run

Open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Bills

- Electricity: ₹10,000
- Child's education: ₹1,00,000
- Food: ₹15,000
- Platinum debt: ₹50,00,000

## Payment

The sponsor popup shows the live UPI QR code for **Masih Ahmed Shaikh** from `assets/Masih QR.png`.
The UPI ID decoded from the QR is **masih04@okicici** and can be copied from the popup.

```js
const QR_IMAGE_URL = 'assets/Masih%20QR.png';
const UPI_ID = 'masih04@okicici';
```

The QR may not pre-fill the bill amount, so the popup reminds sponsors to enter the selected amount in their UPI app.

## UX features

- Sticky sponsor CTA after the hero
- Copy UPI ID button
- Skeleton loading states for images and QR
- Reduced motion toggle, persisted, plus system preference
- Scroll progress indicator
- Back to top button
- Haptic feedback on supported touch devices
- Auto dark mode with persisted Auto, Light, Dark override
- Touch friendly tap targets

## Design

Premium minimal editorial UI: off-white and charcoal with a single bronze accent, serif display type, hairline borders, generous negative space, and slow refined motion.

## Images

Hero and showcase images are Unsplash placeholders. Replace the `src` values in `index.html` with final photography when ready.
