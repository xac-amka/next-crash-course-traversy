# Next.js Crash Course - Server Side React

## By traversy Media [Link](https://www.youtube.com/watch?v=IkOVe40Sy0U)

## Core Features of Next
 - Server-rendered React apps
 - Automatic code splitting
 - Simple page based routing
 - Built in CSS support
 - Hot Reloading
 - Deployment is very simple

## [0] Installation & Setp
```shell

npm init
npm install next react react-dom
{
	"scripts": {
		"dev": "text",
		"build": "next build",
		"start": "next start"
	}
}
```

## [1] Sample
 > pages/index.js
```js
export default()=> <div> Hello World </div>
```

## [2] Link module
```js
import Link from 'next/link';

<Link href="/"><a>Home</a></Link>
<Link href="/about"><button>About</button></Link>
```

## [3] Deployment

## [4] Learning Resources
 - [https://nextjs.org/learn/basics/create-nextjs-app](https://nextjs.org/learn/basics/create-nextjs-app)
 - [https://www.coindesk.com/coindesk-api](https://www.coindesk.com/coindesk-api)