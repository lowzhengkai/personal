# personal — Visual refresh (draft)

This branch contains a visual redesign focused on a minimalist, professional portfolio:

What changed
- New landing page layout (hero with your banner, projects, writing, about).
- Newsletter form (collects name + email). Form action is a placeholder — replace with your provider endpoint.
- Poppins font, refined spacing, responsive styles.
- Banner added to assets/ (banner.png + optimized webp + social crop).

How to configure newsletter
1. Replace the form `action` in `index.html`:
   - Formspree example: `https://formspree.io/f/your-id` (POST)
   - ConvertKit or Mailchimp require their embedded forms or API wiring — see provider docs.
2. If you prefer, use the mailto fallback already present.

Contact shown on site
- zhengkailow29@gmail.com

Image assets
- /assets/banner.png — original you provided (copy the image into this path)
- /assets/banner.webp — optimized webp version (optional)
- /assets/banner-social.png — 1200×630 cropped share image

Next steps I will take once you confirm
- Push commits to branch `design/visual-update`.
- Create a Pull Request titled: "Design: visual refresh — hero, projects, newsletter"
- Attach screenshots and a short PR description + instructions to swap the newsletter endpoint and the font.

If you want changes before I open the PR, tell me which text/content to replace (2–4 projects, 1–2 blog posts, short about blurb). Otherwise reply `Open PR` and I will open it with the prepared changes.
