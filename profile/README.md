<p align="center">
  <img src="https://raw.githubusercontent.com/getkaramu/.github/main/profile/banner.svg" alt="Karamu — The Hospitality Platform for Africa" width="100%"/>
</p>
<p align="center">
  <strong>Karamu</strong> (Swahili for "feast") is a restaurant management and reservations platform built for the African market.
  <br/>
  We help restaurants fill more tables, reduce no-shows, and keep their best guests coming back.
</p>
<p align="center">
  <a href="https://getkaramu.com">Website</a> •
  <a href="https://getkaramu.com/book/demo">Live Demo</a> •
  <a href="https://docs.getkaramu.com">Docs</a>
</p>
---
 
### What Karamu does
 
Karamu gives restaurants a complete operating system — from the moment a diner books a table to the moment they leave a tip. Built for how African hospitality actually works: M-Pesa deposits, WhatsApp confirmations, SMS reminders, and guest CRM that treats the phone number as the primary identity.
 
**For restaurants:** Online reservations, table management, guest CRM, deposit collection via M-Pesa, real-time dashboard, analytics — all from one platform.
 
**For diners:** Book a table in seconds, pay a deposit from your phone, get WhatsApp/SMS confirmations, and manage your booking without creating an account.
 
---
 
**Domain modules** — each maps 1:1 to a future microservice:
 
| Module | Responsibility |
|--------|---------------|
| `auth` | JWT auth, roles (owner/manager/staff), multi-tenancy |
| `restaurant` | Profile, tables, operating hours, booking rules |
| `reservation` | Availability engine, booking CRUD, waitlist, state machine |
| `payment` | M-Pesa STK Push, Flutterwave, deposits, refunds |
| `notification` | SMS (Africa's Talking), WhatsApp (360dialog), email (Resend) |
| `guest` | CRM — profiles, visit history, tags, notes |
| `analytics` | Covers, peak hours, no-show rate, revenue |
 

 
<p align="center">
  <sub>Built with ☕ for African hospitality.</sub>
</p>