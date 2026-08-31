# Vercel Design System Clone

A faithful clone of the Vercel design system — white canvas with Geist font, shadow-as-border technique, and workflow accent colors.

## Features

- **White Canvas**: Pure white `#ffffff` background with `#171717` Vercel black text
- **Typography**: Geist font family with `font-feature-settings: 'liga'` (ligatures enabled)
- **Shadow-as-Border**: Signature `rgba(0,0,0,0.08) 0px 0px 0px 1px` replaces traditional CSS borders
- **Typographic Scale**: 48px display with -2.4px tracking → 12px caption, 3-weight system (400/500/600)
- **Workflow Colors**: Ship Red `#ff5b4f`, Preview Pink `#de1d8d`, Develop Blue `#0a72ef`
- **Multi-layer Shadows**: Card elevation with border + ambient + inner highlight rings
- **Pill Badges**: `#ebf5ff` background, `#0068d6` text, 9999px radius
- **Focus States**: `2px solid hsla(212, 100%, 48%, 1)` accessibility focus ring
- **Workflow Pipeline**: 3-step Develop → Preview → Ship with color-coded pills
- **Responsive**: Mobile < 768px, Tablet 768-1024px, Desktop > 1024px

## Demo

Open `public/index.html` directly in a browser, or run:

```bash
npm install
npm run dev
```

Then visit `http://localhost:8083`

## Design System Reference

Based on the [Vercel design system](https://vercel.com/design) from the `popular-web-designs` skill.

## License

MIT