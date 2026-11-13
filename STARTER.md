# JW Scaffolding Website Starter

## Base design
The uploaded FORM / ACCESS Scroll Assembly v2 is stored unchanged as index.html. This is a fictional prospect-preview design, not a trading scaffolding business. The enquiry form only previews information locally and does not deliver messages.

## Prospect workflow
Keep main as the generic base. Create each prospect branch from main, using preview/company-name. Tailor only that branch. Do not merge a prospect's branding into main. Improvements to main do not automatically propagate to existing branches; review and merge shared changes deliberately.

## Customisation
Edit index.html: the :root CSS variables control the main background, panel, text and accent colours. Replace FORM / ACCESS branding, page title, description, approved services and coverage copy as appropriate. Replace illustration project panels only with permissioned assets and accurate project descriptions. Never invent accreditations, testimonials or completed projects. Add only verified telephone, email and WhatsApp details.

## Preview deployment
This is a plain static site with index.html at repository root and no build dependencies. Connect this repository to Cloudflare Pages and select main as the production branch for the base demo. Enable the required preview branches in Cloudflare branch deployment controls. A commit triggers deployment only if the Git integration and automatic builds are already configured. This commit does not provision Cloudflare or a domain. Check the current dashboard for the root/output directory settings for a plain static project.

## Preview protection
HTML includes noindex,nofollow and _headers adds X-Robots-Tag for static Pages responses. Noindex is not access control: add authentication for confidential previews. Review indexing restrictions only when an approved real business site is ready for production.

## Before client launch
Configure secure form delivery, validation, spam protection and appropriate privacy information. Test actual delivery and error handling. Verify contact numbers, mobile layout, keyboard controls, motion toggle, reduced-motion settings and scroll animation. Confirm real metadata, canonical, domain and indexing settings. Do not put private API keys in client-side code.

## Repository template setting
If desired, manually enable Settings > General > Template repository in GitHub. Branch-based previews do not require this flag. No template flag or Cloudflare settings were changed by this upload.
