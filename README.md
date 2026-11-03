# PayMyBill

A playful, luxury landing page where billionaires can adopt everyday bills.

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

## Style

Clear Liquid Glass UI: very transparent glass, minimal blur, specular edges, light refraction, light and dark mode support, and a generated luxury background at `assets/bg-luxury.jpg`.

## Responsive behavior

- Desktop: multi-column bill grid and side-by-side hero.
- Tablet: stacked hero and adaptive bill grid.
- Mobile: fully stacked cards, full-width buttons, compact nav, and a bottom-sheet sponsor modal.
- Horizontal overflow is clipped and scrollbars are kept thin and minimal.
