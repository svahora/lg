# FunAds

A clickable prototype of everything in the self-serve ads v2 build: the admin pages the ads team runs, auto-added fundraisers from approved accounts, the compliance review queue, the package inventory, the live season setting, and the creator checkout with card or bank payment.

Live: https://svahora.github.io/lg/funads/

What to try:
- **Creator's fundraiser:** switch between a fundraiser on the seasonal list, one auto-added from an approved account, one on the test list, and one on no list (no offer shown).
- **Buy an ad:** See packages, pick one (Gold is sold out), add details, pay by card or bank. The masjid fundraiser sees 3 tiers; other categories see 4. Bronze has an optional image upload.
- **Three nudges:** a fundraiser on a list gets a page alert, an in-app notification (Notifications) and an email. Each opens packages with its own entry point.
- **Admin to creator loop:** in Admin, Package inventory, hide a package or change slots, then go back to the creator checkout. In Live season, switch the season and the checkout changes.
- **Auto-add:** in Approved accounts, simulate an account creating a fundraiser, then approve or reject it in Compliance review.
- **Requested, not committed:** shows the dashboard Promote button, prefill and the ROI display, marked as requests.
- **Engineering notes:** build notes and open questions on every screen.
- **Data events:** logs the event each action would send, with the shared IDs.

All names, amounts and prices are sample data.
