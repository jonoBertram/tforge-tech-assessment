# Section 7: Additional Programming and Design Skills

### Question 1

> Explain the concept of server-side rendering (SSR) in Next.js and its benefits.

SSR in NextJS refers to a method of serving web pages to a client whereby pages are rendered on the server upon receiving a request. This makes sites much more performant as only parts of the HTML served on the client that are being viewed and interacted with by the user are updated. It also means that a stale version of the site can still be shown on the client and interacted with in the event of a slow internet connection which is much better than having no site to display or a hanging site.

### Question 2

> Describe the usage of API routes in Next.js and how they differ from traditional REST APIs.

API routes are used by defining routes inside the `pages/api/{endpoint_name}.js` or `app/api/{endpoint_name}/route.js` folder depending on which structure you are using in your NextJS app. These routes will be treated as public API endpoints instead of pages and are server-side only. They are javascript functions that accept `NextApiRequest` and `NextApiResponse<T>` props to define the data structure of the request.

Because API routes are server-side-only bundles, they do not increase the client bundle size and therefore do not effect the initial page load speed of the app on a client which is an immediate advantage over a traditional REST API setup. This can also have the downside of making these endpoints difficult to test in non-production environments if not configured correctly.

### Question 3

> Discuss the role of static site generation (SSG) in Next.js and its advantages for performance and SEO.

When SSG is used, a page is rendered once at build time and that version of the page is what is served to the client. Statically generated pages can still be used with dynamic data but server-side rendered pages generally handle this better. SSG is great for pages that will barely ever change once created like a 404 page or an "About Us" page. It is great for SEO because statically generated pages can be easily scraped for keywords and links as it is all readily available at any time without large chunks of data missing that would otherwise only be provided at run time. A statically generated page requires little to no rendering on-demand meaning fantastic performance is possible when using this method.
