# House of Kelp

A conversion-focused B2B landing page and lead-capture flow for a fictional sustainable food packaging brand.

**Live site:** https://house-of-kelp.vercel.app

## About

House of Kelp replaces single-use plastic packaging with edible, compostable material made from seaweed. This project is a landing page and dedicated sample-request page designed around a single goal: get visitors to request a sample kit.

## Features

- Responsive landing page with hero, social proof, problem/solution sections, and process walkthrough
- Dedicated `/request-sample` page with a full B2B lead-capture form
- Clean URL routing via `vercel.json`
- Security headers (X-Frame-Options, X-Content-Type-Options, Referrer-Policy)
- Mobile-optimized layout and typography

## Stack

- HTML, CSS, JavaScript (no framework/build step)
- Deployed via GitHub + Vercel with automatic CI/CD on push to `main`

## Structure

```
index.html            → main landing page
request-sample.html   → sample request form page
assets/logo.png        → brand logo
vercel.json            → routing + security headers config
```
