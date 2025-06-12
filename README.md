# Tech_Watch

The most interesting topics from my personal Tech Watch.

---

## Auto-Sizing Columns in CSS Grid: `auto-fill` vs `auto-fit` - 2022

src = https://css-tricks.com/auto-sizing-columns-css-grid-auto-fill-vs-auto-fit/  

The idea is to easily handle the responsiveness of our columns while using CSS Grid.  
And not having to write a single media query for that...  

We’re able to do that using just one line of CSS.  
This magical, media-query-less responsiveness is achieved using the `repeat()` function and the `auto-xxx` keywords.  

the `repeat()` function allows you to repeat columns as many times as needed.  
For example, if you’re creating a 12-columns grid, you could write the following one-liner:
```css
.container {
  display: grid;

  /* define the number of grid columns */
  grid-template-columns: repeat(12, 1fr);
}
```

The `1fr` is what tells the browser to distribute the space between the columns so that each column equally gets one fraction of that space.  
That is, they’re all fluid, equal-width columns. And the grid will, in this example, always have 12 columns regardless of how wide it is.   
This, as you have probably guessed, is not good enough, as the content will be too squished on smaller viewports.  



---

## Bun & Hono - 2023

src = https://youtu.be/uxMADW3CmN4  

Using **Bun** & **Hono** instead of **Node.js** and **Express**.  

---

## TODO - Next.js 15 - 2024

src = https://youtu.be/Zq5fmkH0T78?si=Vjqom5Ay2J03MLCp



---

## Node.js 23 - 2025

src = https://www.totaltypescript.com/typescript-is-coming-to-node-23

Node now supports **TypeScript** with zero extra configuration.  
After years of waiting, we can finally run **.ts** files directly with Node: `node example.ts`

However, it seems like **Bun** can do the same thing:  
https://bun.sh/docs/runtime/typescript  
"Bun can directly execute .ts and .tsx files just like vanilla JavaScript, with no extra configuration."

---

## 

---
EOF
