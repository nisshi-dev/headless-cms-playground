## headless-cms-playground

ヘッドレスCMSの実験用リポジトリです。
どのヘッドレスCMSがもっともよい体験か検証するためのリポジトリです。

### Sanity

[Sanity](https://www.sanity.io/)を使用しています。

- sanity-with-astro-sample
  - フロントURL
    - https://sanity-with-astro-sample.vercel.app/
  - CMS
    - https://nisshi-dev-astro-sample.sanity.studio/
  - その他
    - 現在、CMSでデータ入稿した後、フロントエンドのビルドを手動で行う必要があります。
- sanity-with-nextjs-sample
  - フロントURL
    - https://sanity-with-nextjs-sample.vercel.app/
  - CMS
    - https://nisshi-dev-nextjs-sample.sanity.studio/
  - その他
    - デプロイしたCMSページでデータ入稿ができないため、ローカルで起動してデータ入稿を行う必要があります。
      - https://github.com/sanity-io/sanity-template-nextjs-clean/issues/120