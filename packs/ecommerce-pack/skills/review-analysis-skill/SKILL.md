---
name: review-analysis-skill
description: Analyze provided ecommerce review excerpts to extract positive themes, complaints, buyer motivations, usage scenarios, product improvements, listing improvements, ad angles, FAQs, and claim risks.
---

# Skill: review-analysis-skill

## Purpose

Turn provided customer review excerpts into themes, complaints, motivations, improvement ideas, listing changes, ad angles, and FAQs.

## Best for

Amazon, Etsy, Shopify, and marketplace sellers analyzing their own or competitor review excerpts.

## Not for

Fabricating reviews, scraping private data, manipulating reviews, or making claims beyond the supplied reviews.

## Input

- Product category
- Platform
- Positive reviews
- Negative reviews
- Neutral reviews
- Competitor reviews
- Product facts

## Output

1. Top positive themes
2. Top negative themes
3. Common buyer motivations
4. Common usage scenarios
5. Repeated complaints
6. Product improvement suggestions
7. Listing optimization suggestions
8. Ad copy angles
9. FAQ opportunities
10. Claims to avoid
11. Review summary table

## Process

1. Group only the provided review excerpts.
2. Separate high-frequency and low-frequency signals.
3. Map review themes to product, listing, ad, image, and FAQ actions.
4. Flag unsupported claims.
5. Summarize evidence in a table.

## Quality Bar

- Analyzes only user-provided reviews.
- Does not fabricate reviews.
- Does not encourage review manipulation.
- Converts review signals into ecommerce actions.
- Clearly labels high-frequency and low-frequency issues.

## Example Input

Product category: pet hair remover
Positive reviews: works well on couch fabric; easy to clean
Negative reviews: handle feels small; not ideal for delicate knit fabric
Product facts: reusable manual tool

## Example Output

Repeated complaints: handle comfort appears in negative reviews; delicate fabric limitations should be clarified in listing and FAQ.

## Safety / Compliance Notes

Do not invent sentiment, ratings, quotes, certifications, or product claims. Do not ask users to create fake reviews or suppress negative feedback.
