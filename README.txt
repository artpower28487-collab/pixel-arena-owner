PIXEL ARENA OWNER PORTAL

Deploy the complete folder to HTTPS static hosting and keep supabase-config.js beside index.html. The login screen asks for the owner's PIN only; Supabase Auth uses the configured owner email behind the scenes.

Before first login, run the public website's supabase-setup.sql, disable public sign-ups, and create/confirm the owner account. Set its password to PixelArena-<PIN>-Portal! for a private PIN of 8–12 digits. Full setup steps are in ../pixel-arena-public-website/CONNECT-BOTH-SITES.txt. Do not use the old demo PIN 6527.

Bookings and offers sync through Supabase. Slot availability and rates remain local to this browser. Cafe orders still arrive by WhatsApp.
