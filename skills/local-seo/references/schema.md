# Local schema

Structured data that tells search engines the facts about the business. Small job, real effect on how the listing looks.

## Use the specific type

`LocalBusiness` works. A more specific type works better where one exists: `Dentist`, `Attorney`, `Plumber`, `AutoRepair`, `Restaurant`, `HairSalon`, `MedicalClinic`, `AccountingService`, `RealEstateAgent`.

## The markup

Fill in the real details. Never hand over a template with placeholders still in it.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "AutoWash",
  "name": "Star Wash",
  "image": "https://example.com/photo.jpg",
  "url": "https://example.com",
  "telephone": "+1-780-555-1234",
  "priceRange": "$$",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "1234 Jasper Avenue",
    "addressLocality": "Edmonton",
    "addressRegion": "AB",
    "postalCode": "T5J 0A1",
    "addressCountry": "CA"
  },
  "geo": { "@type": "GeoCoordinates", "latitude": 53.5461, "longitude": -113.4938 },
  "openingHoursSpecification": [{
    "@type": "OpeningHoursSpecification",
    "dayOfWeek": ["Monday","Tuesday","Wednesday","Thursday","Friday"],
    "opens": "08:00", "closes": "18:00"
  }],
  "sameAs": [
    "https://www.facebook.com/...",
    "https://www.instagram.com/...",
    "https://g.page/..."
  ]
}
</script>
```

The address here must match the Google Business Profile and the website footer character for character.

## Service-area businesses

Use `areaServed` instead of leaning on the street address:

```json
"areaServed": [
  { "@type": "City", "name": "Edmonton" },
  { "@type": "City", "name": "St. Albert" },
  { "@type": "City", "name": "Sherwood Park" }
]
```

## Also worth adding

- `FAQPage` on service pages that have a questions section
- `Service` on each service page
- `BreadcrumbList` if the site has breadcrumbs

Do not mark up reviews as `AggregateRating` using Google reviews. Self-serving review markup for your own business is against Google's guidelines and can trigger a manual action.

## Verifying it

`WebFetch` and `curl` strip `<script>` tags, and Yoast, RankMath and AIOSEO often inject schema with JavaScript. So:

- Check it in a rendered browser: `document.querySelectorAll('script[type="application/ld+json"]')`
- Or Google's Rich Results Test: https://search.google.com/test/rich-results
- Or say you could not verify it

Never report schema missing based on a plain fetch. It is the most common false finding in automated audits.
