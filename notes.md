**Nest JS**

<Image> component - 
extension of img tag from html for automatic image optimization
refactor size, format, layout and adds lazy loading

when we use the layout.tsx. only the page component update while layout wont re-render.(layout is shared by all nested folders inside the folder where layout.tsx is made)

whenever <Link> components appear in the browser's viewport, Next.js automatically prefetches the code for the linked route in the background.

loading.tsx is a special Next.js file built on top of React Suspense. It allows you to create fallback UI to show as a replacement while page content loads.

The great thing about Partial Prerendering is that you don't need to change your code to use it. As long as you're using Suspense to wrap the dynamic parts of your route, Next.js will know which parts of your route are static and which are dynamic.