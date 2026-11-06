# GeminiMan Website Content and Roadmaps

Welcome to the public content repository for [GeminiMan](https://geminiman.net), an independent collection of Android and Wear OS applications, watch faces, research projects, and practical software ideas.

I maintain this repository as **GeminiMan / XDA-Dante63** to make development plans easier to follow. It shows what I am building now, what is waiting its turn, and which milestones have been completed. It is a living plan, not a schedule of guaranteed release dates.

## What lives here

| File | Contents |
| --- | --- |
| [`data/public-roadmap.json`](data/public-roadmap.json) | Project directory, completion states, milestones, priorities, and the post-BP research sequence. |
| [`data/site-copy.json`](data/site-copy.json) | Public introduction, developer story, quotes, optional support destinations, social destinations, and the featured project-page summaries. |

The website uses GitHub-hosted copies of these files and keeps a bundled fallback for network outages. Google Play catalog updates, server code, app-specific privacy disclosures, and backend crawler operations remain on the website infrastructure. This repository contains **no API keys, server access, personal identification details, or private research datasets**.

## Editing content

1. Open a JSON file above and choose **Edit**.
2. Change the text or the milestone status. Keep the same field names and `schemaVersion` values.
3. Update `lastUpdated` in the edited file, use **Preview**, then commit after reviewing the public text.
4. The staging site reads published data automatically. GitHub Pages may need a few minutes to refresh, and existing browser caches may briefly retain the previous version.

Use `phase` values `now`, `next`, or `later` for roadmap items. Completed project statuses should contain `complete`, `completed`, `done`, or `finished` to receive the website's green badge. Unreleased concepts must remain clearly distinguished from released applications. Do not publish sensitive health measurements, private beta data, release dates presented as promises, or identifying personal information.

## Follow the work

- [GeminiMan website](https://geminiman.net/)
- [Wellness Companion's illustrated roadmap](https://github.com/ITDev93/Geminiman-Wellness-Companion/tree/main/roadmap)
- [WearOS Manager](https://github.com/ITDev93/Geminiman-WearOS-Manager)
- [Released applications and watch faces](https://play.google.com/store/apps/dev?id=7888616598517940731)

## Optional support

Everything I share is built with the community in mind. There are no advertising requirements or mandatory subscriptions.

- [Patreon](https://www.patreon.com/xda_dante63)
- [PayPal](https://paypal.me/dante63)
- [Google Play support app](https://play.google.com/store/apps/details?id=com.geminiman.watchfaces)

Thank you for using the projects, reporting problems, sharing ideas, and helping independent development continue.
