# A quick app to learn about Next.js

## What is Next.js?

-Minimalistic framework for rendering react applications on the server

## CORE FEATURES

- Server rendered react apps
- Automatic code splitting (and lazy loading)
- Prevents loading of unnecessary code
- Simple page based routing (no need to map your routes)
  (using the Link Module to navigate between pages)
- Built in CSS support
- Hot Reloading
- Deployment

## SETUP

npm init
npm install next react react-dom

pages/index.js
export default ()=> <div> Hello World</div>

Import Link from next/link

<Link href="/"><a>Home</a></Link>
<Link href="/"><button>Home</button></Link>
