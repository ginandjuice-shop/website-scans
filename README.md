[![Website Scans](https://github.com/ginandjuice-shop/website-scans/actions/workflows/website-scans.yaml/badge.svg?branch=main)](https://github.com/ginandjuice-shop/website-scans/actions/workflows/website-scans.yaml)
[![Staging Image Scans](https://github.com/ginandjuice-shop/website-scans/actions/workflows/staging-scans.yaml/badge.svg?branch=main)](https://github.com/ginandjuice-shop/website-scans/actions/workflows/staging-scans.yaml)
# website-scans
Example demonstrating scanning multiple websites with [PortSwigger's Dastardly Action](https://github.com/PortSwigger/dastardly-github-action) on a schedule and manually.

> :warning: **If using in a public repo**: You may publicise vulnerabilities for all to see (although, they're already there...)!

See:
- [.github/workflows/website-scans.yaml](https://github.com/ginandjuice-shop/website-scans/blob/main/.github/workflows/website-scans.yaml) for an example of how to scan multiple websites.
- [.github/workflows/staging-scans.yaml](https://github.com/ginandjuice-shop/website-scans/blob/main/.github/workflows/staging-scans.yaml) for an example of how to scan images containing web applications.


Dastdardly creates a Junit report which, when parsed gives you feedback on the GitHub Workflow:
![Dastardly Screenshot](https://user-images.githubusercontent.com/109664963/198978316-8f0aca73-4e22-4b5e-ad2d-cf6612aca151.png)
