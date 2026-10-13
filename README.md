# What's Really In This Chatbot?

A classroom activity for the Wesley College Digital Life unit, *Empathy Engineered*.

Students design a nutrition-style ingredients label for an invented AI chatbot, the way
food packaging tells you what is really inside. It replaces a static PDF worksheet, and
it is built so a 13 year old never has to type anything.

## The six steps

1. **Product** — a slot machine spins a chatbot name and a marketing slogan.
2. **Ingredients** — drag tiles into "In the mix" or "Contains no". The traps (feelings,
   lived experience, memories of its own life, genuine concern, a body that gets tired)
   refuse to go in the mix and explain why.
3. **Amounts** — tap to set how much of each. The label reorders itself most-first and a
   wellbeing star rating moves as flattery and engagement design go up.
4. **Warnings** — peel and stick at least two warning stickers.
5. **Pairing** — drag humans and real-world things onto a plate, at least three.
6. **Packet** — the finished label, with barcode and stamp, saveable as a picture.

## Running it

Open `index.html` in any browser. That is the whole thing.

It is a single self-contained file. No build step, no install, no dependencies, and no
internet connection needed once the page has loaded.

## Privacy

Nothing is collected, stored, or sent anywhere. There is no database, no analytics, no
login, and no network request of any kind. Everything a student does lives in the
browser's memory and disappears when the tab closes.

The only phone number in the file is Kids Helpline (1800 55 1800), a public national
service line.

## Hosting and embedding

Served via GitHub Pages, then embedded in Schoolbox with an iframe:

```html
<iframe src="https://wesdlpteam.github.io/empathy-engineered-/"
        width="100%" height="900"
        style="border:1px solid #ccc; border-radius:8px;"
        title="What's really in this chatbot?"></iframe>
```

Use the `github.io` address, not the `raw.githubusercontent.com` one. The raw address
serves the file as plain text and students would see code instead of the activity.

To update: replace `index.html` and push. The address stays the same, so the Schoolbox
embed keeps working untouched.
