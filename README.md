# Profile Site

https://tatsukoizumi.dev/

[Astro](https://astro.build/) で構築した静的サイトを [Cloudflare Workers](https://workers.cloudflare.com/) にデプロイしています。

## Stack

- Framework: Astro (`output: "static"`)
- Hosting: Cloudflare Workers (`@astrojs/cloudflare` adapter, Wrangler)
- Package manager: pnpm

## Development

```sh
pnpm install
pnpm dev      # ローカルサーバー起動
pnpm build    # dist/ にビルド
pnpm preview  # ビルド結果のプレビュー
```
