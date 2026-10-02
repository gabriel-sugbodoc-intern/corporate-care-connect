# Clinic Buddy

clone this github repo and add ont hsi feature 
https://github.com/Sabang123/anyoneclinic.git

Update the AnyoneClinic booking website to add a patient type option to the booking flow.

On the booking page (/book), add a new first step: "Choose patient type" with two selectable cards:

1. Corporate / Partner Company Employee

   - For individuals covered by a company partnered with AnyoneClinic.

   - Show extra fields: company name (dropdown of mock partner companies), employee ID, and an optional authorization letter upload (mock).

   - Show only the services included in the partner company's package, with a note: "Covered under your company's agreement."

2. Walk-in Individual

   - For individuals with no affiliation to the clinic or any company.

   - No extra affiliation fields.

   - Show all available services with regular prices and a note: "Pay at the clinic."

Then:

- The service selection step should change based on the chosen patient type (different available services and pricing).

- Add a patient type badge (Corporate or Walk-in) to the review step and the final booking card, plus company name and employee ID if corporate, and a payment note ("Covered by company" or "Pay at clinic").

- Add a short "Who can book?" section on the home page explaining both patient types, with a "Book as Corporate" and "Book as Walk-in" button that opens /book with that type pre-selected.

- Add friendly validation for the corporate fields, and keep everything frontend-only with mock data and clearly marked placeholders for partner companies and prices.

- Keep the existing blue/cyan color scheme and design style.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://partner-care-select.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/2bb23ae1-2be6-458b-a891-806b7e454269).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
