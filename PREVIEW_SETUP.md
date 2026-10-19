# Mayura Café — V2.1 GitHub Pages PREVIEW ONLY

**Status:** Design prototype; **not** the official restaurant website. This preview was staged on `mayura-v2-1-pages-preview`, which is separate from the existing `main` branch and its FTP deployment workflow.

## Where the website lives

The complete responsive preview is in `docs/index.html`. It is a standalone file: CSS, JavaScript, illustrative food-card images, and the two earlier reference photos are embedded.

The design includes:
- Prominent Get Directions links to the user-confirmed listing: https://maps.app.goo.gl/mbjmqLDb7YmWp7bW9
- Confirmed restaurant address and **Monday–Sunday, 7:30 AM–9:30 PM**
- Menu highlights and interactive provisional price list
- Clear **“design preview / concept in progress”** disclaimer and `noindex,nofollow` metadata

**Provenance:** None of the twelve user-supplied Google Maps menu screenshot images are used. Menu names and provisional prices were transcribed as text only. Food tiles are illustrative, not authenticated dish photos. Earlier user-supplied storefront/dosa photos are for preview; publicly sharing the preview requires the restaurant owner to confirm publication and photo rights.

## GitHub Pages activation (account owner)

A GitHub repository setting—not a code change—is needed to activate Pages. Under the repository **Settings → Pages**:

1. For **Build and deployment**, select **Deploy from a branch**.
2. Branch: **`mayura-v2-1-pages-preview`**.
3. Folder: **`/docs`**.
4. Save and wait for the Pages deployment to succeed.

The expected Pages URL, **only after activation**, is `https://gyanart.github.io/mayuracafe/`. Do not claim this URL works until it has been verified after Pages is enabled.

**Private repository caveat:** GitHub Pages publication from a private repository depends on the owner's GitHub plan and Pages settings. The resulting Pages website can be publicly accessible despite the repository being private. Do **not** change repository visibility merely to enable Pages without considering the existing production sources and obtaining owner approval.

## Production safety

The existing `.github/workflows/deploy.yml` in `main` deploys `site/` to a cPanel subdomain on pushes to `main`. Do not merge this preview branch to `main` just to enable Pages. Selecting the preview branch in Pages **does not** merge it and should not trigger the FTP workflow.

Do not call this finished, published on the restaurant's official domain, or an indexed portfolio case study. Before any official restaurant launch, confirm owner signoff, licensed images, provisional menu prices/GST, real-device usability and accessibility, exact domain and rollback plan.

## Portfolio purpose

This preview demonstrates the visual/design implementation stage of a true end-to-end GyanArt project. Record owner feedback and the screenshots of responsive QA as dated artifacts; no improvement in restaurant visits, sales or rankings has been measured or claimed.
