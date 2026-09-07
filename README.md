# Orpin Cold Email Desk

Simple dashboard for Farhan Rahman / Orpin daily cold outreach.

## What it shows
- Month totals: sent, replies, positive, follow-ups, deals
- Recent sends with business, city, category, note
- Breakdown by category (restaurant, e-commerce, service, salon, professional)

## How to update after daily emails
Edit the `DATA` object inside `index.html` (or later split to `data.json`).

After each automation run, update:
- `month.sent`, `replies`, `positive`, `followUps`
- Add new rows to `recent`
- Adjust `byCategory` counts

## Deploy
Static site — works on Vercel with zero config.
