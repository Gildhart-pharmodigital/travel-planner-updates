# Travel Planner updates

The released versions of **Travel Planner by Gildhart**, a WordPress plugin for
pharmacy travel clinics, and the file each installed copy reads to find a newer
one. Nothing else lives here: the plugin's source, tests and guidance pipeline
are Gildhart's own.

<!-- latest -->
**Latest: 1.5.0** (2026-11-13): [gildhart-travel-planner-1.5.0.zip](https://github.com/Gildhart-pharmodigital/travel-planner-updates/raw/main/travel-planner/gildhart-travel-planner-1.5.0.zip)
<!-- /latest -->

## Installing it on a site

1. Download the latest zip (the link above).
2. In wp-admin: Plugins > Add New Plugin > Upload Plugin, choose the zip,
   Install Now, then Activate.
3. Travel Planner > Settings: prices, booking link, colours. Visitors see
   nothing until "Show the planner to everyone" is ticked.

From then on WordPress finds each new version here and installs it by itself
(Travel Planner > Settings > Updates can turn that off). A site's settings and
prices are kept across every update.

## What is here

```
travel-planner/info.json                          the latest version, its zip and its notes
travel-planner/gildhart-travel-planner-<v>.zip    every released version
```

Each file is written by Gildhart's release workflow when a version passes its
checks. A version, once here, is never changed or removed.
