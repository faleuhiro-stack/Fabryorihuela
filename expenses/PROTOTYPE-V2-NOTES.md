# Fabry Expenses V2 — Prototype

This is an isolated design prototype. It is intentionally stored on branch `prototype/fabry-expenses-v2`.

## Preview file
- `expenses/prototype-v2.html`

## Scope represented
- Combined dashboard: financial summary, upcoming bookings, tasks and alerts
- Booking list and planned one-screen booking detail
- Manual Booking-to-quote action concept
- Expenses assigned to one Booking, general expenses, or split across multiple Bookings
- Mileage form with Booking-linked or independent trips, Maps workflow placeholder, and per-trip one-way/round-trip choice
- Financial calendar showing expected, collected and outstanding amounts
- Profitability by dollar gain and margin percentage, ranking and formation comparison
- In-app reminders and proposed phone push notification rules

## Important limitations
- Uses fictional sample values only.
- Does not connect to Supabase or production data.
- Does not write to or replace `expenses/index.html`.
- Forms are visual placeholders and do not persist data.
- Google Maps distance calculation is not connected; no API key is included.
- Push notifications are not implemented.
- No GPS/background tracking is implemented.

## Safety
Do not merge this branch or copy this file over the production app without Fabry's explicit approval and a separate implementation/testing plan.
