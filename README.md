# Brandon Sayre Consulting Website

A Next.js website for Brandon Sayre Consulting, a shipping company. The website allows customers to inquire about better shipping deals through a contact form.

## Features

- Responsive design with Tailwind CSS
- Contact form for shipping inquiries
- API endpoint to handle form submissions
- TypeScript support

## Getting Started

First, install dependencies:

```bash
npm install
```

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `app/page.tsx` - Main homepage with company info and contact form
- `app/api/contact/route.ts` - API route for handling form submissions
- `components/ContactForm.tsx` - Client component for the contact form

## Technologies Used

- Next.js 16
- React
- TypeScript
- Tailwind CSS
- ESLint

## Deployment

This app can be deployed on Vercel, Netlify, or any platform supporting Next.js.

### Email setup

A `.env.local` file has been created in the project root with the SMTP credentials needed for email delivery.

If you want to update these values later, edit `.env.local` directly.

Then restart the dev server.

For Gmail, use an App Password if your account has 2-step verification enabled.

For Vercel deployment:

```bash
npm run build
```

Then deploy the `.next` folder and other necessary files.
