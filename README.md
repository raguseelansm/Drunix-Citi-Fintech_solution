# Drunix-Citi-Fintech_solution
TrustShield UPI with VoicePay: An accessible payment gateway featuring new-contact risk profiling, secure cryptographic escrow, and locked-by-default AutoPay with voice-assisted dual-gate authentication.
# TrustShield UPI
**Smart Payment Warnings and Safe Cash Transit Framework** | Drinix × Citi Hackathon

## Problem Statement
UPI payments are instant and final. With no clearing window, nobody can step in once a user taps **Pay**, and today's apps leave users exposed in four ways:

- **Risky first-time transfers:** scammers create urgency ("hospital emergency", "pay this bill now"). Apps show the same generic pop-up every time, so users tap "Proceed" out of habit and cannot tell a verified business from a private account posing as one.
- **Hidden AutoPay:** confusing layouts silently enrol users in recurring debits and bury the frequency, maximum amount and receiver's real identity.
- **Unsafe deals between strangers:** buyers fear paying upfront, but holding the money lets a dishonest buyer take the item and falsely claim "not received".
- **Inaccessible to blind users:** they cannot read warnings, verify long UPI IDs or spot business flags.

## Our Solution: TrustShield UPI
A smart security and accessibility layer for payment apps. Real checkpoints for the exact situation, while payments stay fast.

### 1. Smart First-Time Alerts
- Detects a new phone number or UPI ID and switches to high-alert mode
- Banner shows **Verified Business** or **Unverified Private Account**
- 3-second Pay lock plus a scam-matched question ("Paying to claim a cash prize?")
- Scans payment notes ("Lottery Prize", "Customs Duty Fee") and warns the user
- Large unverified transfers: only a small fraction is sent now, the rest is held for 2 hours

### 2. Locked-by-Default AutoPay
- Every auto-debit starts **OFF**, with no pre-checked boxes
- One mandate card shows the real business name, maximum charge and frequency
- Two-step approval: fingerprint or app PIN, then UPI PIN on the official secure page
- 24-hour pre-charge alert and one-click **Cancel AutoPay**

### 3. Secure Transit Pool
- Buyer's money waits in a bank-managed pool, not with the unknown seller
- App generates a one-time QR code and 4-digit delivery PIN
- Buyer inspects the item, then shows the code and the seller scans it
- The scan releases funds instantly and leaves permanent proof, so no false "not received" claims
- If the deal falls through, the buyer cancels and the money returns

### 4. VoicePay (Accessibility)
- Pay by voice: say the recipient and the amount
- App reads back the recipient, amount and fraud-risk warnings, then asks to confirm
- Same-name contacts are told apart by reading distinguishing details
- Payment status and history are available by voice; AutoPay details and delivery PIN are voice-delivered too

## Impact
- Fewer scams, no hidden subscriptions, and safe trades between strangers
- Independent, secure payments for visually impaired users

