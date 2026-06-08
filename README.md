# Anushka's Confetti Corner

A festive birthday-card helper web page that creates funny, personalized card messages from a recipient's details.

## What It Does

- Takes the person's name, age, date of birth, hobby, recipient type, and personality.
- Generates a longer funny birthday wish that matches the selected personality.
- Displays the result like the inside of a birthday card.
- Keeps previous cards visible by stacking new cards above older ones.
- Changes the color theme based on the person's mood or personality.
- Includes a birthday countdown using the date of birth.
- Lets you copy each card message to the clipboard.
- Plays a happy-birthday melody with the person's name using browser speech.
- Includes optional instrumental background music.
- Lets you blow out the candle with extra party popouts and sprinkles across the page.
- Includes a GitHub profile button in the page header.

## Files

- `birthday-card-helper.html` - The complete web app.
- `README.md` - Project explanation and usage notes.

## Tools And Technologies Used

- **HTML5** for the page structure, form inputs, buttons, and card layout.
- **CSS3** for the festive theme, responsive layout, birthday-card styling, doodle cake, balloons, confetti, and candle animations.
- **JavaScript** for generating birthday messages, stacking cards, copy buttons, countdown logic, theme switching, and interactive candle blowing.
- **Web Speech API** for saying "Happy Birthday" with the person's name.
- **Web Audio API** for the happy-birthday melody, whoosh sound, and instrumental background music.
- **Clipboard API** for copying generated card text.
- **Python `http.server`** was used locally to preview the static page in the browser.

## How To Run

Open the HTML file directly in a browser, or serve it locally:

[```bash
python -m http.server 4173 --bind 127.0.0.1 --directory outputs]
cd "/c/Users/anush/Documents/Codex/2026-06-08/create-a-web-page-to-help/outputs"
git init
git add index.html README.md
git commit -m "Add Anushka's Confetti Corner"
git branch -M main
git remote add origin https://github.com/anushkas13122005/anushkas-confetti-corner.git
git push -u origin main
```

Then open:

```text
https://anushkas13122005.github.io/anushkas-confetti-corner/
```

## GitHub Profile Link

The page is connected to this GitHub profile:

[https://github.com/anushkas13122005](https://github.com/anushkas13122005)

## Notes

The softer feminine voice depends on which voices your browser and operating system provide. The app tries to choose voices like Zira, Samantha, Jenny, Serena, or similar names first, then falls back to a softer pitch and slower speech rate.
