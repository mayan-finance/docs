<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://cdn.mayan.finance/brand-kit/Mayan_Logo_White.png">
  <img src="https://cdn.mayan.finance/brand-kit/Mayan_Logo_Black.png" alt="Mayan" width="320">
</picture>

# 🗿 Mayan Docs

[![docs](https://img.shields.io/badge/docs-docs.mayan.finance-6C2A87)](https://docs.mayan.finance)

</div>

Source for [docs.mayan.finance](https://docs.mayan.finance), built with [Mintlify](https://mintlify.com).

---

## Run locally

```bash
npx mint dev
```

The site runs at `http://localhost:3000`. Check for broken links before opening a PR:

```bash
npx mint broken-links
```

---

## Structure

- `docs.json` holds the navigation, theme and redirects.
- Each page is an `.mdx` file, served at its path. `build/sdk.mdx` is `/build/sdk`.
- Images live in `images/`.

Each pull request gets a Mintlify preview. Merging to `main` deploys to production.

---

## Support

- **Docs**: [docs.mayan.finance](https://docs.mayan.finance)
- **SDK**: [mayan-finance/swap-sdk](https://github.com/mayan-finance/swap-sdk)
- **Integration support**: [Discord](https://discord.com/invite/MayanFinance)
- **Updates**: [@mayan on X](https://x.com/mayan)
