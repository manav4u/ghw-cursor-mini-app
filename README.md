<h1 align="center">Tipwise</h1>

<p align="center">
A tip calculator in one HTML file, with a dark mode toggle.<br>
Built with Cursor for MLH Global Hack Week: Hacktoberfest 2026.
</p>

<p align="center">
<sub>HTML &nbsp;|&nbsp; CSS &nbsp;|&nbsp; vanilla JavaScript &nbsp;|&nbsp; no build step</sub>
</p>

---

## What it does

Enter a bill, pick a tip, say how many people are splitting it, and Tipwise shows the tip, the total and what each person pays.

- Bill amount, tip percent and number of people
- One-click tip presets: 10%, 18%, 20% and 25%
- Live results for tip, total and per-person share
- Dark mode toggle that remembers your choice and follows your system setting on the first visit

## Run it

No install and no server. Download the file and open it in a browser.

```bash
git clone https://github.com/manav4u/ghw-cursor-mini-app.git
cd ghw-cursor-mini-app
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

You can also double-click `index.html` in your file manager.

## Example

| Input | Value |
| --- | --- |
| Bill | 86.50 |
| Tip | 18% |
| People | 2 |

| Result | Amount |
| --- | --- |
| Tip | 15.57 |
| Total | 102.07 |
| Per person | 51.04 |

## About this project

This is my submission for **Challenge 1: Build a Mini App with Cursor** in MLH [Global Hack Week: Hacktoberfest](https://ghw.mlh.com/events/open-source) (October 9 to 15, 2026). The challenge asks for something small but real, built from a blank file with an AI pair.

How it was built, honestly:

- I used the **Cursor Agent CLI** with the **Auto** model on a Cursor Free account, not the desktop app. Cloud agents need a paid plan, and Free accounts can only use Auto.
- The app came from one plain-language prompt asking for a single-page tip calculator with a dark mode toggle.
- I checked the result by rendering it in a headless browser and comparing the numbers in the example above.

## Project layout

```text
.
|-- index.html   markup, styles and script in one file
`-- README.md
```
