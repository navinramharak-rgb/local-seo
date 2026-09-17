---
name: local-seo
description: Get a local business found in its own city. Use when the user runs a business customers search for locally and says "I'm not showing up on Google", "not in the map", "my competitor ranks above me", "Google Business Profile", "GBP", "google maps listing", "near me searches", "local SEO", "get found in [city]", "I need more local customers", or asks why a nearby competitor outranks them. Also use after audit-website flags a local business. Covers Google Business Profile, service and area pages, reviews, citations and local schema.
---

# Local SEO

For a plumber, a clinic, a law firm, a car wash or a restaurant, this is the order of what matters:

1. **The Google Business Profile.** Free. Most people never finish setting it up. It is what fills the map results, and it wins searches the website never will.
2. **Reviews.** The single strongest lever on local ranking that is also a sales asset.
3. **The website's local pages.** One page per service, one per area worth having.
4. **Citations.** Being listed consistently in the places that matter, not all 300 of them.
5. **Local schema.** Small job, real effect on how the listing appears.

Almost everyone does this list backwards, starting with the website and never touching the profile.

The person running this is a business owner. No jargon without a plain-English translation attached.

**The rule that matters most: every number in the output came from something you actually looked at.** Review counts, photo counts, ranking positions, competitor figures. You searched for it and read it, or the report says "couldn't check". An invented number is worse than a missing one, because they will act on it. And never report a ranking position without saying where the search was run from, because map results change with the searcher's location.

---

## Step 1. Five questions

Ask all five at once, keep them short.

1. What's the business name, exactly as it appears on the sign and on Google?
2. What do you actually do, and which of those services makes you the most money?
3. Do customers come to you, or do you go to them? What's the furthest you'll travel?
4. Which city and neighbourhoods matter most?
5. Who's the competitor that always seems to be above you?

Question 3 decides everything about how the profile gets set up, and it is the one most people get wrong. Storefront and service-area businesses follow different rules and mixing them up suppresses the listing.

Get the website URL too, if there is one. A business with no website can still win the map. Say that out loud if it applies.

---

## Step 2. Look at the profile first, not the website

Read `references/gbp.md`. It has the full audit, the field-by-field detail and the category work, which is the highest leverage decision in the whole skill.

You cannot see inside someone's Google Business Profile dashboard. You **can** see the public listing. So:

- Search the business name plus the city and read the listing that comes back.
- Search the main service plus the city and see who fills the map results, and whether they are in it.
- Look at the competitor they named and note what that listing does that theirs does not.

Report what you observed. If you could not find a listing at all, that is the headline finding and the first job.

Cover: name, category (primary and secondary), full service list, hours including holidays, service area, description, photos and how recent, products or services with prices, Q&A, posts, messaging, attributes, and the review picture.

The most common finding, by a distance: **the primary category is wrong or generic.** Category is the strongest single ranking factor in the map. A "car wash" listed as "car detailing service" loses every car wash search in the city and nobody ever notices.

---

## Step 3. Tear down the three businesses beating them

Read `references/competitors.md`. This is the step that makes the difference between a list of best practices and something the owner can act on this afternoon.

Search the money keyword the way a customer types it, take the three businesses in the map pack, and pull the same fields for all of them plus the client. Category, review count and recency, photos, hours, services, products, posts, Q&A, booking link, attributes, description.

Then turn it into three or four **gaps**, ranked. Not a table dump. "All three above you are in the Car Wash category and you are in Car Detailing Service" is a gap. "They are bigger than you" is not.

The gap list is the spine of the whole deliverable. Do this before writing a single recommendation.

---

## Step 4. Reviews

Read `references/reviews.md` for the request scripts, the response templates and the rules about what you must never do.

Assess: how many, how recent, average rating, whether the owner replies, and what the negative ones actually say.

Recency matters more than people think. Forty reviews with the newest from two years ago reads worse than twelve from the last three months.

Then build the machine:
- The exact moment in the job to ask, which is the moment the customer is happiest, not the moment you send the invoice
- The short-link request, ready to paste into a text
- A reply template for good ones and for bad ones
- A simple cadence that survives a busy week

**Never:** offer anything in exchange for a review, write a review, write a fake one, filter customers so only happy ones get asked, or set up a page that screens people before they reach Google. These break Google's policies and can cost the whole listing. If the user asks for any of it, say plainly that it risks the listing and give them the version that works instead.

---

## Step 5. The pages on the website

Read `references/pages.md` for the page structures and the title formulas.

The rule: **one page per thing you want to rank for.** One page listing six services ranks for none of them.

- A page per service that actually makes money
- A page per area worth having, and only if there is something real to say about each. Six near-identical suburb pages is a spam pattern and Google treats it as one.
- Title tags carrying the service and the city
- The city, in text, in the H1 and the first paragraph, written like a human wrote it
- Address in text, not baked into an image, matching the profile exactly
- A map, directions, parking, what the building looks like
- Photos of real jobs in recognisable places

Say the address rule out loud: whatever is on the profile, the website and every directory has to match, character for character. "Suite 4" in one place and "#4" in another is a genuine problem. It is called NAP consistency, which is name, address, phone.

---

## Step 6. Citations

Read `references/citations.md` for the list that is actually worth the afternoon.

Do not chase 300 directories. There are about a dozen that matter, plus whatever is specific to the trade and the country. For Canada that includes Yellow Pages Canada, Canada411 and 411.ca, which a lot of American advice skips entirely.

Find the wrong ones before adding new ones. An old address on a directory is actively working against them. Search the phone number and the old address to find the stragglers.

---

## Step 7. Local schema

Read `references/schema.md` for copy-paste-ready markup.

`LocalBusiness` schema, or the more specific type where one exists, with name, address, phone, hours, geo, URL and `sameAs` links. Ready to paste, filled in with their real details, not a template with placeholders left in.

Note the same limitation the audit skill has: schema injected by JavaScript is invisible to a plain fetch. Verify in a rendered browser or with Google's Rich Results Test. Never report it missing based on a plain fetch.

---

## Step 8. Take the baseline before anything changes

Read `references/measure.md`.

Five measurements, written down with today's date: review count and average, date of the newest review, photo count and date of the newest photo, and where they appear for three to five real searches, **with where those searches were run from**. Screenshot the profile performance tab if they can get to it.

This takes ten minutes and it is the only reason anyone will know in a month whether any of this worked. Skip it and the whole engagement becomes an argument about feelings.

Same file also covers the proximity point, which they need to hear early: there is no single ranking, it changes with where the searcher is standing. Say it plainly, in the document.

---

## Step 9. Score it

Six areas, weighted by what actually moves the map. Show the breakdown so the number is not a black box.

| Area | Weight |
|---|---|
| Profile completeness | 30 |
| Category fit | 20 |
| Reviews | 20 |
| Local pages | 15 |
| NAP and citations | 10 |
| Schema and measurement | 5 |

Score it honestly. Most businesses who ask for this land in the 30s and 40s. That is the point. It is a before photo, and a generous score makes the after photo meaningless.

---

## Step 10. The deliverable

Read `references/report-format.md`, then build the page from `references/report-template.html`. Copy the template, fill every `{{TOKEN}}`, delete what you have nothing for. Search the finished file for `{{` before handing it over.

One self-contained HTML file, no external anything, prints properly. Named `[business-name]-local-search-plan-[YYYY-MM-DD].html`.

Order, which is not negotiable:

1. The score, and **the one thing to do first**, on its own above everything. Nearly always the primary category.
2. Where you are today: the five baseline measurements, dated.
3. The competitors side by side, then the three or four gaps.
4. The six scored areas.
5. What you couldn't check.
6. The ninety day plan: today (free, about an hour, the profile), this week (the review machine and the first ten asks), this month (service pages, area pages, citations, schema).
7. How they will know it worked: the repeat measurement date, and the tagged profile link.

Be honest about timing inside the document, not just in conversation. Profile changes can move within days. Website changes take weeks to months. Someone promising rankings by Friday is lying to them.

---

## Chains with

- **`audit-website`** — run it first when there is a website. This skill assumes the site is not fundamentally broken.
- **`build-premium-site`** — when the audit says rebuild, build it with the service and area page structure from `references/pages.md` already in place, rather than retrofitting.

For technical SEO beyond local (hreflang, crawl budget, international, programmatic pages), use Corey Haines' `seo-audit` skill. It goes much deeper on that axis. This skill deliberately covers what that one does not: the local half.

---

## Things to get right

**Profile before website, every time.** It is free, it is faster, and for most local businesses it brings more calls. Leading with website work is how agencies bill for six months before anything moves.

**Never invent numbers.** No made-up rankings, search volumes, review counts or competitor stats. Look it up or say you could not check it.

**No review gating, ever.** Explained above. Be firm about it.

**Say what is slow.** Local SEO is not instant. Set the expectation honestly, at the start, so they do not give up in week three when it is actually working.

**Compare, do not lecture.** The gap list against the three businesses actually in the map is worth more than every general best practice in these files. Someone can argue with advice. Nobody argues with "they are in this category and you are not."

**Measure before you touch anything.** Ten minutes of baseline is what turns this from an opinion into a result you can show them in thirty days.

**No ranking without a location.** Map results change with where the searcher is standing. Any position you report says where it was searched from, or it is not a fact.
