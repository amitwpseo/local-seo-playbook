{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "LocalBusiness",
      "@id": "https://www.example.com/austin#business",
      "name": "Example Business Austin",
      "address": { ... },
      "telephone": "+15125551234",
      "parentOrganization": {
        "@type": "Organization",
        "name": "Example Business HQ",
        "url": "https://www.example.com"
      }
    },
    {
      "@type": "LocalBusiness",
      "@id": "https://www.example.com/dallas#business",
      "name": "Example Business Dallas",
      "address": { ... },
      "telephone": "+12145551234",
      "parentOrganization": { "@id": "https://www.example.com#organization" }
    }
  ]
}
