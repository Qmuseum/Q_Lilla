# Qanita Lilla — GitHub Pages website

This is a **complete, standalone static website** that can be uploaded directly to a GitHub repository. It does not require Ruby, Jekyll, Node, or a separate build step.

## Quickest way to publish

1. Download and unzip this package on your computer.
2. On GitHub, create a new **empty repository**. For a personal site, use `Qmuseum.github.io` if that repository name is available and appropriate for your account. Otherwise, create any repository and use its project-site URL.
3. Upload the **contents** of this folder to the repository root (not the enclosing folder). Make sure `index.html`, `CNAME`, `assets/`, and `.github/` are at the top level.
4. Commit the files to the `main` branch.
5. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the build/deployment source.
6. The workflow in `.github/workflows/pages.yml` should deploy the site after the commit. Check the **Actions** tab for the deployment result.
7. The package includes `CNAME` for `qanitalilla.com`. In **Settings → Pages**, confirm the custom domain. At the DNS provider where you bought the domain, configure the GitHub Pages DNS records shown in GitHub's official documentation. DNS setup depends on your provider and can take time to propagate.

Official references:
- GitHub Pages: https://docs.github.com/en/pages
- Custom domain setup: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Before publishing

- Review all biography and project text for accuracy and preferred wording.
- Confirm that the portrait is approved for public use.
- The site intentionally uses email-only contact and does **not** publish the phone number from the CV.
- The Google Scholar link is a search for the name, not a claimed verified author profile.
- Publication metadata is abbreviated in places; check the CV and complete the bibliography before treating it as definitive.
- This is a self-contained website, not the al-folio Jekyll theme. It is designed to be simpler to publish by uploading files directly. If you specifically want the al-folio theme, that requires starting from the upstream al-folio repository and merging this content into its structure.
