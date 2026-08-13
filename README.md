# ВОРС — pet grooming studio landing

Landing page for a fictional dog/cat grooming studio ("ВОРС") in Moscow:
services and prices by size, booking form, masters, before/after gallery,
reviews. Practice project for a freelance-portfolio landing-page format. Two
hero variants (`/` and `/hero-b`) for A/B-style comparison.

## Stack

Next.js 16, React 19, TypeScript, Tailwind CSS 4. Copy, prices, and studio
details live in `src/content.ts`.

## Structure

```
src/
├── app/
│   ├── page.tsx        # hero variant A
│   ├── hero-b/page.tsx # hero variant B
│   └── layout.tsx
├── components/          # Prices, Booking, Masters, Works (before/after), Reviews, ...
└── content.ts             # studio info, prices, copy
```

## Running it

```bash
pnpm install
pnpm dev
```
