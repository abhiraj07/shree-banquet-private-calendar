# Shree Banquet Hall — Private Admin Calendar Checklist

## Required experience
- [ ] Admin login with username admin980123 and password.
- [ ] No Google/Gmail sign-in.
- [ ] Calendar month navigation and date selection.
- [ ] Display Available / Pending / Booked status.
- [ ] View and edit full booking details after admin login only.
- [ ] Fields: client name, phone, event type, private notes.
- [ ] Save/update booking.
- [ ] Clear booking.
- [ ] Upcoming bookings for the selected month.
- [ ] Realtime sync with Android app and public website.

## Security
- [ ] Supabase Auth session required for all admin operations.
- [ ] RLS is the authority; hiding UI is not security.
- [ ] Public website must not receive client PII.
- [ ] Do not expose service-role keys in browser code.

## Rollout
- [ ] Work only on feature branch.
- [ ] No merge/deploy without explicit approval.
- [ ] Fresh start is acceptable; existing booking history need not be migrated.
