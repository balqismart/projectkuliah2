LEARNSPACE — ENGLISH FOR EVERYDAY LIFE

Files:
- index.html: responsive learning website prototype.

H5P.com integration:
1. Create and publish an H5P activity in your H5P.com account.
2. Open the activity's Embed option and copy the embed URL (the URL used in the iframe src).
3. Open index.html in a text editor.
4. Find the H5P_EMBEDS object near the bottom of the file.
5. Paste the matching URL between the quotation marks, for example:
   greetings: "https://your-account.h5p.com/content/123456789/embed"
6. Save the file and open index.html in a browser.

Suggested H5P content:
- greetings: Course Presentation or Dialog Cards
- routines: Image Hotspots or Drag and Drop
- food: Course Presentation
- match: Drag and Drop
- listen: Interactive Video (or Audio-based content if available in your H5P account)
- quiz: Question Set

Important:
This is a working front-end website scaffold. Actual H5P interactions load from H5P.com only after you add the published embed URLs. The website itself does not create or host H5P content, and H5P.com account access/permissions may affect embedding.
