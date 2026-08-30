# Vibework

Vibework is a single-file field guide to the social web: mainstream platforms, independent communities, federated networks, archives, and niche places worth finding.

Live site: https://vibework.pages.bu.app/

## What is included

- Search across the catalog by name, category, or description
- A compact filter menu for mainstream, niche, new wave, decentralized, regional, and more
- A visible link to every listed network
- Expandable "what you can do" descriptions on every card
- A local-only submit form with a name, category, official link, and description

## Run it

Open `index.html` in any modern browser. There is no build step and no server required.

## Update it

Edit the `networks` data in `index.html`, then republish the same file to the Vibework page. The public address stays the same while the catalog changes. GitHub is the source-of-truth repository; the live page is a static publication of that file.

Each network entry follows this order:

```js
['Facebook', 'What people do there.', 'Mainstream', 'F', 'https://facebook.com', 'blue']
```

The second value is the expandable description. The fifth value is the link that appears below it on the card.

## Contributing

Add networks with a working official URL, a short description of what people do there, and a useful category. Prefer independent, niche, regional, open, and new communities while keeping the major platforms represented.

Licensed under the MIT License.
