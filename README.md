# PTV Inspector Tracker

Despise inspectors and how they treat passengers, so here's a handy website to report the exact locations of them at all times. Use to check heatmaps of current locations, report inspectors and remember to share this with your mates!

> [!NOTE]
> Currently a work in progress! Will always remain open source + open to contributers :)

## Details

### Features

- Google Maps for mapping ...maybe, still deciding on this. Don't love that it could cost me money
- Uses your location to pinpoint inspector locations
- PTV API to track current tram + train locations, so inspectors can be attached to those vehicles
- Use Supabase (Postgres) for storing inspector locations

### Framework

Vercel + NextJS + React + HeroUI + Supabase

## Next Steps

- Integrate PTV API - get current tram + train (+ bus?) locations, add option to attach inspectors to these vehicles
- More security for supabase requests - might need to add users to report inspectors? Could create some sort of leaderboard for most reported inspectors, most reports, etc
- Merge reports in same location, upvotes them and adds to heatmap weighting
- Descriptions for reports? Or just link to a facebook group post? Costly space wise, but could be useful
- A way to report inspectors without location services, just default location to melbourne CBD if location time out or rejected by user
- Lock Google Maps API to custom domain, also rate limit requests
