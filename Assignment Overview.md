# Assignment: Style a Web Page with Tailwind CSS

**Topic:** Tailwind CSS · **Difficulty:** Beginner → Medium · **Time:** 3–4 hours · **Total: 100 marks**

## Overview

Today you learned Tailwind CSS. Now you'll use it on a real page.

You've been given an **unstyled HTML file** (`tailwind-assignment.html`) for a fictional coffee shop called **Bean & Brew**. Right now it's plain black text on a white background — a bare skeleton. Your job is to turn it into a polished, modern, responsive website **using only Tailwind utility classes**.

Everything you need is already set up: the Tailwind CDN is loaded in the file, so you can start adding classes and see results immediately. Open the file in your browser, open your code editor beside it, and begin.

## The Rules

- **Style using Tailwind utility classes only** (`class="..."`). No separate CSS file, no `<style>` block, no inline `style=""` attributes.
- **Do not change the HTML structure or the text.** Your job is styling, not rewriting. You may only add `class` attributes (and, if you like, swap the image placeholder `<div>`s for real `<img>` tags).
- **It must be responsive** — it should look good on a phone *and* on a laptop. Use Tailwind's breakpoint prefixes (`sm:`, `md:`, `lg:`).
- Work in a repo called `tailwind-assignment`, commit as you go, and push to GitHub.

## What Your Page Must Include

Each section of the page must be styled. Aim for a clean, consistent look with one colour theme throughout.

1. **Navigation bar** — a horizontal bar with the logo on one side and the links/button on the other. (`flex`, `justify-between`, `items-center`)
2. **Hero section** — a large, bold headline that grabs attention, with styled call-to-action buttons.
3. **Features (3 cards)** — displayed in a row on desktop and stacked on mobile. Use cards with padding, rounded corners, and shadows. (`grid`, `md:grid-cols-3`, `gap`, `rounded`, `shadow`)
4. **Menu** — a responsive grid of menu cards, each with the item name, description, and price neatly laid out.
5. **About section** — a two-column layout (text + image area) that stacks into one column on mobile.
6. **Contact form** — a centered form with styled inputs. Inputs should have a visible focus state. (`focus:ring`, `border`, `rounded`, `w-full`)
7. **Footer** — a multi-column footer with a dark background and light text.

## Must-Have Techniques (checklist)

Your submission should demonstrate all of these:

- ☐ **Flexbox** (`flex`, `justify-*`, `items-*`) — e.g. the nav bar
- ☐ **Grid** (`grid`, `grid-cols-*`, `gap-*`) — e.g. the features and menu
- ☐ **Responsive breakpoints** (`sm:`, `md:`, `lg:`) — layout changes between mobile and desktop
- ☐ **Spacing** (`p-*`, `m-*`, `gap-*`) — consistent, not cramped
- ☐ **Typography** (`text-*`, `font-*`) — a clear size hierarchy (big headings, readable body)
- ☐ **Colours** (`bg-*`, `text-*`) — one consistent theme/palette
- ☐ **Rounded corners & shadows** (`rounded-*`, `shadow-*`) — on cards and buttons
- ☐ **Hover states** (`hover:*`) — buttons and links respond to the mouse
- ☐ **Focus states** (`focus:*`) — form inputs on the contact form

## How You'll Be Marked (100 marks)

| Criterion | What we're looking for | Marks |
|---|---|---|
| **Responsiveness** | Looks good on both mobile and desktop; layouts adapt with breakpoints | 25 |
| **Layout (flex & grid)** | Nav, feature cards, and menu use flexbox/grid correctly | 25 |
| **Visual polish** | Consistent colours, good spacing, readable typography, rounded corners & shadows | 20 |
| **Interactivity** | Working hover states on buttons/links and focus states on inputs | 15 |
| **Completeness** | Every one of the seven sections is styled | 10 |
| **Code quality** | Sensible, consistent use of classes; committed to GitHub | 5 |

**Pass mark: 60.**

## Tips

- **Pick your colour theme first** and stick to it — choose one accent colour (e.g. an `amber`, `emerald`, or `indigo`) and use its shades consistently. A consistent palette instantly looks more professional than a rainbow.
- **Mobile first.** Style it for a narrow screen first, then add `md:` classes to change the layout on bigger screens.
- **Resize your browser window** constantly as you work to check it still looks good at every width.
- **When stuck, search the Tailwind docs** (tailwindcss.com) — searching the utility you want (e.g. "shadow", "grid columns") is faster than guessing.
- There's no single "correct" design. Make it *yours* — you'll be marked on the techniques above, not on copying an exact look.

## Submitting

- Push your finished `tailwind-assignment` repo to GitHub.
- Submit the repository link.
- If you used any AI help, declare it in your README.

---

That's the standalone brief. Two quick notes:

- The **section list and checklist line up exactly** with the unstyled HTML I gave you — the seven sections and the guiding comments in the file match items 1–7 here, so students can work section by section.
- I set the **pass mark at 60** to match the other single-day assignments in this series (the JS ones use 60; the multi-day capstones use 70–75). Adjust if your cohort's standard differs.
