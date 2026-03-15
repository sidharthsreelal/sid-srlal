# sid-srlal

my portfolio. built it so i'd stop having to explain what i do to people.

live at → [sid-srlal.vercel.app](https://sid-srlal.vercel.app)

---

## what's in here

a personal portfolio site. has some cool interactive stuff like a cursor that follows you around, a terminal that types itself out, and a grid that reacts to your mouse. probably over-engineered for a portfolio but i had fun with it so whatever.

**stack:**
- react + typescript
- vite
- tailwind css
- framer motion (mostly for the cursor and animations)

the whole aesthetic is this olive/off-white earthy thing. don't ask why, i just like it.

---

## running it locally

```bash
npm install
npm run dev
```

that's it. should work. if it doesn't, try deleting `node_modules` and running `npm install` again. works 90% of the time.

---

## deploying

it's on vercel. push to main and it deploys automatically. there are some `preview_err.txt` files in the root — those are just debug logs from when vercel was being annoying during setup, you can ignore them (i should probably delete them at some point).

---

## notes

- the cursor effect only works on desktop, obviously
- the terminal typing animation only starts when it's in the viewport
- there's a `data-theme` system for dark/light sections that the cursor uses to flip its colors

feel free to poke around and steal whatever. just don't copy the whole thing and call it your portfolio, that'd be weird.
