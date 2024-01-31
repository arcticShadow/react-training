# Tasks x1
https://nextjs.org/docs/pages/api-reference/create-next-app

* Create new nextJS app
  * Use this command to bootstrap nextjs 
  ```
  npx create-next-app@latest --js --no-eslint --no-tailwind  --app --import-alias "@/*" --src-dir 06-nextjs  06-nextjs
  ```
* Make sure you have two pages (you may need to add a couple of pages) 

Reference: https://nextjs.org/docs/app/building-your-application/routing/pages-and-layouts
tip: add a folder insider `app` called `page1` and another folder called `page2`. Inside each folder, create a `page.js` file with the following content

```
// `app/page1/page.js` and `app/page2/page.js`
export default function Page() {
  return <h1>Hello, page!</h1>
}
```

* Add an image to one of the pages (refer to https://nextjs.org/docs/app/api-reference/components/image )

Discussion
* What's different in NextJS than vite and create react app?
* What would be easier to build a website in? 
* Can you see  any opinionated parts of NextJS?


Background: Metadata, is the data about a html page that is advertised to the browser. often represented by `<meta>` tags in the `<head>` 

# Tasks x2

* Open layout.js, and inspect the metadata variable - add Open graph metadata to this variable, using the example at https://ogp.me/ for content.
  * Hint: your working with a metadata object: https://nextjs.org/docs/app/api-reference/functions/generate-metadata#the-metadata-object
* Try adding a new property to the metadata variable - i.e. `fakePropery:true` - what happens?

Discussion
* How easy/hard is it to know if what you added is correct?
* How do you find out what acceptable values are?
