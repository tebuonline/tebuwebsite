# tebu website: putting it live on Cloudflare

Everything the site needs is in the `public` folder: `index.html` plus all photos and videos in `img/`.

## Upload

1. Log in to Cloudflare and go to **Workers & Pages → Create → Pages → Upload assets** (drag and drop).
2. Name the project `tebu`, then drag in the **contents of the `public` folder** (index.html and the img folder).
3. Deploy.

## Add your domain

Open the Pages project → **Custom domains → Set up a custom domain** → type your domain and follow the prompts. If the domain is already on your Cloudflare account, it connects within a few minutes.

## Updating later

Upload the new `public` folder contents to the same project (Create new deployment). Your domain stays connected.
