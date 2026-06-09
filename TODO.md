# TODO

## Step 0 — Confirm scope
- [x] Target: update only `services/motherboard-repair.html`.
- [x] Method: merge missing sections/modals/widgets (no wholesale replace).

## Step 1 — Add missing UI blocks from provided Tailwind template
- [ ] Insert booking modal + WhatsApp chat widget (non-destructive merge).
- [ ] Add FAQ accordion markup + JS hook (or map into existing FAQ if present).

## Step 2 — Wire modal open/submit functions
- [ ] Ensure `openBookingModal(sourceContext)` and `handleModalSubmit(event)` work without breaking current WhatsApp modal.
- [ ] Add WhatsApp widget `toggleWaChatBox()` and `sendQuickWaMessage()`.

## Step 3 — Verify
- [ ] Load `services/motherboard-repair.html` in browser; check JS console for errors.
- [ ] Ensure existing sidebar + thankYouModal continue working.

