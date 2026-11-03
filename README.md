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

Payments are not enabled yet. The sponsor modal shows a safe placeholder.
When the real QR image is ready, drop it into `assets/` and set `QR_IMAGE_URL`
near the top of the script in `index.html`, for example:

```js
const QR_IMAGE_URL = 'assets/upi-qr.png';
```

## Style

Clear Liquid Glass UI: transparent glass, minimal blur, specular edges, light refraction, light and dark mode support, and a generated luxury background at `assets/bg-luxury.jpg`.
