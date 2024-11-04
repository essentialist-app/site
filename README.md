## Overview

The site is generated using Hugo and hosted as a Github page under a custom domain.

The Github user is essentialist-app (login with <essentialist@peaceful.ninja>).

The repo `github.com/essentialist-app/site` contains the Hugo site. It is
published using the Github action defined at `.github/workflows/hugo.yaml`.

The site is hosted at <https://essentialist.app> using custom domain
integrated with Github Page. This domain was purchased at namecheap.com.

## How to publish a change?

1. Create or update the markdown content in the repo
   `github.com/essentialist-app/site`.
1. Test it using `hugo server`. To see the draft content which won't be
   published, use `hugo server -D`.
1. Submit the change.

## Documentation

- Hugo: <https://gohugo.io/documentation/>

- Deployment using CI: <https://gohugo.io/hosting-and-deployment/hosting-on-github/>

- Custom domain: <https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site>
