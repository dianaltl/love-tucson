# Love, Tucson ♡

A static, GitHub Pages-ready community/event discovery website for Tucson, Arizona.

## Files
- `index.html` — homepage, event cards, interactive calendar, event modal
- `blog.html` — blog landing page
- `sources.html` — source/transparency page
- `css/style.css` — all styling
- `js/events.js` — event data (edit this to add real events)
- `js/main.js` — calendar, filters, mobile menu, and event modal behavior

## Add an event
Open `js/events.js` and add an object like:

```js
{
  id: 6,
  date: '2026-10-03',
  title: 'Your Real Tucson Event',
  category: 'arts',
  time: '6:00 PM – 9:00 PM',
  location: 'Venue Name, Tucson, AZ',
  description: 'A verified description from the organizer.',
  source: 'https://official-event-source.example/'
}
```

Categories currently supported: `arts`, `community`, `music`.

## Important
The events in `events.js` are clearly marked DEMO EVENT placeholders. Replace them with verified events before publishing.

## GitHub Pages
Upload this folder to a GitHub repository. GitHub Pages can publish static HTML, CSS, and JavaScript directly from a repository. Configure the repository's Pages settings to publish from the `main` branch and root folder.
