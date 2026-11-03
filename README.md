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

## QR code

The sponsor popup shows the live UPI QR code for **Masih Ahmed Shaikh** from `assets/Masih QR.png`.
The path is configured near the top of the script in `index.html`:

```js
const QR_IMAGE_URL = 'assets/Masih%20QR.png';
```

The QR may not pre-fill the bill amount, so the popup reminds sponsors to enter the selected amount in their UPI app.

## Design

Premium minimal editorial UI: off-white and charcoal with a single bronze accent, serif display type, hairline borders, generous negative space, and slow refined motion. Supports light and dark color schemes and reduced motion.

## Images

Hero and showcase images are Unsplash placeholders. Replace the `src` values in `index.html` with final photography when ready.
