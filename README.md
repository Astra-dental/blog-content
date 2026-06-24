# Astra Dental Blog Content

Repository for Astra Dental Centre blog drafts, SEO titles, meta descriptions, internal-link plans, FAQ sections, keyword notes, and published content backups.

Website: https://astradentalcentre.com/

## Purpose

This repository organizes the content and SEO workflow for the Astra Dental Centre blog, from topic idea through to published, validated post.

## Repository structure

| Folder | What it holds |
| --- | --- |
| `blog-drafts/` | Full post drafts (with frontmatter) and the topic-ideas backlog |
| `seo-titles/` | Optimized title tag options per post |
| `meta-descriptions/` | Meta description options per post |
| `faqs/` | FAQ blocks to add to posts/pages (mirror in schema) |
| `internal-links/` | Internal linking plan and per-post link map |
| `keyword-notes/` | Target keyword list and intent notes |
| `image-alt-text/` | Alt text suggestions for post images |
| `content-refreshes/` | Refresh tracker and checklist for existing posts |
| `schema-notes/` | Which structured data to apply to posts (templates live in schema-markup repo) |
| `published-backups/` | Final published versions of posts |

## Content workflow

1. Pick a topic from `blog-drafts/blog-topic-ideas.md` (mapped to a keyword in `keyword-notes/`).
2. Draft the post in `blog-drafts/` with frontmatter (title, slug, target keyword, meta description).
3. Choose a title from `seo-titles/` and a meta description from `meta-descriptions/`.
4. Add internal links per `internal-links/blog-internal-linking-plan.md`.
5. Write alt text from `image-alt-text/` for each image.
6. Add FAQ + schema per `faqs/` and `schema-notes/` (use templates from the schema-markup repo).
7. Publish, validate, then save a copy in `published-backups/`.

## Editorial & SEO checklist

- [ ] One clear primary keyword, used naturally (no stuffing).
- [ ] Title tag ~50-60 chars; meta description ~150-160 chars.
- [ ] At least one internal link to a service page and one to a conversion page.
- [ ] All images have descriptive alt text.
- [ ] Facts, pricing, and stats verified and current.
- [ ] Schema added and passes the Google Rich Results Test.
- [ ] Final version backed up in `published-backups/`.

## Business reference

- Astra Dental Centre, Unit 120, 20061 Fraser Hwy, Langley, BC
- Phone: 604-533-8806 | Email: reception@astradentalcentre.com
- Dentist: Dr. B. Kumar Potluri (Invisalign & CEREC certified, 30+ years)

## Notes

- Do not commit credentials, API keys, or analytics IDs to this repository.
- Draft content here is not legal or medical advice; have a clinician review health claims before publishing.
