# Castbuilder Starter

This example shows a very basic version of a *Castbuilder* project with Next.js. 

- There's one page, `pages/index.js`, that shows the visual editor (in development) and the compiled version (in production). 
- All the magic is done in, `pages/api/builder/handle.js`, that has to be setup once and handles templates saving and loading.

## How to

#### Development

Clone this repository:
```sh
git clone https://github.com/learncast/cast-builder-starter
```
Install dependencies:
```sh
npm i
```
Run in development:
```sh
npm run dev
```

#### Production

Build for production:
```sh
npm run build
```
Run in production:
```sh
npm start
```

Deploy it to the cloud with [Vercel](https://vercel.com/new) ([Documentation](https://nextjs.org/docs/deployment)).
