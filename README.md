# Save The People Website

A modern, responsive React-based non-profit web application with an interactive donation flow, Razorpay gateway integration, and a password-protected Admin Control Center.

## Features Included

- **Brand Integration:** Automatically looks for your logo in `images/logo.png` (or `logo.jpg`/`logo.svg`), with a fallback badge.
- **Hero & Mission Section:** Quick donation buttons (₹500, ₹1000, ₹2500, ₹5000, or Custom).
- **Urgent Causes Showcase:** Visual cards with live progress bars, donor counts, and direct action buttons.
- **Donation Flow with Razorpay:**
  - Collects Name, Email, Phone, and PAN Number (for 80G Indian Tax Exemption receipts).
  - Integrates with Razorpay Standard Checkout (UPI, Cards, NetBanking, Wallets).
- **Admin Control Center:**
  ## Admin Login Credentials

- **Username:** `admin` (or `savethepeople`)
- **Password:** `admin123` (or `savethepeople123`)

Direct URL: `http://localhost:3000/admin` (or `index.html#admin`)
  - Total funds raised, total donor count, active campaign counters.
  - Live transactions table with donor details, payment IDs, and 80G tax data.
  - Ability to create and publish new fundraising campaigns.
  - One-click **Export Donors to CSV** for your accounting and 80G reporting.

## How to Run Locally

You can open `index.html` directly in any web browser:
- Double click [index.html](file:///c:/Users/91767/Desktop/savethepeople/index.html) or right-click and choose **Open with > Chrome / Edge / Firefox**.
- Or run a lightweight local server if you prefer:
  ```bash
  npx serve .
  ```

## Setting Up Your Real Razorpay Key

When you are ready to connect your live or test Razorpay account:
1. Open `index.html`.
2. Search for `rzp_test_YourKeyHere`.
3. Replace it with your actual **Key ID** from your Razorpay Dashboard (`Settings > API Keys`).

