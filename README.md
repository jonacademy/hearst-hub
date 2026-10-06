# Hearst Content Creator Learning Hub

Built for Hearst apprentices learning with Bauer Academy. Creators, editors and managers use the same resource library, with three practical perspectives on applying learning.

## Publish on GitHub Pages
1. Extract this ZIP.
2. Upload `index.html`, `learning-guide.html`, `ksbs.html` and this README to the same root folder of your chosen GitHub repository.
3. In Settings → Pages, choose Deploy from a branch, your publishing branch, and / (root).
4. Open the resulting Pages address. To update an existing hub, replace index.html and add both new HTML pages alongside it.

Each HTML page contains its own CSS, JavaScript and embedded logos. The resource library remains in index.html. Keep all three HTML files together so the internal links work. No external fonts, build step or image folders are required. External learning links need an internet connection. The hub also opens directly as a local HTML file.

## What is included
- 180 resources across 16 learning areas, including the retained Canva section.
- Hearst brand and audience profiles, Studio, campaign cases, memberships, commerce, research, representation and the magazine shop.
- Practical prompts for creating, editing and managing content, plus a shared evidence prompt.
- Multi-word search with all/any matching, category filters, expand/collapse, reset and empty-state guidance.
- OneAdvanced at https://education.oneadvanced.com.
- Opaque full-width desktop sticky search. On small screens the search flows with the page to leave room for reading.
- Original compact Bauer header logo and supplied transparent white-and-mint footer logo. The Hearst mark was sourced from its public corporate site.

## Edit resources
Search index.html for `window.RESOURCE_CATEGORIES`. Each area has resources with title, url, type, source, optional date, optional summary, search tags and a ksbs array (for example ["K10", "S10"]). window.KSB_REFERENCE contains the supplied definitions. Use only codes in that reference and map to the actual content of a resource. Do not give a whole area the same codes. Keep the JSON valid and preserve case-sensitive video URLs. The total and area filters are calculated automatically. Featured reading cards are static HTML: update them too when changing the highlighted selection.

## Editorial notes
New Hearst links and featured sources were reviewed on 6 October 2026. Featured items show publication dates, or an explicit updated date for guidance. This is a manually curated hub, not a live news feed. Existing general resources are carried over from the approved Bauer version; some may require payment, an account or a subscription. Not every inherited third-party destination has been reverified in this update.

Individual resources carry suggested KSB learning tags mapped against the cohort reference supplied by Bauer Academy: https://jonacademy.github.io/apprenticeship/ccksb. The native KSB selector includes all 58 definitions (K1–K30, S1–S21 and B1–B7). KSB searches match exact codes, so K1 does not match K10 and S1 does not match S11. KSB filters combine with learning areas and text search. Tags indicate learning support, not proof of competence. Some requirements need workplace practice rather than a direct external resource. All KSBs remain available in the selector, including those without a direct resource match. Learners should use the standard and assessment plan for their enrolment and their agreed programme briefs. The shared role prompts do not replace the practical contribution required by the apprenticeship.

This is a Bauer Academy learning resource for the Hearst cohort, not the public Hearst corporate website. Its editorial styling draws on Hearst’s public black-and-white identity; no unpublished Hearst brand guide was supplied. Logos remain embedded so remote image changes cannot break the hub.

## Selected sources
- Hearst brands: https://www.hearst.co.uk/brands
- Hearst Studio: https://www.hearst.co.uk/solutions/branded-content
- Hearst case studies: https://www.hearst.co.uk/case-studies
- Hearst insights: https://www.hearst.co.uk/insights-initiatives
- Hearst media centre: https://www.hearst.co.uk/media-centre
- Reuters Institute, Digital News Report 2026: https://reutersinstitute.politics.ox.ac.uk/digital-news-report/2026/dnr-executive-summary
- Google, generative AI content guidance: https://developers.google.com/search/docs/fundamentals/using-gen-ai-content
- Google, AI features and your website: https://developers.google.com/search/docs/appearance/ai-features
- IPSO Editors’ Code: https://www.ipso.co.uk/editors-code-of-practice/
- ASA affiliate marketing: https://www.asa.org.uk/advice-online/affiliate-marketing.html
- W3C accessibility tutorials: https://www.w3.org/WAI/tutorials/

## Validation
Browser checks passed for logo loading, all/any multi-word search, empty results, reset, category filters, Canva expansion/collapse and role prompt search links. No JavaScript page errors were observed. Layouts at widths from 320px to 1440px had no horizontal overflow. The desktop search backing was checked as opaque and full-width, positioned directly below the header.

## KSB mapping coverage
172 resource entries have suggested KSB learning links, covering 54 of the 58 supplied codes. No direct resource is currently tagged for K1, S4, B4, B7. These remain in the selector and reference page. Behaviours such as taking ownership and reflecting on your own results need demonstrated workplace activity, not a reading link alone.

KSB update checks: all 58 dropdown options, exact K/S code searches, combined KSB/area/text filters, all/any matching, reset and role prompt links passed in the browser. Canva search, logos, opaque desktop search backing and layouts at 320–1440px also passed with no JavaScript page errors.


## New programme pages
- learning-guide.html: an expanded OTJ / DDT guide with the four eligibility checks, 10 searchable subjects, 30 role examples, 10 grey-area explanations, a logging template and three worked entries.
- ksbs.html: all 58 supplied KSB definitions, their supplied assessment-method allocation and all 13 assessment themes with the full pass/distinction wording. Search and group/method filters are available. The original source remains linked.
- The hub’s KSB reference links now use the local page. New programme navigation works on desktop and mobile. Supporting-resource links use index.html?ksb=K10#resources; topic links can use index.html?q=budget#resources.

The OTJ examples are suggestions for agreed training, not automatic eligibility decisions. Guidance was checked against the government’s England off-the-job training guidance updated 4 August 2026. Actual hours targets and applicable policy are determined by the learner’s start date, initial assessment and agreed training plan; no blanket weekly hours target is invented. Routine productive duties, general meetings, portfolio compilation and personal-time study are distinguished from eligible planned training. Advanced learning in familiar tools is included when it addresses a relevant gap.

The KSB definitions and descriptors reproduce the cohort reference supplied at https://jonacademy.github.io/apprenticeship/ccksb, retrieved 6 October 2026. The original OTJ guide is https://jonacademy.github.io/apprenticeship/ddt. Official guidance: https://www.gov.uk/government/publications/apprenticeships-off-the-job-training/apprenticeship-off-the-job-training-guidance--2 (Crown copyright 2026, Open Government Licence v3.0). Workplace and logging examples are newly written illustrations.

Programme-page checks: all three pages and internal links, embedded logos, layouts from 320px to 1440px, all 58 KSB learning-example searches, guide search/reset, exact source KSB wording and assessment allocation, group/method filters, deep links and mobile navigation passed without JavaScript page errors.
