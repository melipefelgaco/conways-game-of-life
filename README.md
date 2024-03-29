## TODO:

-   RECORD GIF FOR CURRENT VERSION - THE GAME IS RENDERING VERY FAST MAKING IT SEEM LIKE THE CELL IS TELEPORTING
-   TIDY UP DOCS FORMATATION - WROTE THIS IN A HURRY AND NOW ITS MESSY BUT READABLE

# Game of life

Based on [Conway's game of life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)

Making this for fun

# Recent Updates:

(WIP) August 12th 2022:

Only a single cell so far and it's going crazy inside a useEffect function that is making it re-render very fast. So visually it's like the cell is blinking on the board and teleporting everywhere. I have to find a way to record a gif for this later but at this point it's not a bug anymore, it's a featureTM
![](V1.1.2.png)

(WIP) August 7th 2022:
![img](20220807184512.png)

(WIP) September 23rd 2022:

Finally had some time to work on this app and want to finish it soon but let's see :laughing:

Now generating the initial board with a fixed value for the initial cells displayed on the board. Next steps are to dinamically get this initial cell value dinamically through user input (might as well make it for the board size too, with some restrictions) and then finish the logic for the cells state of being alive/dead based on the game rules

![img](20220923133517.png)

April 14th 2023:

The game is (finally) finished. I don't know if that can be said for anything and I could implement a lot more stuff on it but it's working 100% and will call it finished just for the sake of finishing a project ;P
![img](20230414180126.png)

# NextJ auto-generated docs:

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

-   [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
-   [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
