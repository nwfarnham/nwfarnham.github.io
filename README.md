# nwfarnham.github.io

Static landing page hosted on GitHub Pages.

## Analytics

Cloudflare Web Analytics uses a public site token in the module script at the end
of the page. This is not an API key. No Google Analytics, consent storage, or
cookie banner is installed. The expandable Privacy notice identifies the
analytics provider and hosting provider. It omits the operator's identity and
contact details.

The content security policy permits only the Cloudflare beacon script and its
`https://cloudflareinsights.com` collection endpoint. Other scripts and
connections remain blocked. The site retains its no-referrer policy.

Configure `nwfarnham.com` as the hostname in Cloudflare Web Analytics. Do not also
enable automatic beacon injection if the site is later proxied through
Cloudflare, or measurements may be duplicated. Ad blockers and browser settings
can prevent collection.

After deployment, visit the production hostname, inspect the network panel for
the beacon script and successful collection requests, then check the Cloudflare
dashboard after a few minutes. Localhost is not the registered analytics host.

This manual integration loads without a consent prompt and does not implement
regional exclusion. A cookieless service is not a worldwide consent exemption;
the operator must assess applicable requirements and provider terms before
publishing. The notice currently has no operator identity or privacy contact
method; assess applicable disclosure requirements before treating it as complete.
