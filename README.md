# ts-starter
By Garran Plum

## Overview
This Typescript starter pack contains everything you need to develop a website or app in Typescript, test it locally in your browser, and publish it to a static hosting website like Firebase Hosting.


## What's Inside
This is a minimum scaffold with an index.html page and main.ts script. The development server is [Vite](https://vitejs.dev). Typescript and Vite are oth are installed automatically.

## Installation with NPM
Place the entire contents of this repo in what will become the **root folder** of your application. From the command line *in that folder*, run:

```npm install```

## Usage
Edit the index.html in the *root* folder. Edit the `main.ts` file in the *src* folder. To add Typescript in additional files, they must be loaded in `index.html` using the pattern shown for `main.ts`.

## Running the App
From the command line in your *root folder*, to start the webserver, run:

```npm run dev```

Then visit `http://127.0.0.01:5173` in your browser to view your app. Your Vite installation may display a different server address after you `npm run dev`, in which case you should visit that address instead.