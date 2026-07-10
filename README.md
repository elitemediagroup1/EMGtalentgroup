# EMG Talent Group Website

Production-ready static multi-page website for **emgtalentgroup.com**.

## Deploy to GitHub + Netlify

1. Upload the contents of this folder to the root of a GitHub repository.
2. In Netlify, choose **Add new site → Import an existing project** and select the repository.
3. Build command: leave blank. Publish directory: `.`
4. Deploy the site and attach the custom domain `emgtalentgroup.com`.
5. In **Netlify → Forms → Form notifications**, add an email notification for each form and send it to `hello@elitemediagroup.io`. Netlify controls notification recipients in the dashboard; this cannot be securely forced from public HTML.
6. Verify all three forms appear after the first production deploy:
   - `creator-application`
   - `talent-access-request`
   - `general-and-brand-inquiry`
7. Submit a test entry through each form and confirm receipt at `hello@elitemediagroup.io`.

## Included

- Multi-page responsive design
- Creator and brand journeys
- Creator Hubs, niches, ecosystem, leadership, process, standards, and insights
- Netlify Forms with spam honeypots
- Privacy Policy and Terms of Use
- Sitemap, robots.txt, security headers, SEO metadata, social metadata, 404, and success page
- No external libraries, trackers, AI widgets, fake logos, fake clients, or unverified performance claims

## Important launch notes

- The private roster is intentionally request-based. Approved brands receive curated creator recommendations directly from EMG; no creator data is exposed publicly.
- Update legal text with counsel as the business, analytics stack, revenue programs, or data practices evolve.
- If analytics are added later, update the Content Security Policy in `netlify.toml` and add any legally required consent controls.
