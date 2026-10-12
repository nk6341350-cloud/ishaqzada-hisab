ISHAQZADA HISAB

GitHub Pages source: main branch, repository root.
Keep index.html, app.js, bill.js, bill-arabic.woff, design.png and real-logo.jpg together.
The bundled Noto Arabic font is licensed under the SIL Open Font License; see FONT-LICENSE.txt.

The original navy/gold dashboard artwork is preserved. The former admin control
is replaced by a non-interactive personal-account badge. Settings and backups
remain available.

Each person has one chronological ledger. Add multiple product lines in one
submission; later dates append to the same person. Sales and payments made
increase the net receivable; purchases and payments received decrease it.
Positive balance = owed to owner. Negative balance = owner owes the person.
Home/report totals add the separate net receivable/payable for each person.
Existing storage key and IDs are preserved. Editing people, products and
transactions does not create another account. Failed storage writes keep the
previous database. JSON restore validates references and downloads the old data
before replacement.

PDF bills contain every transaction, notes, dates, quantities, prices and totals,
with a final payment summary and directional balance. PDF generation is local,
using native canvas text shaping and a self-contained JPEG/PDF encoder.
Prepare PDF, then tap Share and select WhatsApp/contact. Where file sharing is
unavailable, download the PDF and attach it manually. No message is auto-sent.

DATA: Records live in this browser's localStorage, not in the GitHub repository.
There is no cloud sync or account login. Use the same browser/device; export JSON
backups regularly and before clearing browser data or changing phones.
