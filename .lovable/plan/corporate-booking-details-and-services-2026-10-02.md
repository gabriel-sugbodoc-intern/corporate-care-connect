# Corporate booking details and services

## Changes
- Replace the partner-company dropdown with company name, company email, employee ID, and optional authorization-letter fields.
- Add friendly validation and safe length/type limits for every corporate field; keep the uploaded file as an in-browser mock only.
- Keep all four standard services available to both patient types, and add a separate corporate-only service group with the requested four options.
- Label corporate-only choices clearly and show the appropriate payment or coverage note.
- Carry patient type, company name, company email, and selected service through review and the final booking card.
- Keep mock prices/details visibly marked as placeholders and preserve the existing blue/cyan presentation.

## Technical details
- Extend the shared booking model and service catalogue so saved browser bookings retain the new corporate details.
- Remove the old partner-company coverage filtering because corporate patients now see all standard services plus exclusive services.
- Update route metadata with the required social-card fields while touching the booking page.
- Verify both corporate and walk-in flows in the running preview, including validation and corporate-only visibility.
