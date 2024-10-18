## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

/app contains all the routes, components and logic of the application.
/app/lib contains functions used in the application such as reusbale utility and data fetching functions.
/app/ui contains all the UI components of the application such as cards, tables and forms. 
/public contains all the static assets of the application such as the images. 

Placeholder data

Each JavaScript Object represents a table in the database

Using the clsx library to toggle class names.

There are many cases where you need to conditionally style an element based on the state or some other condition.

NextJs can serve static asset, like images under the top level /public folder. Files inside /public can be referrenced in the application.
Instead of implementing images manually we can use the next/image component toautomatically optimize the image.

The <Image> Component.

Nested Routing.
Nextjs uses file-system routing where foulders are used to create nested loops. You can create separate UI's for each route using the layout.tsx and page.tsx files.

Creating the dashboard layout.

In Nextjs you can use a special layout.tsx file to create UI that is shared across multiple pages.

Navigating Between Pages

In Nextjs you can use the <Link> Component to link between pages in your application. 

Pattern: Showing active links

This is a common UI pattern to show an actve link to indicate to the user what page they are currently on. To do this you get the users current path from the URL. Nextjs provides hook called usePathname() that you can use to check the path and implement this pattern 