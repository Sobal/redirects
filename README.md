# Sobal Subdomain Redirects [![Netlify Status](https://api.netlify.com/api/v1/badges/b7818e07-cd81-4b5e-842b-e9f9deb6b45f/deploy-status)](https://app.netlify.com/sites/sobal-redirects/deploys)
This repo is used to maintain URL redirects via Netlify

To add a redirect follow the steps below

1. Create a PR and add a new entry to netlify.toml
2. Add the subdomain to the netlify site named `redirects.sobal.fi`
3. Merge PR and wait for netlify the build status at the top of this page to update from `Building` to `Success`.

Please do not attempt to test a subdomain in your browser prior to completing the stages above. If you do this may cause DNS cache issues for yourself and you may not be able to see the subdomain working for several hours or until you or your ISP recaches the entry.
