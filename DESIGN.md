# Design preview

This branch applies the supplied visual direction to the existing Jekyll site. It uses Uni Blue, warm accent colours, Plus Jakarta Sans headings and Atkinson Hyperlegible Next body text. The fonts load from Google Fonts, with local sans-serif fallbacks. The logo is a temporary raster extraction from the recommended direction in the branding PDF; replace it with the designer’s vector export before publication.

Run `make serve` and visit http://127.0.0.1:4000. Run `make build` to check the static build. No new application dependencies are needed.

The homepage introduces the audience routes and featured resources. The resource library contains the five themes in the Word brief. Existing lesson guides, slide downloads, comics, conversation materials and casefiles remain accessible. FAQs use native HTML disclosures and work without JavaScript.

## Before sharing publicly

- Confirm the final logo and hero photograph. The Figma prototype could not be retrieved; this design follows the supplied PDFs and Word text rather than reproducing its layout.
- Provide the new Stay Safe session files, Super Debunkers classroom slides, health campaign URL and second research paper. The preview labels unavailable materials rather than inventing links.
- Confirm the research status and participant quotations supplied in the brief. Uncertain impact statistics have been omitted.
- Choose the collaborator preview URL and hosting arrangement. The existing CNAME is unchanged; this branch has not been pushed or deployed. For another hostname, override the Jekyll url/baseurl and omit the production CNAME from that deployment.

Source materials and temporary files are excluded from the generated site.
