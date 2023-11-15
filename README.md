# dEagleUI

This is an app that uses tldraw and the GPT-4-vision API to generate html based on a wireframe you draw.
# <p align='center'> 🔗 _LIVE_ - [_**dEagleUI**_](https://deagleui.vercel.app/)</p>

## Images

<a href="https://deagleui.vercel.app" target="_blank">
  <img src="https://i.imgur.com/P2ptMEv.jpg"> 
</a>

<a href="https://deagleui.vercel.app" target="_blank">
  <img src="https://i.imgur.com/JEr4HWS.png"> 
</a>

<a href="https://deagleui.vercel.app" target="_blank">
  <img src="https://i.imgur.com/ACb34F7.png"> 
</a>

# About

This works by just taking the current canvas SVG, converting it to a PNG, and sending that png to gpt-4-vision with instructions to return a single html file with tailwind.

> Disclaimer: This is a demo and is not intended for production use. It doesn't have any auth so you will go broke if you deploy it.

## Getting Started

This is a Next.js app. To get started run the following commands in the root directory of the project. You will need an OpenAI API key with access to the GPT-4 Vision API.

> Note this uses Next.js 14 and requires a version of `node` greater than 18.17. [Read more here](https://nextjs.org/docs/pages/building-your-application/upgrading/version-14).

```bash
add "OPENAI_API_KEY=sk-your-key" > .env and change "sk-your-key" on your own API keys
npm install
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

To run build
```
npm run build
```

## Deployment
**<p align='center'> Deployed on [_**Vercel**_](https://vercel.app/)</p>**
