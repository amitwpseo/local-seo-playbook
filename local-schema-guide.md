# Local Business Schema Markup Guide

Schema markup helps search engines understand your business details and can enhance your search listings with rich results. This guide focuses on LocalBusiness schema using JSON-LD.

## What is LocalBusiness Schema?
It’s a structured data format that provides information about your business: name, address, phone, hours, reviews, and more.

## Basic LocalBusiness Schema Example
Add this JSON-LD to your website’s homepage or contact page (inside `<head>` or `<body>`).

```json
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "name": "Your Business Name",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "123 Main St",
    "addressLocality": "Austin",
    "addressRegion": "TX",
    "postalCode": "78701",
    "addressCountry": "US"
  },
  "telephone": "+15125551234",
  "email": "info@yourbusiness.com",
  "openingHours": "Mo-Fr 09:00-17:00",
  "url": "https://www.yourbusiness.com",
  "logo": "https://www.yourbusiness.com/logo.png",
  "priceRange": "$$",
  "sameAs": [
    "https://www.facebook.com/yourpage",
    "https://www.instagram.com/yourprofile"
  ]
}
