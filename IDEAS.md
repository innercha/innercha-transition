# Future Ideas

These are possibilities, not current commitments. They should not distract from Phase 2 or from making music.

## Lightweight artist data layer

Create machine-readable snapshots that Codex, Claude, or ChatGPT can use without repeated screenshots.

Possible structure:

```text
data/
  releases.json
  spotify-public.json
  private-metrics.example.csv
  snapshots/
scripts/
  fetch_spotify_public.*
```

## Public Spotify metadata

Potential uses:

- artist, album, and track IDs
- canonical URLs and URIs
- artwork
- release dates
- credits and basic public metadata
- available public follower or popularity fields, subject to current API access

Important: Spotify's public Web API should not be assumed to expose private Spotify for Artists analytics such as detailed streams, saves, sources, demographics, or city data.

## Manual private analytics

Periodically record or export useful private metrics in a local or private CSV:

- date
- artist
- release
- streams
- listeners
- saves
- followers
- notes

Do not commit private exports unless intentionally sanitized.

## Other data sources

- DistroKid distribution and earnings exports
- Bandcamp sales exports
- YouTube Data API public metrics
- SoundCloud public/account data where officially available
- MusicBrainz canonical metadata
- ListenBrainz listening-history data
- Manual event, booking, and relationship notes

## Career operations ideas

- Release database
- Artist timeline
- Contact and follow-up notes
- Booking history
- Set and performance footage index
- Press kit generator
- Monthly project review
- Reusable release checklist

## Website ideas

- Minimal landing page
- Music and live clips
- Short meaning/story
- Mailing list
- Booking contact
- Archive note connecting SubRoot to Innercha

## Icaro

Icaro is a separate collaborative project with Pat. Its low-pressure reawakening can coexist with Innercha. Do not merge its identity or roadmap into this transition repository unless a shared asset or schedule genuinely requires coordination.

