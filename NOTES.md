# Learning Nextjs

### Folder structure

![folder structure](Images/learn-folder-structure.avif)

`/app`: Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.

`/app/lib`: Contains functions used in your application, such as reusable utility functions and data fetching functions.
`/app/ui`: Contains all the UI components for your application, such as cards, tables, and forms.
`/public`: Contains all the static assets for your application, such as images.

# images optimization

[read more here](https://nextjs.org/learn/dashboard-app/optimizing-fonts-images)

# Creating Layouts and Pages

# Fetching Data

## choosing how to fetch data

### API LAYER

- APIs are an intermediary layer between your application code and database.

## Using Server Components to fetch data

- By default, Next.js applications use React Server Components. Fetching data with Server Components is a relatively new approach and there are a few benefits of using them:
  - Server Components support promises, providing a simpler solution for asynchronous tasks like data fetching. You can use async/await syntax without reaching out for useEffect, useState or data fetching libraries.
  - Server Components execute on the server, so you can keep expensive data fetches and logic on the server and only send the result to the client.
  - As mentioned before, since Server Components execute on the server, you can query the database directly without an additional API layer.

# Static and Dynamic Rendering
