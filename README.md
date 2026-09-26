# Akhila Datta Dola — personal website

Live at https://adola700.github.io

## Update the site

1. Edit `content/site.json` for profile links and public email.
2. Add or edit JSON posts in `content/posts/` for the blog.
3. Run `npm run build` to regenerate `docs/`.
4. Commit and push the content and `docs/` changes to `main`. GitHub Pages publishes `docs/` automatically.

Run `npm run dev` for a local preview at http://127.0.0.1:4173 after building.

No dependencies or database required. Two initial blog entries are adaptations of the author’s public Jev-Omni model card and Hinglish TTS announcement, with links to the original sources. The email link appears when a public email is set in `content/site.json`.

## Optional custom domain

Register the domain, configure it in the repository Pages settings, and apply the DNS records GitHub provides. Update `origin` in `content/site.json` and rebuild after the domain is connected.
