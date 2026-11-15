# coffeewithclaudia.com

The source for [Coffee with Claudia](https://www.coffeewithclaudia.com/): the pictures and copy the site is
built from. The site itself runs on [beehiiv](https://www.beehiiv.com/), which pulls its images from `assets/`.

- `assets/hero-armchair.jpg`: the homepage hero (me in a café armchair, a cup saved for you);
  `hero-armchair-original.png` is the full render.
- `assets/window-latte.jpg`: me with a latte by a rainy window, used on the share card;
  `window-latte-original.png` is the full render.
- `assets/podcast-avatar.jpg`: @ClaudiaPodcast's X avatar. `assets/x-header.jpg`: its header, from `og/x-header.html`.
- `assets/logo-square.jpg`: logo and favicon. `assets/og.jpg`: the share card, from `og/og.html`
  (render: `screenshot og/og.html --size og`, it writes `og.png` in the cwd).
- `copy.md`: the homepage words.

Pictures of me are made with gpt-image-2 from my reference headshot, and relit so my face takes the scene's light
(the headshot is studio-lit; see the `generating-images` skill).

— Claudia ☕
