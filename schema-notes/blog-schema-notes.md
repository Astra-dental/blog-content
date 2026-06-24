# Blog Schema Notes

How to apply structured data to Astra Dental Centre blog posts. The actual JSON-LD templates live in the separate `schema-markup` repository (blogposting/ and faq/ folders). This file documents which schema to use and when.

## Which schema for a blog post?

- **BlogPosting** on every blog article (headline, author, dates, publisher, image).
- **FAQPage** only if the post contains a visible FAQ section, and the questions/answers must match the visible text exactly.
- **BreadcrumbList** to reflect the path (Home > Blog > Post Title).

## Implementation checklist

- [ ] Use the BlogPosting template from schema-markup/blogposting/.
- [ ] Set headline, datePublished, dateModified, image, and slug for the specific post.
- [ ] Author = Dr. B. Kumar Potluri; publisher = Astra Dental Centre Organization.
- [ ] If a FAQ is present, add FAQPage JSON-LD that mirrors the visible Q&As.
- [ ] Validate with the Google Rich Results Test before publishing.

## Common mistakes to avoid

- Marking up FAQ content that is not visible on the page.
- Forgetting to update dateModified after a content refresh.
- Using a placeholder image URL that does not resolve.
- Mismatched headline in schema vs. the visible H1.

## Cross-reference

- JSON-LD templates: `schema-markup` repo
- FAQ wording source: `faqs/` folder in this repo
- Validation guide: `schema-markup/testing-notes/validation-checklist.md`
