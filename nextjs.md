# https://nextjs.org/docs llms-full.txt

## Next.js Documentation

Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

# Introduction

Welcome to the Next.js documentation!

## [What is Next.js?](https://nextjs.org/docs\#what-is-nextjs)

Next.js is a React framework for building full-stack web applications. You use React Components to build user interfaces, and Next.js for additional features and optimizations.

Under the hood, Next.js also abstracts and automatically configures tooling needed for React, like bundling, compiling, and more. This allows you to focus on building your application instead of spending time with configuration.

Whether you're an individual developer or part of a larger team, Next.js can help you build interactive, dynamic, and fast React applications.

## [Main Features](https://nextjs.org/docs\#main-features)

Some of the main Next.js features include:

| Feature | Description |
| --- | --- |
| [Routing](https://nextjs.org/docs/app/building-your-application/routing) | A file-system based router built on top of Server Components that supports layouts, nested routing, loading states, error handling, and more. |
| [Rendering](https://nextjs.org/docs/app/building-your-application/rendering) | Client-side and Server-side Rendering with Client and Server Components. Further optimized with Static and Dynamic Rendering on the server with Next.js. Streaming on Edge and Node.js runtimes. |
| [Data Fetching](https://nextjs.org/docs/app/building-your-application/data-fetching) | Simplified data fetching with async/await in Server Components, and an extended `fetch` API for request memoization, data caching and revalidation. |
| [Styling](https://nextjs.org/docs/app/building-your-application/styling) | Support for your preferred styling methods, including CSS Modules, Tailwind CSS, and CSS-in-JS |
| [Optimizations](https://nextjs.org/docs/app/building-your-application/optimizing) | Image, Fonts, and Script Optimizations to improve your application's Core Web Vitals and User Experience. |
| [TypeScript](https://nextjs.org/docs/app/api-reference/config/typescript) | Improved support for TypeScript, with better type checking and more efficient compilation, as well as custom TypeScript Plugin and type checker. |

## [How to Use These Docs](https://nextjs.org/docs\#how-to-use-these-docs)

On the left side of the screen, you'll find the docs navbar. The pages of the docs are organized sequentially, from basic to advanced, so you can follow them step-by-step when building your application. However, you can read them in any order or skip to the pages that apply to your use case.

On the right side of the screen, you'll see a table of contents that makes it easier to navigate between sections of a page. If you need to quickly find a page, you can use the search bar at the top, or the search shortcut ( `Ctrl+K` or `Cmd+K`).

To get started, check out the [Installation](https://nextjs.org/docs/app/getting-started/installation) guide.

## [App Router vs Pages Router](https://nextjs.org/docs\#app-router-vs-pages-router)

Next.js has two different routers: the App Router and the Pages Router. The App Router is a newer router that allows you to use React's latest features, such as Server Components and Streaming. The Pages Router is the original Next.js router, which allowed you to build server-rendered React applications and continues to be supported for older Next.js applications.

At the top of the sidebar, you'll notice a dropdown menu that allows you to switch between the **App Router** and the **Pages Router** features. Since there are features that are unique to each directory, it's important to keep track of which tab is selected.

The breadcrumbs at the top of the page will also indicate whether you're viewing App Router docs or Pages Router docs.

## [Pre-Requisite Knowledge](https://nextjs.org/docs\#pre-requisite-knowledge)

Although our docs are designed to be beginner-friendly, we need to establish a baseline so that the docs can stay focused on Next.js functionality. We'll make sure to provide links to relevant documentation whenever we introduce a new concept.

To get the most out of our docs, it's recommended that you have a basic understanding of HTML, CSS, and React. If you need to brush up on your React skills, check out our [React Foundations Course](https://nextjs.org/learn/react-foundations), which will introduce you to the fundamentals. Then, learn more about Next.js by [building a dashboard application](https://nextjs.org/learn/dashboard-app).

## [Accessibility](https://nextjs.org/docs\#accessibility)

For optimal accessibility when using a screen reader while reading the docs, we recommend using Firefox and NVDA, or Safari and VoiceOver.

## [Join our Community](https://nextjs.org/docs\#join-our-community)

If you have questions about anything related to Next.js, you're always welcome to ask our community on [GitHub Discussions](https://github.com/vercel/next.js/discussions), [Discord](https://discord.com/invite/bUG2bvbtHy), [X (Twitter)](https://x.com/nextjs), and [Reddit](https://www.reddit.com/r/nextjs).

[**Getting Started** \\
Learn how to create full-stack web applications with the Next.js App Router.](https://nextjs.org/docs/app/getting-started) [**Examples** \\
Learn how to implement common UI patterns and use cases using Next.js](https://nextjs.org/docs/app/examples) [**Building Your Application** \\
Learn how to use Next.js features to build your application.](https://nextjs.org/docs/app/building-your-application) [**API Reference** \\
Next.js API Reference for the App Router.](https://nextjs.org/docs/app/api-reference) [**Getting Started** \\
Learn how to create full-stack web applications with Next.js with the Pages Router.](https://nextjs.org/docs/pages/getting-started) [**Building Your Application** \\
Learn how to use Next.js features to build your application.](https://nextjs.org/docs/pages/building-your-application) [**API Reference** \\
Next.js API Reference for the Pages Router.](https://nextjs.org/docs/pages/api-reference) [**Architecture** \\
How Next.js Works](https://nextjs.org/docs/architecture) [**Community** \\
Get involved in the Next.js community.](https://nextjs.org/docs/community)

Was this helpful?

supported.

Send

## Next.js Installation Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Getting Started](https://nextjs.org/docs/app/getting-started) Installation

# How to set up a new Next.js project

## [System requirements](https://nextjs.org/docs/app/getting-started/installation\#system-requirements)

- [Node.js 18.18](https://nodejs.org/) or later.
- macOS, Windows (including WSL), and Linux are supported.

## [Automatic installation](https://nextjs.org/docs/app/getting-started/installation\#automatic-installation)

We recommend starting a new Next.js app using [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app), which sets up everything automatically for you. To create a project, run:

Terminal

```code-block_code__isn_V
npx create-next-app@latest
```

On installation, you'll see the following prompts:

Terminal

```code-block_code__isn_V
What is your project named? my-app
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like your code inside a `src/` directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to use Turbopack for `next dev`?  No / Yes
Would you like to customize the import alias (`@/*` by default)? No / Yes
What import alias would you like configured? @/*
```

After the prompts, [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app) will create a folder with your project name and install the required dependencies.

## [Manual installation](https://nextjs.org/docs/app/getting-started/installation\#manual-installation)

To manually create a new Next.js app, install the required packages:

Terminal

```code-block_code__isn_V
npm install next@latest react@latest react-dom@latest
```

Open your `package.json` file and add the following `scripts`:

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  }
}
```

These scripts refer to the different stages of developing an application:

- `dev`: runs [`next dev`](https://nextjs.org/docs/app/api-reference/cli/next#next-dev-options) to start Next.js in development mode.
- `build`: runs [`next build`](https://nextjs.org/docs/app/api-reference/cli/next#next-build-options) to build the application for production usage.
- `start`: runs [`next start`](https://nextjs.org/docs/app/api-reference/cli/next#next-start-options) to start a Next.js production server.
- `lint`: runs [`next lint`](https://nextjs.org/docs/app/api-reference/cli/next#next-lint-options) to set up Next.js' built-in ESLint configuration.

### [Create the `app` directory](https://nextjs.org/docs/app/getting-started/installation\#create-the-app-directory)

Next.js uses file-system routing, which means the routes in your application are determined by how you structure your files.

Create an `app` folder, then add a `layout.tsx` and `page.tsx` file. These will be rendered when the user visits the root of your application ( `/`).

![App Folder Structure](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fapp-getting-started.png&w=3840&q=75)![App Folder Structure](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fapp-getting-started.png&w=3840&q=75)

Create a [root layout](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#root-layout-required) inside `app/layout.tsx` with the required `<html>` and `<body>` tags:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body>{children}</body>
    </html>
  )
}
```

Finally, create a home page `app/page.tsx` with some initial content:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Page() {
  return <h1>Hello, Next.js!</h1>
}
```

> **Good to know**:
>
> - If you forget to create `layout.tsx`, Next.js will automatically create this file when running the development server with `next dev`.
> - You can optionally use a [`src` directory](https://nextjs.org/docs/app/building-your-application/configuring/src-directory) in the root of your project to separate your application's code from configuration files.

### [Create the `public` folder (optional)](https://nextjs.org/docs/app/getting-started/installation\#create-the-public-folder-optional)

You can optionally create a [`public` folder](https://nextjs.org/docs/app/building-your-application/optimizing/static-assets) at the root of your project to store static assets such as images, fonts, etc. Files inside `public` can then be referenced by your code starting from the base URL ( `/`).

## [Run the development server](https://nextjs.org/docs/app/getting-started/installation\#run-the-development-server)

1. Run `npm run dev` to start the development server.
2. Visit `http://localhost:3000` to view your application.
3. Edit the `app/page.tsx` file and save it to see the updated result in your browser.

## [Set up TypeScript](https://nextjs.org/docs/app/getting-started/installation\#set-up-typescript)

> Minimum TypeScript version: `v4.5.2`

Next.js comes with built-in TypeScript support. To add TypeScript to your project, rename a file to `.ts` / `.tsx`. Run `next dev`, Next.js will automatically install the necessary dependencies and add a `tsconfig.json` file with the recommended config options.

### [IDE Plugin](https://nextjs.org/docs/app/getting-started/installation\#ide-plugin)

Next.js includes a custom TypeScript plugin and type checker, which VSCode and other code editors can use for advanced type-checking and auto-completion.

You can enable the plugin in VS Code by:

1. Opening the command palette ( `Ctrl/⌘` \+ `Shift` \+ `P`)
2. Searching for "TypeScript: Select TypeScript Version"
3. Selecting "Use Workspace Version"

![TypeScript Command Palette](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Ftypescript-command-palette.png&w=3840&q=75)![TypeScript Command Palette](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Ftypescript-command-palette.png&w=3840&q=75)

Now, when editing files, the custom plugin will be enabled. When running `next build`, the custom type checker will be used.

See the [TypeScript configuration](https://nextjs.org/docs/app/api-reference/config/next-config-js/typescript) page for more information on how to use TypeScript in your project.

## [Set up ESLint](https://nextjs.org/docs/app/getting-started/installation\#set-up-eslint)

Next.js comes with built-in ESLint, automatically installing the necessary packages and configuring the proper settings when you create a new project with `create-next-app`.

To add ESLint to an existing project, add `next lint` as a script to `package.json`:

package.json

```code-block_code__isn_V
{
  "scripts": {
    "lint": "next lint"
  }
}
```

Then, run `npm run lint` and you will be guided through the installation and configuration process.

Terminal

```code-block_code__isn_V
npm run lint
```

You'll see a prompt like this:

> ? How would you like to configure ESLint?
>
> ❯ Strict (recommended)
>
> Base
>
> Cancel

- **Strict**: Includes Next.js' base ESLint configuration along with a stricter Core Web Vitals rule-set. This is the recommended configuration for developers setting up ESLint for the first time.
- **Base**: Includes Next.js' base ESLint configuration.
- **Cancel**: Does not include any ESLint configuration. Only select this option if you plan on setting up your own custom ESLint configuration.

If either of the two configuration options are selected, Next.js will automatically install `eslint` and `eslint-config-next` as dependencies in your application and create an `.eslintrc.json` file in the root of your project that includes your selected configuration.

You can now run `next lint` every time you want to run ESLint to catch errors. Once ESLint has been set up, it will also automatically run during every build ( `next build`). Errors will fail the build, while warnings will not.

See the [ESLint Plugin](https://nextjs.org/docs/app/api-reference/config/next-config-js/eslint) page for more information on how to configure ESLint in your project.

## [Set up Absolute Imports and Module Path Aliases](https://nextjs.org/docs/app/getting-started/installation\#set-up-absolute-imports-and-module-path-aliases)

Next.js has in-built support for the `"paths"` and `"baseUrl"` options of `tsconfig.json` and `jsconfig.json` files. These options allow you to alias project directories to absolute paths, making it easier to import modules. For example:

```code-block_code__isn_V
// Before
import { Button } from '../../../components/button'

// After
import { Button } from '@/components/button'
```

To configure absolute imports, add the `baseUrl` configuration option to your `tsconfig.json` or `jsconfig.json` file. For example:

tsconfig.json or jsconfig.json

```code-block_code__isn_V
{
  "compilerOptions": {
    "baseUrl": "src/"
  }
}
```

In addition to configuring the `baseUrl` path, you can use the `"paths"` option to `"alias"` module paths.

For example, the following configuration maps `@/components/*` to `components/*`:

tsconfig.json or jsconfig.json

```code-block_code__isn_V
{
  "compilerOptions": {
    "baseUrl": "src/",
    "paths": {
      "@/styles/*": ["styles/*"],
      "@/components/*": ["components/*"]
    }
  }
}
```

Each of the `"paths"` are relative to the `baseUrl` location. For example:

src/app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Button from '@/components/button'
import '@/styles/styles.css'

export default function HomePage() {
  return (
    <div>
      <h1>Hello World</h1>
      <Button />
    </div>
  )
}
```

Was this helpful?

supported.

Send

## Next.js Getting Started
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Introduction](https://nextjs.org/docs) [App Router](https://nextjs.org/docs/app) Getting Started

# Getting Started

[**Installation** \\
Create a new Next.js application with the \`create-next-app\` CLI, and set up TypeScript, ESLint, and Module Path Aliases.](https://nextjs.org/docs/app/getting-started/installation) [**Project Structure** \\
An overview of the folder and file conventions in Next.js, and how to organize your project.](https://nextjs.org/docs/app/getting-started/project-structure) [**Layouts and Pages** \\
Create your first pages and layouts, and link between them.](https://nextjs.org/docs/app/getting-started/layouts-and-pages) [**Images and Fonts** \\
Learn how to optimize images and fonts.](https://nextjs.org/docs/app/getting-started/images-and-fonts) [**CSS** \\
Learn about the different ways to add CSS to your application, including CSS Modules, Global CSS, Tailwind CSS, and more.](https://nextjs.org/docs/app/getting-started/css) [**Fetching Data** \\
Start fetching data and streaming content in your application.](https://nextjs.org/docs/app/getting-started/fetching-data) [**Updating Data** \\
Learn how to update data in your Next.js application.](https://nextjs.org/docs/app/getting-started/updating-data) [**Error Handling** \\
Learn how to display expected errors and handle uncaught exceptions.](https://nextjs.org/docs/app/getting-started/error-handling)

Was this helpful?

supported.

Send

## Next.js App Router Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Introduction](https://nextjs.org/docs) App Router

# App Router

The Next.js App Router introduces a new model for building applications using React's latest features such as [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components), [Streaming with Suspense](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming#streaming-with-suspense), and [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations).

Get started with the App Router by [creating your first page](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates).

## [Frequently Asked Questions](https://nextjs.org/docs/app\#frequently-asked-questions)

### [How can I access the request object in a layout?](https://nextjs.org/docs/app\#how-can-i-access-the-request-object-in-a-layout)

You intentionally cannot access the raw request object. However, you can access [`headers`](https://nextjs.org/docs/app/api-reference/functions/headers) and [`cookies`](https://nextjs.org/docs/app/api-reference/functions/cookies) through server-only functions. You can also [set cookies](https://nextjs.org/docs/app#how-can-i-set-cookies).

[Layouts](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#layouts) do not rerender. They can be cached and reused to avoid unnecessary computation when navigating between pages. By restricting layouts from accessing the raw request, Next.js can prevent the execution of potentially slow or expensive user code within the layout, which could negatively impact performance.

This design also enforces consistent and predictable behavior for layouts across different pages, which simplifies development and debugging.

Depending on the UI pattern you're building, [Parallel Routes](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes) allow you to render multiple pages in the same layout, and pages have access to the route segments as well as the URL search params.

### [How can I access the URL on a page?](https://nextjs.org/docs/app\#how-can-i-access-the-url-on-a-page)

By default, pages are Server Components. You can access the route segments through the [`params`](https://nextjs.org/docs/app/api-reference/file-conventions/page#params-optional) prop and the URL search params through the [`searchParams`](https://nextjs.org/docs/app/api-reference/file-conventions/page#searchparams-optional) prop for a given page.

If you are using Client Components, you can use [`usePathname`](https://nextjs.org/docs/app/api-reference/functions/use-pathname), [`useSelectedLayoutSegment`](https://nextjs.org/docs/app/api-reference/functions/use-selected-layout-segment), and [`useSelectedLayoutSegments`](https://nextjs.org/docs/app/api-reference/functions/use-selected-layout-segments) for more complex routes.

Further, depending on the UI pattern you're building, [Parallel Routes](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes) allow you to render multiple pages in the same layout, and pages have access to the route segments as well as the URL search params.

### [How can I redirect from a Server Component?](https://nextjs.org/docs/app\#how-can-i-redirect-from-a-server-component)

You can use [`redirect`](https://nextjs.org/docs/app/api-reference/functions/redirect) to redirect from a page to a relative or absolute URL. [`redirect`](https://nextjs.org/docs/app/api-reference/functions/redirect) is a temporary (307) redirect, while [`permanentRedirect`](https://nextjs.org/docs/app/api-reference/functions/permanentRedirect) is a permanent (308) redirect. When these functions are used while streaming UI, they will insert a meta tag to emit the redirect on the client side.

### [How can I handle authentication with the App Router?](https://nextjs.org/docs/app\#how-can-i-handle-authentication-with-the-app-router)

Here are some common authentication solutions that support the App Router:

- [NextAuth.js](https://authjs.dev/getting-started/installation?framework=next.js)
- [Clerk](https://clerk.com/docs/quickstarts/nextjs)
- [Stack Auth](https://docs.stack-auth.com/getting-started/setup)
- [Auth0](https://github.com/auth0/nextjs-auth0#app-router)
- [Stytch](https://stytch.com/docs/sdks/resources/nextjs)
- [Kinde](https://docs.kinde.com/developer-tools/sdks/backend/nextjs-sdk/)
- [WorkOS](https://workos.com/docs/user-management/nextjs)
- Or manually handling sessions or JWTs

### [How can I set cookies?](https://nextjs.org/docs/app\#how-can-i-set-cookies)

You can set cookies in [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#cookies) or [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) using the [`cookies`](https://nextjs.org/docs/app/api-reference/functions/cookies) function.

Since HTTP does not allow setting cookies after streaming starts, you cannot set cookies from a page or layout directly. You can also set cookies from [Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware#using-cookies).

### [How can I build multi-tenant apps?](https://nextjs.org/docs/app\#how-can-i-build-multi-tenant-apps)

If you are looking to build a single Next.js application that serves multiple tenants, we have [built an example](https://vercel.com/templates/next.js/platforms-starter-kit) showing our recommended architecture.

### [How can I invalidate the App Router cache?](https://nextjs.org/docs/app\#how-can-i-invalidate-the-app-router-cache)

There are multiple layers of caching in Next.js, and thus, multiple ways to invalidate different parts of the cache. [Learn more about caching](https://nextjs.org/docs/app/building-your-application/caching).

### [Are there any comprehensive, open-source applications built on the App Router?](https://nextjs.org/docs/app\#are-there-any-comprehensive-open-source-applications-built-on-the-app-router)

Yes. You can view [Next.js Commerce](https://vercel.com/templates/next.js/nextjs-commerce) or the [Platforms Starter Kit](https://vercel.com/templates/next.js/platforms-starter-kit) for two larger examples of using the App Router that are open-source.

## [Learn More](https://nextjs.org/docs/app\#learn-more)

- [Routing Fundamentals](https://nextjs.org/docs/app/building-your-application/routing)
- [Data Fetching and Caching](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching)
- [Incremental Static Regeneration](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration)
- [Forms and Mutations](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations)
- [Caching](https://nextjs.org/docs/app/building-your-application/caching)
- [Rendering Fundamentals](https://nextjs.org/docs/app/building-your-application/rendering)
- [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components)
- [Client Components](https://nextjs.org/docs/app/building-your-application/rendering/client-components)

[**Getting Started** \\
Learn how to create full-stack web applications with the Next.js App Router.](https://nextjs.org/docs/app/getting-started) [**Examples** \\
Learn how to implement common UI patterns and use cases using Next.js](https://nextjs.org/docs/app/examples) [**Building Your Application** \\
Learn how to use Next.js features to build your application.](https://nextjs.org/docs/app/building-your-application) [**API Reference** \\
Next.js API Reference for the App Router.](https://nextjs.org/docs/app/api-reference)

Was this helpful?

supported.

Send

## Next.js Pages Router
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Introduction](https://nextjs.org/docs) Pages Router

# Pages Router

Before Next.js 13, the Pages Router was the main way to create routes in Next.js. It used an intuitive file-system router to map each file to a route. The Pages Router is still supported in newer versions of Next.js, but we recommend migrating to the new [App Router](https://nextjs.org/docs/app) to leverage React's latest features.

Use this section of the documentation for existing applications that use the Pages Router.

[**Getting Started** \\
Learn how to create full-stack web applications with Next.js with the Pages Router.](https://nextjs.org/docs/pages/getting-started) [**Building Your Application** \\
Learn how to use Next.js features to build your application.](https://nextjs.org/docs/pages/building-your-application) [**API Reference** \\
Next.js API Reference for the Pages Router.](https://nextjs.org/docs/pages/api-reference)

Was this helpful?

supported.

Send

## Next.js Routing Guide
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[Pages Router](https://nextjs.org/docs/pages) [Building Your Application](https://nextjs.org/docs/pages/building-your-application) Routing

# Routing

The Pages Router has a file-system based router built on concepts of pages. When a file is added to the `pages` directory it's automatically available as a route. Learn more about routing in the Pages Router:

[**Pages and Layouts** \\
Create your first page and shared layout with the Pages Router.](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts) [**Dynamic Routes** \\
Dynamic Routes are pages that allow you to add custom params to your URLs. Start creating Dynamic Routes and learn more here.](https://nextjs.org/docs/pages/building-your-application/routing/dynamic-routes) [**Linking and Navigating** \\
Learn how navigation works in Next.js, and how to use the Link Component and \`useRouter\` hook.](https://nextjs.org/docs/pages/building-your-application/routing/linking-and-navigating) [**Redirecting** \\
Learn the different ways to handle redirects in Next.js.](https://nextjs.org/docs/pages/building-your-application/routing/redirecting) [**Custom App** \\
Control page initialization and add a layout that persists for all pages by overriding the default App component used by Next.js.](https://nextjs.org/docs/pages/building-your-application/routing/custom-app) [**Custom Document** \\
Extend the default document markup added by Next.js.](https://nextjs.org/docs/pages/building-your-application/routing/custom-document) [**API Routes** \\
Next.js supports API Routes, which allow you to build your API without leaving your Next.js app. Learn how it works here.](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) [**Custom Errors** \\
Override and extend the built-in Error page to handle custom errors.](https://nextjs.org/docs/pages/building-your-application/routing/custom-error) [**Internationalization** \\
Next.js has built-in support for internationalized routing and language detection. Learn more here.](https://nextjs.org/docs/pages/building-your-application/routing/internationalization) [**Middleware** \\
Learn how to use Middleware to run code before a request is completed.](https://nextjs.org/docs/pages/building-your-application/routing/middleware)

Was this helpful?

supported.

Send

## Next.js Deployment Guide
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[Pages Router](https://nextjs.org/docs/pages) [Building Your Application](https://nextjs.org/docs/pages/building-your-application) Deploying

# Deploying

Congratulations, it's time to ship to production.

You can deploy [managed Next.js with Vercel](https://nextjs.org/docs/pages/building-your-application/deploying#managed-nextjs-with-vercel), or self-host on a Node.js server, Docker image, or even static HTML files. When deploying using `next start`, all Next.js features are supported.

## [Production Builds](https://nextjs.org/docs/pages/building-your-application/deploying\#production-builds)

Running `next build` generates an optimized version of your application for production. HTML, CSS, and JavaScript files are created based on your pages. JavaScript is **compiled** and browser bundles are **minified** using the [Next.js Compiler](https://nextjs.org/docs/architecture/nextjs-compiler) to help achieve the best performance and support [all modern browsers](https://nextjs.org/docs/architecture/supported-browsers).

Next.js produces a standard deployment output used by managed and self-hosted Next.js. This ensures all features are supported across both methods of deployment. In the next major version, we will be transforming this output into our [Build Output API specification](https://vercel.com/docs/build-output-api/v3?utm_source=next-site&utm_medium=docs&utm_campaign=next-website).

## [Managed Next.js with Vercel](https://nextjs.org/docs/pages/building-your-application/deploying\#managed-nextjs-with-vercel)

[Vercel](https://vercel.com/docs/frameworks/nextjs?utm_source=next-site&utm_medium=docs&utm_campaign=next-website), the creators and maintainers of Next.js, provide managed infrastructure and a developer experience platform for your Next.js applications.

Deploying to Vercel is zero-configuration and provides additional enhancements for scalability, availability, and performance globally. However, all Next.js features are still supported when self-hosted.

Learn more about [Next.js on Vercel](https://vercel.com/docs/frameworks/nextjs?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) or [deploy a template for free](https://vercel.com/templates/next.js?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) to try it out.

## [Self-Hosting](https://nextjs.org/docs/pages/building-your-application/deploying\#self-hosting)

You can self-host Next.js in three different ways:

- [A Node.js server](https://nextjs.org/docs/pages/building-your-application/deploying#nodejs-server)
- [A Docker container](https://nextjs.org/docs/pages/building-your-application/deploying#docker-image)
- [A static export](https://nextjs.org/docs/pages/building-your-application/deploying#static-html-export)

> **🎥 Watch:** Learn more about self-hosting Next.js → [YouTube (45 minutes)](https://www.youtube.com/watch?v=sIVL4JMqRfc).

We have community maintained deployment examples with the following providers:

- [Deno](https://github.com/nextjs/deploy-deno)
- [DigitalOcean](https://github.com/nextjs/deploy-digitalocean)
- [Flightcontrol](https://github.com/nextjs/deploy-flightcontrol)
- [Fly.io](https://github.com/nextjs/deploy-fly)
- [GitHub Pages](https://github.com/nextjs/deploy-github-pages)
- [Google Cloud Run](https://github.com/nextjs/deploy-google-cloud-run)
- [Railway](https://github.com/nextjs/deploy-railway)
- [Render](https://github.com/nextjs/deploy-render)
- [SST](https://github.com/nextjs/deploy-sst)

### [Node.js Server](https://nextjs.org/docs/pages/building-your-application/deploying\#nodejs-server)

Next.js can be deployed to any hosting provider that supports Node.js. Ensure your `package.json` has the `"build"` and `"start"` scripts:

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  }
}
```

Then, run `npm run build` to build your application. Finally, run `npm run start` to start the Node.js server. This server supports all Next.js features.

### [Docker Image](https://nextjs.org/docs/pages/building-your-application/deploying\#docker-image)

Next.js can be deployed to any hosting provider that supports [Docker](https://www.docker.com/) containers. You can use this approach when deploying to container orchestrators such as [Kubernetes](https://kubernetes.io/) or when running inside a container in any cloud provider.

1. [Install Docker](https://docs.docker.com/get-docker/) on your machine
2. [Clone our example](https://github.com/vercel/next.js/tree/canary/examples/with-docker) (or the [multi-environment example](https://github.com/vercel/next.js/tree/canary/examples/with-docker-multi-env))
3. Build your container: `docker build -t nextjs-docker .`
4. Run your container: `docker run -p 3000:3000 nextjs-docker`

Next.js through Docker supports all Next.js features.

### [Static HTML Export](https://nextjs.org/docs/pages/building-your-application/deploying\#static-html-export)

Next.js enables starting as a static site or Single-Page Application (SPA), then later optionally upgrading to use features that require a server.

Since Next.js supports this [static export](https://nextjs.org/docs/app/building-your-application/deploying/static-exports), it can be deployed and hosted on any web server that can serve HTML/CSS/JS static assets. This includes tools like AWS S3, Nginx, or Apache.

Running as a [static export](https://nextjs.org/docs/app/building-your-application/deploying/static-exports) does not support Next.js features that require a server. [Learn more](https://nextjs.org/docs/app/building-your-application/deploying/static-exports#unsupported-features).

> **Good to know:**
>
> - [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components) are supported with static exports.

## [Features](https://nextjs.org/docs/pages/building-your-application/deploying\#features)

### [Image Optimization](https://nextjs.org/docs/pages/building-your-application/deploying\#image-optimization)

[Image Optimization](https://nextjs.org/docs/app/building-your-application/optimizing/images) through `next/image` works self-hosted with zero configuration when deploying using `next start`. If you would prefer to have a separate service to optimize images, you can [configure an image loader](https://nextjs.org/docs/app/building-your-application/optimizing/images#loaders).

Image Optimization can be used with a [static export](https://nextjs.org/docs/app/building-your-application/deploying/static-exports#image-optimization) by defining a custom image loader in `next.config.js`. Note that images are optimized at runtime, not during the build.

> **Good to know:**
>
> - On glibc-based Linux systems, Image Optimization may require [additional configuration](https://sharp.pixelplumbing.com/install#linux-memory-allocator) to prevent excessive memory usage.
> - Learn more about the [caching behavior of optimized images](https://nextjs.org/docs/app/api-reference/components/image#caching-behavior) and how to configure the TTL.
> - You can also [disable Image Optimization](https://nextjs.org/docs/app/api-reference/components/image#unoptimized) and still retain other benefits of using `next/image` if you prefer. For example, if you are optimizing images yourself separately.

### [Middleware](https://nextjs.org/docs/pages/building-your-application/deploying\#middleware)

[Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware) works self-hosted with zero configuration when deploying using `next start`. Since it requires access to the incoming request, it is not supported when using a [static export](https://nextjs.org/docs/app/building-your-application/deploying/static-exports).

Middleware uses a [runtime](https://nextjs.org/docs/app/building-your-application/rendering/edge-and-nodejs-runtimes) that is a subset of all available Node.js APIs to help ensure low latency, since it may run in front of every route or asset in your application. This runtime does not require running “at the edge” and works in a single-region server. Additional configuration and infrastructure are required to run Middleware in multiple regions.

If you are looking to add logic (or use an external package) that requires all Node.js APIs, you might be able to move this logic to a [layout](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#layouts) as a [Server Component](https://nextjs.org/docs/app/building-your-application/rendering/server-components). For example, checking [headers](https://nextjs.org/docs/app/api-reference/functions/headers) and [redirecting](https://nextjs.org/docs/app/api-reference/functions/redirect). You can also use headers, cookies, or query parameters to [redirect](https://nextjs.org/docs/app/api-reference/config/next-config-js/redirects#header-cookie-and-query-matching) or [rewrite](https://nextjs.org/docs/app/api-reference/config/next-config-js/rewrites#header-cookie-and-query-matching) through `next.config.js`. If that does not work, you can also use a [custom server](https://nextjs.org/docs/pages/building-your-application/configuring/custom-server).

### [Environment Variables](https://nextjs.org/docs/pages/building-your-application/deploying\#environment-variables)

Next.js can support both build time and runtime environment variables.

**By default, environment variables are only available on the server**. To expose an environment variable to the browser, it must be prefixed with `NEXT_PUBLIC_`. However, these public environment variables will be inlined into the JavaScript bundle during `next build`.

To read runtime environment variables, we recommend using `getServerSideProps` or [incrementally adopting the App Router](https://nextjs.org/docs/app/building-your-application/upgrading/app-router-migration).

This allows you to use a singular Docker image that can be promoted through multiple environments with different values.

> **Good to know:**
>
> - You can run code on server startup using the [`register` function](https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation).
> - We do not recommend using the [runtimeConfig](https://nextjs.org/docs/pages/api-reference/config/next-config-js/runtime-configuration) option, as this does not work with the standalone output mode. Instead, we recommend [incrementally adopting](https://nextjs.org/docs/app/building-your-application/upgrading/app-router-migration) the App Router.

### [Caching and ISR](https://nextjs.org/docs/pages/building-your-application/deploying\#caching-and-isr)

Next.js can cache responses, generated static pages, build outputs, and other static assets like images, fonts, and scripts.

Caching and revalidating pages (with [Incremental Static Regeneration](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration)) use the **same shared cache**. By default, this cache is stored to the filesystem (on disk) on your Next.js server. **This works automatically when self-hosting** using both the Pages and App Router.

You can configure the Next.js cache location if you want to persist cached pages and data to durable storage, or share the cache across multiple containers or instances of your Next.js application.

#### [Automatic Caching](https://nextjs.org/docs/pages/building-your-application/deploying\#automatic-caching)

- Next.js sets the `Cache-Control` header of `public, max-age=31536000, immutable` to truly immutable assets. It cannot be overridden. These immutable files contain a SHA-hash in the file name, so they can be safely cached indefinitely. For example, [Static Image Imports](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images). You can [configure the TTL](https://nextjs.org/docs/app/api-reference/components/image#caching-behavior) for images.
- Incremental Static Regeneration (ISR) sets the `Cache-Control` header of `s-maxage: <revalidate in getStaticProps>, stale-while-revalidate`. This revalidation time is defined in your [`getStaticProps` function](https://nextjs.org/docs/pages/building-your-application/data-fetching/get-static-props) in seconds. If you set `revalidate: false`, it will default to a one-year cache duration.
- Dynamically rendered pages set a `Cache-Control` header of `private, no-cache, no-store, max-age=0, must-revalidate` to prevent user-specific data from being cached. This applies to both the App Router and Pages Router. This also includes [Draft Mode](https://nextjs.org/docs/app/building-your-application/configuring/draft-mode).

#### [Static Assets](https://nextjs.org/docs/pages/building-your-application/deploying\#static-assets)

If you want to host static assets on a different domain or CDN, you can use the `assetPrefix` [configuration](https://nextjs.org/docs/app/api-reference/config/next-config-js/assetPrefix) in `next.config.js`. Next.js will use this asset prefix when retrieving JavaScript or CSS files. Separating your assets to a different domain does come with the downside of extra time spent on DNS and TLS resolution.

[Learn more about `assetPrefix`](https://nextjs.org/docs/app/api-reference/config/next-config-js/assetPrefix).

#### [Configuring Caching](https://nextjs.org/docs/pages/building-your-application/deploying\#configuring-caching)

By default, generated cache assets will be stored in memory (defaults to 50mb) and on disk. If you are hosting Next.js using a container orchestration platform like Kubernetes, each pod will have a copy of the cache. To prevent stale data from being shown since the cache is not shared between pods by default, you can configure the Next.js cache to provide a cache handler and disable in-memory caching.

To configure the ISR/Data Cache location when self-hosting, you can configure a custom handler in your `next.config.js` file:

next.config.js

```code-block_code__isn_V
module.exports = {
  cacheHandler: require.resolve('./cache-handler.js'),
  cacheMaxMemorySize: 0, // disable default in-memory caching
}
```

Then, create `cache-handler.js` in the root of your project, for example:

cache-handler.js

```code-block_code__isn_V
const cache = new Map()

module.exports = class CacheHandler {
  constructor(options) {
    this.options = options
  }

  async get(key) {
    // This could be stored anywhere, like durable storage
    return cache.get(key)
  }

  async set(key, data, ctx) {
    // This could be stored anywhere, like durable storage
    cache.set(key, {
      value: data,
      lastModified: Date.now(),
      tags: ctx.tags,
    })
  }

  async revalidateTag(tags) {
    // tags is either a string or an array of strings
    tags = [tags].flat()
    // Iterate over all entries in the cache
    for (let [key, value] of cache) {
      // If the value's tags include the specified tag, delete this entry
      if (value.tags.some((tag) => tags.includes(tag))) {
        cache.delete(key)
      }
    }
  }

  // If you want to have temporary in memory cache for a single request that is reset
  // before the next request you can leverage this method
  resetRequestCache() {}
}
```

Using a custom cache handler will allow you to ensure consistency across all pods hosting your Next.js application. For instance, you can save the cached values anywhere, like [Redis](https://github.com/vercel/next.js/tree/canary/examples/cache-handler-redis) or AWS S3.

> **Good to know:**
>
> - `revalidatePath` is a convenience layer on top of cache tags. Calling `revalidatePath` will call the `revalidateTag` function with a special default tag for the provided page.

### [Build Cache](https://nextjs.org/docs/pages/building-your-application/deploying\#build-cache)

Next.js generates an ID during `next build` to identify which version of your application is being served. The same build should be used and boot up multiple containers.

If you are rebuilding for each stage of your environment, you will need to generate a consistent build ID to use between containers. Use the `generateBuildId` command in `next.config.js`:

next.config.js

```code-block_code__isn_V
module.exports = {
  generateBuildId: async () => {
    // This could be anything, using the latest git hash
    return process.env.GIT_HASH
  },
}
```

### [Version Skew](https://nextjs.org/docs/pages/building-your-application/deploying\#version-skew)

Next.js will automatically mitigate most instances of [version skew](https://www.industrialempathy.com/posts/version-skew/) and automatically reload the application to retrieve new assets when detected. For example, if there is a mismatch in the `deploymentId`, transitions between pages will perform a hard navigation versus using a prefetched value.

When the application is reloaded, there may be a loss of application state if it's not designed to persist between page navigations. For example, using URL state or local storage would persist state after a page refresh. However, component state like `useState` would be lost in such navigations.

Vercel provides additional [skew protection](https://vercel.com/docs/deployments/skew-protection?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) for Next.js applications to ensure assets and functions from the previous version are still available to older clients, even after the new version is deployed.

You can manually configure the `deploymentId` property in your `next.config.js` file to ensure each request uses either `?dpl` query string or `x-deployment-id` header.

## [Manual Graceful Shutdowns](https://nextjs.org/docs/pages/building-your-application/deploying\#manual-graceful-shutdowns)

When self-hosting, you might want to run code when the server shuts down on `SIGTERM` or `SIGINT` signals.

You can set the env variable `NEXT_MANUAL_SIG_HANDLE` to `true` and then register a handler for that signal inside your `_document.js` file. You will need to register the environment variable directly in the `package.json` script, and not in the `.env` file.

> **Good to know**: Manual signal handling is not available in `next dev`.

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "NEXT_MANUAL_SIG_HANDLE=true next start"
  }
}
```

pages/\_document.js

```code-block_code__isn_V
if (process.env.NEXT_MANUAL_SIG_HANDLE) {
  process.on('SIGTERM', () => {
    console.log('Received SIGTERM: cleaning up')
    process.exit(0)
  })
  process.on('SIGINT', () => {
    console.log('Received SIGINT: cleaning up')
    process.exit(0)
  })
}
```

[**Production Checklist** \\
Recommendations to ensure the best performance and user experience before taking your Next.js application to production.](https://nextjs.org/docs/pages/building-your-application/deploying/production-checklist) [**Static Exports** \\
Next.js enables starting as a static site or Single-Page Application (SPA), then later optionally upgrading to use features that require a server.](https://nextjs.org/docs/pages/building-your-application/deploying/static-exports) [**Multi-Zones** \\
Learn how to build micro-frontends using Next.js Multi-Zones to deploy multiple Next.js apps under a single domain.](https://nextjs.org/docs/pages/building-your-application/deploying/multi-zones) [**Continuous Integration (CI) Build Caching** \\
Learn how to configure CI to cache Next.js builds](https://nextjs.org/docs/pages/building-your-application/deploying/ci-build-caching)

Was this helpful?

supported.

Send

## Next.js API Routes
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/pages/building-your-application) [Routing](https://nextjs.org/docs/pages/building-your-application/routing) API Routes

# API Routes

Examples

- [API Routes Request Helpers](https://github.com/vercel/next.js/tree/canary/examples/api-routes-middleware)
- [API Routes with GraphQL](https://github.com/vercel/next.js/tree/canary/examples/api-routes-graphql)
- [API Routes with REST](https://github.com/vercel/next.js/tree/canary/examples/api-routes-rest)
- [API Routes with CORS](https://github.com/vercel/next.js/tree/canary/examples/api-routes-cors)

> **Good to know**: If you are using the App Router, you can use [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components) or [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) instead of API Routes.

API routes provide a solution to build a **public API** with Next.js.

Any file inside the folder `pages/api` is mapped to `/api/*` and will be treated as an API endpoint instead of a `page`. They are server-side only bundles and won't increase your client-side bundle size.

For example, the following API route returns a JSON response with a status code of `200`:

pages/api/hello.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

type ResponseData = {
  message: string
}

export default function handler(
  req: NextApiRequest,
  res: NextApiResponse<ResponseData>
) {
  res.status(200).json({ message: 'Hello from Next.js!' })
}
```

> **Good to know**:
>
> - API Routes [do not specify CORS headers](https://developer.mozilla.org/docs/Web/HTTP/CORS), meaning they are **same-origin only** by default. You can customize such behavior by wrapping the request handler with the [CORS request helpers](https://github.com/vercel/next.js/tree/canary/examples/api-routes-cors).

- API Routes can't be used with [static exports](https://nextjs.org/docs/pages/building-your-application/deploying/static-exports). However, [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) in the App Router can.

> - API Routes will be affected by [`pageExtensions` configuration](https://nextjs.org/docs/pages/api-reference/config/next-config-js/pageExtensions) in `next.config.js`.


## [Parameters](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#parameters)

```code-block_code__isn_V
export default function handler(req: NextApiRequest, res: NextApiResponse) {
  // ...
}
```

- `req`: An instance of [http.IncomingMessage](https://nodejs.org/api/http.html#class-httpincomingmessage)
- `res`: An instance of [http.ServerResponse](https://nodejs.org/api/http.html#class-httpserverresponse)

## [HTTP Methods](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#http-methods)

To handle different HTTP methods in an API route, you can use `req.method` in your request handler, like so:

pages/api/hello.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

export default function handler(req: NextApiRequest, res: NextApiResponse) {
  if (req.method === 'POST') {
    // Process a POST request
  } else {
    // Handle any other HTTP method
  }
}
```

## [Request Helpers](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#request-helpers)

API Routes provide built-in request helpers which parse the incoming request ( `req`):

- `req.cookies` \- An object containing the cookies sent by the request. Defaults to `{}`
- `req.query` \- An object containing the [query string](https://en.wikipedia.org/wiki/Query_string). Defaults to `{}`
- `req.body` \- An object containing the body parsed by `content-type`, or `null` if no body was sent

### [Custom config](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#custom-config)

Every API Route can export a `config` object to change the default configuration, which is the following:

```code-block_code__isn_V
export const config = {
  api: {
    bodyParser: {
      sizeLimit: '1mb',
    },
  },
  // Specifies the maximum allowed duration for this function to execute (in seconds)
  maxDuration: 5,
}
```

`bodyParser` is automatically enabled. If you want to consume the body as a `Stream` or with [`raw-body`](https://www.npmjs.com/package/raw-body), you can set this to `false`.

One use case for disabling the automatic `bodyParsing` is to allow you to verify the raw body of a **webhook** request, for example [from GitHub](https://docs.github.com/en/developers/webhooks-and-events/webhooks/securing-your-webhooks#validating-payloads-from-github).

```code-block_code__isn_V
export const config = {
  api: {
    bodyParser: false,
  },
}
```

`bodyParser.sizeLimit` is the maximum size allowed for the parsed body, in any format supported by [bytes](https://github.com/visionmedia/bytes.js), like so:

```code-block_code__isn_V
export const config = {
  api: {
    bodyParser: {
      sizeLimit: '500kb',
    },
  },
}
```

`externalResolver` is an explicit flag that tells the server that this route is being handled by an external resolver like _express_ or _connect_. Enabling this option disables warnings for unresolved requests.

```code-block_code__isn_V
export const config = {
  api: {
    externalResolver: true,
  },
}
```

`responseLimit` is automatically enabled, warning when an API Routes' response body is over 4MB.

If you are not using Next.js in a serverless environment, and understand the performance implications of not using a CDN or dedicated media host, you can set this limit to `false`.

```code-block_code__isn_V
export const config = {
  api: {
    responseLimit: false,
  },
}
```

`responseLimit` can also take the number of bytes or any string format supported by `bytes`, for example `1000`, `'500kb'` or `'3mb'`.
This value will be the maximum response size before a warning is displayed. Default is 4MB. (see above)

```code-block_code__isn_V
export const config = {
  api: {
    responseLimit: '8mb',
  },
}
```

## [Response Helpers](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#response-helpers)

The [Server Response object](https://nodejs.org/api/http.html#http_class_http_serverresponse), (often abbreviated as `res`) includes a set of Express.js-like helper methods to improve the developer experience and increase the speed of creating new API endpoints.

The included helpers are:

- `res.status(code)` \- A function to set the status code. `code` must be a valid [HTTP status code](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes)
- `res.json(body)` \- Sends a JSON response. `body` must be a [serializable object](https://developer.mozilla.org/docs/Glossary/Serialization)
- `res.send(body)` \- Sends the HTTP response. `body` can be a `string`, an `object` or a `Buffer`
- `res.redirect([status,] path)` \- Redirects to a specified path or URL. `status` must be a valid [HTTP status code](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes). If not specified, `status` defaults to "307" "Temporary redirect".
- `res.revalidate(urlPath)` \- [Revalidate a page on demand](https://nextjs.org/docs/pages/building-your-application/data-fetching/incremental-static-regeneration#on-demand-revalidation-with-revalidatepath) using `getStaticProps`. `urlPath` must be a `string`.

### [Setting the status code of a response](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#setting-the-status-code-of-a-response)

When sending a response back to the client, you can set the status code of the response.

The following example sets the status code of the response to `200` ( `OK`) and returns a `message` property with the value of `Hello from Next.js!` as a JSON response:

pages/api/hello.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

type ResponseData = {
  message: string
}

export default function handler(
  req: NextApiRequest,
  res: NextApiResponse<ResponseData>
) {
  res.status(200).json({ message: 'Hello from Next.js!' })
}
```

### [Sending a JSON response](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#sending-a-json-response)

When sending a response back to the client you can send a JSON response, this must be a [serializable object](https://developer.mozilla.org/docs/Glossary/Serialization).
In a real world application you might want to let the client know the status of the request depending on the result of the requested endpoint.

The following example sends a JSON response with the status code `200` ( `OK`) and the result of the async operation. It's contained in a try catch block to handle any errors that may occur, with the appropriate status code and error message caught and sent back to the client:

pages/api/hello.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

export default async function handler(
  req: NextApiRequest,
  res: NextApiResponse
) {
  try {
    const result = await someAsyncOperation()
    res.status(200).json({ result })
  } catch (err) {
    res.status(500).json({ error: 'failed to load data' })
  }
}
```

### [Sending a HTTP response](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#sending-a-http-response)

Sending an HTTP response works the same way as when sending a JSON response. The only difference is that the response body can be a `string`, an `object` or a `Buffer`.

The following example sends a HTTP response with the status code `200` ( `OK`) and the result of the async operation.

pages/api/hello.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

export default async function handler(
  req: NextApiRequest,
  res: NextApiResponse
) {
  try {
    const result = await someAsyncOperation()
    res.status(200).send({ result })
  } catch (err) {
    res.status(500).send({ error: 'failed to fetch data' })
  }
}
```

### [Redirects to a specified path or URL](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#redirects-to-a-specified-path-or-url)

Taking a form as an example, you may want to redirect your client to a specified path or URL once they have submitted the form.

The following example redirects the client to the `/` path if the form is successfully submitted:

pages/api/hello.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

export default async function handler(
  req: NextApiRequest,
  res: NextApiResponse
) {
  const { name, message } = req.body

  try {
    await handleFormInputAsync({ name, message })
    res.redirect(307, '/')
  } catch (err) {
    res.status(500).send({ error: 'Failed to fetch data' })
  }
}
```

### [Adding TypeScript types](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#adding-typescript-types)

You can make your API Routes more type-safe by importing the `NextApiRequest` and `NextApiResponse` types from `next`, in addition to those, you can also type your response data:

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

type ResponseData = {
  message: string
}

export default function handler(
  req: NextApiRequest,
  res: NextApiResponse<ResponseData>
) {
  res.status(200).json({ message: 'Hello from Next.js!' })
}
```

> **Good to know**: The body of `NextApiRequest` is `any` because the client may include any payload. You should validate the type/shape of the body at runtime before using it.

## [Dynamic API Routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#dynamic-api-routes)

API Routes support [dynamic routes](https://nextjs.org/docs/pages/building-your-application/routing/dynamic-routes), and follow the same file naming rules used for `pages/`.

pages/api/post/\[pid\].ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

export default function handler(req: NextApiRequest, res: NextApiResponse) {
  const { pid } = req.query
  res.end(`Post: ${pid}`)
}
```

Now, a request to `/api/post/abc` will respond with the text: `Post: abc`.

### [Catch all API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#catch-all-api-routes)

API Routes can be extended to catch all paths by adding three dots ( `...`) inside the brackets. For example:

- `pages/api/post/[...slug].js` matches `/api/post/a`, but also `/api/post/a/b`, `/api/post/a/b/c` and so on.

> **Good to know**: You can use names other than `slug`, such as: `[...param]`

Matched parameters will be sent as a query parameter ( `slug` in the example) to the page, and it will always be an array, so, the path `/api/post/a` will have the following `query` object:

```code-block_code__isn_V
{ "slug": ["a"] }
```

And in the case of `/api/post/a/b`, and any other matching path, new parameters will be added to the array, like so:

```code-block_code__isn_V
{ "slug": ["a", "b"] }
```

For example:

pages/api/post/\[...slug\].ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

export default function handler(req: NextApiRequest, res: NextApiResponse) {
  const { slug } = req.query
  res.end(`Post: ${slug.join(', ')}`)
}
```

Now, a request to `/api/post/a/b/c` will respond with the text: `Post: a, b, c`.

### [Optional catch all API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#optional-catch-all-api-routes)

Catch all routes can be made optional by including the parameter in double brackets ( `[[...slug]]`).

For example, `pages/api/post/[[...slug]].js` will match `/api/post`, `/api/post/a`, `/api/post/a/b`, and so on.

The main difference between catch all and optional catch all routes is that with optional, the route without the parameter is also matched ( `/api/post` in the example above).

The `query` objects are as follows:

```code-block_code__isn_V
{ } // GET `/api/post` (empty object)
{ "slug": ["a"] } // `GET /api/post/a` (single-element array)
{ "slug": ["a", "b"] } // `GET /api/post/a/b` (multi-element array)
```

### [Caveats](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#caveats)

- Predefined API routes take precedence over dynamic API routes, and dynamic API routes over catch all API routes. Take a look at the following examples:
  - `pages/api/post/create.js` \- Will match `/api/post/create`
  - `pages/api/post/[pid].js` \- Will match `/api/post/1`, `/api/post/abc`, etc. But not `/api/post/create`
  - `pages/api/post/[...slug].js` \- Will match `/api/post/1/2`, `/api/post/a/b/c`, etc. But not `/api/post/create`, `/api/post/abc`

## [Edge API Routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes\#edge-api-routes)

If you would like to use API Routes with the Edge Runtime, we recommend incrementally adopting the App Router and using [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) instead.

The Route Handlers function signature is isomorphic, meaning you can use the same function for both Edge and Node.js runtimes.

Was this helpful?

supported.

Send

## Next.js API Reference
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Introduction](https://nextjs.org/docs) [App Router](https://nextjs.org/docs/app) API Reference

# API Reference

The Next.js API reference is divided into the following sections:

[**Directives** \\
Directives are used to modify the behavior of your Next.js application.](https://nextjs.org/docs/app/api-reference/directives) [**Components** \\
API Reference for Next.js built-in components.](https://nextjs.org/docs/app/api-reference/components) [**File Conventions** \\
API Reference for Next.js File Conventions.](https://nextjs.org/docs/app/api-reference/file-conventions) [**Functions** \\
API Reference for Next.js Functions and Hooks.](https://nextjs.org/docs/app/api-reference/functions) [**Configuration** \\
Learn how to configure Next.js applications.](https://nextjs.org/docs/app/api-reference/config) [**CLI** \\
API Reference for the Next.js Command Line Interface (CLI) tools.](https://nextjs.org/docs/app/api-reference/cli) [**Edge Runtime** \\
API Reference for the Edge Runtime.](https://nextjs.org/docs/app/api-reference/edge) [**Turbopack** \\
Turbopack is an incremental bundler optimized for JavaScript and TypeScript, written in Rust, and built into Next.js.](https://nextjs.org/docs/app/api-reference/turbopack)

Was this helpful?

supported.

Send

## Next.js Pages and Layouts
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/pages/building-your-application) [Routing](https://nextjs.org/docs/pages/building-your-application/routing) Pages and Layouts

# Pages and Layouts

The Pages Router has a file-system based router built on the concept of pages.

When a file is added to the `pages` directory, it's automatically available as a route.

In Next.js, a **page** is a [React Component](https://react.dev/learn/your-first-component) exported from a `.js`, `.jsx`, `.ts`, or `.tsx` file in the `pages` directory. Each page is associated with a route based on its file name.

**Example**: If you create `pages/about.js` that exports a React component like below, it will be accessible at `/about`.

```code-block_code__isn_V
export default function About() {
  return <div>About</div>
}
```

## [Index routes](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts\#index-routes)

The router will automatically route files named `index` to the root of the directory.

- `pages/index.js` → `/`
- `pages/blog/index.js` → `/blog`

## [Nested routes](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts\#nested-routes)

The router supports nested files. If you create a nested folder structure, files will automatically be routed in the same way still.

- `pages/blog/first-post.js` → `/blog/first-post`
- `pages/dashboard/settings/username.js` → `/dashboard/settings/username`

## [Pages with Dynamic Routes](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts\#pages-with-dynamic-routes)

Next.js supports pages with dynamic routes. For example, if you create a file called `pages/posts/[id].js`, then it will be accessible at `posts/1`, `posts/2`, etc.

> To learn more about dynamic routing, check the [Dynamic Routing documentation](https://nextjs.org/docs/pages/building-your-application/routing/dynamic-routes).

## [Layout Pattern](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts\#layout-pattern)

The React model allows us to deconstruct a [page](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts) into a series of components. Many of these components are often reused between pages. For example, you might have the same navigation bar and footer on every page.

components/layout.js

```code-block_code__isn_V
import Navbar from './navbar'
import Footer from './footer'

export default function Layout({ children }) {
  return (
    <>
      <Navbar />
      <main>{children}</main>
      <Footer />
    </>
  )
}
```

## [Examples](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts\#examples)

### [Single Shared Layout with Custom App](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts\#single-shared-layout-with-custom-app)

If you only have one layout for your entire application, you can create a [Custom App](https://nextjs.org/docs/pages/building-your-application/routing/custom-app) and wrap your application with the layout. Since the `<Layout />` component is re-used when changing pages, its component state will be preserved (e.g. input values).

pages/\_app.js

```code-block_code__isn_V
import Layout from '../components/layout'

export default function MyApp({ Component, pageProps }) {
  return (
    <Layout>
      <Component {...pageProps} />
    </Layout>
  )
}
```

### [Per-Page Layouts](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts\#per-page-layouts)

If you need multiple layouts, you can add a property `getLayout` to your page, allowing you to return a React component for the layout. This allows you to define the layout on a _per-page basis_. Since we're returning a function, we can have complex nested layouts if desired.

pages/index.js

```code-block_code__isn_V

import Layout from '../components/layout'
import NestedLayout from '../components/nested-layout'

export default function Page() {
  return (
    /** Your content */
  )
}

Page.getLayout = function getLayout(page) {
  return (
    <Layout>
      <NestedLayout>{page}</NestedLayout>
    </Layout>
  )
}
```

pages/\_app.js

```code-block_code__isn_V
export default function MyApp({ Component, pageProps }) {
  // Use the layout defined at the page level, if available
  const getLayout = Component.getLayout ?? ((page) => page)

  return getLayout(<Component {...pageProps} />)
}
```

When navigating between pages, we want to _persist_ page state (input values, scroll position, etc.) for a Single-Page Application (SPA) experience.

This layout pattern enables state persistence because the React component tree is maintained between page transitions. With the component tree, React can understand which elements have changed to preserve state.

> **Good to know**: This process is called [reconciliation](https://react.dev/learn/preserving-and-resetting-state), which is how React understands which elements have changed.

### [With TypeScript](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts\#with-typescript)

When using TypeScript, you must first create a new type for your pages which includes a `getLayout` function. Then, you must create a new type for your `AppProps` which overrides the `Component` property to use the previously created type.

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { ReactElement } from 'react'
import Layout from '../components/layout'
import NestedLayout from '../components/nested-layout'
import type { NextPageWithLayout } from './_app'

const Page: NextPageWithLayout = () => {
  return <p>hello world</p>
}

Page.getLayout = function getLayout(page: ReactElement) {
  return (
    <Layout>
      <NestedLayout>{page}</NestedLayout>
    </Layout>
  )
}

export default Page
```

pages/\_app.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { ReactElement, ReactNode } from 'react'
import type { NextPage } from 'next'
import type { AppProps } from 'next/app'

export type NextPageWithLayout<P = {}, IP = P> = NextPage<P, IP> & {
  getLayout?: (page: ReactElement) => ReactNode
}

type AppPropsWithLayout = AppProps & {
  Component: NextPageWithLayout
}

export default function MyApp({ Component, pageProps }: AppPropsWithLayout) {
  // Use the layout defined at the page level, if available
  const getLayout = Component.getLayout ?? ((page) => page)

  return getLayout(<Component {...pageProps} />)
}
```

### [Data Fetching](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts\#data-fetching)

Inside your layout, you can fetch data on the client-side using `useEffect` or a library like [SWR](https://swr.vercel.app/). Because this file is not a [Page](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts), you cannot use `getStaticProps` or `getServerSideProps` currently.

components/layout.js

```code-block_code__isn_V
import useSWR from 'swr'
import Navbar from './navbar'
import Footer from './footer'

export default function Layout({ children }) {
  const { data, error } = useSWR('/api/navigation', fetcher)

  if (error) return <div>Failed to load</div>
  if (!data) return <div>Loading...</div>

  return (
    <>
      <Navbar links={data.links} />
      <main>{children}</main>
      <Footer />
    </>
  )
}
```

Was this helpful?

supported.

Send

## Next.js Routing Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Building Your Application](https://nextjs.org/docs/app/building-your-application) Routing

# Routing Fundamentals

[**Layouts and Templates** \\
Create your first shared layout in Next.js.](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates) [**Linking and Navigating** \\
Learn how navigation works in Next.js, and how to use the Link Component and \`useRouter\` hook.](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating) [**Error Handling** \\
Learn how to display expected errors and handle uncaught exceptions.](https://nextjs.org/docs/app/building-your-application/routing/error-handling) [**Loading UI and Streaming** \\
Built on top of Suspense, Loading UI allows you to create a fallback for specific route segments, and automatically stream content as it becomes ready.](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming) [**Redirecting** \\
Learn the different ways to handle redirects in Next.js.](https://nextjs.org/docs/app/building-your-application/routing/redirecting) [**Route Groups** \\
Route Groups can be used to partition your Next.js application into different sections.](https://nextjs.org/docs/app/building-your-application/routing/route-groups) [**Dynamic Routes** \\
Dynamic Routes can be used to programmatically generate route segments from dynamic data.](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes) [**Parallel Routes** \\
Simultaneously render one or more pages in the same view that can be navigated independently. A pattern for highly dynamic applications.](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes) [**Intercepting Routes** \\
Use intercepting routes to load a new route within the current layout while masking the browser URL, useful for advanced routing patterns such as modals.](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes) [**Route Handlers** \\
Create custom request handlers for a given route using the Web's Request and Response APIs.](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) [**Middleware** \\
Learn how to use Middleware to run code before a request is completed.](https://nextjs.org/docs/app/building-your-application/routing/middleware) [**Internationalization** \\
Add support for multiple languages with internationalized routing and localized content.](https://nextjs.org/docs/app/building-your-application/routing/internationalization)

Was this helpful?

supported.

Send

## Next.js 14 Guide
Menu

Using App Router

Features available in /app

Using Version 14

14.2.25

Using App Router

Features available in /app

Using Version 14

14.2.25

[Introduction](https://nextjs.org/docs/14) Getting Started

You are currently viewing documentation for version 14 of Next.js.

# Getting Started

[**Installation** \\
Create a new Next.js application with \`create-next-app\`. Set up TypeScript, styles, and configure your \`next.config.js\` file.](https://nextjs.org/docs/14/getting-started/installation) [**Project Structure** \\
A list of folders and files conventions in a Next.js project](https://nextjs.org/docs/14/getting-started/project-structure)

Was this helpful?

supported.

Send

## Next.js Project Structure
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Getting Started](https://nextjs.org/docs/app/getting-started) Project Structure

# Project structure and organization

This page provides an overview of the folder and file conventions in Next.js, as well as tips for organizing your project.

## [Folder and file conventions](https://nextjs.org/docs/app/getting-started/project-structure\#folder-and-file-conventions)

### [Top-level folders](https://nextjs.org/docs/app/getting-started/project-structure\#top-level-folders)

Top-level folders are used to organize your application's code and static assets.

![Route segments to path segments](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Ftop-level-folders.png&w=3840&q=75)![Route segments to path segments](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Ftop-level-folders.png&w=3840&q=75)

|  |  |
| --- | --- |
| [`app`](https://nextjs.org/docs/app/building-your-application/routing) | App Router |
| [`pages`](https://nextjs.org/docs/pages/building-your-application/routing) | Pages Router |
| [`public`](https://nextjs.org/docs/app/building-your-application/optimizing/static-assets) | Static assets to be served |
| [`src`](https://nextjs.org/docs/app/building-your-application/configuring/src-directory) | Optional application source folder |

### [Top-level files](https://nextjs.org/docs/app/getting-started/project-structure\#top-level-files)

Top-level files are used to configure your application, manage dependencies, run middleware, integrate monitoring tools, and define environment variables.

|  |  |
| --- | --- |
| **Next.js** |  |
| [`next.config.js`](https://nextjs.org/docs/app/api-reference/config/next-config-js) | Configuration file for Next.js |
| [`package.json`](https://nextjs.org/docs/app/getting-started/installation#manual-installation) | Project dependencies and scripts |
| [`instrumentation.ts`](https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation) | OpenTelemetry and Instrumentation file |
| [`middleware.ts`](https://nextjs.org/docs/app/building-your-application/routing/middleware) | Next.js request middleware |
| [`.env`](https://nextjs.org/docs/app/building-your-application/configuring/environment-variables) | Environment variables |
| [`.env.local`](https://nextjs.org/docs/app/building-your-application/configuring/environment-variables) | Local environment variables |
| [`.env.production`](https://nextjs.org/docs/app/building-your-application/configuring/environment-variables) | Production environment variables |
| [`.env.development`](https://nextjs.org/docs/app/building-your-application/configuring/environment-variables) | Development environment variables |
| [`.eslintrc.json`](https://nextjs.org/docs/app/api-reference/config/eslint) | Configuration file for ESLint |
| `.gitignore` | Git files and folders to ignore |
| `next-env.d.ts` | TypeScript declaration file for Next.js |
| `tsconfig.json` | Configuration file for TypeScript |
| `jsconfig.json` | Configuration file for JavaScript |

### [Routing Files](https://nextjs.org/docs/app/getting-started/project-structure\#routing-files)

|  |  |  |
| --- | --- | --- |
| [`layout`](https://nextjs.org/docs/app/api-reference/file-conventions/layout) | `.js` `.jsx` `.tsx` | Layout |
| [`page`](https://nextjs.org/docs/app/api-reference/file-conventions/page) | `.js` `.jsx` `.tsx` | Page |
| [`loading`](https://nextjs.org/docs/app/api-reference/file-conventions/loading) | `.js` `.jsx` `.tsx` | Loading UI |
| [`not-found`](https://nextjs.org/docs/app/api-reference/file-conventions/not-found) | `.js` `.jsx` `.tsx` | Not found UI |
| [`error`](https://nextjs.org/docs/app/api-reference/file-conventions/error) | `.js` `.jsx` `.tsx` | Error UI |
| [`global-error`](https://nextjs.org/docs/app/api-reference/file-conventions/error#global-error) | `.js` `.jsx` `.tsx` | Global error UI |
| [`route`](https://nextjs.org/docs/app/api-reference/file-conventions/route) | `.js` `.ts` | API endpoint |
| [`template`](https://nextjs.org/docs/app/api-reference/file-conventions/template) | `.js` `.jsx` `.tsx` | Re-rendered layout |
| [`default`](https://nextjs.org/docs/app/api-reference/file-conventions/default) | `.js` `.jsx` `.tsx` | Parallel route fallback page |

### [Nested routes](https://nextjs.org/docs/app/getting-started/project-structure\#nested-routes)

|  |  |
| --- | --- |
| `folder` | Route segment |
| `folder/folder` | Nested route segment |

### [Dynamic routes](https://nextjs.org/docs/app/getting-started/project-structure\#dynamic-routes)

|  |  |
| --- | --- |
| [`[folder]`](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes#convention) | Dynamic route segment |
| [`[...folder]`](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes#catch-all-segments) | Catch-all route segment |
| [`[[...folder]]`](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes#optional-catch-all-segments) | Optional catch-all route segment |

### [Route Groups and private folders](https://nextjs.org/docs/app/getting-started/project-structure\#route-groups-and-private-folders)

|  |  |
| --- | --- |
| [`(folder)`](https://nextjs.org/docs/app/building-your-application/routing/route-groups#convention) | Group routes without affecting routing |
| [`_folder`](https://nextjs.org/docs/app/getting-started/project-structure#private-folders) | Opt folder and all child segments out of routing |

### [Parallel and Intercepted Routes](https://nextjs.org/docs/app/getting-started/project-structure\#parallel-and-intercepted-routes)

|  |  |
| --- | --- |
| [`@folder`](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes#slots) | Named slot |
| [`(.)folder`](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes#convention) | Intercept same level |
| [`(..)folder`](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes#convention) | Intercept one level above |
| [`(..)(..)folder`](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes#convention) | Intercept two levels above |
| [`(...)folder`](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes#convention) | Intercept from root |

### [Metadata file conventions](https://nextjs.org/docs/app/getting-started/project-structure\#metadata-file-conventions)

#### [App icons](https://nextjs.org/docs/app/getting-started/project-structure\#app-icons)

|  |  |  |
| --- | --- | --- |
| [`favicon`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/app-icons#favicon) | `.ico` | Favicon file |
| [`icon`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/app-icons#icon) | `.ico` `.jpg` `.jpeg` `.png` `.svg` | App Icon file |
| [`icon`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/app-icons#generate-icons-using-code-js-ts-tsx) | `.js` `.ts` `.tsx` | Generated App Icon |
| [`apple-icon`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/app-icons#apple-icon) | `.jpg` `.jpeg`, `.png` | Apple App Icon file |
| [`apple-icon`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/app-icons#generate-icons-using-code-js-ts-tsx) | `.js` `.ts` `.tsx` | Generated Apple App Icon |

#### [Open Graph and Twitter images](https://nextjs.org/docs/app/getting-started/project-structure\#open-graph-and-twitter-images)

|  |  |  |
| --- | --- | --- |
| [`opengraph-image`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/opengraph-image#opengraph-image) | `.jpg` `.jpeg` `.png` `.gif` | Open Graph image file |
| [`opengraph-image`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/opengraph-image#generate-images-using-code-js-ts-tsx) | `.js` `.ts` `.tsx` | Generated Open Graph image |
| [`twitter-image`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/opengraph-image#twitter-image) | `.jpg` `.jpeg` `.png` `.gif` | Twitter image file |
| [`twitter-image`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/opengraph-image#generate-images-using-code-js-ts-tsx) | `.js` `.ts` `.tsx` | Generated Twitter image |

#### [SEO](https://nextjs.org/docs/app/getting-started/project-structure\#seo)

|  |  |  |
| --- | --- | --- |
| [`sitemap`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/sitemap#sitemap-files-xml) | `.xml` | Sitemap file |
| [`sitemap`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/sitemap#generating-a-sitemap-using-code-js-ts) | `.js` `.ts` | Generated Sitemap |
| [`robots`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/robots#static-robotstxt) | `.txt` | Robots file |
| [`robots`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/robots#generate-a-robots-file) | `.js` `.ts` | Generated Robots file |

## [Component hierarchy](https://nextjs.org/docs/app/getting-started/project-structure\#component-hierarchy)

The React components defined in special files of a route segment are rendered in a specific hierarchy:

- `layout.js`
- `template.js`
- `error.js` (React error boundary)
- `loading.js` (React suspense boundary)
- `not-found.js` (React error boundary)
- `page.js` or nested `layout.js`

![Component Hierarchy for File Conventions](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Ffile-conventions-component-hierarchy.png&w=3840&q=75)![Component Hierarchy for File Conventions](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Ffile-conventions-component-hierarchy.png&w=3840&q=75)

In a nested route, the components of a segment will be nested **inside** the components of its parent segment.

![Nested File Conventions Component Hierarchy](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fnested-file-conventions-component-hierarchy.png&w=3840&q=75)![Nested File Conventions Component Hierarchy](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fnested-file-conventions-component-hierarchy.png&w=3840&q=75)

## [Organizing your project](https://nextjs.org/docs/app/getting-started/project-structure\#organizing-your-project)

Apart from [folder and file conventions](https://nextjs.org/docs/app/getting-started/project-structure), Next.js is **unopinionated** about how you organize and colocate your project files. But it does provide several features to help you organize your project.

### [Colocation](https://nextjs.org/docs/app/getting-started/project-structure\#colocation)

In the `app` directory, nested folders define route structure. Each folder represents a route segment that is mapped to a corresponding segment in a URL path.

However, even though route structure is defined through folders, a route is **not publicly accessible** until a `page.js` or `route.js` file is added to a route segment.

![A diagram showing how a route is not publicly accessible until a page.js or route.js file is added to a route segment.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fproject-organization-not-routable.png&w=3840&q=75)![A diagram showing how a route is not publicly accessible until a page.js or route.js file is added to a route segment.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fproject-organization-not-routable.png&w=3840&q=75)

And, even when a route is made publicly accessible, only the **content returned** by `page.js` or `route.js` is sent to the client.

![A diagram showing how page.js and route.js files make routes publicly accessible.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fproject-organization-routable.png&w=3840&q=75)![A diagram showing how page.js and route.js files make routes publicly accessible.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fproject-organization-routable.png&w=3840&q=75)

This means that **project files** can be **safely colocated** inside route segments in the `app` directory without accidentally being routable.

![A diagram showing colocated project files are not routable even when a segment contains a page.js or route.js file.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fproject-organization-colocation.png&w=3840&q=75)![A diagram showing colocated project files are not routable even when a segment contains a page.js or route.js file.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fproject-organization-colocation.png&w=3840&q=75)

> **Good to know**:
>
> - While you **can** colocate your project files in `app` you don't **have** to. If you prefer, you can [keep them outside the `app` directory](https://nextjs.org/docs/app/getting-started/project-structure#store-project-files-outside-of-app).

### [Private folders](https://nextjs.org/docs/app/getting-started/project-structure\#private-folders)

Private folders can be created by prefixing a folder with an underscore: `_folderName`

This indicates the folder is a private implementation detail and should not be considered by the routing system, thereby **opting the folder and all its subfolders** out of routing.

![An example folder structure using private folders](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fproject-organization-private-folders.png&w=3840&q=75)![An example folder structure using private folders](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fproject-organization-private-folders.png&w=3840&q=75)

Since files in the `app` directory can be [safely colocated by default](https://nextjs.org/docs/app/getting-started/project-structure#colocation), private folders are not required for colocation. However, they can be useful for:

- Separating UI logic from routing logic.
- Consistently organizing internal files across a project and the Next.js ecosystem.
- Sorting and grouping files in code editors.
- Avoiding potential naming conflicts with future Next.js file conventions.

> **Good to know**:
>
> - While not a framework convention, you might also consider marking files outside private folders as "private" using the same underscore pattern.
> - You can create URL segments that start with an underscore by prefixing the folder name with `%5F` (the URL-encoded form of an underscore): `%5FfolderName`.
> - If you don't use private folders, it would be helpful to know Next.js [special file conventions](https://nextjs.org/docs/app/getting-started/project-structure#routing-files) to prevent unexpected naming conflicts.

### [Route groups](https://nextjs.org/docs/app/getting-started/project-structure\#route-groups)

Route groups can be created by wrapping a folder in parenthesis: `(folderName)`

This indicates the folder is for organizational purposes and should **not be included** in the route's URL path.

![An example folder structure using route groups](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fproject-organization-route-groups.png&w=3840&q=75)![An example folder structure using route groups](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fproject-organization-route-groups.png&w=3840&q=75)

Route groups are useful for:

- [Organizing routes into groups](https://nextjs.org/docs/app/building-your-application/routing/route-groups#organize-routes-without-affecting-the-url-path) e.g. by site section, intent, or team.
- Enabling nested layouts in the same route segment level:
  - [Creating multiple nested layouts in the same segment, including multiple root layouts](https://nextjs.org/docs/app/building-your-application/routing/route-groups#creating-multiple-root-layouts)
  - [Adding a layout to a subset of routes in a common segment](https://nextjs.org/docs/app/building-your-application/routing/route-groups#opting-specific-segments-into-a-layout)

### [`src` directory](https://nextjs.org/docs/app/getting-started/project-structure\#src-directory)

Next.js supports storing application code (including `app`) inside an optional [`src` directory](https://nextjs.org/docs/app/building-your-application/configuring/src-directory). This separates application code from project configuration files which mostly live in the root of a project.

![An example folder structure with the `src` directory](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fproject-organization-src-directory.png&w=3840&q=75)![An example folder structure with the `src` directory](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fproject-organization-src-directory.png&w=3840&q=75)

### [Common strategies](https://nextjs.org/docs/app/getting-started/project-structure\#common-strategies)

The following section lists a very high-level overview of common strategies. The simplest takeaway is to choose a strategy that works for you and your team and be consistent across the project.

> **Good to know**: In our examples below, we're using `components` and `lib` folders as generalized placeholders, their naming has no special framework significance and your projects might use other folders like `ui`, `utils`, `hooks`, `styles`, etc.

#### [Store project files outside of `app`](https://nextjs.org/docs/app/getting-started/project-structure\#store-project-files-outside-of-app)

This strategy stores all application code in shared folders in the **root of your project** and keeps the `app` directory purely for routing purposes.

![An example folder structure with project files outside of app](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fproject-organization-project-root.png&w=3840&q=75)![An example folder structure with project files outside of app](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fproject-organization-project-root.png&w=3840&q=75)

#### [Store project files in top-level folders inside of `app`](https://nextjs.org/docs/app/getting-started/project-structure\#store-project-files-in-top-level-folders-inside-of-app)

This strategy stores all application code in shared folders in the **root of the `app` directory**.

![An example folder structure with project files inside app](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fproject-organization-app-root.png&w=3840&q=75)![An example folder structure with project files inside app](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fproject-organization-app-root.png&w=3840&q=75)

#### [Split project files by feature or route](https://nextjs.org/docs/app/getting-started/project-structure\#split-project-files-by-feature-or-route)

This strategy stores globally shared application code in the root `app` directory and **splits** more specific application code into the route segments that use them.

![An example folder structure with project files split by feature or route](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fproject-organization-app-root-split.png&w=3840&q=75)![An example folder structure with project files split by feature or route](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fproject-organization-app-root-split.png&w=3840&q=75)

Was this helpful?

supported.

Send

## Dynamic Routes in Next.js
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/pages/building-your-application) [Routing](https://nextjs.org/docs/pages/building-your-application/routing) Dynamic Routes

# Dynamic Routes

When you don't know the exact segment names ahead of time and want to create routes from dynamic data, you can use Dynamic Segments that are filled in at request time or [prerendered](https://nextjs.org/docs/pages/building-your-application/data-fetching/get-static-paths) at build time.

## [Convention](https://nextjs.org/docs/pages/building-your-application/routing/dynamic-routes\#convention)

A Dynamic Segment can be created by wrapping a file or folder name in square brackets: `[segmentName]`. For example, `[id]` or `[slug]`.

Dynamic Segments can be accessed from [`useRouter`](https://nextjs.org/docs/pages/api-reference/functions/use-router).

## [Example](https://nextjs.org/docs/pages/building-your-application/routing/dynamic-routes\#example)

For example, a blog could include the following route `pages/blog/[slug].js` where `[slug]` is the Dynamic Segment for blog posts.

```code-block_code__isn_V
import { useRouter } from 'next/router'

export default function Page() {
  const router = useRouter()
  return <p>Post: {router.query.slug}</p>
}
```

| Route | Example URL | `params` |
| --- | --- | --- |
| `pages/blog/[slug].js` | `/blog/a` | `{ slug: 'a' }` |
| `pages/blog/[slug].js` | `/blog/b` | `{ slug: 'b' }` |
| `pages/blog/[slug].js` | `/blog/c` | `{ slug: 'c' }` |

## [Catch-all Segments](https://nextjs.org/docs/pages/building-your-application/routing/dynamic-routes\#catch-all-segments)

Dynamic Segments can be extended to **catch-all** subsequent segments by adding an ellipsis inside the brackets `[...segmentName]`.

For example, `pages/shop/[...slug].js` will match `/shop/clothes`, but also `/shop/clothes/tops`, `/shop/clothes/tops/t-shirts`, and so on.

| Route | Example URL | `params` |
| --- | --- | --- |
| `pages/shop/[...slug].js` | `/shop/a` | `{ slug: ['a'] }` |
| `pages/shop/[...slug].js` | `/shop/a/b` | `{ slug: ['a', 'b'] }` |
| `pages/shop/[...slug].js` | `/shop/a/b/c` | `{ slug: ['a', 'b', 'c'] }` |

## [Optional Catch-all Segments](https://nextjs.org/docs/pages/building-your-application/routing/dynamic-routes\#optional-catch-all-segments)

Catch-all Segments can be made **optional** by including the parameter in double square brackets: `[[...segmentName]]`.

For example, `pages/shop/[[...slug]].js` will **also** match `/shop`, in addition to `/shop/clothes`, `/shop/clothes/tops`, `/shop/clothes/tops/t-shirts`.

The difference between **catch-all** and **optional catch-all** segments is that with optional, the route without the parameter is also matched ( `/shop` in the example above).

| Route | Example URL | `params` |
| --- | --- | --- |
| `pages/shop/[[...slug]].js` | `/shop` | `{ slug: undefined }` |
| `pages/shop/[[...slug]].js` | `/shop/a` | `{ slug: ['a'] }` |
| `pages/shop/[[...slug]].js` | `/shop/a/b` | `{ slug: ['a', 'b'] }` |
| `pages/shop/[[...slug]].js` | `/shop/a/b/c` | `{ slug: ['a', 'b', 'c'] }` |

## Next Steps

For more information on what to do next, we recommend the following sections

[**Linking and Navigating** \\
Learn how navigation works in Next.js, and how to use the Link Component and \`useRouter\` hook.](https://nextjs.org/docs/pages/building-your-application/routing/linking-and-navigating) [**useRouter** \\
Learn more about the API of the Next.js Router, and access the router instance in your page with the useRouter hook.](https://nextjs.org/docs/pages/api-reference/functions/use-router)

Was this helpful?

supported.

Send

## Next.js Rendering Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Building Your Application](https://nextjs.org/docs/app/building-your-application) Rendering

# Rendering

Rendering converts the code you write into user interfaces. React and Next.js allow you to create hybrid web applications where parts of your code can be rendered on the server or the client. This section will help you understand the differences between these rendering environments, strategies, and runtimes.

## [Fundamentals](https://nextjs.org/docs/app/building-your-application/rendering\#fundamentals)

To start, it's helpful to be familiar with three foundational web concepts:

- The [Environments](https://nextjs.org/docs/app/building-your-application/rendering#rendering-environments) your application code can be executed in: the server and the client.
- The [Request-Response Lifecycle](https://nextjs.org/docs/app/building-your-application/rendering#request-response-lifecycle) that's initiated when a user visits or interacts with your application.
- The [Network Boundary](https://nextjs.org/docs/app/building-your-application/rendering#network-boundary) that separates server and client code.

### [Rendering Environments](https://nextjs.org/docs/app/building-your-application/rendering\#rendering-environments)

There are two environments where web applications can be rendered: the client and the server.

![Client and Server Environments](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fclient-and-server-environments.png&w=3840&q=75)![Client and Server Environments](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fclient-and-server-environments.png&w=3840&q=75)

- The **client** refers to the browser on a user's device that sends a request to a server for your application code. It then turns the response from the server into a user interface.
- The **server** refers to the computer in a data center that stores your application code, receives requests from a client, and sends back an appropriate response.

Historically, developers had to use different languages (e.g. JavaScript, PHP) and frameworks when writing code for the server and the client. With React, developers can use the **same language** (JavaScript), and the **same framework** (e.g. Next.js or your framework of choice). This flexibility allows you to seamlessly write code for both environments without context switching.

However, each environment has its own set of capabilities and constraints. Therefore, the code you write for the server and the client is not always the same. There are certain operations (e.g. data fetching or managing user state) that are better suited for one environment over the other.

Understanding these differences is key to effectively using React and Next.js. We'll cover the differences and use cases in more detail on the [Server](https://nextjs.org/docs/app/building-your-application/rendering/server-components) and [Client](https://nextjs.org/docs/app/building-your-application/rendering/client-components) Components pages, for now, let's continue building on our foundation.

### [Request-Response Lifecycle](https://nextjs.org/docs/app/building-your-application/rendering\#request-response-lifecycle)

Broadly speaking, all websites follow the same **Request-Response Lifecycle**:

1. **User Action:** The user interacts with a web application. This could be clicking a link, submitting a form, or typing a URL directly into the browser's address bar.
2. **HTTP Request:** The client sends an [HTTP](https://developer.mozilla.org/docs/Web/HTTP) request to the server that contains necessary information about what resources are being requested, what method is being used (e.g. `GET`, `POST`), and additional data if necessary.
3. **Server:** The server processes the request and responds with the appropriate resources. This process may take a couple of steps like routing, fetching data, etc.
4. **HTTP Response:** After processing the request, the server sends an HTTP response back to the client. This response contains a status code (which tells the client whether the request was successful or not) and requested resources (e.g. HTML, CSS, JavaScript, static assets, etc).
5. **Client:** The client parses the resources to render the user interface.
6. **User Action:** Once the user interface is rendered, the user can interact with it, and the whole process starts again.

A major part of building a hybrid web application is deciding how to split the work in the lifecycle, and where to place the Network Boundary.

### [Network Boundary](https://nextjs.org/docs/app/building-your-application/rendering\#network-boundary)

In web development, the **Network Boundary** is a conceptual line that separates the different environments. For example, the client and the server, or the server and the data store.

In React, you choose where to place the client-server network boundary wherever it makes the most sense.

Behind the scenes, the work is split into two parts: the **client module graph** and the **server module graph**. The server module graph contains all the components that are rendered on the server, and the client module graph contains all components that are rendered on the client.

It may be helpful to think about module graphs as a visual representation of how files in your application depend on each other.

You can use the React `"use client"` convention to define the boundary. There's also a `"use server"` convention, which tells React to do some computational work on the server.

## [Building Hybrid Applications](https://nextjs.org/docs/app/building-your-application/rendering\#building-hybrid-applications)

When working in these environments, it's helpful to think of the flow of the code in your application as **unidirectional**. In other words, during a response, your application code flows in one direction: from the server to the client.

If you need to access the server from the client, you send a **new** request to the server rather than re-use the same request. This makes it easier to understand where to render your components and where to place the Network Boundary.

In practice, this model encourages developers to think about what they want to execute on the server first, before sending the result to the client and making the application interactive.

This concept will become clearer when we look at how you can [interleave client and server components](https://nextjs.org/docs/app/building-your-application/rendering/composition-patterns) in the same component tree.

[**Server Components** \\
Learn how you can use React Server Components to render parts of your application on the server.](https://nextjs.org/docs/app/building-your-application/rendering/server-components) [**Client Components** \\
Learn how to use Client Components to render parts of your application on the client.](https://nextjs.org/docs/app/building-your-application/rendering/client-components) [**Composition Patterns** \\
Recommended patterns for using Server and Client Components.](https://nextjs.org/docs/app/building-your-application/rendering/composition-patterns) [**Partial Prerendering** \\
Learn how to combine the benefits of static and dynamic rendering with Partial Prerendering.](https://nextjs.org/docs/app/building-your-application/rendering/partial-prerendering) [**Runtimes** \\
Learn about the switchable runtimes (Edge and Node.js) in Next.js.](https://nextjs.org/docs/app/building-your-application/rendering/edge-and-nodejs-runtimes)

Was this helpful?

supported.

Send

## Next.js Navigation Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Linking and Navigating

# Linking and Navigating

There are four ways to navigate between routes in Next.js:

- Using the [`<Link>` Component](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#link-component)
- Using the [`useRouter` hook](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#userouter-hook) ( [Client Components](https://nextjs.org/docs/app/building-your-application/rendering/client-components))
- Using the [`redirect` function](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#redirect-function) ( [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components))
- Using the native [History API](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#using-the-native-history-api)

This page will go through how to use each of these options, and dive deeper into how navigation works.

## [`<Link>` Component](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#link-component)

`<Link>` is a built-in component that extends the HTML `<a>` tag to provide [prefetching](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#2-prefetching) and client-side navigation between routes. It is the primary and recommended way to navigate between routes in Next.js.

You can use it by importing it from `next/link`, and passing a `href` prop to the component:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return <Link href="/dashboard">Dashboard</Link>
}
```

There are other optional props you can pass to `<Link>`. See the [API reference](https://nextjs.org/docs/app/api-reference/components/link) for more.

## [`useRouter()` hook](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#userouter-hook)

The `useRouter` hook allows you to programmatically change routes from [Client Components](https://nextjs.org/docs/app/building-your-application/rendering/client-components).

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useRouter } from 'next/navigation'

export default function Page() {
  const router = useRouter()

  return (
    <button type="button" onClick={() => router.push('/dashboard')}>
      Dashboard
    </button>
  )
}
```

For a full list of `useRouter` methods, see the [API reference](https://nextjs.org/docs/app/api-reference/functions/use-router).

> **Recommendation:** Use the `<Link>` component to navigate between routes unless you have a specific requirement for using `useRouter`.

## [`redirect` function](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#redirect-function)

For [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components), use the `redirect` function instead.

app/team/\[id\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { redirect } from 'next/navigation'

async function fetchTeam(id: string) {
  const res = await fetch('https://...')
  if (!res.ok) return undefined
  return res.json()
}

export default async function Profile({
  params,
}: {
  params: Promise<{ id: string }>
}) {
  const { id } = await params
  if (!id) {
    redirect('/login')
  }

  const team = await fetchTeam(id)
  if (!team) {
    redirect('/join')
  }

  // ...
}
```

> **Good to know**:
>
> - `redirect` returns a 307 (Temporary Redirect) status code by default. When used in a Server Action, it returns a 303 (See Other), which is commonly used for redirecting to a success page as a result of a POST request.
> - `redirect` internally throws an error so it should be called outside of `try/catch` blocks.
> - `redirect` can be called in Client Components during the rendering process but not in event handlers. You can use the [`useRouter` hook](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#userouter-hook) instead.
> - `redirect` also accepts absolute URLs and can be used to redirect to external links.
> - If you'd like to redirect before the render process, use [`next.config.js`](https://nextjs.org/docs/app/building-your-application/routing/redirecting#redirects-in-nextconfigjs) or [Middleware](https://nextjs.org/docs/app/building-your-application/routing/redirecting#nextresponseredirect-in-middleware).

See the [`redirect` API reference](https://nextjs.org/docs/app/api-reference/functions/redirect) for more information.

## [Using the native History API](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#using-the-native-history-api)

Next.js allows you to use the native [`window.history.pushState`](https://developer.mozilla.org/en-US/docs/Web/API/History/pushState) and [`window.history.replaceState`](https://developer.mozilla.org/en-US/docs/Web/API/History/replaceState) methods to update the browser's history stack without reloading the page.

`pushState` and `replaceState` calls integrate into the Next.js Router, allowing you to sync with [`usePathname`](https://nextjs.org/docs/app/api-reference/functions/use-pathname) and [`useSearchParams`](https://nextjs.org/docs/app/api-reference/functions/use-search-params).

### [`window.history.pushState`](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#windowhistorypushstate)

Use it to add a new entry to the browser's history stack. The user can navigate back to the previous state. For example, to sort a list of products:

```code-block_code__isn_V
'use client'

import { useSearchParams } from 'next/navigation'

export default function SortProducts() {
  const searchParams = useSearchParams()

  function updateSorting(sortOrder: string) {
    const params = new URLSearchParams(searchParams.toString())
    params.set('sort', sortOrder)
    window.history.pushState(null, '', `?${params.toString()}`)
  }

  return (
    <>
      <button onClick={() => updateSorting('asc')}>Sort Ascending</button>
      <button onClick={() => updateSorting('desc')}>Sort Descending</button>
    </>
  )
}
```

### [`window.history.replaceState`](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#windowhistoryreplacestate)

Use it to replace the current entry on the browser's history stack. The user is not able to navigate back to the previous state. For example, to switch the application's locale:

```code-block_code__isn_V
'use client'

import { usePathname } from 'next/navigation'

export function LocaleSwitcher() {
  const pathname = usePathname()

  function switchLocale(locale: string) {
    // e.g. '/en/about' or '/fr/contact'
    const newPath = `/${locale}${pathname}`
    window.history.replaceState(null, '', newPath)
  }

  return (
    <>
      <button onClick={() => switchLocale('en')}>English</button>
      <button onClick={() => switchLocale('fr')}>French</button>
    </>
  )
}
```

## [How Routing and Navigation Works](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#how-routing-and-navigation-works)

The App Router uses a hybrid approach for routing and navigation. On the server, your application code is automatically [code-split](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#1-code-splitting) by route segments. And on the client, Next.js [prefetches](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#2-prefetching) and [caches](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#3-caching) the route segments. This means, when a user navigates to a new route, the browser doesn't reload the page, and only the route segments that change re-render - improving the navigation experience and performance.

### [1\. Code Splitting](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#1-code-splitting)

Code splitting allows you to split your application code into smaller bundles to be downloaded and executed by the browser. This reduces the amount of data transferred and execution time for each request, leading to improved performance.

[Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components) allow your application code to be automatically code-split by route segments. This means only the code needed for the current route is loaded on navigation.

### [2\. Prefetching](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#2-prefetching)

Prefetching is a way to preload a route in the background before the user visits it.

There are two ways routes are prefetched in Next.js:

- **`<Link>` component**: Routes are automatically prefetched as they become visible in the user's viewport. Prefetching happens when the page first loads or when it comes into view through scrolling.
- **`router.prefetch()`**: The `useRouter` hook can be used to prefetch routes programmatically.

The `<Link>`'s default prefetching behavior (i.e. when the `prefetch` prop is left unspecified or set to `null`) is different depending on your usage of [`loading.js`](https://nextjs.org/docs/app/api-reference/file-conventions/loading). Only the shared layout, down the rendered "tree" of components until the first `loading.js` file, is prefetched and cached for `30s`. This reduces the cost of fetching an entire dynamic route, and it means you can show an [instant loading state](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming#instant-loading-states) for better visual feedback to users.

You can disable prefetching by setting the `prefetch` prop to `false`. Alternatively, you can prefetch the full page data beyond the loading boundaries by setting the `prefetch` prop to `true`.

See the [`<Link>` API reference](https://nextjs.org/docs/app/api-reference/components/link) for more information.

> **Good to know**:
>
> - Prefetching is not enabled in development, only in production.

### [3\. Caching](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#3-caching)

Next.js has an **in-memory client-side cache** called the [Router Cache](https://nextjs.org/docs/app/building-your-application/caching#client-side-router-cache). As users navigate around the app, the React Server Component Payload of [prefetched](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#2-prefetching) route segments and visited routes are stored in the cache.

This means on navigation, the cache is reused as much as possible, instead of making a new request to the server - improving performance by reducing the number of requests and data transferred.

Learn more about how the [Router Cache](https://nextjs.org/docs/app/building-your-application/caching#client-side-router-cache) works and how to configure it.

### [4\. Partial Rendering](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#4-partial-rendering)

Partial rendering means only the route segments that change on navigation re-render on the client, and any shared segments are preserved.

For example, when navigating between two sibling routes, `/dashboard/settings` and `/dashboard/analytics`, the `settings` page will be unmounted, the `analytics` page will be mounted with fresh state, and the shared `dashboard` layout will be preserved. This behavior is also present between two routes on the same dynamic segment e.g. with `/blog/[slug]/page` and navigating from `/blog/first` to `/blog/second`.

![How partial rendering works](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fpartial-rendering.png&w=3840&q=75)![How partial rendering works](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fpartial-rendering.png&w=3840&q=75)

Without partial rendering, each navigation would cause the full page to re-render on the client. Rendering only the segment that changes reduces the amount of data transferred and execution time, leading to improved performance.

### [5\. Soft Navigation](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#5-soft-navigation)

Browsers perform a "hard navigation" when navigating between pages. The Next.js App Router enables "soft navigation" between pages, ensuring only the route segments that have changed are re-rendered (partial rendering). This enables client React state to be preserved during navigation.

### [6\. Back and Forward Navigation](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#6-back-and-forward-navigation)

By default, Next.js will maintain the scroll position for backwards and forwards navigation, and re-use route segments in the [Router Cache](https://nextjs.org/docs/app/building-your-application/caching#client-side-router-cache).

### [7\. Routing between `pages/` and `app/`](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating\#7-routing-between-pages-and-app)

When incrementally migrating from `pages/` to `app/`, the Next.js router will automatically handle hard navigation between the two. To detect transitions from `pages/` to `app/`, there is a client router filter that leverages probabilistic checking of app routes, which can occasionally result in false positives. By default, such occurrences should be very rare, as we configure the false positive likelihood to be 0.01%. This likelihood can be customized via the `experimental.clientRouterFilterAllowedRate` option in `next.config.js`. It's important to note that lowering the false positive rate will increase the size of the generated filter in the client bundle.

Alternatively, if you prefer to disable this handling completely and manage the routing between `pages/` and `app/` manually, you can set `experimental.clientRouterFilter` to false in `next.config.js`. When this feature is disabled, any dynamic routes in pages that overlap with app routes won't be navigated to properly by default.

## Next Steps

[**Caching** \\
An overview of caching mechanisms in Next.js.](https://nextjs.org/docs/app/building-your-application/caching) [**TypeScript** \\
Next.js provides a TypeScript-first development experience for building your React application.](https://nextjs.org/docs/app/api-reference/config/typescript)

Was this helpful?

supported.

Send

## Custom Document in Next.js
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/pages/building-your-application) [Routing](https://nextjs.org/docs/pages/building-your-application/routing) Custom Document

# Custom Document

A custom `Document` can update the `<html>` and `<body>` tags used to render a [Page](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts).

To override the default `Document`, create the file `pages/_document` as shown below:

pages/\_document.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Html, Head, Main, NextScript } from 'next/document'

export default function Document() {
  return (
    <Html lang="en">
      <Head />
      <body>
        <Main />
        <NextScript />
      </body>
    </Html>
  )
}
```

> **Good to know**:
>
> - `_document` is only rendered on the server, so event handlers like `onClick` cannot be used in this file.
> - `<Html>`, `<Head />`, `<Main />` and `<NextScript />` are required for the page to be properly rendered.

## [Caveats](https://nextjs.org/docs/pages/building-your-application/routing/custom-document\#caveats)

- The `<Head />` component used in `_document` is not the same as [`next/head`](https://nextjs.org/docs/pages/api-reference/components/head). The `<Head />` component used here should only be used for any `<head>` code that is common for all pages. For all other cases, such as `<title>` tags, we recommend using [`next/head`](https://nextjs.org/docs/pages/api-reference/components/head) in your pages or components.
- React components outside of `<Main />` will not be initialized by the browser. Do _not_ add application logic here or custom CSS (like `styled-jsx`). If you need shared components in all your pages (like a menu or a toolbar), read [Layouts](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts#layout-pattern) instead.
- `Document` currently does not support Next.js [Data Fetching methods](https://nextjs.org/docs/pages/building-your-application/data-fetching) like [`getStaticProps`](https://nextjs.org/docs/pages/building-your-application/data-fetching/get-static-props) or [`getServerSideProps`](https://nextjs.org/docs/pages/building-your-application/data-fetching/get-server-side-props).

## [Customizing `renderPage`](https://nextjs.org/docs/pages/building-your-application/routing/custom-document\#customizing-renderpage)

Customizing `renderPage` is advanced and only needed for libraries like CSS-in-JS to support server-side rendering. This is not needed for built-in `styled-jsx` support.

**We do not recommend using this pattern.** Instead, consider [incrementally adopting](https://nextjs.org/docs/app/building-your-application/upgrading/app-router-migration) the App Router, which allows you to more easily fetch data for [pages and layouts](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates).

pages/\_document.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Document, {
  Html,
  Head,
  Main,
  NextScript,
  DocumentContext,
  DocumentInitialProps,
} from 'next/document'

class MyDocument extends Document {
  static async getInitialProps(
    ctx: DocumentContext
  ): Promise<DocumentInitialProps> {
    const originalRenderPage = ctx.renderPage

    // Run the React rendering logic synchronously
    ctx.renderPage = () =>
      originalRenderPage({
        // Useful for wrapping the whole react tree
        enhanceApp: (App) => App,
        // Useful for wrapping in a per-page basis
        enhanceComponent: (Component) => Component,
      })

    // Run the parent `getInitialProps`, it now includes the custom `renderPage`
    const initialProps = await Document.getInitialProps(ctx)

    return initialProps
  }

  render() {
    return (
      <Html lang="en">
        <Head />
        <body>
          <Main />
          <NextScript />
        </body>
      </Html>
    )
  }
}

export default MyDocument
```

> **Good to know**:
>
> - `getInitialProps` in `_document` is not called during client-side transitions.
> - The `ctx` object for `_document` is equivalent to the one received in [`getInitialProps`](https://nextjs.org/docs/pages/api-reference/functions/get-initial-props#context-object), with the addition of `renderPage`.

Was this helpful?

supported.

Send

## Next.js Link Component
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/pages/api-reference) [Components](https://nextjs.org/docs/pages/api-reference/components) Link

# Link

`<Link>` is a React component that extends the HTML `<a>` element to provide [prefetching](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#2-prefetching) and client-side navigation between routes. It is the primary way to navigate between routes in Next.js.

Basic usage:

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Home() {
  return <Link href="/dashboard">Dashboard</Link>
}
```

## [Reference](https://nextjs.org/docs/pages/api-reference/components/link\#reference)

The following props can be passed to the `<Link>` component:

| Prop | Example | Type | Required |
| --- | --- | --- | --- |
| [`href`](https://nextjs.org/docs/pages/api-reference/components/link#href-required) | `href="/dashboard"` | String or Object | Yes |
| [`replace`](https://nextjs.org/docs/pages/api-reference/components/link#replace) | `replace={false}` | Boolean | - |
| [`scroll`](https://nextjs.org/docs/pages/api-reference/components/link#scroll) | `scroll={false}` | Boolean | - |
| [`prefetch`](https://nextjs.org/docs/pages/api-reference/components/link#prefetch) | `prefetch={false}` | Boolean | - |
| [`legacyBehavior`](https://nextjs.org/docs/pages/api-reference/components/link#legacybehavior) | `legacyBehavior={true}` | Boolean | - |
| [`passHref`](https://nextjs.org/docs/pages/api-reference/components/link#passhref) | `passHref={true}` | Boolean | - |
| [`shallow`](https://nextjs.org/docs/pages/api-reference/components/link#shallow) | `shallow={false}` | Boolean | - |
| [`locale`](https://nextjs.org/docs/pages/api-reference/components/link#locale) | `locale="fr"` | String or Boolean | - |

> **Good to know**: `<a>` tag attributes such as `className` or `target="_blank"` can be added to `<Link>` as props and will be passed to the underlying `<a>` element.

### [`href` (required)](https://nextjs.org/docs/pages/api-reference/components/link\#href-required)

The path or URL to navigate to.

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

// Navigate to /about?name=test
export default function Home() {
  return (
    <Link
      href={{
        pathname: '/about',
        query: { name: 'test' },
      }}
    >
      About
    </Link>
  )
}
```

### [`replace`](https://nextjs.org/docs/pages/api-reference/components/link\#replace)

**Defaults to `false`.** When `true`, `next/link` will replace the current history state instead of adding a new URL into the [browser's history](https://developer.mozilla.org/docs/Web/API/History_API) stack.

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Home() {
  return (
    <Link href="/dashboard" replace>
      Dashboard
    </Link>
  )
}
```

### [`scroll`](https://nextjs.org/docs/pages/api-reference/components/link\#scroll)

**Defaults to `true`.** The default scrolling behavior of `<Link>` in Next.js **is to maintain scroll position**, similar to how browsers handle back and forwards navigation. When you navigate to a new [Page](https://nextjs.org/docs/app/api-reference/file-conventions/page), scroll position will stay the same as long as the Page is visible in the viewport. However, if the Page is not visible in the viewport, Next.js will scroll to the top of the first Page element.

When `scroll = {false}`, Next.js will not attempt to scroll to the first Page element.

> **Good to know**: Next.js checks if `scroll: false` before managing scroll behavior. If scrolling is enabled, it identifies the relevant DOM node for navigation and inspects each top-level element. All non-scrollable elements and those without rendered HTML are bypassed, this includes sticky or fixed positioned elements, and non-visible elements such as those calculated with `getBoundingClientRect`. Next.js then continues through siblings until it identifies a scrollable element that is visible in the viewport.

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Home() {
  return (
    <Link href="/dashboard" scroll={false}>
      Dashboard
    </Link>
  )
}
```

### [`prefetch`](https://nextjs.org/docs/pages/api-reference/components/link\#prefetch)

Prefetching happens when a `<Link />` component enters the user's viewport (initially or through scroll). Next.js prefetches and loads the linked route (denoted by the `href`) and data in the background to improve the performance of client-side navigation's. **Prefetching is only enabled in production**.

The following values can be passed to the `prefetch` prop:

- **`true` (default)**: The full route and its data will be prefetched.
- `false`: Prefetching will not happen when entering the viewport, but will happen on hover. If you want to completely remove fetching on hover as well, consider using an `<a>` tag or [incrementally adopting](https://nextjs.org/docs/app/building-your-application/upgrading/app-router-migration) the App Router, which enables disabling prefetching on hover too.

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Home() {
  return (
    <Link href="/dashboard" prefetch={false}>
      Dashboard
    </Link>
  )
}
```

### [`legacyBehavior`](https://nextjs.org/docs/pages/api-reference/components/link\#legacybehavior)

An `<a>` element is no longer required as a child of `<Link>`. Add the `legacyBehavior` prop to use the legacy behavior or remove the `<a>` to upgrade. A [codemod is available](https://nextjs.org/docs/app/building-your-application/upgrading/codemods#new-link) to automatically upgrade your code.

> **Good to know**: when `legacyBehavior` is not set to `true`, all [`anchor`](https://developer.mozilla.org/docs/Web/HTML/Element/a) tag properties can be passed to `next/link` as well such as, `className`, `onClick`, etc.

### [`passHref`](https://nextjs.org/docs/pages/api-reference/components/link\#passhref)

Forces `Link` to send the `href` property to its child. Defaults to `false`. See the [passing a functional component](https://nextjs.org/docs/pages/api-reference/components/link#nesting-a-functional-component) example for more information.

### [`shallow`](https://nextjs.org/docs/pages/api-reference/components/link\#shallow)

Update the path of the current page without rerunning [`getStaticProps`](https://nextjs.org/docs/pages/building-your-application/data-fetching/get-static-props), [`getServerSideProps`](https://nextjs.org/docs/pages/building-your-application/data-fetching/get-server-side-props) or [`getInitialProps`](https://nextjs.org/docs/pages/api-reference/functions/get-initial-props). Defaults to `false`.

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Home() {
  return (
    <Link href="/dashboard" shallow={false}>
      Dashboard
    </Link>
  )
}
```

### [`locale`](https://nextjs.org/docs/pages/api-reference/components/link\#locale)

The active locale is automatically prepended. `locale` allows for providing a different locale. When `false` `href` has to include the locale as the default behavior is disabled.

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Home() {
  return (
    <>
      {/* Default behavior: locale is prepended */}
      <Link href="/dashboard">Dashboard (with locale)</Link>

      {/* Disable locale prepending */}
      <Link href="/dashboard" locale={false}>
        Dashboard (without locale)
      </Link>

      {/* Specify a different locale */}
      <Link href="/dashboard" locale="fr">
        Dashboard (French)
      </Link>
    </>
  )
}
```

## [Examples](https://nextjs.org/docs/pages/api-reference/components/link\#examples)

The following examples demonstrate how to use the `<Link>` component in different scenarios.

### [Linking to dynamic route segments](https://nextjs.org/docs/pages/api-reference/components/link\#linking-to-dynamic-route-segments)

For [dynamic route segments](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes), it can be handy to use template literals to create the link's path.

For example, you can generate a list of links to the dynamic route `pages/blog/[slug].js`

pages/blog/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

function Posts({ posts }) {
  return (
    <ul>
      {posts.map((post) => (
        <li key={post.id}>
          <Link href={`/blog/${post.slug}`}>{post.title}</Link>
        </li>
      ))}
    </ul>
  )
}
```

### [If the child is a custom component that wraps an `<a>` tag](https://nextjs.org/docs/pages/api-reference/components/link\#if-the-child-is-a-custom-component-that-wraps-an-a-tag)

If the child of `Link` is a custom component that wraps an `<a>` tag, you must add `passHref` to `Link`. This is necessary if you’re using libraries like [styled-components](https://styled-components.com/). Without this, the `<a>` tag will not have the `href` attribute, which hurts your site's accessibility and might affect SEO. If you're using [ESLint](https://nextjs.org/docs/pages/api-reference/config/eslint), there is a built-in rule `next/link-passhref` to ensure correct usage of `passHref`.

components/nav-link.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'
import styled from 'styled-components'

// This creates a custom component that wraps an <a> tag
const RedLink = styled.a`
  color: red;
`

function NavLink({ href, name }) {
  return (
    <Link href={href} passHref legacyBehavior>
      <RedLink>{name}</RedLink>
    </Link>
  )
}

export default NavLink
```

- If you’re using [emotion](https://emotion.sh/)’s JSX pragma feature ( `@jsx jsx`), you must use `passHref` even if you use an `<a>` tag directly.
- The component should support `onClick` property to trigger navigation correctly.

### [Nesting a functional component](https://nextjs.org/docs/pages/api-reference/components/link\#nesting-a-functional-component)

If the child of `Link` is a functional component, in addition to using `passHref` and `legacyBehavior`, you must wrap the component in [`React.forwardRef`](https://react.dev/reference/react/forwardRef):

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'
import React from 'react'

// Define the props type for MyButton
interface MyButtonProps {
  onClick?: React.MouseEventHandler<HTMLAnchorElement>
  href?: string
}

// Use React.ForwardRefRenderFunction to properly type the forwarded ref
const MyButton: React.ForwardRefRenderFunction<
  HTMLAnchorElement,
  MyButtonProps
> = ({ onClick, href }, ref) => {
  return (
    <a href={href} onClick={onClick} ref={ref}>
      Click Me
    </a>
  )
}

// Use React.forwardRef to wrap the component
const ForwardedMyButton = React.forwardRef(MyButton)

export default function Home() {
  return (
    <Link href="/about" passHref legacyBehavior>
      <ForwardedMyButton />
    </Link>
  )
}
```

### [Passing a URL Object](https://nextjs.org/docs/pages/api-reference/components/link\#passing-a-url-object)

`Link` can also receive a URL object and it will automatically format it to create the URL string:

pages/index.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

function Home() {
  return (
    <ul>
      <li>
        <Link
          href={{
            pathname: '/about',
            query: { name: 'test' },
          }}
        >
          About us
        </Link>
      </li>
      <li>
        <Link
          href={{
            pathname: '/blog/[slug]',
            query: { slug: 'my-post' },
          }}
        >
          Blog Post
        </Link>
      </li>
    </ul>
  )
}

export default Home
```

The above example has a link to:

- A predefined route: `/about?name=test`
- A [dynamic route](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes): `/blog/my-post`

You can use every property as defined in the [Node.js URL module documentation](https://nodejs.org/api/url.html#url_url_strings_and_url_objects).

### [Replace the URL instead of push](https://nextjs.org/docs/pages/api-reference/components/link\#replace-the-url-instead-of-push)

The default behavior of the `Link` component is to `push` a new URL into the `history` stack. You can use the `replace` prop to prevent adding a new entry, as in the following example:

pages/index.js

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Home() {
  return (
    <Link href="/about" replace>
      About us
    </Link>
  )
}
```

### [Disable scrolling to the top of the page](https://nextjs.org/docs/pages/api-reference/components/link\#disable-scrolling-to-the-top-of-the-page)

The default behavior of `Link` is to scroll to the top of the page. When there is a hash defined it will scroll to the specific id, like a normal `<a>` tag. To prevent scrolling to the top / hash `scroll={false}` can be added to `Link`:

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Home() {
  return (
    <Link href="/#hashid" scroll={false}>
      Disables scrolling to the top
    </Link>
  )
}
```

### [Prefetching links in Middleware](https://nextjs.org/docs/pages/api-reference/components/link\#prefetching-links-in-middleware)

It's common to use [Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware) for authentication or other purposes that involve rewriting the user to a different page. In order for the `<Link />` component to properly prefetch links with rewrites via Middleware, you need to tell Next.js both the URL to display and the URL to prefetch. This is required to avoid un-necessary fetches to middleware to know the correct route to prefetch.

For example, if you want to serve a `/dashboard` route that has authenticated and visitor views, you can add the following in your Middleware to redirect the user to the correct page:

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextResponse } from 'next/server'

export function middleware(request: Request) {
  const nextUrl = request.nextUrl
  if (nextUrl.pathname === '/dashboard') {
    if (request.cookies.authToken) {
      return NextResponse.rewrite(new URL('/auth/dashboard', request.url))
    } else {
      return NextResponse.rewrite(new URL('/public/dashboard', request.url))
    }
  }
}
```

In this case, you would want to use the following code in your `<Link />` component:

pages/index.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import Link from 'next/link'
import useIsAuthed from './hooks/useIsAuthed' // Your auth hook

export default function Home() {
  const isAuthed = useIsAuthed()
  const path = isAuthed ? '/auth/dashboard' : '/public/dashboard'
  return (
    <Link as="/dashboard" href={path}>
      Dashboard
    </Link>
  )
}
```

> **Good to know**: If you're using [Dynamic Routes](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes), you'll need to adapt your `as` and `href` props. For example, if you have a Dynamic Route like `/dashboard/authed/[user]` that you want to present differently via middleware, you would write: `<Link href={{ pathname: '/dashboard/authed/[user]', query: { user: username } }} as="/dashboard/[user]">Profile</Link>`.

## [Version history](https://nextjs.org/docs/pages/api-reference/components/link\#version-history)

| Version | Changes |
| --- | --- |
| `v13.0.0` | No longer requires a child `<a>` tag. A [codemod](https://nextjs.org/docs/app/building-your-application/upgrading/codemods#remove-a-tags-from-link-components) is provided to automatically update your codebase. |
| `v10.0.0` | `href` props pointing to a dynamic route are automatically resolved and no longer require an `as` prop. |
| `v8.0.0` | Improved prefetching performance. |
| `v1.0.0` | `next/link` introduced. |

Was this helpful?

supported.

Send

## Next.js Route Handlers
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Route Handlers

# Route Handlers

Route Handlers allow you to create custom request handlers for a given route using the Web [Request](https://developer.mozilla.org/docs/Web/API/Request) and [Response](https://developer.mozilla.org/docs/Web/API/Response) APIs.

![Route.js Special File](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Froute-special-file.png&w=3840&q=75)![Route.js Special File](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Froute-special-file.png&w=3840&q=75)

> **Good to know**: Route Handlers are only available inside the `app` directory. They are the equivalent of [API Routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) inside the `pages` directory meaning you **do not** need to use API Routes and Route Handlers together.

## [Convention](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#convention)

Route Handlers are defined in a [`route.js|ts` file](https://nextjs.org/docs/app/api-reference/file-conventions/route) inside the `app` directory:

app/api/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function GET(request: Request) {}
```

Route Handlers can be nested anywhere inside the `app` directory, similar to `page.js` and `layout.js`. But there **cannot** be a `route.js` file at the same route segment level as `page.js`.

### [Supported HTTP Methods](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#supported-http-methods)

The following [HTTP methods](https://developer.mozilla.org/docs/Web/HTTP/Methods) are supported: `GET`, `POST`, `PUT`, `PATCH`, `DELETE`, `HEAD`, and `OPTIONS`. If an unsupported method is called, Next.js will return a `405 Method Not Allowed` response.

### [Extended `NextRequest` and `NextResponse` APIs](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#extended-nextrequest-and-nextresponse-apis)

In addition to supporting the native [Request](https://developer.mozilla.org/docs/Web/API/Request) and [Response](https://developer.mozilla.org/docs/Web/API/Response) APIs, Next.js extends them with [`NextRequest`](https://nextjs.org/docs/app/api-reference/functions/next-request) and [`NextResponse`](https://nextjs.org/docs/app/api-reference/functions/next-response) to provide convenient helpers for advanced use cases.

## [Behavior](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#behavior)

### [Caching](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#caching)

Route Handlers are not cached by default. You can, however, opt into caching for `GET` methods. Other supported HTTP methods are **not** cached. To cache a `GET` method, use a [route config option](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config#dynamic) such as `export const dynamic = 'force-static'` in your Route Handler file.

app/items/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export const dynamic = 'force-static'

export async function GET() {
  const res = await fetch('https://data.mongodb-api.com/...', {
    headers: {
      'Content-Type': 'application/json',
      'API-Key': process.env.DATA_API_KEY,
    },
  })
  const data = await res.json()

  return Response.json({ data })
}
```

> **Good to know**: Other supported HTTP methods are **not** cached, even if they are placed alongside a `GET` method that is cached, in the same file.

### [Special Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#special-route-handlers)

Special Route Handlers like [`sitemap.ts`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/sitemap), [`opengraph-image.tsx`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/opengraph-image), and [`icon.tsx`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/app-icons), and other [metadata files](https://nextjs.org/docs/app/api-reference/file-conventions/metadata) remain static by default unless they use Dynamic APIs or dynamic config options.

### [Route Resolution](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#route-resolution)

You can consider a `route` the lowest level routing primitive.

- They **do not** participate in layouts or client-side navigations like `page`.
- There **cannot** be a `route.js` file at the same route as `page.js`.

| Page | Route | Result |
| --- | --- | --- |
| `app/page.js` | `app/route.js` | Conflict |
| `app/page.js` | `app/api/route.js` | Valid |
| `app/[user]/page.js` | `app/api/route.js` | Valid |

Each `route.js` or `page.js` file takes over all HTTP verbs for that route.

app/page.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Page() {
  return <h1>Hello, Next.js!</h1>
}

// ❌ Conflict
// `app/route.ts`
export async function POST(request: Request) {}
```

## [Examples](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#examples)

The following examples show how to combine Route Handlers with other Next.js APIs and features.

### [Revalidating Cached Data](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#revalidating-cached-data)

You can [revalidate cached data](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration) using Incremental Static Regeneration (ISR):

app/posts/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export const revalidate = 60

export async function GET() {
  const data = await fetch('https://api.vercel.app/blog')
  const posts = await data.json()

  return Response.json(posts)
}
```

### [Cookies](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#cookies)

You can read or set cookies with [`cookies`](https://nextjs.org/docs/app/api-reference/functions/cookies) from `next/headers`. This server function can be called directly in a Route Handler, or nested inside of another function.

Alternatively, you can return a new `Response` using the [`Set-Cookie`](https://developer.mozilla.org/docs/Web/HTTP/Headers/Set-Cookie) header.

app/api/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { cookies } from 'next/headers'

export async function GET(request: Request) {
  const cookieStore = await cookies()
  const token = cookieStore.get('token')

  return new Response('Hello, Next.js!', {
    status: 200,
    headers: { 'Set-Cookie': `token=${token.value}` },
  })
}
```

You can also use the underlying Web APIs to read cookies from the request ( [`NextRequest`](https://nextjs.org/docs/app/api-reference/functions/next-request)):

app/api/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { type NextRequest } from 'next/server'

export async function GET(request: NextRequest) {
  const token = request.cookies.get('token')
}
```

### [Headers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#headers)

You can read headers with [`headers`](https://nextjs.org/docs/app/api-reference/functions/headers) from `next/headers`. This server function can be called directly in a Route Handler, or nested inside of another function.

This `headers` instance is read-only. To set headers, you need to return a new `Response` with new `headers`.

app/api/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { headers } from 'next/headers'

export async function GET(request: Request) {
  const headersList = await headers()
  const referer = headersList.get('referer')

  return new Response('Hello, Next.js!', {
    status: 200,
    headers: { referer: referer },
  })
}
```

You can also use the underlying Web APIs to read headers from the request ( [`NextRequest`](https://nextjs.org/docs/app/api-reference/functions/next-request)):

app/api/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { type NextRequest } from 'next/server'

export async function GET(request: NextRequest) {
  const requestHeaders = new Headers(request.headers)
}
```

### [Redirects](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#redirects)

app/api/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { redirect } from 'next/navigation'

export async function GET(request: Request) {
  redirect('https://nextjs.org/')
}
```

### [Dynamic Route Segments](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#dynamic-route-segments)

Route Handlers can use [Dynamic Segments](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes) to create request handlers from dynamic data.

app/items/\[slug\]/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function GET(
  request: Request,
  { params }: { params: Promise<{ slug: string }> }
) {
  const { slug } = await params // 'a', 'b', or 'c'
}
```

| Route | Example URL | `params` |
| --- | --- | --- |
| `app/items/[slug]/route.js` | `/items/a` | `Promise<{ slug: 'a' }>` |
| `app/items/[slug]/route.js` | `/items/b` | `Promise<{ slug: 'b' }>` |
| `app/items/[slug]/route.js` | `/items/c` | `Promise<{ slug: 'c' }>` |

### [URL Query Parameters](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#url-query-parameters)

The request object passed to the Route Handler is a `NextRequest` instance, which has [some additional convenience methods](https://nextjs.org/docs/app/api-reference/functions/next-request#nexturl), including for more easily handling query parameters.

app/api/search/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { type NextRequest } from 'next/server'

export function GET(request: NextRequest) {
  const searchParams = request.nextUrl.searchParams
  const query = searchParams.get('query')
  // query is "hello" for /api/search?query=hello
}
```

### [Streaming](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#streaming)

Streaming is commonly used in combination with Large Language Models (LLMs), such as OpenAI, for AI-generated content. Learn more about the [AI SDK](https://sdk.vercel.ai/docs/introduction).

app/api/chat/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { openai } from '@ai-sdk/openai'
import { StreamingTextResponse, streamText } from 'ai'

export async function POST(req: Request) {
  const { messages } = await req.json()
  const result = await streamText({
    model: openai('gpt-4-turbo'),
    messages,
  })

  return new StreamingTextResponse(result.toAIStream())
}
```

These abstractions use the Web APIs to create a stream. You can also use the underlying Web APIs directly.

app/api/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
// https://developer.mozilla.org/docs/Web/API/ReadableStream#convert_async_iterator_to_stream
function iteratorToStream(iterator: any) {
  return new ReadableStream({
    async pull(controller) {
      const { value, done } = await iterator.next()

      if (done) {
        controller.close()
      } else {
        controller.enqueue(value)
      }
    },
  })
}

function sleep(time: number) {
  return new Promise((resolve) => {
    setTimeout(resolve, time)
  })
}

const encoder = new TextEncoder()

async function* makeIterator() {
  yield encoder.encode('<p>One</p>')
  await sleep(200)
  yield encoder.encode('<p>Two</p>')
  await sleep(200)
  yield encoder.encode('<p>Three</p>')
}

export async function GET() {
  const iterator = makeIterator()
  const stream = iteratorToStream(iterator)

  return new Response(stream)
}
```

### [Request Body](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#request-body)

You can read the `Request` body using the standard Web API methods:

app/items/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function POST(request: Request) {
  const res = await request.json()
  return Response.json({ res })
}
```

### [Request Body FormData](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#request-body-formdata)

You can read the `FormData` using the `request.formData()` function:

app/items/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function POST(request: Request) {
  const formData = await request.formData()
  const name = formData.get('name')
  const email = formData.get('email')
  return Response.json({ name, email })
}
```

Since `formData` data are all strings, you may want to use [`zod-form-data`](https://www.npmjs.com/zod-form-data) to validate the request and retrieve data in the format you prefer (e.g. `number`).

### [CORS](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#cors)

You can set CORS headers for a specific Route Handler using the standard Web API methods:

app/api/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function GET(request: Request) {
  return new Response('Hello, Next.js!', {
    status: 200,
    headers: {
      'Access-Control-Allow-Origin': '*',
      'Access-Control-Allow-Methods': 'GET, POST, PUT, DELETE, OPTIONS',
      'Access-Control-Allow-Headers': 'Content-Type, Authorization',
    },
  })
}
```

> **Good to know**:
>
> - To add CORS headers to multiple Route Handlers, you can use [Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware#cors) or the [`next.config.js` file](https://nextjs.org/docs/app/api-reference/config/next-config-js/headers#cors).
> - Alternatively, see our [CORS example](https://github.com/vercel/examples/blob/main/edge-functions/cors/lib/cors.ts) package.

### [Webhooks](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#webhooks)

You can use a Route Handler to receive webhooks from third-party services:

app/api/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function POST(request: Request) {
  try {
    const text = await request.text()
    // Process the webhook payload
  } catch (error) {
    return new Response(`Webhook error: ${error.message}`, {
      status: 400,
    })
  }

  return new Response('Success!', {
    status: 200,
  })
}
```

Notably, unlike API Routes with the Pages Router, you do not need to use `bodyParser` to use any additional configuration.

### [Non-UI Responses](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#non-ui-responses)

You can use Route Handlers to return non-UI content. Note that [`sitemap.xml`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/sitemap#generating-a-sitemap-using-code-js-ts), [`robots.txt`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/robots#generate-a-robots-file), [`app icons`](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/app-icons#generate-icons-using-code-js-ts-tsx), and [open graph images](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/opengraph-image) all have built-in support.

app/rss.xml/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function GET() {
  return new Response(
    `<?xml version="1.0" encoding="UTF-8" ?>
<rss version="2.0">

<channel>
  <title>Next.js Documentation</title>
  <link>https://nextjs.org/docs</link>
  <description>The React Framework for the Web</description>
</channel>

</rss>`,
    {
      headers: {
        'Content-Type': 'text/xml',
      },
    }
  )
}
```

### [Segment Config Options](https://nextjs.org/docs/app/building-your-application/routing/route-handlers\#segment-config-options)

Route Handlers use the same [route segment configuration](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config) as pages and layouts.

app/items/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export const dynamic = 'auto'
export const dynamicParams = true
export const revalidate = false
export const fetchCache = 'auto'
export const runtime = 'nodejs'
export const preferredRegion = 'auto'
```

See the [API reference](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config) for more details.

## API Reference

Learn more about the route.js file.

[**route.js** \\
API reference for the route.js special file.](https://nextjs.org/docs/app/api-reference/file-conventions/route)

Was this helpful?

supported.

Send

## Building Next.js Applications
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Introduction](https://nextjs.org/docs) [App Router](https://nextjs.org/docs/app) Building Your Application

# Building Your Application

Next.js provides the building blocks to create flexible, full-stack web applications. The guides in **Building Your Application** explain how to use these features and how to customize your application's behavior.

The sections and pages are organized sequentially, from basic to advanced, so you can follow them step-by-step when building your Next.js application. However, you can read them in any order or skip to the pages that apply to your use case.

If you're new to Next.js, we recommend starting with the [Routing](https://nextjs.org/docs/app/building-your-application/routing), [Rendering](https://nextjs.org/docs/app/building-your-application/rendering), [Data Fetching](https://nextjs.org/docs/app/building-your-application/data-fetching) and [Styling](https://nextjs.org/docs/app/building-your-application/styling) sections, as they introduce the fundamental Next.js and web concepts to help you get started. Then, you can dive deeper into the other sections such as [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) and [Configuring](https://nextjs.org/docs/app/building-your-application/configuring). Finally, once you're ready, checkout the [Deploying](https://nextjs.org/docs/app/building-your-application/deploying) and [Upgrading](https://nextjs.org/docs/app/building-your-application/upgrading) sections.

[**Routing** \\
Learn the fundamentals of routing for front-end applications.](https://nextjs.org/docs/app/building-your-application/routing) [**Data Fetching** \\
Learn how to fetch, cache, revalidate, and mutate data with Next.js.](https://nextjs.org/docs/app/building-your-application/data-fetching) [**Rendering** \\
Learn the differences between Next.js rendering environments, strategies, and runtimes.](https://nextjs.org/docs/app/building-your-application/rendering) [**Caching** \\
An overview of caching mechanisms in Next.js.](https://nextjs.org/docs/app/building-your-application/caching) [**Styling** \\
Learn the different ways you can style your Next.js application.](https://nextjs.org/docs/app/building-your-application/styling) [**Optimizing** \\
Optimize your Next.js application for best performance and user experience.](https://nextjs.org/docs/app/building-your-application/optimizing) [**Configuring** \\
Learn how to configure your Next.js application.](https://nextjs.org/docs/app/building-your-application/configuring) [**Testing** \\
Learn how to set up Next.js with four commonly used testing tools — Cypress, Playwright, Vitest, and Jest.](https://nextjs.org/docs/app/building-your-application/testing) [**Authentication** \\
Learn how to implement authentication in your Next.js application.](https://nextjs.org/docs/app/building-your-application/authentication) [**Deploying** \\
Learn how to deploy your Next.js app to production, either managed or self-hosted.](https://nextjs.org/docs/app/building-your-application/deploying) [**Upgrading** \\
Learn how to upgrade to the latest versions of Next.js.](https://nextjs.org/docs/app/building-your-application/upgrading)

Was this helpful?

supported.

Send

## Client Components Overview
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Rendering](https://nextjs.org/docs/app/building-your-application/rendering) Client Components

# Client Components

Client Components allow you to write interactive UI that is [prerendered on the server](https://github.com/reactwg/server-components/discussions/4) and can use client JavaScript to run in the browser.

This page will go through how Client Components work, how they're rendered, and when you might use them.

## [Benefits of Client Rendering](https://nextjs.org/docs/app/building-your-application/rendering/client-components\#benefits-of-client-rendering)

There are a couple of benefits to doing the rendering work on the client, including:

- **Interactivity**: Client Components can use state, effects, and event listeners, meaning they can provide immediate feedback to the user and update the UI.
- **Browser APIs**: Client Components have access to browser APIs, like [geolocation](https://developer.mozilla.org/docs/Web/API/Geolocation_API) or [localStorage](https://developer.mozilla.org/docs/Web/API/Window/localStorage).

## [Using Client Components in Next.js](https://nextjs.org/docs/app/building-your-application/rendering/client-components\#using-client-components-in-nextjs)

To use Client Components, you can add the React [`"use client"` directive](https://react.dev/reference/react/use-client) at the top of a file, above your imports.

`"use client"` is used to declare a [boundary](https://nextjs.org/docs/app/building-your-application/rendering#network-boundary) between a Server and Client Component modules. This means that by defining a `"use client"` in a file, all other modules imported into it, including child components, are considered part of the client bundle.

app/counter.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useState } from 'react'

export default function Counter() {
  const [count, setCount] = useState(0)

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>Click me</button>
    </div>
  )
}
```

The diagram below shows that using `onClick` and `useState` in a nested component ( `toggle.js`) will cause an error if the `"use client"` directive is not defined. This is because, by default, all components in the App Router are Server Components where these APIs are not available. By defining the `"use client"` directive in `toggle.js`, you can tell React to enter the client boundary where these APIs are available.

![Use Client Directive and Network Boundary](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fuse-client-directive.png&w=3840&q=75)![Use Client Directive and Network Boundary](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fuse-client-directive.png&w=3840&q=75)

> **Defining multiple `use client` entry points**:
>
> You can define multiple "use client" entry points in your React Component tree. This allows you to split your application into multiple client bundles.
>
> However, `"use client"` doesn't need to be defined in every component that needs to be rendered on the client. Once you define the boundary, all child components and modules imported into it are considered part of the client bundle.

## [How are Client Components Rendered?](https://nextjs.org/docs/app/building-your-application/rendering/client-components\#how-are-client-components-rendered)

In Next.js, Client Components are rendered differently depending on whether the request is part of a full page load (an initial visit to your application or a page reload triggered by a browser refresh) or a subsequent navigation.

### [Full page load](https://nextjs.org/docs/app/building-your-application/rendering/client-components\#full-page-load)

To optimize the initial page load, Next.js will use React's APIs to render a static HTML preview on the server for both Client and Server Components. This means, when the user first visits your application, they will see the content of the page immediately, without having to wait for the client to download, parse, and execute the Client Component JavaScript bundle.

On the server:

1. React renders Server Components into a special data format called the [**React Server Component Payload (RSC Payload)**](https://nextjs.org/docs/app/building-your-application/rendering/server-components#what-is-the-react-server-component-payload-rsc), which includes references to Client Components.
2. Next.js uses the RSC Payload and Client Component JavaScript instructions to render **HTML** for the route on the server.

Then, on the client:

1. The HTML is used to immediately show a fast non-interactive initial preview of the route.
2. The React Server Components Payload is used to reconcile the Client and Server Component trees, and update the DOM.
3. The JavaScript instructions are used to [hydrate](https://react.dev/reference/react-dom/client/hydrateRoot) Client Components and make their UI interactive.

> **What is hydration?**
>
> Hydration is the process of attaching event listeners to the DOM, to make the static HTML interactive. Behind the scenes, hydration is done with the [`hydrateRoot`](https://react.dev/reference/react-dom/client/hydrateRoot) React API.

### [Subsequent Navigations](https://nextjs.org/docs/app/building-your-application/rendering/client-components\#subsequent-navigations)

On subsequent navigations, Client Components are rendered entirely on the client, without the server-rendered HTML.

This means the Client Component JavaScript bundle is downloaded and parsed. Once the bundle is ready, React will use the [RSC Payload](https://nextjs.org/docs/app/building-your-application/rendering/server-components#what-is-the-react-server-component-payload-rsc) to reconcile the Client and Server Component trees, and update the DOM.

## [Going back to the Server Environment](https://nextjs.org/docs/app/building-your-application/rendering/client-components\#going-back-to-the-server-environment)

Sometimes, after you've declared the `"use client"` boundary, you may want to go back to the server environment. For example, you may want to reduce the client bundle size, fetch data on the server, or use an API that is only available on the server.

You can keep code on the server even though it's theoretically nested inside Client Components by interleaving Client and Server Components and [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations). See the [Composition Patterns](https://nextjs.org/docs/app/building-your-application/rendering/composition-patterns) page for more information.

Was this helpful?

supported.

Send

## TypeScript in Next.js
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/pages/api-reference) [Configuration](https://nextjs.org/docs/pages/api-reference/config) TypeScript

# TypeScript

Next.js comes with built-in TypeScript, automatically installing the necessary packages and configuring the proper settings when you create a new project with `create-next-app`.

To add TypeScript to an existing project, rename a file to `.ts` / `.tsx`. Run `next dev` and `next build` to automatically install the necessary dependencies and add a `tsconfig.json` file with the recommended config options.

> **Good to know**: If you already have a `jsconfig.json` file, copy the `paths` compiler option from the old `jsconfig.json` into the new `tsconfig.json` file, and delete the old `jsconfig.json` file.

## [Examples](https://nextjs.org/docs/pages/api-reference/config/typescript\#examples)

### [Type checking `next.config.ts`](https://nextjs.org/docs/pages/api-reference/config/typescript\#type-checking-nextconfigts)

You can use TypeScript and import types in your Next.js configuration by using `next.config.ts`.

next.config.ts

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  /* config options here */
}

export default nextConfig
```

> **Good to know**: Module resolution in `next.config.ts` is currently limited to `CommonJS`. This may cause incompatibilities with ESM only packages being loaded in `next.config.ts`.

When using the `next.config.js` file, you can add some type checking in your IDE using JSDoc as below:

next.config.js

```code-block_code__isn_V
// @ts-check

/** @type {import('next').NextConfig} */
const nextConfig = {
  /* config options here */
}

module.exports = nextConfig
```

### [Static Generation and Server-side Rendering](https://nextjs.org/docs/pages/api-reference/config/typescript\#static-generation-and-server-side-rendering)

For [`getStaticProps`](https://nextjs.org/docs/pages/api-reference/functions/get-static-props), [`getStaticPaths`](https://nextjs.org/docs/pages/api-reference/functions/get-static-paths), and [`getServerSideProps`](https://nextjs.org/docs/pages/api-reference/functions/get-server-side-props), you can use the `GetStaticProps`, `GetStaticPaths`, and `GetServerSideProps` types respectively:

pages/blog/\[slug\].tsx

```code-block_code__isn_V
import type { GetStaticProps, GetStaticPaths, GetServerSideProps } from 'next'

export const getStaticProps = (async (context) => {
  // ...
}) satisfies GetStaticProps

export const getStaticPaths = (async () => {
  // ...
}) satisfies GetStaticPaths

export const getServerSideProps = (async (context) => {
  // ...
}) satisfies GetServerSideProps
```

> **Good to know:** `satisfies` was added to TypeScript in [4.9](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-4-9.html). We recommend upgrading to the latest version of TypeScript.

### [With API Routes](https://nextjs.org/docs/pages/api-reference/config/typescript\#with-api-routes)

The following is an example of how to use the built-in types for API routes:

pages/api/hello.ts

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

export default function handler(req: NextApiRequest, res: NextApiResponse) {
  res.status(200).json({ name: 'John Doe' })
}
```

You can also type the response data:

pages/api/hello.ts

```code-block_code__isn_V
import type { NextApiRequest, NextApiResponse } from 'next'

type Data = {
  name: string
}

export default function handler(
  req: NextApiRequest,
  res: NextApiResponse<Data>
) {
  res.status(200).json({ name: 'John Doe' })
}
```

### [With custom `App`](https://nextjs.org/docs/pages/api-reference/config/typescript\#with-custom-app)

If you have a [custom `App`](https://nextjs.org/docs/pages/building-your-application/routing/custom-app), you can use the built-in type `AppProps` and change file name to `./pages/_app.tsx` like so:

```code-block_code__isn_V
import type { AppProps } from 'next/app'

export default function MyApp({ Component, pageProps }: AppProps) {
  return <Component {...pageProps} />
}
```

### [Incremental type checking](https://nextjs.org/docs/pages/api-reference/config/typescript\#incremental-type-checking)

Since `v10.2.1` Next.js supports [incremental type checking](https://www.typescriptlang.org/tsconfig#incremental) when enabled in your `tsconfig.json`, this can help speed up type checking in larger applications.

### [Disabling TypeScript errors in production](https://nextjs.org/docs/pages/api-reference/config/typescript\#disabling-typescript-errors-in-production)

Next.js fails your **production build** ( `next build`) when TypeScript errors are present in your project.

If you'd like Next.js to dangerously produce production code even when your application has errors, you can disable the built-in type checking step.

If disabled, be sure you are running type checks as part of your build or deploy process, otherwise this can be very dangerous.

Open `next.config.ts` and enable the `ignoreBuildErrors` option in the `typescript` config:

next.config.ts

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  typescript: {
    // !! WARN !!
    // Dangerously allow production builds to successfully complete even if
    // your project has type errors.
    // !! WARN !!
    ignoreBuildErrors: true,
  },
}

export default nextConfig
```

> **Good to know**: You can run `tsc --noEmit` to check for TypeScript errors yourself before building. This is useful for CI/CD pipelines where you'd like to check for TypeScript errors before deploying.

### [Custom type declarations](https://nextjs.org/docs/pages/api-reference/config/typescript\#custom-type-declarations)

When you need to declare custom types, you might be tempted to modify `next-env.d.ts`. However, this file is automatically generated, so any changes you make will be overwritten. Instead, you should create a new file, let's call it `new-types.d.ts`, and reference it in your `tsconfig.json`:

tsconfig.json

```code-block_code__isn_V
{
  "compilerOptions": {
    "skipLibCheck": true
    //...truncated...
  },
  "include": [\
    "new-types.d.ts",\
    "next-env.d.ts",\
    ".next/types/**/*.ts",\
    "**/*.ts",\
    "**/*.tsx"\
  ],
  "exclude": ["node_modules"]
}
```

## [Version Changes](https://nextjs.org/docs/pages/api-reference/config/typescript\#version-changes)

| Version | Changes |
| --- | --- |
| `v15.0.0` | [`next.config.ts`](https://nextjs.org/docs/pages/api-reference/config/typescript#type-checking-nextconfigts) support added for TypeScript projects. |
| `v13.2.0` | Statically typed links are available in beta. |
| `v12.0.0` | [SWC](https://nextjs.org/docs/architecture/nextjs-compiler) is now used by default to compile TypeScript and TSX for faster builds. |
| `v10.2.1` | [Incremental type checking](https://www.typescriptlang.org/tsconfig#incremental) support added when enabled in your `tsconfig.json`. |

Was this helpful?

supported.

Send

## Next.js Image Component
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/pages/api-reference) [Components](https://nextjs.org/docs/pages/api-reference/components) Image

# Image

Examples

- [Image Component](https://github.com/vercel/next.js/tree/canary/examples/image-component)

> **Good to know**: If you are using a version of Next.js prior to 13, you'll want to use the [next/legacy/image](https://nextjs.org/docs/pages/api-reference/components/image-legacy) documentation since the component was renamed.

This API reference will help you understand how to use [props](https://nextjs.org/docs/pages/api-reference/components/image#props) and [configuration options](https://nextjs.org/docs/pages/api-reference/components/image#configuration-options) available for the Image Component. For features and usage, please see the [Image Component](https://nextjs.org/docs/app/building-your-application/optimizing/images) page.

app/page.js

```code-block_code__isn_V
import Image from 'next/image'

export default function Page() {
  return (
    <Image
      src="/profile.png"
      width={500}
      height={500}
      alt="Picture of the author"
    />
  )
}
```

## [Props](https://nextjs.org/docs/pages/api-reference/components/image\#props)

Here's a summary of the props available for the Image Component:

| Prop | Example | Type | Status |
| --- | --- | --- | --- |
| [`src`](https://nextjs.org/docs/pages/api-reference/components/image#src) | `src="/profile.png"` | String | Required |
| [`width`](https://nextjs.org/docs/pages/api-reference/components/image#width) | `width={500}` | Integer (px) | Required |
| [`height`](https://nextjs.org/docs/pages/api-reference/components/image#height) | `height={500}` | Integer (px) | Required |
| [`alt`](https://nextjs.org/docs/pages/api-reference/components/image#alt) | `alt="Picture of the author"` | String | Required |
| [`loader`](https://nextjs.org/docs/pages/api-reference/components/image#loader) | `loader={imageLoader}` | Function | - |
| [`fill`](https://nextjs.org/docs/pages/api-reference/components/image#fill) | `fill={true}` | Boolean | - |
| [`sizes`](https://nextjs.org/docs/pages/api-reference/components/image#sizes) | `sizes="(max-width: 768px) 100vw, 33vw"` | String | - |
| [`quality`](https://nextjs.org/docs/pages/api-reference/components/image#quality) | `quality={80}` | Integer (1-100) | - |
| [`priority`](https://nextjs.org/docs/pages/api-reference/components/image#priority) | `priority={true}` | Boolean | - |
| [`placeholder`](https://nextjs.org/docs/pages/api-reference/components/image#placeholder) | `placeholder="blur"` | String | - |
| [`style`](https://nextjs.org/docs/pages/api-reference/components/image#style) | `style={{objectFit: "contain"}}` | Object | - |
| [`onLoadingComplete`](https://nextjs.org/docs/pages/api-reference/components/image#onloadingcomplete) | `onLoadingComplete={img => done())}` | Function | Deprecated |
| [`onLoad`](https://nextjs.org/docs/pages/api-reference/components/image#onload) | `onLoad={event => done())}` | Function | - |
| [`onError`](https://nextjs.org/docs/pages/api-reference/components/image#onerror) | `onError(event => fail()}` | Function | - |
| [`loading`](https://nextjs.org/docs/pages/api-reference/components/image#loading) | `loading="lazy"` | String | - |
| [`blurDataURL`](https://nextjs.org/docs/pages/api-reference/components/image#blurdataurl) | `blurDataURL="data:image/jpeg..."` | String | - |
| [`overrideSrc`](https://nextjs.org/docs/pages/api-reference/components/image#overridesrc) | `overrideSrc="/seo.png"` | String | - |

## [Required Props](https://nextjs.org/docs/pages/api-reference/components/image\#required-props)

The Image Component requires the following properties: `src`, `alt`, `width` and `height` (or `fill`).

app/page.js

```code-block_code__isn_V
import Image from 'next/image'

export default function Page() {
  return (
    <div>
      <Image
        src="/profile.png"
        width={500}
        height={500}
        alt="Picture of the author"
      />
    </div>
  )
}
```

### [`src`](https://nextjs.org/docs/pages/api-reference/components/image\#src)

Must be one of the following:

- A [statically imported](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images) image file
- A path string. This can be either an absolute external URL, or an internal path depending on the [loader](https://nextjs.org/docs/pages/api-reference/components/image#loader) prop.

When using the default [loader](https://nextjs.org/docs/pages/api-reference/components/image#loader), also consider the following for source images:

- When src is an external URL, you must also configure [remotePatterns](https://nextjs.org/docs/pages/api-reference/components/image#remotepatterns)
- When src is [animated](https://nextjs.org/docs/pages/api-reference/components/image#animated-images) or not a known format (JPEG, PNG, WebP, AVIF, GIF, TIFF) the image will be served as-is
- When src is SVG format, it will be blocked unless [`unoptimized`](https://nextjs.org/docs/pages/api-reference/components/image#unoptimized) or [`dangerouslyAllowSVG`](https://nextjs.org/docs/pages/api-reference/components/image#dangerouslyallowsvg) is enabled

### [`width`](https://nextjs.org/docs/pages/api-reference/components/image\#width)

The `width` property represents the _intrinsic_ image width in pixels. This property is used to infer the correct aspect ratio of the image and avoid layout shift during loading. It does not determine the rendered size of the image, which is controlled by CSS, similar to the `width` attribute in the HTML `<img>` tag.

Required, except for [statically imported images](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images) or images with the [`fill` property](https://nextjs.org/docs/pages/api-reference/components/image#fill).

### [`height`](https://nextjs.org/docs/pages/api-reference/components/image\#height)

The `height` property represents the _intrinsic_ image height in pixels. This property is used to infer the correct aspect ratio of the image and avoid layout shift during loading. It does not determine the rendered size of the image, which is controlled by CSS, similar to the `height` attribute in the HTML `<img>` tag.

Required, except for [statically imported images](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images) or images with the [`fill` property](https://nextjs.org/docs/pages/api-reference/components/image#fill).

> **Good to know:**
>
> - Combined, both `width` and `height` properties are used to determine the aspect ratio of the image which used by browsers to reserve space for the image before it loads.
> - The intrinsic size does not always mean the rendered size in the browser, which will be determined by the parent container. For example, if the parent container is smaller than the intrinsic size, the image will be scaled down to fit the container.
> - You can use the [`fill`](https://nextjs.org/docs/pages/api-reference/components/image#fill) property when the width and height are unknown.

### [`alt`](https://nextjs.org/docs/pages/api-reference/components/image\#alt)

The `alt` property is used to describe the image for screen readers and search engines. It is also the fallback text if images have been disabled or an error occurs while loading the image.

It should contain text that could replace the image [without changing the meaning of the page](https://html.spec.whatwg.org/multipage/images.html#general-guidelines). It is not meant to supplement the image and should not repeat information that is already provided in the captions above or below the image.

If the image is [purely decorative](https://html.spec.whatwg.org/multipage/images.html#a-purely-decorative-image-that-doesn't-add-any-information) or [not intended for the user](https://html.spec.whatwg.org/multipage/images.html#an-image-not-intended-for-the-user), the `alt` property should be an empty string ( `alt=""`).

[Learn more](https://html.spec.whatwg.org/multipage/images.html#alt)

## [Optional Props](https://nextjs.org/docs/pages/api-reference/components/image\#optional-props)

The `<Image />` component accepts a number of additional properties beyond those which are required. This section describes the most commonly-used properties of the Image component. Find details about more rarely-used properties in the [Advanced Props](https://nextjs.org/docs/pages/api-reference/components/image#advanced-props) section.

### [`loader`](https://nextjs.org/docs/pages/api-reference/components/image\#loader)

A custom function used to resolve image URLs.

A `loader` is a function returning a URL string for the image, given the following parameters:

- [`src`](https://nextjs.org/docs/pages/api-reference/components/image#src)
- [`width`](https://nextjs.org/docs/pages/api-reference/components/image#width)
- [`quality`](https://nextjs.org/docs/pages/api-reference/components/image#quality)

Here is an example of using a custom loader:

```code-block_code__isn_V
import Image from 'next/image'

const imageLoader = ({ src, width, quality }) => {
  return `https://example.com/${src}?w=${width}&q=${quality || 75}`
}

export default function Page() {
  return (
    <Image
      loader={imageLoader}
      src="me.png"
      alt="Picture of the author"
      width={500}
      height={500}
    />
  )
}
```

Alternatively, you can use the [loaderFile](https://nextjs.org/docs/pages/api-reference/components/image#loaderfile) configuration in `next.config.js` to configure every instance of `next/image` in your application, without passing a prop.

### [`fill`](https://nextjs.org/docs/pages/api-reference/components/image\#fill)

```code-block_code__isn_V
fill={true} // {true} | {false}
```

A boolean that causes the image to fill the parent element, which is useful when the [`width`](https://nextjs.org/docs/pages/api-reference/components/image#width) and [`height`](https://nextjs.org/docs/pages/api-reference/components/image#height) are unknown.

The parent element _must_ assign `position: "relative"`, `position: "fixed"`, or `position: "absolute"` style.

By default, the img element will automatically be assigned the `position: "absolute"` style.

If no styles are applied to the image, the image will stretch to fit the container. You may prefer to set `object-fit: "contain"` for an image which is letterboxed to fit the container and preserve aspect ratio.

Alternatively, `object-fit: "cover"` will cause the image to fill the entire container and be cropped to preserve aspect ratio.

For more information, see also:

- [`position`](https://developer.mozilla.org/docs/Web/CSS/position)
- [`object-fit`](https://developer.mozilla.org/docs/Web/CSS/object-fit)
- [`object-position`](https://developer.mozilla.org/docs/Web/CSS/object-position)

### [`sizes`](https://nextjs.org/docs/pages/api-reference/components/image\#sizes)

A string, similar to a media query, that provides information about how wide the image will be at different breakpoints. The value of `sizes` will greatly affect performance for images using [`fill`](https://nextjs.org/docs/pages/api-reference/components/image#fill) or which are [styled to have a responsive size](https://nextjs.org/docs/pages/api-reference/components/image#responsive-images).

The `sizes` property serves two important purposes related to image performance:

- First, the value of `sizes` is used by the browser to determine which size of the image to download, from `next/image`'s automatically generated `srcset`. When the browser chooses, it does not yet know the size of the image on the page, so it selects an image that is the same size or larger than the viewport. The `sizes` property allows you to tell the browser that the image will actually be smaller than full screen. If you don't specify a `sizes` value in an image with the `fill` property, a default value of `100vw` (full screen width) is used.
- Second, the `sizes` property changes the behavior of the automatically generated `srcset` value. If no `sizes` value is present, a small `srcset` is generated, suitable for a fixed-size image (1x/2x/etc). If `sizes` is defined, a large `srcset` is generated, suitable for a responsive image (640w/750w/etc). If the `sizes` property includes sizes such as `50vw`, which represent a percentage of the viewport width, then the `srcset` is trimmed to not include any values which are too small to ever be necessary.

For example, if you know your styling will cause an image to be full-width on mobile devices, in a 2-column layout on tablets, and a 3-column layout on desktop displays, you should include a sizes property such as the following:

```code-block_code__isn_V
import Image from 'next/image'

export default function Page() {
  return (
    <div className="grid-element">
      <Image
        fill
        src="/example.png"
        sizes="(max-width: 768px) 100vw, (max-width: 1200px) 50vw, 33vw"
      />
    </div>
  )
}
```

This example `sizes` could have a dramatic effect on performance metrics. Without the `33vw` sizes, the image selected from the server would be 3 times as wide as it needs to be. Because file size is proportional to the square of the width, without `sizes` the user would download an image that's 9 times larger than necessary.

Learn more about `srcset` and `sizes`:

- [web.dev](https://web.dev/learn/design/responsive-images/#sizes)
- [mdn](https://developer.mozilla.org/docs/Web/HTML/Element/img#sizes)

### [`quality`](https://nextjs.org/docs/pages/api-reference/components/image\#quality)

```code-block_code__isn_V
quality={75} // {number 1-100}
```

The quality of the optimized image, an integer between `1` and `100`, where `100` is the best quality and therefore largest file size. Defaults to `75`.

If the [`qualities`](https://nextjs.org/docs/pages/api-reference/components/image#qualities) configuration is defined in `next.config.js`, the `quality` prop must match one of the values defined in the configuration.

> **Good to know**: If the original source image was already low quality, setting the quality prop too high could cause the resulting optimized image to be larger than the original source image.

### [`priority`](https://nextjs.org/docs/pages/api-reference/components/image\#priority)

```code-block_code__isn_V
priority={false} // {false} | {true}
```

When true, Next.js will
[preload](https://web.dev/preload-responsive-images/) the image. Lazy loading is automatically disabled for images using `priority`. If the [`loading`](https://nextjs.org/docs/pages/api-reference/components/image#loading) property is also used and set to `lazy`, the `priority` property can't be used. The [`loading`](https://nextjs.org/docs/pages/api-reference/components/image#loading) property is only meant for advanced use cases. Remove `loading` when `priority` is needed.

You should use the `priority` property on any image detected as the [Largest Contentful Paint (LCP)](https://nextjs.org/learn/seo/web-performance/lcp) element. It may be appropriate to have multiple priority images, as different images may be the LCP element for different viewport sizes.

Should only be used when the image is visible above the fold. Defaults to `false`.

### [`placeholder`](https://nextjs.org/docs/pages/api-reference/components/image\#placeholder)

```code-block_code__isn_V
placeholder = 'empty' // "empty" | "blur" | "data:image/..."
```

A placeholder to use while the image is loading. Possible values are `blur`, `empty`, or `data:image/...`. Defaults to `empty`.

When `blur`, the [`blurDataURL`](https://nextjs.org/docs/pages/api-reference/components/image#blurdataurl) property will be used as the placeholder. If `src` is an object from a [static import](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images) and the imported image is `.jpg`, `.png`, `.webp`, or `.avif`, then `blurDataURL` will be automatically populated, except when the image is detected to be animated.

For dynamic images, you must provide the [`blurDataURL`](https://nextjs.org/docs/pages/api-reference/components/image#blurdataurl) property. Solutions such as [Plaiceholder](https://github.com/joe-bell/plaiceholder) can help with `base64` generation.

When `data:image/...`, the [Data URL](https://developer.mozilla.org/docs/Web/HTTP/Basics_of_HTTP/Data_URIs) will be used as the placeholder while the image is loading.

When `empty`, there will be no placeholder while the image is loading, only empty space.

Try it out:

- [Demo the `blur` placeholder](https://image-component.nextjs.gallery/placeholder)
- [Demo the shimmer effect with data URL `placeholder` prop](https://image-component.nextjs.gallery/shimmer)
- [Demo the color effect with `blurDataURL` prop](https://image-component.nextjs.gallery/color)

## [Advanced Props](https://nextjs.org/docs/pages/api-reference/components/image\#advanced-props)

In some cases, you may need more advanced usage. The `<Image />` component optionally accepts the following advanced properties.

### [`style`](https://nextjs.org/docs/pages/api-reference/components/image\#style)

Allows passing CSS styles to the underlying image element.

components/ProfileImage.js

```code-block_code__isn_V
const imageStyle = {
  borderRadius: '50%',
  border: '1px solid #fff',
}

export default function ProfileImage() {
  return <Image src="..." style={imageStyle} />
}
```

Remember that the required width and height props can interact with your styling. If you use styling to modify an image's width, you should also style its height to `auto` to preserve its intrinsic aspect ratio, or your image will be distorted.

### [`onLoadingComplete`](https://nextjs.org/docs/pages/api-reference/components/image\#onloadingcomplete)

```code-block_code__isn_V
<Image onLoadingComplete={(img) => console.log(img.naturalWidth)} />
```

> **Warning**: Deprecated since Next.js 14 in favor of [`onLoad`](https://nextjs.org/docs/pages/api-reference/components/image#onload).

A callback function that is invoked once the image is completely loaded and the [placeholder](https://nextjs.org/docs/pages/api-reference/components/image#placeholder) has been removed.

The callback function will be called with one argument, a reference to the underlying `<img>` element.

### [`onLoad`](https://nextjs.org/docs/pages/api-reference/components/image\#onload)

```code-block_code__isn_V
<Image onLoad={(e) => console.log(e.target.naturalWidth)} />
```

A callback function that is invoked once the image is completely loaded and the [placeholder](https://nextjs.org/docs/pages/api-reference/components/image#placeholder) has been removed.

The callback function will be called with one argument, the Event which has a `target` that references the underlying `<img>` element.

### [`onError`](https://nextjs.org/docs/pages/api-reference/components/image\#onerror)

```code-block_code__isn_V
<Image onError={(e) => console.error(e.target.id)} />
```

A callback function that is invoked if the image fails to load.

### [`loading`](https://nextjs.org/docs/pages/api-reference/components/image\#loading)

```code-block_code__isn_V
loading = 'lazy' // {lazy} | {eager}
```

The loading behavior of the image. Defaults to `lazy`.

When `lazy`, defer loading the image until it reaches a calculated distance from
the viewport.

When `eager`, load the image immediately.

Learn more about the [`loading` attribute](https://developer.mozilla.org/docs/Web/HTML/Element/img#loading).

### [`blurDataURL`](https://nextjs.org/docs/pages/api-reference/components/image\#blurdataurl)

A [Data URL](https://developer.mozilla.org/docs/Web/HTTP/Basics_of_HTTP/Data_URIs) to
be used as a placeholder image before the `src` image successfully loads. Only takes effect when combined
with [`placeholder="blur"`](https://nextjs.org/docs/pages/api-reference/components/image#placeholder).

Must be a base64-encoded image. It will be enlarged and blurred, so a very small image (10px or
less) is recommended. Including larger images as placeholders may harm your application performance.

Try it out:

- [Demo the default `blurDataURL` prop](https://image-component.nextjs.gallery/placeholder)
- [Demo the color effect with `blurDataURL` prop](https://image-component.nextjs.gallery/color)

You can also [generate a solid color Data URL](https://png-pixel.com/) to match the image.

### [`unoptimized`](https://nextjs.org/docs/pages/api-reference/components/image\#unoptimized)

```code-block_code__isn_V
unoptimized = {false} // {false} | {true}
```

When true, the source image will be served as-is from the `src` instead of changing quality, size, or format. Defaults to `false`.

This is useful for images that do not benefit from optimization such as small images (less than 1KB), vector images (SVG), or animated images (GIF).

```code-block_code__isn_V
import Image from 'next/image'

const UnoptimizedImage = (props) => {
  return <Image {...props} unoptimized />
}
```

Since Next.js 12.3.0, this prop can be assigned to all images by updating `next.config.js` with the following configuration:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    unoptimized: true,
  },
}
```

### [`overrideSrc`](https://nextjs.org/docs/pages/api-reference/components/image\#overridesrc)

When providing the `src` prop to the `<Image>` component, both the `srcset` and `src` attributes are generated automatically for the resulting `<img>`.

input.js

```code-block_code__isn_V
<Image src="/me.jpg" />
```

output.html

```code-block_code__isn_V
<img
  srcset="
    /_next/image?url=%2Fme.jpg&w=640&q=75 1x,
    /_next/image?url=%2Fme.jpg&w=828&q=75 2x
  "
  src="/_next/image?url=%2Fme.jpg&w=828&q=75"
/>
```

In some cases, it is not desirable to have the `src` attribute generated and you may wish to override it using the `overrideSrc` prop.

For example, when upgrading an existing website from `<img>` to `<Image>`, you may wish to maintain the same `src` attribute for SEO purposes such as image ranking or avoiding recrawl.

input.js

```code-block_code__isn_V
<Image src="/me.jpg" overrideSrc="/override.jpg" />
```

output.html

```code-block_code__isn_V
<img
  srcset="
    /_next/image?url=%2Fme.jpg&w=640&q=75 1x,
    /_next/image?url=%2Fme.jpg&w=828&q=75 2x
  "
  src="/override.jpg"
/>
```

### [decoding](https://nextjs.org/docs/pages/api-reference/components/image\#decoding)

A hint to the browser indicating if it should wait for the image to be decoded before presenting other content updates or not. Defaults to `async`.

Possible values are the following:

- `async` \- Asynchronously decode the image and allow other content to be rendered before it completes.
- `sync` \- Synchronously decode the image for atomic presentation with other content.
- `auto` \- No preference for the decoding mode; the browser decides what's best.

Learn more about the [`decoding` attribute](https://developer.mozilla.org/docs/Web/HTML/Element/img#decoding).

### [Other Props](https://nextjs.org/docs/pages/api-reference/components/image\#other-props)

Other properties on the `<Image />` component will be passed to the underlying
`img` element with the exception of the following:

- `srcSet`. Use [Device Sizes](https://nextjs.org/docs/pages/api-reference/components/image#devicesizes) instead.

## [Configuration Options](https://nextjs.org/docs/pages/api-reference/components/image\#configuration-options)

In addition to props, you can configure the Image Component in `next.config.js`. The following options are available:

### [`localPatterns`](https://nextjs.org/docs/pages/api-reference/components/image\#localpatterns)

You can optionally configure `localPatterns` in your `next.config.js` file in order to allow specific paths to be optimized and block all others paths.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    localPatterns: [\
      {\
        pathname: '/assets/images/**',\
        search: '',\
      },\
    ],
  },
}
```

> **Good to know**: The example above will ensure the `src` property of `next/image` must start with `/assets/images/` and must not have a query string. Attempting to optimize any other path will respond with 400 Bad Request.

### [`remotePatterns`](https://nextjs.org/docs/pages/api-reference/components/image\#remotepatterns)

To protect your application from malicious users, configuration is required in order to use external images. This ensures that only external images from your account can be served from the Next.js Image Optimization API. These external images can be configured with the `remotePatterns` property in your `next.config.js` file, as shown below:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    remotePatterns: [\
      {\
        protocol: 'https',\
        hostname: 'example.com',\
        port: '',\
        pathname: '/account123/**',\
        search: '',\
      },\
    ],
  },
}
```

> **Good to know**: The example above will ensure the `src` property of `next/image` must start with `https://example.com/account123/` and must not have a query string. Any other protocol, hostname, port, or unmatched path will respond with 400 Bad Request.

Below is an example of the `remotePatterns` property in the `next.config.js` file using a wildcard pattern in the `hostname`:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    remotePatterns: [\
      {\
        protocol: 'https',\
        hostname: '**.example.com',\
        port: '',\
        search: '',\
      },\
    ],
  },
}
```

> **Good to know**: The example above will ensure the `src` property of `next/image` must start with `https://img1.example.com` or `https://me.avatar.example.com` or any number of subdomains. It cannot have a port or query string. Any other protocol or unmatched hostname will respond with 400 Bad Request.

Wildcard patterns can be used for both `pathname` and `hostname` and have the following syntax:

- `*` match a single path segment or subdomain
- `**` match any number of path segments at the end or subdomains at the beginning

The `**` syntax does not work in the middle of the pattern.

> **Good to know**: When omitting `protocol`, `port`, `pathname`, or `search` then the wildcard `**` is implied. This is not recommended because it may allow malicious actors to optimize urls you did not intend.

Below is an example of the `remotePatterns` property in the `next.config.js` file using `search`:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    remotePatterns: [\
      {\
        protocol: 'https',\
        hostname: 'assets.example.com',\
        search: '?v=1727111025337',\
      },\
    ],
  },
}
```

> **Good to know**: The example above will ensure the `src` property of `next/image` must start with `https://assets.example.com` and must have the exact query string `?v=1727111025337`. Any other protocol or query string will respond with 400 Bad Request.

### [`domains`](https://nextjs.org/docs/pages/api-reference/components/image\#domains)

> **Warning**: Deprecated since Next.js 14 in favor of strict [`remotePatterns`](https://nextjs.org/docs/pages/api-reference/components/image#remotepatterns) in order to protect your application from malicious users. Only use `domains` if you own all the content served from the domain.

Similar to [`remotePatterns`](https://nextjs.org/docs/pages/api-reference/components/image#remotepatterns), the `domains` configuration can be used to provide a list of allowed hostnames for external images.

However, the `domains` configuration does not support wildcard pattern matching and it cannot restrict protocol, port, or pathname.

Below is an example of the `domains` property in the `next.config.js` file:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    domains: ['assets.acme.com'],
  },
}
```

### [`loaderFile`](https://nextjs.org/docs/pages/api-reference/components/image\#loaderfile)

If you want to use a cloud provider to optimize images instead of using the Next.js built-in Image Optimization API, you can configure the `loaderFile` in your `next.config.js` like the following:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    loader: 'custom',
    loaderFile: './my/image/loader.js',
  },
}
```

This must point to a file relative to the root of your Next.js application. The file must export a default function that returns a string, for example:

my/image/loader.js

```code-block_code__isn_V
export default function myImageLoader({ src, width, quality }) {
  return `https://example.com/${src}?w=${width}&q=${quality || 75}`
}
```

Alternatively, you can use the [`loader` prop](https://nextjs.org/docs/pages/api-reference/components/image#loader) to configure each instance of `next/image`.

Examples:

- [Custom Image Loader Configuration](https://nextjs.org/docs/app/api-reference/config/next-config-js/images#example-loader-configuration)

## [Advanced](https://nextjs.org/docs/pages/api-reference/components/image\#advanced)

The following configuration is for advanced use cases and is usually not necessary. If you choose to configure the properties below, you will override any changes to the Next.js defaults in future updates.

### [`deviceSizes`](https://nextjs.org/docs/pages/api-reference/components/image\#devicesizes)

If you know the expected device widths of your users, you can specify a list of device width breakpoints using the `deviceSizes` property in `next.config.js`. These widths are used when the `next/image` component uses [`sizes`](https://nextjs.org/docs/pages/api-reference/components/image#sizes) prop to ensure the correct image is served for user's device.

If no configuration is provided, the default below is used.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    deviceSizes: [640, 750, 828, 1080, 1200, 1920, 2048, 3840],
  },
}
```

### [`imageSizes`](https://nextjs.org/docs/pages/api-reference/components/image\#imagesizes)

You can specify a list of image widths using the `images.imageSizes` property in your `next.config.js` file. These widths are concatenated with the array of [device sizes](https://nextjs.org/docs/pages/api-reference/components/image#devicesizes) to form the full array of sizes used to generate image [srcset](https://developer.mozilla.org/docs/Web/API/HTMLImageElement/srcset) s.

The reason there are two separate lists is that imageSizes is only used for images which provide a [`sizes`](https://nextjs.org/docs/pages/api-reference/components/image#sizes) prop, which indicates that the image is less than the full width of the screen. **Therefore, the sizes in imageSizes should all be smaller than the smallest size in deviceSizes.**

If no configuration is provided, the default below is used.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    imageSizes: [16, 32, 48, 64, 96, 128, 256, 384],
  },
}
```

### [`qualities`](https://nextjs.org/docs/pages/api-reference/components/image\#qualities)

The default [Image Optimization API](https://nextjs.org/docs/pages/api-reference/components/image#loader) will automatically allow all qualities from 1 to 100. If you wish to restrict the allowed qualities, you can add configuration to `next.config.js`.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    qualities: [25, 50, 75],
  },
}
```

In this example above, only three qualities are allowed: 25, 50, and 75. If the [`quality`](https://nextjs.org/docs/pages/api-reference/components/image#quality) prop does not match a value in this array, the image will fail with 400 Bad Request.

### [`formats`](https://nextjs.org/docs/pages/api-reference/components/image\#formats)

The default [Image Optimization API](https://nextjs.org/docs/pages/api-reference/components/image#loader) will automatically detect the browser's supported image formats via the request's `Accept` header in order to determine the best output format.

If the `Accept` header matches more than one of the configured formats, the first match in the array is used. Therefore, the array order matters. If there is no match (or the source image is [animated](https://nextjs.org/docs/pages/api-reference/components/image#animated-images)), the Image Optimization API will fallback to the original image's format.

If no configuration is provided, the default below is used.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    formats: ['image/webp'],
  },
}
```

You can enable AVIF support, which will fallback to the original format of the src image if the browser [does not support AVIF](https://caniuse.com/avif):

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    formats: ['image/avif'],
  },
}
```

> **Good to know**:
>
> - We still recommend using WebP for most use cases.
> - AVIF generally takes 50% longer to encode but it compresses 20% smaller compared to WebP. This means that the first time an image is requested, it will typically be slower and then subsequent requests that are cached will be faster.
> - If you self-host with a Proxy/CDN in front of Next.js, you must configure the Proxy to forward the `Accept` header.

## [Caching Behavior](https://nextjs.org/docs/pages/api-reference/components/image\#caching-behavior)

The following describes the caching algorithm for the default [loader](https://nextjs.org/docs/pages/api-reference/components/image#loader). For all other loaders, please refer to your cloud provider's documentation.

Images are optimized dynamically upon request and stored in the `<distDir>/cache/images` directory. The optimized image file will be served for subsequent requests until the expiration is reached. When a request is made that matches a cached but expired file, the expired image is served stale immediately. Then the image is optimized again in the background (also called revalidation) and saved to the cache with the new expiration date.

The cache status of an image can be determined by reading the value of the `x-nextjs-cache` response header. The possible values are the following:

- `MISS` \- the path is not in the cache (occurs at most once, on the first visit)
- `STALE` \- the path is in the cache but exceeded the revalidate time so it will be updated in the background
- `HIT` \- the path is in the cache and has not exceeded the revalidate time

The expiration (or rather Max Age) is defined by either the [`minimumCacheTTL`](https://nextjs.org/docs/pages/api-reference/components/image#minimumcachettl) configuration or the upstream image `Cache-Control` header, whichever is larger. Specifically, the `max-age` value of the `Cache-Control` header is used. If both `s-maxage` and `max-age` are found, then `s-maxage` is preferred. The `max-age` is also passed-through to any downstream clients including CDNs and browsers.

- You can configure [`minimumCacheTTL`](https://nextjs.org/docs/pages/api-reference/components/image#minimumcachettl) to increase the cache duration when the upstream image does not include `Cache-Control` header or the value is very low.
- You can configure [`deviceSizes`](https://nextjs.org/docs/pages/api-reference/components/image#devicesizes) and [`imageSizes`](https://nextjs.org/docs/pages/api-reference/components/image#imagesizes) to reduce the total number of possible generated images.
- You can configure [formats](https://nextjs.org/docs/pages/api-reference/components/image#formats) to disable multiple formats in favor of a single image format.

### [`minimumCacheTTL`](https://nextjs.org/docs/pages/api-reference/components/image\#minimumcachettl)

You can configure the Time to Live (TTL) in seconds for cached optimized images. In many cases, it's better to use a [Static Image Import](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images) which will automatically hash the file contents and cache the image forever with a `Cache-Control` header of `immutable`.

If no configuration is provided, the default below is used.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    minimumCacheTTL: 60, // 1 minute
  },
}
```

You can increase the TTL to reduce the number of revalidations and potentionally lower cost:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    minimumCacheTTL: 2678400, // 31 days
  },
}
```

The expiration (or rather Max Age) of the optimized image is defined by either the `minimumCacheTTL` or the upstream image `Cache-Control` header, whichever is larger.

If you need to change the caching behavior per image, you can configure [`headers`](https://nextjs.org/docs/app/api-reference/config/next-config-js/headers) to set the `Cache-Control` header on the upstream image (e.g. `/some-asset.jpg`, not `/_next/image` itself).

There is no mechanism to invalidate the cache at this time, so its best to keep `minimumCacheTTL` low. Otherwise you may need to manually change the [`src`](https://nextjs.org/docs/pages/api-reference/components/image#src) prop or delete `<distDir>/cache/images`.

### [`disableStaticImages`](https://nextjs.org/docs/pages/api-reference/components/image\#disablestaticimages)

The default behavior allows you to import static files such as `import icon from './icon.png'` and then pass that to the `src` property.

In some cases, you may wish to disable this feature if it conflicts with other plugins that expect the import to behave differently.

You can disable static image imports inside your `next.config.js`:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    disableStaticImages: true,
  },
}
```

### [`dangerouslyAllowSVG`](https://nextjs.org/docs/pages/api-reference/components/image\#dangerouslyallowsvg)

The default [loader](https://nextjs.org/docs/pages/api-reference/components/image#loader) does not optimize SVG images for a few reasons. First, SVG is a vector format meaning it can be resized losslessly. Second, SVG has many of the same features as HTML/CSS, which can lead to vulnerabilities without proper [Content Security Policy (CSP) headers](https://nextjs.org/docs/app/api-reference/config/next-config-js/headers#content-security-policy).

Therefore, we recommended using the [`unoptimized`](https://nextjs.org/docs/pages/api-reference/components/image#unoptimized) prop when the [`src`](https://nextjs.org/docs/pages/api-reference/components/image#src) prop is known to be SVG. This happens automatically when `src` ends with `".svg"`.

However, if you need to serve SVG images with the default Image Optimization API, you can set `dangerouslyAllowSVG` inside your `next.config.js`:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    dangerouslyAllowSVG: true,
    contentDispositionType: 'attachment',
    contentSecurityPolicy: "default-src 'self'; script-src 'none'; sandbox;",
  },
}
```

In addition, it is strongly recommended to also set `contentDispositionType` to force the browser to download the image, as well as `contentSecurityPolicy` to prevent scripts embedded in the image from executing.

### [`contentDispositionType`](https://nextjs.org/docs/pages/api-reference/components/image\#contentdispositiontype)

The default [loader](https://nextjs.org/docs/pages/api-reference/components/image#loader) sets the [`Content-Disposition`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Disposition#as_a_response_header_for_the_main_body) header to `attachment` for added protection since the API can serve arbitrary remote images.

The default value is `attachment` which forces the browser to download the image when visiting directly. This is particularly important when [`dangerouslyAllowSVG`](https://nextjs.org/docs/pages/api-reference/components/image#dangerouslyallowsvg) is true.

You can optionally configure `inline` to allow the browser to render the image when visiting directly, without downloading it.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    contentDispositionType: 'inline',
  },
}
```

## [Animated Images](https://nextjs.org/docs/pages/api-reference/components/image\#animated-images)

The default [loader](https://nextjs.org/docs/pages/api-reference/components/image#loader) will automatically bypass Image Optimization for animated images and serve the image as-is.

Auto-detection for animated files is best-effort and supports GIF, APNG, and WebP. If you want to explicitly bypass Image Optimization for a given animated image, use the [unoptimized](https://nextjs.org/docs/pages/api-reference/components/image#unoptimized) prop.

## [Responsive Images](https://nextjs.org/docs/pages/api-reference/components/image\#responsive-images)

The default generated `srcset` contains `1x` and `2x` images in order to support different device pixel ratios. However, you may wish to render a responsive image that stretches with the viewport. In that case, you'll need to set [`sizes`](https://nextjs.org/docs/pages/api-reference/components/image#sizes) as well as `style` (or `className`).

You can render a responsive image using one of the following methods below.

### [Responsive image using a static import](https://nextjs.org/docs/pages/api-reference/components/image\#responsive-image-using-a-static-import)

If the source image is not dynamic, you can statically import to create a responsive image:

components/author.js

```code-block_code__isn_V
import Image from 'next/image'
import me from '../photos/me.jpg'

export default function Author() {
  return (
    <Image
      src={me}
      alt="Picture of the author"
      sizes="100vw"
      style={{
        width: '100%',
        height: 'auto',
      }}
    />
  )
}
```

Try it out:

- [Demo the image responsive to viewport](https://image-component.nextjs.gallery/responsive)

### [Responsive image with aspect ratio](https://nextjs.org/docs/pages/api-reference/components/image\#responsive-image-with-aspect-ratio)

If the source image is a dynamic or a remote url, you will also need to provide `width` and `height` to set the correct aspect ratio of the responsive image:

components/page.js

```code-block_code__isn_V
import Image from 'next/image'

export default function Page({ photoUrl }) {
  return (
    <Image
      src={photoUrl}
      alt="Picture of the author"
      sizes="100vw"
      style={{
        width: '100%',
        height: 'auto',
      }}
      width={500}
      height={300}
    />
  )
}
```

Try it out:

- [Demo the image responsive to viewport](https://image-component.nextjs.gallery/responsive)

### [Responsive image with `fill`](https://nextjs.org/docs/pages/api-reference/components/image\#responsive-image-with-fill)

If you don't know the aspect ratio, you will need to set the [`fill`](https://nextjs.org/docs/pages/api-reference/components/image#fill) prop and set `position: relative` on the parent. Optionally, you can set `object-fit` style depending on the desired stretch vs crop behavior:

app/page.js

```code-block_code__isn_V
import Image from 'next/image'

export default function Page({ photoUrl }) {
  return (
    <div style={{ position: 'relative', width: '300px', height: '500px' }}>
      <Image
        src={photoUrl}
        alt="Picture of the author"
        sizes="300px"
        fill
        style={{
          objectFit: 'contain',
        }}
      />
    </div>
  )
}
```

Try it out:

- [Demo the `fill` prop](https://image-component.nextjs.gallery/fill)

## [Theme Detection CSS](https://nextjs.org/docs/pages/api-reference/components/image\#theme-detection-css)

If you want to display a different image for light and dark mode, you can create a new component that wraps two `<Image>` components and reveals the correct one based on a CSS media query.

components/theme-image.module.css

```code-block_code__isn_V
.imgDark {
  display: none;
}

@media (prefers-color-scheme: dark) {
  .imgLight {
    display: none;
  }
  .imgDark {
    display: unset;
  }
}
```

components/theme-image.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import styles from './theme-image.module.css'
import Image, { ImageProps } from 'next/image'

type Props = Omit<ImageProps, 'src' | 'priority' | 'loading'> & {
  srcLight: string
  srcDark: string
}

const ThemeImage = (props: Props) => {
  const { srcLight, srcDark, ...rest } = props

  return (
    <>
      <Image {...rest} src={srcLight} className={styles.imgLight} />
      <Image {...rest} src={srcDark} className={styles.imgDark} />
    </>
  )
}
```

> **Good to know**: The default behavior of `loading="lazy"` ensures that only the correct image is loaded. You cannot use `priority` or `loading="eager"` because that would cause both images to load. Instead, you can use [`fetchPriority="high"`](https://developer.mozilla.org/docs/Web/API/HTMLImageElement/fetchPriority).

Try it out:

- [Demo light/dark mode theme detection](https://image-component.nextjs.gallery/theme)

## [getImageProps](https://nextjs.org/docs/pages/api-reference/components/image\#getimageprops)

For more advanced use cases, you can call `getImageProps()` to get the props that would be passed to the underlying `<img>` element, and instead pass to them to another component, style, canvas, etc.

This also avoid calling React `useState()` so it can lead to better performance, but it cannot be used with the [`placeholder`](https://nextjs.org/docs/pages/api-reference/components/image#placeholder) prop because the placeholder will never be removed.

### [Theme Detection Picture](https://nextjs.org/docs/pages/api-reference/components/image\#theme-detection-picture)

If you want to display a different image for light and dark mode, you can use the [`<picture>`](https://developer.mozilla.org/docs/Web/HTML/Element/picture) element to display a different image based on the user's [preferred color scheme](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme).

app/page.js

```code-block_code__isn_V
import { getImageProps } from 'next/image'

export default function Page() {
  const common = { alt: 'Theme Example', width: 800, height: 400 }
  const {
    props: { srcSet: dark },
  } = getImageProps({ ...common, src: '/dark.png' })
  const {
    props: { srcSet: light, ...rest },
  } = getImageProps({ ...common, src: '/light.png' })

  return (
    <picture>
      <source media="(prefers-color-scheme: dark)" srcSet={dark} />
      <source media="(prefers-color-scheme: light)" srcSet={light} />
      <img {...rest} />
    </picture>
  )
}
```

### [Art Direction](https://nextjs.org/docs/pages/api-reference/components/image\#art-direction)

If you want to display a different image for mobile and desktop, sometimes called [Art Direction](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images#art_direction), you can provide different `src`, `width`, `height`, and `quality` props to `getImageProps()`.

app/page.js

```code-block_code__isn_V
import { getImageProps } from 'next/image'

export default function Home() {
  const common = { alt: 'Art Direction Example', sizes: '100vw' }
  const {
    props: { srcSet: desktop },
  } = getImageProps({
    ...common,
    width: 1440,
    height: 875,
    quality: 80,
    src: '/desktop.jpg',
  })
  const {
    props: { srcSet: mobile, ...rest },
  } = getImageProps({
    ...common,
    width: 750,
    height: 1334,
    quality: 70,
    src: '/mobile.jpg',
  })

  return (
    <picture>
      <source media="(min-width: 1000px)" srcSet={desktop} />
      <source media="(min-width: 500px)" srcSet={mobile} />
      <img {...rest} style={{ width: '100%', height: 'auto' }} />
    </picture>
  )
}
```

### [Background CSS](https://nextjs.org/docs/pages/api-reference/components/image\#background-css)

You can even convert the `srcSet` string to the [`image-set()`](https://developer.mozilla.org/en-US/docs/Web/CSS/image/image-set) CSS function to optimize a background image.

app/page.js

```code-block_code__isn_V
import { getImageProps } from 'next/image'

function getBackgroundImage(srcSet = '') {
  const imageSet = srcSet
    .split(', ')
    .map((str) => {
      const [url, dpi] = str.split(' ')
      return `url("${url}") ${dpi}`
    })
    .join(', ')
  return `image-set(${imageSet})`
}

export default function Home() {
  const {
    props: { srcSet },
  } = getImageProps({ alt: '', width: 128, height: 128, src: '/img.png' })
  const backgroundImage = getBackgroundImage(srcSet)
  const style = { height: '100vh', width: '100vw', backgroundImage }

  return (
    <main style={style}>
      <h1>Hello World</h1>
    </main>
  )
}
```

## [Known Browser Bugs](https://nextjs.org/docs/pages/api-reference/components/image\#known-browser-bugs)

This `next/image` component uses browser native [lazy loading](https://caniuse.com/loading-lazy-attr), which may fallback to eager loading for older browsers before Safari 15.4. When using the blur-up placeholder, older browsers before Safari 12 will fallback to empty placeholder. When using styles with `width`/ `height` of `auto`, it is possible to cause [Layout Shift](https://web.dev/cls/) on older browsers before Safari 15 that don't [preserve the aspect ratio](https://caniuse.com/mdn-html_elements_img_aspect_ratio_computed_from_attributes). For more details, see [this MDN video](https://www.youtube.com/watch?v=4-d_SoCHeWE).

- [Safari 15 - 16.3](https://bugs.webkit.org/show_bug.cgi?id=243601) display a gray border while loading. Safari 16.4 [fixed this issue](https://webkit.org/blog/13966/webkit-features-in-safari-16-4/#:~:text=Now%20in%20Safari%2016.4%2C%20a%20gray%20line%20no%20longer%20appears%20to%20mark%20the%20space%20where%20a%20lazy%2Dloaded%20image%20will%20appear%20once%20it%E2%80%99s%20been%20loaded.). Possible solutions:
  - Use CSS `@supports (font: -apple-system-body) and (-webkit-appearance: none) { img[loading="lazy"] { clip-path: inset(0.6px) } }`
  - Use [`priority`](https://nextjs.org/docs/pages/api-reference/components/image#priority) if the image is above the fold
- [Firefox 67+](https://bugzilla.mozilla.org/show_bug.cgi?id=1556156) displays a white background while loading. Possible solutions:
  - Enable [AVIF `formats`](https://nextjs.org/docs/pages/api-reference/components/image#formats)
  - Use [`placeholder`](https://nextjs.org/docs/pages/api-reference/components/image#placeholder)

## [Version History](https://nextjs.org/docs/pages/api-reference/components/image\#version-history)

| Version | Changes |
| --- | --- |
| `v15.0.0` | `contentDispositionType` configuration default changed to `attachment`. |
| `v14.2.23` | `qualities` configuration added. |
| `v14.2.15` | `decoding` prop added and `localPatterns` configuration added. |
| `v14.2.14` | `remotePatterns.search` prop added. |
| `v14.2.0` | `overrideSrc` prop added. |
| `v14.1.0` | `getImageProps()` is stable. |
| `v14.0.0` | `onLoadingComplete` prop and `domains` config deprecated. |
| `v13.4.14` | `placeholder` prop support for `data:/image...` |
| `v13.2.0` | `contentDispositionType` configuration added. |
| `v13.0.6` | `ref` prop added. |
| `v13.0.0` | The `next/image` import was renamed to `next/legacy/image`. The `next/future/image` import was renamed to `next/image`. A [codemod is available](https://nextjs.org/docs/app/building-your-application/upgrading/codemods#next-image-to-legacy-image) to safely and automatically rename your imports. `<span>` wrapper removed. `layout`, `objectFit`, `objectPosition`, `lazyBoundary`, `lazyRoot` props removed. `alt` is required. `onLoadingComplete` receives reference to `img` element. Built-in loader config removed. |
| `v12.3.0` | `remotePatterns` and `unoptimized` configuration is stable. |
| `v12.2.0` | Experimental `remotePatterns` and experimental `unoptimized` configuration added. `layout="raw"` removed. |
| `v12.1.1` | `style` prop added. Experimental support for `layout="raw"` added. |
| `v12.1.0` | `dangerouslyAllowSVG` and `contentSecurityPolicy` configuration added. |
| `v12.0.9` | `lazyRoot` prop added. |
| `v12.0.0` | `formats` configuration added.<br>AVIF support added.<br>Wrapper `<div>` changed to `<span>`. |
| `v11.1.0` | `onLoadingComplete` and `lazyBoundary` props added. |
| `v11.0.0` | `src` prop support for static import.<br>`placeholder` prop added.<br>`blurDataURL` prop added. |
| `v10.0.5` | `loader` prop added. |
| `v10.0.1` | `layout` prop added. |
| `v10.0.0` | `next/image` introduced. |

Was this helpful?

supported.

Send

## Next.js Layouts and Pages
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Getting Started](https://nextjs.org/docs/app/getting-started) Layouts and Pages

# How to create layouts and pages

Next.js uses **file-system based routing**, meaning you can use folders and files to define routes. This page will guide you through how to create layouts and pages, and link between them.

## [Creating a page](https://nextjs.org/docs/app/getting-started/layouts-and-pages\#creating-a-page)

A **page** is UI that is rendered on a specific route. To create a page, add a [`page` file](https://nextjs.org/docs/app/api-reference/file-conventions/page) inside the `app` directory and default export a React component. For example, to create an index page ( `/`):

![page.js special file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fpage-special-file.png&w=3840&q=75)![page.js special file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fpage-special-file.png&w=3840&q=75)

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Page() {
  return <h1>Hello Next.js!</h1>
}
```

## [Creating a layout](https://nextjs.org/docs/app/getting-started/layouts-and-pages\#creating-a-layout)

A layout is UI that is **shared** between multiple pages. On navigation, layouts preserve state, remain interactive, and do not rerender.

You can define a layout by default exporting a React component from a [`layout` file](https://nextjs.org/docs/app/api-reference/file-conventions/layout). The component should accept a `children` prop which can be a page or another [layout](https://nextjs.org/docs/app/getting-started/layouts-and-pages#nesting-layouts).

For example, to create a layout that accepts your index page as child, add a `layout` file inside the `app` directory:

![layout.js special file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Flayout-special-file.png&w=3840&q=75)![layout.js special file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Flayout-special-file.png&w=3840&q=75)

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function DashboardLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body>
        {/* Layout UI */}
        {/* Place children where you want to render a page or nested layout */}
        <main>{children}</main>
      </body>
    </html>
  )
}
```

The layout above is called a [root layout](https://nextjs.org/docs/app/api-reference/file-conventions/layout#root-layouts) because it's defined at the root of the `app` directory. The root layout is **required** and must contain `html` and `body` tags.

## [Creating a nested route](https://nextjs.org/docs/app/getting-started/layouts-and-pages\#creating-a-nested-route)

A nested route is a route composed of multiple URL segments. For example, the `/blog/[slug]` route is composed of three segments:

- `/` (Root Segment)
- `blog` (Segment)
- `[slug]` (Leaf Segment)

In Next.js:

- **Folders** are used to define the route segments that map to URL segments.
- **Files** (like `page` and `layout`) are used to create UI that is shown for a segment.

To create nested routes, you can nest folders inside each other. For example, to add a route for `/blog`, create a folder called `blog` in the `app` directory. Then, to make `/blog` publicly accessible, add a `page` file:

![File hierarchy showing blog folder and a page.js file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fblog-nested-route.png&w=3840&q=75)![File hierarchy showing blog folder and a page.js file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fblog-nested-route.png&w=3840&q=75)

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { getPosts } from '@/lib/posts'
import { Post } from '@/ui/post'

export default async function Page() {
  const posts = await getPosts()

  return (
    <ul>
      {posts.map((post) => (
        <Post key={post.id} post={post} />
      ))}
    </ul>
  )
}
```

You can continue nesting folders to create nested routes. For example, to create a route for a specific blog post, create a new `[slug]` folder inside `blog` and add a `page` file:

![File hierarchy showing blog folder with a nested slug folder and a page.js file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fblog-post-nested-route.png&w=3840&q=75)![File hierarchy showing blog folder with a nested slug folder and a page.js file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fblog-post-nested-route.png&w=3840&q=75)

app/blog/\[slug\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
function generateStaticParams() {}

export default function Page() {
  return <h1>Hello, Blog Post Page!</h1>
}
```

> **Good to know**: Wrapping a folder name in square brackets (e.g. `[slug]`) creates a special [dynamic route segment](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes) used to generate multiple pages from data. This is useful for blog posts, product pages, etc.

## [Nesting layouts](https://nextjs.org/docs/app/getting-started/layouts-and-pages\#nesting-layouts)

By default, layouts in the folder hierarchy are also nested, which means they wrap child layouts via their `children` prop. You can nest layouts by adding `layout` inside specific route segments (folders).

For example, to create a layout for the `/blog` route, add a new `layout` file inside the `blog` folder.

![File hierarchy showing root layout wrapping the blog layout](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fnested-layouts.png&w=3840&q=75)![File hierarchy showing root layout wrapping the blog layout](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fnested-layouts.png&w=3840&q=75)

app/blog/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function BlogLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return <section>{children}</section>
}
```

If you were to combine the two layouts above, the root layout ( `app/layout.js`) would wrap the blog layout ( `app/blog/layout.js`), which would wrap the blog ( `app/blog/page.js`) and blog post page ( `app/blog/[slug]/page.js`).

## [Linking between pages](https://nextjs.org/docs/app/getting-started/layouts-and-pages\#linking-between-pages)

You can use the [`<Link>` component](https://nextjs.org/docs/app/api-reference/components/link) to navigate between routes. `<Link>` is a built-in Next.js component that extends the HTML `<a>` tag to provide prefetching and client-side navigation.

For example, to generate a list of blog posts, import `<Link>` from `next/link` and pass a `href` prop to the component:

app/ui/post.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default async function Post({ post }) {
  const posts = await getPosts()

  return (
    <ul>
      {posts.map((post) => (
        <li key={post.slug}>
          <Link href={`/blog/${post.slug}`}>{post.title}</Link>
        </li>
      ))}
    </ul>
  )
}
```

`<Link>` is the primary and recommended way to navigate between routes in your Next.js application. However, you can also use the [`useRouter` hook](https://nextjs.org/docs/app/api-reference/functions/use-router) for more advanced navigation.

## API Reference

Learn more about the features mentioned in this page by reading the API Reference.

[**layout.js** \\
API reference for the layout.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/layout) [**page.js** \\
API reference for the page.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/page) [**Link** \\
Enable fast client-side navigation with the built-in \`next/link\` component.](https://nextjs.org/docs/app/api-reference/components/link)

Was this helpful?

supported.

Send

## Next.js Upgrading Guide
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[Pages Router](https://nextjs.org/docs/pages) [Building Your Application](https://nextjs.org/docs/pages/building-your-application) Upgrading

# Upgrading

Upgrade your application to newer versions of Next.js or migrate from the Pages Router to the App Router.

[**Codemods** \\
Use codemods to upgrade your Next.js codebase when new features are released.](https://nextjs.org/docs/pages/building-your-application/upgrading/codemods) [**From Pages to App** \\
Learn how to upgrade your existing Next.js application from the Pages Router to the App Router.](https://nextjs.org/docs/pages/building-your-application/upgrading/app-router-migration) [**Migrating from Vite** \\
Learn how to migrate your existing React application from Vite to Next.js.](https://nextjs.org/docs/pages/building-your-application/upgrading/from-vite) [**Migrating from Create React App** \\
Learn how to migrate your existing React application from Create React App to Next.js.](https://nextjs.org/docs/pages/building-your-application/upgrading/from-create-react-app) [**Version 14** \\
Upgrade your Next.js Application from Version 13 to 14.](https://nextjs.org/docs/pages/building-your-application/upgrading/version-14) [**Version 13** \\
Upgrade your Next.js Application from Version 12 to 13.](https://nextjs.org/docs/pages/building-your-application/upgrading/version-13) [**Version 12** \\
Upgrade your Next.js Application from Version 11 to Version 12.](https://nextjs.org/docs/pages/building-your-application/upgrading/version-12) [**Version 11** \\
Upgrade your Next.js Application from Version 10 to Version 11.](https://nextjs.org/docs/pages/building-your-application/upgrading/version-11) [**Version 10** \\
Upgrade your Next.js Application from Version 9 to Version 10.](https://nextjs.org/docs/pages/building-your-application/upgrading/version-10) [**Version 9** \\
Upgrade your Next.js Application from Version 8 to Version 9.](https://nextjs.org/docs/pages/building-your-application/upgrading/version-9)

Was this helpful?

supported.

Send

## Server Components Overview
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Rendering](https://nextjs.org/docs/app/building-your-application/rendering) Server Components

# Server Components

React Server Components allow you to write UI that can be rendered and optionally cached on the server. In Next.js, the rendering work is further split by route segments to enable streaming and partial rendering, and there are three different server rendering strategies:

- [Static Rendering](https://nextjs.org/docs/app/building-your-application/rendering/server-components#static-rendering-default)
- [Dynamic Rendering](https://nextjs.org/docs/app/building-your-application/rendering/server-components#dynamic-rendering)
- [Streaming](https://nextjs.org/docs/app/building-your-application/rendering/server-components#streaming)

This page will go through how Server Components work, when you might use them, and the different server rendering strategies.

## [Benefits of Server Rendering](https://nextjs.org/docs/app/building-your-application/rendering/server-components\#benefits-of-server-rendering)

There are a couple of benefits to doing the rendering work on the server, including:

- **Data Fetching**: Server Components allow you to move data fetching to the server, closer to your data source. This can improve performance by reducing time it takes to fetch data needed for rendering, and the number of requests the client needs to make.
- **Security**: Server Components allow you to keep sensitive data and logic on the server, such as tokens and API keys, without the risk of exposing them to the client.
- **Caching**: By rendering on the server, the result can be cached and reused on subsequent requests and across users. This can improve performance and reduce cost by reducing the amount of rendering and data fetching done on each request.
- **Performance**: Server Components give you additional tools to optimize performance from the baseline. For example, if you start with an app composed of entirely Client Components, moving non-interactive pieces of your UI to Server Components can reduce the amount of client-side JavaScript needed. This is beneficial for users with slower internet or less powerful devices, as the browser has less client-side JavaScript to download, parse, and execute.
- **Initial Page Load and [First Contentful Paint (FCP)](https://web.dev/fcp/)**: On the server, we can generate HTML to allow users to view the page immediately, without waiting for the client to download, parse and execute the JavaScript needed to render the page.
- **Search Engine Optimization and Social Network Shareability**: The rendered HTML can be used by search engine bots to index your pages and social network bots to generate social card previews for your pages.
- **Streaming**: Server Components allow you to split the rendering work into chunks and stream them to the client as they become ready. This allows the user to see parts of the page earlier without having to wait for the entire page to be rendered on the server.

## [Using Server Components in Next.js](https://nextjs.org/docs/app/building-your-application/rendering/server-components\#using-server-components-in-nextjs)

By default, Next.js uses Server Components. This allows you to automatically implement server rendering with no additional configuration, and you can opt into using Client Components when needed, see [Client Components](https://nextjs.org/docs/app/building-your-application/rendering/client-components).

## [How are Server Components rendered?](https://nextjs.org/docs/app/building-your-application/rendering/server-components\#how-are-server-components-rendered)

On the server, Next.js uses React's APIs to orchestrate rendering. The rendering work is split into chunks: by individual route segments and [Suspense Boundaries](https://react.dev/reference/react/Suspense).

Each chunk is rendered in two steps:

1. React renders Server Components into a special data format called the **React Server Component Payload (RSC Payload)**.
2. Next.js uses the RSC Payload and Client Component JavaScript instructions to render **HTML** on the server.

Then, on the client:

1. The HTML is used to immediately show a fast non-interactive preview of the route - this is for the initial page load only.
2. The React Server Components Payload is used to reconcile the Client and Server Component trees, and update the DOM.
3. The JavaScript instructions are used to [hydrate](https://react.dev/reference/react-dom/client/hydrateRoot) Client Components and make the application interactive.

> #### [What is the React Server Component Payload (RSC)?](https://nextjs.org/docs/app/building-your-application/rendering/server-components\#what-is-the-react-server-component-payload-rsc)
>
> The RSC Payload is a compact binary representation of the rendered React Server Components tree. It's used by React on the client to update the browser's DOM. The RSC Payload contains:
>
> - The rendered result of Server Components
> - Placeholders for where Client Components should be rendered and references to their JavaScript files
> - Any props passed from a Server Component to a Client Component

## [Server Rendering Strategies](https://nextjs.org/docs/app/building-your-application/rendering/server-components\#server-rendering-strategies)

There are three subsets of server rendering: Static, Dynamic, and Streaming.

### [Static Rendering (Default)](https://nextjs.org/docs/app/building-your-application/rendering/server-components\#static-rendering-default)

With Static Rendering, routes are rendered at **build time**, or in the background after [data revalidation](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration). The result is cached and can be pushed to a [Content Delivery Network (CDN)](https://developer.mozilla.org/docs/Glossary/CDN). This optimization allows you to share the result of the rendering work between users and server requests.

Static rendering is useful when a route has data that is not personalized to the user and can be known at build time, such as a static blog post or a product page.

### [Dynamic Rendering](https://nextjs.org/docs/app/building-your-application/rendering/server-components\#dynamic-rendering)

With Dynamic Rendering, routes are rendered for each user at **request time**.

Dynamic rendering is useful when a route has data that is personalized to the user or has information that can only be known at request time, such as cookies or the URL's search params.

> **Dynamic Routes with Cached Data**
>
> In most websites, routes are not fully static or fully dynamic - it's a spectrum. For example, you can have an e-commerce page that uses cached product data that's revalidated at an interval, but also has uncached, personalized customer data.
>
> In Next.js, you can have dynamically rendered routes that have both cached and uncached data. This is because the RSC Payload and data are cached separately. This allows you to opt into dynamic rendering without worrying about the performance impact of fetching all the data at request time.
>
> Learn more about the [full-route cache](https://nextjs.org/docs/app/building-your-application/caching#full-route-cache) and [Data Cache](https://nextjs.org/docs/app/building-your-application/caching#data-cache).

#### [Switching to Dynamic Rendering](https://nextjs.org/docs/app/building-your-application/rendering/server-components\#switching-to-dynamic-rendering)

During rendering, if a [Dynamic API](https://nextjs.org/docs/app/building-your-application/rendering/server-components#dynamic-apis) or a [fetch](https://nextjs.org/docs/app/api-reference/functions/fetch) option of `{ cache: 'no-store' }` is discovered, Next.js will switch to dynamically rendering the whole route. This table summarizes how Dynamic APIs and data caching affect whether a route is statically or dynamically rendered:

| Dynamic APIs | Data | Route |
| --- | --- | --- |
| No | Cached | Statically Rendered |
| Yes | Cached | Dynamically Rendered |
| No | Not Cached | Dynamically Rendered |
| Yes | Not Cached | Dynamically Rendered |

In the table above, for a route to be fully static, all data must be cached. However, you can have a dynamically rendered route that uses both cached and uncached data fetches.

As a developer, you do not need to choose between static and dynamic rendering as Next.js will automatically choose the best rendering strategy for each route based on the features and APIs used. Instead, you choose when to [cache](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching) or [revalidate specific data](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration), and you may choose to [stream](https://nextjs.org/docs/app/building-your-application/rendering/server-components#streaming) parts of your UI.

### [Dynamic APIs](https://nextjs.org/docs/app/building-your-application/rendering/server-components\#dynamic-apis)

Dynamic APIs rely on information that can only be known at request time (and not ahead of time during prerendering). Using any of these APIs signals the developer's intention and will opt the whole route into dynamic rendering at the request time. These APIs include:

- [`cookies`](https://nextjs.org/docs/app/api-reference/functions/cookies)
- [`headers`](https://nextjs.org/docs/app/api-reference/functions/headers)
- [`connection`](https://nextjs.org/docs/app/api-reference/functions/connection)
- [`draftMode`](https://nextjs.org/docs/app/api-reference/functions/draft-mode)
- [`searchParams` prop](https://nextjs.org/docs/app/api-reference/file-conventions/page#searchparams-optional)
- [`unstable_noStore`](https://nextjs.org/docs/app/api-reference/functions/unstable_noStore)

### [Streaming](https://nextjs.org/docs/app/building-your-application/rendering/server-components\#streaming)

![Diagram showing parallelization of route segments during streaming, showing data fetching, rendering, and hydration of individual chunks.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fsequential-parallel-data-fetching.png&w=3840&q=75)![Diagram showing parallelization of route segments during streaming, showing data fetching, rendering, and hydration of individual chunks.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fsequential-parallel-data-fetching.png&w=3840&q=75)

Streaming enables you to progressively render UI from the server. Work is split into chunks and streamed to the client as it becomes ready. This allows the user to see parts of the page immediately, before the entire content has finished rendering.

![Diagram showing partially rendered page on the client, with loading UI for chunks that are being streamed.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fserver-rendering-with-streaming.png&w=3840&q=75)![Diagram showing partially rendered page on the client, with loading UI for chunks that are being streamed.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fserver-rendering-with-streaming.png&w=3840&q=75)

Streaming is built into the Next.js App Router by default. This helps improve both the initial page loading performance, as well as UI that depends on slower data fetches that would block rendering the whole route. For example, reviews on a product page.

You can start streaming route segments using `loading.js` and UI components with [React Suspense](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming). See the [Loading UI and Streaming](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming) section for more information.

## Next Steps

Learn how Next.js caches data and the result of static rendering.

[**Caching** \\
An overview of caching mechanisms in Next.js.](https://nextjs.org/docs/app/building-your-application/caching)

Was this helpful?

supported.

Send

## Next.js TypeScript Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [Configuration](https://nextjs.org/docs/app/api-reference/config) TypeScript

# TypeScript

Next.js comes with built-in TypeScript, automatically installing the necessary packages and configuring the proper settings when you create a new project with `create-next-app`.

To add TypeScript to an existing project, rename a file to `.ts` / `.tsx`. Run `next dev` and `next build` to automatically install the necessary dependencies and add a `tsconfig.json` file with the recommended config options.

> **Good to know**: If you already have a `jsconfig.json` file, copy the `paths` compiler option from the old `jsconfig.json` into the new `tsconfig.json` file, and delete the old `jsconfig.json` file.

## [IDE Plugin](https://nextjs.org/docs/app/api-reference/config/typescript\#ide-plugin)

Next.js includes a custom TypeScript plugin and type checker, which VSCode and other code editors can use for advanced type-checking and auto-completion.

You can enable the plugin in VS Code by:

1. Opening the command palette ( `Ctrl/⌘` \+ `Shift` \+ `P`)
2. Searching for "TypeScript: Select TypeScript Version"
3. Selecting "Use Workspace Version"

![TypeScript Command Palette](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Ftypescript-command-palette.png&w=3840&q=75)![TypeScript Command Palette](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Ftypescript-command-palette.png&w=3840&q=75)

Now, when editing files, the custom plugin will be enabled. When running `next build`, the custom type checker will be used.

The TypeScript plugin can help with:

- Warning if the invalid values for [segment config options](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config) are passed.
- Showing available options and in-context documentation.
- Ensuring the `use client` directive is used correctly.
- Ensuring client hooks (like `useState`) are only used in Client Components.

> **🎥 Watch:** Learn about the built-in TypeScript plugin → [YouTube (3 minutes)](https://www.youtube.com/watch?v=pqMqn9fKEf8)

## [End-to-End Type Safety](https://nextjs.org/docs/app/api-reference/config/typescript\#end-to-end-type-safety)

The Next.js App Router has **enhanced type safety**. This includes:

1. **No serialization of data between fetching function and page**: You can `fetch` directly in components, layouts, and pages on the server. This data _does not_ need to be serialized (converted to a string) to be passed to the client side for consumption in React. Instead, since `app` uses Server Components by default, we can use values like `Date`, `Map`, `Set`, and more without any extra steps. Previously, you needed to manually type the boundary between server and client with Next.js-specific types.
2. **Streamlined data flow between components**: With the removal of `_app` in favor of root layouts, it is now easier to visualize the data flow between components and pages. Previously, data flowing between individual `pages` and `_app` were difficult to type and could introduce confusing bugs. With [colocated data fetching](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching) in the App Router, this is no longer an issue.

[Data Fetching in Next.js](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching) now provides as close to end-to-end type safety as possible without being prescriptive about your database or content provider selection.

We're able to type the response data as you would expect with normal TypeScript. For example:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
async function getData() {
  const res = await fetch('https://api.example.com/...')
  // The return value is *not* serialized
  // You can return Date, Map, Set, etc.
  return res.json()
}

export default async function Page() {
  const name = await getData()

  return '...'
}
```

For _complete_ end-to-end type safety, this also requires your database or content provider to support TypeScript. This could be through using an [ORM](https://en.wikipedia.org/wiki/Object%E2%80%93relational_mapping) or type-safe query builder.

## [Examples](https://nextjs.org/docs/app/api-reference/config/typescript\#examples)

### [Type checking `next.config.ts`](https://nextjs.org/docs/app/api-reference/config/typescript\#type-checking-nextconfigts)

You can use TypeScript and import types in your Next.js configuration by using `next.config.ts`.

next.config.ts

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  /* config options here */
}

export default nextConfig
```

> **Good to know**: Module resolution in `next.config.ts` is currently limited to `CommonJS`. This may cause incompatibilities with ESM only packages being loaded in `next.config.ts`.

When using the `next.config.js` file, you can add some type checking in your IDE using JSDoc as below:

next.config.js

```code-block_code__isn_V
// @ts-check

/** @type {import('next').NextConfig} */
const nextConfig = {
  /* config options here */
}

module.exports = nextConfig
```

### [Statically Typed Links](https://nextjs.org/docs/app/api-reference/config/typescript\#statically-typed-links)

Next.js can statically type links to prevent typos and other errors when using `next/link`, improving type safety when navigating between pages.

To opt-into this feature, `experimental.typedRoutes` need to be enabled and the project needs to be using TypeScript.

next.config.ts

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  experimental: {
    typedRoutes: true,
  },
}

export default nextConfig
```

Next.js will generate a link definition in `.next/types` that contains information about all existing routes in your application, which TypeScript can then use to provide feedback in your editor about invalid links.

Currently, experimental support includes any string literal, including dynamic segments. For non-literal strings, you currently need to manually cast the `href` with `as Route`:

```code-block_code__isn_V
import type { Route } from 'next';
import Link from 'next/link'

// No TypeScript errors if href is a valid route
<Link href="/about" />
<Link href="/blog/nextjs" />
<Link href={`/blog/${slug}`} />
<Link href={('/blog' + slug) as Route} />

// TypeScript errors if href is not a valid route
<Link href="/aboot" />
```

To accept `href` in a custom component wrapping `next/link`, use a generic:

```code-block_code__isn_V
import type { Route } from 'next'
import Link from 'next/link'

function Card<T extends string>({ href }: { href: Route<T> | URL }) {
  return (
    <Link href={href}>
      <div>My Card</div>
    </Link>
  )
}
```

> **How does it work?**
>
> When running `next dev` or `next build`, Next.js generates a hidden `.d.ts` file inside `.next` that contains information about all existing routes in your application (all valid routes as the `href` type of `Link`). This `.d.ts` file is included in `tsconfig.json` and the TypeScript compiler will check that `.d.ts` and provide feedback in your editor about invalid links.

### [With Async Server Components](https://nextjs.org/docs/app/api-reference/config/typescript\#with-async-server-components)

To use an `async` Server Component with TypeScript, ensure you are using TypeScript `5.1.3` or higher and `@types/react` `18.2.8` or higher.

If you are using an older version of TypeScript, you may see a `'Promise<Element>' is not a valid JSX element` type error. Updating to the latest version of TypeScript and `@types/react` should resolve this issue.

### [Incremental type checking](https://nextjs.org/docs/app/api-reference/config/typescript\#incremental-type-checking)

Since `v10.2.1` Next.js supports [incremental type checking](https://www.typescriptlang.org/tsconfig#incremental) when enabled in your `tsconfig.json`, this can help speed up type checking in larger applications.

### [Disabling TypeScript errors in production](https://nextjs.org/docs/app/api-reference/config/typescript\#disabling-typescript-errors-in-production)

Next.js fails your **production build** ( `next build`) when TypeScript errors are present in your project.

If you'd like Next.js to dangerously produce production code even when your application has errors, you can disable the built-in type checking step.

If disabled, be sure you are running type checks as part of your build or deploy process, otherwise this can be very dangerous.

Open `next.config.ts` and enable the `ignoreBuildErrors` option in the `typescript` config:

next.config.ts

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  typescript: {
    // !! WARN !!
    // Dangerously allow production builds to successfully complete even if
    // your project has type errors.
    // !! WARN !!
    ignoreBuildErrors: true,
  },
}

export default nextConfig
```

> **Good to know**: You can run `tsc --noEmit` to check for TypeScript errors yourself before building. This is useful for CI/CD pipelines where you'd like to check for TypeScript errors before deploying.

### [Custom type declarations](https://nextjs.org/docs/app/api-reference/config/typescript\#custom-type-declarations)

When you need to declare custom types, you might be tempted to modify `next-env.d.ts`. However, this file is automatically generated, so any changes you make will be overwritten. Instead, you should create a new file, let's call it `new-types.d.ts`, and reference it in your `tsconfig.json`:

tsconfig.json

```code-block_code__isn_V
{
  "compilerOptions": {
    "skipLibCheck": true
    //...truncated...
  },
  "include": [\
    "new-types.d.ts",\
    "next-env.d.ts",\
    ".next/types/**/*.ts",\
    "**/*.ts",\
    "**/*.tsx"\
  ],
  "exclude": ["node_modules"]
}
```

## [Version Changes](https://nextjs.org/docs/app/api-reference/config/typescript\#version-changes)

| Version | Changes |
| --- | --- |
| `v15.0.0` | [`next.config.ts`](https://nextjs.org/docs/app/api-reference/config/typescript#type-checking-nextconfigts) support added for TypeScript projects. |
| `v13.2.0` | Statically typed links are available in beta. |
| `v12.0.0` | [SWC](https://nextjs.org/docs/architecture/nextjs-compiler) is now used by default to compile TypeScript and TSX for faster builds. |
| `v10.2.1` | [Incremental type checking](https://www.typescriptlang.org/tsconfig#incremental) support added when enabled in your `tsconfig.json`. |

Was this helpful?

supported.

Send

## Next.js Middleware Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Middleware

# Middleware

Middleware allows you to run code before a request is completed. Then, based on the incoming request, you can modify the response by rewriting, redirecting, modifying the request or response headers, or responding directly.

Middleware runs before cached content and routes are matched. See [Matching Paths](https://nextjs.org/docs/app/building-your-application/routing/middleware#matching-paths) for more details.

## [Use Cases](https://nextjs.org/docs/app/building-your-application/routing/middleware\#use-cases)

Integrating Middleware into your application can lead to significant improvements in performance, security, and user experience. Some common scenarios where Middleware is particularly effective include:

- Authentication and Authorization: Ensure user identity and check session cookies before granting access to specific pages or API routes.
- Server-Side Redirects: Redirect users at the server level based on certain conditions (e.g., locale, user role).
- Path Rewriting: Support A/B testing, feature rollouts, or legacy paths by dynamically rewriting paths to API routes or pages based on request properties.
- Bot Detection: Protect your resources by detecting and blocking bot traffic.
- Logging and Analytics: Capture and analyze request data for insights before processing by the page or API.
- Feature Flagging: Enable or disable features dynamically for seamless feature rollouts or testing.

Recognizing situations where middleware may not be the optimal approach is just as crucial. Here are some scenarios to be mindful of:

- Complex Data Fetching and Manipulation: Middleware is not designed for direct data fetching or manipulation, this should be done within Route Handlers or server-side utilities instead.
- Heavy Computational Tasks: Middleware should be lightweight and respond quickly or it can cause delays in page load. Heavy computational tasks or long-running processes should be done within dedicated Route Handlers.
- Extensive Session Management: While Middleware can manage basic session tasks, extensive session management should be managed by dedicated authentication services or within Route Handlers.
- Direct Database Operations: Performing direct database operations within Middleware is not recommended. Database interactions should be done within Route Handlers or server-side utilities.

## [Convention](https://nextjs.org/docs/app/building-your-application/routing/middleware\#convention)

Use the file `middleware.ts` (or `.js`) in the root of your project to define Middleware. For example, at the same level as `pages` or `app`, or inside `src` if applicable.

> **Note**: While only one `middleware.ts` file is supported per project, you can still organize your middleware logic modularly. Break out middleware functionalities into separate `.ts` or `.js` files and import them into your main `middleware.ts` file. This allows for cleaner management of route-specific middleware, aggregated in the `middleware.ts` for centralized control. By enforcing a single middleware file, it simplifies configuration, prevents potential conflicts, and optimizes performance by avoiding multiple middleware layers.

## [Example](https://nextjs.org/docs/app/building-your-application/routing/middleware\#example)

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextResponse } from 'next/server'
import type { NextRequest } from 'next/server'

// This function can be marked `async` if using `await` inside
export function middleware(request: NextRequest) {
  return NextResponse.redirect(new URL('/home', request.url))
}

// See "Matching Paths" below to learn more
export const config = {
  matcher: '/about/:path*',
}
```

## [Matching Paths](https://nextjs.org/docs/app/building-your-application/routing/middleware\#matching-paths)

Middleware will be invoked for **every route in your project**. Given this, it's crucial to use matchers to precisely target or exclude specific routes. The following is the execution order:

1. `headers` from `next.config.js`
2. `redirects` from `next.config.js`
3. Middleware ( `rewrites`, `redirects`, etc.)
4. `beforeFiles` ( `rewrites`) from `next.config.js`
5. Filesystem routes ( `public/`, `_next/static/`, `pages/`, `app/`, etc.)
6. `afterFiles` ( `rewrites`) from `next.config.js`
7. Dynamic Routes ( `/blog/[slug]`)
8. `fallback` ( `rewrites`) from `next.config.js`

There are two ways to define which paths Middleware will run on:

1. [Custom matcher config](https://nextjs.org/docs/app/building-your-application/routing/middleware#matcher)
2. [Conditional statements](https://nextjs.org/docs/app/building-your-application/routing/middleware#conditional-statements)

### [Matcher](https://nextjs.org/docs/app/building-your-application/routing/middleware\#matcher)

`matcher` allows you to filter Middleware to run on specific paths.

middleware.js

```code-block_code__isn_V
export const config = {
  matcher: '/about/:path*',
}
```

You can match a single path or multiple paths with an array syntax:

middleware.js

```code-block_code__isn_V
export const config = {
  matcher: ['/about/:path*', '/dashboard/:path*'],
}
```

The `matcher` config allows full regex so matching like negative lookaheads or character matching is supported. An example of a negative lookahead to match all except specific paths can be seen here:

middleware.js

```code-block_code__isn_V
export const config = {
  matcher: [\
    /*\
     * Match all request paths except for the ones starting with:\
     * - api (API routes)\
     * - _next/static (static files)\
     * - _next/image (image optimization files)\
     * - favicon.ico, sitemap.xml, robots.txt (metadata files)\
     */\
    '/((?!api|_next/static|_next/image|favicon.ico|sitemap.xml|robots.txt).*)',\
  ],
}
```

You can also bypass Middleware for certain requests by using the `missing` or `has` arrays, or a combination of both:

middleware.js

```code-block_code__isn_V
export const config = {
  matcher: [\
    /*\
     * Match all request paths except for the ones starting with:\
     * - api (API routes)\
     * - _next/static (static files)\
     * - _next/image (image optimization files)\
     * - favicon.ico, sitemap.xml, robots.txt (metadata files)\
     */\
    {\
      source:\
        '/((?!api|_next/static|_next/image|favicon.ico|sitemap.xml|robots.txt).*)',\
      missing: [\
        { type: 'header', key: 'next-router-prefetch' },\
        { type: 'header', key: 'purpose', value: 'prefetch' },\
      ],\
    },\
\
    {\
      source:\
        '/((?!api|_next/static|_next/image|favicon.ico|sitemap.xml|robots.txt).*)',\
      has: [\
        { type: 'header', key: 'next-router-prefetch' },\
        { type: 'header', key: 'purpose', value: 'prefetch' },\
      ],\
    },\
\
    {\
      source:\
        '/((?!api|_next/static|_next/image|favicon.ico|sitemap.xml|robots.txt).*)',\
      has: [{ type: 'header', key: 'x-present' }],\
      missing: [{ type: 'header', key: 'x-missing', value: 'prefetch' }],\
    },\
  ],
}
```

> **Good to know**: The `matcher` values need to be constants so they can be statically analyzed at build-time. Dynamic values such as variables will be ignored.

Configured matchers:

1. MUST start with `/`
2. Can include named parameters: `/about/:path` matches `/about/a` and `/about/b` but not `/about/a/c`
3. Can have modifiers on named parameters (starting with `:`): `/about/:path*` matches `/about/a/b/c` because `*` is _zero or more_. `?` is _zero or one_ and `+` _one or more_
4. Can use regular expression enclosed in parenthesis: `/about/(.*)` is the same as `/about/:path*`

Read more details on [path-to-regexp](https://github.com/pillarjs/path-to-regexp#path-to-regexp-1) documentation.

> **Good to know**: For backward compatibility, Next.js always considers `/public` as `/public/index`. Therefore, a matcher of `/public/:path` will match.

### [Conditional Statements](https://nextjs.org/docs/app/building-your-application/routing/middleware\#conditional-statements)

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextResponse } from 'next/server'
import type { NextRequest } from 'next/server'

export function middleware(request: NextRequest) {
  if (request.nextUrl.pathname.startsWith('/about')) {
    return NextResponse.rewrite(new URL('/about-2', request.url))
  }

  if (request.nextUrl.pathname.startsWith('/dashboard')) {
    return NextResponse.rewrite(new URL('/dashboard/user', request.url))
  }
}
```

## [NextResponse](https://nextjs.org/docs/app/building-your-application/routing/middleware\#nextresponse)

The `NextResponse` API allows you to:

- `redirect` the incoming request to a different URL
- `rewrite` the response by displaying a given URL
- Set request headers for API Routes, `getServerSideProps`, and `rewrite` destinations
- Set response cookies
- Set response headers

To produce a response from Middleware, you can:

1. `rewrite` to a route ( [Page](https://nextjs.org/docs/app/api-reference/file-conventions/page) or [Route Handler](https://nextjs.org/docs/app/building-your-application/routing/route-handlers)) that produces a response
2. return a `NextResponse` directly. See [Producing a Response](https://nextjs.org/docs/app/building-your-application/routing/middleware#producing-a-response)

## [Using Cookies](https://nextjs.org/docs/app/building-your-application/routing/middleware\#using-cookies)

Cookies are regular headers. On a `Request`, they are stored in the `Cookie` header. On a `Response` they are in the `Set-Cookie` header. Next.js provides a convenient way to access and manipulate these cookies through the `cookies` extension on `NextRequest` and `NextResponse`.

1. For incoming requests, `cookies` comes with the following methods: `get`, `getAll`, `set`, and `delete` cookies. You can check for the existence of a cookie with `has` or remove all cookies with `clear`.
2. For outgoing responses, `cookies` have the following methods `get`, `getAll`, `set`, and `delete`.

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextResponse } from 'next/server'
import type { NextRequest } from 'next/server'

export function middleware(request: NextRequest) {
  // Assume a "Cookie:nextjs=fast" header to be present on the incoming request
  // Getting cookies from the request using the `RequestCookies` API
  let cookie = request.cookies.get('nextjs')
  console.log(cookie) // => { name: 'nextjs', value: 'fast', Path: '/' }
  const allCookies = request.cookies.getAll()
  console.log(allCookies) // => [{ name: 'nextjs', value: 'fast' }]

  request.cookies.has('nextjs') // => true
  request.cookies.delete('nextjs')
  request.cookies.has('nextjs') // => false

  // Setting cookies on the response using the `ResponseCookies` API
  const response = NextResponse.next()
  response.cookies.set('vercel', 'fast')
  response.cookies.set({
    name: 'vercel',
    value: 'fast',
    path: '/',
  })
  cookie = response.cookies.get('vercel')
  console.log(cookie) // => { name: 'vercel', value: 'fast', Path: '/' }
  // The outgoing response will have a `Set-Cookie:vercel=fast;path=/` header.

  return response
}
```

## [Setting Headers](https://nextjs.org/docs/app/building-your-application/routing/middleware\#setting-headers)

You can set request and response headers using the `NextResponse` API (setting _request_ headers is available since Next.js v13.0.0).

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextResponse } from 'next/server'
import type { NextRequest } from 'next/server'

export function middleware(request: NextRequest) {
  // Clone the request headers and set a new header `x-hello-from-middleware1`
  const requestHeaders = new Headers(request.headers)
  requestHeaders.set('x-hello-from-middleware1', 'hello')

  // You can also set request headers in NextResponse.next
  const response = NextResponse.next({
    request: {
      // New request headers
      headers: requestHeaders,
    },
  })

  // Set a new response header `x-hello-from-middleware2`
  response.headers.set('x-hello-from-middleware2', 'hello')
  return response
}
```

> **Good to know**: Avoid setting large headers as it might cause [431 Request Header Fields Too Large](https://developer.mozilla.org/docs/Web/HTTP/Status/431) error depending on your backend web server configuration.

### [CORS](https://nextjs.org/docs/app/building-your-application/routing/middleware\#cors)

You can set CORS headers in Middleware to allow cross-origin requests, including [simple](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#simple_requests) and [preflighted](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#preflighted_requests) requests.

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextRequest, NextResponse } from 'next/server'

const allowedOrigins = ['https://acme.com', 'https://my-app.org']

const corsOptions = {
  'Access-Control-Allow-Methods': 'GET, POST, PUT, DELETE, OPTIONS',
  'Access-Control-Allow-Headers': 'Content-Type, Authorization',
}

export function middleware(request: NextRequest) {
  // Check the origin from the request
  const origin = request.headers.get('origin') ?? ''
  const isAllowedOrigin = allowedOrigins.includes(origin)

  // Handle preflighted requests
  const isPreflight = request.method === 'OPTIONS'

  if (isPreflight) {
    const preflightHeaders = {
      ...(isAllowedOrigin && { 'Access-Control-Allow-Origin': origin }),
      ...corsOptions,
    }
    return NextResponse.json({}, { headers: preflightHeaders })
  }

  // Handle simple requests
  const response = NextResponse.next()

  if (isAllowedOrigin) {
    response.headers.set('Access-Control-Allow-Origin', origin)
  }

  Object.entries(corsOptions).forEach(([key, value]) => {
    response.headers.set(key, value)
  })

  return response
}

export const config = {
  matcher: '/api/:path*',
}
```

> **Good to know:** You can configure CORS headers for individual routes in [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers#cors).

## [Producing a Response](https://nextjs.org/docs/app/building-your-application/routing/middleware\#producing-a-response)

You can respond from Middleware directly by returning a `Response` or `NextResponse` instance. (This is available since [Next.js v13.1.0](https://nextjs.org/blog/next-13-1#nextjs-advanced-middleware))

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextRequest } from 'next/server'
import { isAuthenticated } from '@lib/auth'

// Limit the middleware to paths starting with `/api/`
export const config = {
  matcher: '/api/:function*',
}

export function middleware(request: NextRequest) {
  // Call our authentication function to check the request
  if (!isAuthenticated(request)) {
    // Respond with JSON indicating an error message
    return Response.json(
      { success: false, message: 'authentication failed' },
      { status: 401 }
    )
  }
}
```

### [`waitUntil` and `NextFetchEvent`](https://nextjs.org/docs/app/building-your-application/routing/middleware\#waituntil-and-nextfetchevent)

The `NextFetchEvent` object extends the native [`FetchEvent`](https://developer.mozilla.org/docs/Web/API/FetchEvent) object, and includes the [`waitUntil()`](https://developer.mozilla.org/docs/Web/API/ExtendableEvent/waitUntil) method.

The `waitUntil()` method takes a promise as an argument, and extends the lifetime of the Middleware until the promise settles. This is useful for performing work in the background.

middleware.ts

```code-block_code__isn_V
import { NextResponse } from 'next/server'
import type { NextFetchEvent, NextRequest } from 'next/server'

export function middleware(req: NextRequest, event: NextFetchEvent) {
  event.waitUntil(
    fetch('https://my-analytics-platform.com', {
      method: 'POST',
      body: JSON.stringify({ pathname: req.nextUrl.pathname }),
    })
  )

  return NextResponse.next()
}
```

## [Advanced Middleware Flags](https://nextjs.org/docs/app/building-your-application/routing/middleware\#advanced-middleware-flags)

In `v13.1` of Next.js two additional flags were introduced for middleware, `skipMiddlewareUrlNormalize` and `skipTrailingSlashRedirect` to handle advanced use cases.

`skipTrailingSlashRedirect` disables Next.js redirects for adding or removing trailing slashes. This allows custom handling inside middleware to maintain the trailing slash for some paths but not others, which can make incremental migrations easier.

next.config.js

```code-block_code__isn_V
module.exports = {
  skipTrailingSlashRedirect: true,
}
```

middleware.js

```code-block_code__isn_V
const legacyPrefixes = ['/docs', '/blog']

export default async function middleware(req) {
  const { pathname } = req.nextUrl

  if (legacyPrefixes.some((prefix) => pathname.startsWith(prefix))) {
    return NextResponse.next()
  }

  // apply trailing slash handling
  if (
    !pathname.endsWith('/') &&
    !pathname.match(/((?!\.well-known(?:\/.*)?)(?:[^/]+\/)*[^/]+\.\w+)/)
  ) {
    return NextResponse.redirect(
      new URL(`${req.nextUrl.pathname}/`, req.nextUrl)
    )
  }
}
```

`skipMiddlewareUrlNormalize` allows for disabling the URL normalization in Next.js to make handling direct visits and client-transitions the same. In some advanced cases, this option provides full control by using the original URL.

next.config.js

```code-block_code__isn_V
module.exports = {
  skipMiddlewareUrlNormalize: true,
}
```

middleware.js

```code-block_code__isn_V
export default async function middleware(req) {
  const { pathname } = req.nextUrl

  // GET /_next/data/build-id/hello.json

  console.log(pathname)
  // with the flag this now /_next/data/build-id/hello.json
  // without the flag this would be normalized to /hello
}
```

## [Unit Testing (experimental)](https://nextjs.org/docs/app/building-your-application/routing/middleware\#unit-testing-experimental)

Starting in Next.js 15.1, the `next/experimental/testing/server` package contains utilities to help unit test middleware files. Unit testing middleware can help ensure that it's only run on desired paths and that custom routing logic works as intended before code reaches production.

The `unstable_doesMiddlewareMatch` function can be used to assert whether middleware will run for the provided URL, headers, and cookies.

```code-block_code__isn_V
import { unstable_doesMiddlewareMatch } from 'next/experimental/testing/server'

expect(
  unstable_doesMiddlewareMatch({
    config,
    nextConfig,
    url: '/test',
  })
).toEqual(false)
```

The entire middleware function can also be tested.

```code-block_code__isn_V
import { isRewrite, getRewrittenUrl } from 'next/experimental/testing/server'

const request = new NextRequest('https://nextjs.org/docs')
const response = await middleware(request)
expect(isRewrite(response)).toEqual(true)
expect(getRewrittenUrl(response)).toEqual('https://other-domain.com/docs')
// getRedirectUrl could also be used if the response were a redirect
```

## [Runtime](https://nextjs.org/docs/app/building-your-application/routing/middleware\#runtime)

Middleware defaults to using the Edge runtime. As of v15.2 (canary), we have experimental support for using the Node.js runtime. To enable, add the flag to your `next.config` file:

next.config.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  experimental: {
    nodeMiddleware: true,
  },
}

export default nextConfig
```

Then in your middleware file, set the runtime to `nodejs` in the `config` object:

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export const config = {
  runtime: 'nodejs',
}
```

> **Note**: This feature is not yet recommended for production use. Therefore, Next.js will throw an error unless you are using the next@canary release instead of the stable release.

## [Version History](https://nextjs.org/docs/app/building-your-application/routing/middleware\#version-history)

| Version | Changes |
| --- | --- |
| `v15.2.0` | Middleware can now use the Node.js runtime (experimental) |
| `v13.1.0` | Advanced Middleware flags added |
| `v13.0.0` | Middleware can modify request headers, response headers, and send responses |
| `v12.2.0` | Middleware is stable, please see the [upgrade guide](https://nextjs.org/docs/messages/middleware-upgrade-guide) |
| `v12.0.9` | Enforce absolute URLs in Edge Runtime ( [PR](https://github.com/vercel/next.js/pull/33410)) |
| `v12.0.0` | Middleware (Beta) added |

Was this helpful?

supported.

Send

## Next.js Configuration Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [Configuration](https://nextjs.org/docs/app/api-reference/config) next.config.js

# next.config.js

Next.js can be configured through a `next.config.js` file in the root of your project directory (for example, by `package.json`) with a default export.

next.config.js

```code-block_code__isn_V
// @ts-check

/** @type {import('next').NextConfig} */
const nextConfig = {
  /* config options here */
}

module.exports = nextConfig
```

## [ECMAScript Modules](https://nextjs.org/docs/app/api-reference/config/next-config-js\#ecmascript-modules)

`next.config.js` is a regular Node.js module, not a JSON file. It gets used by the Next.js server and build phases, and it's not included in the browser build.

If you need [ECMAScript modules](https://nodejs.org/api/esm.html), you can use `next.config.mjs`:

next.config.mjs

```code-block_code__isn_V
// @ts-check

/**
 * @type {import('next').NextConfig}
 */
const nextConfig = {
  /* config options here */
}

export default nextConfig
```

> **Good to know**: `next.config` with the `.cjs`, `.cts`, or `.mts` extensions are currently **not** supported.

## [Configuration as a Function](https://nextjs.org/docs/app/api-reference/config/next-config-js\#configuration-as-a-function)

You can also use a function:

next.config.mjs

```code-block_code__isn_V
// @ts-check

export default (phase, { defaultConfig }) => {
  /**
   * @type {import('next').NextConfig}
   */
  const nextConfig = {
    /* config options here */
  }
  return nextConfig
}
```

### [Async Configuration](https://nextjs.org/docs/app/api-reference/config/next-config-js\#async-configuration)

Since Next.js 12.1.0, you can use an async function:

next.config.js

```code-block_code__isn_V
// @ts-check

module.exports = async (phase, { defaultConfig }) => {
  /**
   * @type {import('next').NextConfig}
   */
  const nextConfig = {
    /* config options here */
  }
  return nextConfig
}
```

### [Phase](https://nextjs.org/docs/app/api-reference/config/next-config-js\#phase)

`phase` is the current context in which the configuration is loaded. You can see the [available phases](https://github.com/vercel/next.js/blob/5e6b008b561caf2710ab7be63320a3d549474a5b/packages/next/shared/lib/constants.ts#L19-L23). Phases can be imported from `next/constants`:

next.config.js

```code-block_code__isn_V
// @ts-check

const { PHASE_DEVELOPMENT_SERVER } = require('next/constants')

module.exports = (phase, { defaultConfig }) => {
  if (phase === PHASE_DEVELOPMENT_SERVER) {
    return {
      /* development only config options here */
    }
  }

  return {
    /* config options for all phases except development here */
  }
}
```

## [TypeScript](https://nextjs.org/docs/app/api-reference/config/next-config-js\#typescript)

If you are using TypeScript in your project, you can use `next.config.ts` to use TypeScript in your configuration:

next.config.ts

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  /* config options here */
}

export default nextConfig
```

The commented lines are the place where you can put the configs allowed by `next.config.js`, which are [defined in this file](https://github.com/vercel/next.js/blob/canary/packages/next/src/server/config-shared.ts).

However, none of the configs are required, and it's not necessary to understand what each config does. Instead, search for the features you need to enable or modify in this section and they will show you what to do.

> Avoid using new JavaScript features not available in your target Node.js version. `next.config.js` will not be parsed by Webpack or Babel.

This page documents all the available configuration options:

## [Unit Testing (experimental)](https://nextjs.org/docs/app/api-reference/config/next-config-js\#unit-testing-experimental)

Starting in Next.js 15.1, the `next/experimental/testing/server` package contains utilities to help unit test `next.config.js` files.

The `unstable_getResponseFromNextConfig` function runs the [`headers`](https://nextjs.org/docs/app/api-reference/config/next-config-js/headers), [`redirects`](https://nextjs.org/docs/app/api-reference/config/next-config-js/redirects), and [`rewrites`](https://nextjs.org/docs/app/api-reference/config/next-config-js/rewrites) functions from `next.config.js` with the provided request information and returns `NextResponse` with the results of the routing.

> The response from `unstable_getResponseFromNextConfig` only considers `next.config.js` fields and does not consider middleware or filesystem routes, so the result in production may be different than the unit test.

```code-block_code__isn_V
import {
  getRedirectUrl,
  unstable_getResponseFromNextConfig,
} from 'next/experimental/testing/server'

const response = await unstable_getResponseFromNextConfig({
  url: 'https://nextjs.org/test',
  nextConfig: {
    async redirects() {
      return [{ source: '/test', destination: '/test2', permanent: false }]
    },
  },
})
expect(response.status).toEqual(307)
expect(getRedirectUrl(response)).toEqual('https://nextjs.org/test2')
```

[**allowedDevOrigins** \\
Use \`allowedDevOrigins\` to configure additional origins that can request the dev server.](https://nextjs.org/docs/app/api-reference/config/next-config-js/allowedDevOrigins) [**appDir** \\
Enable the App Router to use layouts, streaming, and more.](https://nextjs.org/docs/app/api-reference/config/next-config-js/appDir) [**assetPrefix** \\
Learn how to use the assetPrefix config option to configure your CDN.](https://nextjs.org/docs/app/api-reference/config/next-config-js/assetPrefix) [**authInterrupts** \\
Learn how to enable the experimental \`authInterrupts\` configuration option to use \`forbidden\` and \`unauthorized\`.](https://nextjs.org/docs/app/api-reference/config/next-config-js/authInterrupts) [**basePath** \\
Use \`basePath\` to deploy a Next.js application under a sub-path of a domain.](https://nextjs.org/docs/app/api-reference/config/next-config-js/basePath) [**cacheLife** \\
Learn how to set up cacheLife configurations in Next.js.](https://nextjs.org/docs/app/api-reference/config/next-config-js/cacheLife) [**clientInstrumentationHook** \\
Enable client-side instrumentation.](https://nextjs.org/docs/app/api-reference/config/next-config-js/clientInstrumentationHook) [**compress** \\
Next.js provides gzip compression to compress rendered content and static files, it only works with the server target. Learn more about it here.](https://nextjs.org/docs/app/api-reference/config/next-config-js/compress) [**crossOrigin** \\
Use the \`crossOrigin\` option to add a crossOrigin tag on the \`script\` tags generated by \`next/script\`.](https://nextjs.org/docs/app/api-reference/config/next-config-js/crossOrigin) [**cssChunking** \\
Use the \`cssChunking\` option to control how CSS files are chunked in your Next.js application.](https://nextjs.org/docs/app/api-reference/config/next-config-js/cssChunking) [**devIndicators** \\
Configuration options for the on-screen indicator that gives context about the current route you're viewing during development.](https://nextjs.org/docs/app/api-reference/config/next-config-js/devIndicators) [**distDir** \\
Set a custom build directory to use instead of the default .next directory.](https://nextjs.org/docs/app/api-reference/config/next-config-js/distDir) [**dynamicIO** \\
Learn how to enable the dynamicIO flag in Next.js.](https://nextjs.org/docs/app/api-reference/config/next-config-js/dynamicIO) [**env** \\
Learn to add and access environment variables in your Next.js application at build time.](https://nextjs.org/docs/app/api-reference/config/next-config-js/env) [**eslint** \\
Next.js reports ESLint errors and warnings during builds by default. Learn how to opt-out of this behavior here.](https://nextjs.org/docs/app/api-reference/config/next-config-js/eslint) [**expireTime** \\
Customize stale-while-revalidate expire time for ISR enabled pages.](https://nextjs.org/docs/app/api-reference/config/next-config-js/expireTime) [**exportPathMap** \\
Customize the pages that will be exported as HTML files when using \`next export\`.](https://nextjs.org/docs/app/api-reference/config/next-config-js/exportPathMap) [**generateBuildId** \\
Configure the build id, which is used to identify the current build in which your application is being served.](https://nextjs.org/docs/app/api-reference/config/next-config-js/generateBuildId) [**generateEtags** \\
Next.js will generate etags for every page by default. Learn more about how to disable etag generation here.](https://nextjs.org/docs/app/api-reference/config/next-config-js/generateEtags) [**headers** \\
Add custom HTTP headers to your Next.js app.](https://nextjs.org/docs/app/api-reference/config/next-config-js/headers) [**htmlLimitedBots** \\
Specify a list of user agents that should receive blocking metadata.](https://nextjs.org/docs/app/api-reference/config/next-config-js/htmlLimitedBots) [**httpAgentOptions** \\
Next.js will automatically use HTTP Keep-Alive by default. Learn more about how to disable HTTP Keep-Alive here.](https://nextjs.org/docs/app/api-reference/config/next-config-js/httpAgentOptions) [**images** \\
Custom configuration for the next/image loader](https://nextjs.org/docs/app/api-reference/config/next-config-js/images) [**cacheHandler** \\
Configure the Next.js cache used for storing and revalidating data to use any external service like Redis, Memcached, or others.](https://nextjs.org/docs/app/api-reference/config/next-config-js/incrementalCacheHandlerPath) [**inlineCss** \\
Enable inline CSS support.](https://nextjs.org/docs/app/api-reference/config/next-config-js/inlineCss) [**logging** \\
Configure how data fetches are logged to the console when running Next.js in development mode.](https://nextjs.org/docs/app/api-reference/config/next-config-js/logging) [**mdxRs** \\
Use the new Rust compiler to compile MDX files in the App Router.](https://nextjs.org/docs/app/api-reference/config/next-config-js/mdxRs) [**onDemandEntries** \\
Configure how Next.js will dispose and keep in memory pages created in development.](https://nextjs.org/docs/app/api-reference/config/next-config-js/onDemandEntries) [**optimizePackageImports** \\
API Reference for optimizePackageImports Next.js Config Option](https://nextjs.org/docs/app/api-reference/config/next-config-js/optimizePackageImports) [**output** \\
Next.js automatically traces which files are needed by each page to allow for easy deployment of your application. Learn how it works here.](https://nextjs.org/docs/app/api-reference/config/next-config-js/output) [**pageExtensions** \\
Extend the default page extensions used by Next.js when resolving pages in the Pages Router.](https://nextjs.org/docs/app/api-reference/config/next-config-js/pageExtensions) [**poweredByHeader** \\
Next.js will add the \`x-powered-by\` header by default. Learn to opt-out of it here.](https://nextjs.org/docs/app/api-reference/config/next-config-js/poweredByHeader) [**ppr** \\
Learn how to enable Partial Prerendering in Next.js.](https://nextjs.org/docs/app/api-reference/config/next-config-js/ppr) [**productionBrowserSourceMaps** \\
Enables browser source map generation during the production build.](https://nextjs.org/docs/app/api-reference/config/next-config-js/productionBrowserSourceMaps) [**reactCompiler** \\
Enable the React Compiler to automatically optimize component rendering.](https://nextjs.org/docs/app/api-reference/config/next-config-js/reactCompiler) [**reactMaxHeadersLength** \\
The maximum length of the headers that are emitted by React and added to the response.](https://nextjs.org/docs/app/api-reference/config/next-config-js/reactMaxHeadersLength) [**reactStrictMode** \\
The complete Next.js runtime is now Strict Mode-compliant, learn how to opt-in](https://nextjs.org/docs/app/api-reference/config/next-config-js/reactStrictMode) [**redirects** \\
Add redirects to your Next.js app.](https://nextjs.org/docs/app/api-reference/config/next-config-js/redirects) [**rewrites** \\
Add rewrites to your Next.js app.](https://nextjs.org/docs/app/api-reference/config/next-config-js/rewrites) [**sassOptions** \\
Configure Sass options.](https://nextjs.org/docs/app/api-reference/config/next-config-js/sassOptions) [**serverActions** \\
Configure Server Actions behavior in your Next.js application.](https://nextjs.org/docs/app/api-reference/config/next-config-js/serverActions) [**serverComponentsHmrCache** \\
Configure whether fetch responses in Server Components are cached across HMR refresh requests.](https://nextjs.org/docs/app/api-reference/config/next-config-js/serverComponentsHmrCache) [**serverExternalPackages** \\
Opt-out specific dependencies from the Server Components bundling and use native Node.js \`require\`.](https://nextjs.org/docs/app/api-reference/config/next-config-js/serverExternalPackages) [**staleTimes** \\
Learn how to override the invalidation time of the Client Router Cache.](https://nextjs.org/docs/app/api-reference/config/next-config-js/staleTimes) [**staticGeneration\*** \\
Learn how to configure static generation in your Next.js application.](https://nextjs.org/docs/app/api-reference/config/next-config-js/staticGeneration) [**trailingSlash** \\
Configure Next.js pages to resolve with or without a trailing slash.](https://nextjs.org/docs/app/api-reference/config/next-config-js/trailingSlash) [**transpilePackages** \\
Automatically transpile and bundle dependencies from local packages (like monorepos) or from external dependencies (\`node\_modules\`).](https://nextjs.org/docs/app/api-reference/config/next-config-js/transpilePackages) [**turbo** \\
Configure Next.js with Turbopack-specific options](https://nextjs.org/docs/app/api-reference/config/next-config-js/turbo) [**typedRoutes** \\
Enable experimental support for statically typed links.](https://nextjs.org/docs/app/api-reference/config/next-config-js/typedRoutes) [**typescript** \\
Next.js reports TypeScript errors by default. Learn to opt-out of this behavior here.](https://nextjs.org/docs/app/api-reference/config/next-config-js/typescript) [**urlImports** \\
Configure Next.js to allow importing modules from external URLs.](https://nextjs.org/docs/app/api-reference/config/next-config-js/urlImports) [**useCache** \\
Learn how to enable the useCache flag in Next.js.](https://nextjs.org/docs/app/api-reference/config/next-config-js/useCache) [**useLightningcss** \\
Enable experimental support for Lightning CSS.](https://nextjs.org/docs/app/api-reference/config/next-config-js/useLightningcss) [**ViewTransition** \\
Enable ViewTransition API from React in App Router](https://nextjs.org/docs/app/api-reference/config/next-config-js/viewTransition) [**webpack** \\
Learn how to customize the webpack config used by Next.js](https://nextjs.org/docs/app/api-reference/config/next-config-js/webpack) [**webVitalsAttribution** \\
Learn how to use the webVitalsAttribution option to pinpoint the source of Web Vitals issues.](https://nextjs.org/docs/app/api-reference/config/next-config-js/webVitalsAttribution)

Was this helpful?

supported.

Send

## Next.js Output Tracing
Menu

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

Using Pages Router

Features available in /pages

Using Latest Version

15.2.3

[Configuration](https://nextjs.org/docs/pages/api-reference/config) [next.config.js Options](https://nextjs.org/docs/pages/api-reference/config/next-config-js) output

# output

During a build, Next.js will automatically trace each page and its dependencies to determine all of the files that are needed for deploying a production version of your application.

This feature helps reduce the size of deployments drastically. Previously, when deploying with Docker you would need to have all files from your package's `dependencies` installed to run `next start`. Starting with Next.js 12, you can leverage Output File Tracing in the `.next/` directory to only include the necessary files.

Furthermore, this removes the need for the deprecated `serverless` target which can cause various issues and also creates unnecessary duplication.

## [How it Works](https://nextjs.org/docs/pages/api-reference/config/next-config-js/output\#how-it-works)

During `next build`, Next.js will use [`@vercel/nft`](https://github.com/vercel/nft) to statically analyze `import`, `require`, and `fs` usage to determine all files that a page might load.

Next.js' production server is also traced for its needed files and output at `.next/next-server.js.nft.json` which can be leveraged in production.

To leverage the `.nft.json` files emitted to the `.next` output directory, you can read the list of files in each trace that are relative to the `.nft.json` file and then copy them to your deployment location.

## [Automatically Copying Traced Files](https://nextjs.org/docs/pages/api-reference/config/next-config-js/output\#automatically-copying-traced-files)

Next.js can automatically create a `standalone` folder that copies only the necessary files for a production deployment including select files in `node_modules`.

To leverage this automatic copying you can enable it in your `next.config.js`:

next.config.js

```code-block_code__isn_V
module.exports = {
  output: 'standalone',
}
```

This will create a folder at `.next/standalone` which can then be deployed on its own without installing `node_modules`.

Additionally, a minimal `server.js` file is also output which can be used instead of `next start`. This minimal server does not copy the `public` or `.next/static` folders by default as these should ideally be handled by a CDN instead, although these folders can be copied to the `standalone/public` and `standalone/.next/static` folders manually, after which `server.js` file will serve these automatically.

To copy these manually, you can use the `cp` command-line tool after you `next build`:

Terminal

```code-block_code__isn_V
cp -r public .next/standalone/ && cp -r .next/static .next/standalone/.next/
```

To start your minimal `server.js` file locally, run the following command:

Terminal

```code-block_code__isn_V
node .next/standalone/server.js
```

> **Good to know**:
>
> - `next.config.js` is read during `next build` and serialized into the `server.js` output file. If the legacy [`serverRuntimeConfig` or `publicRuntimeConfig` options](https://nextjs.org/docs/pages/api-reference/config/next-config-js/runtime-configuration) are being used, the values will be specific to values at build time.
> - If your project needs to listen to a specific port or hostname, you can define `PORT` or `HOSTNAME` environment variables before running `server.js`. For example, run `PORT=8080 HOSTNAME=0.0.0.0 node server.js` to start the server on `http://0.0.0.0:8080`.

## [Caveats](https://nextjs.org/docs/pages/api-reference/config/next-config-js/output\#caveats)

- While tracing in monorepo setups, the project directory is used for tracing by default. For `next build packages/web-app`, `packages/web-app` would be the tracing root and any files outside of that folder will not be included. To include files outside of this folder you can set `outputFileTracingRoot` in your `next.config.js`.

packages/web-app/next.config.js

```code-block_code__isn_V
module.exports = {
  // this includes files from the monorepo base two directories up
  outputFileTracingRoot: path.join(__dirname, '../../'),
}
```

- There are some cases in which Next.js might fail to include required files, or might incorrectly include unused files. In those cases, you can leverage `outputFileTracingExcludes` and `outputFileTracingIncludes` respectively in `next.config.js`. Each config accepts an object with [minimatch globs](https://www.npmjs.com/package/minimatch) for the key to match specific pages and a value of an array with globs relative to the project's root to either include or exclude in the trace.

next.config.js

```code-block_code__isn_V
module.exports = {
  outputFileTracingExcludes: {
    '/api/hello': ['./un-necessary-folder/**/*'],
  },
  outputFileTracingIncludes: {
    '/api/another': ['./necessary-folder/**/*'],
    '/api/login/\\[\\[\\.\\.\\.slug\\]\\]': [\
      './node_modules/aws-crt/dist/bin/**/*',\
    ],
  },
}
```

**Note:** The key of `outputFileTracingIncludes`/ `outputFileTracingExcludes` is a [glob](https://www.npmjs.com/package/picomatch#basic-globbing), so special characters need to be escaped.

- Currently, Next.js does not do anything with the emitted `.nft.json` files. The files must be read by your deployment platform, for example [Vercel](https://vercel.com/), to create a minimal deployment. In a future release, a new command is planned to utilize these `.nft.json` files.

## [Experimental `turbotrace`](https://nextjs.org/docs/pages/api-reference/config/next-config-js/output\#experimental-turbotrace)

Tracing dependencies can be slow because it requires very complex computations and analysis. We created `turbotrace` in Rust as a faster and smarter alternative to the JavaScript implementation.

To enable it, you can add the following configuration to your `next.config.js`:

next.config.js

```code-block_code__isn_V
module.exports = {
  experimental: {
    turbotrace: {
      // control the log level of the turbotrace, default is `error`
      logLevel?:
      | 'bug'
      | 'fatal'
      | 'error'
      | 'warning'
      | 'hint'
      | 'note'
      | 'suggestions'
      | 'info',
      // control if the log of turbotrace should contain the details of the analysis, default is `false`
      logDetail?: boolean
      // show all log messages without limit
      // turbotrace only show 1 log message for each categories by default
      logAll?: boolean
      // control the context directory of the turbotrace
      // files outside of the context directory will not be traced
      // set the `outputFileTracingRoot` has the same effect
      // if the `outputFileTracingRoot` and this option are both set, the `experimental.turbotrace.contextDirectory` will be used
      contextDirectory?: string
      // if there is `process.cwd()` expression in your code, you can set this option to tell `turbotrace` the value of `process.cwd()` while tracing.
      // for example the require(process.cwd() + '/package.json') will be traced as require('/path/to/cwd/package.json')
      processCwd?: string
      // control the maximum memory usage of the `turbotrace`, in `MB`, default is `6000`.
      memoryLimit?: number
    },
  },
}
```

Was this helpful?

supported.

Send

## Next.js Components Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [API Reference](https://nextjs.org/docs/app/api-reference) Components

# Components

[**Font** \\
Optimizing loading web fonts with the built-in \`next/font\` loaders.](https://nextjs.org/docs/app/api-reference/components/font) [**Form** \\
Learn how to use the \`<Form>\` component to handle form submissions and search params updates with client-side navigation.](https://nextjs.org/docs/app/api-reference/components/form) [**Image** \\
Optimize Images in your Next.js Application using the built-in \`next/image\` Component.](https://nextjs.org/docs/app/api-reference/components/image) [**Link** \\
Enable fast client-side navigation with the built-in \`next/link\` component.](https://nextjs.org/docs/app/api-reference/components/link) [**Script** \\
Optimize third-party scripts in your Next.js application using the built-in \`next/script\` Component.](https://nextjs.org/docs/app/api-reference/components/script)

Was this helpful?

supported.

Send

## Next.js CLI Tools
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [API Reference](https://nextjs.org/docs/app/api-reference) CLI

# CLI

Next.js comes with **two** Command Line Interface (CLI) tools:

- **`create-next-app`**: Quickly create a new Next.js application using the default template or an [example](https://github.com/vercel/next.js/tree/canary/examples) from a public GitHub repository.
- **`next`**: Run the Next.js development server, build your application, and more.

[**create-next-app** \\
Create Next.js apps using one command with the create-next-app CLI.](https://nextjs.org/docs/app/api-reference/cli/create-next-app) [**next CLI** \\
Learn how to run and build your application with the Next.js CLI.](https://nextjs.org/docs/app/api-reference/cli/next)

Was this helpful?

supported.

Send

## Create Next.js App
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [CLI](https://nextjs.org/docs/app/api-reference/cli) create-next-app

# create-next-app

The `create-next-app` CLI allow you to create a new Next.js application using the default template or an [example](https://github.com/vercel/next.js/tree/canary/examples) from a public GitHub repository. It is the easiest way to get started with Next.js.

Basic usage:

Terminal

```code-block_code__isn_V
npx create-next-app@latest [project-name] [options]
```

## [Reference](https://nextjs.org/docs/app/api-reference/cli/create-next-app\#reference)

The following options are available:

| Options | Description |
| --- | --- |
| `-h` or `--help` | Show all available options |
| `-v` or `--version` | Output the version number |
| `--no-*` | Negate default options. E.g. `--no-eslint` |
| `--ts` or `--typescript` | Initialize as a TypeScript project (default) |
| `--js` or `--javascript` | Initialize as a JavaScript project |
| `--tailwind` | Initialize with Tailwind CSS config (default) |
| `--eslint` | Initialize with ESLint config |
| `--app` | Initialize as an App Router project |
| `--api` | Initialize a project with only route handlers |
| `--src-dir` | Initialize inside a `src/` directory |
| `--turbopack` | Enable Turbopack by default for development |
| `--import-alias <alias-to-configure>` | Specify import alias to use (default "@/\*") |
| `--empty` | Initialize an empty project |
| `--use-npm` | Explicitly tell the CLI to bootstrap the application using npm |
| `--use-pnpm` | Explicitly tell the CLI to bootstrap the application using pnpm |
| `--use-yarn` | Explicitly tell the CLI to bootstrap the application using Yarn |
| `--use-bun` | Explicitly tell the CLI to bootstrap the application using Bun |
| `-e` or `--example [name] [github-url]` | An example to bootstrap the app with |
| `--example-path <path-to-example>` | Specify the path to the example separately |
| `--reset-preferences` | Explicitly tell the CLI to reset any stored preferences |
| `--skip-install` | Explicitly tell the CLI to skip installing packages |
| `--yes` | Use previous preferences or defaults for all options |

## [Examples](https://nextjs.org/docs/app/api-reference/cli/create-next-app\#examples)

### [With the default template](https://nextjs.org/docs/app/api-reference/cli/create-next-app\#with-the-default-template)

To create a new app using the default template, run the following command in your terminal:

Terminal

```code-block_code__isn_V
npx create-next-app@latest
```

You will then be asked the following prompts:

Terminal

```code-block_code__isn_V
What is your project named?  my-app
Would you like to use TypeScript?  No / Yes
Would you like to use ESLint?  No / Yes
Would you like to use Tailwind CSS?  No / Yes
Would you like your code inside a `src/` directory?  No / Yes
Would you like to use App Router? (recommended)  No / Yes
Would you like to use Turbopack for `next dev`?  No / Yes
Would you like to customize the import alias (`@/*` by default)?  No / Yes
```

Once you've answered the prompts, a new project will be created with your chosen configuration.

### [With an official Next.js example](https://nextjs.org/docs/app/api-reference/cli/create-next-app\#with-an-official-nextjs-example)

To create a new app using an official Next.js example, use the `--example` flag. For example:

Terminal

```code-block_code__isn_V
npx create-next-app@latest --example [example-name] [your-project-name]
```

You can view a list of all available examples along with setup instructions in the [Next.js repository](https://github.com/vercel/next.js/tree/canary/examples).

### [With any public GitHub example](https://nextjs.org/docs/app/api-reference/cli/create-next-app\#with-any-public-github-example)

To create a new app using any public GitHub example, use the `--example` option with the GitHub repo's URL. For example:

Terminal

```code-block_code__isn_V
npx create-next-app@latest --example "https://github.com/.../" [your-project-name]
```

Was this helpful?

supported.

Send

## Next.js CLI Reference
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [CLI](https://nextjs.org/docs/app/api-reference/cli) next CLI

# next CLI

The Next.js CLI allows you to develop, build, start your application, and more.

Basic usage:

Terminal

```code-block_code__isn_V
npx next [command] [options]
```

## [Reference](https://nextjs.org/docs/app/api-reference/cli/next\#reference)

The following options are available:

| Options | Description |
| --- | --- |
| `-h` or `--help` | Shows all available options |
| `-v` or `--version` | Outputs the Next.js version number |

### [Commands](https://nextjs.org/docs/app/api-reference/cli/next\#commands)

The following commands are available:

| Command | Description |
| --- | --- |
| [`dev`](https://nextjs.org/docs/app/api-reference/cli/next#next-dev-options) | Starts Next.js in development mode with Hot Module Reloading, error reporting, and more. |
| [`build`](https://nextjs.org/docs/app/api-reference/cli/next#next-build-options) | Creates an optimized production build of your application. Displaying information about each route. |
| [`start`](https://nextjs.org/docs/app/api-reference/cli/next#next-start-options) | Starts Next.js in production mode. The application should be compiled with `next build` first. |
| [`info`](https://nextjs.org/docs/app/api-reference/cli/next#next-info-options) | Prints relevant details about the current system which can be used to report Next.js bugs. |
| [`lint`](https://nextjs.org/docs/app/api-reference/cli/next#next-lint-options) | Runs ESLint for all files in the `/src`, `/app`, `/pages`, `/components`, and `/lib` directories. It also provides a guided setup to install any required dependencies if ESLint it is not already configured in your application. |
| [`telemetry`](https://nextjs.org/docs/app/api-reference/cli/next#next-telemetry-options) | Allows you to enable or disable Next.js' completely anonymous telemetry collection. |

> **Good to know**: Running `next` without a command is an alias for `next dev`.

### [`next dev` options](https://nextjs.org/docs/app/api-reference/cli/next\#next-dev-options)

`next dev` starts the application in development mode with Hot Module Reloading (HMR), error reporting, and more. The following options are available when running `next dev`:

| Option | Description |
| --- | --- |
| `-h, --help` | Show all available options. |
| `[directory]` | A directory in which to build the application. If not provided, current directory is used. |
| `--turbopack` | Starts development mode using [Turbopack](https://nextjs.org/docs/app/api-reference/turbopack). |
| `-p` or `--port <port>` | Specify a port number on which to start the application. Default: 3000, env: PORT |
| `-H` or `--hostname <hostname>` | Specify a hostname on which to start the application. Useful for making the application available for other devices on the network. Default: 0.0.0.0 |
| `--experimental-https` | Starts the server with HTTPS and generates a self-signed certificate. |
| `--experimental-https-key <path>` | Path to a HTTPS key file. |
| `--experimental-https-cert <path>` | Path to a HTTPS certificate file. |
| `--experimental-https-ca <path>` | Path to a HTTPS certificate authority file. |
| `--experimental-upload-trace <traceUrl>` | Reports a subset of the debugging trace to a remote HTTP URL. |

### [`next build` options](https://nextjs.org/docs/app/api-reference/cli/next\#next-build-options)

`next build` creates an optimized production build of your application. The output displays information about each route. For example:

Terminal

```code-block_code__isn_V
Route (app)                              Size     First Load JS
┌ ○ /_not-found                          0 B               0 kB
└ ƒ /products/[id]                       0 B               0 kB

○  (Static)   prerendered as static content
ƒ  (Dynamic)  server-rendered on demand
```

- **Size**: The size of assets downloaded when navigating to the page client-side. The size for each route only includes its dependencies.
- **First Load JS**: The size of assets downloaded when visiting the page from the server. The amount of JS shared by all is shown as a separate metric.

Both of these values are [**compressed with gzip**](https://nextjs.org/docs/app/api-reference/config/next-config-js/compress). The first load is indicated by green, yellow, or red. Aim for green for performant applications.

The following options are available for the `next build` command:

| Option | Description |
| --- | --- |
| `-h, --help` | Show all available options. |
| `[directory]` | A directory on which to build the application. If not provided, the current directory will be used. |
| `-d` or `--debug` | Enables a more verbose build output. With this flag enabled additional build output like rewrites, redirects, and headers will be shown. |
|  |  |
| `--profile` | Enables production [profiling for React](https://react.dev/reference/react/Profiler). |
| `--no-lint` | Disables linting. |
| `--no-mangling` | Disables [mangling](https://en.wikipedia.org/wiki/Name_mangling). This may affect performance and should only be used for debugging purposes. |
| `--experimental-app-only` | Builds only App Router routes. |
| `--experimental-build-mode [mode]` | Uses an experimental build mode. (choices: "compile", "generate", default: "default") |

### [`next start` options](https://nextjs.org/docs/app/api-reference/cli/next\#next-start-options)

`next start` starts the application in production mode. The application should be compiled with [`next build`](https://nextjs.org/docs/app/api-reference/cli/next#next-build-options) first.

The following options are available for the `next start` command:

| Option | Description |
| --- | --- |
| `-h` or `--help` | Show all available options. |
| `[directory]` | A directory on which to start the application. If no directory is provided, the current directory will be used. |
| `-p` or `--port <port>` | Specify a port number on which to start the application. (default: 3000, env: PORT) |
| `-H` or `--hostname <hostname>` | Specify a hostname on which to start the application (default: 0.0.0.0). |
| `--keepAliveTimeout <keepAliveTimeout>` | Specify the maximum amount of milliseconds to wait before closing the inactive connections. |

### [`next info` options](https://nextjs.org/docs/app/api-reference/cli/next\#next-info-options)

`next info` prints relevant details about the current system which can be used to report Next.js bugs when opening a [GitHub issue](https://github.com/vercel/next.js/issues). This information includes Operating System platform/arch/version, Binaries (Node.js, npm, Yarn, pnpm), package versions ( `next`, `react`, `react-dom`), and more.

The output should look like this:

Terminal

```code-block_code__isn_V
Operating System:
  Platform: darwin
  Arch: arm64
  Version: Darwin Kernel Version 23.6.0
  Available memory (MB): 65536
  Available CPU cores: 10
Binaries:
  Node: 20.12.0
  npm: 10.5.0
  Yarn: 1.22.19
  pnpm: 9.6.0
Relevant Packages:
  next: 15.0.0-canary.115 // Latest available version is detected (15.0.0-canary.115).
  eslint-config-next: 14.2.5
  react: 19.0.0-rc
  react-dom: 19.0.0
  typescript: 5.5.4
Next.js Config:
  output: N/A
```

The following options are available for the `next info` command:

| Option | Description |
| --- | --- |
| `-h` or `--help` | Show all available options |
| `--verbose` | Collects additional information for debugging. |

### [`next lint` options](https://nextjs.org/docs/app/api-reference/cli/next\#next-lint-options)

`next lint` runs ESLint for all files in the `pages/`, `app/`, `components/`, `lib/`, and `src/` directories. It also provides a guided setup to install any required dependencies if ESLint is not already configured in your application.

The following options are available for the `next lint` command:

| Option | Description |
| --- | --- |
| `[directory]` | A base directory on which to lint the application. If not provided, the current directory will be used. |
| `-d, --dir, <dirs...>` | Include directory, or directories, to run ESLint. |
| `--file, <files...>` | Include file, or files, to run ESLint. |
| `--ext, [exts...]` | Specify JavaScript file extensions. (default: \[".js", ".mjs", ".cjs", ".jsx", ".ts", ".mts", ".cts", ".tsx"\]) |
| `-c, --config, <config>` | Uses this configuration file, overriding all other configuration options. |
| `--resolve-plugins-relative-to, <rprt>` | Specify a directory where plugins should be resolved from. |
| `--strict` | Creates a `.eslintrc.json` file using the Next.js strict configuration. |
| `--rulesdir, <rulesdir...>` | Uses additional rules from this directory(s). |
| `--fix` | Automatically fix linting issues. |
| `--fix-type <fixType>` | Specify the types of fixes to apply (e.g., problem, suggestion, layout). |
| `--ignore-path <path>` | Specify a file to ignore. |
| `--no-ignore <path>` | Disables the `--ignore-path` option. |
| `--quiet` | Reports errors only. |
| `--max-warnings [maxWarnings]` | Specify the number of warnings before triggering a non-zero exit code. (default: -1) |
| `-o, --output-file, <outputFile>` | Specify a file to write report to. |
| `-f, --format, <format>` | Uses a specific output format. |
| `--no-inline-config` | Prevents comments from changing config or rules. |
| `--report-unused-disable-directives-severity <level>` | Specify severity level for unused eslint-disable directives. (choices: "error", "off", "warn") |
| `--no-cache` | Disables caching. |
| `--cache-location, <cacheLocation>` | Specify a location for cache. |
| `--cache-strategy, [cacheStrategy]` | Specify a strategy to use for detecting changed files in the cache. (default: "metadata") |
| `--error-on-unmatched-pattern` | Reports errors when any file patterns are unmatched. |
| `-h, --help` | Displays this message. |

### [`next telemetry` options](https://nextjs.org/docs/app/api-reference/cli/next\#next-telemetry-options)

Next.js collects **completely anonymous** telemetry data about general usage. Participation in this anonymous program is optional, and you can opt-out if you prefer not to share information.

The following options are available for the `next telemetry` command:

| Option | Description |
| --- | --- |
| `-h, --help` | Show all available options. |
| `--enable` | Enables Next.js' telemetry collection. |
| `--disable` | Disables Next.js' telemetry collection. |

Learn more about [Telemetry](https://nextjs.org/telemetry).

## [Examples](https://nextjs.org/docs/app/api-reference/cli/next\#examples)

### [Changing the default port](https://nextjs.org/docs/app/api-reference/cli/next\#changing-the-default-port)

By default, Next.js uses `http://localhost:3000` during development and with `next start`. The default port can be changed with the `-p` option, like so:

Terminal

```code-block_code__isn_V
next dev -p 4000
```

Or using the `PORT` environment variable:

Terminal

```code-block_code__isn_V
PORT=4000 next dev
```

> **Good to know**: `PORT` cannot be set in `.env` as booting up the HTTP server happens before any other code is initialized.

### [Using HTTPS during development](https://nextjs.org/docs/app/api-reference/cli/next\#using-https-during-development)

For certain use cases like webhooks or authentication, you can use [HTTPS](https://developer.mozilla.org/en-US/docs/Glossary/HTTPS) to have a secure environment on `localhost`. Next.js can generate a self-signed certificate with `next dev` using the `--experimental-https` flag:

Terminal

```code-block_code__isn_V
next dev --experimental-https
```

With the generated certificate, the Next.js development server will exist at `https://localhost:3000`. The default port `3000` is used unless a port is specified with `-p`, `--port`, or `PORT`.

You can also provide a custom certificate and key with `--experimental-https-key` and `--experimental-https-cert`. Optionally, you can provide a custom CA certificate with `--experimental-https-ca` as well.

Terminal

```code-block_code__isn_V
next dev --experimental-https --experimental-https-key ./certificates/localhost-key.pem --experimental-https-cert ./certificates/localhost.pem
```

`next dev --experimental-https` is only intended for development and creates a locally trusted certificate with [`mkcert`](https://github.com/FiloSottile/mkcert). In production, use properly issued certificates from trusted authorities.

> **Good to know**: When deploying to Vercel, HTTPS is [automatically configured](https://vercel.com/docs/security/encryption) for your Next.js application.

### [Configuring a timeout for downstream proxies](https://nextjs.org/docs/app/api-reference/cli/next\#configuring-a-timeout-for-downstream-proxies)

When deploying Next.js behind a downstream proxy (e.g. a load-balancer like AWS ELB/ALB), it's important to configure Next's underlying HTTP server with [keep-alive timeouts](https://nodejs.org/api/http.html#http_server_keepalivetimeout) that are _larger_ than the downstream proxy's timeouts. Otherwise, once a keep-alive timeout is reached for a given TCP connection, Node.js will immediately terminate that connection without notifying the downstream proxy. This results in a proxy error whenever it attempts to reuse a connection that Node.js has already terminated.

To configure the timeout values for the production Next.js server, pass `--keepAliveTimeout` (in milliseconds) to `next start`, like so:

Terminal

```code-block_code__isn_V
next start --keepAliveTimeout 70000
```

### [Passing Node.js arguments](https://nextjs.org/docs/app/api-reference/cli/next\#passing-nodejs-arguments)

You can pass any [node arguments](https://nodejs.org/api/cli.html#cli_node_options_options) to `next` commands. For example:

Terminal

```code-block_code__isn_V
NODE_OPTIONS='--throw-deprecation' next
NODE_OPTIONS='-r esm' next
NODE_OPTIONS='--inspect' next
```

Was this helpful?

supported.

Send

## Next.js Font Module
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [Components](https://nextjs.org/docs/app/api-reference/components) Font

# Font Module

This API reference will help you understand how to use [`next/font/google`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts#google-fonts) and [`next/font/local`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts#local-fonts). For features and usage, please see the [Optimizing Fonts](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) page.

### [Font Function Arguments](https://nextjs.org/docs/app/api-reference/components/font\#font-function-arguments)

For usage, review [Google Fonts](https://nextjs.org/docs/app/building-your-application/optimizing/fonts#google-fonts) and [Local Fonts](https://nextjs.org/docs/app/building-your-application/optimizing/fonts#local-fonts).

| Key | `font/google` | `font/local` | Type | Required |
| --- | --- | --- | --- | --- |
| [`src`](https://nextjs.org/docs/app/api-reference/components/font#src) |  |  | String or Array of Objects | Yes |
| [`weight`](https://nextjs.org/docs/app/api-reference/components/font#weight) |  |  | String or Array | Required/Optional |
| [`style`](https://nextjs.org/docs/app/api-reference/components/font#style) |  |  | String or Array | - |
| [`subsets`](https://nextjs.org/docs/app/api-reference/components/font#subsets) |  |  | Array of Strings | - |
| [`axes`](https://nextjs.org/docs/app/api-reference/components/font#axes) |  |  | Array of Strings | - |
| [`display`](https://nextjs.org/docs/app/api-reference/components/font#display) |  |  | String | - |
| [`preload`](https://nextjs.org/docs/app/api-reference/components/font#preload) |  |  | Boolean | - |
| [`fallback`](https://nextjs.org/docs/app/api-reference/components/font#fallback) |  |  | Array of Strings | - |
| [`adjustFontFallback`](https://nextjs.org/docs/app/api-reference/components/font#adjustfontfallback) |  |  | Boolean or String | - |
| [`variable`](https://nextjs.org/docs/app/api-reference/components/font#variable) |  |  | String | - |
| [`declarations`](https://nextjs.org/docs/app/api-reference/components/font#declarations) |  |  | Array of Objects | - |

### [`src`](https://nextjs.org/docs/app/api-reference/components/font\#src)

The path of the font file as a string or an array of objects (with type `Array<{path: string, weight?: string, style?: string}>`) relative to the directory where the font loader function is called.

Used in `next/font/local`

- Required

Examples:

- `src:'./fonts/my-font.woff2'` where `my-font.woff2` is placed in a directory named `fonts` inside the `app` directory
- `src:[{path: './inter/Inter-Thin.ttf', weight: '100',},{path: './inter/Inter-Regular.ttf',weight: '400',},{path: './inter/Inter-Bold-Italic.ttf', weight: '700',style: 'italic',},]`
- if the font loader function is called in `app/page.tsx` using `src:'../styles/fonts/my-font.ttf'`, then `my-font.ttf` is placed in `styles/fonts` at the root of the project

### [`weight`](https://nextjs.org/docs/app/api-reference/components/font\#weight)

The font [`weight`](https://fonts.google.com/knowledge/glossary/weight) with the following possibilities:

- A string with possible values of the weights available for the specific font or a range of values if it's a [variable](https://fonts.google.com/variablefonts) font
- An array of weight values if the font is not a [variable google font](https://fonts.google.com/variablefonts). It applies to `next/font/google` only.

Used in `next/font/google` and `next/font/local`

- Required if the font being used is **not** [variable](https://fonts.google.com/variablefonts)

Examples:

- `weight: '400'`: A string for a single weight value - for the font [`Inter`](https://fonts.google.com/specimen/Inter?query=inter), the possible values are `'100'`, `'200'`, `'300'`, `'400'`, `'500'`, `'600'`, `'700'`, `'800'`, `'900'` or `'variable'` where `'variable'` is the default)
- `weight: '100 900'`: A string for the range between `100` and `900` for a variable font
- `weight: ['100','400','900']`: An array of 3 possible values for a non variable font

### [`style`](https://nextjs.org/docs/app/api-reference/components/font\#style)

The font [`style`](https://developer.mozilla.org/docs/Web/CSS/font-style) with the following possibilities:

- A string [value](https://developer.mozilla.org/docs/Web/CSS/font-style#values) with default value of `'normal'`
- An array of style values if the font is not a [variable google font](https://fonts.google.com/variablefonts). It applies to `next/font/google` only.

Used in `next/font/google` and `next/font/local`

- Optional

Examples:

- `style: 'italic'`: A string - it can be `normal` or `italic` for `next/font/google`
- `style: 'oblique'`: A string - it can take any value for `next/font/local` but is expected to come from [standard font styles](https://developer.mozilla.org/docs/Web/CSS/font-style)
- `style: ['italic','normal']`: An array of 2 values for `next/font/google` \- the values are from `normal` and `italic`

### [`subsets`](https://nextjs.org/docs/app/api-reference/components/font\#subsets)

The font [`subsets`](https://fonts.google.com/knowledge/glossary/subsetting) defined by an array of string values with the names of each subset you would like to be [preloaded](https://nextjs.org/docs/app/building-your-application/optimizing/fonts#specifying-a-subset). Fonts specified via `subsets` will have a link preload tag injected into the head when the [`preload`](https://nextjs.org/docs/app/api-reference/components/font#preload) option is true, which is the default.

Used in `next/font/google`

- Optional

Examples:

- `subsets: ['latin']`: An array with the subset `latin`

You can find a list of all subsets on the Google Fonts page for your font.

### [`axes`](https://nextjs.org/docs/app/api-reference/components/font\#axes)

Some variable fonts have extra `axes` that can be included. By default, only the font weight is included to keep the file size down. The possible values of `axes` depend on the specific font.

Used in `next/font/google`

- Optional

Examples:

- `axes: ['slnt']`: An array with value `slnt` for the `Inter` variable font which has `slnt` as additional `axes` as shown [here](https://fonts.google.com/variablefonts?vfquery=inter#font-families). You can find the possible `axes` values for your font by using the filter on the [Google variable fonts page](https://fonts.google.com/variablefonts#font-families) and looking for axes other than `wght`

### [`display`](https://nextjs.org/docs/app/api-reference/components/font\#display)

The font [`display`](https://developer.mozilla.org/docs/Web/CSS/@font-face/font-display) with possible string [values](https://developer.mozilla.org/docs/Web/CSS/@font-face/font-display#values) of `'auto'`, `'block'`, `'swap'`, `'fallback'` or `'optional'` with default value of `'swap'`.

Used in `next/font/google` and `next/font/local`

- Optional

Examples:

- `display: 'optional'`: A string assigned to the `optional` value

### [`preload`](https://nextjs.org/docs/app/api-reference/components/font\#preload)

A boolean value that specifies whether the font should be [preloaded](https://nextjs.org/docs/app/building-your-application/optimizing/fonts#preloading) or not. The default is `true`.

Used in `next/font/google` and `next/font/local`

- Optional

Examples:

- `preload: false`

### [`fallback`](https://nextjs.org/docs/app/api-reference/components/font\#fallback)

The fallback font to use if the font cannot be loaded. An array of strings of fallback fonts with no default.

- Optional

Used in `next/font/google` and `next/font/local`

Examples:

- `fallback: ['system-ui', 'arial']`: An array setting the fallback fonts to `system-ui` or `arial`

### [`adjustFontFallback`](https://nextjs.org/docs/app/api-reference/components/font\#adjustfontfallback)

- For `next/font/google`: A boolean value that sets whether an automatic fallback font should be used to reduce [Cumulative Layout Shift](https://web.dev/cls/). The default is `true`.
- For `next/font/local`: A string or boolean `false` value that sets whether an automatic fallback font should be used to reduce [Cumulative Layout Shift](https://web.dev/cls/). The possible values are `'Arial'`, `'Times New Roman'` or `false`. The default is `'Arial'`.

Used in `next/font/google` and `next/font/local`

- Optional

Examples:

- `adjustFontFallback: false`: for `next/font/google`
- `adjustFontFallback: 'Times New Roman'`: for `next/font/local`

### [`variable`](https://nextjs.org/docs/app/api-reference/components/font\#variable)

A string value to define the CSS variable name to be used if the style is applied with the [CSS variable method](https://nextjs.org/docs/app/api-reference/components/font#css-variables).

Used in `next/font/google` and `next/font/local`

- Optional

Examples:

- `variable: '--my-font'`: The CSS variable `--my-font` is declared

### [`declarations`](https://nextjs.org/docs/app/api-reference/components/font\#declarations)

An array of font face [descriptor](https://developer.mozilla.org/docs/Web/CSS/@font-face#descriptors) key-value pairs that define the generated `@font-face` further.

Used in `next/font/local`

- Optional

Examples:

- `declarations: [{ prop: 'ascent-override', value: '90%' }]`

## [Applying Styles](https://nextjs.org/docs/app/api-reference/components/font\#applying-styles)

You can apply the font styles in three ways:

- [`className`](https://nextjs.org/docs/app/api-reference/components/font#classname)
- [`style`](https://nextjs.org/docs/app/api-reference/components/font#style-1)
- [CSS Variables](https://nextjs.org/docs/app/api-reference/components/font#css-variables)

### [`className`](https://nextjs.org/docs/app/api-reference/components/font\#classname)

Returns a read-only CSS `className` for the loaded font to be passed to an HTML element.

```code-block_code__isn_V
<p className={inter.className}>Hello, Next.js!</p>
```

### [`style`](https://nextjs.org/docs/app/api-reference/components/font\#style-1)

Returns a read-only CSS `style` object for the loaded font to be passed to an HTML element, including `style.fontFamily` to access the font family name and fallback fonts.

```code-block_code__isn_V
<p style={inter.style}>Hello World</p>
```

### [CSS Variables](https://nextjs.org/docs/app/api-reference/components/font\#css-variables)

If you would like to set your styles in an external style sheet and specify additional options there, use the CSS variable method.

In addition to importing the font, also import the CSS file where the CSS variable is defined and set the variable option of the font loader object as follows:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Inter } from 'next/font/google'
import styles from '../styles/component.module.css'

const inter = Inter({
  variable: '--font-inter',
})
```

To use the font, set the `className` of the parent container of the text you would like to style to the font loader's `variable` value and the `className` of the text to the `styles` property from the external CSS file.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
<main className={inter.variable}>
  <p className={styles.text}>Hello World</p>
</main>
```

Define the `text` selector class in the `component.module.css` CSS file as follows:

styles/component.module.css

```code-block_code__isn_V
.text {
  font-family: var(--font-inter);
  font-weight: 200;
  font-style: italic;
}
```

In the example above, the text `Hello World` is styled using the `Inter` font and the generated font fallback with `font-weight: 200` and `font-style: italic`.

## [Using a font definitions file](https://nextjs.org/docs/app/api-reference/components/font\#using-a-font-definitions-file)

Every time you call the `localFont` or Google font function, that font will be hosted as one instance in your application. Therefore, if you need to use the same font in multiple places, you should load it in one place and import the related font object where you need it. This is done using a font definitions file.

For example, create a `fonts.ts` file in a `styles` folder at the root of your app directory.

Then, specify your font definitions as follows:

styles/fonts.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Inter, Lora, Source_Sans_3 } from 'next/font/google'
import localFont from 'next/font/local'

// define your variable fonts
const inter = Inter()
const lora = Lora()
// define 2 weights of a non-variable font
const sourceCodePro400 = Source_Sans_3({ weight: '400' })
const sourceCodePro700 = Source_Sans_3({ weight: '700' })
// define a custom local font where GreatVibes-Regular.ttf is stored in the styles folder
const greatVibes = localFont({ src: './GreatVibes-Regular.ttf' })

export { inter, lora, sourceCodePro400, sourceCodePro700, greatVibes }
```

You can now use these definitions in your code as follows:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { inter, lora, sourceCodePro700, greatVibes } from '../styles/fonts'

export default function Page() {
  return (
    <div>
      <p className={inter.className}>Hello world using Inter font</p>
      <p style={lora.style}>Hello world using Lora font</p>
      <p className={sourceCodePro700.className}>
        Hello world using Source_Sans_3 font with weight 700
      </p>
      <p className={greatVibes.className}>My title in Great Vibes font</p>
    </div>
  )
}
```

To make it easier to access the font definitions in your code, you can define a path alias in your `tsconfig.json` or `jsconfig.json` files as follows:

tsconfig.json

```code-block_code__isn_V
{
  "compilerOptions": {
    "paths": {
      "@/fonts": ["./styles/fonts"]
    }
  }
}
```

You can now import any font definition as follows:

app/about/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { greatVibes, sourceCodePro400 } from '@/fonts'
```

## [Version Changes](https://nextjs.org/docs/app/api-reference/components/font\#version-changes)

| Version | Changes |
| --- | --- |
| `v13.2.0` | `@next/font` renamed to `next/font`. Installation no longer required. |
| `v13.0.0` | `@next/font` was added. |

Was this helpful?

supported.

Send

## Next.js Form Component
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [Components](https://nextjs.org/docs/app/api-reference/components) Form

# Form

The `<Form>` component extends the HTML `<form>` element to provide [**prefetching**](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#2-prefetching) of [loading UI](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming), **client-side navigation** on submission, and **progressive enhancement**.

It's useful for forms that update URL search params as it reduces the boilerplate code needed to achieve the above.

Basic usage:

/app/ui/search.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Form from 'next/form'

export default function Page() {
  return (
    <Form action="/search">
      {/* On submission, the input value will be appended to
          the URL, e.g. /search?query=abc */}
      <input name="query" />
      <button type="submit">Submit</button>
    </Form>
  )
}
```

## [Reference](https://nextjs.org/docs/app/api-reference/components/form\#reference)

The behavior of the `<Form>` component depends on whether the `action` prop is passed a `string` or `function`.

- When `action` is a **string**, the `<Form>` behaves like a native HTML form that uses a **`GET`** method. The form data is encoded into the URL as search params, and when the form is submitted, it navigates to the specified URL. In addition, Next.js:
  - [Prefetches](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#2-prefetching) the path when the form becomes visible, this preloads shared UI (e.g. `layout.js` and `loading.js`), resulting in faster navigation.
  - Performs a [client-side navigation](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#5-soft-navigation) instead of a full page reload when the form is submitted. This retains shared UI and client-side state.
- When `action` is a **function** (Server Action), `<Form>` behaves like a [React form](https://react.dev/reference/react-dom/components/form), executing the action when the form is submitted.

### [`action` (string) Props](https://nextjs.org/docs/app/api-reference/components/form\#action-string-props)

When `action` is a string, the `<Form>` component supports the following props:

| Prop | Example | Type | Required |
| --- | --- | --- | --- |
| `action` | `action="/search"` | `string` (URL or relative path) | Yes |
| `replace` | `replace={false}` | `boolean` | - |
| `scroll` | `scroll={true}` | `boolean` | - |
| `prefetch` | `prefetch={true}` | `boolean` | - |

- **`action`**: The URL or path to navigate to when the form is submitted.
  - An empty string `""` will navigate to the same route with updated search params.
- **`replace`**: Replaces the current history state instead of pushing a new one to the [browser's history](https://developer.mozilla.org/en-US/docs/Web/API/History_API) stack. Default is `false`.
- **`scroll`**: Controls the scroll behavior during navigation. Defaults to `true`, this means it will scroll to the top of the new route, and maintain the scroll position for backwards and forwards navigation.
- **`prefetch`**: Controls whether the path should be prefetched when the form becomes visible in the user's viewport. Defaults to `true`.

### [`action` (function) Props](https://nextjs.org/docs/app/api-reference/components/form\#action-function-props)

When `action` is a function, the `<Form>` component supports the following prop:

| Prop | Example | Type | Required |
| --- | --- | --- | --- |
| `action` | `action={myAction}` | `function` (Server Action) | Yes |

- **`action`**: The Server Action to be called when the form is submitted. See the [React docs](https://react.dev/reference/react-dom/components/form#props) for more.

> **Good to know**: When `action` is a function, the `replace` and `scroll` props are ignored.

### [Caveats](https://nextjs.org/docs/app/api-reference/components/form\#caveats)

- **`formAction`**: Can be used in a `<button>` or `<input type="submit">` fields to override the `action` prop. Next.js will perform a client-side navigation, however, this approach doesn't support prefetching.
  - When using [`basePath`](https://nextjs.org/docs/app/api-reference/config/next-config-js/basePath), you must also include it in the `formAction` path. e.g. `formAction="/base-path/search"`.
- **`key`**: Passing a `key` prop to a string `action` is not supported. If you'd like to trigger a re-render or perform a mutation, consider using a function `action` instead.

- **`onSubmit`**: Can be used to handle form submission logic. However, calling `event.preventDefault()` will override `<Form>` behavior such as navigating to the specified URL.
- **[`method`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form#method), [`encType`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form#enctype), [`target`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form#target)**: Are not supported as they override `<Form>` behavior.
  - Similarly, `formMethod`, `formEncType`, and `formTarget` can be used to override the `method`, `encType`, and `target` props respectively, and using them will fallback to native browser behavior.
  - If you need to use these props, use the HTML `<form>` element instead.
- **`<input type="file">`**: Using this input type when the `action` is a string will match browser behavior by submitting the filename instead of the file object.

## [Examples](https://nextjs.org/docs/app/api-reference/components/form\#examples)

### [Search form that leads to a search result page](https://nextjs.org/docs/app/api-reference/components/form\#search-form-that-leads-to-a-search-result-page)

You can create a search form that navigates to a search results page by passing the path as an `action`:

/app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Form from 'next/form'

export default function Page() {
  return (
    <Form action="/search">
      <input name="query" />
      <button type="submit">Submit</button>
    </Form>
  )
}
```

When the user updates the query input field and submits the form, the form data will be encoded into the URL as search params, e.g. `/search?query=abc`.

> **Good to know**: If you pass an empty string `""` to `action`, the form will navigate to the same route with updated search params.

On the results page, you can access the query using the [`searchParams`](https://nextjs.org/docs/app/api-reference/file-conventions/page#searchparams-optional) `page.js` prop and use it to fetch data from an external source.

/app/search/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { getSearchResults } from '@/lib/search'

export default async function SearchPage({
  searchParams,
}: {
  searchParams: Promise<{ [key: string]: string | string[] | undefined }>
}) {
  const results = await getSearchResults((await searchParams).query)

  return <div>...</div>
}
```

When the `<Form>` becomes visible in the user's viewport, shared UI (such as `layout.js` and `loading.js`) on the `/search` page will be prefetched. On submission, the form will immediately navigate to the new route and show loading UI while the results are being fetched. You can design the fallback UI using [`loading.js`](https://nextjs.org/docs/app/api-reference/file-conventions/loading):

/app/search/loading.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Loading() {
  return <div>Loading...</div>
}
```

To cover cases when shared UI hasn't yet loaded, you can show instant feedback to the user using [`useFormStatus`](https://react.dev/reference/react-dom/hooks/useFormStatus).

First, create a component that displays a loading state when the form is pending:

/app/ui/search-button.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'
import { useFormStatus } from 'react-dom'

export default function SearchButton() {
  const status = useFormStatus()
  return (
    <button type="submit">{status.pending ? 'Searching...' : 'Search'}</button>
  )
}
```

Then, update the search form page to use the `SearchButton` component:

/app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Form from 'next/form'
import { SearchButton } from '@/ui/search-button'

export default function Page() {
  return (
    <Form action="/search">
      <input name="query" />
      <SearchButton />
    </Form>
  )
}
```

### [Mutations with Server Actions](https://nextjs.org/docs/app/api-reference/components/form\#mutations-with-server-actions)

You can perform mutations by passing a function to the `action` prop.

/app/posts/create/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Form from 'next/form'
import { createPost } from '@/posts/actions'

export default function Page() {
  return (
    <Form action={createPost}>
      <input name="title" />
      {/* ... */}
      <button type="submit">Create Post</button>
    </Form>
  )
}
```

After a mutation, it's common to redirect to the new resource. You can use the [`redirect`](https://nextjs.org/docs/app/building-your-application/routing/redirecting) function from `next/navigation` to navigate to the new post page.

> **Good to know**: Since the "destination" of the form submission is not known until the action is executed, `<Form>` cannot automatically prefetch shared UI.

/app/posts/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'
import { redirect } from 'next/navigation'

export async function createPost(formData: FormData) {
  // Create a new post
  // ...

  // Redirect to the new post
  redirect(`/posts/${data.id}`)
}
```

Then, in the new page, you can fetch data using the `params` prop:

/app/posts/\[id\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { getPost } from '@/posts/data'

export default async function PostPage({
  params,
}: {
  params: Promise<{ id: string }>
}) {
  const { id } = await params
  const data = await getPost(id)

  return (
    <div>
      <h1>{data.title}</h1>
      {/* ... */}
    </div>
  )
}
```

See the [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations) docs for more examples.

Was this helpful?

supported.

Send

## Next.js Image Component
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [Components](https://nextjs.org/docs/app/api-reference/components) Image

# Image

Examples

- [Image Component](https://github.com/vercel/next.js/tree/canary/examples/image-component)

This API reference will help you understand how to use [props](https://nextjs.org/docs/app/api-reference/components/image#props) and [configuration options](https://nextjs.org/docs/app/api-reference/components/image#configuration-options) available for the Image Component. For features and usage, please see the [Image Component](https://nextjs.org/docs/app/building-your-application/optimizing/images) page.

app/page.js

```code-block_code__isn_V
import Image from 'next/image'

export default function Page() {
  return (
    <Image
      src="/profile.png"
      width={500}
      height={500}
      alt="Picture of the author"
    />
  )
}
```

## [Props](https://nextjs.org/docs/app/api-reference/components/image\#props)

Here's a summary of the props available for the Image Component:

| Prop | Example | Type | Status |
| --- | --- | --- | --- |
| [`src`](https://nextjs.org/docs/app/api-reference/components/image#src) | `src="/profile.png"` | String | Required |
| [`width`](https://nextjs.org/docs/app/api-reference/components/image#width) | `width={500}` | Integer (px) | Required |
| [`height`](https://nextjs.org/docs/app/api-reference/components/image#height) | `height={500}` | Integer (px) | Required |
| [`alt`](https://nextjs.org/docs/app/api-reference/components/image#alt) | `alt="Picture of the author"` | String | Required |
| [`loader`](https://nextjs.org/docs/app/api-reference/components/image#loader) | `loader={imageLoader}` | Function | - |
| [`fill`](https://nextjs.org/docs/app/api-reference/components/image#fill) | `fill={true}` | Boolean | - |
| [`sizes`](https://nextjs.org/docs/app/api-reference/components/image#sizes) | `sizes="(max-width: 768px) 100vw, 33vw"` | String | - |
| [`quality`](https://nextjs.org/docs/app/api-reference/components/image#quality) | `quality={80}` | Integer (1-100) | - |
| [`priority`](https://nextjs.org/docs/app/api-reference/components/image#priority) | `priority={true}` | Boolean | - |
| [`placeholder`](https://nextjs.org/docs/app/api-reference/components/image#placeholder) | `placeholder="blur"` | String | - |
| [`style`](https://nextjs.org/docs/app/api-reference/components/image#style) | `style={{objectFit: "contain"}}` | Object | - |
| [`onLoadingComplete`](https://nextjs.org/docs/app/api-reference/components/image#onloadingcomplete) | `onLoadingComplete={img => done())}` | Function | Deprecated |
| [`onLoad`](https://nextjs.org/docs/app/api-reference/components/image#onload) | `onLoad={event => done())}` | Function | - |
| [`onError`](https://nextjs.org/docs/app/api-reference/components/image#onerror) | `onError(event => fail()}` | Function | - |
| [`loading`](https://nextjs.org/docs/app/api-reference/components/image#loading) | `loading="lazy"` | String | - |
| [`blurDataURL`](https://nextjs.org/docs/app/api-reference/components/image#blurdataurl) | `blurDataURL="data:image/jpeg..."` | String | - |
| [`overrideSrc`](https://nextjs.org/docs/app/api-reference/components/image#overridesrc) | `overrideSrc="/seo.png"` | String | - |

## [Required Props](https://nextjs.org/docs/app/api-reference/components/image\#required-props)

The Image Component requires the following properties: `src`, `alt`, `width` and `height` (or `fill`).

app/page.js

```code-block_code__isn_V
import Image from 'next/image'

export default function Page() {
  return (
    <div>
      <Image
        src="/profile.png"
        width={500}
        height={500}
        alt="Picture of the author"
      />
    </div>
  )
}
```

### [`src`](https://nextjs.org/docs/app/api-reference/components/image\#src)

Must be one of the following:

- A [statically imported](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images) image file
- A path string. This can be either an absolute external URL, or an internal path depending on the [loader](https://nextjs.org/docs/app/api-reference/components/image#loader) prop.

When using the default [loader](https://nextjs.org/docs/app/api-reference/components/image#loader), also consider the following for source images:

- When src is an external URL, you must also configure [remotePatterns](https://nextjs.org/docs/app/api-reference/components/image#remotepatterns)
- When src is [animated](https://nextjs.org/docs/app/api-reference/components/image#animated-images) or not a known format (JPEG, PNG, WebP, AVIF, GIF, TIFF) the image will be served as-is
- When src is SVG format, it will be blocked unless [`unoptimized`](https://nextjs.org/docs/app/api-reference/components/image#unoptimized) or [`dangerouslyAllowSVG`](https://nextjs.org/docs/app/api-reference/components/image#dangerouslyallowsvg) is enabled

### [`width`](https://nextjs.org/docs/app/api-reference/components/image\#width)

The `width` property represents the _intrinsic_ image width in pixels. This property is used to infer the correct aspect ratio of the image and avoid layout shift during loading. It does not determine the rendered size of the image, which is controlled by CSS, similar to the `width` attribute in the HTML `<img>` tag.

Required, except for [statically imported images](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images) or images with the [`fill` property](https://nextjs.org/docs/app/api-reference/components/image#fill).

### [`height`](https://nextjs.org/docs/app/api-reference/components/image\#height)

The `height` property represents the _intrinsic_ image height in pixels. This property is used to infer the correct aspect ratio of the image and avoid layout shift during loading. It does not determine the rendered size of the image, which is controlled by CSS, similar to the `height` attribute in the HTML `<img>` tag.

Required, except for [statically imported images](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images) or images with the [`fill` property](https://nextjs.org/docs/app/api-reference/components/image#fill).

> **Good to know:**
>
> - Combined, both `width` and `height` properties are used to determine the aspect ratio of the image which used by browsers to reserve space for the image before it loads.
> - The intrinsic size does not always mean the rendered size in the browser, which will be determined by the parent container. For example, if the parent container is smaller than the intrinsic size, the image will be scaled down to fit the container.
> - You can use the [`fill`](https://nextjs.org/docs/app/api-reference/components/image#fill) property when the width and height are unknown.

### [`alt`](https://nextjs.org/docs/app/api-reference/components/image\#alt)

The `alt` property is used to describe the image for screen readers and search engines. It is also the fallback text if images have been disabled or an error occurs while loading the image.

It should contain text that could replace the image [without changing the meaning of the page](https://html.spec.whatwg.org/multipage/images.html#general-guidelines). It is not meant to supplement the image and should not repeat information that is already provided in the captions above or below the image.

If the image is [purely decorative](https://html.spec.whatwg.org/multipage/images.html#a-purely-decorative-image-that-doesn't-add-any-information) or [not intended for the user](https://html.spec.whatwg.org/multipage/images.html#an-image-not-intended-for-the-user), the `alt` property should be an empty string ( `alt=""`).

[Learn more](https://html.spec.whatwg.org/multipage/images.html#alt)

## [Optional Props](https://nextjs.org/docs/app/api-reference/components/image\#optional-props)

The `<Image />` component accepts a number of additional properties beyond those which are required. This section describes the most commonly-used properties of the Image component. Find details about more rarely-used properties in the [Advanced Props](https://nextjs.org/docs/app/api-reference/components/image#advanced-props) section.

### [`loader`](https://nextjs.org/docs/app/api-reference/components/image\#loader)

A custom function used to resolve image URLs.

A `loader` is a function returning a URL string for the image, given the following parameters:

- [`src`](https://nextjs.org/docs/app/api-reference/components/image#src)
- [`width`](https://nextjs.org/docs/app/api-reference/components/image#width)
- [`quality`](https://nextjs.org/docs/app/api-reference/components/image#quality)

Here is an example of using a custom loader:

```code-block_code__isn_V
'use client'

import Image from 'next/image'

const imageLoader = ({ src, width, quality }) => {
  return `https://example.com/${src}?w=${width}&q=${quality || 75}`
}

export default function Page() {
  return (
    <Image
      loader={imageLoader}
      src="me.png"
      alt="Picture of the author"
      width={500}
      height={500}
    />
  )
}
```

> **Good to know**: Using props like `loader`, which accept a function, requires using [Client Components](https://nextjs.org/docs/app/building-your-application/rendering/client-components) to serialize the provided function.

Alternatively, you can use the [loaderFile](https://nextjs.org/docs/app/api-reference/components/image#loaderfile) configuration in `next.config.js` to configure every instance of `next/image` in your application, without passing a prop.

### [`fill`](https://nextjs.org/docs/app/api-reference/components/image\#fill)

```code-block_code__isn_V
fill={true} // {true} | {false}
```

A boolean that causes the image to fill the parent element, which is useful when the [`width`](https://nextjs.org/docs/app/api-reference/components/image#width) and [`height`](https://nextjs.org/docs/app/api-reference/components/image#height) are unknown.

The parent element _must_ assign `position: "relative"`, `position: "fixed"`, or `position: "absolute"` style.

By default, the img element will automatically be assigned the `position: "absolute"` style.

If no styles are applied to the image, the image will stretch to fit the container. You may prefer to set `object-fit: "contain"` for an image which is letterboxed to fit the container and preserve aspect ratio.

Alternatively, `object-fit: "cover"` will cause the image to fill the entire container and be cropped to preserve aspect ratio.

For more information, see also:

- [`position`](https://developer.mozilla.org/docs/Web/CSS/position)
- [`object-fit`](https://developer.mozilla.org/docs/Web/CSS/object-fit)
- [`object-position`](https://developer.mozilla.org/docs/Web/CSS/object-position)

### [`sizes`](https://nextjs.org/docs/app/api-reference/components/image\#sizes)

A string, similar to a media query, that provides information about how wide the image will be at different breakpoints. The value of `sizes` will greatly affect performance for images using [`fill`](https://nextjs.org/docs/app/api-reference/components/image#fill) or which are [styled to have a responsive size](https://nextjs.org/docs/app/api-reference/components/image#responsive-images).

The `sizes` property serves two important purposes related to image performance:

- First, the value of `sizes` is used by the browser to determine which size of the image to download, from `next/image`'s automatically generated `srcset`. When the browser chooses, it does not yet know the size of the image on the page, so it selects an image that is the same size or larger than the viewport. The `sizes` property allows you to tell the browser that the image will actually be smaller than full screen. If you don't specify a `sizes` value in an image with the `fill` property, a default value of `100vw` (full screen width) is used.
- Second, the `sizes` property changes the behavior of the automatically generated `srcset` value. If no `sizes` value is present, a small `srcset` is generated, suitable for a fixed-size image (1x/2x/etc). If `sizes` is defined, a large `srcset` is generated, suitable for a responsive image (640w/750w/etc). If the `sizes` property includes sizes such as `50vw`, which represent a percentage of the viewport width, then the `srcset` is trimmed to not include any values which are too small to ever be necessary.

For example, if you know your styling will cause an image to be full-width on mobile devices, in a 2-column layout on tablets, and a 3-column layout on desktop displays, you should include a sizes property such as the following:

```code-block_code__isn_V
import Image from 'next/image'

export default function Page() {
  return (
    <div className="grid-element">
      <Image
        fill
        src="/example.png"
        sizes="(max-width: 768px) 100vw, (max-width: 1200px) 50vw, 33vw"
      />
    </div>
  )
}
```

This example `sizes` could have a dramatic effect on performance metrics. Without the `33vw` sizes, the image selected from the server would be 3 times as wide as it needs to be. Because file size is proportional to the square of the width, without `sizes` the user would download an image that's 9 times larger than necessary.

Learn more about `srcset` and `sizes`:

- [web.dev](https://web.dev/learn/design/responsive-images/#sizes)
- [mdn](https://developer.mozilla.org/docs/Web/HTML/Element/img#sizes)

### [`quality`](https://nextjs.org/docs/app/api-reference/components/image\#quality)

```code-block_code__isn_V
quality={75} // {number 1-100}
```

The quality of the optimized image, an integer between `1` and `100`, where `100` is the best quality and therefore largest file size. Defaults to `75`.

If the [`qualities`](https://nextjs.org/docs/app/api-reference/components/image#qualities) configuration is defined in `next.config.js`, the `quality` prop must match one of the values defined in the configuration.

> **Good to know**: If the original source image was already low quality, setting the quality prop too high could cause the resulting optimized image to be larger than the original source image.

### [`priority`](https://nextjs.org/docs/app/api-reference/components/image\#priority)

```code-block_code__isn_V
priority={false} // {false} | {true}
```

When true, Next.js will
[preload](https://web.dev/preload-responsive-images/) the image. Lazy loading is automatically disabled for images using `priority`. If the [`loading`](https://nextjs.org/docs/app/api-reference/components/image#loading) property is also used and set to `lazy`, the `priority` property can't be used. The [`loading`](https://nextjs.org/docs/app/api-reference/components/image#loading) property is only meant for advanced use cases. Remove `loading` when `priority` is needed.

You should use the `priority` property on any image detected as the [Largest Contentful Paint (LCP)](https://nextjs.org/learn/seo/web-performance/lcp) element. It may be appropriate to have multiple priority images, as different images may be the LCP element for different viewport sizes.

Should only be used when the image is visible above the fold. Defaults to `false`.

### [`placeholder`](https://nextjs.org/docs/app/api-reference/components/image\#placeholder)

```code-block_code__isn_V
placeholder = 'empty' // "empty" | "blur" | "data:image/..."
```

A placeholder to use while the image is loading. Possible values are `blur`, `empty`, or `data:image/...`. Defaults to `empty`.

When `blur`, the [`blurDataURL`](https://nextjs.org/docs/app/api-reference/components/image#blurdataurl) property will be used as the placeholder. If `src` is an object from a [static import](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images) and the imported image is `.jpg`, `.png`, `.webp`, or `.avif`, then `blurDataURL` will be automatically populated, except when the image is detected to be animated.

For dynamic images, you must provide the [`blurDataURL`](https://nextjs.org/docs/app/api-reference/components/image#blurdataurl) property. Solutions such as [Plaiceholder](https://github.com/joe-bell/plaiceholder) can help with `base64` generation.

When `data:image/...`, the [Data URL](https://developer.mozilla.org/docs/Web/HTTP/Basics_of_HTTP/Data_URIs) will be used as the placeholder while the image is loading.

When `empty`, there will be no placeholder while the image is loading, only empty space.

Try it out:

- [Demo the `blur` placeholder](https://image-component.nextjs.gallery/placeholder)
- [Demo the shimmer effect with data URL `placeholder` prop](https://image-component.nextjs.gallery/shimmer)
- [Demo the color effect with `blurDataURL` prop](https://image-component.nextjs.gallery/color)

## [Advanced Props](https://nextjs.org/docs/app/api-reference/components/image\#advanced-props)

In some cases, you may need more advanced usage. The `<Image />` component optionally accepts the following advanced properties.

### [`style`](https://nextjs.org/docs/app/api-reference/components/image\#style)

Allows passing CSS styles to the underlying image element.

components/ProfileImage.js

```code-block_code__isn_V
const imageStyle = {
  borderRadius: '50%',
  border: '1px solid #fff',
}

export default function ProfileImage() {
  return <Image src="..." style={imageStyle} />
}
```

Remember that the required width and height props can interact with your styling. If you use styling to modify an image's width, you should also style its height to `auto` to preserve its intrinsic aspect ratio, or your image will be distorted.

### [`onLoadingComplete`](https://nextjs.org/docs/app/api-reference/components/image\#onloadingcomplete)

```code-block_code__isn_V
'use client'

<Image onLoadingComplete={(img) => console.log(img.naturalWidth)} />
```

> **Warning**: Deprecated since Next.js 14 in favor of [`onLoad`](https://nextjs.org/docs/app/api-reference/components/image#onload).

A callback function that is invoked once the image is completely loaded and the [placeholder](https://nextjs.org/docs/app/api-reference/components/image#placeholder) has been removed.

The callback function will be called with one argument, a reference to the underlying `<img>` element.

> **Good to know**: Using props like `onLoadingComplete`, which accept a function, requires using [Client Components](https://nextjs.org/docs/app/building-your-application/rendering/client-components) to serialize the provided function.

### [`onLoad`](https://nextjs.org/docs/app/api-reference/components/image\#onload)

```code-block_code__isn_V
<Image onLoad={(e) => console.log(e.target.naturalWidth)} />
```

A callback function that is invoked once the image is completely loaded and the [placeholder](https://nextjs.org/docs/app/api-reference/components/image#placeholder) has been removed.

The callback function will be called with one argument, the Event which has a `target` that references the underlying `<img>` element.

> **Good to know**: Using props like `onLoad`, which accept a function, requires using [Client Components](https://nextjs.org/docs/app/building-your-application/rendering/client-components) to serialize the provided function.

### [`onError`](https://nextjs.org/docs/app/api-reference/components/image\#onerror)

```code-block_code__isn_V
<Image onError={(e) => console.error(e.target.id)} />
```

A callback function that is invoked if the image fails to load.

> **Good to know**: Using props like `onError`, which accept a function, requires using [Client Components](https://nextjs.org/docs/app/building-your-application/rendering/client-components) to serialize the provided function.

### [`loading`](https://nextjs.org/docs/app/api-reference/components/image\#loading)

```code-block_code__isn_V
loading = 'lazy' // {lazy} | {eager}
```

The loading behavior of the image. Defaults to `lazy`.

When `lazy`, defer loading the image until it reaches a calculated distance from
the viewport.

When `eager`, load the image immediately.

Learn more about the [`loading` attribute](https://developer.mozilla.org/docs/Web/HTML/Element/img#loading).

### [`blurDataURL`](https://nextjs.org/docs/app/api-reference/components/image\#blurdataurl)

A [Data URL](https://developer.mozilla.org/docs/Web/HTTP/Basics_of_HTTP/Data_URIs) to
be used as a placeholder image before the `src` image successfully loads. Only takes effect when combined
with [`placeholder="blur"`](https://nextjs.org/docs/app/api-reference/components/image#placeholder).

Must be a base64-encoded image. It will be enlarged and blurred, so a very small image (10px or
less) is recommended. Including larger images as placeholders may harm your application performance.

Try it out:

- [Demo the default `blurDataURL` prop](https://image-component.nextjs.gallery/placeholder)
- [Demo the color effect with `blurDataURL` prop](https://image-component.nextjs.gallery/color)

You can also [generate a solid color Data URL](https://png-pixel.com/) to match the image.

### [`unoptimized`](https://nextjs.org/docs/app/api-reference/components/image\#unoptimized)

```code-block_code__isn_V
unoptimized = {false} // {false} | {true}
```

When true, the source image will be served as-is from the `src` instead of changing quality, size, or format. Defaults to `false`.

This is useful for images that do not benefit from optimization such as small images (less than 1KB), vector images (SVG), or animated images (GIF).

```code-block_code__isn_V
import Image from 'next/image'

const UnoptimizedImage = (props) => {
  return <Image {...props} unoptimized />
}
```

Since Next.js 12.3.0, this prop can be assigned to all images by updating `next.config.js` with the following configuration:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    unoptimized: true,
  },
}
```

### [`overrideSrc`](https://nextjs.org/docs/app/api-reference/components/image\#overridesrc)

When providing the `src` prop to the `<Image>` component, both the `srcset` and `src` attributes are generated automatically for the resulting `<img>`.

input.js

```code-block_code__isn_V
<Image src="/me.jpg" />
```

output.html

```code-block_code__isn_V
<img
  srcset="
    /_next/image?url=%2Fme.jpg&w=640&q=75 1x,
    /_next/image?url=%2Fme.jpg&w=828&q=75 2x
  "
  src="/_next/image?url=%2Fme.jpg&w=828&q=75"
/>
```

In some cases, it is not desirable to have the `src` attribute generated and you may wish to override it using the `overrideSrc` prop.

For example, when upgrading an existing website from `<img>` to `<Image>`, you may wish to maintain the same `src` attribute for SEO purposes such as image ranking or avoiding recrawl.

input.js

```code-block_code__isn_V
<Image src="/me.jpg" overrideSrc="/override.jpg" />
```

output.html

```code-block_code__isn_V
<img
  srcset="
    /_next/image?url=%2Fme.jpg&w=640&q=75 1x,
    /_next/image?url=%2Fme.jpg&w=828&q=75 2x
  "
  src="/override.jpg"
/>
```

### [decoding](https://nextjs.org/docs/app/api-reference/components/image\#decoding)

A hint to the browser indicating if it should wait for the image to be decoded before presenting other content updates or not. Defaults to `async`.

Possible values are the following:

- `async` \- Asynchronously decode the image and allow other content to be rendered before it completes.
- `sync` \- Synchronously decode the image for atomic presentation with other content.
- `auto` \- No preference for the decoding mode; the browser decides what's best.

Learn more about the [`decoding` attribute](https://developer.mozilla.org/docs/Web/HTML/Element/img#decoding).

### [Other Props](https://nextjs.org/docs/app/api-reference/components/image\#other-props)

Other properties on the `<Image />` component will be passed to the underlying
`img` element with the exception of the following:

- `srcSet`. Use [Device Sizes](https://nextjs.org/docs/app/api-reference/components/image#devicesizes) instead.

## [Configuration Options](https://nextjs.org/docs/app/api-reference/components/image\#configuration-options)

In addition to props, you can configure the Image Component in `next.config.js`. The following options are available:

### [`localPatterns`](https://nextjs.org/docs/app/api-reference/components/image\#localpatterns)

You can optionally configure `localPatterns` in your `next.config.js` file in order to allow specific paths to be optimized and block all others paths.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    localPatterns: [\
      {\
        pathname: '/assets/images/**',\
        search: '',\
      },\
    ],
  },
}
```

> **Good to know**: The example above will ensure the `src` property of `next/image` must start with `/assets/images/` and must not have a query string. Attempting to optimize any other path will respond with 400 Bad Request.

### [`remotePatterns`](https://nextjs.org/docs/app/api-reference/components/image\#remotepatterns)

To protect your application from malicious users, configuration is required in order to use external images. This ensures that only external images from your account can be served from the Next.js Image Optimization API. These external images can be configured with the `remotePatterns` property in your `next.config.js` file, as shown below:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    remotePatterns: [\
      {\
        protocol: 'https',\
        hostname: 'example.com',\
        port: '',\
        pathname: '/account123/**',\
        search: '',\
      },\
    ],
  },
}
```

> **Good to know**: The example above will ensure the `src` property of `next/image` must start with `https://example.com/account123/` and must not have a query string. Any other protocol, hostname, port, or unmatched path will respond with 400 Bad Request.

Below is an example of the `remotePatterns` property in the `next.config.js` file using a wildcard pattern in the `hostname`:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    remotePatterns: [\
      {\
        protocol: 'https',\
        hostname: '**.example.com',\
        port: '',\
        search: '',\
      },\
    ],
  },
}
```

> **Good to know**: The example above will ensure the `src` property of `next/image` must start with `https://img1.example.com` or `https://me.avatar.example.com` or any number of subdomains. It cannot have a port or query string. Any other protocol or unmatched hostname will respond with 400 Bad Request.

Wildcard patterns can be used for both `pathname` and `hostname` and have the following syntax:

- `*` match a single path segment or subdomain
- `**` match any number of path segments at the end or subdomains at the beginning

The `**` syntax does not work in the middle of the pattern.

> **Good to know**: When omitting `protocol`, `port`, `pathname`, or `search` then the wildcard `**` is implied. This is not recommended because it may allow malicious actors to optimize urls you did not intend.

Below is an example of the `remotePatterns` property in the `next.config.js` file using `search`:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    remotePatterns: [\
      {\
        protocol: 'https',\
        hostname: 'assets.example.com',\
        search: '?v=1727111025337',\
      },\
    ],
  },
}
```

> **Good to know**: The example above will ensure the `src` property of `next/image` must start with `https://assets.example.com` and must have the exact query string `?v=1727111025337`. Any other protocol or query string will respond with 400 Bad Request.

### [`domains`](https://nextjs.org/docs/app/api-reference/components/image\#domains)

> **Warning**: Deprecated since Next.js 14 in favor of strict [`remotePatterns`](https://nextjs.org/docs/app/api-reference/components/image#remotepatterns) in order to protect your application from malicious users. Only use `domains` if you own all the content served from the domain.

Similar to [`remotePatterns`](https://nextjs.org/docs/app/api-reference/components/image#remotepatterns), the `domains` configuration can be used to provide a list of allowed hostnames for external images.

However, the `domains` configuration does not support wildcard pattern matching and it cannot restrict protocol, port, or pathname.

Below is an example of the `domains` property in the `next.config.js` file:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    domains: ['assets.acme.com'],
  },
}
```

### [`loaderFile`](https://nextjs.org/docs/app/api-reference/components/image\#loaderfile)

If you want to use a cloud provider to optimize images instead of using the Next.js built-in Image Optimization API, you can configure the `loaderFile` in your `next.config.js` like the following:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    loader: 'custom',
    loaderFile: './my/image/loader.js',
  },
}
```

This must point to a file relative to the root of your Next.js application. The file must export a default function that returns a string, for example:

my/image/loader.js

```code-block_code__isn_V
'use client'

export default function myImageLoader({ src, width, quality }) {
  return `https://example.com/${src}?w=${width}&q=${quality || 75}`
}
```

Alternatively, you can use the [`loader` prop](https://nextjs.org/docs/app/api-reference/components/image#loader) to configure each instance of `next/image`.

Examples:

- [Custom Image Loader Configuration](https://nextjs.org/docs/app/api-reference/config/next-config-js/images#example-loader-configuration)

> **Good to know**: Customizing the image loader file, which accepts a function, requires using [Client Components](https://nextjs.org/docs/app/building-your-application/rendering/client-components) to serialize the provided function.

## [Advanced](https://nextjs.org/docs/app/api-reference/components/image\#advanced)

The following configuration is for advanced use cases and is usually not necessary. If you choose to configure the properties below, you will override any changes to the Next.js defaults in future updates.

### [`deviceSizes`](https://nextjs.org/docs/app/api-reference/components/image\#devicesizes)

If you know the expected device widths of your users, you can specify a list of device width breakpoints using the `deviceSizes` property in `next.config.js`. These widths are used when the `next/image` component uses [`sizes`](https://nextjs.org/docs/app/api-reference/components/image#sizes) prop to ensure the correct image is served for user's device.

If no configuration is provided, the default below is used.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    deviceSizes: [640, 750, 828, 1080, 1200, 1920, 2048, 3840],
  },
}
```

### [`imageSizes`](https://nextjs.org/docs/app/api-reference/components/image\#imagesizes)

You can specify a list of image widths using the `images.imageSizes` property in your `next.config.js` file. These widths are concatenated with the array of [device sizes](https://nextjs.org/docs/app/api-reference/components/image#devicesizes) to form the full array of sizes used to generate image [srcset](https://developer.mozilla.org/docs/Web/API/HTMLImageElement/srcset) s.

The reason there are two separate lists is that imageSizes is only used for images which provide a [`sizes`](https://nextjs.org/docs/app/api-reference/components/image#sizes) prop, which indicates that the image is less than the full width of the screen. **Therefore, the sizes in imageSizes should all be smaller than the smallest size in deviceSizes.**

If no configuration is provided, the default below is used.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    imageSizes: [16, 32, 48, 64, 96, 128, 256, 384],
  },
}
```

### [`qualities`](https://nextjs.org/docs/app/api-reference/components/image\#qualities)

The default [Image Optimization API](https://nextjs.org/docs/app/api-reference/components/image#loader) will automatically allow all qualities from 1 to 100. If you wish to restrict the allowed qualities, you can add configuration to `next.config.js`.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    qualities: [25, 50, 75],
  },
}
```

In this example above, only three qualities are allowed: 25, 50, and 75. If the [`quality`](https://nextjs.org/docs/app/api-reference/components/image#quality) prop does not match a value in this array, the image will fail with 400 Bad Request.

### [`formats`](https://nextjs.org/docs/app/api-reference/components/image\#formats)

The default [Image Optimization API](https://nextjs.org/docs/app/api-reference/components/image#loader) will automatically detect the browser's supported image formats via the request's `Accept` header in order to determine the best output format.

If the `Accept` header matches more than one of the configured formats, the first match in the array is used. Therefore, the array order matters. If there is no match (or the source image is [animated](https://nextjs.org/docs/app/api-reference/components/image#animated-images)), the Image Optimization API will fallback to the original image's format.

If no configuration is provided, the default below is used.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    formats: ['image/webp'],
  },
}
```

You can enable AVIF support, which will fallback to the original format of the src image if the browser [does not support AVIF](https://caniuse.com/avif):

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    formats: ['image/avif'],
  },
}
```

> **Good to know**:
>
> - We still recommend using WebP for most use cases.
> - AVIF generally takes 50% longer to encode but it compresses 20% smaller compared to WebP. This means that the first time an image is requested, it will typically be slower and then subsequent requests that are cached will be faster.
> - If you self-host with a Proxy/CDN in front of Next.js, you must configure the Proxy to forward the `Accept` header.

## [Caching Behavior](https://nextjs.org/docs/app/api-reference/components/image\#caching-behavior)

The following describes the caching algorithm for the default [loader](https://nextjs.org/docs/app/api-reference/components/image#loader). For all other loaders, please refer to your cloud provider's documentation.

Images are optimized dynamically upon request and stored in the `<distDir>/cache/images` directory. The optimized image file will be served for subsequent requests until the expiration is reached. When a request is made that matches a cached but expired file, the expired image is served stale immediately. Then the image is optimized again in the background (also called revalidation) and saved to the cache with the new expiration date.

The cache status of an image can be determined by reading the value of the `x-nextjs-cache` response header. The possible values are the following:

- `MISS` \- the path is not in the cache (occurs at most once, on the first visit)
- `STALE` \- the path is in the cache but exceeded the revalidate time so it will be updated in the background
- `HIT` \- the path is in the cache and has not exceeded the revalidate time

The expiration (or rather Max Age) is defined by either the [`minimumCacheTTL`](https://nextjs.org/docs/app/api-reference/components/image#minimumcachettl) configuration or the upstream image `Cache-Control` header, whichever is larger. Specifically, the `max-age` value of the `Cache-Control` header is used. If both `s-maxage` and `max-age` are found, then `s-maxage` is preferred. The `max-age` is also passed-through to any downstream clients including CDNs and browsers.

- You can configure [`minimumCacheTTL`](https://nextjs.org/docs/app/api-reference/components/image#minimumcachettl) to increase the cache duration when the upstream image does not include `Cache-Control` header or the value is very low.
- You can configure [`deviceSizes`](https://nextjs.org/docs/app/api-reference/components/image#devicesizes) and [`imageSizes`](https://nextjs.org/docs/app/api-reference/components/image#imagesizes) to reduce the total number of possible generated images.
- You can configure [formats](https://nextjs.org/docs/app/api-reference/components/image#formats) to disable multiple formats in favor of a single image format.

### [`minimumCacheTTL`](https://nextjs.org/docs/app/api-reference/components/image\#minimumcachettl)

You can configure the Time to Live (TTL) in seconds for cached optimized images. In many cases, it's better to use a [Static Image Import](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images) which will automatically hash the file contents and cache the image forever with a `Cache-Control` header of `immutable`.

If no configuration is provided, the default below is used.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    minimumCacheTTL: 60, // 1 minute
  },
}
```

You can increase the TTL to reduce the number of revalidations and potentionally lower cost:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    minimumCacheTTL: 2678400, // 31 days
  },
}
```

The expiration (or rather Max Age) of the optimized image is defined by either the `minimumCacheTTL` or the upstream image `Cache-Control` header, whichever is larger.

If you need to change the caching behavior per image, you can configure [`headers`](https://nextjs.org/docs/app/api-reference/config/next-config-js/headers) to set the `Cache-Control` header on the upstream image (e.g. `/some-asset.jpg`, not `/_next/image` itself).

There is no mechanism to invalidate the cache at this time, so its best to keep `minimumCacheTTL` low. Otherwise you may need to manually change the [`src`](https://nextjs.org/docs/app/api-reference/components/image#src) prop or delete `<distDir>/cache/images`.

### [`disableStaticImages`](https://nextjs.org/docs/app/api-reference/components/image\#disablestaticimages)

The default behavior allows you to import static files such as `import icon from './icon.png'` and then pass that to the `src` property.

In some cases, you may wish to disable this feature if it conflicts with other plugins that expect the import to behave differently.

You can disable static image imports inside your `next.config.js`:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    disableStaticImages: true,
  },
}
```

### [`dangerouslyAllowSVG`](https://nextjs.org/docs/app/api-reference/components/image\#dangerouslyallowsvg)

The default [loader](https://nextjs.org/docs/app/api-reference/components/image#loader) does not optimize SVG images for a few reasons. First, SVG is a vector format meaning it can be resized losslessly. Second, SVG has many of the same features as HTML/CSS, which can lead to vulnerabilities without proper [Content Security Policy (CSP) headers](https://nextjs.org/docs/app/api-reference/config/next-config-js/headers#content-security-policy).

Therefore, we recommended using the [`unoptimized`](https://nextjs.org/docs/app/api-reference/components/image#unoptimized) prop when the [`src`](https://nextjs.org/docs/app/api-reference/components/image#src) prop is known to be SVG. This happens automatically when `src` ends with `".svg"`.

However, if you need to serve SVG images with the default Image Optimization API, you can set `dangerouslyAllowSVG` inside your `next.config.js`:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    dangerouslyAllowSVG: true,
    contentDispositionType: 'attachment',
    contentSecurityPolicy: "default-src 'self'; script-src 'none'; sandbox;",
  },
}
```

In addition, it is strongly recommended to also set `contentDispositionType` to force the browser to download the image, as well as `contentSecurityPolicy` to prevent scripts embedded in the image from executing.

### [`contentDispositionType`](https://nextjs.org/docs/app/api-reference/components/image\#contentdispositiontype)

The default [loader](https://nextjs.org/docs/app/api-reference/components/image#loader) sets the [`Content-Disposition`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Disposition#as_a_response_header_for_the_main_body) header to `attachment` for added protection since the API can serve arbitrary remote images.

The default value is `attachment` which forces the browser to download the image when visiting directly. This is particularly important when [`dangerouslyAllowSVG`](https://nextjs.org/docs/app/api-reference/components/image#dangerouslyallowsvg) is true.

You can optionally configure `inline` to allow the browser to render the image when visiting directly, without downloading it.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    contentDispositionType: 'inline',
  },
}
```

## [Animated Images](https://nextjs.org/docs/app/api-reference/components/image\#animated-images)

The default [loader](https://nextjs.org/docs/app/api-reference/components/image#loader) will automatically bypass Image Optimization for animated images and serve the image as-is.

Auto-detection for animated files is best-effort and supports GIF, APNG, and WebP. If you want to explicitly bypass Image Optimization for a given animated image, use the [unoptimized](https://nextjs.org/docs/app/api-reference/components/image#unoptimized) prop.

## [Responsive Images](https://nextjs.org/docs/app/api-reference/components/image\#responsive-images)

The default generated `srcset` contains `1x` and `2x` images in order to support different device pixel ratios. However, you may wish to render a responsive image that stretches with the viewport. In that case, you'll need to set [`sizes`](https://nextjs.org/docs/app/api-reference/components/image#sizes) as well as `style` (or `className`).

You can render a responsive image using one of the following methods below.

### [Responsive image using a static import](https://nextjs.org/docs/app/api-reference/components/image\#responsive-image-using-a-static-import)

If the source image is not dynamic, you can statically import to create a responsive image:

components/author.js

```code-block_code__isn_V
import Image from 'next/image'
import me from '../photos/me.jpg'

export default function Author() {
  return (
    <Image
      src={me}
      alt="Picture of the author"
      sizes="100vw"
      style={{
        width: '100%',
        height: 'auto',
      }}
    />
  )
}
```

Try it out:

- [Demo the image responsive to viewport](https://image-component.nextjs.gallery/responsive)

### [Responsive image with aspect ratio](https://nextjs.org/docs/app/api-reference/components/image\#responsive-image-with-aspect-ratio)

If the source image is a dynamic or a remote url, you will also need to provide `width` and `height` to set the correct aspect ratio of the responsive image:

components/page.js

```code-block_code__isn_V
import Image from 'next/image'

export default function Page({ photoUrl }) {
  return (
    <Image
      src={photoUrl}
      alt="Picture of the author"
      sizes="100vw"
      style={{
        width: '100%',
        height: 'auto',
      }}
      width={500}
      height={300}
    />
  )
}
```

Try it out:

- [Demo the image responsive to viewport](https://image-component.nextjs.gallery/responsive)

### [Responsive image with `fill`](https://nextjs.org/docs/app/api-reference/components/image\#responsive-image-with-fill)

If you don't know the aspect ratio, you will need to set the [`fill`](https://nextjs.org/docs/app/api-reference/components/image#fill) prop and set `position: relative` on the parent. Optionally, you can set `object-fit` style depending on the desired stretch vs crop behavior:

app/page.js

```code-block_code__isn_V
import Image from 'next/image'

export default function Page({ photoUrl }) {
  return (
    <div style={{ position: 'relative', width: '300px', height: '500px' }}>
      <Image
        src={photoUrl}
        alt="Picture of the author"
        sizes="300px"
        fill
        style={{
          objectFit: 'contain',
        }}
      />
    </div>
  )
}
```

Try it out:

- [Demo the `fill` prop](https://image-component.nextjs.gallery/fill)

## [Theme Detection CSS](https://nextjs.org/docs/app/api-reference/components/image\#theme-detection-css)

If you want to display a different image for light and dark mode, you can create a new component that wraps two `<Image>` components and reveals the correct one based on a CSS media query.

components/theme-image.module.css

```code-block_code__isn_V
.imgDark {
  display: none;
}

@media (prefers-color-scheme: dark) {
  .imgLight {
    display: none;
  }
  .imgDark {
    display: unset;
  }
}
```

components/theme-image.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import styles from './theme-image.module.css'
import Image, { ImageProps } from 'next/image'

type Props = Omit<ImageProps, 'src' | 'priority' | 'loading'> & {
  srcLight: string
  srcDark: string
}

const ThemeImage = (props: Props) => {
  const { srcLight, srcDark, ...rest } = props

  return (
    <>
      <Image {...rest} src={srcLight} className={styles.imgLight} />
      <Image {...rest} src={srcDark} className={styles.imgDark} />
    </>
  )
}
```

> **Good to know**: The default behavior of `loading="lazy"` ensures that only the correct image is loaded. You cannot use `priority` or `loading="eager"` because that would cause both images to load. Instead, you can use [`fetchPriority="high"`](https://developer.mozilla.org/docs/Web/API/HTMLImageElement/fetchPriority).

Try it out:

- [Demo light/dark mode theme detection](https://image-component.nextjs.gallery/theme)

## [getImageProps](https://nextjs.org/docs/app/api-reference/components/image\#getimageprops)

For more advanced use cases, you can call `getImageProps()` to get the props that would be passed to the underlying `<img>` element, and instead pass to them to another component, style, canvas, etc.

This also avoid calling React `useState()` so it can lead to better performance, but it cannot be used with the [`placeholder`](https://nextjs.org/docs/app/api-reference/components/image#placeholder) prop because the placeholder will never be removed.

### [Theme Detection Picture](https://nextjs.org/docs/app/api-reference/components/image\#theme-detection-picture)

If you want to display a different image for light and dark mode, you can use the [`<picture>`](https://developer.mozilla.org/docs/Web/HTML/Element/picture) element to display a different image based on the user's [preferred color scheme](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme).

app/page.js

```code-block_code__isn_V
import { getImageProps } from 'next/image'

export default function Page() {
  const common = { alt: 'Theme Example', width: 800, height: 400 }
  const {
    props: { srcSet: dark },
  } = getImageProps({ ...common, src: '/dark.png' })
  const {
    props: { srcSet: light, ...rest },
  } = getImageProps({ ...common, src: '/light.png' })

  return (
    <picture>
      <source media="(prefers-color-scheme: dark)" srcSet={dark} />
      <source media="(prefers-color-scheme: light)" srcSet={light} />
      <img {...rest} />
    </picture>
  )
}
```

### [Art Direction](https://nextjs.org/docs/app/api-reference/components/image\#art-direction)

If you want to display a different image for mobile and desktop, sometimes called [Art Direction](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images#art_direction), you can provide different `src`, `width`, `height`, and `quality` props to `getImageProps()`.

app/page.js

```code-block_code__isn_V
import { getImageProps } from 'next/image'

export default function Home() {
  const common = { alt: 'Art Direction Example', sizes: '100vw' }
  const {
    props: { srcSet: desktop },
  } = getImageProps({
    ...common,
    width: 1440,
    height: 875,
    quality: 80,
    src: '/desktop.jpg',
  })
  const {
    props: { srcSet: mobile, ...rest },
  } = getImageProps({
    ...common,
    width: 750,
    height: 1334,
    quality: 70,
    src: '/mobile.jpg',
  })

  return (
    <picture>
      <source media="(min-width: 1000px)" srcSet={desktop} />
      <source media="(min-width: 500px)" srcSet={mobile} />
      <img {...rest} style={{ width: '100%', height: 'auto' }} />
    </picture>
  )
}
```

### [Background CSS](https://nextjs.org/docs/app/api-reference/components/image\#background-css)

You can even convert the `srcSet` string to the [`image-set()`](https://developer.mozilla.org/en-US/docs/Web/CSS/image/image-set) CSS function to optimize a background image.

app/page.js

```code-block_code__isn_V
import { getImageProps } from 'next/image'

function getBackgroundImage(srcSet = '') {
  const imageSet = srcSet
    .split(', ')
    .map((str) => {
      const [url, dpi] = str.split(' ')
      return `url("${url}") ${dpi}`
    })
    .join(', ')
  return `image-set(${imageSet})`
}

export default function Home() {
  const {
    props: { srcSet },
  } = getImageProps({ alt: '', width: 128, height: 128, src: '/img.png' })
  const backgroundImage = getBackgroundImage(srcSet)
  const style = { height: '100vh', width: '100vw', backgroundImage }

  return (
    <main style={style}>
      <h1>Hello World</h1>
    </main>
  )
}
```

## [Known Browser Bugs](https://nextjs.org/docs/app/api-reference/components/image\#known-browser-bugs)

This `next/image` component uses browser native [lazy loading](https://caniuse.com/loading-lazy-attr), which may fallback to eager loading for older browsers before Safari 15.4. When using the blur-up placeholder, older browsers before Safari 12 will fallback to empty placeholder. When using styles with `width`/ `height` of `auto`, it is possible to cause [Layout Shift](https://web.dev/cls/) on older browsers before Safari 15 that don't [preserve the aspect ratio](https://caniuse.com/mdn-html_elements_img_aspect_ratio_computed_from_attributes). For more details, see [this MDN video](https://www.youtube.com/watch?v=4-d_SoCHeWE).

- [Safari 15 - 16.3](https://bugs.webkit.org/show_bug.cgi?id=243601) display a gray border while loading. Safari 16.4 [fixed this issue](https://webkit.org/blog/13966/webkit-features-in-safari-16-4/#:~:text=Now%20in%20Safari%2016.4%2C%20a%20gray%20line%20no%20longer%20appears%20to%20mark%20the%20space%20where%20a%20lazy%2Dloaded%20image%20will%20appear%20once%20it%E2%80%99s%20been%20loaded.). Possible solutions:
  - Use CSS `@supports (font: -apple-system-body) and (-webkit-appearance: none) { img[loading="lazy"] { clip-path: inset(0.6px) } }`
  - Use [`priority`](https://nextjs.org/docs/app/api-reference/components/image#priority) if the image is above the fold
- [Firefox 67+](https://bugzilla.mozilla.org/show_bug.cgi?id=1556156) displays a white background while loading. Possible solutions:
  - Enable [AVIF `formats`](https://nextjs.org/docs/app/api-reference/components/image#formats)
  - Use [`placeholder`](https://nextjs.org/docs/app/api-reference/components/image#placeholder)

## [Version History](https://nextjs.org/docs/app/api-reference/components/image\#version-history)

| Version | Changes |
| --- | --- |
| `v15.0.0` | `contentDispositionType` configuration default changed to `attachment`. |
| `v14.2.23` | `qualities` configuration added. |
| `v14.2.15` | `decoding` prop added and `localPatterns` configuration added. |
| `v14.2.14` | `remotePatterns.search` prop added. |
| `v14.2.0` | `overrideSrc` prop added. |
| `v14.1.0` | `getImageProps()` is stable. |
| `v14.0.0` | `onLoadingComplete` prop and `domains` config deprecated. |
| `v13.4.14` | `placeholder` prop support for `data:/image...` |
| `v13.2.0` | `contentDispositionType` configuration added. |
| `v13.0.6` | `ref` prop added. |
| `v13.0.0` | The `next/image` import was renamed to `next/legacy/image`. The `next/future/image` import was renamed to `next/image`. A [codemod is available](https://nextjs.org/docs/app/building-your-application/upgrading/codemods#next-image-to-legacy-image) to safely and automatically rename your imports. `<span>` wrapper removed. `layout`, `objectFit`, `objectPosition`, `lazyBoundary`, `lazyRoot` props removed. `alt` is required. `onLoadingComplete` receives reference to `img` element. Built-in loader config removed. |
| `v12.3.0` | `remotePatterns` and `unoptimized` configuration is stable. |
| `v12.2.0` | Experimental `remotePatterns` and experimental `unoptimized` configuration added. `layout="raw"` removed. |
| `v12.1.1` | `style` prop added. Experimental support for `layout="raw"` added. |
| `v12.1.0` | `dangerouslyAllowSVG` and `contentSecurityPolicy` configuration added. |
| `v12.0.9` | `lazyRoot` prop added. |
| `v12.0.0` | `formats` configuration added.<br>AVIF support added.<br>Wrapper `<div>` changed to `<span>`. |
| `v11.1.0` | `onLoadingComplete` and `lazyBoundary` props added. |
| `v11.0.0` | `src` prop support for static import.<br>`placeholder` prop added.<br>`blurDataURL` prop added. |
| `v10.0.5` | `loader` prop added. |
| `v10.0.1` | `layout` prop added. |
| `v10.0.0` | `next/image` introduced. |

Was this helpful?

supported.

Send

## Next.js Link Component
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [Components](https://nextjs.org/docs/app/api-reference/components) Link

# Link

`<Link>` is a React component that extends the HTML `<a>` element to provide [prefetching](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#2-prefetching) and client-side navigation between routes. It is the primary way to navigate between routes in Next.js.

Basic usage:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return <Link href="/dashboard">Dashboard</Link>
}
```

## [Reference](https://nextjs.org/docs/app/api-reference/components/link\#reference)

The following props can be passed to the `<Link>` component:

| Prop | Example | Type | Required |
| --- | --- | --- | --- |
| [`href`](https://nextjs.org/docs/app/api-reference/components/link#href-required) | `href="/dashboard"` | String or Object | Yes |
| [`replace`](https://nextjs.org/docs/app/api-reference/components/link#replace) | `replace={false}` | Boolean | - |
| [`scroll`](https://nextjs.org/docs/app/api-reference/components/link#scroll) | `scroll={false}` | Boolean | - |
| [`prefetch`](https://nextjs.org/docs/app/api-reference/components/link#prefetch) | `prefetch={false}` | Boolean or null | - |

> **Good to know**: `<a>` tag attributes such as `className` or `target="_blank"` can be added to `<Link>` as props and will be passed to the underlying `<a>` element.

### [`href` (required)](https://nextjs.org/docs/app/api-reference/components/link\#href-required)

The path or URL to navigate to.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

// Navigate to /about?name=test
export default function Page() {
  return (
    <Link
      href={{
        pathname: '/about',
        query: { name: 'test' },
      }}
    >
      About
    </Link>
  )
}
```

### [`replace`](https://nextjs.org/docs/app/api-reference/components/link\#replace)

**Defaults to `false`.** When `true`, `next/link` will replace the current history state instead of adding a new URL into the [browser's history](https://developer.mozilla.org/docs/Web/API/History_API) stack.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return (
    <Link href="/dashboard" replace>
      Dashboard
    </Link>
  )
}
```

### [`scroll`](https://nextjs.org/docs/app/api-reference/components/link\#scroll)

**Defaults to `true`.** The default scrolling behavior of `<Link>` in Next.js **is to maintain scroll position**, similar to how browsers handle back and forwards navigation. When you navigate to a new [Page](https://nextjs.org/docs/app/api-reference/file-conventions/page), scroll position will stay the same as long as the Page is visible in the viewport. However, if the Page is not visible in the viewport, Next.js will scroll to the top of the first Page element.

When `scroll = {false}`, Next.js will not attempt to scroll to the first Page element.

> **Good to know**: Next.js checks if `scroll: false` before managing scroll behavior. If scrolling is enabled, it identifies the relevant DOM node for navigation and inspects each top-level element. All non-scrollable elements and those without rendered HTML are bypassed, this includes sticky or fixed positioned elements, and non-visible elements such as those calculated with `getBoundingClientRect`. Next.js then continues through siblings until it identifies a scrollable element that is visible in the viewport.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return (
    <Link href="/dashboard" scroll={false}>
      Dashboard
    </Link>
  )
}
```

### [`prefetch`](https://nextjs.org/docs/app/api-reference/components/link\#prefetch)

Prefetching happens when a `<Link />` component enters the user's viewport (initially or through scroll). Next.js prefetches and loads the linked route (denoted by the `href`) and its data in the background to improve the performance of client-side navigations. If the prefetched data has expired by the time the user hovers over a `<Link />`, Next.js will attempt to prefetch it again. **Prefetching is only enabled in production**.

The following values can be passed to the `prefetch` prop:

- **`null` (default)**: Prefetch behavior depends on whether the route is static or dynamic. For static routes, the full route will be prefetched (including all its data). For dynamic routes, the partial route down to the nearest segment with a [`loading.js`](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming#instant-loading-states) boundary will be prefetched.
- `true`: The full route will be prefetched for both static and dynamic routes.
- `false`: Prefetching will never happen both on entering the viewport and on hover.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return (
    <Link href="/dashboard" prefetch={false}>
      Dashboard
    </Link>
  )
}
```

## [Examples](https://nextjs.org/docs/app/api-reference/components/link\#examples)

The following examples demonstrate how to use the `<Link>` component in different scenarios.

### [Linking to dynamic segments](https://nextjs.org/docs/app/api-reference/components/link\#linking-to-dynamic-segments)

When linking to [dynamic segments](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes), you can use [template literals and interpolation](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Template_literals) to generate a list of links. For example, to generate a list of blog posts:

app/blog/post-list.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

interface Post {
  id: number
  title: string
  slug: string
}

export default function PostList({ posts }: { posts: Post[] }) {
  return (
    <ul>
      {posts.map((post) => (
        <li key={post.id}>
          <Link href={`/blog/${post.slug}`}>{post.title}</Link>
        </li>
      ))}
    </ul>
  )
}
```

### [Checking active links](https://nextjs.org/docs/app/api-reference/components/link\#checking-active-links)

You can use [`usePathname()`](https://nextjs.org/docs/app/api-reference/functions/use-pathname) to determine if a link is active. For example, to add a class to the active link, you can check if the current `pathname` matches the `href` of the link:

app/ui/nav-links.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { usePathname } from 'next/navigation'
import Link from 'next/link'

export function Links() {
  const pathname = usePathname()

  return (
    <nav>
      <Link className={`link ${pathname === '/' ? 'active' : ''}`} href="/">
        Home
      </Link>

      <Link
        className={`link ${pathname === '/about' ? 'active' : ''}`}
        href="/about"
      >
        About
      </Link>
    </nav>
  )
}
```

### [Scrolling to an `id`](https://nextjs.org/docs/app/api-reference/components/link\#scrolling-to-an-id)

If you'd like to scroll to a specific `id` on navigation, you can append your URL with a `#` hash link or just pass a hash link to the `href` prop. This is possible since `<Link>` renders to an `<a>` element.

```code-block_code__isn_V
<Link href="/dashboard#settings">Settings</Link>

// Output
<a href="/dashboard#settings">Settings</a>
```

> **Good to know**:
>
> - Next.js will scroll to the [Page](https://nextjs.org/docs/app/api-reference/file-conventions/page) if it is not visible in the viewport upon navigation.

### [Linking to dynamic route segments](https://nextjs.org/docs/app/api-reference/components/link\#linking-to-dynamic-route-segments)

For [dynamic route segments](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes), it can be handy to use template literals to create the link's path.

For example, you can generate a list of links to the dynamic route `app/blog/[slug]/page.js`:

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Page({ posts }) {
  return (
    <ul>
      {posts.map((post) => (
        <li key={post.id}>
          <Link href={`/blog/${post.slug}`}>{post.title}</Link>
        </li>
      ))}
    </ul>
  )
}
```

### [If the child is a custom component that wraps an `<a>` tag](https://nextjs.org/docs/app/api-reference/components/link\#if-the-child-is-a-custom-component-that-wraps-an-a-tag)

If the child of `Link` is a custom component that wraps an `<a>` tag, you must add `passHref` to `Link`. This is necessary if you’re using libraries like [styled-components](https://styled-components.com/). Without this, the `<a>` tag will not have the `href` attribute, which hurts your site's accessibility and might affect SEO. If you're using [ESLint](https://nextjs.org/docs/pages/api-reference/config/eslint), there is a built-in rule `next/link-passhref` to ensure correct usage of `passHref`.

components/nav-link.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'
import styled from 'styled-components'

// This creates a custom component that wraps an <a> tag
const RedLink = styled.a`
  color: red;
`

function NavLink({ href, name }) {
  return (
    <Link href={href} passHref legacyBehavior>
      <RedLink>{name}</RedLink>
    </Link>
  )
}

export default NavLink
```

- If you’re using [emotion](https://emotion.sh/)’s JSX pragma feature ( `@jsx jsx`), you must use `passHref` even if you use an `<a>` tag directly.
- The component should support `onClick` property to trigger navigation correctly.

### [Nesting a functional component](https://nextjs.org/docs/app/api-reference/components/link\#nesting-a-functional-component)

If the child of `Link` is a functional component, in addition to using `passHref` and `legacyBehavior`, you must wrap the component in [`React.forwardRef`](https://react.dev/reference/react/forwardRef):

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'
import React from 'react'

// Define the props type for MyButton
interface MyButtonProps {
  onClick?: React.MouseEventHandler<HTMLAnchorElement>
  href?: string
}

// Use React.ForwardRefRenderFunction to properly type the forwarded ref
const MyButton: React.ForwardRefRenderFunction<
  HTMLAnchorElement,
  MyButtonProps
> = ({ onClick, href }, ref) => {
  return (
    <a href={href} onClick={onClick} ref={ref}>
      Click Me
    </a>
  )
}

// Use React.forwardRef to wrap the component
const ForwardedMyButton = React.forwardRef(MyButton)

export default function Page() {
  return (
    <Link href="/about" passHref legacyBehavior>
      <ForwardedMyButton />
    </Link>
  )
}
```

### [Replace the URL instead of push](https://nextjs.org/docs/app/api-reference/components/link\#replace-the-url-instead-of-push)

The default behavior of the `Link` component is to `push` a new URL into the `history` stack. You can use the `replace` prop to prevent adding a new entry, as in the following example:

app/page.js

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return (
    <Link href="/about" replace>
      About us
    </Link>
  )
}
```

### [Disable scrolling to the top of the page](https://nextjs.org/docs/app/api-reference/components/link\#disable-scrolling-to-the-top-of-the-page)

The default scrolling behavior of `<Link>` in Next.js **is to maintain scroll position**, similar to how browsers handle back and forwards navigation. When you navigate to a new [Page](https://nextjs.org/docs/app/api-reference/file-conventions/page), scroll position will stay the same as long as the Page is visible in the viewport.

However, if the Page is not visible in the viewport, Next.js will scroll to the top of the first Page element. If you'd like to disable this behavior, you can pass `scroll={false}` to the `<Link>` component, or `scroll: false` to `router.push()` or `router.replace()`.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return (
    <Link href="/#hashid" scroll={false}>
      Disables scrolling to the top
    </Link>
  )
}
```

Using `router.push()` or `router.replace()`:

```code-block_code__isn_V
// useRouter
import { useRouter } from 'next/navigation'

const router = useRouter()

router.push('/dashboard', { scroll: false })
```

### [Prefetching links in Middleware](https://nextjs.org/docs/app/api-reference/components/link\#prefetching-links-in-middleware)

It's common to use [Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware) for authentication or other purposes that involve rewriting the user to a different page. In order for the `<Link />` component to properly prefetch links with rewrites via Middleware, you need to tell Next.js both the URL to display and the URL to prefetch. This is required to avoid un-necessary fetches to middleware to know the correct route to prefetch.

For example, if you want to serve a `/dashboard` route that has authenticated and visitor views, you can add the following in your Middleware to redirect the user to the correct page:

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextResponse } from 'next/server'

export function middleware(request: Request) {
  const nextUrl = request.nextUrl
  if (nextUrl.pathname === '/dashboard') {
    if (request.cookies.authToken) {
      return NextResponse.rewrite(new URL('/auth/dashboard', request.url))
    } else {
      return NextResponse.rewrite(new URL('/public/dashboard', request.url))
    }
  }
}
```

In this case, you would want to use the following code in your `<Link />` component:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import Link from 'next/link'
import useIsAuthed from './hooks/useIsAuthed' // Your auth hook

export default function Page() {
  const isAuthed = useIsAuthed()
  const path = isAuthed ? '/auth/dashboard' : '/public/dashboard'
  return (
    <Link as="/dashboard" href={path}>
      Dashboard
    </Link>
  )
}
```

## [Version history](https://nextjs.org/docs/app/api-reference/components/link\#version-history)

| Version | Changes |
| --- | --- |
| `v13.0.0` | No longer requires a child `<a>` tag. A [codemod](https://nextjs.org/docs/app/building-your-application/upgrading/codemods#remove-a-tags-from-link-components) is provided to automatically update your codebase. |
| `v10.0.0` | `href` props pointing to a dynamic route are automatically resolved and no longer require an `as` prop. |
| `v8.0.0` | Improved prefetching performance. |
| `v1.0.0` | `next/link` introduced. |

Was this helpful?

supported.

Send

## Migrate to Next.js
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Upgrading](https://nextjs.org/docs/app/building-your-application/upgrading) Migrating from CRA

# Migrating from Create React App

This guide will help you migrate an existing Create React App (CRA) site to Next.js.

## [Why Switch?](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#why-switch)

There are several reasons why you might want to switch from Create React App to Next.js:

### [Slow initial page loading time](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#slow-initial-page-loading-time)

Create React App uses purely client-side React. Client-side only applications, also known as [single-page applications (SPAs)](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications), often experience slow initial page loading time. This happens due to a couple of reasons:

1. The browser needs to wait for the React code and your entire application bundle to download and run before your code is able to send requests to load data.
2. Your application code grows with every new feature and dependency you add.

### [No automatic code splitting](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#no-automatic-code-splitting)

The previous issue of slow loading times can be somewhat mitigated with code splitting. However, if you try to do code splitting manually, you can inadvertently introduce network waterfalls. Next.js provides automatic code splitting and tree-shaking built into its router and build pipeline.

### [Network waterfalls](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#network-waterfalls)

A common cause of poor performance occurs when applications make sequential client-server requests to fetch data. One pattern for data fetching in a [SPA](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications) is to render a placeholder, and then fetch data after the component has mounted. Unfortunately, a child component can only begin fetching data after its parent has finished loading its own data, resulting in a “waterfall” of requests.

While client-side data fetching is supported in Next.js, Next.js also lets you move data fetching to the server. This often eliminates client-server waterfalls altogether.

### [Fast and intentional loading states](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#fast-and-intentional-loading-states)

With built-in support for [streaming through React Suspense](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming#streaming-with-suspense), you can define which parts of your UI load first and in what order, without creating network waterfalls.

This enables you to build pages that are faster to load and eliminate [layout shifts](https://vercel.com/blog/how-core-web-vitals-affect-seo).

### [Choose the data fetching strategy](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#choose-the-data-fetching-strategy)

Depending on your needs, Next.js allows you to choose your data fetching strategy on a page or component-level basis. For example, you could fetch data from your CMS and render blog posts at build time (SSG) for quick load speeds, or fetch data at request time (SSR) when necessary.

### [Middleware](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#middleware)

[Next.js Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware) allows you to run code on the server before a request is completed. For instance, you can avoid a flash of unauthenticated content by redirecting a user to a login page in the middleware for authenticated-only pages. You can also use it for features like A/B testing, experimentation, and [internationalization](https://nextjs.org/docs/app/building-your-application/routing/internationalization).

### [Built-in Optimizations](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#built-in-optimizations)

[Images](https://nextjs.org/docs/app/building-your-application/optimizing/images), [fonts](https://nextjs.org/docs/app/building-your-application/optimizing/fonts), and [third-party scripts](https://nextjs.org/docs/app/building-your-application/optimizing/scripts) often have a large impact on an application’s performance. Next.js includes specialized components and APIs that automatically optimize them for you.

## [Migration Steps](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#migration-steps)

Our goal is to get a working Next.js application as quickly as possible so that you can then adopt Next.js features incrementally. To begin with, we’ll treat your application as a purely client-side application ( [SPA](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications)) without immediately replacing your existing router. This reduces complexity and merge conflicts.

> **Note**: If you are using advanced CRA configurations such as a custom `homepage` field in your `package.json`, a custom service worker, or specific Babel/webpack tweaks, please see the **Additional Considerations** section at the end of this guide for tips on replicating or adapting these features in Next.js.

### [Step 1: Install the Next.js Dependency](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-1-install-the-nextjs-dependency)

Install Next.js in your existing project:

Terminal

```code-block_code__isn_V
npm install next@latest
```

### [Step 2: Create the Next.js Configuration File](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-2-create-the-nextjs-configuration-file)

Create a `next.config.ts` at the root of your project (same level as your `package.json`). This file holds your [Next.js configuration options](https://nextjs.org/docs/app/api-reference/config/next-config-js).

next.config.ts

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  output: 'export', // Outputs a Single-Page Application (SPA)
  distDir: 'build', // Changes the build output directory to `build`
}

export default nextConfig
```

> **Note**: Using `output: 'export'` means you’re doing a static export. You will **not** have access to server-side features like SSR or APIs. You can remove this line to leverage Next.js server features.

### [Step 3: Create the Root Layout](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-3-create-the-root-layout)

A Next.js [App Router](https://nextjs.org/docs/app) application must include a [root layout](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#root-layout-required) file, which is a [React Server Component](https://nextjs.org/docs/app/building-your-application/rendering/server-components) that will wrap all your pages.

The closest equivalent of the root layout file in a CRA application is `public/index.html`, which includes your `<html>`, `<head>`, and `<body>` tags.

1. Create a new `app` directory inside your `src` directory (or at your project root if you prefer `app` at the root).
2. Inside the `app` directory, create a `layout.tsx` (or `layout.js`) file:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return '...'
}
```

Now copy the content of your old `index.html` into this `<RootLayout>` component. Replace `body div#root` (and `body noscript`) with `<div id="root">{children}</div>`.

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <head>
        <meta charSet="UTF-8" />
        <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <title>React App</title>
        <meta name="description" content="Web site created..." />
      </head>
      <body>
        <div id="root">{children}</div>
      </body>
    </html>
  )
}
```

> **Good to know**: Next.js ignores CRA’s `public/manifest.json`, additional iconography, and [testing configuration](https://nextjs.org/docs/app/building-your-application/testing) by default. If you need these, Next.js has support with its [Metadata API](https://nextjs.org/docs/app/building-your-application/optimizing/metadata) and [Testing](https://nextjs.org/docs/app/building-your-application/testing) setup.

### [Step 4: Metadata](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-4-metadata)

Next.js automatically includes the `<meta charset="UTF-8" />` and `<meta name="viewport" content="width=device-width, initial-scale=1" />` tags, so you can remove them from `<head>`:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <head>
        <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
        <title>React App</title>
        <meta name="description" content="Web site created..." />
      </head>
      <body>
        <div id="root">{children}</div>
      </body>
    </html>
  )
}
```

Any [metadata files](https://nextjs.org/docs/app/building-your-application/optimizing/metadata#file-based-metadata) such as `favicon.ico`, `icon.png`, `robots.txt` are automatically added to the application `<head>` tag as long as you have them placed into the top level of the `app` directory. After moving [all supported files](https://nextjs.org/docs/app/building-your-application/optimizing/metadata#file-based-metadata) into the `app` directory you can safely delete their `<link>` tags:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <head>
        <title>React App</title>
        <meta name="description" content="Web site created..." />
      </head>
      <body>
        <div id="root">{children}</div>
      </body>
    </html>
  )
}
```

Finally, Next.js can manage your last `<head>` tags with the [Metadata API](https://nextjs.org/docs/app/building-your-application/optimizing/metadata). Move your final metadata info into an exported [`metadata` object](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#metadata-object):

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { Metadata } from 'next'

export const metadata: Metadata = {
  title: 'React App',
  description: 'Web site created with Next.js.',
}

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body>
        <div id="root">{children}</div>
      </body>
    </html>
  )
}
```

With the above changes, you shifted from declaring everything in your `index.html` to using Next.js' convention-based approach built into the framework ( [Metadata API](https://nextjs.org/docs/app/building-your-application/optimizing/metadata)). This approach enables you to more easily improve your SEO and web shareability of your pages.

### [Step 5: Styles](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-5-styles)

Like CRA, Next.js supports [CSS Modules](https://nextjs.org/docs/app/building-your-application/styling/css#css-modules) out of the box. It also supports [global CSS imports](https://nextjs.org/docs/app/building-your-application/styling/css#global-styles).

If you have a global CSS file, import it into your `app/layout.tsx`:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import '../index.css'

export const metadata = {
  title: 'React App',
  description: 'Web site created with Next.js.',
}

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body>
        <div id="root">{children}</div>
      </body>
    </html>
  )
}
```

If you’re using Tailwind CSS, see our [installation docs](https://nextjs.org/docs/app/building-your-application/styling/tailwind-css).

### [Step 6: Create the Entrypoint Page](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-6-create-the-entrypoint-page)

Create React App uses `src/index.tsx` (or `index.js`) as the entry point. In Next.js (App Router), each folder inside the `app` directory corresponds to a route, and each folder should have a `page.tsx`.

Since we want to keep the app as an SPA for now and intercept **all** routes, we’ll use an [optional catch-all route](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes#optional-catch-all-segments).

1. **Create a `[[...slug]]` directory inside `app`.**

```code-block_code__isn_V
app
 ┣ [[...slug]]
 ┃ ┗ page.tsx
 ┣ layout.tsx
```

2. **Add the following to `page.tsx`**:

app/\[\[...slug\]\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export function generateStaticParams() {
  return [{ slug: [''] }]
}

export default function Page() {
  return '...' // We'll update this
}
```

This tells Next.js to generate a single route for the empty slug ( `/`), effectively mapping **all** routes to the same page. This page is a [Server Component](https://nextjs.org/docs/app/building-your-application/rendering/server-components), prerendered into static HTML.

### [Step 7: Add a Client-Only Entrypoint](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-7-add-a-client-only-entrypoint)

Next, we’ll embed your CRA’s root App component inside a [Client Component](https://nextjs.org/docs/app/building-your-application/rendering/client-components) so that all logic remains client-side. If this is your first time using Next.js, it's worth knowing that clients components (by default) are still prerendered on the server. You can think about them as having the additional capability of running client-side JavaScript.

Create a `client.tsx` (or `client.js`) in `app/[[...slug]]/`:

app/\[\[...slug\]\]/client.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import dynamic from 'next/dynamic'

const App = dynamic(() => import('../../App'), { ssr: false })

export function ClientOnly() {
  return <App />
}
```

- The `'use client'` directive makes this file a **Client Component**.
- The `dynamic` import with `ssr: false` disables server-side rendering for the `<App />` component, making it truly client-only (SPA).

Now update your `page.tsx` (or `page.js`) to use your new component:

app/\[\[...slug\]\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { ClientOnly } from './client'

export function generateStaticParams() {
  return [{ slug: [''] }]
}

export default function Page() {
  return <ClientOnly />
}
```

### [Step 8: Update Static Image Imports](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-8-update-static-image-imports)

In CRA, importing an image file returns its public URL as a string:

```code-block_code__isn_V
import image from './img.png'

export default function App() {
  return <img src={image} />
}
```

With Next.js, static image imports return an object. The object can then be used directly with the Next.js [`<Image>` component](https://nextjs.org/docs/app/api-reference/components/image), or you can use the object's `src` property with your existing `<img>` tag.

The `<Image>` component has the added benefits of [automatic image optimization](https://nextjs.org/docs/app/building-your-application/optimizing/images). The `<Image>` component automatically sets the `width` and `height` attributes of the resulting `<img>` based on the image's dimensions. This prevents layout shifts when the image loads. However, this can cause issues if your app contains images with only one of their dimensions being styled without the other styled to `auto`. When not styled to `auto`, the dimension will default to the `<img>` dimension attribute's value, which can cause the image to appear distorted.

Keeping the `<img>` tag will reduce the amount of changes in your application and prevent the above issues. You can then optionally later migrate to the `<Image>` component to take advantage of optimizing images by [configuring a loader](https://nextjs.org/docs/app/building-your-application/optimizing/images#loaders), or moving to the default Next.js server which has automatic image optimization.

**Convert absolute import paths for images imported from `/public` into relative imports:**

```code-block_code__isn_V
// Before
import logo from '/logo.png'

// After
import logo from '../public/logo.png'
```

**Pass the image `src` property instead of the whole image object to your `<img>` tag:**

```code-block_code__isn_V
// Before
<img src={logo} />

// After
<img src={logo.src} />
```

Alternatively, you can reference the public URL for the image asset based on the filename. For example, `public/logo.png` will serve the image at `/logo.png` for your application, which would be the `src` value.

> **Warning:** If you're using TypeScript, you might encounter type errors when accessing the `src` property. To fix them, you need to add `next-env.d.ts` to the [`include` array](https://www.typescriptlang.org/tsconfig#include) of your `tsconfig.json` file. Next.js will automatically generate this file when you run your application on step 9.

### [Step 9: Migrate Environment Variables](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-9-migrate-environment-variables)

Next.js supports [environment variables](https://nextjs.org/docs/app/building-your-application/configuring/environment-variables) similarly to CRA but **requires** a `NEXT_PUBLIC_` prefix for any variable you want to expose in the browser.

The main difference is the prefix used to expose environment variables on the client-side. Change all environment variables with the `REACT_APP_` prefix to `NEXT_PUBLIC_`.

### [Step 10: Update Scripts in `package.json`](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-10-update-scripts-in-packagejson)

Update your `package.json` scripts to use Next.js commands. Also, add `.next` and `next-env.d.ts` to your `.gitignore`:

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "next dev --turbopack",
    "build": "next build",
    "start": "npx serve@latest ./build"
  }
}
```

.gitignore

```code-block_code__isn_V
# ...
.next
next-env.d.ts
```

Now you can run:

```code-block_code__isn_V
npm run dev
```

Open [http://localhost:3000](http://localhost:3000/). You should see your application now running on Next.js (in SPA mode).

### [Step 11: Clean Up](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#step-11-clean-up)

You can now remove artifacts that are specific to Create React App:

- `public/index.html`
- `src/index.tsx`
- `src/react-app-env.d.ts`
- The `reportWebVitals` setup
- The `react-scripts` dependency (uninstall it from `package.json`)

## [Additional Considerations](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#additional-considerations)

### [Using a Custom `homepage` in CRA](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#using-a-custom-homepage-in-cra)

If you used the `homepage` field in your CRA `package.json` to serve the app under a specific subpath, you can replicate that in Next.js using the [`basePath` configuration](https://nextjs.org/docs/app/api-reference/config/next-config-js/basePath) in `next.config.ts`:

next.config.ts

```code-block_code__isn_V
import { NextConfig } from 'next'

const nextConfig: NextConfig = {
  basePath: '/my-subpath',
  // ...
}

export default nextConfig
```

### [Handling a Custom `Service Worker`](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#handling-a-custom-service-worker)

If you used CRA’s service worker (e.g., `serviceWorker.js` from `create-react-app`), you can learn how to create [Progressive Web Applications (PWAs)](https://nextjs.org/docs/app/building-your-application/configuring/progressive-web-apps) with Next.js.

### [Proxying API Requests](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#proxying-api-requests)

If your CRA app used the `proxy` field in `package.json` to forward requests to a backend server, you can replicate this with [Next.js rewrites](https://nextjs.org/docs/app/api-reference/config/next-config-js/rewrites) in `next.config.ts`:

next.config.ts

```code-block_code__isn_V
import { NextConfig } from 'next'

const nextConfig: NextConfig = {
  async rewrites() {
    return [\
      {\
        source: '/api/:path*',\
        destination: 'https://your-backend.com/:path*',\
      },\
    ]
  },
}
```

### [Custom Webpack / Babel Config](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#custom-webpack--babel-config)

If you had a custom webpack or Babel configuration in CRA, you can extend Next.js’s config in `next.config.ts`:

next.config.ts

```code-block_code__isn_V
import { NextConfig } from 'next'

const nextConfig: NextConfig = {
  webpack: (config, { isServer }) => {
    // Modify the webpack config here
    return config
  },
}

export default nextConfig
```

> **Note**: This will require disabling Turbopack by removing `--turbopack` from your `dev` script.

### [TypeScript Setup](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#typescript-setup)

Next.js automatically sets up TypeScript if you have a `tsconfig.json`. Make sure `next-env.d.ts` is listed in your `tsconfig.json` `include` array:

```code-block_code__isn_V
{
  "include": ["next-env.d.ts", "app/**/*", "src/**/*"]
}
```

## [Bundler Compatibility](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#bundler-compatibility)

Both Create React App and Next.js default to webpack for bundling. Next.js also offers [Turbopack](https://nextjs.org/docs/app/api-reference/config/next-config-js/turbo) for faster local development with:

```code-block_code__isn_V
next dev --turbopack
```

You can still provide a [custom webpack configuration](https://nextjs.org/docs/app/api-reference/config/next-config-js/webpack) if you need to migrate advanced webpack settings from CRA.

## [Next Steps](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app\#next-steps)

If everything worked, you now have a functioning Next.js application running as a single-page application. You aren’t yet leveraging Next.js features like server-side rendering or file-based routing, but you can now do so incrementally:

- **Migrate from React Router** to the [Next.js App Router](https://nextjs.org/docs/app/building-your-application/routing) for:
  - Automatic code splitting
  - [Streaming server rendering](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming)
  - [React Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components)
- **Optimize images** with the [`<Image>` component](https://nextjs.org/docs/app/building-your-application/optimizing/images)
- **Optimize fonts** with [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts)
- **Optimize third-party scripts** with the [`<Script>` component](https://nextjs.org/docs/app/building-your-application/optimizing/scripts)
- **Enable ESLint** with Next.js recommended rules by running `npx next lint` and configuring it to match your project’s needs

> **Note**: Using a static export ( `output: 'export'`) [does not currently support](https://github.com/vercel/next.js/issues/54393) the `useParams` hook or other server features. To use all Next.js features, remove `output: 'export'` from your `next.config.ts`.

Was this helpful?

supported.

Send

## Next.js Sass Integration
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Styling](https://nextjs.org/docs/app/building-your-application/styling) Sass

# Sass

Next.js has built-in support for integrating with Sass after the package is installed using both the `.scss` and `.sass` extensions. You can use component-level Sass via CSS Modules and the `.module.scss` or `.module.sass` extension.

First, install [`sass`](https://github.com/sass/sass):

Terminal

```code-block_code__isn_V
npm install --save-dev sass
```

> **Good to know**:
>
> Sass supports [two different syntaxes](https://sass-lang.com/documentation/syntax), each with their own extension.
> The `.scss` extension requires you use the [SCSS syntax](https://sass-lang.com/documentation/syntax#scss),
> while the `.sass` extension requires you use the [Indented Syntax ("Sass")](https://sass-lang.com/documentation/syntax#the-indented-syntax).
>
> If you're not sure which to choose, start with the `.scss` extension which is a superset of CSS, and doesn't require you learn the
> Indented Syntax ("Sass").

### [Customizing Sass Options](https://nextjs.org/docs/app/building-your-application/styling/sass\#customizing-sass-options)

If you want to configure your Sass options, use `sassOptions` in `next.config`.

next.config.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  sassOptions: {
    additionalData: `$var: red;`,
  },
}

export default nextConfig
```

#### [Implementation](https://nextjs.org/docs/app/building-your-application/styling/sass\#implementation)

You can use the `implementation` property to specify the Sass implementation to use. By default, Next.js uses the [`sass`](https://www.npmjs.com/package/sass) package.

next.config.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  sassOptions: {
    implementation: 'sass-embedded',
  },
}

export default nextConfig
```

### [Sass Variables](https://nextjs.org/docs/app/building-your-application/styling/sass\#sass-variables)

Next.js supports Sass variables exported from CSS Module files.

For example, using the exported `primaryColor` Sass variable:

app/variables.module.scss

```code-block_code__isn_V
$primary-color: #64ff00;

:export {
  primaryColor: $primary-color;
}
```

app/page.js

```code-block_code__isn_V
// maps to root `/` URL

import variables from './variables.module.scss'

export default function Page() {
  return <h1 style={{ color: variables.primaryColor }}>Hello, Next.js!</h1>
}
```

Was this helpful?

supported.

Send

## Next.js use client directive
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [Directives](https://nextjs.org/docs/app/api-reference/directives) use client

# use client

The `use client` directive designates a component to be rendered on the **client side** and should be used when creating interactive user interfaces (UI) that require client-side JavaScript capabilities, such as state management, event handling, and access to browser APIs. This is a React feature.

## [Usage](https://nextjs.org/docs/app/api-reference/directives/use-client\#usage)

To designate a component as a Client Component, add the `use client` directive **at the top of the file**, before any imports:

app/components/counter.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useState } from 'react'

export default function Counter() {
  const [count, setCount] = useState(0)

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={() => setCount(count + 1)}>Increment</button>
    </div>
  )
}
```

## [Nesting Client Components within Server Components](https://nextjs.org/docs/app/api-reference/directives/use-client\#nesting-client-components-within-server-components)

Combining Server and Client Components allows you to build applications that are both performant and interactive:

1. **Server Components**: Use for static content, data fetching, and SEO-friendly elements.
2. **Client Components**: Use for interactive elements that require state, effects, or browser APIs.
3. **Component composition**: Nest Client Components within Server Components as needed for a clear separation of server and client logic.

In the following example:

- `Header` is a Server Component handling static content.
- `Counter` is a Client Component enabling interactivity within the page.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Header from './header'
import Counter from './counter' // This is a Client Component

export default function Page() {
  return (
    <div>
      <Header />
      <Counter />
    </div>
  )
}
```

## [Reference](https://nextjs.org/docs/app/api-reference/directives/use-client\#reference)

See the [React documentation](https://react.dev/reference/rsc/use-client) for more information on `use client`.

Was this helpful?

supported.

Send

## Optimize Next.js Memory
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) Memory Usage

# Memory Usage

As applications grow and become more feature rich, they can demand more resources when developing locally or creating production builds.

Let's explore some strategies and techniques to optimize memory and address common memory issues in Next.js.

## [Reduce number of dependencies](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage\#reduce-number-of-dependencies)

Applications with a large amount of dependencies will use more memory.

The [Bundle Analyzer](https://nextjs.org/docs/app/building-your-application/optimizing/package-bundling) can help you investigate large dependencies in your application that may be able to be removed to improve performance and memory usage.

## [Try `experimental.webpackMemoryOptimizations`](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage\#try-experimentalwebpackmemoryoptimizations)

Starting in `v15.0.0`, you can add `experimental.webpackMemoryOptimizations: true` to your `next.config.js` file to change behavior in Webpack that reduces max memory usage but may increase compilation times by a slight amount.

> **Good to know**: This feature is currently experimental to test on more projects first, but it is considered to be low-risk.

## [Run `next build` with `--experimental-debug-memory-usage`](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage\#run-next-build-with---experimental-debug-memory-usage)

Starting in `14.2.0`, you can run `next build --experimental-debug-memory-usage` to run the build in a mode where Next.js will print out information about memory usage continuously throughout the build, such as heap usage and garbage collection statistics. Heap snapshots will also be taken automatically when memory usage gets close to the configured limit.

> **Good to know**: This feature is not compatible with the Webpack build worker option which is auto-enabled unless you have custom webpack config.

## [Record a heap profile](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage\#record-a-heap-profile)

To look for memory issues, you can record a heap profile from Node.js and load it in Chrome DevTools to identify potential sources of memory leaks.

In your terminal, pass the `--heap-prof` flag to Node.js when starting your Next.js build:

```code-block_code__isn_V
node --heap-prof node_modules/next/dist/bin/next build
```

At the end of the build, a `.heapprofile` file will be created by Node.js.

In Chrome DevTools, you can open the Memory tab and click on the "Load Profile" button to visualize the file.

## [Analyze a snapshot of the heap](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage\#analyze-a-snapshot-of-the-heap)

You can use an inspector tool to analyze the memory usage of the application.

When running the `next build` or `next dev` command, add `NODE_OPTIONS=--inspect` to the beginning of the command. This will expose the inspector agent on the default port.
If you wish to break before any user code starts, you can pass `--inspect-brk` instead. While the process is running, you can use a tool such as Chrome DevTools to connect to the debugging port to record and analyze a snapshot of the heap to see what memory is being retained.

Starting in `14.2.0`, you can also run `next build` with the `--experimental-debug-memory-usage` flag to make it easier to take heap snapshots.

While running in this mode, you can send a `SIGUSR2` signal to the process at any point, and the process will take a heap snapshot.

The heap snapshot will be saved to the project root of the Next.js application and can be loaded in any heap analyzer, such as Chrome DevTools, to see what memory is retained. This mode is not yet compatible with Webpack build workers.

See [how to record and analyze heap snapshots](https://developer.chrome.com/docs/devtools/memory-problems/heap-snapshots) for more information.

## [Webpack build worker](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage\#webpack-build-worker)

The Webpack build worker allows you to run Webpack compilations inside a separate Node.js worker which will decrease memory usage of your application during builds.

This option is enabled by default if your application does not have a custom Webpack configuration starting in `v14.1.0`.

If you are using an older version of Next.js or you have a custom Webpack configuration, you can enable this option by setting `experimental.webpackBuildWorker: true` inside your `next.config.js`.

> **Good to know**: This feature may not be compatible with all custom Webpack plugins.

## [Disable Webpack cache](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage\#disable-webpack-cache)

The [Webpack cache](https://webpack.js.org/configuration/cache/) saves generated Webpack modules in memory and/or to disk to improve the speed of builds. This can
help with performance, but it will also increase the memory usage of your application to store the cached data.

You can disable this behavior by adding a [custom Webpack configuration](https://nextjs.org/docs/app/api-reference/config/next-config-js/webpack) to your application:

next.config.mjs

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
const nextConfig = {
  webpack: (
    config,
    { buildId, dev, isServer, defaultLoaders, nextRuntime, webpack }
  ) => {
    if (config.cache && !dev) {
      config.cache = Object.freeze({
        type: 'memory',
      })
    }
    // Important: return the modified config
    return config
  },
}

export default nextConfig
```

## [Disable static analysis](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage\#disable-static-analysis)

Typechecking and linting may require a lot of memory, especially in large projects.
However, most projects have a dedicated CI runner that already handles these tasks.
When the build produces out-of-memory issues during the "Linting and checking validity of types" step, you can disable these task during builds:

next.config.mjs

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
const nextConfig = {
  eslint: {
    // Warning: This allows production builds to successfully complete even if
    // your project has ESLint errors.
    ignoreDuringBuilds: true,
  },
  typescript: {
    // !! WARN !!
    // Dangerously allow production builds to successfully complete even if
    // your project has type errors.
    // !! WARN !!
    ignoreBuildErrors: true,
  },
}

export default nextConfig
```

- [Ignoring TypeScript Errors](https://nextjs.org/docs/app/api-reference/config/typescript#disabling-typescript-errors-in-production)
- [ESLint in Next.js config](https://nextjs.org/docs/pages/api-reference/config/next-config-js/eslint)

Keep in mind that this may produce faulty deploys due to type errors or linting issues.
We strongly recommend only promoting builds to production after static analysis has completed.
If you deploy to Vercel, you can check out the [guide for staging deployments](https://vercel.com/docs/deployments/managing-deployments#staging-and-promoting-a-production-deployment) to learn how to promote builds to production after custom tasks have succeeded.

## [Disable source maps](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage\#disable-source-maps)

Generating source maps consumes extra memory during the build process.

You can disable source map generation by adding `productionBrowserSourceMaps: false` and `experimental.serverSourceMaps: false` to your Next.js configuration.

> **Good to know**: Some plugins may turn on source maps and may require custom configuration to disable.

## [Edge memory issues](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage\#edge-memory-issues)

Next.js `v14.1.3` fixed a memory issue when using the Edge runtime. Please update to this version (or later) to see if it addresses your issue.

Was this helpful?

supported.

Send

## Optimizing Static Assets
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) Static Assets

# Static Assets in \`public\`

Next.js can serve static files, like images, under a folder called `public` in the root directory. Files inside `public` can then be referenced by your code starting from the base URL ( `/`).

For example, the file `public/avatars/me.png` can be viewed by visiting the `/avatars/me.png` path. The code to display that image might look like:

avatar.js

```code-block_code__isn_V
import Image from 'next/image'

export function Avatar({ id, alt }) {
  return <Image src={`/avatars/${id}.png`} alt={alt} width="64" height="64" />
}

export function AvatarOfMe() {
  return <Avatar id="me" alt="A portrait of me" />
}
```

## [Caching](https://nextjs.org/docs/app/building-your-application/optimizing/static-assets\#caching)

Next.js cannot safely cache assets in the `public` folder because they may change. The default caching headers applied are:

```code-block_code__isn_V
Cache-Control: public, max-age=0
```

## [Robots, Favicons, and others](https://nextjs.org/docs/app/building-your-application/optimizing/static-assets\#robots-favicons-and-others)

For static metadata files, such as `robots.txt`, `favicon.ico`, etc, you should use [special metadata files](https://nextjs.org/docs/app/api-reference/file-conventions/metadata) inside the `app` folder.

> Good to know:
>
> - The directory must be named `public`. The name cannot be changed and it's the only directory used to serve static assets.
> - Only assets that are in the `public` directory at [build time](https://nextjs.org/docs/app/api-reference/cli/next#next-build-options) will be served by Next.js. Files added at request time won't be available. We recommend using a third-party service like [Vercel Blob](https://vercel.com/docs/storage/vercel-blob?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) for persistent file storage.

Was this helpful?

supported.

Send

## Next.js Runtimes Overview
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Rendering](https://nextjs.org/docs/app/building-your-application/rendering) Runtimes

# Runtimes

Next.js has two server runtimes you can use in your application:

- The **Node.js Runtime** (default), which has access to all Node.js APIs and compatible packages from the ecosystem.
- The **Edge Runtime** which contains a more limited [set of APIs](https://nextjs.org/docs/app/api-reference/edge).

The Edge Runtime is the default runtime for [Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware). However, this can be changed to the Node.js runtime. See the [Middleware documentation](https://nextjs.org/docs/app/building-your-application/routing/middleware#runtime) for more details.

## [Use Cases](https://nextjs.org/docs/app/building-your-application/rendering/edge-and-nodejs-runtimes\#use-cases)

- The Node.js Runtime is used for rendering your application.
- The Edge Runtime is used for Middleware (routing rules like redirects, rewrites, and setting headers).

## [Caveats](https://nextjs.org/docs/app/building-your-application/rendering/edge-and-nodejs-runtimes\#caveats)

- The Edge Runtime does not support all Node.js APIs. Some packages may not work as expected. Learn more about the unsupported APIs in the [Edge Runtime](https://nextjs.org/docs/app/api-reference/edge#unsupported-apis).
- The Edge Runtime does not support Incremental Static Regeneration (ISR).
- Both runtimes can support [streaming](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming) depending on your deployment infrastructure.

## Next Steps

View the Edge Runtime API reference.

[**Edge Runtime** \\
API Reference for the Edge Runtime.](https://nextjs.org/docs/app/api-reference/edge)

Was this helpful?

supported.

Send

## Next.js Configuration Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Building Your Application](https://nextjs.org/docs/app/building-your-application) Configuring

# Configuring

Next.js allows you to customize your project to meet specific requirements. This includes integrations with TypeScript, ESlint, and more, as well as internal configuration options such as Absolute Imports and Environment Variables.

[**Environment Variables** \\
Learn to add and access environment variables in your Next.js application.](https://nextjs.org/docs/app/building-your-application/configuring/environment-variables) [**MDX** \\
Learn how to configure MDX and use it in your Next.js apps.](https://nextjs.org/docs/app/building-your-application/configuring/mdx) [**src Directory** \\
Save pages under the \`src\` directory as an alternative to the root \`pages\` directory.](https://nextjs.org/docs/app/building-your-application/configuring/src-directory) [**Custom Server** \\
Start a Next.js app programmatically using a custom server.](https://nextjs.org/docs/app/building-your-application/configuring/custom-server) [**Draft Mode** \\
Next.js has draft mode to toggle between static and dynamic pages. You can learn how it works with App Router here.](https://nextjs.org/docs/app/building-your-application/configuring/draft-mode) [**Content Security Policy** \\
Learn how to set a Content Security Policy (CSP) for your Next.js application.](https://nextjs.org/docs/app/building-your-application/configuring/content-security-policy) [**Debugging** \\
Learn how to debug your Next.js application with VS Code, Chrome DevTools, or Firefox DevTools.](https://nextjs.org/docs/app/building-your-application/configuring/debugging) [**Progressive Web Applications (PWA)** \\
Learn how to build a Progressive Web Application (PWA) with Next.js.](https://nextjs.org/docs/app/building-your-application/configuring/progressive-web-apps)

Was this helpful?

supported.

Send

## Next.js Layouts Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [File Conventions](https://nextjs.org/docs/app/api-reference/file-conventions) layout.js

# layout.js

The `layout` file is used to define a layout in your Next.js application.

app/dashboard/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function DashboardLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return <section>{children}</section>
}
```

A **root layout** is the top-most layout in the root `app` directory. It is used to define the `<html>` and `<body>` tags and other globally shared UI.

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body>{children}</body>
    </html>
  )
}
```

## [Reference](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#reference)

### [Props](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#props)

#### [`children` (required)](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#children-required)

Layout components should accept and use a `children` prop. During rendering, `children` will be populated with the route segments the layout is wrapping. These will primarily be the component of a child [Layout](https://nextjs.org/docs/app/api-reference/file-conventions/page) (if it exists) or [Page](https://nextjs.org/docs/app/api-reference/file-conventions/page), but could also be other special files like [Loading](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming) or [Error](https://nextjs.org/docs/app/building-your-application/routing/error-handling) when applicable.

#### [`params` (optional)](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#params-optional)

A promise that resolves to an object containing the [dynamic route parameters](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes) object from the root segment down to that layout.

app/dashboard/\[team\]/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Layout({
  params,
}: {
  params: Promise<{ team: string }>
}) {
  const { team } = await params
}
```

| Example Route | URL | `params` |
| --- | --- | --- |
| `app/dashboard/[team]/layout.js` | `/dashboard/1` | `Promise<{ team: '1' }>` |
| `app/shop/[tag]/[item]/layout.js` | `/shop/1/2` | `Promise<{ tag: '1', item: '2' }>` |
| `app/blog/[...slug]/layout.js` | `/blog/1/2` | `Promise<{ slug: ['1', '2'] }>` |

- Since the `params` prop is a promise. You must use `async/await` or React's [`use`](https://react.dev/reference/react/use) function to access the values.
  - In version 14 and earlier, `params` was a synchronous prop. To help with backwards compatibility, you can still access it synchronously in Next.js 15, but this behavior will be deprecated in the future.

### [Root Layouts](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#root-layouts)

The `app` directory **must** include a root `app/layout.js`.

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html>
      <body>{children}</body>
    </html>
  )
}
```

- The root layout **must** define `<html>` and `<body>` tags.
  - You should **not** manually add `<head>` tags such as `<title>` and `<meta>` to root layouts. Instead, you should use the [Metadata API](https://nextjs.org/docs/app/building-your-application/optimizing/metadata) which automatically handles advanced requirements such as streaming and de-duplicating `<head>` elements.
- You can use [route groups](https://nextjs.org/docs/app/building-your-application/routing/route-groups) to create multiple root layouts.
  - Navigating **across multiple root layouts** will cause a **full page load** (as opposed to a client-side navigation). For example, navigating from `/cart` that uses `app/(shop)/layout.js` to `/blog` that uses `app/(marketing)/layout.js` will cause a full page load. This **only** applies to multiple root layouts.

## [Caveats](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#caveats)

### [Layouts do not receive `searchParams`](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#layouts-do-not-receive-searchparams)

Unlike [Pages](https://nextjs.org/docs/app/api-reference/file-conventions/page), Layout components **do not** receive the `searchParams` prop. This is because a shared layout is [not re-rendered during navigation](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#4-partial-rendering) which could lead to stale `searchParams` between navigations.

When using client-side navigation, Next.js automatically only renders the part of the page below the common layout between two routes.

For example, in the following directory structure, `dashboard/layout.tsx` is the common layout for both `/dashboard/settings` and `/dashboard/analytics`:

![File structure showing a dashboard folder nesting a layout.tsx file, and settings and analytics folders with their own pages](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fshared-dashboard-layout.png&w=3840&q=75)![File structure showing a dashboard folder nesting a layout.tsx file, and settings and analytics folders with their own pages](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fshared-dashboard-layout.png&w=3840&q=75)

When navigating from `/dashboard/settings` to `/dashboard/analytics`, `page.tsx` in `/dashboard/analytics` will rerender on the server, while `dashboard/layout.tsx` will **not** rerender because it's a common UI shared between the two routes.

This performance optimization allows navigation between pages that share a layout to be quicker as only the data fetching and rendering for the page has to run, instead of the entire route that could include shared layouts that fetch their own data.

Because `dashboard/layout.tsx` doesn't re-render, the `searchParams` prop in the layout Server Component might become **stale** after navigation.

Instead, use the Page [`searchParams`](https://nextjs.org/docs/app/api-reference/file-conventions/page#searchparams-optional) prop or the [`useSearchParams`](https://nextjs.org/docs/app/api-reference/functions/use-search-params) hook in a Client Component within the layout, which is rerendered on the client with the latest `searchParams`.

### [Layouts cannot access `pathname`](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#layouts-cannot-access-pathname)

Layouts cannot access `pathname`. This is because layouts are Server Components by default, and [don't rerender during client-side navigation](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#4-partial-rendering), which could lead to `pathname` becoming stale between navigations. To prevent staleness, Next.js would need to refetch all segments of a route, losing the benefits of caching and increasing the [RSC payload](https://nextjs.org/docs/app/building-your-application/rendering/server-components#what-is-the-react-server-component-payload-rsc) size on navigation.

Instead, you can extract the logic that depends on pathname into a Client Component and import it into your layouts. Since Client Components rerender (but are not refetched) during navigation, you can use Next.js hooks such as [`usePathname`](https://nextjs.org/docs/app/api-reference/functions/use-pathname) to access the current pathname and prevent staleness.

app/dashboard/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { ClientComponent } from '@/app/ui/ClientComponent'

export default function Layout({ children }: { children: React.ReactNode }) {
  return (
    <>
      <ClientComponent />
      {/* Other Layout UI */}
      <main>{children}</main>
    </>
  )
}
```

Common `pathname` patterns can also be implemented with [`params`](https://nextjs.org/docs/app/api-reference/file-conventions/layout#params-optional) prop.

See the [examples](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#examples) section for more information.

## [Examples](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#examples)

### [Displaying content based on `params`](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#displaying-content-based-on-params)

Using [dynamic route segments](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes), you can display or fetch specific content based on the `params` prop.

app/dashboard/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function DashboardLayout({
  children,
  params,
}: {
  children: React.ReactNode
  params: Promise<{ team: string }>
}) {
  const { team } = await params

  return (
    <section>
      <header>
        <h1>Welcome to {team}'s Dashboard</h1>
      </header>
      <main>{children}</main>
    </section>
  )
}
```

### [Reading `params` in Client Components](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#reading-params-in-client-components)

To use `params` in a Client Component (which cannot be `async`), you can use React's [`use`](https://react.dev/reference/react/use) function to read the promise:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { use } from 'react'

export default function Page({
  params,
}: {
  params: Promise<{ slug: string }>
}) {
  const { slug } = use(params)
}
```

## [Version History](https://nextjs.org/docs/app/api-reference/file-conventions/layout\#version-history)

| Version | Changes |
| --- | --- |
| `v15.0.0-RC` | `params` is now a promise. A [codemod](https://nextjs.org/docs/app/building-your-application/upgrading/codemods#150) is available. |
| `v13.0.0` | `layout` introduced. |

Was this helpful?

supported.

Send

## Configuring src Directory
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Configuring](https://nextjs.org/docs/app/building-your-application/configuring) src Directory

# src Directory

As an alternative to having the special Next.js `app` or `pages` directories in the root of your project, Next.js also supports the common pattern of placing application code under the `src` directory.

This separates application code from project configuration files which mostly live in the root of a project, which is preferred by some individuals and teams.

To use the `src` directory, move the `app` Router folder or `pages` Router folder to `src/app` or `src/pages` respectively.

![An example folder structure with the `src` directory](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fproject-organization-src-directory.png&w=3840&q=75)![An example folder structure with the `src` directory](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fproject-organization-src-directory.png&w=3840&q=75)

> **Good to know**:
>
> - The `/public` directory should remain in the root of your project.
> - Config files like `package.json`, `next.config.js` and `tsconfig.json` should remain in the root of your project.
> - `.env.*` files should remain in the root of your project.
> - `src/app` or `src/pages` will be ignored if `app` or `pages` are present in the root directory.
> - If you're using `src`, you'll probably also move other application folders such as `/components` or `/lib`.
> - If you're using Middleware, ensure it is placed inside the `src` directory.
> - If you're using Tailwind CSS, you'll need to add the `/src` prefix to the `tailwind.config.js` file in the [content section](https://tailwindcss.com/docs/content-configuration).
> - If you are using TypeScript paths for imports such as `@/*`, you should update the `paths` object in `tsconfig.json` to include `src/`.

## Next Steps

[**Project Structure** \\
An overview of the folder and file conventions in Next.js, and how to organize your project.](https://nextjs.org/docs/app/getting-started/project-structure)

Was this helpful?

supported.

Send

## Next.js Image Optimization
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) Images

# Image Optimization

Examples

- [Image Component](https://github.com/vercel/next.js/tree/canary/examples/image-component)

According to [Web Almanac](https://almanac.httparchive.org/), images account for a huge portion of the typical website’s [page weight](https://almanac.httparchive.org/en/2022/page-weight#content-type-and-file-formats) and can have a sizable impact on your website's [LCP performance](https://almanac.httparchive.org/en/2022/performance#lcp-image-optimization).

The Next.js Image component extends the HTML `<img>` element with features for automatic image optimization:

- **Size Optimization:** Automatically serve correctly sized images for each device, using modern image formats like WebP.
- **Visual Stability:** Prevent [layout shift](https://nextjs.org/learn/seo/web-performance/cls) automatically when images are loading.
- **Faster Page Loads:** Images are only loaded when they enter the viewport using native browser lazy loading, with optional blur-up placeholders.
- **Asset Flexibility:** On-demand image resizing, even for images stored on remote servers

> **🎥 Watch:** Learn more about how to use `next/image` → [YouTube (9 minutes)](https://youtu.be/IU_qq_c_lKA).

## [Usage](https://nextjs.org/docs/app/building-your-application/optimizing/images\#usage)

```code-block_code__isn_V
import Image from 'next/image'
```

You can then define the `src` for your image (either local or remote).

### [Local Images](https://nextjs.org/docs/app/building-your-application/optimizing/images\#local-images)

To use a local image, `import` your `.jpg`, `.png`, or `.webp` image files.

Next.js will [automatically determine](https://nextjs.org/docs/app/building-your-application/optimizing/images#image-sizing) the intrinsic `width` and `height` of your image based on the imported file. These values are used to determine the image ratio and prevent [Cumulative Layout Shift](https://nextjs.org/learn/seo/web-performance/cls) while your image is loading.

app/page.js

```code-block_code__isn_V
import Image from 'next/image'
import profilePic from './me.png'

export default function Page() {
  return (
    <Image
      src={profilePic}
      alt="Picture of the author"
      // width={500} automatically provided
      // height={500} automatically provided
      // blurDataURL="data:..." automatically provided
      // placeholder="blur" // Optional blur-up while loading
    />
  )
}
```

> **Warning:** Dynamic `await import()` or `require()` are _not_ supported. The `import` must be static so it can be analyzed at build time.

You can optionally configure `localPatterns` in your `next.config.js` file in order to allow specific images and block all others.

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    localPatterns: [\
      {\
        pathname: '/assets/images/**',\
        search: '',\
      },\
    ],
  },
}
```

### [Remote Images](https://nextjs.org/docs/app/building-your-application/optimizing/images\#remote-images)

To use a remote image, the `src` property should be a URL string.

Since Next.js does not have access to remote files during the build process, you'll need to provide the [`width`](https://nextjs.org/docs/app/api-reference/components/image#width), [`height`](https://nextjs.org/docs/app/api-reference/components/image#height) and optional [`blurDataURL`](https://nextjs.org/docs/app/api-reference/components/image#blurdataurl) props manually.

The `width` and `height` attributes are used to infer the correct aspect ratio of image and avoid layout shift from the image loading in. The `width` and `height` do _not_ determine the rendered size of the image file. Learn more about [Image Sizing](https://nextjs.org/docs/app/building-your-application/optimizing/images#image-sizing).

app/page.js

```code-block_code__isn_V
import Image from 'next/image'

export default function Page() {
  return (
    <Image
      src="https://s3.amazonaws.com/my-bucket/profile.png"
      alt="Picture of the author"
      width={500}
      height={500}
    />
  )
}
```

To safely allow optimizing images, define a list of supported URL patterns in `next.config.js`. Be as specific as possible to prevent malicious usage. For example, the following configuration will only allow images from a specific AWS S3 bucket:

next.config.js

```code-block_code__isn_V
module.exports = {
  images: {
    remotePatterns: [\
      {\
        protocol: 'https',\
        hostname: 's3.amazonaws.com',\
        port: '',\
        pathname: '/my-bucket/**',\
        search: '',\
      },\
    ],
  },
}
```

Learn more about [`remotePatterns`](https://nextjs.org/docs/app/api-reference/components/image#remotepatterns) configuration. If you want to use relative URLs for the image `src`, use a [`loader`](https://nextjs.org/docs/app/api-reference/components/image#loader).

### [Domains](https://nextjs.org/docs/app/building-your-application/optimizing/images\#domains)

Sometimes you may want to optimize a remote image, but still use the built-in Next.js Image Optimization API. To do this, leave the `loader` at its default setting and enter an absolute URL for the Image `src` prop.

To protect your application from malicious users, you must define a list of remote hostnames you intend to use with the `next/image` component.

> Learn more about [`remotePatterns`](https://nextjs.org/docs/app/api-reference/components/image#remotepatterns) configuration.

### [Loaders](https://nextjs.org/docs/app/building-your-application/optimizing/images\#loaders)

Note that in the [example earlier](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images), a partial URL ( `"/me.png"`) is provided for a local image. This is possible because of the loader architecture.

A loader is a function that generates the URLs for your image. It modifies the provided `src`, and generates multiple URLs to request the image at different sizes. These multiple URLs are used in the automatic [srcset](https://developer.mozilla.org/docs/Web/API/HTMLImageElement/srcset) generation, so that visitors to your site will be served an image that is the right size for their viewport.

The default loader for Next.js applications uses the built-in Image Optimization API, which optimizes images from anywhere on the web, and then serves them directly from the Next.js web server. If you would like to serve your images directly from a CDN or image server, you can write your own loader function with a few lines of JavaScript.

You can define a loader per-image with the [`loader` prop](https://nextjs.org/docs/app/api-reference/components/image#loader), or at the application level with the [`loaderFile` configuration](https://nextjs.org/docs/app/api-reference/components/image#loaderfile).

## [Priority](https://nextjs.org/docs/app/building-your-application/optimizing/images\#priority)

You should add the `priority` property to the image that will be the [Largest Contentful Paint (LCP) element](https://web.dev/lcp/#what-elements-are-considered) for each page. Doing so allows Next.js to [preload](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/rel/preload) the image, leading to a meaningful boost in LCP.

The LCP element is typically the largest image or text block visible within the viewport of the page. When you run `next dev`, you'll see a console warning if the LCP element is an `<Image>` without the `priority` property.

Once you've identified the LCP image, you can add the property like this:

app/page.js

```code-block_code__isn_V
import Image from 'next/image'
import profilePic from '../public/me.png'

export default function Page() {
  return <Image src={profilePic} alt="Picture of the author" priority />
}
```

See more about priority in the [`next/image` component documentation](https://nextjs.org/docs/app/api-reference/components/image#priority).

## [Image Sizing](https://nextjs.org/docs/app/building-your-application/optimizing/images\#image-sizing)

One of the ways that images most commonly hurt performance is through _layout shift_, where the image pushes other elements around on the page as it loads in. This performance problem is so annoying to users that it has its own Core Web Vital, called [Cumulative Layout Shift](https://web.dev/cls/). The way to avoid image-based layout shifts is to [always size your images](https://web.dev/optimize-cls/#images-without-dimensions). This allows the browser to reserve precisely enough space for the image before it loads.

Because `next/image` is designed to guarantee good performance results, it cannot be used in a way that will contribute to layout shift, and **must** be sized in one of three ways:

1. Automatically, using a [static import](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images)
2. Manually, by including a [`width`](https://nextjs.org/docs/app/api-reference/components/image#width) and [`height`](https://nextjs.org/docs/app/api-reference/components/image#height) property used to determine the image's aspect ratio.
3. Implicitly, by using [fill](https://nextjs.org/docs/app/api-reference/components/image#fill) which causes the image to expand to fill its parent element.

> **What if I don't know the size of my images?**
>
> If you are accessing images from a source without knowledge of the images' sizes, there are several things you can do:
>
> **Use `fill`**
>
> The [`fill`](https://nextjs.org/docs/app/api-reference/components/image#fill) prop allows your image to be sized by its parent element. Consider using CSS to give the image's parent element space on the page along [`sizes`](https://nextjs.org/docs/app/api-reference/components/image#sizes) prop to match any media query break points. You can also use [`object-fit`](https://developer.mozilla.org/docs/Web/CSS/object-fit) with `fill`, `contain`, or `cover`, and [`object-position`](https://developer.mozilla.org/docs/Web/CSS/object-position) to define how the image should occupy that space.
>
> **Normalize your images**
>
> If you're serving images from a source that you control, consider modifying your image pipeline to normalize the images to a specific size.
>
> **Modify your API calls**
>
> If your application is retrieving image URLs using an API call (such as to a CMS), you may be able to modify the API call to return the image dimensions along with the URL.

If none of the suggested methods works for sizing your images, the `next/image` component is designed to work well on a page alongside standard `<img>` elements.

## [Styling](https://nextjs.org/docs/app/building-your-application/optimizing/images\#styling)

Styling the Image component is similar to styling a normal `<img>` element, but there are a few guidelines to keep in mind:

- Use `className` or `style`, not `styled-jsx`.
  - In most cases, we recommend using the `className` prop. This can be an imported [CSS Module](https://nextjs.org/docs/app/building-your-application/styling/css), a [global stylesheet](https://nextjs.org/docs/app/building-your-application/styling/css#global-styles), etc.
  - You can also use the `style` prop to assign inline styles.
  - You cannot use [styled-jsx](https://nextjs.org/docs/app/building-your-application/styling/css-in-js) because it's scoped to the current component (unless you mark the style as `global`).
- When using `fill`, the parent element must have `position: relative`
  - This is necessary for the proper rendering of the image element in that layout mode.
- When using `fill`, the parent element must have `display: block`
  - This is the default for `<div>` elements but should be specified otherwise.

## [Examples](https://nextjs.org/docs/app/building-your-application/optimizing/images\#examples)

### [Responsive](https://nextjs.org/docs/app/building-your-application/optimizing/images\#responsive)

![Responsive image filling the width and height of its parent container](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fresponsive-image.png&w=3840&q=75)![Responsive image filling the width and height of its parent container](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fresponsive-image.png&w=3840&q=75)

```code-block_code__isn_V
import Image from 'next/image'
import mountains from '../public/mountains.jpg'

export default function Responsive() {
  return (
    <div style={{ display: 'flex', flexDirection: 'column' }}>
      <Image
        alt="Mountains"
        // Importing an image will
        // automatically set the width and height
        src={mountains}
        sizes="100vw"
        // Make the image display full width
        style={{
          width: '100%',
          height: 'auto',
        }}
      />
    </div>
  )
}
```

### [Fill Container](https://nextjs.org/docs/app/building-your-application/optimizing/images\#fill-container)

![Grid of images filling parent container width](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Ffill-container.png&w=3840&q=75)![Grid of images filling parent container width](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Ffill-container.png&w=3840&q=75)

```code-block_code__isn_V
import Image from 'next/image'
import mountains from '../public/mountains.jpg'

export default function Fill() {
  return (
    <div
      style={{
        display: 'grid',
        gridGap: '8px',
        gridTemplateColumns: 'repeat(auto-fit, minmax(400px, auto))',
      }}
    >
      <div style={{ position: 'relative', height: '400px' }}>
        <Image
          alt="Mountains"
          src={mountains}
          fill
          sizes="(min-width: 808px) 50vw, 100vw"
          style={{
            objectFit: 'cover', // cover, contain, none
          }}
        />
      </div>
      {/* And more images in the grid... */}
    </div>
  )
}
```

### [Background Image](https://nextjs.org/docs/app/building-your-application/optimizing/images\#background-image)

![Background image taking full width and height of page](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fbackground-image.png&w=3840&q=75)![Background image taking full width and height of page](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fbackground-image.png&w=3840&q=75)

```code-block_code__isn_V
import Image from 'next/image'
import mountains from '../public/mountains.jpg'

export default function Background() {
  return (
    <Image
      alt="Mountains"
      src={mountains}
      placeholder="blur"
      quality={100}
      fill
      sizes="100vw"
      style={{
        objectFit: 'cover',
      }}
    />
  )
}
```

For examples of the Image component used with the various styles, see the [Image Component Demo](https://image-component.nextjs.gallery/).

## [Other Properties](https://nextjs.org/docs/app/building-your-application/optimizing/images\#other-properties)

[**View all properties available to the `next/image` component.**](https://nextjs.org/docs/app/api-reference/components/image)

## [Configuration](https://nextjs.org/docs/app/building-your-application/optimizing/images\#configuration)

The `next/image` component and Next.js Image Optimization API can be configured in the [`next.config.js` file](https://nextjs.org/docs/app/api-reference/config/next-config-js). These configurations allow you to [enable remote images](https://nextjs.org/docs/app/api-reference/components/image#remotepatterns), [define custom image breakpoints](https://nextjs.org/docs/app/api-reference/components/image#devicesizes), [change caching behavior](https://nextjs.org/docs/app/api-reference/components/image#caching-behavior) and more.

[**Read the full image configuration documentation for more information.**](https://nextjs.org/docs/app/api-reference/components/image#configuration-options)

## API Reference

Learn more about the next/image API.

[**Image** \\
Optimize Images in your Next.js Application using the built-in \`next/image\` Component.](https://nextjs.org/docs/app/api-reference/components/image)

Was this helpful?

supported.

Send

## Next.js Multi-Zones Deployment
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Deploying](https://nextjs.org/docs/app/building-your-application/deploying) Multi-Zones

# Multi-Zones

Examples

- [With Zones](https://github.com/vercel/next.js/tree/canary/examples/with-zones)

Multi-Zones are an approach to micro-frontends that separate a large application on a domain into smaller Next.js applications that each serve a set of paths. This is useful when there are collections of pages unrelated to the other pages in the application. By moving those pages to a separate zone (i.e., a separate application), you can reduce the size of each application which improves build times and removes code that is only necessary for one of the zones. Since applications are decoupled, Multi-Zones also allows other applications on the domain to use their own choice of framework.

For example, let's say you have the following set of pages that you would like to split up:

- `/blog/*` for all blog posts
- `/dashboard/*` for all pages when the user is logged-in to the dashboard
- `/*` for the rest of your website not covered by other zones

With Multi-Zones support, you can create three applications that all are served on the same domain and look the same to the user, but you can develop and deploy each of the applications independently.

![Three zones: A, B, C. Showing a hard navigation between routes from different zones, and soft navigations between routes within the same zone.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fmulti-zones.png&w=3840&q=75)![Three zones: A, B, C. Showing a hard navigation between routes from different zones, and soft navigations between routes within the same zone.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fmulti-zones.png&w=3840&q=75)

Navigating between pages in the same zone will perform soft navigations, a navigation that does not require reloading the page. For example, in this diagram, navigating from `/` to `/products` will be a soft navigation.

Navigating from a page in one zone to a page in another zone, such as from `/` to `/dashboard`, will perform a hard navigation, unloading the resources of the current page and loading the resources of the new page. Pages that are frequently visited together should live in the same zone to avoid hard navigations.

## [How to define a zone](https://nextjs.org/docs/app/building-your-application/deploying/multi-zones\#how-to-define-a-zone)

A zone is a normal Next.js application where you also configure an [assetPrefix](https://nextjs.org/docs/app/api-reference/config/next-config-js/assetPrefix) to avoid conflicts with pages and static files in other zones.

next.config.js

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
const nextConfig = {
  assetPrefix: '/blog-static',
}
```

Next.js assets, such as JavaScript and CSS, will be prefixed with `assetPrefix` to make sure that they don't conflict with assets from other zones. These assets will be served under `/assetPrefix/_next/...` for each of the zones.

The default application handling all paths not routed to another more specific zone does not need an `assetPrefix`.

In versions older than Next.js 15, you may also need an additional rewrite to handle the static assets. This is no longer necessary in Next.js 15.

next.config.js

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
const nextConfig = {
  assetPrefix: '/blog-static',
  async rewrites() {
    return {
      beforeFiles: [\
        {\
          source: '/blog-static/_next/:path+',\
          destination: '/_next/:path+',\
        },\
      ],
    }
  },
}
```

## [How to route requests to the right zone](https://nextjs.org/docs/app/building-your-application/deploying/multi-zones\#how-to-route-requests-to-the-right-zone)

With the Multi Zones set-up, you need to route the paths to the correct zone since they are served by different applications. You can use any HTTP proxy to do this, but one of the Next.js applications can also be used to route requests for the entire domain.

To route to the correct zone using a Next.js application, you can use [`rewrites`](https://nextjs.org/docs/app/api-reference/config/next-config-js/rewrites). For each path served by a different zone, you would add a rewrite rule to send that path to the domain of the other zone. For example:

next.config.js

```code-block_code__isn_V
async rewrites() {
    return [\
        {\
            source: '/blog',\
            destination: `${process.env.BLOG_DOMAIN}/blog`,\
        },\
        {\
            source: '/blog/:path+',\
            destination: `${process.env.BLOG_DOMAIN}/blog/:path+`,\
        }\
    ];
}
```

`destination` should be a URL that is served by the zone, including scheme and domain. This should point to the zone's production domain, but it can also be used to route requests to `localhost` in local development.

> **Good to know**: URL paths should be unique to a zone. For example, two zones trying to serve `/blog` would create a routing conflict.

### [Routing requests using middleware](https://nextjs.org/docs/app/building-your-application/deploying/multi-zones\#routing-requests-using-middleware)

Routing requests through [`rewrites`](https://nextjs.org/docs/app/api-reference/config/next-config-js/rewrites) is recommended to minimize latency overhead for the requests, but middleware can also be used when there is a need for a dynamic decision when routing. For example, if you are using a feature flag to decide where a path should be routed such as during a migration, you can use middleware.

middleware.js

```code-block_code__isn_V
export async function middleware(request) {
  const { pathname, search } = req.nextUrl;
  if (pathname === '/your-path' && myFeatureFlag.isEnabled()) {
    return NextResponse.rewrite(`${rewriteDomain}${pathname}${search});
  }
}
```

## [Linking between zones](https://nextjs.org/docs/app/building-your-application/deploying/multi-zones\#linking-between-zones)

Links to paths in a different zone should use an `a` tag instead of the Next.js [`<Link>`](https://nextjs.org/docs/pages/api-reference/components/link) component. This is because Next.js will try to prefetch and soft navigate to any relative path in `<Link>` component, which will not work across zones.

## [Sharing code](https://nextjs.org/docs/app/building-your-application/deploying/multi-zones\#sharing-code)

The Next.js applications that make up the different zones can live in any repository. However, it is often convenient to put these zones in a [monorepo](https://en.wikipedia.org/wiki/Monorepo) to more easily share code. For zones that live in different repositories, code can also be shared using public or private NPM packages.

Since the pages in different zones may be released at different times, feature flags can be useful for enabling or disabling features in unison across the different zones.

For [Next.js on Vercel](https://vercel.com/?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) applications, you can use a [monorepo](https://vercel.com/blog/monorepos-are-changing-how-teams-build-software?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) to deploy all affected zones with a single `git push`.

## [Server Actions](https://nextjs.org/docs/app/building-your-application/deploying/multi-zones\#server-actions)

When using [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations) with Multi-Zones, you must explicitly allow the user-facing origin since your user facing domain may serve multiple applications. In your `next.config.js` file, add the following lines:

next.config.js

```code-block_code__isn_V
const nextConfig = {
  experimental: {
    serverActions: {
      allowedOrigins: ['your-production-domain.com'],
    },
  },
}
```

See [`serverActions.allowedOrigins`](https://nextjs.org/docs/app/api-reference/config/next-config-js/serverActions#allowedorigins) for more information.

Was this helpful?

supported.

Send

## Next.js Testing Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Building Your Application](https://nextjs.org/docs/app/building-your-application) Testing

# Testing

In React and Next.js, there are a few different types of tests you can write, each with its own purpose and use cases. This page provides an overview of types and commonly used tools you can use to test your application.

## [Types of tests](https://nextjs.org/docs/app/building-your-application/testing\#types-of-tests)

- **Unit Testing** involves testing individual units (or blocks of code) in isolation. In React, a unit can be a single function, hook, or component.
  - **Component Testing** is a more focused version of unit testing where the primary subject of the tests is React components. This may involve testing how components are rendered, their interaction with props, and their behavior in response to user events.
  - **Integration Testing** involves testing how multiple units work together. This can be a combination of components, hooks, and functions.
- **End-to-End (E2E) Testing** involves testing user flows in an environment that simulates real user scenarios, like the browser. This means testing specific tasks (e.g. signup flow) in a production-like environment.
- **Snapshot Testing** involves capturing the rendered output of a component and saving it to a snapshot file. When tests run, the current rendered output of the component is compared against the saved snapshot. Changes in the snapshot are used to indicate unexpected changes in behavior.

## [Async Server Components](https://nextjs.org/docs/app/building-your-application/testing\#async-server-components)

Since `async` Server Components are new to the React ecosystem, some tools do not fully support them. In the meantime, we recommend using **End-to-End Testing** over **Unit Testing** for `async` components.

## [Guides](https://nextjs.org/docs/app/building-your-application/testing\#guides)

See the guides below to learn how to set up Next.js with these commonly used testing tools:

[**Vitest** \\
Learn how to set up Vitest with Next.js for Unit Testing.](https://nextjs.org/docs/app/building-your-application/testing/vitest) [**Jest** \\
Learn how to set up Jest with Next.js for Unit Testing and Snapshot Testing.](https://nextjs.org/docs/app/building-your-application/testing/jest) [**Playwright** \\
Learn how to set up Playwright with Next.js for End-to-End (E2E) Testing.](https://nextjs.org/docs/app/building-your-application/testing/playwright) [**Cypress** \\
Learn how to set up Cypress with Next.js for End-to-End (E2E) and Component Testing.](https://nextjs.org/docs/app/building-your-application/testing/cypress)

Was this helpful?

supported.

Send

## Next.js default.js Overview
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [File Conventions](https://nextjs.org/docs/app/api-reference/file-conventions) default.js

# default.js

The `default.js` file is used to render a fallback within [Parallel Routes](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes) when Next.js cannot recover a [slot's](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes#slots) active state after a full-page load.

During [soft navigation](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#5-soft-navigation), Next.js keeps track of the active _state_ (subpage) for each slot. However, for hard navigations (full-page load), Next.js cannot recover the active state. In this case, a `default.js` file can be rendered for subpages that don't match the current URL.

Consider the following folder structure. The `@team` slot has a `settings` page, but `@analytics` does not.

![Parallel Routes unmatched routes](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fparallel-routes-unmatched-routes.png&w=3840&q=75)![Parallel Routes unmatched routes](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fparallel-routes-unmatched-routes.png&w=3840&q=75)

When navigating to `/settings`, the `@team` slot will render the `settings` page while maintaining the currently active page for the `@analytics` slot.

On refresh, Next.js will render a `default.js` for `@analytics`. If `default.js` doesn't exist, a `404` is rendered instead.

Additionally, since `children` is an implicit slot, you also need to create a `default.js` file to render a fallback for `children` when Next.js cannot recover the active state of the parent page.

## [Reference](https://nextjs.org/docs/app/api-reference/file-conventions/default\#reference)

### [`params` (optional)](https://nextjs.org/docs/app/api-reference/file-conventions/default\#params-optional)

A promise that resolves to an object containing the [dynamic route parameters](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes) from the root segment down to the slot's subpages. For example:

app/\[artist\]/@sidebar/default.js

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Default({
  params,
}: {
  params: Promise<{ artist: string }>
}) {
  const { artist } = await params
}
```

| Example | URL | `params` |
| --- | --- | --- |
| `app/[artist]/@sidebar/default.js` | `/zack` | `Promise<{ artist: 'zack' }>` |
| `app/[artist]/[album]/@sidebar/default.js` | `/zack/next` | `Promise<{ artist: 'zack', album: 'next' }>` |

- Since the `params` prop is a promise. You must use `async/await` or React's [`use`](https://react.dev/reference/react/use) function to access the values.
  - In version 14 and earlier, `params` was a synchronous prop. To help with backwards compatibility, you can still access it synchronously in Next.js 15, but this behavior will be deprecated in the future.

## Learn more about Parallel Routes

[**Parallel Routes** \\
Simultaneously render one or more pages in the same view that can be navigated independently. A pattern for highly dynamic applications.](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes)

Was this helpful?

supported.

Send

## Intercepting Routes in Next.js
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Intercepting Routes

# Intercepting Routes

Intercepting routes allows you to load a route from another part of your application within the current layout. This routing paradigm can be useful when you want to display the content of a route without the user switching to a different context.

For example, when clicking on a photo in a feed, you can display the photo in a modal, overlaying the feed. In this case, Next.js intercepts the `/photo/123` route, masks the URL, and overlays it over `/feed`.

![Intercepting routes soft navigation](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fintercepting-routes-soft-navigate.png&w=3840&q=75)![Intercepting routes soft navigation](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fintercepting-routes-soft-navigate.png&w=3840&q=75)

However, when navigating to the photo by clicking a shareable URL or by refreshing the page, the entire photo page should render instead of the modal. No route interception should occur.

![Intercepting routes hard navigation](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fintercepting-routes-hard-navigate.png&w=3840&q=75)![Intercepting routes hard navigation](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fintercepting-routes-hard-navigate.png&w=3840&q=75)

## [Convention](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes\#convention)

Intercepting routes can be defined with the `(..)` convention, which is similar to relative path convention `../` but for segments.

You can use:

- `(.)` to match segments on the **same level**
- `(..)` to match segments **one level above**
- `(..)(..)` to match segments **two levels above**
- `(...)` to match segments from the **root** `app` directory

For example, you can intercept the `photo` segment from within the `feed` segment by creating a `(..)photo` directory.

![Intercepting routes folder structure](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fintercepted-routes-files.png&w=3840&q=75)![Intercepting routes folder structure](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fintercepted-routes-files.png&w=3840&q=75)

> Note that the `(..)` convention is based on _route segments_, not the file-system.

## [Examples](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes\#examples)

### [Modals](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes\#modals)

Intercepting Routes can be used together with [Parallel Routes](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes) to create modals. This allows you to solve common challenges when building modals, such as:

- Making the modal content **shareable through a URL**.
- **Preserving context** when the page is refreshed, instead of closing the modal.
- **Closing the modal on backwards navigation** rather than going to the previous route.
- **Reopening the modal on forwards navigation**.

Consider the following UI pattern, where a user can open a photo modal from a gallery using client-side navigation, or navigate to the photo page directly from a shareable URL:

![Intercepting routes modal example](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fintercepted-routes-modal-example.png&w=3840&q=75)![Intercepting routes modal example](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fintercepted-routes-modal-example.png&w=3840&q=75)

In the above example, the path to the `photo` segment can use the `(..)` matcher since `@modal` is a slot and **not** a segment. This means that the `photo` route is only one segment level higher, despite being two file-system levels higher.

See the [Parallel Routes](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes#modals) documentation for a step-by-step example, or see our [image gallery example](https://github.com/vercel-labs/nextgram).

> **Good to know:**
>
> - Other examples could include opening a login modal in a top navbar while also having a dedicated `/login` page, or opening a shopping cart in a side modal.

## Next Steps

Learn how to use modals with Intercepted and Parallel Routes.

[**Parallel Routes** \\
Simultaneously render one or more pages in the same view that can be navigated independently. A pattern for highly dynamic applications.](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes)

Was this helpful?

supported.

Send

## Server Actions Overview
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Data Fetching](https://nextjs.org/docs/app/building-your-application/data-fetching) Server Actions and Mutations

# Server Actions and Mutations

[Server Actions](https://react.dev/reference/rsc/server-actions) are **asynchronous functions** that are executed on the server. They can be called in Server and Client Components to handle form submissions and data mutations in Next.js applications.

> **🎥 Watch:** Learn more about mutations with Server Actions → [YouTube (10 minutes)](https://youtu.be/dDpZfOQBMaU?si=cJZHlUu_jFhCzHUg).

## [Convention](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#convention)

A Server Action can be defined with the React [`"use server"`](https://react.dev/reference/react/use-server) directive. You can place the directive at the top of an `async` function to mark the function as a Server Action, or at the top of a separate file to mark all exports of that file as Server Actions.

### [Server Components](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#server-components)

Server Components can use the inline function level or module level `"use server"` directive. To inline a Server Action, add `"use server"` to the top of the function body:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Page() {
  // Server Action
  async function create() {
    'use server'
    // Mutate data
  }

  return '...'
}
```

### [Client Components](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#client-components)

To call a Server Action in a Client Component, create a new file and add the `"use server"` directive at the top of it. All exported functions within the file will be marked as Server Actions that can be reused in both Client and Server Components:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

export async function create() {}
```

app/button.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { create } from './actions'

export function Button() {
  return <button onClick={() => create()}>Create</button>
}
```

### [Passing actions as props](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#passing-actions-as-props)

You can also pass a Server Action to a Client Component as a prop:

```code-block_code__isn_V
<ClientComponent updateItemAction={updateItem} />
```

app/client-component.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

export default function ClientComponent({
  updateItemAction,
}: {
  updateItemAction: (formData: FormData) => void
}) {
  return <form action={updateItemAction}>{/* ... */}</form>
}
```

Usually, the Next.js TypeScript plugin would flag `updateItemAction` in `client-component.tsx` since it is a function which generally can't be serialized across client-server boundaries.
However, props named `action` or ending with `Action` are assumed to receive Server Actions.
This is only a heuristic since the TypeScript plugin doesn't actually know if it receives a Server Action or an ordinary function.
Runtime type-checking will still ensure you don't accidentally pass a function to a Client Component.

## [Behavior](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#behavior)

- Server actions can be invoked using the `action` attribute in a [`<form>` element](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#forms):
  - Server Components support progressive enhancement by default, meaning the form will be submitted even if JavaScript hasn't loaded yet or is disabled.
  - In Client Components, forms invoking Server Actions will queue submissions if JavaScript isn't loaded yet, prioritizing client hydration.
  - After hydration, the browser does not refresh on form submission.
- Server Actions are not limited to `<form>` and can be invoked from event handlers, `useEffect`, third-party libraries, and other form elements like `<button>`.
- Server Actions integrate with the Next.js [caching and revalidation](https://nextjs.org/docs/app/building-your-application/caching) architecture. When an action is invoked, Next.js can return both the updated UI and new data in a single server roundtrip.
- Behind the scenes, actions use the `POST` method, and only this HTTP method can invoke them.
- The arguments and return value of Server Actions must be serializable by React. See the React docs for a list of [serializable arguments and values](https://react.dev/reference/react/use-server#serializable-parameters-and-return-values).
- Server Actions are functions. This means they can be reused anywhere in your application.
- Server Actions inherit the [runtime](https://nextjs.org/docs/app/building-your-application/rendering/edge-and-nodejs-runtimes) from the page or layout they are used on.
- Server Actions inherit the [Route Segment Config](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config) from the page or layout they are used on, including fields like `maxDuration`.

## [Examples](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#examples)

### [Forms](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#forms)

React extends the HTML [`<form>`](https://developer.mozilla.org/docs/Web/HTML/Element/form) element to allow Server Actions to be invoked with the `action` prop.

When invoked in a form, the action automatically receives the [`FormData`](https://developer.mozilla.org/docs/Web/API/FormData/FormData) object. You don't need to use React `useState` to manage fields, instead, you can extract the data using the native [`FormData` methods](https://developer.mozilla.org/en-US/docs/Web/API/FormData#instance_methods):

app/invoices/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Page() {
  async function createInvoice(formData: FormData) {
    'use server'

    const rawFormData = {
      customerId: formData.get('customerId'),
      amount: formData.get('amount'),
      status: formData.get('status'),
    }

    // mutate data
    // revalidate cache
  }

  return <form action={createInvoice}>...</form>
}
```

> **Good to know:**
>
> - Example: [Form with Loading & Error States](https://github.com/vercel/next.js/tree/canary/examples/next-forms)
> - When working with forms that have many fields, you may want to consider using the [`entries()`](https://developer.mozilla.org/en-US/docs/Web/API/FormData/entries) method with JavaScript's [`Object.fromEntries()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/fromEntries). For example: `const rawFormData = Object.fromEntries(formData)`. One thing to note is that the `formData` will include additional `$ACTION_` properties.
> - See [React `<form>` documentation](https://react.dev/reference/react-dom/components/form#handle-form-submission-with-a-server-action) to learn more.

### [Passing additional arguments](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#passing-additional-arguments)

You can pass additional arguments to a Server Action using the JavaScript `bind` method.

app/client-component.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { updateUser } from './actions'

export function UserProfile({ userId }: { userId: string }) {
  const updateUserWithId = updateUser.bind(null, userId)

  return (
    <form action={updateUserWithId}>
      <input type="text" name="name" />
      <button type="submit">Update User Name</button>
    </form>
  )
}
```

The Server Action will receive the `userId` argument, in addition to the form data:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

export async function updateUser(userId: string, formData: FormData) {}
```

> **Good to know**:
>
> - An alternative is to pass arguments as hidden input fields in the form (e.g. `<input type="hidden" name="userId" value={userId} />`). However, the value will be part of the rendered HTML and will not be encoded.
> - `.bind` works in both Server and Client Components. It also supports progressive enhancement.

### [Nested form elements](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#nested-form-elements)

You can also invoke a Server Action in elements nested inside `<form>` such as `<button>`, `<input type="submit">`, and `<input type="image">`. These elements accept the `formAction` prop or [event handlers](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#event-handlers).

This is useful in cases where you want to call multiple server actions within a form. For example, you can create a specific `<button>` element for saving a post draft in addition to publishing it. See the [React `<form>` docs](https://react.dev/reference/react-dom/components/form#handling-multiple-submission-types) for more information.

### [Programmatic form submission](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#programmatic-form-submission)

You can trigger a form submission programmatically using the [`requestSubmit()`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/requestSubmit) method. For example, when the user submits a form using the `⌘` \+ `Enter` keyboard shortcut, you can listen for the `onKeyDown` event:

app/entry.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

export function Entry() {
  const handleKeyDown = (e: React.KeyboardEvent<HTMLTextAreaElement>) => {
    if (
      (e.ctrlKey || e.metaKey) &&
      (e.key === 'Enter' || e.key === 'NumpadEnter')
    ) {
      e.preventDefault()
      e.currentTarget.form?.requestSubmit()
    }
  }

  return (
    <div>
      <textarea name="entry" rows={20} required onKeyDown={handleKeyDown} />
    </div>
  )
}
```

This will trigger the submission of the nearest `<form>` ancestor, which will invoke the Server Action.

### [Server-side form validation](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#server-side-form-validation)

You can use the HTML attributes like `required` and `type="email"` for basic client-side form validation.

For more advanced server-side validation, you can use a library like [zod](https://zod.dev/) to validate the form fields before mutating the data:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { z } from 'zod'

const schema = z.object({
  email: z.string({
    invalid_type_error: 'Invalid Email',
  }),
})

export default async function createUser(formData: FormData) {
  const validatedFields = schema.safeParse({
    email: formData.get('email'),
  })

  // Return early if the form data is invalid
  if (!validatedFields.success) {
    return {
      errors: validatedFields.error.flatten().fieldErrors,
    }
  }

  // Mutate data
}
```

Once the fields have been validated on the server, you can return a serializable object in your action and use the React `useActionState` hook to show a message to the user.

- By passing the action to `useActionState`, the action's function signature changes to receive a new `prevState` or `initialState` parameter as its first argument.
- `useActionState` is a React hook and therefore must be used in a Client Component.

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { redirect } from 'next/navigation'

export async function createUser(prevState: any, formData: FormData) {
  const res = await fetch('https://...')
  const json = await res.json()

  if (!res.ok) {
    return { message: 'Please enter a valid email' }
  }

  redirect('/dashboard')
}
```

Then, you can pass your action to the `useActionState` hook and use the returned `state` to display an error message.

app/ui/signup.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useActionState } from 'react'
import { createUser } from '@/app/actions'

const initialState = {
  message: '',
}

export function Signup() {
  const [state, formAction, pending] = useActionState(createUser, initialState)

  return (
    <form action={formAction}>
      <label htmlFor="email">Email</label>
      <input type="text" id="email" name="email" required />
      {/* ... */}
      <p aria-live="polite">{state?.message}</p>
      <button disabled={pending}>Sign up</button>
    </form>
  )
}
```

### [Pending states](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#pending-states)

The [`useActionState`](https://react.dev/reference/react/useActionState) hook exposes a `pending` boolean that can be used to show a loading indicator while the action is being executed.

Alternatively, you can use the [`useFormStatus`](https://react.dev/reference/react-dom/hooks/useFormStatus) hook to show a loading indicator while the action is being executed. When using this hook, you'll need to create a separate component to render the loading indicator. For example, to disable the button when the action is pending:

app/ui/button.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useFormStatus } from 'react-dom'

export function SubmitButton() {
  const { pending } = useFormStatus()

  return (
    <button disabled={pending} type="submit">
      Sign Up
    </button>
  )
}
```

You can then nest the `SubmitButton` component inside the form:

app/ui/signup.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { SubmitButton } from './button'
import { createUser } from '@/app/actions'

export function Signup() {
  return (
    <form action={createUser}>
      {/* Other form elements */}
      <SubmitButton />
    </form>
  )
}
```

> **Good to know:** In React 19, `useFormStatus` includes additional keys on the returned object, like data, method, and action. If you are not using React 19, only the `pending` key is available.

### [Optimistic updates](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#optimistic-updates)

You can use the React [`useOptimistic`](https://react.dev/reference/react/useOptimistic) hook to optimistically update the UI before the Server Action finishes executing, rather than waiting for the response:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useOptimistic } from 'react'
import { send } from './actions'

type Message = {
  message: string
}

export function Thread({ messages }: { messages: Message[] }) {
  const [optimisticMessages, addOptimisticMessage] = useOptimistic<
    Message[],
    string
  >(messages, (state, newMessage) => [...state, { message: newMessage }])

  const formAction = async (formData: FormData) => {
    const message = formData.get('message') as string
    addOptimisticMessage(message)
    await send(message)
  }

  return (
    <div>
      {optimisticMessages.map((m, i) => (
        <div key={i}>{m.message}</div>
      ))}
      <form action={formAction}>
        <input type="text" name="message" />
        <button type="submit">Send</button>
      </form>
    </div>
  )
}
```

### [Event handlers](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#event-handlers)

While it's common to use Server Actions within `<form>` elements, they can also be invoked with event handlers such as `onClick`. For example, to increment a like count:

app/like-button.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { incrementLike } from './actions'
import { useState } from 'react'

export default function LikeButton({ initialLikes }: { initialLikes: number }) {
  const [likes, setLikes] = useState(initialLikes)

  return (
    <>
      <p>Total Likes: {likes}</p>
      <button
        onClick={async () => {
          const updatedLikes = await incrementLike()
          setLikes(updatedLikes)
        }}
      >
        Like
      </button>
    </>
  )
}
```

You can also add event handlers to form elements, for example, to save a form field `onChange`:

app/ui/edit-post.tsx

```code-block_code__isn_V
'use client'

import { publishPost, saveDraft } from './actions'

export default function EditPost() {
  return (
    <form action={publishPost}>
      <textarea
        name="content"
        onChange={async (e) => {
          await saveDraft(e.target.value)
        }}
      />
      <button type="submit">Publish</button>
    </form>
  )
}
```

For cases like this, where multiple events might be fired in quick succession, we recommend **debouncing** to prevent unnecessary Server Action invocations.

### [`useEffect`](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#useeffect)

You can use the React [`useEffect`](https://react.dev/reference/react/useEffect) hook to invoke a Server Action when the component mounts or a dependency changes. This is useful for mutations that depend on global events or need to be triggered automatically. For example, `onKeyDown` for app shortcuts, an intersection observer hook for infinite scrolling, or when the component mounts to update a view count:

app/view-count.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { incrementViews } from './actions'
import { useState, useEffect } from 'react'

export default function ViewCount({ initialViews }: { initialViews: number }) {
  const [views, setViews] = useState(initialViews)

  useEffect(() => {
    const updateViews = async () => {
      const updatedViews = await incrementViews()
      setViews(updatedViews)
    }

    updateViews()
  }, [])

  return <p>Total Views: {views}</p>
}
```

Remember to consider the [behavior and caveats](https://react.dev/reference/react/useEffect#caveats) of `useEffect`.

### [Error Handling](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#error-handling)

When an error is thrown, it'll be caught by the nearest `error.js` or `<Suspense>` boundary on the client. See [Error Handling](https://nextjs.org/docs/app/building-your-application/routing/error-handling) for more information.

> **Good to know:**
>
> - Aside from throwing the error, you can also return an object to be handled by `useActionState`. See [Server-side validation and error handling](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#server-side-form-validation).

### [Revalidating data](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#revalidating-data)

You can revalidate the [Next.js Cache](https://nextjs.org/docs/app/building-your-application/caching) inside your Server Actions with the [`revalidatePath`](https://nextjs.org/docs/app/api-reference/functions/revalidatePath) API:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { revalidatePath } from 'next/cache'

export async function createPost() {
  try {
    // ...
  } catch (error) {
    // ...
  }

  revalidatePath('/posts')
}
```

Or invalidate a specific data fetch with a cache tag using [`revalidateTag`](https://nextjs.org/docs/app/api-reference/functions/revalidateTag):

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { revalidateTag } from 'next/cache'

export async function createPost() {
  try {
    // ...
  } catch (error) {
    // ...
  }

  revalidateTag('posts')
}
```

### [Redirecting](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#redirecting)

If you would like to redirect the user to a different route after the completion of a Server Action, you can use [`redirect`](https://nextjs.org/docs/app/api-reference/functions/redirect) API. `redirect` needs to be called outside of the `try/catch` block:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { redirect } from 'next/navigation'
import { revalidateTag } from 'next/cache'

export async function createPost(id: string) {
  try {
    // ...
  } catch (error) {
    // ...
  }

  revalidateTag('posts') // Update cached posts
  redirect(`/post/${id}`) // Navigate to the new post page
}
```

### [Cookies](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#cookies)

You can `get`, `set`, and `delete` cookies inside a Server Action using the [`cookies`](https://nextjs.org/docs/app/api-reference/functions/cookies) API:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { cookies } from 'next/headers'

export async function exampleAction() {
  const cookieStore = await cookies()

  // Get cookie
  cookieStore.get('name')?.value

  // Set cookie
  cookieStore.set('name', 'Delba')

  // Delete cookie
  cookieStore.delete('name')
}
```

See [additional examples](https://nextjs.org/docs/app/api-reference/functions/cookies#deleting-cookies) for deleting cookies from Server Actions.

## [Security](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#security)

By default, when a Server Action is created and exported, it creates a public HTTP endpoint
and should be treated with the same security assumptions and authorization checks. This means, even if a Server Action or utility function is not imported elsewhere in your code, it’s still publicly accessible.

To improve security, Next.js has the following built-in features:

- **Secure action IDs:** Next.js creates encrypted, non-deterministic IDs to allow the client to reference and call the Server Action. These IDs are periodically recalculated between builds for enhanced security.
- **Dead code elimination:** Unused Server Actions (referenced by their IDs) are removed from client bundle to avoid public access by third-party.

> **Good to know**:
>
> The IDs are created during compilation and are cached for a maximum of 14 days. They will be regenerated when a new build is initiated or when the build cache is invalidated.
> This security improvement reduces the risk in cases where an authentication layer is missing. However, you should still treat Server Actions like public HTTP endpoints.

```code-block_code__isn_V
// app/actions.js
'use server'

// This action **is** used in our application, so Next.js
// will create a secure ID to allow the client to reference
// and call the Server Action.
export async function updateUserAction(formData) {}

// This action **is not** used in our application, so Next.js
// will automatically remove this code during `next build`
// and will not create a public endpoint.
export async function deleteUserAction(formData) {}
```

### [Authentication and authorization](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#authentication-and-authorization)

You should ensure that the user is authorized to perform the action. For example:

app/actions.ts

```code-block_code__isn_V
'use server'

import { auth } from './lib'

export function addItem() {
  const { user } = auth()
  if (!user) {
    throw new Error('You must be signed in to perform this action')
  }

  // ...
}
```

### [Closures and encryption](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#closures-and-encryption)

Defining a Server Action inside a component creates a [closure](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures) where the action has access to the outer function's scope. For example, the `publish` action has access to the `publishVersion` variable:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Page() {
  const publishVersion = await getLatestVersion();

  async function publish() {
    "use server";
    if (publishVersion !== await getLatestVersion()) {
      throw new Error('The version has changed since pressing publish');
    }
    ...
  }

  return (
    <form>
      <button formAction={publish}>Publish</button>
    </form>
  );
}
```

Closures are useful when you need to capture a _snapshot_ of data (e.g. `publishVersion`) at the time of rendering so that it can be used later when the action is invoked.

However, for this to happen, the captured variables are sent to the client and back to the server when the action is invoked. To prevent sensitive data from being exposed to the client, Next.js automatically encrypts the closed-over variables. A new private key is generated for each action every time a Next.js application is built. This means actions can only be invoked for a specific build.

> **Good to know:** We don't recommend relying on encryption alone to prevent sensitive values from being exposed on the client. Instead, you should use the [React taint APIs](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching#preventing-sensitive-data-from-being-exposed-to-the-client) to proactively prevent specific data from being sent to the client.

### [Overwriting encryption keys (advanced)](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#overwriting-encryption-keys-advanced)

When self-hosting your Next.js application across multiple servers, each server instance may end up with a different encryption key, leading to potential inconsistencies.

To mitigate this, you can overwrite the encryption key using the `process.env.NEXT_SERVER_ACTIONS_ENCRYPTION_KEY` environment variable. Specifying this variable ensures that your encryption keys are persistent across builds, and all server instances use the same key. This variable **must** be AES-GCM encrypted.

This is an advanced use case where consistent encryption behavior across multiple deployments is critical for your application. You should consider standard security practices such key rotation and signing.

> **Good to know:** Next.js applications deployed to Vercel automatically handle this.

### [Allowed origins (advanced)](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#allowed-origins-advanced)

Since Server Actions can be invoked in a `<form>` element, this opens them up to [CSRF attacks](https://developer.mozilla.org/en-US/docs/Glossary/CSRF).

Behind the scenes, Server Actions use the `POST` method, and only this HTTP method is allowed to invoke them. This prevents most CSRF vulnerabilities in modern browsers, particularly with [SameSite cookies](https://web.dev/articles/samesite-cookies-explained) being the default.

As an additional protection, Server Actions in Next.js also compare the [Origin header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Origin) to the [Host header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Host) (or `X-Forwarded-Host`). If these don't match, the request will be aborted. In other words, Server Actions can only be invoked on the same host as the page that hosts it.

For large applications that use reverse proxies or multi-layered backend architectures (where the server API differs from the production domain), it's recommended to use the configuration option [`serverActions.allowedOrigins`](https://nextjs.org/docs/app/api-reference/config/next-config-js/serverActions) option to specify a list of safe origins. The option accepts an array of strings.

next.config.js

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
module.exports = {
  experimental: {
    serverActions: {
      allowedOrigins: ['my-proxy.com', '*.my-proxy.com'],
    },
  },
}
```

Learn more about [Security and Server Actions](https://nextjs.org/blog/security-nextjs-server-components-actions).

## [Additional resources](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations\#additional-resources)

For more information, check out the following React docs:

- [Server Actions](https://react.dev/reference/rsc/server-actions)
- [`"use server"`](https://react.dev/reference/react/use-server)
- [`<form>`](https://react.dev/reference/react-dom/components/form)
- [`useFormStatus`](https://react.dev/reference/react-dom/hooks/useFormStatus)
- [`useActionState`](https://react.dev/reference/react/useActionState)
- [`useOptimistic`](https://react.dev/reference/react/useOptimistic)

## Next Steps

Learn how to configure Server Actions in Next.js

[**serverActions** \\
Configure Server Actions behavior in your Next.js application.](https://nextjs.org/docs/app/api-reference/config/next-config-js/serverActions)

Was this helpful?

supported.

Send

## OpenTelemetry for Next.js
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) OpenTelemetry

# OpenTelemetry

Observability is crucial for understanding and optimizing the behavior and performance of your Next.js app.

As applications become more complex, it becomes increasingly difficult to identify and diagnose issues that may arise. By leveraging observability tools, such as logging and metrics, developers can gain insights into their application's behavior and identify areas for optimization. With observability, developers can proactively address issues before they become major problems and provide a better user experience. Therefore, it is highly recommended to use observability in your Next.js applications to improve performance, optimize resources, and enhance user experience.

We recommend using OpenTelemetry for instrumenting your apps.
It's a platform-agnostic way to instrument apps that allows you to change your observability provider without changing your code.
Read [Official OpenTelemetry docs](https://opentelemetry.io/docs/) for more information about OpenTelemetry and how it works.

This documentation uses terms like _Span_, _Trace_ or _Exporter_ throughout this doc, all of which can be found in [the OpenTelemetry Observability Primer](https://opentelemetry.io/docs/concepts/observability-primer/).

Next.js supports OpenTelemetry instrumentation out of the box, which means that we already instrumented Next.js itself.
When you enable OpenTelemetry we will automatically wrap all your code like `getStaticProps` in _spans_ with helpful attributes.

## [Getting Started](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#getting-started)

OpenTelemetry is extensible but setting it up properly can be quite verbose.
That's why we prepared a package `@vercel/otel` that helps you get started quickly.

### [Using `@vercel/otel`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#using-vercelotel)

To get started, install the following packages:

Terminal

```code-block_code__isn_V
npm install @vercel/otel @opentelemetry/sdk-logs @opentelemetry/api-logs @opentelemetry/instrumentation
```

Next, create a custom [`instrumentation.ts`](https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation) (or `.js`) file in the **root directory** of the project (or inside `src` folder if using one):

your-project/instrumentation.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { registerOTel } from '@vercel/otel'

export function register() {
  registerOTel({ serviceName: 'next-app' })
}
```

See the [`@vercel/otel` documentation](https://www.npmjs.com/package/@vercel/otel) for additional configuration options.

> **Good to know**:
>
> - The `instrumentation` file should be in the root of your project and not inside the `app` or `pages` directory. If you're using the `src` folder, then place the file inside `src` alongside `pages` and `app`.
> - If you use the [`pageExtensions` config option](https://nextjs.org/docs/app/api-reference/config/next-config-js/pageExtensions) to add a suffix, you will also need to update the `instrumentation` filename to match.
> - We have created a basic [with-opentelemetry](https://github.com/vercel/next.js/tree/canary/examples/with-opentelemetry) example that you can use.

### [Manual OpenTelemetry configuration](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#manual-opentelemetry-configuration)

The `@vercel/otel` package provides many configuration options and should serve most of common use cases. But if it doesn't suit your needs, you can configure OpenTelemetry manually.

Firstly you need to install OpenTelemetry packages:

Terminal

```code-block_code__isn_V
npm install @opentelemetry/sdk-node @opentelemetry/resources @opentelemetry/semantic-conventions @opentelemetry/sdk-trace-node @opentelemetry/exporter-trace-otlp-http
```

Now you can initialize `NodeSDK` in your `instrumentation.ts`.
Unlike `@vercel/otel`, `NodeSDK` is not compatible with edge runtime, so you need to make sure that you are importing them only when `process.env.NEXT_RUNTIME === 'nodejs'`. We recommend creating a new file `instrumentation.node.ts` which you conditionally import only when using node:

instrumentation.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function register() {
  if (process.env.NEXT_RUNTIME === 'nodejs') {
    await import('./instrumentation.node.ts')
  }
}
```

instrumentation.node.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { OTLPTraceExporter } from '@opentelemetry/exporter-trace-otlp-http'
import { Resource } from '@opentelemetry/resources'
import { NodeSDK } from '@opentelemetry/sdk-node'
import { SimpleSpanProcessor } from '@opentelemetry/sdk-trace-node'
import { ATTR_SERVICE_NAME } from '@opentelemetry/semantic-conventions'

const sdk = new NodeSDK({
  resource: new Resource({
    [ATTR_SERVICE_NAME]: 'next-app',
  }),
  spanProcessor: new SimpleSpanProcessor(new OTLPTraceExporter()),
})
sdk.start()
```

Doing this is equivalent to using `@vercel/otel`, but it's possible to modify and extend some features that are not exposed by the `@vercel/otel`. If edge runtime support is necessary, you will have to use `@vercel/otel`.

## [Testing your instrumentation](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#testing-your-instrumentation)

You need an OpenTelemetry collector with a compatible backend to test OpenTelemetry traces locally.
We recommend using our [OpenTelemetry dev environment](https://github.com/vercel/opentelemetry-collector-dev-setup).

If everything works well you should be able to see the root server span labeled as `GET /requested/pathname`.
All other spans from that particular trace will be nested under it.

Next.js traces more spans than are emitted by default.
To see more spans, you must set `NEXT_OTEL_VERBOSE=1`.

## [Deployment](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#deployment)

### [Using OpenTelemetry Collector](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#using-opentelemetry-collector)

When you are deploying with OpenTelemetry Collector, you can use `@vercel/otel`.
It will work both on Vercel and when self-hosted.

#### [Deploying on Vercel](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#deploying-on-vercel)

We made sure that OpenTelemetry works out of the box on Vercel.

Follow [Vercel documentation](https://vercel.com/docs/concepts/observability/otel-overview/quickstart) to connect your project to an observability provider.

#### [Self-hosting](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#self-hosting)

Deploying to other platforms is also straightforward. You will need to spin up your own OpenTelemetry Collector to receive and process the telemetry data from your Next.js app.

To do this, follow the [OpenTelemetry Collector Getting Started guide](https://opentelemetry.io/docs/collector/getting-started/), which will walk you through setting up the collector and configuring it to receive data from your Next.js app.

Once you have your collector up and running, you can deploy your Next.js app to your chosen platform following their respective deployment guides.

### [Custom Exporters](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#custom-exporters)

OpenTelemetry Collector is not necessary. You can use a custom OpenTelemetry exporter with [`@vercel/otel`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry#using-vercelotel) or [manual OpenTelemetry configuration](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry#manual-opentelemetry-configuration).

## [Custom Spans](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#custom-spans)

You can add a custom span with [OpenTelemetry APIs](https://opentelemetry.io/docs/instrumentation/js/instrumentation).

Terminal

```code-block_code__isn_V
npm install @opentelemetry/api
```

The following example demonstrates a function that fetches GitHub stars and adds a custom `fetchGithubStars` span to track the fetch request's result:

```code-block_code__isn_V
import { trace } from '@opentelemetry/api'

export async function fetchGithubStars() {
  return await trace
    .getTracer('nextjs-example')
    .startActiveSpan('fetchGithubStars', async (span) => {
      try {
        return await getValue()
      } finally {
        span.end()
      }
    })
}
```

The `register` function will execute before your code runs in a new environment.
You can start creating new spans, and they should be correctly added to the exported trace.

## [Default Spans in Next.js](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#default-spans-in-nextjs)

Next.js automatically instruments several spans for you to provide useful insights into your application's performance.

Attributes on spans follow [OpenTelemetry semantic conventions](https://opentelemetry.io/docs/reference/specification/trace/semantic_conventions/). We also add some custom attributes under the `next` namespace:

- `next.span_name` \- duplicates span name
- `next.span_type` \- each span type has a unique identifier
- `next.route` \- The route pattern of the request (e.g., `/[param]/user`).
- `next.rsc` (true/false) - Whether the request is an RSC request, such as prefetch.
- `next.page`
  - This is an internal value used by an app router.
  - You can think about it as a route to a special file (like `page.ts`, `layout.ts`, `loading.ts` and others)
  - It can be used as a unique identifier only when paired with `next.route` because `/layout` can be used to identify both `/(groupA)/layout.ts` and `/(groupB)/layout.ts`

### [`[http.method] [next.route]`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#httpmethod-nextroute)

- `next.span_type`: `BaseServer.handleRequest`

This span represents the root span for each incoming request to your Next.js application. It tracks the HTTP method, route, target, and status code of the request.

Attributes:

- [Common HTTP attributes](https://opentelemetry.io/docs/reference/specification/trace/semantic_conventions/http/#common-attributes)
  - `http.method`
  - `http.status_code`
- [Server HTTP attributes](https://opentelemetry.io/docs/reference/specification/trace/semantic_conventions/http/#http-server-semantic-conventions)
  - `http.route`
  - `http.target`
- `next.span_name`
- `next.span_type`
- `next.route`

### [`render route (app) [next.route]`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#render-route-app-nextroute)

- `next.span_type`: `AppRender.getBodyResult`.

This span represents the process of rendering a route in the app router.

Attributes:

- `next.span_name`
- `next.span_type`
- `next.route`

### [`fetch [http.method] [http.url]`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#fetch-httpmethod-httpurl)

- `next.span_type`: `AppRender.fetch`

This span represents the fetch request executed in your code.

Attributes:

- [Common HTTP attributes](https://opentelemetry.io/docs/reference/specification/trace/semantic_conventions/http/#common-attributes)
  - `http.method`
- [Client HTTP attributes](https://opentelemetry.io/docs/reference/specification/trace/semantic_conventions/http/#http-client)
  - `http.url`
  - `net.peer.name`
  - `net.peer.port` (only if specified)
- `next.span_name`
- `next.span_type`

This span can be turned off by setting `NEXT_OTEL_FETCH_DISABLED=1` in your environment. This is useful when you want to use a custom fetch instrumentation library.

### [`executing api route (app) [next.route]`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#executing-api-route-app-nextroute)

- `next.span_type`: `AppRouteRouteHandlers.runHandler`.

This span represents the execution of an API Route Handler in the app router.

Attributes:

- `next.span_name`
- `next.span_type`
- `next.route`

### [`getServerSideProps [next.route]`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#getserversideprops-nextroute)

- `next.span_type`: `Render.getServerSideProps`.

This span represents the execution of `getServerSideProps` for a specific route.

Attributes:

- `next.span_name`
- `next.span_type`
- `next.route`

### [`getStaticProps [next.route]`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#getstaticprops-nextroute)

- `next.span_type`: `Render.getStaticProps`.

This span represents the execution of `getStaticProps` for a specific route.

Attributes:

- `next.span_name`
- `next.span_type`
- `next.route`

### [`render route (pages) [next.route]`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#render-route-pages-nextroute)

- `next.span_type`: `Render.renderDocument`.

This span represents the process of rendering the document for a specific route.

Attributes:

- `next.span_name`
- `next.span_type`
- `next.route`

### [`generateMetadata [next.page]`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#generatemetadata-nextpage)

- `next.span_type`: `ResolveMetadata.generateMetadata`.

This span represents the process of generating metadata for a specific page (a single route can have multiple of these spans).

Attributes:

- `next.span_name`
- `next.span_type`
- `next.page`

### [`resolve page components`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#resolve-page-components)

- `next.span_type`: `NextNodeServer.findPageComponents`.

This span represents the process of resolving page components for a specific page.

Attributes:

- `next.span_name`
- `next.span_type`
- `next.route`

### [`resolve segment modules`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#resolve-segment-modules)

- `next.span_type`: `NextNodeServer.getLayoutOrPageModule`.

This span represents loading of code modules for a layout or a page.

Attributes:

- `next.span_name`
- `next.span_type`
- `next.segment`

### [`start response`](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry\#start-response)

- `next.span_type`: `NextNodeServer.startResponse`.

This zero-length span represents the time when the first byte has been sent in the response.

Was this helpful?

supported.

Send

## Next.js Instrumentation Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) Instrumentation

# Instrumentation

Instrumentation is the process of using code to integrate monitoring and logging tools into your application. This allows you to track the performance and behavior of your application, and to debug issues in production.

## [Convention](https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation\#convention)

To set up instrumentation, create `instrumentation.ts|js` file in the **root directory** of your project (or inside the [`src`](https://nextjs.org/docs/app/building-your-application/configuring/src-directory) folder if using one).

Then, export a `register` function in the file. This function will be called **once** when a new Next.js server instance is initiated.

For example, to use Next.js with [OpenTelemetry](https://opentelemetry.io/) and [@vercel/otel](https://vercel.com/docs/observability/otel-overview):

instrumentation.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { registerOTel } from '@vercel/otel'

export function register() {
  registerOTel('next-app')
}
```

See the [Next.js with OpenTelemetry example](https://github.com/vercel/next.js/tree/canary/examples/with-opentelemetry) for a complete implementation.

> **Good to know**:
>
> - The `instrumentation` file should be in the root of your project and not inside the `app` or `pages` directory. If you're using the `src` folder, then place the file inside `src` alongside `pages` and `app`.
> - If you use the [`pageExtensions` config option](https://nextjs.org/docs/app/api-reference/config/next-config-js/pageExtensions) to add a suffix, you will also need to update the `instrumentation` filename to match.

## [Examples](https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation\#examples)

### [Importing files with side effects](https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation\#importing-files-with-side-effects)

Sometimes, it may be useful to import a file in your code because of the side effects it will cause. For example, you might import a file that defines a set of global variables, but never explicitly use the imported file in your code. You would still have access to the global variables the package has declared.

We recommend importing files using JavaScript `import` syntax within your `register` function. The following example demonstrates a basic usage of `import` in a `register` function:

instrumentation.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function register() {
  await import('package-with-side-effect')
}
```

> **Good to know:**
>
> We recommend importing the file from within the `register` function, rather than at the top of the file. By doing this, you can colocate all of your side effects in one place in your code, and avoid any unintended consequences from importing globally at the top of the file.

### [Importing runtime-specific code](https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation\#importing-runtime-specific-code)

Next.js calls `register` in all environments, so it's important to conditionally import any code that doesn't support specific runtimes (e.g. [Edge or Node.js](https://nextjs.org/docs/app/building-your-application/rendering/edge-and-nodejs-runtimes)). You can use the `NEXT_RUNTIME` environment variable to get the current environment:

instrumentation.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function register() {
  if (process.env.NEXT_RUNTIME === 'nodejs') {
    await import('./instrumentation-node')
  }

  if (process.env.NEXT_RUNTIME === 'edge') {
    await import('./instrumentation-edge')
  }
}
```

## Learn more about Instrumentation

[**instrumentation.js** \\
API reference for the instrumentation.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/instrumentation)

Was this helpful?

supported.

Send

## Next.js 'use server' Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [Directives](https://nextjs.org/docs/app/api-reference/directives) use server

# use server

The `use server` directive designates a function or file to be executed on the **server side**. It can be used at the top of a file to indicate that all functions in the file are server-side, or inline at the top of a function to mark the function as a [Server Function](https://19.react.dev/reference/rsc/server-functions). This is a React feature.

## [Using `use server` at the top of a file](https://nextjs.org/docs/app/api-reference/directives/use-server\#using-use-server-at-the-top-of-a-file)

The following example shows a file with a `use server` directive at the top. All functions in the file are executed on the server.

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'
import { db } from '@/lib/db' // Your database client

export async function createUser(data: { name: string; email: string }) {
  const user = await db.user.create({ data })
  return user
}
```

### [Using Server Functions in a Client Component](https://nextjs.org/docs/app/api-reference/directives/use-server\#using-server-functions-in-a-client-component)

To use Server Functions in Client Components you need to create your Server Functions in a dedicated file using the `use server` directive at the top of the file. These Server Functions can then be imported into Client and Server Components and executed.

Assuming you have a `fetchUsers` Server Function in `actions.ts`:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'
import { db } from '@/lib/db' // Your database client

export async function fetchUsers() {
  const users = await db.user.findMany()
  return users
}
```

Then you can import the `fetchUsers` Server Function into a Client Component and execute it on the client-side.

app/components/my-button.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'
import { fetchUsers } from '../actions'

export default function MyButton() {
  return <button onClick={() => fetchUsers()}>Fetch Users</button>
}
```

## [Using `use server` inline](https://nextjs.org/docs/app/api-reference/directives/use-server\#using-use-server-inline)

In the following example, `use server` is used inline at the top of a function to mark it as a [Server Function](https://19.react.dev/reference/rsc/server-functions):

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { db } from '@/lib/db' // Your database client

export default function UserList() {
  async function fetchUsers() {
    'use server'
    const users = await db.user.findMany()
    return users
  }

  return <button onClick={() => fetchUsers()}>Fetch Users</button>
}
```

## [Security considerations](https://nextjs.org/docs/app/api-reference/directives/use-server\#security-considerations)

When using the `use server` directive, it's important to ensure that all server-side logic is secure and that sensitive data remains protected.

### [Authentication and authorization](https://nextjs.org/docs/app/api-reference/directives/use-server\#authentication-and-authorization)

Always authenticate and authorize users before performing sensitive server-side operations.

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { db } from '@/lib/db' // Your database client
import { authenticate } from '@/lib/auth' // Your authentication library

export async function createUser(
  data: { name: string; email: string },
  token: string
) {
  const user = authenticate(token)
  if (!user) {
    throw new Error('Unauthorized')
  }
  const newUser = await db.user.create({ data })
  return newUser
}
```

## [Reference](https://nextjs.org/docs/app/api-reference/directives/use-server\#reference)

See the [React documentation](https://react.dev/reference/rsc/use-server) for more information on `use server`.

Was this helpful?

supported.

Send

## Next.js Data Fetching
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Building Your Application](https://nextjs.org/docs/app/building-your-application) Data Fetching

# Data Fetching

[**Data Fetching and Caching** \\
Learn best practices for fetching data on the server or client in Next.js.](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching) [**Server Actions and Mutations** \\
Learn how to handle form submissions and data mutations with Next.js.](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations) [**Incremental Static Regeneration (ISR)** \\
Learn how to create or update static pages at runtime with Incremental Static Regeneration.](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration)

Was this helpful?

supported.

Send

## Partial Prerendering Overview
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Rendering](https://nextjs.org/docs/app/building-your-application/rendering) Partial Prerendering

# Partial Prerendering

> **Note:** Partial Prerendering is an **experimental** feature only available on canary and is subject to change. It is not ready for production use.

Partial Prerendering (PPR) enables you to combine static and dynamic components together in the same route.

During the build, Next.js prerenders as much of the route as possible. If [dynamic](https://nextjs.org/docs/app/building-your-application/rendering/server-components#dynamic-rendering) code is detected, like reading from the incoming request, you can wrap the relevant component with a [React Suspense](https://react.dev/reference/react/Suspense) boundary. The Suspense boundary fallback will then be included in the prerendered HTML.

![Partially Prerendered Product Page showing static nav and product information, and dynamic cart and recommended products](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Flearn%2Flight%2Fthinking-in-ppr.png&w=3840&q=75)![Partially Prerendered Product Page showing static nav and product information, and dynamic cart and recommended products](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Flearn%2Fdark%2Fthinking-in-ppr.png&w=3840&q=75)

> **🎥 Watch:** Why PPR and how it works → [YouTube (10 minutes)](https://www.youtube.com/watch?v=MTcPrTIBkpA).

## [Background](https://nextjs.org/docs/app/building-your-application/rendering/partial-prerendering\#background)

PPR enables your Next.js server to immediately send prerendered content.

To prevent client to server waterfalls, dynamic components begin streaming from the server in parallel while serving the initial prerender. This ensures dynamic components can begin rendering before client JavaScript has been loaded in the browser.

To prevent creating many HTTP requests for each dynamic component, PPR is able to combine the static prerender and dynamic components together into a single HTTP request. This ensures there are not multiple network roundtrips needed for each dynamic component.

## [Using Partial Prerendering](https://nextjs.org/docs/app/building-your-application/rendering/partial-prerendering\#using-partial-prerendering)

### [Incremental Adoption (Version 15 Canary Versions)](https://nextjs.org/docs/app/building-your-application/rendering/partial-prerendering\#incremental-adoption-version-15-canary-versions)

In Next.js 15 canary versions, PPR is available as an experimental feature. It's not available in the stable versions yet. To install:

```code-block_code__isn_V
npm install next@canary
```

You can incrementally adopt Partial Prerendering in [layouts](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates) and [pages](https://nextjs.org/docs/app/api-reference/file-conventions/page) by setting the [`ppr`](https://nextjs.org/docs/app/api-reference/config/next-config-js/ppr) option in `next.config.js` to `incremental`, and exporting the `experimental_ppr` [route config option](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config) at the top of the file:

next.config.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  experimental: {
    ppr: 'incremental',
  },
}

export default nextConfig
```

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Suspense } from 'react'
import { StaticComponent, DynamicComponent, Fallback } from '@/app/ui'

export const experimental_ppr = true

export default function Page() {
  return (
    <>
      <StaticComponent />
      <Suspense fallback={<Fallback />}>
        <DynamicComponent />
      </Suspense>
    </>
  )
}
```

> **Good to know**:
>
> - Routes that don't have `experimental_ppr` will default to `false` and will not be prerendered using PPR. You need to explicitly opt-in to PPR for each route.
> - `experimental_ppr` will apply to all children of the route segment, including nested layouts and pages. You don't have to add it to every file, only the top segment of a route.
> - To disable PPR for children segments, you can set `experimental_ppr` to `false` in the child segment.

## [Dynamic Components](https://nextjs.org/docs/app/building-your-application/rendering/partial-prerendering\#dynamic-components)

When creating the prerender for your route during `next build`, Next.js requires that Dynamic APIs are wrapped with React Suspense. The `fallback` is then included in the prerender.

For example, using functions like `cookies` or `headers`:

app/user.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { cookies } from 'next/headers'

export async function User() {
  const session = (await cookies()).get('session')?.value
  return '...'
}
```

This component requires looking at the incoming request to read cookies. To use this with PPR, you should wrap the component with Suspense:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Suspense } from 'react'
import { User, AvatarSkeleton } from './user'

export const experimental_ppr = true

export default function Page() {
  return (
    <section>
      <h1>This will be prerendered</h1>
      <Suspense fallback={<AvatarSkeleton />}>
        <User />
      </Suspense>
    </section>
  )
}
```

Components only opt into dynamic rendering when the value is accessed.

For example, if you are reading `searchParams` from a `page`, you can forward this value to another component as a prop:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Table } from './table'

export default function Page({
  searchParams,
}: {
  searchParams: Promise<{ sort: string }>
}) {
  return (
    <section>
      <h1>This will be prerendered</h1>
      <Table searchParams={searchParams} />
    </section>
  )
}
```

Inside of the table component, accessing the value from `searchParams` will make the component run dynamically:

app/table.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function Table({
  searchParams,
}: {
  searchParams: Promise<{ sort: string }>
}) {
  const sort = (await searchParams).sort === 'true'
  return '...'
}
```

Was this helpful?

supported.

Send

## Next.js Metadata Optimization
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) Metadata

# Metadata

Next.js has a Metadata API that can be used to define your application metadata (e.g. `meta` and `link` tags inside your HTML `head` element) for improved SEO and web shareability.

There are two ways you can add metadata to your application:

- **Config-based Metadata**: Export a [static `metadata` object](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#metadata-object) or a dynamic [`generateMetadata` function](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#generatemetadata-function) in a `layout.js` or `page.js` file.
- **File-based Metadata**: Add static or dynamically generated special files to route segments.

With both these options, Next.js will automatically generate the relevant `<head>` elements for your pages. You can also create dynamic OG images using the [`ImageResponse`](https://nextjs.org/docs/app/api-reference/functions/image-response) constructor.

## [Static Metadata](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#static-metadata)

To define static metadata, export a [`Metadata` object](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#metadata-object) from a `layout.js` or static `page.js` file.

layout.tsx \| page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { Metadata } from 'next'

export const metadata: Metadata = {
  title: '...',
  description: '...',
}

export default function Page() {}
```

For all the available options, see the [API Reference](https://nextjs.org/docs/app/api-reference/functions/generate-metadata).

## [Dynamic Metadata](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#dynamic-metadata)

You can use `generateMetadata` function to `fetch` metadata that requires dynamic values.

app/products/\[id\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { Metadata, ResolvingMetadata } from 'next'

type Props = {
  params: Promise<{ id: string }>
  searchParams: Promise<{ [key: string]: string | string[] | undefined }>
}

export async function generateMetadata(
  { params, searchParams }: Props,
  parent: ResolvingMetadata
): Promise<Metadata> {
  // read route params
  const { id } = await params

  // fetch data
  const product = await fetch(`https://.../${id}`).then((res) => res.json())

  // optionally access and extend (rather than replace) parent metadata
  const previousImages = (await parent).openGraph?.images || []

  return {
    title: product.title,
    openGraph: {
      images: ['/some-specific-page-image.jpg', ...previousImages],
    },
  }
}

export default function Page({ params, searchParams }: Props) {}
```

For all the available params, see the [API Reference](https://nextjs.org/docs/app/api-reference/functions/generate-metadata).

> **Good to know**:
>
> - Both static and dynamic metadata through `generateMetadata` are **only supported in Server Components**.
> - `fetch` requests are automatically [memoized](https://nextjs.org/docs/app/building-your-application/caching#request-memoization) for the same data across `generateMetadata`, `generateStaticParams`, Layouts, Pages, and Server Components. React [`cache` can be used](https://nextjs.org/docs/app/building-your-application/caching#react-cache-function) if `fetch` is unavailable.
> - Next.js will wait for data fetching inside `generateMetadata` to complete before streaming UI to the client. This guarantees the first part of a [streamed response](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming) includes `<head>` tags.

## [File-based metadata](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#file-based-metadata)

These special files are available for metadata:

- [favicon.ico, apple-icon.jpg, and icon.jpg](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/app-icons)
- [opengraph-image.jpg and twitter-image.jpg](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/opengraph-image)
- [robots.txt](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/robots)
- [sitemap.xml](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/sitemap)

You can use these for static metadata, or you can programmatically generate these files with code.

For implementation and examples, see the [Metadata Files](https://nextjs.org/docs/app/api-reference/file-conventions/metadata) API Reference and [Dynamic Image Generation](https://nextjs.org/docs/app/building-your-application/optimizing/metadata#dynamic-image-generation).

## [Behavior](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#behavior)

File-based metadata has the higher priority and will override any config-based metadata.

### [Default Fields](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#default-fields)

There are two default `meta` tags that are always added even if a route doesn't define metadata:

- The [meta charset tag](https://developer.mozilla.org/docs/Web/HTML/Element/meta#attr-charset) sets the character encoding for the website.
- The [meta viewport tag](https://developer.mozilla.org/docs/Web/HTML/Viewport_meta_tag) sets the viewport width and scale for the website to adjust for different devices.

```code-block_code__isn_V
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
```

> **Good to know**: You can overwrite the default [`viewport`](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#viewport) meta tag.

### [Ordering](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#ordering)

Metadata is evaluated in order, starting from the root segment down to the segment closest to the final `page.js` segment. For example:

1. `app/layout.tsx` (Root Layout)
2. `app/blog/layout.tsx` (Nested Blog Layout)
3. `app/blog/[slug]/page.tsx` (Blog Page)

### [Merging](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#merging)

Following the [evaluation order](https://nextjs.org/docs/app/building-your-application/optimizing/metadata#ordering), Metadata objects exported from multiple segments in the same route are **shallowly** merged together to form the final metadata output of a route. Duplicate keys are **replaced** based on their ordering.

This means metadata with nested fields such as [`openGraph`](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#opengraph) and [`robots`](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#robots) that are defined in an earlier segment are **overwritten** by the last segment to define them.

#### [Overwriting fields](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#overwriting-fields)

app/layout.js

```code-block_code__isn_V
export const metadata = {
  title: 'Acme',
  openGraph: {
    title: 'Acme',
    description: 'Acme is a...',
  },
}
```

app/blog/page.js

```code-block_code__isn_V
export const metadata = {
  title: 'Blog',
  openGraph: {
    title: 'Blog',
  },
}

// Output:
// <title>Blog</title>
// <meta property="og:title" content="Blog" />
```

In the example above:

- `title` from `app/layout.js` is **replaced** by `title` in `app/blog/page.js`.
- All `openGraph` fields from `app/layout.js` are **replaced** in `app/blog/page.js` because `app/blog/page.js` sets `openGraph` metadata. Note the absence of `openGraph.description`.

If you'd like to share some nested fields between segments while overwriting others, you can pull them out into a separate variable:

app/shared-metadata.js

```code-block_code__isn_V
export const openGraphImage = { images: ['http://...'] }
```

app/page.js

```code-block_code__isn_V
import { openGraphImage } from './shared-metadata'

export const metadata = {
  openGraph: {
    ...openGraphImage,
    title: 'Home',
  },
}
```

app/about/page.js

```code-block_code__isn_V
import { openGraphImage } from '../shared-metadata'

export const metadata = {
  openGraph: {
    ...openGraphImage,
    title: 'About',
  },
}
```

In the example above, the OG image is shared between `app/layout.js` and `app/about/page.js` while the titles are different.

#### [Inheriting fields](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#inheriting-fields)

app/layout.js

```code-block_code__isn_V
export const metadata = {
  title: 'Acme',
  openGraph: {
    title: 'Acme',
    description: 'Acme is a...',
  },
}
```

app/about/page.js

```code-block_code__isn_V
export const metadata = {
  title: 'About',
}

// Output:
// <title>About</title>
// <meta property="og:title" content="Acme" />
// <meta property="og:description" content="Acme is a..." />
```

**Notes**

- `title` from `app/layout.js` is **replaced** by `title` in `app/about/page.js`.
- All `openGraph` fields from `app/layout.js` are **inherited** in `app/about/page.js` because `app/about/page.js` doesn't set `openGraph` metadata.

## [Dynamic Image Generation](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#dynamic-image-generation)

The `ImageResponse` constructor allows you to generate dynamic images using JSX and CSS. This is useful for creating social media images such as Open Graph images, Twitter cards, and more.

To use it, you can import `ImageResponse` from `next/og`:

app/about/route.js

```code-block_code__isn_V
import { ImageResponse } from 'next/og'

export async function GET() {
  return new ImageResponse(
    (
      <div
        style={{
          fontSize: 128,
          background: 'white',
          width: '100%',
          height: '100%',
          display: 'flex',
          textAlign: 'center',
          alignItems: 'center',
          justifyContent: 'center',
        }}
      >
        Hello world!
      </div>
    ),
    {
      width: 1200,
      height: 600,
    }
  )
}
```

`ImageResponse` integrates well with other Next.js APIs, including [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) and file-based Metadata. For example, you can use `ImageResponse` in a `opengraph-image.tsx` file to generate Open Graph images at build time or dynamically at request time.

`ImageResponse` supports common CSS properties including flexbox and absolute positioning, custom fonts, text wrapping, centering, and nested images. [See the full list of supported CSS properties](https://nextjs.org/docs/app/api-reference/functions/image-response).

> **Good to know**:
>
> - Examples are available in the [Vercel OG Playground](https://og-playground.vercel.app/).
> - `ImageResponse` uses [@vercel/og](https://vercel.com/docs/concepts/functions/edge-functions/og-image-generation), [Satori](https://github.com/vercel/satori), and Resvg to convert HTML and CSS into PNG.
> - Only flexbox and a subset of CSS properties are supported. Advanced layouts (e.g. `display: grid`) will not work.
> - Maximum bundle size of `500KB`. The bundle size includes your JSX, CSS, fonts, images, and any other assets. If you exceed the limit, consider reducing the size of any assets or fetching at runtime.
> - Only `ttf`, `otf`, and `woff` font formats are supported. To maximize the font parsing speed, `ttf` or `otf` are preferred over `woff`.

## [JSON-LD](https://nextjs.org/docs/app/building-your-application/optimizing/metadata\#json-ld)

[JSON-LD](https://json-ld.org/) is a format for structured data that can be used by search engines to understand your content. For example, you can use it to describe a person, an event, an organization, a movie, a book, a recipe, and many other types of entities.

Our current recommendation for JSON-LD is to render structured data as a `<script>` tag in your `layout.js` or `page.js` components. For example:

app/products/\[id\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Page({ params }) {
  const { id } = await params
  const product = await getProduct(id)

  const jsonLd = {
    '@context': 'https://schema.org',
    '@type': 'Product',
    name: product.name,
    image: product.image,
    description: product.description,
  }

  return (
    <section>
      {/* Add JSON-LD to your page */}
      <script
        type="application/ld+json"
        dangerouslySetInnerHTML={{ __html: JSON.stringify(jsonLd) }}
      />
      {/* ... */}
    </section>
  )
}
```

You can validate and test your structured data with the [Rich Results Test](https://search.google.com/test/rich-results) for Google or the generic [Schema Markup Validator](https://validator.schema.org/).

You can type your JSON-LD with TypeScript using community packages like [`schema-dts`](https://www.npmjs.com/package/schema-dts):

```code-block_code__isn_V
import { Product, WithContext } from 'schema-dts'

const jsonLd: WithContext<Product> = {
  '@context': 'https://schema.org',
  '@type': 'Product',
  name: 'Next.js Sticker',
  image: 'https://nextjs.org/imgs/sticker.png',
  description: 'Dynamic at the speed of static.',
}
```

## Next Steps

View all the Metadata API options.

[**generateMetadata** \\
Learn how to add Metadata to your Next.js application for improved search engine optimization (SEO) and web shareability.](https://nextjs.org/docs/app/api-reference/functions/generate-metadata) [**Metadata Files** \\
API documentation for the metadata file conventions.](https://nextjs.org/docs/app/api-reference/file-conventions/metadata) [**generateViewport** \\
API Reference for the generateViewport function.](https://nextjs.org/docs/app/api-reference/functions/generate-viewport)

Was this helpful?

supported.

Send

## Using CSS in Next.js
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Getting Started](https://nextjs.org/docs/app/getting-started) CSS

# How to use CSS in your application

Next.js provides several ways to use CSS in your application, including:

- [CSS Modules](https://nextjs.org/docs/app/getting-started/css#css-modules)
- [Global CSS](https://nextjs.org/docs/app/getting-started/css#global-css)
- [Tailwind CSS](https://nextjs.org/docs/app/getting-started/css#tailwind-css)
- [Sass](https://nextjs.org/docs/app/getting-started/css#sass)
- [CSS-in-JS](https://nextjs.org/docs/app/getting-started/css#css-in-js)
- [External Stylesheets](https://nextjs.org/docs/app/getting-started/css#external-stylesheets)

This page will guide you through how to use each of these approaches.

## [CSS Modules](https://nextjs.org/docs/app/getting-started/css\#css-modules)

CSS Modules locally scope CSS by generating unique class names. This allows you to use the same class in different files without worrying about collisions.

To start using CSS Modules, create a new file with the extension `.module.css` and import it into any component inside the `app` directory:

app/blog/styles.module.css

```code-block_code__isn_V
.blog {
  padding: 24px;
}
```

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import styles from './styles.module.css'

export default function Page({ children }: { children: React.ReactNode }) {
  return <main className={styles.blog}>{children}</main>
}
```

## [Global CSS](https://nextjs.org/docs/app/getting-started/css\#global-css)

You can use global CSS to apply styles across your application.

To use global styles, create a new CSS file, for example `app/global.css`:

app/global.css

```code-block_code__isn_V
body {
  padding: 20px 20px 60px;
  max-width: 680px;
  margin: 0 auto;
}
```

Import the file in the root layout ( `app/layout.js`) to apply the styles to **every route** in your application:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
// These styles apply to every route in the application
import './global.css'

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body>{children}</body>
    </html>
  )
}
```

> **Good to know:** Global styles can be imported into any layout, page, or component inside the `app` directory. However, since Next.js uses React's built-in support for stylesheets to integrate with Suspense. This built-in support currently does not remove stylesheets as you navigate between routes. Therefore, we recommend using global styles for _truly_ global CSS, and [CSS Modules](https://nextjs.org/docs/app/getting-started/css#css-modules) for scoped CSS.

## [Tailwind CSS](https://nextjs.org/docs/app/getting-started/css\#tailwind-css)

[Tailwind CSS](https://tailwindcss.com/) is a utility-first CSS framework that integrates seamlessly with Next.js.

### [Installing Tailwind](https://nextjs.org/docs/app/getting-started/css\#installing-tailwind)

To start using Tailwind, install the necessary Tailwind CSS packages:

Terminal

```code-block_code__isn_V
npm install -D tailwindcss @tailwindcss/postcss postcss
```

### [Configuring Tailwind](https://nextjs.org/docs/app/getting-started/css\#configuring-tailwind)

Create a `postcss.config.mjs` file in the root of your project and add the `@tailwindcss/postcss` plugin to your PostCSS configuration:

postcss.config.mjs

```code-block_code__isn_V
/** @type {import('tailwindcss').Config} */
export default {
  plugins: {
    '@tailwindcss/postcss': {},
  },
}
```

### [Using Tailwind](https://nextjs.org/docs/app/getting-started/css\#using-tailwind)

Add the [Tailwind directives](https://tailwindcss.com/docs/functions-and-directives#directives) to your [Global Stylesheet](https://nextjs.org/docs/app/getting-started/css#global-css):

app/globals.css

```code-block_code__isn_V
@import 'tailwindcss';
```

Then, import the styles in the [root layout](https://nextjs.org/docs/app/api-reference/file-conventions/layout#root-layouts):

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { Metadata } from 'next'

// These styles apply to every route in the application
import './globals.css'

export const metadata: Metadata = {
  title: 'Create Next App',
  description: 'Generated by create next app',
}

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body>{children}</body>
    </html>
  )
}
```

Lastly, you can start writing Tailwind's utility classes in your application.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Page() {
  return <h1 className="text-3xl font-bold underline">Hello, Next.js!</h1>
}
```

## [Sass](https://nextjs.org/docs/app/getting-started/css\#sass)

Next.js integrates with [Sass](https://sass-lang.com/) using both the [`.scss`](https://sass-lang.com/documentation/syntax/#scss) and [`.sass`](https://sass-lang.com/documentation/syntax#the-indented-syntax) extensions and syntax.

You can also use component-level Sass via [CSS Modules](https://nextjs.org/docs/app/getting-started/css#css-modules) and the `.module.scss` or `.module.sass` extension.

### [Installing Sass](https://nextjs.org/docs/app/getting-started/css\#installing-sass)

To start using Sass, install the `sass` package:

Terminal

```code-block_code__isn_V
npm install --save-dev sass
```

### [Customizing Sass options](https://nextjs.org/docs/app/getting-started/css\#customizing-sass-options)

If you want to configure your Sass options, use the [`sassOptions`](https://nextjs.org/docs/app/api-reference/config/next-config-js/sassOptions) option in `next.config.js`.

next.config.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  sassOptions: {
    additionalData: `$var: red;`,
  },
}

export default nextConfig
```

## [CSS-in-JS](https://nextjs.org/docs/app/getting-started/css\#css-in-js)

> **Warning:** CSS-in-JS libraries which require runtime JavaScript are not currently supported in React Server Components. Using CSS-in-JS with newer React features like Server Components and Streaming requires library authors to support the latest version of React.

The following libraries are supported in **Client Components** in the `app` directory (alphabetical):

- [`ant-design`](https://ant.design/docs/react/use-with-next#using-app-router)
- [`chakra-ui`](https://chakra-ui.com/getting-started/nextjs-app-guide)
- [`@fluentui/react-components`](https://react.fluentui.dev/?path=/docs/concepts-developer-server-side-rendering-next-js-appdir-setup--page)
- [`kuma-ui`](https://kuma-ui.com/)
- [`@mui/material`](https://mui.com/material-ui/guides/next-js-app-router/)
- [`@mui/joy`](https://mui.com/joy-ui/integrations/next-js-app-router/)
- [`pandacss`](https://panda-css.com/)
- [`styled-jsx`](https://nextjs.org/docs/app/getting-started/css#styled-jsx)
- [`styled-components`](https://nextjs.org/docs/app/getting-started/css#styled-components)
- [`stylex`](https://stylexjs.com/)
- [`tamagui`](https://tamagui.dev/docs/guides/next-js#server-components)
- [`tss-react`](https://tss-react.dev/)
- [`vanilla-extract`](https://vanilla-extract.style/)

The following are currently working on support:

- [`emotion`](https://github.com/emotion-js/emotion/issues/2928)

If you want to style Server Components, we recommend using [CSS Modules](https://nextjs.org/docs/app/getting-started/css#css-modules) or other solutions that output CSS files, like [Tailwind CSS](https://nextjs.org/docs/app/getting-started/css#tailwind-css).

### [Configuring CSS-in-JS](https://nextjs.org/docs/app/getting-started/css\#configuring-css-in-js)

To configure CSS-in-JS, you need to:

1. Create a **style registry** to collect all CSS rules in a render.
2. Use the `useServerInsertedHTML` hook to inject rules before any content that might use them.
3. Create a Client Component that wraps your app with the style registry during initial server-side rendering.

#### [`styled-jsx`](https://nextjs.org/docs/app/getting-started/css\#styled-jsx)

To configure `styled-jsx` for your application, create a new registry:

app/registry.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import React, { useState } from 'react'
import { useServerInsertedHTML } from 'next/navigation'
import { StyleRegistry, createStyleRegistry } from 'styled-jsx'

export default function StyledJsxRegistry({
  children,
}: {
  children: React.ReactNode
}) {
  // Only create stylesheet once with lazy initial state
  // x-ref: https://reactjs.org/docs/hooks-reference.html#lazy-initial-state
  const [jsxStyleRegistry] = useState(() => createStyleRegistry())

  useServerInsertedHTML(() => {
    const styles = jsxStyleRegistry.styles()
    jsxStyleRegistry.flush()
    return <>{styles}</>
  })

  return <StyleRegistry registry={jsxStyleRegistry}>{children}</StyleRegistry>
}
```

Then, wrap your [root layout](https://nextjs.org/docs/app/api-reference/file-conventions/layout#root-layouts) with the registry:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import StyledJsxRegistry from './registry'

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html>
      <body>
        <StyledJsxRegistry>{children}</StyledJsxRegistry>
      </body>
    </html>
  )
}
```

#### [`styled-components`](https://nextjs.org/docs/app/getting-started/css\#styled-components)

To use `styled-components`, enable it in `next.config.js`:

next.config.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  compiler: {
    styledComponents: true,
  },
}

export default nextConfig
```

Then, use the `styled-components` API to create a global registry component to collect all CSS style rules generated during a render, and a function to return those rules. Then use the `useServerInsertedHTML` hook to inject the styles collected in the registry into the `<head>` HTML tag in the root layout.

lib/registry.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import React, { useState } from 'react'
import { useServerInsertedHTML } from 'next/navigation'
import { ServerStyleSheet, StyleSheetManager } from 'styled-components'

export default function StyledComponentsRegistry({
  children,
}: {
  children: React.ReactNode
}) {
  // Only create stylesheet once with lazy initial state
  // x-ref: https://reactjs.org/docs/hooks-reference.html#lazy-initial-state
  const [styledComponentsStyleSheet] = useState(() => new ServerStyleSheet())

  useServerInsertedHTML(() => {
    const styles = styledComponentsStyleSheet.getStyleElement()
    styledComponentsStyleSheet.instance.clearTag()
    return <>{styles}</>
  })

  if (typeof window !== 'undefined') return <>{children}</>

  return (
    <StyleSheetManager sheet={styledComponentsStyleSheet.instance}>
      {children}
    </StyleSheetManager>
  )
}
```

Wrap the `children` of the root layout with the style registry component:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import StyledComponentsRegistry from './lib/registry'

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html>
      <body>
        <StyledComponentsRegistry>{children}</StyledComponentsRegistry>
      </body>
    </html>
  )
}
```

## [External stylesheets](https://nextjs.org/docs/app/getting-started/css\#external-stylesheets)

Stylesheets published by external packages can be imported anywhere in the `app` directory, including colocated components:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import 'bootstrap/dist/css/bootstrap.css'

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body className="container">{children}</body>
    </html>
  )
}
```

External stylesheets must be directly imported from an npm package or downloaded and colocated with your codebase. You cannot use `<link rel="stylesheet" />`.

## API Reference

Learn more about the features mentioned in this page by reading the API Reference.

[**sassOptions** \\
Configure Sass options.](https://nextjs.org/docs/app/api-reference/config/next-config-js/sassOptions) [**Next.js Compiler** \\
Next.js Compiler, written in Rust, which transforms and minifies your Next.js application.](https://nextjs.org/docs/architecture/nextjs-compiler)

Was this helpful?

supported.

Send

## Next.js Error Handling
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Getting Started](https://nextjs.org/docs/app/getting-started) Error Handling

# How to handle errors

Errors can be divided into two categories: [expected errors](https://nextjs.org/docs/app/getting-started/error-handling#handling-expected-errors) and [uncaught exceptions](https://nextjs.org/docs/app/getting-started/error-handling#handling-uncaught-exceptions). This page will walk you through how you can handle these errors in your Next.js application.

## [Handling expected errors](https://nextjs.org/docs/app/getting-started/error-handling\#handling-expected-errors)

Expected errors are those that can occur during the normal operation of the application, such as those from [server-side form validation](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#server-side-form-validation) or failed requests. These errors should be handled explicitly and returned to the client.

### [Server Actions](https://nextjs.org/docs/app/getting-started/error-handling\#server-actions)

You can use the [`useActionState`](https://react.dev/reference/react/useActionState) hook to manage the state of [Server Functions](https://react.dev/reference/rsc/server-functions) and handle expected errors. Avoid using `try`/ `catch` blocks for expected errors. Instead, you can model expected errors as return values, not as thrown exceptions.

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

export async function createPost(prevState: any, formData: FormData) {
  const title = formData.get('title')
  const content = formData.get('content')

  const res = await fetch('https://api.vercel.app/posts', {
    method: 'POST',
    body: { title, content },
  })
  const json = await res.json()

  if (!res.ok) {
    return { message: 'Failed to create post' }
  }
}
```

Then, you can pass your action to the `useActionState` hook and use the returned `state` to display an error message.

app/ui/form.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useActionState } from 'react'
import { createPost } from '@/app/actions'

const initialState = {
  message: '',
}

export function Form() {
  const [state, formAction, pending] = useActionState(createPost, initialState)

  return (
    <form action={formAction}>
      <label htmlFor="title">Title</label>
      <input type="text" id="title" name="title" required />
      <label htmlFor="content">Content</label>
      <textarea id="content" name="content" required />
      {state?.message && <p aria-live="polite">{state.message}</p>}
      <button disabled={pending}>Create Post</button>
    </form>
  )
}
```

### [Server Components](https://nextjs.org/docs/app/getting-started/error-handling\#server-components)

When fetching data inside of a Server Component, you can use the response to conditionally render an error message or [`redirect`](https://nextjs.org/docs/app/api-reference/functions/redirect).

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Page() {
  const res = await fetch(`https://...`)
  const data = await res.json()

  if (!res.ok) {
    return 'There was an error.'
  }

  return '...'
}
```

### [Not found](https://nextjs.org/docs/app/getting-started/error-handling\#not-found)

You can call the [`notFound`](https://nextjs.org/docs/app/api-reference/functions/not-found) function within a route segment and use the [`not-found.js`](https://nextjs.org/docs/app/api-reference/file-conventions/not-found) file to show a 404 UI.

app/blog/\[slug\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { getPostBySlug } from '@/lib/posts'

export default async function Page({ params }: { params: { slug: string } }) {
  const { slug } = await params
  const post = getPostBySlug(slug)

  if (!post) {
    notFound()
  }

  return <div>{post.title}</div>
}
```

app/blog/\[slug\]/not-found.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function NotFound() {
  return <div>404 - Page Not Found</div>
}
```

## [Handling uncaught exceptions](https://nextjs.org/docs/app/getting-started/error-handling\#handling-uncaught-exceptions)

Uncaught exceptions are unexpected errors that indicate bugs or issues that should not occur during the normal flow of your application. These should be handled by throwing errors, which will then be caught by error boundaries.

### [Nested error boundaries](https://nextjs.org/docs/app/getting-started/error-handling\#nested-error-boundaries)

Next.js uses error boundaries to handle uncaught exceptions. Error boundaries catch errors in their child components and display a fallback UI instead of the component tree that crashed.

Create an error boundary by adding an [`error.js`](https://nextjs.org/docs/app/api-reference/file-conventions/error) file inside a route segment and exporting a React component:

app/dashboard/error.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client' // Error boundaries must be Client Components

import { useEffect } from 'react'

export default function Error({
  error,
  reset,
}: {
  error: Error & { digest?: string }
  reset: () => void
}) {
  useEffect(() => {
    // Log the error to an error reporting service
    console.error(error)
  }, [error])

  return (
    <div>
      <h2>Something went wrong!</h2>
      <button
        onClick={
          // Attempt to recover by trying to re-render the segment
          () => reset()
        }
      >
        Try again
      </button>
    </div>
  )
}
```

Errors will bubble up to the nearest parent error boundary. This allows for granular error handling by placing `error.tsx` files at different levels in the [route hierarchy](https://nextjs.org/docs/app/getting-started/project-structure#component-hierarchy).

![Nested Error Component Hierarchy](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fnested-error-component-hierarchy.png&w=3840&q=75)![Nested Error Component Hierarchy](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fnested-error-component-hierarchy.png&w=3840&q=75)

### [Global errors](https://nextjs.org/docs/app/getting-started/error-handling\#global-errors)

While less common, you can handle errors in the root layout using the [`global-error.js`](https://nextjs.org/docs/app/api-reference/file-conventions/error#global-error) file, located in the root app directory, even when leveraging [internationalization](https://nextjs.org/docs/app/building-your-application/routing/internationalization). Global error UI must define its own `<html>` and `<body>` tags, since it is replacing the root layout or template when active.

app/global-error.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client' // Error boundaries must be Client Components

export default function GlobalError({
  error,
  reset,
}: {
  error: Error & { digest?: string }
  reset: () => void
}) {
  return (
    // global-error must include html and body tags
    <html>
      <body>
        <h2>Something went wrong!</h2>
        <button onClick={() => reset()}>Try again</button>
      </body>
    </html>
  )
}
```

## API Reference

Learn more about the features mentioned in this page by reading the API Reference.

[**redirect** \\
API Reference for the redirect function.](https://nextjs.org/docs/app/api-reference/functions/redirect) [**error.js** \\
API reference for the error.js special file.](https://nextjs.org/docs/app/api-reference/file-conventions/error) [**notFound** \\
API Reference for the notFound function.](https://nextjs.org/docs/app/api-reference/functions/not-found) [**not-found.js** \\
API reference for the not-found.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/not-found)

Was this helpful?

supported.

Send

## Parallel Routes Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Parallel Routes

# Parallel Routes

Parallel Routes allows you to simultaneously or conditionally render one or more pages within the same layout. They are useful for highly dynamic sections of an app, such as dashboards and feeds on social sites.

For example, considering a dashboard, you can use parallel routes to simultaneously render the `team` and `analytics` pages:

![Parallel Routes Diagram](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fparallel-routes.png&w=3840&q=75)![Parallel Routes Diagram](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fparallel-routes.png&w=3840&q=75)

## [Slots](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#slots)

Parallel routes are created using named **slots**. Slots are defined with the `@folder` convention. For example, the following file structure defines two slots: `@analytics` and `@team`:

![Parallel Routes File-system Structure](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fparallel-routes-file-system.png&w=3840&q=75)![Parallel Routes File-system Structure](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fparallel-routes-file-system.png&w=3840&q=75)

Slots are passed as props to the shared parent layout. For the example above, the component in `app/layout.js` now accepts the `@analytics` and `@team` slots props, and can render them in parallel alongside the `children` prop:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Layout({
  children,
  team,
  analytics,
}: {
  children: React.ReactNode
  analytics: React.ReactNode
  team: React.ReactNode
}) {
  return (
    <>
      {children}
      {team}
      {analytics}
    </>
  )
}
```

However, slots are **not** route segments and do not affect the URL structure. For example, for `/@analytics/views`, the URL will be `/views` since `@analytics` is a slot. Slots are combined with the regular [Page](https://nextjs.org/docs/app/api-reference/file-conventions/page) component to form the final page associated with the route segment. Because of this, you cannot have separate [static](https://nextjs.org/docs/app/building-your-application/rendering/server-components#static-rendering-default) and [dynamic](https://nextjs.org/docs/app/building-your-application/rendering/server-components#dynamic-rendering) slots at the same route segment level. If one slot is dynamic, all slots at that level must be dynamic.

> **Good to know**:
>
> - The `children` prop is an implicit slot that does not need to be mapped to a folder. This means `app/page.js` is equivalent to `app/@children/page.js`.

## [Active state and navigation](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#active-state-and-navigation)

By default, Next.js keeps track of the active _state_ (or subpage) for each slot. However, the content rendered within a slot will depend on the type of navigation:

- [**Soft Navigation**](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#5-soft-navigation): During client-side navigation, Next.js will perform a [partial render](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#4-partial-rendering), changing the subpage within the slot, while maintaining the other slot's active subpages, even if they don't match the current URL.
- **Hard Navigation**: After a full-page load (browser refresh), Next.js cannot determine the active state for the slots that don't match the current URL. Instead, it will render a [`default.js`](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes#defaultjs) file for the unmatched slots, or `404` if `default.js` doesn't exist.

> **Good to know**:
>
> - The `404` for unmatched routes helps ensure that you don't accidentally render a parallel route on a page that it was not intended for.

### [`default.js`](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#defaultjs)

You can define a `default.js` file to render as a fallback for unmatched slots during the initial load or full-page reload.

Consider the following folder structure. The `@team` slot has a `/settings` page, but `@analytics` does not.

![Parallel Routes unmatched routes](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fparallel-routes-unmatched-routes.png&w=3840&q=75)![Parallel Routes unmatched routes](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fparallel-routes-unmatched-routes.png&w=3840&q=75)

When navigating to `/settings`, the `@team` slot will render the `/settings` page while maintaining the currently active page for the `@analytics` slot.

On refresh, Next.js will render a `default.js` for `@analytics`. If `default.js` doesn't exist, a `404` is rendered instead.

Additionally, since `children` is an implicit slot, you also need to create a `default.js` file to render a fallback for `children` when Next.js cannot recover the active state of the parent page.

### [`useSelectedLayoutSegment(s)`](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#useselectedlayoutsegments)

Both [`useSelectedLayoutSegment`](https://nextjs.org/docs/app/api-reference/functions/use-selected-layout-segment) and [`useSelectedLayoutSegments`](https://nextjs.org/docs/app/api-reference/functions/use-selected-layout-segments) accept a `parallelRoutesKey` parameter, which allows you to read the active route segment within a slot.

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useSelectedLayoutSegment } from 'next/navigation'

export default function Layout({ auth }: { auth: React.ReactNode }) {
  const loginSegment = useSelectedLayoutSegment('auth')
  // ...
}
```

When a user navigates to `app/@auth/login` (or `/login` in the URL bar), `loginSegment` will be equal to the string `"login"`.

## [Examples](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#examples)

### [Conditional Routes](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#conditional-routes)

You can use Parallel Routes to conditionally render routes based on certain conditions, such as user role. For example, to render a different dashboard page for the `/admin` or `/user` roles:

![Conditional routes diagram](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fconditional-routes-ui.png&w=3840&q=75)![Conditional routes diagram](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fconditional-routes-ui.png&w=3840&q=75)

app/dashboard/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { checkUserRole } from '@/lib/auth'

export default function Layout({
  user,
  admin,
}: {
  user: React.ReactNode
  admin: React.ReactNode
}) {
  const role = checkUserRole()
  return role === 'admin' ? admin : user
}
```

### [Tab Groups](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#tab-groups)

You can add a `layout` inside a slot to allow users to navigate the slot independently. This is useful for creating tabs.

For example, the `@analytics` slot has two subpages: `/page-views` and `/visitors`.

![Analytics slot with two subpages and a layout](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fparallel-routes-tab-groups.png&w=3840&q=75)![Analytics slot with two subpages and a layout](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fparallel-routes-tab-groups.png&w=3840&q=75)

Within `@analytics`, create a [`layout`](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates) file to share the tabs between the two pages:

app/@analytics/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Layout({ children }: { children: React.ReactNode }) {
  return (
    <>
      <nav>
        <Link href="/page-views">Page Views</Link>
        <Link href="/visitors">Visitors</Link>
      </nav>
      <div>{children}</div>
    </>
  )
}
```

### [Modals](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#modals)

Parallel Routes can be used together with [Intercepting Routes](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes) to create modals that support deep linking. This allows you to solve common challenges when building modals, such as:

- Making the modal content **shareable through a URL**.
- **Preserving context** when the page is refreshed, instead of closing the modal.
- **Closing the modal on backwards navigation** rather than going to the previous route.
- **Reopening the modal on forwards navigation**.

Consider the following UI pattern, where a user can open a login modal from a layout using client-side navigation, or access a separate `/login` page:

![Parallel Routes Diagram](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fparallel-routes-auth-modal.png&w=3840&q=75)![Parallel Routes Diagram](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fparallel-routes-auth-modal.png&w=3840&q=75)

To implement this pattern, start by creating a `/login` route that renders your **main** login page.

![Parallel Routes Diagram](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fparallel-routes-modal-login-page.png&w=3840&q=75)![Parallel Routes Diagram](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fparallel-routes-modal-login-page.png&w=3840&q=75)

app/login/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Login } from '@/app/ui/login'

export default function Page() {
  return <Login />
}
```

Then, inside the `@auth` slot, add [`default.js`](https://nextjs.org/docs/app/api-reference/file-conventions/default) file that returns `null`. This ensures that the modal is not rendered when it's not active.

app/@auth/default.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Default() {
  return null
}
```

Inside your `@auth` slot, intercept the `/login` route by updating the `/(.)login` folder. Import the `<Modal>` component and its children into the `/(.)login/page.tsx` file:

app/@auth/(.)login/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Modal } from '@/app/ui/modal'
import { Login } from '@/app/ui/login'

export default function Page() {
  return (
    <Modal>
      <Login />
    </Modal>
  )
}
```

> **Good to know:**
>
> - The convention used to intercept the route, e.g. `(.)`, depends on your file-system structure. See [Intercepting Routes convention](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes#convention).
> - By separating the `<Modal>` functionality from the modal content ( `<Login>`), you can ensure any content inside the modal, e.g. [forms](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#forms), are Server Components. See [Interleaving Client and Server Components](https://nextjs.org/docs/app/building-your-application/rendering/composition-patterns#supported-pattern-passing-server-components-to-client-components-as-props) for more information.

#### [Opening the modal](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#opening-the-modal)

Now, you can leverage the Next.js router to open and close the modal. This ensures the URL is correctly updated when the modal is open, and when navigating backwards and forwards.

To open the modal, pass the `@auth` slot as a prop to the parent layout and render it alongside the `children` prop.

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Layout({
  auth,
  children,
}: {
  auth: React.ReactNode
  children: React.ReactNode
}) {
  return (
    <>
      <nav>
        <Link href="/login">Open modal</Link>
      </nav>
      <div>{auth}</div>
      <div>{children}</div>
    </>
  )
}
```

When the user clicks the `<Link>`, the modal will open instead of navigating to the `/login` page. However, on refresh or initial load, navigating to `/login` will take the user to the main login page.

#### [Closing the modal](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#closing-the-modal)

You can close the modal by calling `router.back()` or by using the `Link` component.

app/ui/modal.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useRouter } from 'next/navigation'

export function Modal({ children }: { children: React.ReactNode }) {
  const router = useRouter()

  return (
    <>
      <button
        onClick={() => {
          router.back()
        }}
      >
        Close modal
      </button>
      <div>{children}</div>
    </>
  )
}
```

When using the `Link` component to navigate away from a page that shouldn't render the `@auth` slot anymore, we need to make sure the parallel route matches to a component that returns `null`. For example, when navigating back to the root page, we create a `@auth/page.tsx` component:

app/ui/modal.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export function Modal({ children }: { children: React.ReactNode }) {
  return (
    <>
      <Link href="/">Close modal</Link>
      <div>{children}</div>
    </>
  )
}
```

app/@auth/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Page() {
  return null
}
```

Or if navigating to any other page (such as `/foo`, `/foo/bar`, etc), you can use a catch-all slot:

app/@auth/\[...catchAll\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function CatchAll() {
  return null
}
```

> **Good to know:**
>
> - We use a catch-all route in our `@auth` slot to close the modal because of the behavior described in [Active state and navigation](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes#active-state-and-navigation). Since client-side navigations to a route that no longer match the slot will remain visible, we need to match the slot to a route that returns `null` to close the modal.
> - Other examples could include opening a photo modal in a gallery while also having a dedicated `/photo/[id]` page, or opening a shopping cart in a side modal.
> - [View an example](https://github.com/vercel-labs/nextgram) of modals with Intercepted and Parallel Routes.

### [Loading and Error UI](https://nextjs.org/docs/app/building-your-application/routing/parallel-routes\#loading-and-error-ui)

Parallel Routes can be streamed independently, allowing you to define independent error and loading states for each route:

![Parallel routes enable custom error and loading states](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fparallel-routes-cinematic-universe.png&w=3840&q=75)![Parallel routes enable custom error and loading states](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fparallel-routes-cinematic-universe.png&w=3840&q=75)

See the [Loading UI](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming) and [Error Handling](https://nextjs.org/docs/app/building-your-application/routing/error-handling) documentation for more information.

## Next Steps

[**default.js** \\
API Reference for the default.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/default)

Was this helpful?

supported.

Send

## Updating Data in Next.js
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Getting Started](https://nextjs.org/docs/app/getting-started) Updating Data

# How to update data

You can update data in Next.js using React's [Server Functions](https://react.dev/reference/rsc/server-functions). This page will go through how you can [create](https://nextjs.org/docs/app/getting-started/updating-data#creating-server-functions) and [invoke](https://nextjs.org/docs/app/getting-started/updating-data#invoking-server-functions) Server Functions.

## [Creating Server Functions](https://nextjs.org/docs/app/getting-started/updating-data\#creating-server-functions)

A Server Function can be defined by using the [`use server`](https://react.dev/reference/rsc/use-server) directive. You can place the directive at the top of an **asynchronous** function to mark the function as a Server Function, or at the top of a separate file to mark all exports of that file. We recommend using a separate file in most instances.

app/lib/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

export async function createPost(formData: FormData) {}

export async function deletePost(formData: FormData) {}
```

### [Server Components](https://nextjs.org/docs/app/getting-started/updating-data\#server-components)

Server Functions can be inlined in Server Components by adding the `"use server"` directive to the top of the function body:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Page() {
  // Server Action
  async function createPost() {
    'use server'
    // Update data
    // ...
  }

  return <></>
}
```

### [Client Components](https://nextjs.org/docs/app/getting-started/updating-data\#client-components)

It's not possible to define Server Functions in Client Components. However, you can invoke them in Client Components by importing them from a file that has the `"use server"` directive at the top of it:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

export async function createPost() {}
```

app/ui/button.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { createPost } from '@/app/actions'

export function Button() {
  return <button formAction={createPost}>Create</button>
}
```

## [Invoking Server Functions](https://nextjs.org/docs/app/getting-started/updating-data\#invoking-server-functions)

There are two main ways you can invoke a Server Function:

1. [Forms](https://nextjs.org/docs/app/getting-started/updating-data#forms) in Server and Client Components
2. [Event Handlers](https://nextjs.org/docs/app/getting-started/updating-data#event-handlers) in Client Components

### [Forms](https://nextjs.org/docs/app/getting-started/updating-data\#forms)

React extends the HTML [`<form>`](https://react.dev/reference/react-dom/components/form) element to allow Server Function to be invoked with the HTML `action` prop.

When invoked in a form, the function automatically receives the [`FormData`](https://developer.mozilla.org/docs/Web/API/FormData/FormData) object. You can extract the data using the native [`FormData` methods](https://developer.mozilla.org/en-US/docs/Web/API/FormData#instance_methods):

app/ui/form.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { createPost } from '@/app/actions'

export function Form() {
  return (
    <form action={createPost}>
      <input type="text" name="title" />
      <input type="text" name="content" />
      <button type="submit">Create</button>
    </form>
  )
}
```

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

export async function createPost(formData: FormData) {
  const title = formData.get('title')
  const content = formData.get('content')

  // Update data
  // Revalidate cache
}
```

> **Good to know:** When passed to the `action` prop, Server Functions are also known as _Server Actions_.

### [Event Handlers](https://nextjs.org/docs/app/getting-started/updating-data\#event-handlers)

You can invoke a Server Function in a Client Component by using event handlers such as `onClick`.

app/like-button.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { incrementLike } from './actions'
import { useState } from 'react'

export default function LikeButton({ initialLikes }: { initialLikes: number }) {
  const [likes, setLikes] = useState(initialLikes)

  return (
    <>
      <p>Total Likes: {likes}</p>
      <button
        onClick={async () => {
          const updatedLikes = await incrementLike()
          setLikes(updatedLikes)
        }}
      >
        Like
      </button>
    </>
  )
}
```

### [Showing a pending state](https://nextjs.org/docs/app/getting-started/updating-data\#showing-a-pending-state)

While executing a Server Function, you can show a loading indicator with React's [`useActionState`](https://react.dev/reference/react/useActionState) hook. This hook returns a `pending` boolean:

app/ui/button.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useActionState } from 'react'
import { createPost } from '@/app/actions'
import { LoadingSpinner } from '@/app/ui/loading-spinner'

export function Button() {
  const [state, action, pending] = useActionState(createPost, false)

  return (
    <button onClick={async () => action()}>
      {pending ? <LoadingSpinner /> : 'Create Post'}
    </button>
  )
}
```

### [Revalidating the cache](https://nextjs.org/docs/app/getting-started/updating-data\#revalidating-the-cache)

After performing an update, you can revalidate the Next.js cache and show the updated data by calling [`revalidatePath`](https://nextjs.org/docs/app/api-reference/functions/revalidatePath) or [`revalidateTag`](https://nextjs.org/docs/app/api-reference/functions/revalidateTag) within the Server Function:

app/lib/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { revalidatePath } from 'next/cache'

export async function createPost(formData: FormData) {
  // Update data
  // ...

  revalidatePath('/posts')
}
```

### [Redirecting](https://nextjs.org/docs/app/getting-started/updating-data\#redirecting)

You may want to redirect the user to a different page after performing an update. You can do this by calling [`redirect`](https://nextjs.org/docs/app/api-reference/functions/redirect) within the Server Function:

app/lib/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { redirect } from 'next/navigation'

export async function createPost(formData: FormData) {
  // Update data
  // ...

  redirect('/posts')
}
```

## API Reference

Learn more about the features mentioned in this page by reading the API Reference.

[**revalidatePath** \\
API Reference for the revalidatePath function.](https://nextjs.org/docs/app/api-reference/functions/revalidatePath) [**revalidateTag** \\
API Reference for the revalidateTag function.](https://nextjs.org/docs/app/api-reference/functions/revalidateTag) [**redirect** \\
API Reference for the redirect function.](https://nextjs.org/docs/app/api-reference/functions/redirect)

Was this helpful?

supported.

Send

## Next.js Static Exports
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Deploying](https://nextjs.org/docs/app/building-your-application/deploying) Static Exports

# Static Exports

Next.js enables starting as a static site or Single-Page Application (SPA), then later optionally upgrading to use features that require a server.

When running `next build`, Next.js generates an HTML file per route. By breaking a strict SPA into individual HTML files, Next.js can avoid loading unnecessary JavaScript code on the client-side, reducing the bundle size and enabling faster page loads.

Since Next.js supports this static export, it can be deployed and hosted on any web server that can serve HTML/CSS/JS static assets.

## [Configuration](https://nextjs.org/docs/app/building-your-application/deploying/static-exports\#configuration)

To enable a static export, change the output mode inside `next.config.js`:

next.config.js

```code-block_code__isn_V
/**
 * @type {import('next').NextConfig}
 */
const nextConfig = {
  output: 'export',

  // Optional: Change links `/me` -> `/me/` and emit `/me.html` -> `/me/index.html`
  // trailingSlash: true,

  // Optional: Prevent automatic `/me` -> `/me/`, instead preserve `href`
  // skipTrailingSlashRedirect: true,

  // Optional: Change the output directory `out` -> `dist`
  // distDir: 'dist',
}

module.exports = nextConfig
```

After running `next build`, Next.js will create an `out` folder with the HTML/CSS/JS assets for your application.

## [Supported Features](https://nextjs.org/docs/app/building-your-application/deploying/static-exports\#supported-features)

The core of Next.js has been designed to support static exports.

### [Server Components](https://nextjs.org/docs/app/building-your-application/deploying/static-exports\#server-components)

When you run `next build` to generate a static export, Server Components consumed inside the `app` directory will run during the build, similar to traditional static-site generation.

The resulting component will be rendered into static HTML for the initial page load and a static payload for client navigation between routes. No changes are required for your Server Components when using the static export, unless they consume [dynamic server functions](https://nextjs.org/docs/app/building-your-application/deploying/static-exports#unsupported-features).

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Page() {
  // This fetch will run on the server during `next build`
  const res = await fetch('https://api.example.com/...')
  const data = await res.json()

  return <main>...</main>
}
```

### [Client Components](https://nextjs.org/docs/app/building-your-application/deploying/static-exports\#client-components)

If you want to perform data fetching on the client, you can use a Client Component with [SWR](https://github.com/vercel/swr) to memoize requests.

app/other/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import useSWR from 'swr'

const fetcher = (url: string) => fetch(url).then((r) => r.json())

export default function Page() {
  const { data, error } = useSWR(
    `https://jsonplaceholder.typicode.com/posts/1`,
    fetcher
  )
  if (error) return 'Failed to load'
  if (!data) return 'Loading...'

  return data.title
}
```

Since route transitions happen client-side, this behaves like a traditional SPA. For example, the following index route allows you to navigate to different posts on the client:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return (
    <>
      <h1>Index Page</h1>
      <hr />
      <ul>
        <li>
          <Link href="/post/1">Post 1</Link>
        </li>
        <li>
          <Link href="/post/2">Post 2</Link>
        </li>
      </ul>
    </>
  )
}
```

### [Image Optimization](https://nextjs.org/docs/app/building-your-application/deploying/static-exports\#image-optimization)

[Image Optimization](https://nextjs.org/docs/app/building-your-application/optimizing/images) through `next/image` can be used with a static export by defining a custom image loader in `next.config.js`. For example, you can optimize images with a service like Cloudinary:

next.config.js

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
const nextConfig = {
  output: 'export',
  images: {
    loader: 'custom',
    loaderFile: './my-loader.ts',
  },
}

module.exports = nextConfig
```

This custom loader will define how to fetch images from a remote source. For example, the following loader will construct the URL for Cloudinary:

my-loader.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function cloudinaryLoader({
  src,
  width,
  quality,
}: {
  src: string
  width: number
  quality?: number
}) {
  const params = ['f_auto', 'c_limit', `w_${width}`, `q_${quality || 'auto'}`]
  return `https://res.cloudinary.com/demo/image/upload/${params.join(
    ','
  )}${src}`
}
```

You can then use `next/image` in your application, defining relative paths to the image in Cloudinary:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Image from 'next/image'

export default function Page() {
  return <Image alt="turtles" src="/turtles.jpg" width={300} height={300} />
}
```

### [Route Handlers](https://nextjs.org/docs/app/building-your-application/deploying/static-exports\#route-handlers)

Route Handlers will render a static response when running `next build`. Only the `GET` HTTP verb is supported. This can be used to generate static HTML, JSON, TXT, or other files from cached or uncached data. For example:

app/data.json/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function GET() {
  return Response.json({ name: 'Lee' })
}
```

The above file `app/data.json/route.ts` will render to a static file during `next build`, producing `data.json` containing `{ name: 'Lee' }`.

If you need to read dynamic values from the incoming request, you cannot use a static export.

### [Browser APIs](https://nextjs.org/docs/app/building-your-application/deploying/static-exports\#browser-apis)

Client Components are pre-rendered to HTML during `next build`. Because [Web APIs](https://developer.mozilla.org/docs/Web/API) like `window`, `localStorage`, and `navigator` are not available on the server, you need to safely access these APIs only when running in the browser. For example:

```code-block_code__isn_V
'use client';

import { useEffect } from 'react';

export default function ClientComponent() {
  useEffect(() => {
    // You now have access to `window`
    console.log(window.innerHeight);
  }, [])

  return ...;
}
```

## [Unsupported Features](https://nextjs.org/docs/app/building-your-application/deploying/static-exports\#unsupported-features)

Features that require a Node.js server, or dynamic logic that cannot be computed during the build process, are **not** supported:

- [Dynamic Routes](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes) with `dynamicParams: true`
- [Dynamic Routes](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes) without `generateStaticParams()`
- [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) that rely on Request
- [Cookies](https://nextjs.org/docs/app/api-reference/functions/cookies)
- [Rewrites](https://nextjs.org/docs/app/api-reference/config/next-config-js/rewrites)
- [Redirects](https://nextjs.org/docs/app/api-reference/config/next-config-js/redirects)
- [Headers](https://nextjs.org/docs/app/api-reference/config/next-config-js/headers)
- [Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware)
- [Incremental Static Regeneration](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration)
- [Image Optimization](https://nextjs.org/docs/app/building-your-application/optimizing/images) with the default `loader`
- [Draft Mode](https://nextjs.org/docs/app/building-your-application/configuring/draft-mode)
- [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations)
- [Intercepting Routes](https://nextjs.org/docs/app/building-your-application/routing/intercepting-routes)

Attempting to use any of these features with `next dev` will result in an error, similar to setting the [`dynamic`](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config#dynamic) option to `error` in the root layout.

```code-block_code__isn_V
export const dynamic = 'error'
```

## [Deploying](https://nextjs.org/docs/app/building-your-application/deploying/static-exports\#deploying)

With a static export, Next.js can be deployed and hosted on any web server that can serve HTML/CSS/JS static assets.

When running `next build`, Next.js generates the static export into the `out` folder. For example, let's say you have the following routes:

- `/`
- `/blog/[id]`

After running `next build`, Next.js will generate the following files:

- `/out/index.html`
- `/out/404.html`
- `/out/blog/post-1.html`
- `/out/blog/post-2.html`

If you are using a static host like Nginx, you can configure rewrites from incoming requests to the correct files:

nginx.conf

```code-block_code__isn_V
server {
  listen 80;
  server_name acme.com;

  root /var/www/out;

  location / {
      try_files $uri $uri.html $uri/ =404;
  }

  # This is necessary when `trailingSlash: false`.
  # You can omit this when `trailingSlash: true`.
  location /blog/ {
      rewrite ^/blog/(.*)$ /blog/$1.html break;
  }

  error_page 404 /404.html;
  location = /404.html {
      internal;
  }
}
```

## [Version History](https://nextjs.org/docs/app/building-your-application/deploying/static-exports\#version-history)

| Version | Changes |
| --- | --- |
| `v14.0.0` | `next export` has been removed in favor of `"output": "export"` |
| `v13.4.0` | App Router (Stable) adds enhanced static export support, including using React Server Components and Route Handlers. |
| `v13.3.0` | `next export` is deprecated and replaced with `"output": "export"` |

Was this helpful?

supported.

Send

## Next.js App Examples
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Introduction](https://nextjs.org/docs) [App Router](https://nextjs.org/docs/app) Examples

# Examples

### [Data Fetching](https://nextjs.org/docs/app/examples\#data-fetching)

- [Using the `fetch` API](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching#fetching-data-on-the-server-with-the-fetch-api)
- [Using an ORM or database client](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching#fetching-data-on-the-server-with-an-orm-or-database)
- [Reading search params on the server](https://nextjs.org/docs/app/api-reference/file-conventions/page)
- [Reading search params on the client](https://nextjs.org/docs/app/api-reference/functions/use-search-params)

### [Revalidating Data](https://nextjs.org/docs/app/examples\#revalidating-data)

- [Using ISR to revalidate data after a certain time](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration#time-based-revalidation)
- [Using ISR to revalidate data on-demand](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration#on-demand-revalidation-with-revalidatepath)

### [Forms](https://nextjs.org/docs/app/examples\#forms)

- [Showing a pending state while submitting a form](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#pending-states)
- [Server-side form validation](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#server-side-form-validation)
- [Handling expected errors](https://nextjs.org/docs/app/building-your-application/routing/error-handling#handling-expected-errors-from-server-actions)
- [Handling unexpected exceptions](https://nextjs.org/docs/app/building-your-application/routing/error-handling#uncaught-exceptions)
- [Showing optimistic UI updates](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#optimistic-updates)
- [Programmatic form submission](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#programmatic-form-submission)

### [Server Actions](https://nextjs.org/docs/app/examples\#server-actions)

- [Passing additional values](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#passing-additional-arguments)
- [Revalidating data](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#revalidating-data)
- [Redirecting](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#redirecting)
- [Setting cookies](https://nextjs.org/docs/app/api-reference/functions/cookies#setting-a-cookie)
- [Deleting cookies](https://nextjs.org/docs/app/api-reference/functions/cookies#deleting-cookies)

### [Metadata](https://nextjs.org/docs/app/examples\#metadata)

- [Creating an RSS feed](https://nextjs.org/docs/app/building-your-application/routing/route-handlers#non-ui-responses)
- [Creating an Open Graph image](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/opengraph-image)
- [Creating a sitemap](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/sitemap)
- [Creating a robots.txt file](https://nextjs.org/docs/app/api-reference/file-conventions/metadata/robots)
- [Creating a custom 404 page](https://nextjs.org/docs/app/api-reference/file-conventions/not-found)
- [Creating a custom 500 page](https://nextjs.org/docs/app/api-reference/file-conventions/error)

### [Auth](https://nextjs.org/docs/app/examples\#auth)

- [Creating a sign-up form](https://nextjs.org/docs/app/building-your-application/authentication#sign-up-and-login-functionality)
- [Stateless, cookie-based session management](https://nextjs.org/docs/app/building-your-application/authentication#stateless-sessions)
- [Stateful, database-backed session management](https://nextjs.org/docs/app/building-your-application/authentication#database-sessions)
- [Managing authorization](https://nextjs.org/docs/app/building-your-application/authentication#authorization)

### [Testing](https://nextjs.org/docs/app/examples\#testing)

- [Vitest](https://nextjs.org/docs/app/building-your-application/testing/vitest)
- [Jest](https://nextjs.org/docs/app/building-your-application/testing/jest)
- [Playwright](https://nextjs.org/docs/app/building-your-application/testing/playwright)
- [Cypress](https://nextjs.org/docs/app/building-your-application/testing/cypress)

### [Deployment](https://nextjs.org/docs/app/examples\#deployment)

- [Creating a Dockerfile](https://nextjs.org/docs/app/building-your-application/deploying#docker-image)
- [Creating a static export (SPA)](https://nextjs.org/docs/app/building-your-application/deploying/static-exports)
- [Configuring caching when self-hosting](https://nextjs.org/docs/app/building-your-application/deploying#configuring-caching)
- [Configuring Image Optimization when self-hosting](https://nextjs.org/docs/app/building-your-application/deploying#image-optimization)

Was this helpful?

supported.

Send

## Vitest Setup for Next.js
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Testing](https://nextjs.org/docs/app/building-your-application/testing) Vitest

# Setting up Vitest with Next.js

Vite and React Testing Library are frequently used together for **Unit Testing**. This guide will show you how to setup Vitest with Next.js and write your first tests.

> **Good to know:** Since `async` Server Components are new to the React ecosystem, Vitest currently does not support them. While you can still run **unit tests** for synchronous Server and Client Components, we recommend using an **E2E tests** for `async` components.

## [Quickstart](https://nextjs.org/docs/app/building-your-application/testing/vitest\#quickstart)

You can use `create-next-app` with the Next.js [with-vitest](https://github.com/vercel/next.js/tree/canary/examples/with-vitest) example to quickly get started:

Terminal

```code-block_code__isn_V
npx create-next-app@latest --example with-vitest with-vitest-app
```

## [Manual Setup](https://nextjs.org/docs/app/building-your-application/testing/vitest\#manual-setup)

To manually set up Vitest, install `vitest` and the following packages as dev dependencies:

Terminal

```code-block_code__isn_V
# Using TypeScript
npm install -D vitest @vitejs/plugin-react jsdom @testing-library/react @testing-library/dom vite-tsconfig-paths
# Using JavaScript
npm install -D vitest @vitejs/plugin-react jsdom @testing-library/react @testing-library/dom
```

Create a `vitest.config.mts|js` file in the root of your project, and add the following options:

vitest.config.mts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { defineConfig } from 'vitest/config'
import react from '@vitejs/plugin-react'
import tsconfigPaths from 'vite-tsconfig-paths'

export default defineConfig({
  plugins: [tsconfigPaths(), react()],
  test: {
    environment: 'jsdom',
  },
})
```

For more information on configuring Vitest, please refer to the [Vitest Configuration](https://vitest.dev/config/#configuration) docs.

Then, add a `test` script to your `package.json`:

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "test": "vitest"
  }
}
```

When you run `npm run test`, Vitest will **watch** for changes in your project by default.

## [Creating your first Vitest Unit Test](https://nextjs.org/docs/app/building-your-application/testing/vitest\#creating-your-first-vitest-unit-test)

Check that everything is working by creating a test to check if the `<Page />` component successfully renders a heading:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return (
    <div>
      <h1>Home</h1>
      <Link href="/about">About</Link>
    </div>
  )
}
```

\_\_tests\_\_/page.test.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { expect, test } from 'vitest'
import { render, screen } from '@testing-library/react'
import Page from '../app/page'

test('Page', () => {
  render(<Page />)
  expect(screen.getByRole('heading', { level: 1, name: 'Home' })).toBeDefined()
})
```

> **Good to know**: The example above uses the common `__tests__` convention, but test files can also be colocated inside the `app` router.

## [Running your tests](https://nextjs.org/docs/app/building-your-application/testing/vitest\#running-your-tests)

Then, run the following command to run your tests:

Terminal

```code-block_code__isn_V
npm run test
# or
yarn test
# or
pnpm test
# or
bun test
```

## [Additional Resources](https://nextjs.org/docs/app/building-your-application/testing/vitest\#additional-resources)

You may find these resources helpful:

- [Next.js with Vitest example](https://github.com/vercel/next.js/tree/canary/examples/with-vitest)
- [Vitest Docs](https://vitest.dev/guide/)
- [React Testing Library Docs](https://testing-library.com/docs/react-testing-library/intro/)

Was this helpful?

supported.

Send

## Next.js Application Optimizations
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Building Your Application](https://nextjs.org/docs/app/building-your-application) Optimizing

# Optimizations

Next.js comes with a variety of built-in optimizations designed to improve your application's speed and [Core Web Vitals](https://web.dev/vitals/). This guide will cover the optimizations you can leverage to enhance your user experience.

## [Built-in Components](https://nextjs.org/docs/app/building-your-application/optimizing\#built-in-components)

Built-in components abstract away the complexity of implementing common UI optimizations. These components are:

- **Images**: Built on the native `<img>` element. The Image Component optimizes images for performance by lazy loading and automatically resizing images based on device size.
- **Link**: Built on the native `<a>` tags. The Link Component prefetches pages in the background, for faster and smoother page transitions.
- **Scripts**: Built on the native `<script>` tags. The Script Component gives you control over loading and execution of third-party scripts.

## [Metadata](https://nextjs.org/docs/app/building-your-application/optimizing\#metadata)

Metadata helps search engines understand your content better (which can result in better SEO), and allows you to customize how your content is presented on social media, helping you create a more engaging and consistent user experience across various platforms.

The Metadata API in Next.js allows you to modify the `<head>` element of a page. You can configure metadata in two ways:

- **Config-based Metadata**: Export a [static `metadata` object](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#metadata-object) or a dynamic [`generateMetadata` function](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#generatemetadata-function) in a `layout.js` or `page.js` file.
- **File-based Metadata**: Add static or dynamically generated special files to route segments.

Additionally, you can create dynamic Open Graph Images using JSX and CSS with [imageResponse](https://nextjs.org/docs/app/api-reference/functions/image-response) constructor.

## [Static Assets](https://nextjs.org/docs/app/building-your-application/optimizing\#static-assets)

Next.js `/public` folder can be used to serve static assets like images, fonts, and other files. Files inside `/public` can also be cached by CDN providers so that they are delivered efficiently.

## [Analytics and Monitoring](https://nextjs.org/docs/app/building-your-application/optimizing\#analytics-and-monitoring)

For large applications, Next.js integrates with popular analytics and monitoring tools to help you understand how your application is performing. Learn more in the [OpenTelemetry](https://nextjs.org/docs/pages/building-your-application/optimizing/open-telemetry) and [Instrumentation](https://nextjs.org/docs/pages/building-your-application/optimizing/instrumentation) guides.

[**Images** \\
Optimize your images with the built-in \`next/image\` component.](https://nextjs.org/docs/app/building-your-application/optimizing/images) [**Videos** \\
Recommendations and best practices for optimizing videos in your Next.js application.](https://nextjs.org/docs/app/building-your-application/optimizing/videos) [**Fonts** \\
Optimize your application's web fonts with the built-in \`next/font\` loaders.](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) [**Metadata** \\
Use the Metadata API to define metadata in any layout or page.](https://nextjs.org/docs/app/building-your-application/optimizing/metadata) [**Scripts** \\
Optimize 3rd party scripts with the built-in Script component.](https://nextjs.org/docs/app/building-your-application/optimizing/scripts) [**Package Bundling** \\
Learn how to optimize your application's server and client bundles.](https://nextjs.org/docs/app/building-your-application/optimizing/package-bundling) [**Lazy Loading** \\
Lazy load imported libraries and React Components to improve your application's loading performance.](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading) [**Analytics** \\
Measure and track page performance using Next.js Speed Insights](https://nextjs.org/docs/app/building-your-application/optimizing/analytics) [**Instrumentation** \\
Learn how to use instrumentation to run code at server startup in your Next.js app](https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation) [**OpenTelemetry** \\
Learn how to instrument your Next.js app with OpenTelemetry.](https://nextjs.org/docs/app/building-your-application/optimizing/open-telemetry) [**Static Assets** \\
Next.js allows you to serve static files, like images, in the public directory. You can learn how it works here.](https://nextjs.org/docs/app/building-your-application/optimizing/static-assets) [**Third Party Libraries** \\
Optimize the performance of third-party libraries in your application with the \`@next/third-parties\` package.](https://nextjs.org/docs/app/building-your-application/optimizing/third-party-libraries) [**Memory Usage** \\
Optimize memory used by your application in development and production.](https://nextjs.org/docs/app/building-your-application/optimizing/memory-usage) [**Local Development** \\
Learn how to optimize your local development environment with Next.js.](https://nextjs.org/docs/app/building-your-application/optimizing/local-development)

Was this helpful?

supported.

Send

## Next.js Script Optimization
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) Scripts

# Script Optimization

### [Layout Scripts](https://nextjs.org/docs/app/building-your-application/optimizing/scripts\#layout-scripts)

To load a third-party script for multiple routes, import `next/script` and include the script directly in your layout component:

app/dashboard/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Script from 'next/script'

export default function DashboardLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <>
      <section>{children}</section>
      <Script src="https://example.com/script.js" />
    </>
  )
}
```

The third-party script is fetched when the folder route (e.g. `dashboard/page.js`) or any nested route (e.g. `dashboard/settings/page.js`) is accessed by the user. Next.js will ensure the script will **only load once**, even if a user navigates between multiple routes in the same layout.

### [Application Scripts](https://nextjs.org/docs/app/building-your-application/optimizing/scripts\#application-scripts)

To load a third-party script for all routes, import `next/script` and include the script directly in your root layout:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Script from 'next/script'

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body>{children}</body>
      <Script src="https://example.com/script.js" />
    </html>
  )
}
```

This script will load and execute when _any_ route in your application is accessed. Next.js will ensure the script will **only load once**, even if a user navigates between multiple pages.

> **Recommendation**: We recommend only including third-party scripts in specific pages or layouts in order to minimize any unnecessary impact to performance.

### [Strategy](https://nextjs.org/docs/app/building-your-application/optimizing/scripts\#strategy)

Although the default behavior of `next/script` allows you to load third-party scripts in any page or layout, you can fine-tune its loading behavior by using the `strategy` property:

- `beforeInteractive`: Load the script before any Next.js code and before any page hydration occurs.
- `afterInteractive`: ( **default**) Load the script early but after some hydration on the page occurs.
- `lazyOnload`: Load the script later during browser idle time.
- `worker`: (experimental) Load the script in a web worker.

Refer to the [`next/script`](https://nextjs.org/docs/app/api-reference/components/script#strategy) API reference documentation to learn more about each strategy and their use cases.

### [Offloading Scripts To A Web Worker (experimental)](https://nextjs.org/docs/app/building-your-application/optimizing/scripts\#offloading-scripts-to-a-web-worker-experimental)

> **Warning:** The `worker` strategy is not yet stable and does not yet work with the App Router. Use with caution.

Scripts that use the `worker` strategy are offloaded and executed in a web worker with [Partytown](https://partytown.builder.io/). This can improve the performance of your site by dedicating the main thread to the rest of your application code.

This strategy is still experimental and can only be used if the `nextScriptWorkers` flag is enabled in `next.config.js`:

next.config.js

```code-block_code__isn_V
module.exports = {
  experimental: {
    nextScriptWorkers: true,
  },
}
```

Then, run `next` (normally `npm run dev` or `yarn dev`) and Next.js will guide you through the installation of the required packages to finish the setup:

Terminal

```code-block_code__isn_V
npm run dev
```

You'll see instructions like these: Please install Partytown by running `npm install @builder.io/partytown`

Once setup is complete, defining `strategy="worker"` will automatically instantiate Partytown in your application and offload the script to a web worker.

pages/home.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Script from 'next/script'

export default function Home() {
  return (
    <>
      <Script src="https://example.com/script.js" strategy="worker" />
    </>
  )
}
```

There are a number of trade-offs that need to be considered when loading a third-party script in a web worker. Please see Partytown's [tradeoffs](https://partytown.builder.io/trade-offs) documentation for more information.

### [Inline Scripts](https://nextjs.org/docs/app/building-your-application/optimizing/scripts\#inline-scripts)

Inline scripts, or scripts not loaded from an external file, are also supported by the Script component. They can be written by placing the JavaScript within curly braces:

```code-block_code__isn_V
<Script id="show-banner">
  {`document.getElementById('banner').classList.remove('hidden')`}
</Script>
```

Or by using the `dangerouslySetInnerHTML` property:

```code-block_code__isn_V
<Script
  id="show-banner"
  dangerouslySetInnerHTML={{
    __html: `document.getElementById('banner').classList.remove('hidden')`,
  }}
/>
```

> **Warning**: An `id` property must be assigned for inline scripts in order for Next.js to track and optimize the script.

### [Executing Additional Code](https://nextjs.org/docs/app/building-your-application/optimizing/scripts\#executing-additional-code)

Event handlers can be used with the Script component to execute additional code after a certain event occurs:

- `onLoad`: Execute code after the script has finished loading.
- `onReady`: Execute code after the script has finished loading and every time the component is mounted.
- `onError`: Execute code if the script fails to load.

These handlers will only work when `next/script` is imported and used inside of a [Client Component](https://nextjs.org/docs/app/building-your-application/rendering/client-components) where `"use client"` is defined as the first line of code:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import Script from 'next/script'

export default function Page() {
  return (
    <>
      <Script
        src="https://example.com/script.js"
        onLoad={() => {
          console.log('Script has loaded')
        }}
      />
    </>
  )
}
```

Refer to the [`next/script`](https://nextjs.org/docs/app/api-reference/components/script#onload) API reference to learn more about each event handler and view examples.

### [Additional Attributes](https://nextjs.org/docs/app/building-your-application/optimizing/scripts\#additional-attributes)

There are many DOM attributes that can be assigned to a `<script>` element that are not used by the Script component, like [`nonce`](https://developer.mozilla.org/docs/Web/HTML/Global_attributes/nonce) or [custom data attributes](https://developer.mozilla.org/docs/Web/HTML/Global_attributes/data-*). Including any additional attributes will automatically forward it to the final, optimized `<script>` element that is included in the HTML.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Script from 'next/script'

export default function Page() {
  return (
    <>
      <Script
        src="https://example.com/script.js"
        id="example-script"
        nonce="XUENAJFW"
        data-test="script"
      />
    </>
  )
}
```

## API Reference

Learn more about the next/script API.

[**Script** \\
Optimize third-party scripts in your Next.js application using the built-in \`next/script\` Component.](https://nextjs.org/docs/app/api-reference/components/script)

Was this helpful?

supported.

Send

## Next.js Lazy Loading
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) Lazy Loading

# Lazy Loading

[Lazy loading](https://developer.mozilla.org/docs/Web/Performance/Lazy_loading) in Next.js helps improve the initial loading performance of an application by decreasing the amount of JavaScript needed to render a route.

It allows you to defer loading of **Client Components** and imported libraries, and only include them in the client bundle when they're needed. For example, you might want to defer loading a modal until a user clicks to open it.

There are two ways you can implement lazy loading in Next.js:

1. Using [Dynamic Imports](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading#nextdynamic) with `next/dynamic`
2. Using [`React.lazy()`](https://react.dev/reference/react/lazy) with [Suspense](https://react.dev/reference/react/Suspense)

By default, Server Components are automatically [code split](https://developer.mozilla.org/docs/Glossary/Code_splitting), and you can use [streaming](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming) to progressively send pieces of UI from the server to the client. Lazy loading applies to Client Components.

## [`next/dynamic`](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading\#nextdynamic)

`next/dynamic` is a composite of [`React.lazy()`](https://react.dev/reference/react/lazy) and [Suspense](https://react.dev/reference/react/Suspense). It behaves the same way in the `app` and `pages` directories to allow for incremental migration.

## [Examples](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading\#examples)

### [Importing Client Components](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading\#importing-client-components)

app/page.js

```code-block_code__isn_V
'use client'

import { useState } from 'react'
import dynamic from 'next/dynamic'

// Client Components:
const ComponentA = dynamic(() => import('../components/A'))
const ComponentB = dynamic(() => import('../components/B'))
const ComponentC = dynamic(() => import('../components/C'), { ssr: false })

export default function ClientComponentExample() {
  const [showMore, setShowMore] = useState(false)

  return (
    <div>
      {/* Load immediately, but in a separate client bundle */}
      <ComponentA />

      {/* Load on demand, only when/if the condition is met */}
      {showMore && <ComponentB />}
      <button onClick={() => setShowMore(!showMore)}>Toggle</button>

      {/* Load only on the client side */}
      <ComponentC />
    </div>
  )
}
```

> **Note:** When a Server Component dynamically imports a Client Component, automatic [code splitting](https://developer.mozilla.org/docs/Glossary/Code_splitting) is currently **not** supported.

### [Skipping SSR](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading\#skipping-ssr)

When using `React.lazy()` and Suspense, Client Components will be [prerendered](https://github.com/reactwg/server-components/discussions/4) (SSR) by default.

> **Note:** `ssr: false` option will only work for client components, move it into client components ensure the client code-splitting working properly.

If you want to disable pre-rendering for a Client Component, you can use the `ssr` option set to `false`:

```code-block_code__isn_V
const ComponentC = dynamic(() => import('../components/C'), { ssr: false })
```

### [Importing Server Components](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading\#importing-server-components)

If you dynamically import a Server Component, only the Client Components that are children of the Server Component will be lazy-loaded - not the Server Component itself.
It will also help preload the static assets such as CSS when you're using it in Server Components.

app/page.js

```code-block_code__isn_V
import dynamic from 'next/dynamic'

// Server Component:
const ServerComponent = dynamic(() => import('../components/ServerComponent'))

export default function ServerComponentExample() {
  return (
    <div>
      <ServerComponent />
    </div>
  )
}
```

> **Note:** `ssr: false` option is not supported in Server Components. You will see an error if you try to use it in Server Components.
> `ssr: false` is not allowed with `next/dynamic` in Server Components. Please move it into a client component.

### [Loading External Libraries](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading\#loading-external-libraries)

External libraries can be loaded on demand using the [`import()`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Operators/import) function. This example uses the external library `fuse.js` for fuzzy search. The module is only loaded on the client after the user types in the search input.

app/page.js

```code-block_code__isn_V
'use client'

import { useState } from 'react'

const names = ['Tim', 'Joe', 'Bel', 'Lee']

export default function Page() {
  const [results, setResults] = useState()

  return (
    <div>
      <input
        type="text"
        placeholder="Search"
        onChange={async (e) => {
          const { value } = e.currentTarget
          // Dynamically load fuse.js
          const Fuse = (await import('fuse.js')).default
          const fuse = new Fuse(names)

          setResults(fuse.search(value))
        }}
      />
      <pre>Results: {JSON.stringify(results, null, 2)}</pre>
    </div>
  )
}
```

### [Adding a custom loading component](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading\#adding-a-custom-loading-component)

app/page.js

```code-block_code__isn_V
'use client'

import dynamic from 'next/dynamic'

const WithCustomLoading = dynamic(
  () => import('../components/WithCustomLoading'),
  {
    loading: () => <p>Loading...</p>,
  }
)

export default function Page() {
  return (
    <div>
      {/* The loading component will be rendered while  <WithCustomLoading/> is loading */}
      <WithCustomLoading />
    </div>
  )
}
```

### [Importing Named Exports](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading\#importing-named-exports)

To dynamically import a named export, you can return it from the Promise returned by [`import()`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Operators/import) function:

components/hello.js

```code-block_code__isn_V
'use client'

export function Hello() {
  return <p>Hello!</p>
}
```

app/page.js

```code-block_code__isn_V
import dynamic from 'next/dynamic'

const ClientComponent = dynamic(() =>
  import('../components/hello').then((mod) => mod.Hello)
)
```

Was this helpful?

supported.

Send

## Custom Server Configuration
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Configuring](https://nextjs.org/docs/app/building-your-application/configuring) Custom Server

# Custom Server

Next.js includes its own server with `next start` by default. If you have an existing backend, you can still use it with Next.js (this is not a custom server). A custom Next.js server allows you to programmatically start a server for custom patterns. The majority of the time, you will not need this approach. However, it's available if you need to eject.

> **Good to know**:
>
> - Before deciding to use a custom server, keep in mind that it should only be used when the integrated router of Next.js can't meet your app requirements. A custom server will remove important performance optimizations, like **[Automatic Static Optimization](https://nextjs.org/docs/pages/building-your-application/rendering/automatic-static-optimization).**
> - A custom server **cannot** be deployed on [Vercel](https://vercel.com/frameworks/nextjs).
> - When using standalone output mode, it does not trace custom server files. This mode outputs a separate minimal `server.js` file, instead. These cannot be used together.

Take a look at the [following example](https://github.com/vercel/next.js/tree/canary/examples/custom-server) of a custom server:

server.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { createServer } from 'http'
import { parse } from 'url'
import next from 'next'

const port = parseInt(process.env.PORT || '3000', 10)
const dev = process.env.NODE_ENV !== 'production'
const app = next({ dev })
const handle = app.getRequestHandler()

app.prepare().then(() => {
  createServer((req, res) => {
    const parsedUrl = parse(req.url!, true)
    handle(req, res, parsedUrl)
  }).listen(port)

  console.log(
    `> Server listening at http://localhost:${port} as ${
      dev ? 'development' : process.env.NODE_ENV
    }`
  )
})
```

> `server.js` does not run through the Next.js Compiler or bundling process. Make sure the syntax and source code this file requires are compatible with the current Node.js version you are using. [View an example](https://github.com/vercel/next.js/tree/canary/examples/custom-server).

To run the custom server, you'll need to update the `scripts` in `package.json` like so:

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "node server.js",
    "build": "next build",
    "start": "NODE_ENV=production node server.js"
  }
}
```

Alternatively, you can set up `nodemon` ( [example](https://github.com/vercel/next.js/tree/canary/examples/custom-server)). The custom server uses the following import to connect the server with the Next.js application:

```code-block_code__isn_V
import next from 'next'

const app = next({})
```

The above `next` import is a function that receives an object with the following options:

| Option | Type | Description |
| --- | --- | --- |
| `conf` | `Object` | The same object you would use in `next.config.js`. Defaults to `{}` |
| `dev` | `Boolean` | ( _Optional_) Whether or not to launch Next.js in dev mode. Defaults to `false` |
| `dir` | `String` | ( _Optional_) Location of the Next.js project. Defaults to `'.'` |
| `quiet` | `Boolean` | ( _Optional_) Hide error messages containing server information. Defaults to `false` |
| `hostname` | `String` | ( _Optional_) The hostname the server is running behind |
| `port` | `Number` | ( _Optional_) The port the server is running behind |
| `httpServer` | `node:http#Server` | ( _Optional_) The HTTP Server that Next.js is running behind |
| `turbo` | `Boolean` | ( _Optional_) Enable Turbopack |

The returned `app` can then be used to let Next.js handle requests as required.

Was this helpful?

supported.

Send

## Migrating from Vite
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Upgrading](https://nextjs.org/docs/app/building-your-application/upgrading) Migrating from Vite

# Migrating from Vite

This guide will help you migrate an existing Vite application to Next.js.

## [Why Switch?](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#why-switch)

There are several reasons why you might want to switch from Vite to Next.js:

### [Slow initial page loading time](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#slow-initial-page-loading-time)

If you have built your application with the [default Vite plugin for React](https://github.com/vitejs/vite-plugin-react/tree/main/packages/plugin-react), your application is a purely client-side application. Client-side only applications, also known as single-page applications (SPAs), often experience slow initial page loading time. This happens due to a couple of reasons:

1. The browser needs to wait for the React code and your entire application bundle to download and run before your code is able to send requests to load some data.
2. Your application code grows with every new feature and extra dependency you add.

### [No automatic code splitting](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#no-automatic-code-splitting)

The previous issue of slow loading times can be somewhat managed with code splitting. However, if you try to do code splitting manually, you'll often make performance worse. It's easy to inadvertently introduce network waterfalls when code-splitting manually. Next.js provides automatic code splitting built into its router.

### [Network waterfalls](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#network-waterfalls)

A common cause of poor performance occurs when applications make sequential client-server requests to fetch data. One common pattern for data fetching in an SPA is to initially render a placeholder, and then fetch data after the component has mounted. Unfortunately, this means that a child component that fetches data can't start fetching until the parent component has finished loading its own data.

While fetching data on the client is supported with Next.js, it also gives you the option to shift data fetching to the server, which can eliminate client-server waterfalls.

### [Fast and intentional loading states](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#fast-and-intentional-loading-states)

With built-in support for [streaming through React Suspense](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming#streaming-with-suspense), you can be more intentional about which parts of your UI you want to load first and in what order without introducing network waterfalls.

This enables you to build pages that are faster to load and eliminate [layout shifts](https://vercel.com/blog/how-core-web-vitals-affect-seo).

### [Choose the data fetching strategy](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#choose-the-data-fetching-strategy)

Depending on your needs, Next.js allows you to choose your data fetching strategy on a page and component basis. You can decide to fetch at build time, at request time on the server, or on the client. For example, you can fetch data from your CMS and render your blog posts at build time, which can then be efficiently cached on a CDN.

### [Middleware](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#middleware)

[Next.js Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware) allows you to run code on the server before a request is completed. This is especially useful to avoid having a flash of unauthenticated content when the user visits an authenticated-only page by redirecting the user to a login page. The middleware is also useful for experimentation and [internationalization](https://nextjs.org/docs/app/building-your-application/routing/internationalization).

### [Built-in Optimizations](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#built-in-optimizations)

[Images](https://nextjs.org/docs/app/building-your-application/optimizing/images), [fonts](https://nextjs.org/docs/app/building-your-application/optimizing/fonts), and [third-party scripts](https://nextjs.org/docs/app/building-your-application/optimizing/scripts) often have significant impact on an application's performance. Next.js comes with built-in components that automatically optimize those for you.

## [Migration Steps](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#migration-steps)

Our goal with this migration is to get a working Next.js application as quickly as possible, so that
you can then adopt Next.js features incrementally. To begin with, we'll keep it as a purely
client-side application (SPA) without migrating your existing router. This helps minimize the
chances of encountering issues during the migration process and reduces merge conflicts.

### [Step 1: Install the Next.js Dependency](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#step-1-install-the-nextjs-dependency)

The first thing you need to do is to install `next` as a dependency:

Terminal

```code-block_code__isn_V
npm install next@latest
```

### [Step 2: Create the Next.js Configuration File](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#step-2-create-the-nextjs-configuration-file)

Create a `next.config.mjs` at the root of your project. This file will hold your
[Next.js configuration options](https://nextjs.org/docs/app/api-reference/config/next-config-js).

next.config.mjs

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
const nextConfig = {
  output: 'export', // Outputs a Single-Page Application (SPA).
  distDir: './dist', // Changes the build output directory to `./dist/`.
}

export default nextConfig
```

> **Good to know:** You can use either `.js` or `.mjs` for your Next.js configuration file.

### [Step 3: Update TypeScript Configuration](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#step-3-update-typescript-configuration)

If you're using TypeScript, you need to update your `tsconfig.json` file with the following changes
to make it compatible with Next.js. If you're not using TypeScript, you can skip this step.

1. Remove the [project reference](https://www.typescriptlang.org/tsconfig#references) to `tsconfig.node.json`
2. Add `./dist/types/**/*.ts` and `./next-env.d.ts` to the [`include` array](https://www.typescriptlang.org/tsconfig#include)
3. Add `./node_modules` to the [`exclude` array](https://www.typescriptlang.org/tsconfig#exclude)
4. Add `{ "name": "next" }` to the [`plugins` array in `compilerOptions`](https://www.typescriptlang.org/tsconfig#plugins): `"plugins": [{ "name": "next" }]`
5. Set [`esModuleInterop`](https://www.typescriptlang.org/tsconfig#esModuleInterop) to `true`: `"esModuleInterop": true`
6. Set [`jsx`](https://www.typescriptlang.org/tsconfig#jsx) to `preserve`: `"jsx": "preserve"`
7. Set [`allowJs`](https://www.typescriptlang.org/tsconfig#allowJs) to `true`: `"allowJs": true`
8. Set [`forceConsistentCasingInFileNames`](https://www.typescriptlang.org/tsconfig#forceConsistentCasingInFileNames) to `true`: `"forceConsistentCasingInFileNames": true`
9. Set [`incremental`](https://www.typescriptlang.org/tsconfig#incremental) to `true`: `"incremental": true`

Here's an example of a working `tsconfig.json` with those changes:

tsconfig.json

```code-block_code__isn_V
{
  "compilerOptions": {
    "target": "ES2020",
    "useDefineForClassFields": true,
    "lib": ["ES2020", "DOM", "DOM.Iterable"],
    "module": "ESNext",
    "esModuleInterop": true,
    "skipLibCheck": true,
    "moduleResolution": "bundler",
    "allowImportingTsExtensions": true,
    "resolveJsonModule": true,
    "isolatedModules": true,
    "noEmit": true,
    "jsx": "preserve",
    "strict": true,
    "noUnusedLocals": true,
    "noUnusedParameters": true,
    "noFallthroughCasesInSwitch": true,
    "allowJs": true,
    "forceConsistentCasingInFileNames": true,
    "incremental": true,
    "plugins": [{ "name": "next" }]
  },
  "include": ["./src", "./dist/types/**/*.ts", "./next-env.d.ts"],
  "exclude": ["./node_modules"]
}
```

You can find more information about configuring TypeScript on the
[Next.js docs](https://nextjs.org/docs/app/api-reference/config/typescript#ide-plugin).

### [Step 4: Create the Root Layout](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#step-4-create-the-root-layout)

A Next.js [App Router](https://nextjs.org/docs/app) application must include a
[root layout](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#root-layout-required)
file, which is a [React Server Component](https://nextjs.org/docs/app/building-your-application/rendering/server-components)
that will wrap all pages in your application. This file is defined at the top level of the `app`
directory.

The closest equivalent to the root layout file in a Vite application is the
[`index.html` file](https://vitejs.dev/guide/#index-html-and-project-root), which contains your
`<html>`, `<head>`, and `<body>` tags.

In this step, you'll convert your `index.html` file into a root layout file:

1. Create a new `app` directory in your `src` directory.
2. Create a new `layout.tsx` file inside that `app` directory:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return '...'
}
```

> **Good to know**: `.js`, `.jsx`, or `.tsx` extensions can be used for Layout files.

3. Copy the content of your `index.html` file into the previously created `<RootLayout>` component while
replacing the `body.div#root` and `body.script` tags with `<div id="root">{children}</div>`:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <link rel="icon" type="image/svg+xml" href="/icon.svg" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>My App</title>
        <meta name="description" content="My App is a..." />
      </head>
      <body>
        <div id="root">{children}</div>
      </body>
    </html>
  )
}
```

4. Next.js already includes by default the
[meta charset](https://developer.mozilla.org/docs/Web/HTML/Element/meta#charset) and
[meta viewport](https://developer.mozilla.org/docs/Web/HTML/Viewport_meta_tag) tags, so you
can safely remove those from your `<head>`:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <head>
        <link rel="icon" type="image/svg+xml" href="/icon.svg" />
        <title>My App</title>
        <meta name="description" content="My App is a..." />
      </head>
      <body>
        <div id="root">{children}</div>
      </body>
    </html>
  )
}
```

5. Any [metadata files](https://nextjs.org/docs/app/building-your-application/optimizing/metadata#file-based-metadata)
such as `favicon.ico`, `icon.png`, `robots.txt` are automatically added to the application
`<head>` tag as long as you have them placed into the top level of the `app` directory. After
moving
[all supported files](https://nextjs.org/docs/app/building-your-application/optimizing/metadata#file-based-metadata)
into the `app` directory you can safely delete their `<link>` tags:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <head>
        <title>My App</title>
        <meta name="description" content="My App is a..." />
      </head>
      <body>
        <div id="root">{children}</div>
      </body>
    </html>
  )
}
```

6. Finally, Next.js can manage your last `<head>` tags with the
[Metadata API](https://nextjs.org/docs/app/building-your-application/optimizing/metadata). Move your final metadata
info into an exported
[`metadata` object](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#metadata-object):

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { Metadata } from 'next'

export const metadata: Metadata = {
  title: 'My App',
  description: 'My App is a...',
}

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body>
        <div id="root">{children}</div>
      </body>
    </html>
  )
}
```

With the above changes, you shifted from declaring everything in your `index.html` to using Next.js'
convention-based approach built into the framework
( [Metadata API](https://nextjs.org/docs/app/building-your-application/optimizing/metadata)). This approach enables you
to more easily improve your SEO and web shareability of your pages.

### [Step 5: Create the Entrypoint Page](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#step-5-create-the-entrypoint-page)

On Next.js you declare an entrypoint for your application by creating a `page.tsx` file. The
closest equivalent of this file on Vite is your `main.tsx` file. In this step, you’ll set up the
entrypoint of your application.

1. **Create a `[[...slug]]` directory in your `app` directory.**

Since in this guide we're aiming first to set up our Next.js as an SPA (Single Page Application), you need your page entrypoint to catch all possible routes of your application. For that, create a new `[[...slug]]` directory in your `app` directory.

This directory is what is called an [optional catch-all route segment](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes#optional-catch-all-segments). Next.js uses a file-system based router where folders are used to define routes. This special directory will make sure that all routes of your application will be directed to its containing `page.tsx` file.

2. **Create a new `page.tsx` file inside the `app/[[...slug]]` directory with the following content:**

app/\[\[...slug\]\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import '../../index.css'

export function generateStaticParams() {
  return [{ slug: [''] }]
}

export default function Page() {
  return '...' // We'll update this
}
```

> **Good to know**: `.js`, `.jsx`, or `.tsx` extensions can be used for Page files.

This file is a [Server Component](https://nextjs.org/docs/app/building-your-application/rendering/server-components). When you run `next build`, the file is prerendered into a static asset. It does _not_ require any dynamic code.

This file imports our global CSS and tells [`generateStaticParams`](https://nextjs.org/docs/app/api-reference/functions/generate-static-params) we are only going to generate one route, the index route at `/`.

Now, let's move the rest of our Vite application which will run client-only.

app/\[\[...slug\]\]/client.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import React from 'react'
import dynamic from 'next/dynamic'

const App = dynamic(() => import('../../App'), { ssr: false })

export function ClientOnly() {
  return <App />
}
```

This file is a [Client Component](https://nextjs.org/docs/app/building-your-application/rendering/client-components), defined by the `'use client'`
directive. Client Components are still [prerendered to HTML](https://nextjs.org/docs/app/building-your-application/rendering/client-components#how-are-client-components-rendered) on the server before being sent to the client.

Since we want a client-only application to start, we can configure Next.js to disable prerendering from the `App` component down.

```code-block_code__isn_V
const App = dynamic(() => import('../../App'), { ssr: false })
```

Now, update your entrypoint page to use the new component:

app/\[\[...slug\]\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import '../../index.css'
import { ClientOnly } from './client'

export function generateStaticParams() {
  return [{ slug: [''] }]
}

export default function Page() {
  return <ClientOnly />
}
```

### [Step 6: Update Static Image Imports](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#step-6-update-static-image-imports)

Next.js handles static image imports slightly different from Vite. With Vite, importing an image
file will return its public URL as a string:

App.tsx

```code-block_code__isn_V
import image from './img.png' // `image` will be '/assets/img.2d8efhg.png' in production

export default function App() {
  return <img src={image} />
}
```

With Next.js, static image imports return an object. The object can then be used directly with the
Next.js [`<Image>` component](https://nextjs.org/docs/app/api-reference/components/image), or you can use the object's
`src` property with your existing `<img>` tag.

The `<Image>` component has the added benefits of
[automatic image optimization](https://nextjs.org/docs/app/building-your-application/optimizing/images). The `<Image>`
component automatically sets the `width` and `height` attributes of the resulting `<img>` based on
the image's dimensions. This prevents layout shifts when the image loads. However, this can cause
issues if your app contains images with only one of their dimensions being styled without the other
styled to `auto`. When not styled to `auto`, the dimension will default to the `<img>` dimension
attribute's value, which can cause the image to appear distorted.

Keeping the `<img>` tag will reduce the amount of changes in your application and prevent the above
issues. You can then optionally later migrate to the `<Image>` component to take advantage of optimizing images by [configuring a loader](https://nextjs.org/docs/app/building-your-application/optimizing/images#loaders), or moving to the default Next.js server which has automatic image optimization.

1. **Convert absolute import paths for images imported from `/public` into relative imports:**

```code-block_code__isn_V
// Before
import logo from '/logo.png'

// After
import logo from '../public/logo.png'
```

2. **Pass the image `src` property instead of the whole image object to your `<img>` tag:**

```code-block_code__isn_V
// Before
<img src={logo} />

// After
<img src={logo.src} />
```

Alternatively, you can reference the public URL for the image asset based on the filename. For example, `public/logo.png` will serve the image at `/logo.png` for your application, which would be the `src` value.

> **Warning:** If you're using TypeScript, you might encounter type errors when accessing the `src`
> property. You can safely ignore those for now. They will be fixed by the end of this guide.

### [Step 7: Migrate the Environment Variables](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#step-7-migrate-the-environment-variables)

Next.js has support for `.env` [environment variables](https://nextjs.org/docs/app/building-your-application/configuring/environment-variables)
similar to Vite. The main difference is the prefix used to expose environment variables on the
client-side.

- Change all environment variables with the `VITE_` prefix to `NEXT_PUBLIC_`.

Vite exposes a few built-in environment variables on the special `import.meta.env` object which
aren’t supported by Next.js. You need to update their usage as follows:

- `import.meta.env.MODE` ⇒ `process.env.NODE_ENV`
- `import.meta.env.PROD` ⇒ `process.env.NODE_ENV === 'production'`
- `import.meta.env.DEV` ⇒ `process.env.NODE_ENV !== 'production'`
- `import.meta.env.SSR` ⇒ `typeof window !== 'undefined'`

Next.js also doesn't provide a built-in `BASE_URL` environment variable. However, you can still
configure one, if you need it:

1. **Add the following to your `.env` file:**

.env

```code-block_code__isn_V
# ...
NEXT_PUBLIC_BASE_PATH="/some-base-path"
```

2. **Set [`basePath`](https://nextjs.org/docs/app/api-reference/config/next-config-js/basePath) to `process.env.NEXT_PUBLIC_BASE_PATH` in your `next.config.mjs` file:**

next.config.mjs

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
const nextConfig = {
  output: 'export', // Outputs a Single-Page Application (SPA).
  distDir: './dist', // Changes the build output directory to `./dist/`.
  basePath: process.env.NEXT_PUBLIC_BASE_PATH, // Sets the base path to `/some-base-path`.
}

export default nextConfig
```

3. **Update `import.meta.env.BASE_URL` usages to `process.env.NEXT_PUBLIC_BASE_PATH`**

### [Step 8: Update Scripts in `package.json`](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#step-8-update-scripts-in-packagejson)

You should now be able to run your application to test if you successfully migrated to Next.js. But
before that, you need to update your `scripts` in your `package.json` with Next.js related commands,
and add `.next` and `next-env.d.ts` to your `.gitignore`:

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  }
}
```

.gitignore

```code-block_code__isn_V
# ...
.next
next-env.d.ts
dist
```

Now run `npm run dev`, and open [`http://localhost:3000`](http://localhost:3000/). You should see your application now running on Next.js.

> **Example:** Check out [this pull request](https://github.com/inngest/vite-to-nextjs/pull/1) for a
> working example of a Vite application migrated to Next.js.

### [Step 9: Clean Up](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#step-9-clean-up)

You can now clean up your codebase from Vite related artifacts:

- Delete `main.tsx`
- Delete `index.html`
- Delete `vite-env.d.ts`
- Delete `tsconfig.node.json`
- Delete `vite.config.ts`
- Uninstall Vite dependencies

## [Next Steps](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite\#next-steps)

If everything went according to plan, you now have a functioning Next.js application running as a
single-page application. However, you aren't yet taking advantage of most of Next.js' benefits, but
you can now start making incremental changes to reap all the benefits. Here's what you might want to
do next:

- Migrate from React Router to the [Next.js App Router](https://nextjs.org/docs/app/building-your-application/routing) to get:
  - Automatic code splitting
  - [Streaming Server-Rendering](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming)
  - [React Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components)
- [Optimize images with the `<Image>` component](https://nextjs.org/docs/app/building-your-application/optimizing/images)
- [Optimize fonts with `next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts)
- [Optimize third-party scripts with the `<Script>` component](https://nextjs.org/docs/app/building-your-application/optimizing/scripts)
- [Update your ESLint configuration to support Next.js rules](https://nextjs.org/docs/app/api-reference/config/eslint)

Was this helpful?

supported.

Send

## Loading UI and Streaming
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Loading UI and Streaming

# Loading UI and Streaming

The special file `loading.js` helps you create meaningful Loading UI with [React Suspense](https://react.dev/reference/react/Suspense). With this convention, you can show an [instant loading state](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming#instant-loading-states) from the server while the content of a route segment loads. The new content is automatically swapped in once rendering is complete.

![Loading UI](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Floading-ui.png&w=3840&q=75)![Loading UI](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Floading-ui.png&w=3840&q=75)

## [Instant Loading States](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming\#instant-loading-states)

An instant loading state is fallback UI that is shown immediately upon navigation. You can pre-render loading indicators such as skeletons and spinners, or a small but meaningful part of future screens such as a cover photo, title, etc. This helps users understand the app is responding and provides a better user experience.

Create a loading state by adding a `loading.js` file inside a folder.

![loading.js special file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Floading-special-file.png&w=3840&q=75)![loading.js special file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Floading-special-file.png&w=3840&q=75)

app/dashboard/loading.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Loading() {
  // You can add any UI inside Loading, including a Skeleton.
  return <LoadingSkeleton />
}
```

In the same folder, `loading.js` will be nested inside `layout.js`. It will automatically wrap the `page.js` file and any children below in a `<Suspense>` boundary.

![loading.js overview](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Floading-overview.png&w=3840&q=75)![loading.js overview](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Floading-overview.png&w=3840&q=75)

> **Good to know**:
>
> - Navigation is immediate, even with [server-centric routing](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#how-routing-and-navigation-works).
> - Navigation is interruptible, meaning changing routes does not need to wait for the content of the route to fully load before navigating to another route.
> - Shared layouts remain interactive while new route segments load.

> **Recommendation:** Use the `loading.js` convention for route segments (layouts and pages) as Next.js optimizes this functionality.

## [Streaming with Suspense](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming\#streaming-with-suspense)

In addition to `loading.js`, you can also manually create Suspense Boundaries for your own UI components. The App Router supports streaming with [Suspense](https://react.dev/reference/react/Suspense).

> **Good to know**:
>
> - [Some browsers](https://bugs.webkit.org/show_bug.cgi?id=252413) buffer a streaming response. You may not see the streamed response until the response exceeds 1024 bytes. This typically only affects “hello world” applications, but not real applications.

### [What is Streaming?](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming\#what-is-streaming)

To learn how Streaming works in React and Next.js, it's helpful to understand **Server-Side Rendering (SSR)** and its limitations.

With SSR, there's a series of steps that need to be completed before a user can see and interact with a page:

1. First, all data for a given page is fetched on the server.
2. The server then renders the HTML for the page.
3. The HTML, CSS, and JavaScript for the page are sent to the client.
4. A non-interactive user interface is shown using the generated HTML, and CSS.
5. Finally, React [hydrates](https://react.dev/reference/react-dom/client/hydrateRoot#hydrating-server-rendered-html) the user interface to make it interactive.

![Chart showing Server Rendering without Streaming](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fserver-rendering-without-streaming-chart.png&w=3840&q=75)![Chart showing Server Rendering without Streaming](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fserver-rendering-without-streaming-chart.png&w=3840&q=75)

These steps are sequential and blocking, meaning the server can only render the HTML for a page once all the data has been fetched. And, on the client, React can only hydrate the UI once the code for all components in the page has been downloaded.

SSR with React and Next.js helps improve the perceived loading performance by showing a non-interactive page to the user as soon as possible.

![Server Rendering without Streaming](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fserver-rendering-without-streaming.png&w=3840&q=75)![Server Rendering without Streaming](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fserver-rendering-without-streaming.png&w=3840&q=75)

However, it can still be slow as all data fetching on server needs to be completed before the page can be shown to the user.

**Streaming** allows you to break down the page's HTML into smaller chunks and progressively send those chunks from the server to the client.

![How Server Rendering with Streaming Works](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fserver-rendering-with-streaming.png&w=3840&q=75)![How Server Rendering with Streaming Works](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fserver-rendering-with-streaming.png&w=3840&q=75)

This enables parts of the page to be displayed sooner, without waiting for all the data to load before any UI can be rendered.

Streaming works well with React's component model because each component can be considered a chunk. Components that have higher priority (e.g. product information) or that don't rely on data can be sent first (e.g. layout), and React can start hydration earlier. Components that have lower priority (e.g. reviews, related products) can be sent in the same server request after their data has been fetched.

![Chart showing Server Rendering with Streaming](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fserver-rendering-with-streaming-chart.png&w=3840&q=75)![Chart showing Server Rendering with Streaming](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fserver-rendering-with-streaming-chart.png&w=3840&q=75)

Streaming is particularly beneficial when you want to prevent long data requests from blocking the page from rendering as it can reduce the [Time To First Byte (TTFB)](https://web.dev/ttfb/) and [First Contentful Paint (FCP)](https://web.dev/first-contentful-paint/). It also helps improve [Time to Interactive (TTI)](https://developer.chrome.com/en/docs/lighthouse/performance/interactive/), especially on slower devices.

### [Example](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming\#example)

`<Suspense>` works by wrapping a component that performs an asynchronous action (e.g. fetch data), showing fallback UI (e.g. skeleton, spinner) while it's happening, and then swapping in your component once the action completes.

app/dashboard/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Suspense } from 'react'
import { PostFeed, Weather } from './Components'

export default function Posts() {
  return (
    <section>
      <Suspense fallback={<p>Loading feed...</p>}>
        <PostFeed />
      </Suspense>
      <Suspense fallback={<p>Loading weather...</p>}>
        <Weather />
      </Suspense>
    </section>
  )
}
```

By using Suspense, you get the benefits of:

1. **Streaming Server Rendering** \- Progressively rendering HTML from the server to the client.
2. **Selective Hydration** \- React prioritizes what components to make interactive first based on user interaction.

For more Suspense examples and use cases, please see the [React Documentation](https://react.dev/reference/react/Suspense).

### [SEO](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming\#seo)

- Next.js will wait for data fetching inside [`generateMetadata`](https://nextjs.org/docs/app/api-reference/functions/generate-metadata) to complete before streaming UI to the client. This guarantees the first part of a streamed response includes `<head>` tags.
- Since streaming is server-rendered, it does not impact SEO. You can use the [Rich Results Test](https://search.google.com/test/rich-results) tool from Google to see how your page appears to Google's web crawlers and view the serialized HTML ( [source](https://web.dev/rendering-on-the-web/#seo-considerations)).

### [Status Codes](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming\#status-codes)

When streaming, a `200` status code will be returned to signal that the request was successful.

The server can still communicate errors or issues to the client within the streamed content itself, for example, when using [`redirect`](https://nextjs.org/docs/app/api-reference/functions/redirect) or [`notFound`](https://nextjs.org/docs/app/api-reference/functions/not-found). Since the response headers have already been sent to the client, the status code of the response cannot be updated. This does not affect SEO.

Was this helpful?

supported.

Send

## MDX Components Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [File Conventions](https://nextjs.org/docs/app/api-reference/file-conventions) mdx-components.js

# mdx-components.js

The `mdx-components.js|tsx` file is **required** to use [`@next/mdx` with App Router](https://nextjs.org/docs/app/building-your-application/configuring/mdx) and will not work without it. Additionally, you can use it to [customize styles](https://nextjs.org/docs/app/building-your-application/configuring/mdx#using-custom-styles-and-components).

Use the file `mdx-components.tsx` (or `.js`) in the root of your project to define MDX Components. For example, at the same level as `pages` or `app`, or inside `src` if applicable.

mdx-components.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { MDXComponents } from 'mdx/types'

export function useMDXComponents(components: MDXComponents): MDXComponents {
  return {
    ...components,
  }
}
```

## [Exports](https://nextjs.org/docs/app/api-reference/file-conventions/mdx-components\#exports)

### [`useMDXComponents` function](https://nextjs.org/docs/app/api-reference/file-conventions/mdx-components\#usemdxcomponents-function)

The file must export a single function, either as a default export or named `useMDXComponents`.

mdx-components.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { MDXComponents } from 'mdx/types'

export function useMDXComponents(components: MDXComponents): MDXComponents {
  return {
    ...components,
  }
}
```

## [Params](https://nextjs.org/docs/app/api-reference/file-conventions/mdx-components\#params)

### [`components`](https://nextjs.org/docs/app/api-reference/file-conventions/mdx-components\#components)

When defining MDX Components, the export function accepts a single parameter, `components`. This parameter is an instance of `MDXComponents`.

- The key is the name of the HTML element to override.
- The value is the component to render instead.

> **Good to know**: Remember to pass all other components (i.e. `...components`) that do not have overrides.

## [Version History](https://nextjs.org/docs/app/api-reference/file-conventions/mdx-components\#version-history)

| Version | Changes |
| --- | --- |
| `v13.1.2` | MDX Components added |

## Learn more about MDX Components

[**MDX** \\
Learn how to configure MDX and use it in your Next.js apps.](https://nextjs.org/docs/app/building-your-application/configuring/mdx)

Was this helpful?

supported.

Send

## Dynamic Routes in Next.js
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Dynamic Routes

# Dynamic Routes

When you don't know the exact segment names ahead of time and want to create routes from dynamic data, you can use Dynamic Segments that are filled in at request time or [prerendered](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes#generating-static-params) at build time.

## [Convention](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes\#convention)

A Dynamic Segment can be created by wrapping a folder's name in square brackets: `[folderName]`. For example, `[id]` or `[slug]`.

Dynamic Segments are passed as the `params` prop to [`layout`](https://nextjs.org/docs/app/api-reference/file-conventions/layout), [`page`](https://nextjs.org/docs/app/api-reference/file-conventions/page), [`route`](https://nextjs.org/docs/app/building-your-application/routing/route-handlers), and [`generateMetadata`](https://nextjs.org/docs/app/api-reference/functions/generate-metadata#generatemetadata-function) functions.

## [Example](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes\#example)

For example, a blog could include the following route `app/blog/[slug]/page.js` where `[slug]` is the Dynamic Segment for blog posts.

app/blog/\[slug\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Page({
  params,
}: {
  params: Promise<{ slug: string }>
}) {
  const { slug } = await params
  return <div>My Post: {slug}</div>
}
```

| Route | Example URL | `params` |
| --- | --- | --- |
| `app/blog/[slug]/page.js` | `/blog/a` | `{ slug: 'a' }` |
| `app/blog/[slug]/page.js` | `/blog/b` | `{ slug: 'b' }` |
| `app/blog/[slug]/page.js` | `/blog/c` | `{ slug: 'c' }` |

See the [generateStaticParams()](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes#generating-static-params) page to learn how to generate the params for the segment.

## [Good to know](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes\#good-to-know)

- Since the `params` prop is a promise. You must use async/await or React's use function to access the values.
  - In version 14 and earlier, `params` was a synchronous prop. To help with backwards compatibility, you can still access it synchronously in Next.js 15, but this behavior will be deprecated in the future.
- Dynamic Segments are equivalent to [Dynamic Routes](https://nextjs.org/docs/pages/building-your-application/routing/dynamic-routes) in the `pages` directory.

## [Generating Static Params](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes\#generating-static-params)

The `generateStaticParams` function can be used in combination with [dynamic route segments](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes) to [**statically generate**](https://nextjs.org/docs/app/building-your-application/rendering/server-components#static-rendering-default) routes at build time instead of on-demand at request time.

app/blog/\[slug\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function generateStaticParams() {
  const posts = await fetch('https://.../posts').then((res) => res.json())

  return posts.map((post) => ({
    slug: post.slug,
  }))
}
```

The primary benefit of the `generateStaticParams` function is its smart retrieval of data. If content is fetched within the `generateStaticParams` function using a `fetch` request, the requests are [automatically memoized](https://nextjs.org/docs/app/building-your-application/caching#request-memoization). This means a `fetch` request with the same arguments across multiple `generateStaticParams`, Layouts, and Pages will only be made once, which decreases build times.

Use the [migration guide](https://nextjs.org/docs/app/building-your-application/upgrading/app-router-migration#dynamic-paths-getstaticpaths) if you are migrating from the `pages` directory.

See [`generateStaticParams` server function documentation](https://nextjs.org/docs/app/api-reference/functions/generate-static-params) for more information and advanced use cases.

## [Catch-all Segments](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes\#catch-all-segments)

Dynamic Segments can be extended to **catch-all** subsequent segments by adding an ellipsis inside the brackets `[...folderName]`.

For example, `app/shop/[...slug]/page.js` will match `/shop/clothes`, but also `/shop/clothes/tops`, `/shop/clothes/tops/t-shirts`, and so on.

| Route | Example URL | `params` |
| --- | --- | --- |
| `app/shop/[...slug]/page.js` | `/shop/a` | `{ slug: ['a'] }` |
| `app/shop/[...slug]/page.js` | `/shop/a/b` | `{ slug: ['a', 'b'] }` |
| `app/shop/[...slug]/page.js` | `/shop/a/b/c` | `{ slug: ['a', 'b', 'c'] }` |

## [Optional Catch-all Segments](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes\#optional-catch-all-segments)

Catch-all Segments can be made **optional** by including the parameter in double square brackets: `[[...folderName]]`.

For example, `app/shop/[[...slug]]/page.js` will **also** match `/shop`, in addition to `/shop/clothes`, `/shop/clothes/tops`, `/shop/clothes/tops/t-shirts`.

The difference between **catch-all** and **optional catch-all** segments is that with optional, the route without the parameter is also matched ( `/shop` in the example above).

| Route | Example URL | `params` |
| --- | --- | --- |
| `app/shop/[[...slug]]/page.js` | `/shop` | `{ slug: undefined }` |
| `app/shop/[[...slug]]/page.js` | `/shop/a` | `{ slug: ['a'] }` |
| `app/shop/[[...slug]]/page.js` | `/shop/a/b` | `{ slug: ['a', 'b'] }` |
| `app/shop/[[...slug]]/page.js` | `/shop/a/b/c` | `{ slug: ['a', 'b', 'c'] }` |

## [TypeScript](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes\#typescript)

When using TypeScript, you can add types for `params` depending on your configured route segment.

app/blog/\[slug\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Page({
  params,
}: {
  params: Promise<{ slug: string }>
}) {
  return <h1>My Page</h1>
}
```

| Route | `params` Type Definition |
| --- | --- |
| `app/blog/[slug]/page.js` | `{ slug: string }` |
| `app/shop/[...slug]/page.js` | `{ slug: string[] }` |
| `app/shop/[[...slug]]/page.js` | `{ slug?: string[] }` |
| `app/[categoryId]/[itemId]/page.js` | `{ categoryId: string, itemId: string }` |

> **Good to know**: This may be done automatically by the [TypeScript plugin](https://nextjs.org/docs/app/api-reference/config/typescript#ide-plugin) in the future.

## Next Steps

For more information on what to do next, we recommend the following sections

[**Linking and Navigating** \\
Learn how navigation works in Next.js, and how to use the Link Component and \`useRouter\` hook.](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating) [**generateStaticParams** \\
API reference for the generateStaticParams function.](https://nextjs.org/docs/app/api-reference/functions/generate-static-params)

Was this helpful?

supported.

Send

## Playwright Setup Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Testing](https://nextjs.org/docs/app/building-your-application/testing) Playwright

# Setting up Playwright with Next.js

Playwright is a testing framework that lets you automate Chromium, Firefox, and WebKit with a single API. You can use it to write **End-to-End (E2E)** testing. This guide will show you how to set up Playwright with Next.js and write your first tests.

## [Quickstart](https://nextjs.org/docs/app/building-your-application/testing/playwright\#quickstart)

The fastest way to get started is to use `create-next-app` with the [with-playwright example](https://github.com/vercel/next.js/tree/canary/examples/with-playwright). This will create a Next.js project complete with Playwright configured.

Terminal

```code-block_code__isn_V
npx create-next-app@latest --example with-playwright with-playwright-app
```

## [Manual setup](https://nextjs.org/docs/app/building-your-application/testing/playwright\#manual-setup)

To install Playwright, run the following command:

Terminal

```code-block_code__isn_V
npm init playwright
# or
yarn create playwright
# or
pnpm create playwright
```

This will take you through a series of prompts to setup and configure Playwright for your project, including adding a `playwright.config.ts` file. Please refer to the [Playwright installation guide](https://playwright.dev/docs/intro#installation) for the step-by-step guide.

## [Creating your first Playwright E2E test](https://nextjs.org/docs/app/building-your-application/testing/playwright\#creating-your-first-playwright-e2e-test)

Create two new Next.js pages:

app/page.tsx

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return (
    <div>
      <h1>Home</h1>
      <Link href="/about">About</Link>
    </div>
  )
}
```

app/about/page.tsx

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return (
    <div>
      <h1>About</h1>
      <Link href="/">Home</Link>
    </div>
  )
}
```

Then, add a test to verify that your navigation is working correctly:

tests/example.spec.ts

```code-block_code__isn_V
import { test, expect } from '@playwright/test'

test('should navigate to the about page', async ({ page }) => {
  // Start from the index page (the baseURL is set via the webServer in the playwright.config.ts)
  await page.goto('http://localhost:3000/')
  // Find an element with the text 'About' and click on it
  await page.click('text=About')
  // The new URL should be "/about" (baseURL is used there)
  await expect(page).toHaveURL('http://localhost:3000/about')
  // The new page should contain an h1 with "About"
  await expect(page.locator('h1')).toContainText('About')
})
```

> **Good to know**: You can use `page.goto("/")` instead of `page.goto("http://localhost:3000/")`, if you add [`"baseURL": "http://localhost:3000"`](https://playwright.dev/docs/api/class-testoptions#test-options-base-url) to the `playwright.config.ts` [configuration file](https://playwright.dev/docs/test-configuration).

### [Running your Playwright tests](https://nextjs.org/docs/app/building-your-application/testing/playwright\#running-your-playwright-tests)

Playwright will simulate a user navigating your application using three browsers: Chromium, Firefox and Webkit, this requires your Next.js server to be running. We recommend running your tests against your production code to more closely resemble how your application will behave.

Run `npm run build` and `npm run start`, then run `npx playwright test` in another terminal window to run the Playwright tests.

> **Good to know**: Alternatively, you can use the [`webServer`](https://playwright.dev/docs/test-webserver/) feature to let Playwright start the development server and wait until it's fully available.

### [Running Playwright on Continuous Integration (CI)](https://nextjs.org/docs/app/building-your-application/testing/playwright\#running-playwright-on-continuous-integration-ci)

Playwright will by default run your tests in the [headless mode](https://playwright.dev/docs/ci#running-headed). To install all the Playwright dependencies, run `npx playwright install-deps`.

You can learn more about Playwright and Continuous Integration from these resources:

- [Next.js with Playwright example](https://github.com/vercel/next.js/tree/canary/examples/with-playwright)
- [Playwright on your CI provider](https://playwright.dev/docs/ci)
- [Playwright Discord](https://discord.com/invite/playwright-807756831384403968)

Was this helpful?

supported.

Send

## Font Optimization Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) Fonts

# Font Optimization

[**`next/font`**](https://nextjs.org/docs/app/api-reference/components/font) will automatically optimize your fonts (including custom fonts) and remove external network requests for improved privacy and performance.

> **🎥 Watch:** Learn more about using `next/font` → [YouTube (6 minutes)](https://www.youtube.com/watch?v=L8_98i_bMMA).

`next/font` includes **built-in automatic self-hosting** for _any_ font file. This means you can optimally load web fonts with zero layout shift, thanks to the underlying CSS `size-adjust` property used.

This new font system also allows you to conveniently use all Google Fonts with performance and privacy in mind. CSS and font files are downloaded at build time and self-hosted with the rest of your static assets. **No requests are sent to Google by the browser.**

## [Google Fonts](https://nextjs.org/docs/app/building-your-application/optimizing/fonts\#google-fonts)

Automatically self-host any Google Font. Fonts are included in the deployment and served from the same domain as your deployment. **No requests are sent to Google by the browser.**

Get started by importing the font you would like to use from `next/font/google` as a function. We recommend using [variable fonts](https://fonts.google.com/variablefonts) for the best performance and flexibility.

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Inter } from 'next/font/google'

// If loading a variable font, you don't need to specify the font weight
const inter = Inter({
  subsets: ['latin'],
  display: 'swap',
})

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en" className={inter.className}>
      <body>{children}</body>
    </html>
  )
}
```

If you can't use a variable font, you will **need to specify a weight**:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Roboto } from 'next/font/google'

const roboto = Roboto({
  weight: '400',
  subsets: ['latin'],
  display: 'swap',
})

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en" className={roboto.className}>
      <body>{children}</body>
    </html>
  )
}
```

You can specify multiple weights and/or styles by using an array:

app/layout.js

```code-block_code__isn_V
const roboto = Roboto({
  weight: ['400', '700'],
  style: ['normal', 'italic'],
  subsets: ['latin'],
  display: 'swap',
})
```

> **Good to know**: Use an underscore (\_) for font names with multiple words. E.g. `Roboto Mono` should be imported as `Roboto_Mono`.

### [Specifying a subset](https://nextjs.org/docs/app/building-your-application/optimizing/fonts\#specifying-a-subset)

Google Fonts are automatically [subset](https://fonts.google.com/knowledge/glossary/subsetting). This reduces the size of the font file and improves performance. You'll need to define which of these subsets you want to preload. Failing to specify any subsets while [`preload`](https://nextjs.org/docs/app/api-reference/components/font#preload) is `true` will result in a warning.

This can be done by adding it to the function call:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
const inter = Inter({ subsets: ['latin'] })
```

View the [Font API Reference](https://nextjs.org/docs/app/api-reference/components/font) for more information.

### [Using Multiple Fonts](https://nextjs.org/docs/app/building-your-application/optimizing/fonts\#using-multiple-fonts)

You can import and use multiple fonts in your application. There are two approaches you can take.

The first approach is to create a utility function that exports a font, imports it, and applies its `className` where needed. This ensures the font is preloaded only when it's rendered:

app/fonts.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Inter, Roboto_Mono } from 'next/font/google'

export const inter = Inter({
  subsets: ['latin'],
  display: 'swap',
})

export const roboto_mono = Roboto_Mono({
  subsets: ['latin'],
  display: 'swap',
})
```

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { inter } from './fonts'

export default function Layout({ children }: { children: React.ReactNode }) {
  return (
    <html lang="en" className={inter.className}>
      <body>
        <div>{children}</div>
      </body>
    </html>
  )
}
```

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { roboto_mono } from './fonts'

export default function Page() {
  return (
    <>
      <h1 className={roboto_mono.className}>My page</h1>
    </>
  )
}
```

In the example above, `Inter` will be applied globally, and `Roboto Mono` can be imported and applied as needed.

Alternatively, you can create a [CSS variable](https://nextjs.org/docs/app/api-reference/components/font#variable) and use it with your preferred CSS solution:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Inter, Roboto_Mono } from 'next/font/google'
import styles from './global.css'

const inter = Inter({
  subsets: ['latin'],
  variable: '--font-inter',
  display: 'swap',
})

const roboto_mono = Roboto_Mono({
  subsets: ['latin'],
  variable: '--font-roboto-mono',
  display: 'swap',
})

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en" className={`${inter.variable} ${roboto_mono.variable}`}>
      <body>
        <h1>My App</h1>
        <div>{children}</div>
      </body>
    </html>
  )
}
```

app/global.css

```code-block_code__isn_V
html {
  font-family: var(--font-inter);
}

h1 {
  font-family: var(--font-roboto-mono);
}
```

In the example above, `Inter` will be applied globally, and any `<h1>` tags will be styled with `Roboto Mono`.

> **Recommendation**: Use multiple fonts conservatively since each new font is an additional resource the client has to download.

## [Local Fonts](https://nextjs.org/docs/app/building-your-application/optimizing/fonts\#local-fonts)

Import `next/font/local` and specify the `src` of your local font file. We recommend using [variable fonts](https://fonts.google.com/variablefonts) for the best performance and flexibility.

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import localFont from 'next/font/local'

// Font files can be colocated inside of `app`
const myFont = localFont({
  src: './my-font.woff2',
  display: 'swap',
})

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en" className={myFont.className}>
      <body>{children}</body>
    </html>
  )
}
```

If you want to use multiple files for a single font family, `src` can be an array:

```code-block_code__isn_V
const roboto = localFont({
  src: [\
    {\
      path: './Roboto-Regular.woff2',\
      weight: '400',\
      style: 'normal',\
    },\
    {\
      path: './Roboto-Italic.woff2',\
      weight: '400',\
      style: 'italic',\
    },\
    {\
      path: './Roboto-Bold.woff2',\
      weight: '700',\
      style: 'normal',\
    },\
    {\
      path: './Roboto-BoldItalic.woff2',\
      weight: '700',\
      style: 'italic',\
    },\
  ],
})
```

View the [Font API Reference](https://nextjs.org/docs/app/api-reference/components/font) for more information.

## [With Tailwind CSS](https://nextjs.org/docs/app/building-your-application/optimizing/fonts\#with-tailwind-css)

`next/font` can be used with [Tailwind CSS](https://tailwindcss.com/) through a [CSS variable](https://nextjs.org/docs/app/api-reference/components/font#css-variables).

In the example below, we use the font `Inter` from `next/font/google` (you can use any font from Google or Local Fonts). Load your font with the `variable` option to define your CSS variable name and assign it to `inter`. Then, use `inter.variable` to add the CSS variable to your HTML document.

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Inter, Roboto_Mono } from 'next/font/google'

const inter = Inter({
  subsets: ['latin'],
  display: 'swap',
  variable: '--font-inter',
})

const roboto_mono = Roboto_Mono({
  subsets: ['latin'],
  display: 'swap',
  variable: '--font-roboto-mono',
})

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en" className={`${inter.variable} ${roboto_mono.variable}`}>
      <body>{children}</body>
    </html>
  )
}
```

Finally, add the CSS variable to your [Tailwind CSS config](https://nextjs.org/docs/app/building-your-application/styling/tailwind-css#configuring-tailwind):

tailwind.config.js

```code-block_code__isn_V
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [\
    './pages/**/*.{js,ts,jsx,tsx}',\
    './components/**/*.{js,ts,jsx,tsx}',\
    './app/**/*.{js,ts,jsx,tsx}',\
  ],
  theme: {
    extend: {
      fontFamily: {
        sans: ['var(--font-inter)'],
        mono: ['var(--font-roboto-mono)'],
      },
    },
  },
  plugins: [],
}
```

You can now use the `font-sans` and `font-mono` utility classes to apply the font to your elements.

## [Preloading](https://nextjs.org/docs/app/building-your-application/optimizing/fonts\#preloading)

When a font function is called on a page of your site, it is not globally available and preloaded on all routes. Rather, the font is only preloaded on the related routes based on the type of file where it is used:

- If it's a [unique page](https://nextjs.org/docs/app/api-reference/file-conventions/page), it is preloaded on the unique route for that page.
- If it's a [layout](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#layouts), it is preloaded on all the routes wrapped by the layout.
- If it's the [root layout](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#root-layout-required), it is preloaded on all routes.

## [Reusing fonts](https://nextjs.org/docs/app/building-your-application/optimizing/fonts\#reusing-fonts)

Every time you call the `localFont` or Google font function, that font is hosted as one instance in your application. Therefore, if you load the same font function in multiple files, multiple instances of the same font are hosted. In this situation, it is recommended to do the following:

- Call the font loader function in one shared file
- Export it as a constant
- Import the constant in each file where you would like to use this font

## API Reference

Learn more about the next/font API.

[**Font** \\
Optimizing loading web fonts with the built-in \`next/font\` loaders.](https://nextjs.org/docs/app/api-reference/components/font)

Was this helpful?

supported.

Send

## Next.js Error Handling
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Error Handling

# Error Handling

Errors can be divided into two categories: **expected errors** and **uncaught exceptions**:

- **Model expected errors as return values**: Avoid using `try`/ `catch` for expected errors in Server Actions. Use [`useActionState`](https://react.dev/reference/react/useActionState) to manage these errors and return them to the client.
- **Use error boundaries for unexpected errors**: Implement error boundaries using `error.tsx` and `global-error.tsx` files to handle unexpected errors and provide a fallback UI.

## [Handling Expected Errors](https://nextjs.org/docs/app/building-your-application/routing/error-handling\#handling-expected-errors)

Expected errors are those that can occur during the normal operation of the application, such as those from [server-side form validation](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations#server-side-form-validation) or failed requests. These errors should be handled explicitly and returned to the client.

### [Handling Expected Errors from Server Actions](https://nextjs.org/docs/app/building-your-application/routing/error-handling\#handling-expected-errors-from-server-actions)

Use the `useActionState` hook to manage the state of Server Actions, including handling errors. This approach avoids `try`/ `catch` blocks for expected errors, which should be modeled as return values rather than thrown exceptions.

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { redirect } from 'next/navigation'

export async function createUser(prevState: any, formData: FormData) {
  const res = await fetch('https://...')
  const json = await res.json()

  if (!res.ok) {
    return { message: 'Please enter a valid email' }
  }

  redirect('/dashboard')
}
```

Then, you can pass your action to the `useActionState` hook and use the returned `state` to display an error message.

app/ui/signup.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useActionState } from 'react'
import { createUser } from '@/app/actions'

const initialState = {
  message: '',
}

export function Signup() {
  const [state, formAction, pending] = useActionState(createUser, initialState)

  return (
    <form action={formAction}>
      <label htmlFor="email">Email</label>
      <input type="text" id="email" name="email" required />
      {/* ... */}
      <p aria-live="polite">{state?.message}</p>
      <button disabled={pending}>Sign up</button>
    </form>
  )
}
```

You could also use the returned state to display a toast message from the client component.

### [Handling Expected Errors from Server Components](https://nextjs.org/docs/app/building-your-application/routing/error-handling\#handling-expected-errors-from-server-components)

When fetching data inside of a Server Component, you can use the response to conditionally render an error message or [`redirect`](https://nextjs.org/docs/app/building-your-application/routing/redirecting#redirect-function).

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Page() {
  const res = await fetch(`https://...`)
  const data = await res.json()

  if (!res.ok) {
    return 'There was an error.'
  }

  return '...'
}
```

## [Uncaught Exceptions](https://nextjs.org/docs/app/building-your-application/routing/error-handling\#uncaught-exceptions)

Uncaught exceptions are unexpected errors that indicate bugs or issues that should not occur during the normal flow of your application. These should be handled by throwing errors, which will then be caught by error boundaries.

- **Common:** Handle uncaught errors below the root layout with `error.js`.
- **Optional:** Handle granular uncaught errors with nested `error.js` files (e.g. `app/dashboard/error.js`)
- **Uncommon:** Handle uncaught errors in the root layout with `global-error.js`.

### [Using Error Boundaries](https://nextjs.org/docs/app/building-your-application/routing/error-handling\#using-error-boundaries)

Next.js uses error boundaries to handle uncaught exceptions. Error boundaries catch errors in their child components and display a fallback UI instead of the component tree that crashed.

Create an error boundary by adding an `error.tsx` file inside a route segment and exporting a React component:

app/dashboard/error.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client' // Error boundaries must be Client Components

import { useEffect } from 'react'

export default function Error({
  error,
  reset,
}: {
  error: Error & { digest?: string }
  reset: () => void
}) {
  useEffect(() => {
    // Log the error to an error reporting service
    console.error(error)
  }, [error])

  return (
    <div>
      <h2>Something went wrong!</h2>
      <button
        onClick={
          // Attempt to recover by trying to re-render the segment
          () => reset()
        }
      >
        Try again
      </button>
    </div>
  )
}
```

If you want errors to bubble up to the parent error boundary, you can `throw` when rendering the `error` component.

### [Handling Errors in Nested Routes](https://nextjs.org/docs/app/building-your-application/routing/error-handling\#handling-errors-in-nested-routes)

Errors will bubble up to the nearest parent error boundary. This allows for granular error handling by placing `error.tsx` files at different levels in the [route hierarchy](https://nextjs.org/docs/app/getting-started/project-structure#component-hierarchy).

![Nested Error Component Hierarchy](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fnested-error-component-hierarchy.png&w=3840&q=75)![Nested Error Component Hierarchy](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fnested-error-component-hierarchy.png&w=3840&q=75)

### [Handling Global Errors](https://nextjs.org/docs/app/building-your-application/routing/error-handling\#handling-global-errors)

While less common, you can handle errors in the root layout using `app/global-error.js`, located in the root app directory, even when leveraging [internationalization](https://nextjs.org/docs/app/building-your-application/routing/internationalization). Global error UI must define its own `<html>` and `<body>` tags, since it is replacing the root layout or template when active.

app/global-error.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client' // Error boundaries must be Client Components

export default function GlobalError({
  error,
  reset,
}: {
  error: Error & { digest?: string }
  reset: () => void
}) {
  return (
    // global-error must include html and body tags
    <html>
      <body>
        <h2>Something went wrong!</h2>
        <button onClick={() => reset()}>Try again</button>
      </body>
    </html>
  )
}
```

## Next Steps

[**error.js** \\
API reference for the error.js special file.](https://nextjs.org/docs/app/api-reference/file-conventions/error)

Was this helpful?

supported.

Send

## Next.js Upgrade Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Building Your Application](https://nextjs.org/docs/app/building-your-application) Upgrading

# Upgrade Guide

Upgrade your application to newer versions of Next.js or migrate from the Pages Router to the App Router.

[**Codemods** \\
Use codemods to upgrade your Next.js codebase when new features are released.](https://nextjs.org/docs/app/building-your-application/upgrading/codemods) [**Canary** \\
Upgrade your Next.js Application to canary and try out new features.](https://nextjs.org/docs/app/building-your-application/upgrading/canary) [**Version 15** \\
Upgrade your Next.js Application from Version 14 to 15.](https://nextjs.org/docs/app/building-your-application/upgrading/version-15) [**Version 14** \\
Upgrade your Next.js Application from Version 13 to 14.](https://nextjs.org/docs/app/building-your-application/upgrading/version-14) [**App Router Migration** \\
Learn how to upgrade your existing Next.js application from the Pages Router to the App Router.](https://nextjs.org/docs/app/building-your-application/upgrading/app-router-migration) [**Migrating from CRA** \\
Learn how to migrate your existing React application from Create React App to Next.js.](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app) [**Migrating from Vite** \\
Learn how to migrate your existing React application from Vite to Next.js.](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite) [**Single-Page Apps** \\
Next.js fully supports building Single-Page Applications (SPAs).](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications)

Was this helpful?

supported.

Send

## Configuring MDX in Next.js
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Configuring](https://nextjs.org/docs/app/building-your-application/configuring) MDX

# Markdown and MDX

[Markdown](https://daringfireball.net/projects/markdown/syntax) is a lightweight markup language used to format text. It allows you to write using plain text syntax and convert it to structurally valid HTML. It's commonly used for writing content on websites and blogs.

You write...

```code-block_code__isn_V
I **love** using [Next.js](https://nextjs.org/)
```

Output:

```code-block_code__isn_V
<p>I <strong>love</strong> using <a href="https://nextjs.org/">Next.js</a></p>
```

[MDX](https://mdxjs.com/) is a superset of markdown that lets you write [JSX](https://react.dev/learn/writing-markup-with-jsx) directly in your markdown files. It is a powerful way to add dynamic interactivity and embed React components within your content.

Next.js can support both local MDX content inside your application, as well as remote MDX files fetched dynamically on the server. The Next.js plugin handles transforming markdown and React components into HTML, including support for usage in Server Components (the default in App Router).

> **Good to know**: View the [Portfolio Starter Kit](https://vercel.com/templates/next.js/portfolio-starter-kit) template for a complete working example.

## [Install dependencies](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#install-dependencies)

The `@next/mdx` package, and related packages, are used to configure Next.js so it can process markdown and MDX. **It sources data from local files**, allowing you to create pages with a `.md` or `.mdx` extension, directly in your `/pages` or `/app` directory.

Install these packages to render MDX with Next.js:

Terminal

```code-block_code__isn_V
npm install @next/mdx @mdx-js/loader @mdx-js/react @types/mdx
```

## [Configure `next.config.mjs`](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#configure-nextconfigmjs)

Update the `next.config.mjs` file at your project's root to configure it to use MDX:

next.config.mjs

```code-block_code__isn_V
import createMDX from '@next/mdx'

/** @type {import('next').NextConfig} */
const nextConfig = {
  // Configure `pageExtensions` to include markdown and MDX files
  pageExtensions: ['js', 'jsx', 'md', 'mdx', 'ts', 'tsx'],
  // Optionally, add any other Next.js config below
}

const withMDX = createMDX({
  // Add markdown plugins here, as desired
})

// Merge MDX config with Next.js config
export default withMDX(nextConfig)
```

This allows `.md` and `.mdx` files to act as pages, routes, or imports in your application.

## [Add an `mdx-components.tsx` file](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#add-an-mdx-componentstsx-file)

Create an `mdx-components.tsx` (or `.js`) file in the root of your project to define global MDX Components. For example, at the same level as `pages` or `app`, or inside `src` if applicable.

mdx-components.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { MDXComponents } from 'mdx/types'

export function useMDXComponents(components: MDXComponents): MDXComponents {
  return {
    ...components,
  }
}
```

> **Good to know**:
>
> - `mdx-components.tsx` is **required** to use `@next/mdx` with App Router and will not work without it.
> - Learn more about the [`mdx-components.tsx` file convention](https://nextjs.org/docs/app/api-reference/file-conventions/mdx-components).
> - Learn how to [use custom styles and components](https://nextjs.org/docs/app/building-your-application/configuring/mdx#using-custom-styles-and-components).

## [Rendering MDX](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#rendering-mdx)

You can render MDX using Next.js's file based routing or by importing MDX files into other pages.

### [Using file based routing](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#using-file-based-routing)

When using file based routing, you can use MDX pages like any other page.

In App Router apps, that includes being able to use [metadata](https://nextjs.org/docs/app/building-your-application/optimizing/metadata).

Create a new MDX page within the `/app` directory:

```code-block_code__isn_V
  my-project
  ├── app
  │   └── mdx-page
  │       └── page.(mdx/md)
  |── mdx-components.(tsx/js)
  └── package.json
```

You can use MDX in these files, and even import React components, directly inside your MDX page:

```code-block_code__isn_V
import { MyComponent } from 'my-component'

# Welcome to my MDX page!

This is some **bold** and _italics_ text.

This is a list in markdown:

- One
- Two
- Three

Checkout my React component:

<MyComponent />
```

Navigating to the `/mdx-page` route should display your rendered MDX page.

### [Using imports](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#using-imports)

Create a new page within the `/app` directory and an MDX file wherever you'd like:

```code-block_code__isn_V
  my-project
  ├── app
  │   └── mdx-page
  │       └── page.(tsx/js)
  ├── markdown
  │   └── welcome.(mdx/md)
  |── mdx-components.(tsx/js)
  └── package.json
```

You can use MDX in these files, and even import React components, directly inside your MDX page:

Import the MDX file inside the page to display the content:

app/mdx-page/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Welcome from '@/markdown/welcome.mdx'

export default function Page() {
  return <Welcome />
}
```

Navigating to the `/mdx-page` route should display your rendered MDX page.

### [Using dynamic imports](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#using-dynamic-imports)

You can import dynamic MDX components instead of using filesystem routing for MDX files.

For example, you can have a dynamic route segment which loads MDX components from a separate directory:

![Route segments for dynamic MDX components](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fmdx-files.png&w=3840&q=75)![Route segments for dynamic MDX components](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fmdx-files.png&w=3840&q=75)

[`generateStaticParams`](https://nextjs.org/docs/app/api-reference/functions/generate-static-params) can be used to prerender the provided routes. By marking `dynamicParams` as `false`, accessing a route not defined in `generateStaticParams` will 404.

app/blog/\[slug\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Page({
  params,
}: {
  params: Promise<{ slug: string }>
}) {
  const { slug } = await params
  const { default: Post } = await import(`@/content/${slug}.mdx`)

  return <Post />
}

export function generateStaticParams() {
  return [{ slug: 'welcome' }, { slug: 'about' }]
}

export const dynamicParams = false
```

> **Good to know**: Ensure you specify the `.mdx` file extension in your import. While it is not required to use [module path aliases](https://nextjs.org/docs/app/getting-started/installation#set-up-absolute-imports-and-module-path-aliases) (e.g., `@/content`), it does simplify your import path.

## [Using custom styles and components](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#using-custom-styles-and-components)

Markdown, when rendered, maps to native HTML elements. For example, writing the following markdown:

```code-block_code__isn_V
## This is a heading

This is a list in markdown:

- One
- Two
- Three
```

Generates the following HTML:

```code-block_code__isn_V
<h2>This is a heading</h2>

<p>This is a list in markdown:</p>

<ul>
  <li>One</li>
  <li>Two</li>
  <li>Three</li>
</ul>
```

To style your markdown, you can provide custom components that map to the generated HTML elements. Styles and components can be implemented globally, locally, and with shared layouts.

### [Global styles and components](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#global-styles-and-components)

Adding styles and components in `mdx-components.tsx` will affect _all_ MDX files in your application.

mdx-components.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { MDXComponents } from 'mdx/types'
import Image, { ImageProps } from 'next/image'

// This file allows you to provide custom React components
// to be used in MDX files. You can import and use any
// React component you want, including inline styles,
// components from other libraries, and more.

export function useMDXComponents(components: MDXComponents): MDXComponents {
  return {
    // Allows customizing built-in components, e.g. to add styling.
    h1: ({ children }) => (
      <h1 style={{ color: 'red', fontSize: '48px' }}>{children}</h1>
    ),
    img: (props) => (
      <Image
        sizes="100vw"
        style={{ width: '100%', height: 'auto' }}
        {...(props as ImageProps)}
      />
    ),
    ...components,
  }
}
```

### [Local styles and components](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#local-styles-and-components)

You can apply local styles and components to specific pages by passing them into imported MDX components. These will merge with and override [global styles and components](https://nextjs.org/docs/app/building-your-application/configuring/mdx#global-styles-and-components).

app/mdx-page/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Welcome from '@/markdown/welcome.mdx'

function CustomH1({ children }) {
  return <h1 style={{ color: 'blue', fontSize: '100px' }}>{children}</h1>
}

const overrideComponents = {
  h1: CustomH1,
}

export default function Page() {
  return <Welcome components={overrideComponents} />
}
```

### [Shared layouts](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#shared-layouts)

To share a layout across MDX pages, you can use the [built-in layouts support](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#layouts) with the App Router.

app/mdx-page/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function MdxLayout({ children }: { children: React.ReactNode }) {
  // Create any shared layout or styles here
  return <div style={{ color: 'blue' }}>{children}</div>
}
```

### [Using Tailwind typography plugin](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#using-tailwind-typography-plugin)

If you are using [Tailwind](https://tailwindcss.com/) to style your application, using the [`@tailwindcss/typography` plugin](https://tailwindcss.com/docs/plugins#typography) will allow you to reuse your Tailwind configuration and styles in your markdown files.

The plugin adds a set of `prose` classes that can be used to add typographic styles to content blocks that come from sources, like markdown.

[Install Tailwind typography](https://github.com/tailwindlabs/tailwindcss-typography?tab=readme-ov-file#installation) and use with [shared layouts](https://nextjs.org/docs/app/building-your-application/configuring/mdx#shared-layouts) to add the `prose` you want.

app/mdx-page/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function MdxLayout({ children }: { children: React.ReactNode }) {
  // Create any shared layout or styles here
  return (
    <div className="prose prose-headings:mt-8 prose-headings:font-semibold prose-headings:text-black prose-h1:text-5xl prose-h2:text-4xl prose-h3:text-3xl prose-h4:text-2xl prose-h5:text-xl prose-h6:text-lg dark:prose-headings:text-white">
      {children}
    </div>
  )
}
```

## [Frontmatter](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#frontmatter)

Frontmatter is a YAML like key/value pairing that can be used to store data about a page. `@next/mdx` does **not** support frontmatter by default, though there are many solutions for adding frontmatter to your MDX content, such as:

- [remark-frontmatter](https://github.com/remarkjs/remark-frontmatter)
- [remark-mdx-frontmatter](https://github.com/remcohaszing/remark-mdx-frontmatter)
- [gray-matter](https://github.com/jonschlinkert/gray-matter)

`@next/mdx` **does** allow you to use exports like any other JavaScript component:

Metadata can now be referenced outside of the MDX file:

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import BlogPost, { metadata } from '@/content/blog-post.mdx'

export default function Page() {
  console.log('metadata: ', metadata)
  //=> { author: 'John Doe' }
  return <BlogPost />
}
```

A common use case for this is when you want to iterate over a collection of MDX and extract data. For example, creating a blog index page from all blog posts. You can use packages like [Node's `fs` module](https://nodejs.org/api/fs.html) or [globby](https://www.npmjs.com/package/globby) to read a directory of posts and extract the metadata.

> **Good to know**:
>
> - Using `fs`, `globby`, etc. can only be used server-side.
> - View the [Portfolio Starter Kit](https://vercel.com/templates/next.js/portfolio-starter-kit) template for a complete working example.

## [remark and rehype Plugins](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#remark-and-rehype-plugins)

You can optionally provide remark and rehype plugins to transform the MDX content.

For example, you can use [`remark-gfm`](https://github.com/remarkjs/remark-gfm) to support GitHub Flavored Markdown.

Since the remark and rehype ecosystem is ESM only, you'll need to use `next.config.mjs` or `next.config.ts` as the configuration file.

next.config.mjs

```code-block_code__isn_V
import remarkGfm from 'remark-gfm'
import createMDX from '@next/mdx'

/** @type {import('next').NextConfig} */
const nextConfig = {
  // Allow .mdx extensions for files
  pageExtensions: ['js', 'jsx', 'md', 'mdx', 'ts', 'tsx'],
  // Optionally, add any other Next.js config below
}

const withMDX = createMDX({
  // Add markdown plugins here, as desired
  options: {
    remarkPlugins: [remarkGfm],
    rehypePlugins: [],
  },
})

// Combine MDX and Next.js config
export default withMDX(nextConfig)
```

### [Using Plugins with Turbopack](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#using-plugins-with-turbopack)

To use plugins with [Turbopack](https://nextjs.org/docs/app/api-reference/turbopack), upgrade to the latest `@next/mdx` and specify plugin names using a string:

next.config.mjs

```code-block_code__isn_V
import createMDX from '@next/mdx'

/** @type {import('next').NextConfig} */
const nextConfig = {
  pageExtensions: ['js', 'jsx', 'md', 'mdx', 'ts', 'tsx'],
}

const withMDX = createMDX({
  options: {
    remarkPlugins: [],
    rehypePlugins: [['rehype-katex', { strict: true, throwOnError: true }]],
  },
})

export default withMDX(nextConfig)
```

> **Good to know**:
>
> remark and rehype plugins without serializable options cannot be used yet with [Turbopack](https://nextjs.org/docs/app/api-reference/turbopack), due to [inability to pass JavaScript functions to Rust](https://github.com/vercel/next.js/issues/71819#issuecomment-2461802968)

## [Remote MDX](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#remote-mdx)

If your MDX files or content lives _somewhere else_, you can fetch it dynamically on the server. This is useful for content stored in a CMS, database, or anywhere else. A popular community package for this use is [`next-mdx-remote`](https://github.com/hashicorp/next-mdx-remote#react-server-components-rsc--nextjs-app-directory-support).

> **Good to know**: Please proceed with caution. MDX compiles to JavaScript and is executed on the server. You should only fetch MDX content from a trusted source, otherwise this can lead to remote code execution (RCE).

The following example uses `next-mdx-remote`:

app/mdx-page-remote/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { MDXRemote } from 'next-mdx-remote/rsc'

export default async function RemoteMdxPage() {
  // MDX text - can be from a database, CMS, fetch, anywhere...
  const res = await fetch('https://...')
  const markdown = await res.text()
  return <MDXRemote source={markdown} />
}
```

Navigating to the `/mdx-page-remote` route should display your rendered MDX.

## [Deep Dive: How do you transform markdown into HTML?](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#deep-dive-how-do-you-transform-markdown-into-html)

React does not natively understand markdown. The markdown plaintext needs to first be transformed into HTML. This can be accomplished with `remark` and `rehype`.

`remark` is an ecosystem of tools around markdown. `rehype` is the same, but for HTML. For example, the following code snippet transforms markdown into HTML:

```code-block_code__isn_V
import { unified } from 'unified'
import remarkParse from 'remark-parse'
import remarkRehype from 'remark-rehype'
import rehypeSanitize from 'rehype-sanitize'
import rehypeStringify from 'rehype-stringify'

main()

async function main() {
  const file = await unified()
    .use(remarkParse) // Convert into markdown AST
    .use(remarkRehype) // Transform to HTML AST
    .use(rehypeSanitize) // Sanitize HTML input
    .use(rehypeStringify) // Convert AST into serialized HTML
    .process('Hello, Next.js!')

  console.log(String(file)) // <p>Hello, Next.js!</p>
}
```

The `remark` and `rehype` ecosystem contains plugins for [syntax highlighting](https://github.com/atomiks/rehype-pretty-code), [linking headings](https://github.com/rehypejs/rehype-autolink-headings), [generating a table of contents](https://github.com/remarkjs/remark-toc), and more.

When using `@next/mdx` as shown above, you **do not** need to use `remark` or `rehype` directly, as it is handled for you. We're describing it here for a deeper understanding of what the `@next/mdx` package is doing underneath.

## [Using the Rust-based MDX compiler (experimental)](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#using-the-rust-based-mdx-compiler-experimental)

Next.js supports a new MDX compiler written in Rust. This compiler is still experimental and is not recommended for production use. To use the new compiler, you need to configure `next.config.js` when you pass it to `withMDX`:

next.config.js

```code-block_code__isn_V
module.exports = withMDX({
  experimental: {
    mdxRs: true,
  },
})
```

`mdxRs` also accepts an object to configure how to transform mdx files.

next.config.js

```code-block_code__isn_V
module.exports = withMDX({
  experimental: {
    mdxRs: {
      jsxRuntime?: string            // Custom jsx runtime
      jsxImportSource?: string       // Custom jsx import source,
      mdxType?: 'gfm' | 'commonmark' // Configure what kind of mdx syntax will be used to parse & transform
    },
  },
})
```

## [Helpful Links](https://nextjs.org/docs/app/building-your-application/configuring/mdx\#helpful-links)

- [MDX](https://mdxjs.com/)
- [`@next/mdx`](https://www.npmjs.com/package/@next/mdx)
- [remark](https://github.com/remarkjs/remark)
- [rehype](https://github.com/rehypejs/rehype)
- [Markdoc](https://markdoc.dev/docs/nextjs)

Was this helpful?

supported.

Send

## Content Security Policy
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Configuring](https://nextjs.org/docs/app/building-your-application/configuring) Content Security Policy

# Content Security Policy

[Content Security Policy (CSP)](https://developer.mozilla.org/docs/Web/HTTP/CSP) is important to guard your Next.js application against various security threats such as cross-site scripting (XSS), clickjacking, and other code injection attacks.

By using CSP, developers can specify which origins are permissible for content sources, scripts, stylesheets, images, fonts, objects, media (audio, video), iframes, and more.

Examples

- [Strict CSP](https://github.com/vercel/next.js/tree/canary/examples/with-strict-csp)

## [Nonces](https://nextjs.org/docs/app/building-your-application/configuring/content-security-policy\#nonces)

A [nonce](https://developer.mozilla.org/docs/Web/HTML/Global_attributes/nonce) is a unique, random string of characters created for a one-time use. It is used in conjunction with CSP to selectively allow certain inline scripts or styles to execute, bypassing strict CSP directives.

### [Why use a nonce?](https://nextjs.org/docs/app/building-your-application/configuring/content-security-policy\#why-use-a-nonce)

Even though CSPs are designed to block malicious scripts, there are legitimate scenarios where inline scripts are necessary. In such cases, nonces offer a way to allow these scripts to execute if they have the correct nonce.

### [Adding a nonce with Middleware](https://nextjs.org/docs/app/building-your-application/configuring/content-security-policy\#adding-a-nonce-with-middleware)

[Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware) enables you to add headers and generate nonces before the page renders.

Every time a page is viewed, a fresh nonce should be generated. This means that you **must use dynamic rendering to add nonces**.

For example:

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextRequest, NextResponse } from 'next/server'

export function middleware(request: NextRequest) {
  const nonce = Buffer.from(crypto.randomUUID()).toString('base64')
  const cspHeader = `
    default-src 'self';
    script-src 'self' 'nonce-${nonce}' 'strict-dynamic';
    style-src 'self' 'nonce-${nonce}';
    img-src 'self' blob: data:;
    font-src 'self';
    object-src 'none';
    base-uri 'self';
    form-action 'self';
    frame-ancestors 'none';
    upgrade-insecure-requests;
`
  // Replace newline characters and spaces
  const contentSecurityPolicyHeaderValue = cspHeader
    .replace(/\s{2,}/g, ' ')
    .trim()

  const requestHeaders = new Headers(request.headers)
  requestHeaders.set('x-nonce', nonce)

  requestHeaders.set(
    'Content-Security-Policy',
    contentSecurityPolicyHeaderValue
  )

  const response = NextResponse.next({
    request: {
      headers: requestHeaders,
    },
  })
  response.headers.set(
    'Content-Security-Policy',
    contentSecurityPolicyHeaderValue
  )

  return response
}
```

By default, Middleware runs on all requests. You can filter Middleware to run on specific paths using a [`matcher`](https://nextjs.org/docs/app/building-your-application/routing/middleware#matcher).

We recommend ignoring matching prefetches (from `next/link`) and static assets that don't need the CSP header.

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export const config = {
  matcher: [\
    /*\
     * Match all request paths except for the ones starting with:\
     * - api (API routes)\
     * - _next/static (static files)\
     * - _next/image (image optimization files)\
     * - favicon.ico (favicon file)\
     */\
    {\
      source: '/((?!api|_next/static|_next/image|favicon.ico).*)',\
      missing: [\
        { type: 'header', key: 'next-router-prefetch' },\
        { type: 'header', key: 'purpose', value: 'prefetch' },\
      ],\
    },\
  ],
}
```

### [Reading the nonce](https://nextjs.org/docs/app/building-your-application/configuring/content-security-policy\#reading-the-nonce)

You can now read the nonce from a [Server Component](https://nextjs.org/docs/app/building-your-application/rendering/server-components) using [`headers`](https://nextjs.org/docs/app/api-reference/functions/headers):

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { headers } from 'next/headers'
import Script from 'next/script'

export default async function Page() {
  const nonce = (await headers()).get('x-nonce')

  return (
    <Script
      src="https://www.googletagmanager.com/gtag/js"
      strategy="afterInteractive"
      nonce={nonce}
    />
  )
}
```

## [Without Nonces](https://nextjs.org/docs/app/building-your-application/configuring/content-security-policy\#without-nonces)

For applications that do not require nonces, you can set the CSP header directly in your [`next.config.js`](https://nextjs.org/docs/app/api-reference/config/next-config-js) file:

next.config.js

```code-block_code__isn_V
const cspHeader = `
    default-src 'self';
    script-src 'self' 'unsafe-eval' 'unsafe-inline';
    style-src 'self' 'unsafe-inline';
    img-src 'self' blob: data:;
    font-src 'self';
    object-src 'none';
    base-uri 'self';
    form-action 'self';
    frame-ancestors 'none';
    upgrade-insecure-requests;
`

module.exports = {
  async headers() {
    return [\
      {\
        source: '/(.*)',\
        headers: [\
          {\
            key: 'Content-Security-Policy',\
            value: cspHeader.replace(/\n/g, ''),\
          },\
        ],\
      },\
    ]
  },
}
```

## [Version History](https://nextjs.org/docs/app/building-your-application/configuring/content-security-policy\#version-history)

We recommend using `v13.4.20+` of Next.js to properly handle and apply nonces.

## Next Steps

[**Middleware** \\
Learn how to use Middleware to run code before a request is completed.](https://nextjs.org/docs/app/building-your-application/routing/middleware) [**headers** \\
API reference for the headers function.](https://nextjs.org/docs/app/api-reference/functions/headers)

Was this helpful?

supported.

Send

## Next.js Script Component
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [Components](https://nextjs.org/docs/app/api-reference/components) Script

# Script

This API reference will help you understand how to use [props](https://nextjs.org/docs/app/api-reference/components/script#props) available for the Script Component. For features and usage, please see the [Optimizing Scripts](https://nextjs.org/docs/app/building-your-application/optimizing/scripts) page.

app/dashboard/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Script from 'next/script'

export default function Dashboard() {
  return (
    <>
      <Script src="https://example.com/script.js" />
    </>
  )
}
```

## [Props](https://nextjs.org/docs/app/api-reference/components/script\#props)

Here's a summary of the props available for the Script Component:

| Prop | Example | Type | Required |
| --- | --- | --- | --- |
| [`src`](https://nextjs.org/docs/app/api-reference/components/script#src) | `src="http://example.com/script"` | String | Required unless inline script is used |
| [`strategy`](https://nextjs.org/docs/app/api-reference/components/script#strategy) | `strategy="lazyOnload"` | String | - |
| [`onLoad`](https://nextjs.org/docs/app/api-reference/components/script#onload) | `onLoad={onLoadFunc}` | Function | - |
| [`onReady`](https://nextjs.org/docs/app/api-reference/components/script#onready) | `onReady={onReadyFunc}` | Function | - |
| [`onError`](https://nextjs.org/docs/app/api-reference/components/script#onerror) | `onError={onErrorFunc}` | Function | - |

## [Required Props](https://nextjs.org/docs/app/api-reference/components/script\#required-props)

The `<Script />` component requires the following properties.

### [`src`](https://nextjs.org/docs/app/api-reference/components/script\#src)

A path string specifying the URL of an external script. This can be either an absolute external URL or an internal path. The `src` property is required unless an inline script is used.

## [Optional Props](https://nextjs.org/docs/app/api-reference/components/script\#optional-props)

The `<Script />` component accepts a number of additional properties beyond those which are required.

### [`strategy`](https://nextjs.org/docs/app/api-reference/components/script\#strategy)

The loading strategy of the script. There are four different strategies that can be used:

- `beforeInteractive`: Load before any Next.js code and before any page hydration occurs.
- `afterInteractive`: ( **default**) Load early but after some hydration on the page occurs.
- `lazyOnload`: Load during browser idle time.
- `worker`: (experimental) Load in a web worker.

### [`beforeInteractive`](https://nextjs.org/docs/app/api-reference/components/script\#beforeinteractive)

Scripts that load with the `beforeInteractive` strategy are injected into the initial HTML from the server, downloaded before any Next.js module, and executed in the order they are placed.

Scripts denoted with this strategy are preloaded and fetched before any first-party code, but their execution **does not block page hydration from occurring**.

`beforeInteractive` scripts must be placed inside the root layout ( `app/layout.tsx`) and are designed to load scripts that are needed by the entire site (i.e. the script will load when any page in the application has been loaded server-side).

**This strategy should only be used for critical scripts that need to be fetched as soon as possible.**

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Script from 'next/script'

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en">
      <body>
        {children}
        <Script
          src="https://example.com/script.js"
          strategy="beforeInteractive"
        />
      </body>
    </html>
  )
}
```

> **Good to know**: Scripts with `beforeInteractive` will always be injected inside the `head` of the HTML document regardless of where it's placed in the component.

Some examples of scripts that should be fetched as soon as possible with `beforeInteractive` include:

- Bot detectors
- Cookie consent managers

### [`afterInteractive`](https://nextjs.org/docs/app/api-reference/components/script\#afterinteractive)

Scripts that use the `afterInteractive` strategy are injected into the HTML client-side and will load after some (or all) hydration occurs on the page. **This is the default strategy** of the Script component and should be used for any script that needs to load as soon as possible but not before any first-party Next.js code.

`afterInteractive` scripts can be placed inside of any page or layout and will only load and execute when that page (or group of pages) is opened in the browser.

app/page.js

```code-block_code__isn_V
import Script from 'next/script'

export default function Page() {
  return (
    <>
      <Script src="https://example.com/script.js" strategy="afterInteractive" />
    </>
  )
}
```

Some examples of scripts that are good candidates for `afterInteractive` include:

- Tag managers
- Analytics

### [`lazyOnload`](https://nextjs.org/docs/app/api-reference/components/script\#lazyonload)

Scripts that use the `lazyOnload` strategy are injected into the HTML client-side during browser idle time and will load after all resources on the page have been fetched. This strategy should be used for any background or low priority scripts that do not need to load early.

`lazyOnload` scripts can be placed inside of any page or layout and will only load and execute when that page (or group of pages) is opened in the browser.

app/page.js

```code-block_code__isn_V
import Script from 'next/script'

export default function Page() {
  return (
    <>
      <Script src="https://example.com/script.js" strategy="lazyOnload" />
    </>
  )
}
```

Examples of scripts that do not need to load immediately and can be fetched with `lazyOnload` include:

- Chat support plugins
- Social media widgets

### [`worker`](https://nextjs.org/docs/app/api-reference/components/script\#worker)

> **Warning:** The `worker` strategy is not yet stable and does not yet work with the App Router. Use with caution.

Scripts that use the `worker` strategy are off-loaded to a web worker in order to free up the main thread and ensure that only critical, first-party resources are processed on it. While this strategy can be used for any script, it is an advanced use case that is not guaranteed to support all third-party scripts.

To use `worker` as a strategy, the `nextScriptWorkers` flag must be enabled in `next.config.js`:

next.config.js

```code-block_code__isn_V
module.exports = {
  experimental: {
    nextScriptWorkers: true,
  },
}
```

`worker` scripts can **only currently be used in the `pages/` directory**:

pages/home.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Script from 'next/script'

export default function Home() {
  return (
    <>
      <Script src="https://example.com/script.js" strategy="worker" />
    </>
  )
}
```

### [`onLoad`](https://nextjs.org/docs/app/api-reference/components/script\#onload)

> **Warning:** `onLoad` does not yet work with Server Components and can only be used in Client Components. Further, `onLoad` can't be used with `beforeInteractive` – consider using `onReady` instead.

Some third-party scripts require users to run JavaScript code once after the script has finished loading in order to instantiate content or call a function. If you are loading a script with either `afterInteractive` or `lazyOnload` as a loading strategy, you can execute code after it has loaded using the `onLoad` property.

Here's an example of executing a lodash method only after the library has been loaded.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import Script from 'next/script'

export default function Page() {
  return (
    <>
      <Script
        src="https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.20/lodash.min.js"
        onLoad={() => {
          console.log(_.sample([1, 2, 3, 4]))
        }}
      />
    </>
  )
}
```

### [`onReady`](https://nextjs.org/docs/app/api-reference/components/script\#onready)

> **Warning:** `onReady` does not yet work with Server Components and can only be used in Client Components.

Some third-party scripts require users to run JavaScript code after the script has finished loading and every time the component is mounted (after a route navigation for example). You can execute code after the script's load event when it first loads and then after every subsequent component re-mount using the `onReady` property.

Here's an example of how to re-instantiate a Google Maps JS embed every time the component is mounted:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useRef } from 'react'
import Script from 'next/script'

export default function Page() {
  const mapRef = useRef()

  return (
    <>
      <div ref={mapRef}></div>
      <Script
        id="google-maps"
        src="https://maps.googleapis.com/maps/api/js"
        onReady={() => {
          new google.maps.Map(mapRef.current, {
            center: { lat: -34.397, lng: 150.644 },
            zoom: 8,
          })
        }}
      />
    </>
  )
}
```

### [`onError`](https://nextjs.org/docs/app/api-reference/components/script\#onerror)

> **Warning:** `onError` does not yet work with Server Components and can only be used in Client Components. `onError` cannot be used with the `beforeInteractive` loading strategy.

Sometimes it is helpful to catch when a script fails to load. These errors can be handled with the `onError` property:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import Script from 'next/script'

export default function Page() {
  return (
    <>
      <Script
        src="https://example.com/script.js"
        onError={(e: Error) => {
          console.error('Script failed to load', e)
        }}
      />
    </>
  )
}
```

## [Version History](https://nextjs.org/docs/app/api-reference/components/script\#version-history)

| Version | Changes |
| --- | --- |
| `v13.0.0` | `beforeInteractive` and `afterInteractive` is modified to support `app`. |
| `v12.2.4` | `onReady` prop added. |
| `v12.2.2` | Allow `next/script` with `beforeInteractive` to be placed in `_document`. |
| `v11.0.0` | `next/script` introduced. |

Was this helpful?

supported.

Send

## Jest Testing Setup
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Testing](https://nextjs.org/docs/app/building-your-application/testing) Jest

# Setting up Jest with Next.js

Jest and React Testing Library are frequently used together for **Unit Testing** and **Snapshot Testing**. This guide will show you how to set up Jest with Next.js and write your first tests.

> **Good to know:** Since `async` Server Components are new to the React ecosystem, Jest currently does not support them. While you can still run **unit tests** for synchronous Server and Client Components, we recommend using an **E2E tests** for `async` components.

## [Quickstart](https://nextjs.org/docs/app/building-your-application/testing/jest\#quickstart)

You can use `create-next-app` with the Next.js [with-jest](https://github.com/vercel/next.js/tree/canary/examples/with-jest) example to quickly get started:

Terminal

```code-block_code__isn_V
npx create-next-app@latest --example with-jest with-jest-app
```

## [Manual setup](https://nextjs.org/docs/app/building-your-application/testing/jest\#manual-setup)

Since the release of [Next.js 12](https://nextjs.org/blog/next-12), Next.js now has built-in configuration for Jest.

To set up Jest, install `jest` and the following packages as dev dependencies:

Terminal

```code-block_code__isn_V
npm install -D jest jest-environment-jsdom @testing-library/react @testing-library/dom @testing-library/jest-dom ts-node
# or
yarn add -D jest jest-environment-jsdom @testing-library/react @testing-library/dom @testing-library/jest-dom ts-node
# or
pnpm install -D jest jest-environment-jsdom @testing-library/react @testing-library/dom @testing-library/jest-dom ts-node
```

Generate a basic Jest configuration file by running the following command:

Terminal

```code-block_code__isn_V
npm init jest@latest
# or
yarn create jest@latest
# or
pnpm create jest@latest
```

This will take you through a series of prompts to setup Jest for your project, including automatically creating a `jest.config.ts|js` file.

Update your config file to use `next/jest`. This transformer has all the necessary configuration options for Jest to work with Next.js:

jest.config.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { Config } from 'jest'
import nextJest from 'next/jest.js'

const createJestConfig = nextJest({
  // Provide the path to your Next.js app to load next.config.js and .env files in your test environment
  dir: './',
})

// Add any custom config to be passed to Jest
const config: Config = {
  coverageProvider: 'v8',
  testEnvironment: 'jsdom',
  // Add more setup options before each test is run
  // setupFilesAfterEnv: ['<rootDir>/jest.setup.ts'],
}

// createJestConfig is exported this way to ensure that next/jest can load the Next.js config which is async
export default createJestConfig(config)
```

Under the hood, `next/jest` is automatically configuring Jest for you, including:

- Setting up `transform` using the [Next.js Compiler](https://nextjs.org/docs/architecture/nextjs-compiler).
- Auto mocking stylesheets ( `.css`, `.module.css`, and their scss variants), image imports and [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts).
- Loading `.env` (and all variants) into `process.env`.
- Ignoring `node_modules` from test resolving and transforms.
- Ignoring `.next` from test resolving.
- Loading `next.config.js` for flags that enable SWC transforms.

> **Good to know**: To test environment variables directly, load them manually in a separate setup script or in your `jest.config.ts` file. For more information, please see [Test Environment Variables](https://nextjs.org/docs/app/building-your-application/configuring/environment-variables#test-environment-variables).

## [Optional: Handling Absolute Imports and Module Path Aliases](https://nextjs.org/docs/app/building-your-application/testing/jest\#optional-handling-absolute-imports-and-module-path-aliases)

If your project is using [Module Path Aliases](https://nextjs.org/docs/app/getting-started/installation#set-up-absolute-imports-and-module-path-aliases), you will need to configure Jest to resolve the imports by matching the paths option in the `jsconfig.json` file with the `moduleNameMapper` option in the `jest.config.js` file. For example:

tsconfig.json or jsconfig.json

```code-block_code__isn_V
{
  "compilerOptions": {
    "module": "esnext",
    "moduleResolution": "bundler",
    "baseUrl": "./",
    "paths": {
      "@/components/*": ["components/*"]
    }
  }
}
```

jest.config.js

```code-block_code__isn_V
moduleNameMapper: {
  // ...
  '^@/components/(.*)$': '<rootDir>/components/$1',
}
```

## [Optional: Extend Jest with custom matchers](https://nextjs.org/docs/app/building-your-application/testing/jest\#optional-extend-jest-with-custom-matchers)

`@testing-library/jest-dom` includes a set of convenient [custom matchers](https://github.com/testing-library/jest-dom#custom-matchers) such as `.toBeInTheDocument()` making it easier to write tests. You can import the custom matchers for every test by adding the following option to the Jest configuration file:

jest.config.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
setupFilesAfterEnv: ['<rootDir>/jest.setup.ts']
```

Then, inside `jest.setup`, add the following import:

jest.setup.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import '@testing-library/jest-dom'
```

> **Good to know:** [`extend-expect` was removed in `v6.0`](https://github.com/testing-library/jest-dom/releases/tag/v6.0.0), so if you are using `@testing-library/jest-dom` before version 6, you will need to import `@testing-library/jest-dom/extend-expect` instead.

If you need to add more setup options before each test, you can add them to the `jest.setup` file above.

## [Add a test script to `package.json`](https://nextjs.org/docs/app/building-your-application/testing/jest\#add-a-test-script-to-packagejson)

Finally, add a Jest `test` script to your `package.json` file:

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "test": "jest",
    "test:watch": "jest --watch"
  }
}
```

`jest --watch` will re-run tests when a file is changed. For more Jest CLI options, please refer to the [Jest Docs](https://jestjs.io/docs/cli#reference).

### [Creating your first test](https://nextjs.org/docs/app/building-your-application/testing/jest\#creating-your-first-test)

Your project is now ready to run tests. Create a folder called `__tests__` in your project's root directory.

For example, we can add a test to check if the `<Page />` component successfully renders a heading:

app/page.js

```code-block_code__isn_V
import Link from 'next/link'

export default function Page() {
  return (
    <div>
      <h1>Home</h1>
      <Link href="/about">About</Link>
    </div>
  )
}
```

\_\_tests\_\_/page.test.jsx

```code-block_code__isn_V
import '@testing-library/jest-dom'
import { render, screen } from '@testing-library/react'
import Page from '../app/page'

describe('Page', () => {
  it('renders a heading', () => {
    render(<Page />)

    const heading = screen.getByRole('heading', { level: 1 })

    expect(heading).toBeInTheDocument()
  })
})
```

Optionally, add a [snapshot test](https://jestjs.io/docs/snapshot-testing) to keep track of any unexpected changes in your component:

\_\_tests\_\_/snapshot.js

```code-block_code__isn_V
import { render } from '@testing-library/react'
import Page from '../app/page'

it('renders homepage unchanged', () => {
  const { container } = render(<Page />)
  expect(container).toMatchSnapshot()
})
```

## [Running your tests](https://nextjs.org/docs/app/building-your-application/testing/jest\#running-your-tests)

Then, run the following command to run your tests:

Terminal

```code-block_code__isn_V
npm run test
# or
yarn test
# or
pnpm test
```

## [Additional Resources](https://nextjs.org/docs/app/building-your-application/testing/jest\#additional-resources)

For further reading, you may find these resources helpful:

- [Next.js with Jest example](https://github.com/vercel/next.js/tree/canary/examples/with-jest)
- [Jest Docs](https://jestjs.io/docs/getting-started)
- [React Testing Library Docs](https://testing-library.com/docs/react-testing-library/intro/)
- [Testing Playground](https://testing-playground.com/) \- use good testing practices to match elements.

Was this helpful?

supported.

Send

## Next.js Debugging Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Configuring](https://nextjs.org/docs/app/building-your-application/configuring) Debugging

# Debugging

This documentation explains how you can debug your Next.js frontend and backend code with full source maps support using the [VS Code debugger](https://code.visualstudio.com/docs/editor/debugging), [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools), or [Firefox DevTools](https://firefox-source-docs.mozilla.org/devtools-user/).

Any debugger that can attach to Node.js can also be used to debug a Next.js application. You can find more details in the Node.js [Debugging Guide](https://nodejs.org/en/docs/guides/debugging-getting-started/).

## [Debugging with VS Code](https://nextjs.org/docs/app/building-your-application/configuring/debugging\#debugging-with-vs-code)

Create a file named `.vscode/launch.json` at the root of your project with the following content:

launch.json

```code-block_code__isn_V
{
  "version": "0.2.0",
  "configurations": [\
    {\
      "name": "Next.js: debug server-side",\
      "type": "node-terminal",\
      "request": "launch",\
      "command": "npm run dev"\
    },\
    {\
      "name": "Next.js: debug client-side",\
      "type": "chrome",\
      "request": "launch",\
      "url": "http://localhost:3000"\
    },\
    {\
      "name": "Next.js: debug client-side (Firefox)",\
      "type": "firefox",\
      "request": "launch",\
      "url": "http://localhost:3000",\
      "reAttach": true,\
      "pathMappings": [\
        {\
          "url": "webpack://_N_E",\
          "path": "${workspaceFolder}"\
        }\
      ]\
    },\
    {\
      "name": "Next.js: debug full stack",\
      "type": "node",\
      "request": "launch",\
      "program": "${workspaceFolder}/node_modules/.bin/next",\
      "runtimeArgs": ["--inspect"],\
      "skipFiles": ["<node_internals>/**"],\
      "serverReadyAction": {\
        "action": "debugWithEdge",\
        "killOnServerStop": true,\
        "pattern": "- Local:.+(https?://.+)",\
        "uriFormat": "%s",\
        "webRoot": "${workspaceFolder}"\
      }\
    }\
  ]
}
```

> **Note**: To use Firefox debugging in VS Code, you'll need to install the [Firefox Debugger extension](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug).

`npm run dev` can be replaced with `yarn dev` if you're using Yarn or `pnpm dev` if you're using pnpm.

In the "Next.js: debug full stack" configuration, `serverReadyAction.action` specifies which browser to open when the server is ready. `debugWithEdge` means to launch the Edge browser. If you are using Chrome, change this value to `debugWithChrome`.

If you're [changing the port number](https://nextjs.org/docs/pages/api-reference/cli/next#next-dev-options) your application starts on, replace the `3000` in `http://localhost:3000` with the port you're using instead.

If you're running Next.js from a directory other than root (for example, if you're using Turborepo) then you need to add `cwd` to the server-side and full stack debugging tasks. For example, `"cwd": "${workspaceFolder}/apps/web"`.

Now go to the Debug panel ( `Ctrl+Shift+D` on Windows/Linux, `⇧+⌘+D` on macOS), select a launch configuration, then press `F5` or select **Debug: Start Debugging** from the Command Palette to start your debugging session.

## [Using the Debugger in Jetbrains WebStorm](https://nextjs.org/docs/app/building-your-application/configuring/debugging\#using-the-debugger-in-jetbrains-webstorm)

Click the drop down menu listing the runtime configuration, and click `Edit Configurations...`. Create a `JavaScript Debug` debug configuration with `http://localhost:3000` as the URL. Customize to your liking (e.g. Browser for debugging, store as project file), and click `OK`. Run this debug configuration, and the selected browser should automatically open. At this point, you should have 2 applications in debug mode: the NextJS node application, and the client/browser application.

## [Debugging with Browser DevTools](https://nextjs.org/docs/app/building-your-application/configuring/debugging\#debugging-with-browser-devtools)

### [Client-side code](https://nextjs.org/docs/app/building-your-application/configuring/debugging\#client-side-code)

Start your development server as usual by running `next dev`, `npm run dev`, or `yarn dev`. Once the server starts, open `http://localhost:3000` (or your alternate URL) in your preferred browser.

For Chrome:

- Open Chrome's Developer Tools ( `Ctrl+Shift+J` on Windows/Linux, `⌥+⌘+I` on macOS)
- Go to the **Sources** tab

For Firefox:

- Open Firefox's Developer Tools ( `Ctrl+Shift+I` on Windows/Linux, `⌥+⌘+I` on macOS)
- Go to the **Debugger** tab

In either browser, any time your client-side code reaches a [`debugger`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Statements/debugger) statement, code execution will pause and that file will appear in the debug area. You can also search for files to set breakpoints manually:

- In Chrome: Press `Ctrl+P` on Windows/Linux or `⌘+P` on macOS
- In Firefox: Press `Ctrl+P` on Windows/Linux or `⌘+P` on macOS, or use the file tree in the left panel

Note that when searching, your source files will have paths starting with `webpack://_N_E/./`.

### [Server-side code](https://nextjs.org/docs/app/building-your-application/configuring/debugging\#server-side-code)

To debug server-side Next.js code with browser DevTools, you need to pass the [`--inspect`](https://nodejs.org/api/cli.html#cli_inspect_host_port) flag to the underlying Node.js process:

Terminal

```code-block_code__isn_V
NODE_OPTIONS='--inspect' next dev
```

> **Good to know**: Use `NODE_OPTIONS='--inspect=0.0.0.0'` to allow remote debugging access outside localhost, such as when running the app in a Docker container.

If you're using `npm run dev` or `yarn dev` then you should update the `dev` script on your `package.json`:

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "NODE_OPTIONS='--inspect' next dev"
  }
}
```

Launching the Next.js dev server with the `--inspect` flag will look something like this:

Terminal

```code-block_code__isn_V
Debugger listening on ws://127.0.0.1:9229/0cf90313-350d-4466-a748-cd60f4e47c95
For help, see: https://nodejs.org/en/docs/inspector
ready - started server on 0.0.0.0:3000, url: http://localhost:3000
```

For Chrome:

1. Open a new tab and visit `chrome://inspect`
2. Click **Configure...** to ensure both debugging ports are listed
3. Add both `localhost:9229` and `localhost:9230` if they're not already present
4. Look for your Next.js application in the **Remote Target** section
5. Click **inspect** to open a separate DevTools window
6. Go to the **Sources** tab

For Firefox:

1. Open a new tab and visit `about:debugging`
2. Click **This Firefox** in the left sidebar
3. Under **Remote Targets**, find your Next.js application
4. Click **Inspect** to open the debugger
5. Go to the **Debugger** tab

Debugging server-side code works similarly to client-side debugging. When searching for files ( `Ctrl+P`/ `⌘+P`), your source files will have paths starting with `webpack://{application-name}/./` (where `{application-name}` will be replaced with the name of your application according to your `package.json` file).

### [Inspect Server Errors with Browser DevTools](https://nextjs.org/docs/app/building-your-application/configuring/debugging\#inspect-server-errors-with-browser-devtools)

When you encounter an error, inspecting the source code can help trace the root cause of errors.

Next.js will display a Node.js icon underneath the Next.js version indicator on the error overlay. By clicking that icon, the DevTools URL is copied to your clipboard. You can open a new browser tab with that URL to inspect the Next.js server process.

### [Debugging on Windows](https://nextjs.org/docs/app/building-your-application/configuring/debugging\#debugging-on-windows)

Windows users may run into an issue when using `NODE_OPTIONS='--inspect'` as that syntax is not supported on Windows platforms. To get around this, install the [`cross-env`](https://www.npmjs.com/package/cross-env) package as a development dependency ( `-D` with `npm` and `yarn`) and replace the `dev` script with the following.

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "cross-env NODE_OPTIONS='--inspect' next dev"
  }
}
```

`cross-env` will set the `NODE_OPTIONS` environment variable regardless of which platform you are on (including Mac, Linux, and Windows) and allow you to debug consistently across devices and operating systems.

> **Good to know**: Ensure Windows Defender is disabled on your machine. This external service will check _every file read_, which has been reported to greatly increase Fast Refresh time with `next dev`. This is a known issue, not related to Next.js, but it does affect Next.js development.

## [More information](https://nextjs.org/docs/app/building-your-application/configuring/debugging\#more-information)

To learn more about how to use a JavaScript debugger, take a look at the following documentation:

- [Node.js debugging in VS Code: Breakpoints](https://code.visualstudio.com/docs/nodejs/nodejs-debugging#_breakpoints)
- [Chrome DevTools: Debug JavaScript](https://developers.google.com/web/tools/chrome-devtools/javascript)
- [Firefox DevTools: Debugger](https://firefox-source-docs.mozilla.org/devtools-user/debugger/)

Was this helpful?

supported.

Send

## Next.js Deployment Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Building Your Application](https://nextjs.org/docs/app/building-your-application) Deploying

# Deploying

Congratulations, it's time to ship to production.

You can deploy [managed Next.js with Vercel](https://nextjs.org/docs/app/building-your-application/deploying#managed-nextjs-with-vercel), or self-host on a Node.js server, Docker image, or even static HTML files. When deploying using `next start`, all Next.js features are supported.

## [Production Builds](https://nextjs.org/docs/app/building-your-application/deploying\#production-builds)

Running `next build` generates an optimized version of your application for production. HTML, CSS, and JavaScript files are created based on your pages. JavaScript is **compiled** and browser bundles are **minified** using the [Next.js Compiler](https://nextjs.org/docs/architecture/nextjs-compiler) to help achieve the best performance and support [all modern browsers](https://nextjs.org/docs/architecture/supported-browsers).

Next.js produces a standard deployment output used by managed and self-hosted Next.js. This ensures all features are supported across both methods of deployment. In the next major version, we will be transforming this output into our [Build Output API specification](https://vercel.com/docs/build-output-api/v3?utm_source=next-site&utm_medium=docs&utm_campaign=next-website).

## [Managed Next.js with Vercel](https://nextjs.org/docs/app/building-your-application/deploying\#managed-nextjs-with-vercel)

[Vercel](https://vercel.com/docs/frameworks/nextjs?utm_source=next-site&utm_medium=docs&utm_campaign=next-website), the creators and maintainers of Next.js, provide managed infrastructure and a developer experience platform for your Next.js applications.

Deploying to Vercel is zero-configuration and provides additional enhancements for scalability, availability, and performance globally. However, all Next.js features are still supported when self-hosted.

Learn more about [Next.js on Vercel](https://vercel.com/docs/frameworks/nextjs?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) or [deploy a template for free](https://vercel.com/templates/next.js?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) to try it out.

## [Self-Hosting](https://nextjs.org/docs/app/building-your-application/deploying\#self-hosting)

You can self-host Next.js in three different ways:

- [A Node.js server](https://nextjs.org/docs/app/building-your-application/deploying#nodejs-server)
- [A Docker container](https://nextjs.org/docs/app/building-your-application/deploying#docker-image)
- [A static export](https://nextjs.org/docs/app/building-your-application/deploying#static-html-export)

> **🎥 Watch:** Learn more about self-hosting Next.js → [YouTube (45 minutes)](https://www.youtube.com/watch?v=sIVL4JMqRfc).

We have community maintained deployment examples with the following providers:

- [Deno](https://github.com/nextjs/deploy-deno)
- [DigitalOcean](https://github.com/nextjs/deploy-digitalocean)
- [Flightcontrol](https://github.com/nextjs/deploy-flightcontrol)
- [Fly.io](https://github.com/nextjs/deploy-fly)
- [GitHub Pages](https://github.com/nextjs/deploy-github-pages)
- [Google Cloud Run](https://github.com/nextjs/deploy-google-cloud-run)
- [Railway](https://github.com/nextjs/deploy-railway)
- [Render](https://github.com/nextjs/deploy-render)
- [SST](https://github.com/nextjs/deploy-sst)

### [Node.js Server](https://nextjs.org/docs/app/building-your-application/deploying\#nodejs-server)

Next.js can be deployed to any hosting provider that supports Node.js. Ensure your `package.json` has the `"build"` and `"start"` scripts:

package.json

```code-block_code__isn_V
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  }
}
```

Then, run `npm run build` to build your application. Finally, run `npm run start` to start the Node.js server. This server supports all Next.js features.

### [Docker Image](https://nextjs.org/docs/app/building-your-application/deploying\#docker-image)

Next.js can be deployed to any hosting provider that supports [Docker](https://www.docker.com/) containers. You can use this approach when deploying to container orchestrators such as [Kubernetes](https://kubernetes.io/) or when running inside a container in any cloud provider.

1. [Install Docker](https://docs.docker.com/get-docker/) on your machine
2. [Clone our example](https://github.com/vercel/next.js/tree/canary/examples/with-docker) (or the [multi-environment example](https://github.com/vercel/next.js/tree/canary/examples/with-docker-multi-env))
3. Build your container: `docker build -t nextjs-docker .`
4. Run your container: `docker run -p 3000:3000 nextjs-docker`

Next.js through Docker supports all Next.js features.

### [Static HTML Export](https://nextjs.org/docs/app/building-your-application/deploying\#static-html-export)

Next.js enables starting as a static site or Single-Page Application (SPA), then later optionally upgrading to use features that require a server.

Since Next.js supports this [static export](https://nextjs.org/docs/app/building-your-application/deploying/static-exports), it can be deployed and hosted on any web server that can serve HTML/CSS/JS static assets. This includes tools like AWS S3, Nginx, or Apache.

Running as a [static export](https://nextjs.org/docs/app/building-your-application/deploying/static-exports) does not support Next.js features that require a server. [Learn more](https://nextjs.org/docs/app/building-your-application/deploying/static-exports#unsupported-features).

> **Good to know:**
>
> - [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components) are supported with static exports.

## [Features](https://nextjs.org/docs/app/building-your-application/deploying\#features)

### [Image Optimization](https://nextjs.org/docs/app/building-your-application/deploying\#image-optimization)

[Image Optimization](https://nextjs.org/docs/app/building-your-application/optimizing/images) through `next/image` works self-hosted with zero configuration when deploying using `next start`. If you would prefer to have a separate service to optimize images, you can [configure an image loader](https://nextjs.org/docs/app/building-your-application/optimizing/images#loaders).

Image Optimization can be used with a [static export](https://nextjs.org/docs/app/building-your-application/deploying/static-exports#image-optimization) by defining a custom image loader in `next.config.js`. Note that images are optimized at runtime, not during the build.

> **Good to know:**
>
> - On glibc-based Linux systems, Image Optimization may require [additional configuration](https://sharp.pixelplumbing.com/install#linux-memory-allocator) to prevent excessive memory usage.
> - Learn more about the [caching behavior of optimized images](https://nextjs.org/docs/app/api-reference/components/image#caching-behavior) and how to configure the TTL.
> - You can also [disable Image Optimization](https://nextjs.org/docs/app/api-reference/components/image#unoptimized) and still retain other benefits of using `next/image` if you prefer. For example, if you are optimizing images yourself separately.

### [Middleware](https://nextjs.org/docs/app/building-your-application/deploying\#middleware)

[Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware) works self-hosted with zero configuration when deploying using `next start`. Since it requires access to the incoming request, it is not supported when using a [static export](https://nextjs.org/docs/app/building-your-application/deploying/static-exports).

Middleware uses a [runtime](https://nextjs.org/docs/app/building-your-application/rendering/edge-and-nodejs-runtimes) that is a subset of all available Node.js APIs to help ensure low latency, since it may run in front of every route or asset in your application. This runtime does not require running “at the edge” and works in a single-region server. Additional configuration and infrastructure are required to run Middleware in multiple regions.

If you are looking to add logic (or use an external package) that requires all Node.js APIs, you might be able to move this logic to a [layout](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#layouts) as a [Server Component](https://nextjs.org/docs/app/building-your-application/rendering/server-components). For example, checking [headers](https://nextjs.org/docs/app/api-reference/functions/headers) and [redirecting](https://nextjs.org/docs/app/api-reference/functions/redirect). You can also use headers, cookies, or query parameters to [redirect](https://nextjs.org/docs/app/api-reference/config/next-config-js/redirects#header-cookie-and-query-matching) or [rewrite](https://nextjs.org/docs/app/api-reference/config/next-config-js/rewrites#header-cookie-and-query-matching) through `next.config.js`. If that does not work, you can also use a [custom server](https://nextjs.org/docs/pages/building-your-application/configuring/custom-server).

### [Environment Variables](https://nextjs.org/docs/app/building-your-application/deploying\#environment-variables)

Next.js can support both build time and runtime environment variables.

**By default, environment variables are only available on the server**. To expose an environment variable to the browser, it must be prefixed with `NEXT_PUBLIC_`. However, these public environment variables will be inlined into the JavaScript bundle during `next build`.

You safely read environment variables on the server during dynamic rendering.

app/page.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { connection } from 'next/server'

export default async function Component() {
  await connection()
  // cookies, headers, and other Dynamic APIs
  // will also opt into dynamic rendering, meaning
  // this env variable is evaluated at runtime
  const value = process.env.MY_VALUE
  // ...
}
```

This allows you to use a singular Docker image that can be promoted through multiple environments with different values.

> **Good to know:**
>
> - You can run code on server startup using the [`register` function](https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation).
> - We do not recommend using the [runtimeConfig](https://nextjs.org/docs/pages/api-reference/config/next-config-js/runtime-configuration) option, as this does not work with the standalone output mode. Instead, we recommend [incrementally adopting](https://nextjs.org/docs/app/building-your-application/upgrading/app-router-migration) the App Router.

### [Caching and ISR](https://nextjs.org/docs/app/building-your-application/deploying\#caching-and-isr)

Next.js can cache responses, generated static pages, build outputs, and other static assets like images, fonts, and scripts.

Caching and revalidating pages (with [Incremental Static Regeneration](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration)) use the **same shared cache**. By default, this cache is stored to the filesystem (on disk) on your Next.js server. **This works automatically when self-hosting** using both the Pages and App Router.

You can configure the Next.js cache location if you want to persist cached pages and data to durable storage, or share the cache across multiple containers or instances of your Next.js application.

#### [Automatic Caching](https://nextjs.org/docs/app/building-your-application/deploying\#automatic-caching)

- Next.js sets the `Cache-Control` header of `public, max-age=31536000, immutable` to truly immutable assets. It cannot be overridden. These immutable files contain a SHA-hash in the file name, so they can be safely cached indefinitely. For example, [Static Image Imports](https://nextjs.org/docs/app/building-your-application/optimizing/images#local-images). You can [configure the TTL](https://nextjs.org/docs/app/api-reference/components/image#caching-behavior) for images.
- Incremental Static Regeneration (ISR) sets the `Cache-Control` header of `s-maxage: <revalidate in getStaticProps>, stale-while-revalidate`. This revalidation time is defined in your [`getStaticProps` function](https://nextjs.org/docs/pages/building-your-application/data-fetching/get-static-props) in seconds. If you set `revalidate: false`, it will default to a one-year cache duration.
- Dynamically rendered pages set a `Cache-Control` header of `private, no-cache, no-store, max-age=0, must-revalidate` to prevent user-specific data from being cached. This applies to both the App Router and Pages Router. This also includes [Draft Mode](https://nextjs.org/docs/app/building-your-application/configuring/draft-mode).

#### [Static Assets](https://nextjs.org/docs/app/building-your-application/deploying\#static-assets)

If you want to host static assets on a different domain or CDN, you can use the `assetPrefix` [configuration](https://nextjs.org/docs/app/api-reference/config/next-config-js/assetPrefix) in `next.config.js`. Next.js will use this asset prefix when retrieving JavaScript or CSS files. Separating your assets to a different domain does come with the downside of extra time spent on DNS and TLS resolution.

[Learn more about `assetPrefix`](https://nextjs.org/docs/app/api-reference/config/next-config-js/assetPrefix).

#### [Configuring Caching](https://nextjs.org/docs/app/building-your-application/deploying\#configuring-caching)

By default, generated cache assets will be stored in memory (defaults to 50mb) and on disk. If you are hosting Next.js using a container orchestration platform like Kubernetes, each pod will have a copy of the cache. To prevent stale data from being shown since the cache is not shared between pods by default, you can configure the Next.js cache to provide a cache handler and disable in-memory caching.

To configure the ISR/Data Cache location when self-hosting, you can configure a custom handler in your `next.config.js` file:

next.config.js

```code-block_code__isn_V
module.exports = {
  cacheHandler: require.resolve('./cache-handler.js'),
  cacheMaxMemorySize: 0, // disable default in-memory caching
}
```

Then, create `cache-handler.js` in the root of your project, for example:

cache-handler.js

```code-block_code__isn_V
const cache = new Map()

module.exports = class CacheHandler {
  constructor(options) {
    this.options = options
  }

  async get(key) {
    // This could be stored anywhere, like durable storage
    return cache.get(key)
  }

  async set(key, data, ctx) {
    // This could be stored anywhere, like durable storage
    cache.set(key, {
      value: data,
      lastModified: Date.now(),
      tags: ctx.tags,
    })
  }

  async revalidateTag(tags) {
    // tags is either a string or an array of strings
    tags = [tags].flat()
    // Iterate over all entries in the cache
    for (let [key, value] of cache) {
      // If the value's tags include the specified tag, delete this entry
      if (value.tags.some((tag) => tags.includes(tag))) {
        cache.delete(key)
      }
    }
  }

  // If you want to have temporary in memory cache for a single request that is reset
  // before the next request you can leverage this method
  resetRequestCache() {}
}
```

Using a custom cache handler will allow you to ensure consistency across all pods hosting your Next.js application. For instance, you can save the cached values anywhere, like [Redis](https://github.com/vercel/next.js/tree/canary/examples/cache-handler-redis) or AWS S3.

> **Good to know:**
>
> - `revalidatePath` is a convenience layer on top of cache tags. Calling `revalidatePath` will call the `revalidateTag` function with a special default tag for the provided page.

### [Build Cache](https://nextjs.org/docs/app/building-your-application/deploying\#build-cache)

Next.js generates an ID during `next build` to identify which version of your application is being served. The same build should be used and boot up multiple containers.

If you are rebuilding for each stage of your environment, you will need to generate a consistent build ID to use between containers. Use the `generateBuildId` command in `next.config.js`:

next.config.js

```code-block_code__isn_V
module.exports = {
  generateBuildId: async () => {
    // This could be anything, using the latest git hash
    return process.env.GIT_HASH
  },
}
```

### [Version Skew](https://nextjs.org/docs/app/building-your-application/deploying\#version-skew)

Next.js will automatically mitigate most instances of [version skew](https://www.industrialempathy.com/posts/version-skew/) and automatically reload the application to retrieve new assets when detected. For example, if there is a mismatch in the `deploymentId`, transitions between pages will perform a hard navigation versus using a prefetched value.

When the application is reloaded, there may be a loss of application state if it's not designed to persist between page navigations. For example, using URL state or local storage would persist state after a page refresh. However, component state like `useState` would be lost in such navigations.

Vercel provides additional [skew protection](https://vercel.com/docs/deployments/skew-protection?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) for Next.js applications to ensure assets and functions from the previous version are still available to older clients, even after the new version is deployed.

You can manually configure the `deploymentId` property in your `next.config.js` file to ensure each request uses either `?dpl` query string or `x-deployment-id` header.

### [Streaming and Suspense](https://nextjs.org/docs/app/building-your-application/deploying\#streaming-and-suspense)

The Next.js App Router supports [streaming responses](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming) when self-hosting. If you are using Nginx or a similar proxy, you will need to configure it to disable buffering to enable streaming.

For example, you can disable buffering in Nginx by setting `X-Accel-Buffering` to `no`:

next.config.js

```code-block_code__isn_V
module.exports = {
  async headers() {
    return [\
      {\
        source: '/:path*{/}?',\
        headers: [\
          {\
            key: 'X-Accel-Buffering',\
            value: 'no',\
          },\
        ],\
      },\
    ]
  },
}
```

### [Partial Prerendering](https://nextjs.org/docs/app/building-your-application/deploying\#partial-prerendering)

[Partial Prerendering (experimental)](https://nextjs.org/docs/app/building-your-application/rendering/partial-prerendering) works by default with Next.js and is not a CDN feature. This includes deployment as a Node.js server (through `next start`) and when used with a Docker container.

### [Usage with CDNs](https://nextjs.org/docs/app/building-your-application/deploying\#usage-with-cdns)

When using a CDN in front on your Next.js application, the page will include `Cache-Control: private` response header when dynamic APIs are accessed. This ensures that the resulting HTML page is marked as non-cachable. If the page is fully prerendered to static, it will include `Cache-Control: public` to allow the page to be cached on the CDN.

If you don't need a mix of both static and dynamic components, you can make your entire route static and cache the output HTML on a CDN. This Automatic Static Optimization is the default behavior when running `next build` if dynamic APIs are not used.

### [`after`](https://nextjs.org/docs/app/building-your-application/deploying\#after)

[`after`](https://nextjs.org/docs/app/api-reference/functions/after) is fully supported when self-hosting with `next start`.

When stopping the server, ensure a graceful shutdown by sending `SIGINT` or `SIGTERM` signals and waiting. This allows the Next.js server to wait until after pending callback functions or promises used inside `after` have finished.

If you want to use `after` on custom infrastructure, check your provider documentation to view support for `after`.

Reference: supporting `after` for serverless platforms
Using `after` in a serverless context requires waiting for asynchronous tasks to finish after the response has been sent. In Next.js and Vercel, this is achieved using a primitive called `waitUntil(promise)`, which extends the lifetime of a serverless invocation until all promises passed to [`waitUntil`](https://vercel.com/docs/functions/functions-api-reference#waituntil) have settled.

If you want your users to be able to run `after`, you will have to provide your implementation of `waitUntil` that behaves in an analogous way.

When `after` is called, Next.js will access `waitUntil` like this:

```code-block_code__isn_V
const RequestContext = globalThis[Symbol.for('@next/request-context')]
const contextValue = RequestContext?.get()
const waitUntil = contextValue?.waitUntil
```

Which means that `globalThis[Symbol.for('@next/request-context')]` is expected to contain an object like this:

```code-block_code__isn_V
type NextRequestContext = {
  get(): NextRequestContextValue | undefined
}

type NextRequestContextValue = {
  waitUntil?: (promise: Promise<any>) => void
}
```

Here is an example of the implementation.

```code-block_code__isn_V
import { AsyncLocalStorage } from 'node:async_hooks'

const RequestContextStorage = new AsyncLocalStorage<NextRequestContextValue>()

// Define and inject the accessor that next.js will use
const RequestContext: NextRequestContext = {
  get() {
    return RequestContextStorage.getStore()
  },
}
globalThis[Symbol.for('@next/request-context')] = RequestContext

const handler = (req, res) => {
  const contextValue = { waitUntil: YOUR_WAITUNTIL }
  // Provide the value
  return RequestContextStorage.run(contextValue, () => nextJsHandler(req, res))
}
```

[**Production Checklist** \\
Recommendations to ensure the best performance and user experience before taking your Next.js application to production.](https://nextjs.org/docs/app/building-your-application/deploying/production-checklist) [**Static Exports** \\
Next.js enables starting as a static site or Single-Page Application (SPA), then later optionally upgrading to use features that require a server.](https://nextjs.org/docs/app/building-your-application/deploying/static-exports) [**Multi-Zones** \\
Learn how to build micro-frontends using Next.js Multi-Zones to deploy multiple Next.js apps under a single domain.](https://nextjs.org/docs/app/building-your-application/deploying/multi-zones)

Was this helpful?

supported.

Send

## Next.js Forbidden File
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[API Reference](https://nextjs.org/docs/app/api-reference) [File Conventions](https://nextjs.org/docs/app/api-reference/file-conventions) forbidden.js

# forbidden.js

This feature is currently experimental and subject to change, it's not recommended for production. Try it out and share your feedback on [GitHub](https://github.com/vercel/next.js/issues).

The **forbidden** file is used to render UI when the [`forbidden`](https://nextjs.org/docs/app/api-reference/functions/forbidden) function is invoked during authentication. Along with allowing you to customize the UI, Next.js will return a `403` status code.

app/forbidden.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Link from 'next/link'

export default function Forbidden() {
  return (
    <div>
      <h2>Forbidden</h2>
      <p>You are not authorized to access this resource.</p>
      <Link href="/">Return Home</Link>
    </div>
  )
}
```

## [Reference](https://nextjs.org/docs/app/api-reference/file-conventions/forbidden\#reference)

### [Props](https://nextjs.org/docs/app/api-reference/file-conventions/forbidden\#props)

`forbidden.js` components do not accept any props.

## [Version History](https://nextjs.org/docs/app/api-reference/file-conventions/forbidden\#version-history)

| Version | Changes |
| --- | --- |
| `v15.1.0` | `forbidden.js` introduced. |

## Next Steps

[**forbidden** \\
API Reference for the forbidden function.](https://nextjs.org/docs/app/api-reference/functions/forbidden)

Was this helpful?

supported.

Send

## Next.js Version 14 Upgrade
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Upgrading](https://nextjs.org/docs/app/building-your-application/upgrading) Version 14

# Version 14

## [Upgrading from 13 to 14](https://nextjs.org/docs/app/building-your-application/upgrading/version-14\#upgrading-from-13-to-14)

To update to Next.js version 14, run the following command using your preferred package manager:

Terminal

```code-block_code__isn_V
npm i next@next-14 react@18 react-dom@18 && npm i eslint-config-next@next-14 -D
```

Terminal

```code-block_code__isn_V
yarn add next@next-14 react@18 react-dom@18 && yarn add eslint-config-next@next-14 -D
```

Terminal

```code-block_code__isn_V
pnpm i next@next-14 react@18 react-dom@18 && pnpm i eslint-config-next@next-14 -D
```

Terminal

```code-block_code__isn_V
bun add next@next-14 react@18 react-dom@18 && bun add eslint-config-next@next-14 -D
```

> **Good to know:** If you are using TypeScript, ensure you also upgrade `@types/react` and `@types/react-dom` to their latest versions.

### [v14 Summary](https://nextjs.org/docs/app/building-your-application/upgrading/version-14\#v14-summary)

- The minimum Node.js version has been bumped from 16.14 to 18.17, since 16.x has reached end-of-life.
- The `next export` command has been removed in favor of `output: 'export'` config. Please see the [docs](https://nextjs.org/docs/app/building-your-application/deploying/static-exports) for more information.
- The `next/server` import for `ImageResponse` was renamed to `next/og`. A [codemod is available](https://nextjs.org/docs/app/building-your-application/upgrading/codemods#next-og-import) to safely and automatically rename your imports.
- The `@next/font` package has been fully removed in favor of the built-in `next/font`. A [codemod is available](https://nextjs.org/docs/app/building-your-application/upgrading/codemods#built-in-next-font) to safely and automatically rename your imports.
- The WASM target for `next-swc` has been removed.

Was this helpful?

supported.

Send

## Next.js Directives Overview
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [API Reference](https://nextjs.org/docs/app/api-reference) Directives

# Directives

The following directives are available:

[**use cache** \\
Learn how to use the use cache directive to cache data in your Next.js application.](https://nextjs.org/docs/app/api-reference/directives/use-cache) [**use client** \\
Learn how to use the use client directive to render a component on the client.](https://nextjs.org/docs/app/api-reference/directives/use-client) [**use server** \\
Learn how to use the use server directive to execute code on the server.](https://nextjs.org/docs/app/api-reference/directives/use-server)

Was this helpful?

supported.

Send

## Optimizing Package Bundling
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Optimizing](https://nextjs.org/docs/app/building-your-application/optimizing) Package Bundling

# Optimizing Package Bundling

Bundling external packages can significantly improve the performance of your application. By default, packages imported inside Server Components and Route Handlers are automatically bundled by Next.js. This page will guide you through how to analyze and further optimize package bundling.

## [Analyzing JavaScript bundles](https://nextjs.org/docs/app/building-your-application/optimizing/package-bundling\#analyzing-javascript-bundles)

[`@next/bundle-analyzer`](https://www.npmjs.com/package/@next/bundle-analyzer) is a plugin for Next.js that helps you manage the size of your application bundles. It generates a visual report of the size of each package and their dependencies. You can use the information to remove large dependencies, split, or [lazy-load](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading) your code.

### [Installation](https://nextjs.org/docs/app/building-your-application/optimizing/package-bundling\#installation)

Install the plugin by running the following command:

```code-block_code__isn_V
npm i @next/bundle-analyzer
# or
yarn add @next/bundle-analyzer
# or
pnpm add @next/bundle-analyzer
```

Then, add the bundle analyzer's settings to your `next.config.js`.

next.config.js

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
const nextConfig = {}

const withBundleAnalyzer = require('@next/bundle-analyzer')({
  enabled: process.env.ANALYZE === 'true',
})

module.exports = withBundleAnalyzer(nextConfig)
```

### [Generating a report](https://nextjs.org/docs/app/building-your-application/optimizing/package-bundling\#generating-a-report)

Run the following command to analyze your bundles:

```code-block_code__isn_V
ANALYZE=true npm run build
# or
ANALYZE=true yarn build
# or
ANALYZE=true pnpm build
```

The report will open three new tabs in your browser, which you can inspect. Periodically evaluating your application's bundles can help you maintain application performance over time.

## [Optimizing package imports](https://nextjs.org/docs/app/building-your-application/optimizing/package-bundling\#optimizing-package-imports)

Some packages, such as icon libraries, can export hundreds of modules, which can cause performance issues in development and production.

You can optimize how these packages are imported by adding the [`optimizePackageImports`](https://nextjs.org/docs/app/api-reference/config/next-config-js/optimizePackageImports) option to your `next.config.js`. This option will only load the modules you _actually_ use, while still giving you the convenience of writing import statements with many named exports.

next.config.js

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
const nextConfig = {
  experimental: {
    optimizePackageImports: ['icon-library'],
  },
}

module.exports = nextConfig
```

Next.js also optimizes some libraries automatically, thus they do not need to be included in the optimizePackageImports list. See the [full list](https://nextjs.org/docs/app/api-reference/config/next-config-js/optimizePackageImports).

## [Opting specific packages out of bundling](https://nextjs.org/docs/app/building-your-application/optimizing/package-bundling\#opting-specific-packages-out-of-bundling-1)

Since packages imported inside Server Components and Route Handlers are automatically bundled by Next.js, you can opt specific packages out of bundling using the [`serverExternalPackages`](https://nextjs.org/docs/app/api-reference/config/next-config-js/serverExternalPackages) option in your `next.config.js`.

next.config.js

```code-block_code__isn_V
/** @type {import('next').NextConfig} */
const nextConfig = {
  serverExternalPackages: ['package-name'],
}

module.exports = nextConfig
```

Next.js includes a list of popular packages that currently are working on compatibility and automatically opt-ed out. See the [full list](https://nextjs.org/docs/app/api-reference/config/next-config-js/serverExternalPackages).

## Next Steps

Learn more about optimizing your application for production.

[**Production Checklist** \\
Recommendations to ensure the best performance and user experience before taking your Next.js application to production.](https://nextjs.org/docs/app/building-your-application/deploying/production-checklist)

Was this helpful?

supported.

Send

## Fetching Data in Next.js
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Getting Started](https://nextjs.org/docs/app/getting-started) Fetching Data

# How to fetch data and stream

This page will walk you through how you can fetch data in [Server Components](https://nextjs.org/docs/app/getting-started/fetching-data#server-components) and [Client Components](https://nextjs.org/docs/app/getting-started/fetching-data#client-components). As well as how to [stream](https://nextjs.org/docs/app/getting-started/fetching-data#streaming) content that depends on data.

## [Fetching data](https://nextjs.org/docs/app/getting-started/fetching-data\#fetching-data)

### [Server Components](https://nextjs.org/docs/app/getting-started/fetching-data\#server-components)

You can fetch data in Server Components using:

1. The [`fetch` API](https://nextjs.org/docs/app/getting-started/fetching-data#with-the-fetch-api)
2. An [ORM or database](https://nextjs.org/docs/app/getting-started/fetching-data#with-an-orm-or-database)

#### [With the `fetch` API](https://nextjs.org/docs/app/getting-started/fetching-data\#with-the-fetch-api)

To fetch data with the `fetch` API, turn your component into an asynchronous function, and await the `fetch` call. For example:

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Page() {
  const data = await fetch('https://api.vercel.app/blog')
  const posts = await data.json()
  return (
    <ul>
      {posts.map((post) => (
        <li key={post.id}>{post.title}</li>
      ))}
    </ul>
  )
}
```

#### [With an ORM or database](https://nextjs.org/docs/app/getting-started/fetching-data\#with-an-orm-or-database)

You can fetch data with an ORM or database by turning your component into an asynchronous function, and awaiting the call:

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { db, posts } from '@/lib/db'

export default async function Page() {
  const allPosts = await db.select().from(posts)
  return (
    <ul>
      {allPosts.map((post) => (
        <li key={post.id}>{post.title}</li>
      ))}
    </ul>
  )
}
```

### [Client Components](https://nextjs.org/docs/app/getting-started/fetching-data\#client-components)

There are two ways to fetch data in Client Components, using:

1. React's [`use` hook](https://react.dev/reference/react/use)
2. A community library like [SWR](https://swr.vercel.app/) or [React Query](https://tanstack.com/query/latest)

#### [With the `use` hook](https://nextjs.org/docs/app/getting-started/fetching-data\#with-the-use-hook)

You can use React's [`use` hook](https://react.dev/reference/react/use) to [stream](https://nextjs.org/docs/app/getting-started/fetching-data#streaming) data from the server to client. Start by fetching data in your Server component, and pass the promise to your Client Component as prop:

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Posts from '@/app/ui/posts
import { Suspense } from 'react'

export default function Page() {
  // Don't await the data fetching function
  const posts = getPosts()

  return (
    <Suspense fallback={<div>Loading...</div>}>
      <Posts posts={posts} />
    </Suspense>
  )
}
```

Then, in your Client Component, use the `use` hook to read the promise:

app/ui/posts.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'
import { use } from 'react'

export default function Posts({
  posts,
}: {
  posts: Promise<{ id: string; title: string }[]>
}) {
  const allPosts = use(posts)

  return (
    <ul>
      {allPosts.map((post) => (
        <li key={post.id}>{post.title}</li>
      ))}
    </ul>
  )
}
```

In the example above, you need to wrap the `<Posts />` component in a [`<Suspense>` boundary](https://react.dev/reference/react/Suspense). This means the fallback will be shown while the promise is being resolved. Learn more about [streaming](https://nextjs.org/docs/app/getting-started/fetching-data#streaming).

#### [Community libraries](https://nextjs.org/docs/app/getting-started/fetching-data\#community-libraries)

You can use a community library like [SWR](https://swr.vercel.app/) or [React Query](https://tanstack.com/query/latest) to fetch data in Client Components. These libraries have their own semantics for caching, streaming, and other features. For example, with SWR:

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'
import useSWR from 'swr'

const fetcher = (url) => fetch(url).then((r) => r.json())

export default function BlogPage() {
  const { data, error, isLoading } = useSWR(
    'https://api.vercel.app/blog',
    fetcher
  )

  if (isLoading) return <div>Loading...</div>
  if (error) return <div>Error: {error.message}</div>

  return (
    <ul>
      {data.map((post: { id: string; title: string }) => (
        <li key={post.id}>{post.title}</li>
      ))}
    </ul>
  )
}
```

## [Streaming](https://nextjs.org/docs/app/getting-started/fetching-data\#streaming)

> **Warning:** The content below assumes the [`dynamicIO` config option](https://nextjs.org/docs/app/api-reference/config/next-config-js/dynamicIO) is enabled in your application. The flag was introduced in Next.js 15 canary.

When using `async/await` in Server Components, Next.js will opt into **dynamic rendering**. This means the data will be fetched and rendered on the server for every user request. If there are any slow data requests, the whole route will be blocked from rendering.

To improve the initial load time and user experience, you can use streaming to break up the page's HTML into smaller chunks and progressively send those chunks from the server to the client.

![How Server Rendering with Streaming Works](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fserver-rendering-with-streaming.png&w=3840&q=75)![How Server Rendering with Streaming Works](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fserver-rendering-with-streaming.png&w=3840&q=75)

There are two ways you can implement streaming in your application:

1. With the [`loading.js` file](https://nextjs.org/docs/app/getting-started/fetching-data#with-loadingjs)
2. With React's [`<Suspense>` component](https://nextjs.org/docs/app/getting-started/fetching-data#with-suspense)

### [With `loading.js`](https://nextjs.org/docs/app/getting-started/fetching-data\#with-loadingjs)

You can create a `loading.js` file in the same folder as your page to stream the **entire page** while the data is being fetched. For example, to stream `app/blog/page.js`, add the file inside the `app/blog` folder.

![Blog folder structure with loading.js file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Floading-file.png&w=3840&q=75)![Blog folder structure with loading.js file](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Floading-file.png&w=3840&q=75)

app/blog/loading.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default function Loading() {
  // Define the Loading UI here
  return <div>Loading...</div>
}
```

On navigation, the user will immediately see the layout and a [loading state](https://nextjs.org/docs/app/getting-started/fetching-data#creating-meaningful-loading-states) while the page is being rendered. The new content will then be automatically swapped in once rendering is complete.

![Loading UI](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Floading-ui.png&w=3840&q=75)![Loading UI](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Floading-ui.png&w=3840&q=75)

Behind-the-scenes, `loading.js` will be nested inside `layout.js`, and will automatically wrap the `page.js` file and any children below in a `<Suspense>` boundary.

![loading.js overview](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Floading-overview.png&w=3840&q=75)![loading.js overview](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Floading-overview.png&w=3840&q=75)

This approach works well for route segments (layouts and pages), but for more granular streaming, you can use `<Suspense>`.

### [With `<Suspense>`](https://nextjs.org/docs/app/getting-started/fetching-data\#with-suspense)

`<Suspense>` allows you to be more granular about what parts of the page to stream. For example, you can immediately show any page content that falls outside of the `<Suspense>` boundary, and stream in the list of blog posts inside the boundary.

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Suspense } from 'react'
import BlogList from '@/components/BlogList'
import BlogListSkeleton from '@/components/BlogListSkeleton'

export default function BlogPage() {
  return (
    <div>
      {/* This content will be sent to the client immediately */}
      <header>
        <h1>Welcome to the Blog</h1>
        <p>Read the latest posts below.</p>
      </header>
      <main>
        {/* Any content wrapped in a <Suspense> boundary will be streamed */}
        <Suspense fallback={<BlogListSkeleton />}>
          <BlogList />
        </Suspense>
      </main>
    </div>
  )
}
```

### [Creating meaningful loading states](https://nextjs.org/docs/app/getting-started/fetching-data\#creating-meaningful-loading-states)

An instant loading state is fallback UI that is shown immediately to the user after navigation. For the best user experience, we recommend designing loading states that are meaningful and help users understand the app is responding. For example, you can use skeletons and spinners, or a small but meaningful part of future screens such as a cover photo, title, etc.

In development, you can preview and inspect the loading state of your components using the [React Devtools](https://react.dev/learn/react-developer-tools).

## API Reference

Learn more about the features mentioned in this page by reading the API Reference.

[**fetch** \\
API reference for the extended fetch function.](https://nextjs.org/docs/app/api-reference/functions/fetch) [**loading.js** \\
API reference for the loading.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/loading)

Was this helpful?

supported.

Send

## Next.js Codemods Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Upgrading](https://nextjs.org/docs/app/building-your-application/upgrading) Codemods

# Codemods

Codemods are transformations that run on your codebase programmatically. This allows a large number of changes to be programmatically applied without having to manually go through every file.

Next.js provides Codemod transformations to help upgrade your Next.js codebase when an API is updated or deprecated.

## [Usage](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#usage)

In your terminal, navigate ( `cd`) into your project's folder, then run:

Terminal

```code-block_code__isn_V
npx @next/codemod <transform> <path>
```

Replacing `<transform>` and `<path>` with appropriate values.

- `transform` \- name of transform
- `path` \- files or directory to transform
- `--dry` Do a dry-run, no code will be edited
- `--print` Prints the changed output for comparison

## [Codemods](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#codemods)

### [15.0](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#150)

#### [Transform App Router Route Segment Config `runtime` value from `experimental-edge` to `edge`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#transform-app-router-route-segment-config-runtime-value-from-experimental-edge-to-edge)

##### [`app-dir-runtime-config-experimental-edge`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#app-dir-runtime-config-experimental-edge)

> **Note**: This codemod is App Router specific.

Terminal

```code-block_code__isn_V
npx @next/codemod@latest app-dir-runtime-config-experimental-edge .
```

This codemod transforms [Route Segment Config `runtime`](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config#runtime) value `experimental-edge` to `edge`.

For example:

```code-block_code__isn_V
export const runtime = 'experimental-edge'
```

Transforms into:

```code-block_code__isn_V
export const runtime = 'edge'
```

#### [Migrate to async Dynamic APIs](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#migrate-to-async-dynamic-apis)

APIs that opted into dynamic rendering that previously supported synchronous access are now asynchronous. You can read more about this breaking change in the [upgrade guide](https://nextjs.org/docs/app/building-your-application/upgrading/version-15).

##### [`next-async-request-api`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#next-async-request-api)

Terminal

```code-block_code__isn_V
npx @next/codemod@latest next-async-request-api .
```

This codemod will transform dynamic APIs ( `cookies()`, `headers()` and `draftMode()` from `next/headers`) that are now asynchronous to be properly awaited or wrapped with `React.use()` if applicable.
When an automatic migration isn't possible, the codemod will either add a typecast (if a TypeScript file) or a comment to inform the user that it needs to be manually reviewed & updated.

For example:

```code-block_code__isn_V
import { cookies, headers } from 'next/headers'
const token = cookies().get('token')

function useToken() {
  const token = cookies().get('token')
  return token
}

export default function Page() {
  const name = cookies().get('name')
}

function getHeader() {
  return headers().get('x-foo')
}
```

Transforms into:

```code-block_code__isn_V
import { use } from 'react'
import {
  cookies,
  headers,
  type UnsafeUnwrappedCookies,
  type UnsafeUnwrappedHeaders,
} from 'next/headers'
const token = (cookies() as unknown as UnsafeUnwrappedCookies).get('token')

function useToken() {
  const token = use(cookies()).get('token')
  return token
}

export default async function Page() {
  const name = (await cookies()).get('name')
}

function getHeader() {
  return (headers() as unknown as UnsafeUnwrappedHeaders).get('x-foo')
}
```

When we detect property access on the `params` or `searchParams` props in the page / route entries ( `page.js`, `layout.js`, `route.js`, or `default.js`) or the `generateMetadata` / `generateViewport` APIs,
it will attempt to transform the callsite from a sync to an async function, and await the property access. If it can't be made async (such as with a client component), it will use `React.use` to unwrap the promise .

For example:

```code-block_code__isn_V
// page.tsx
export default function Page({
  params,
  searchParams,
}: {
  params: { slug: string }
  searchParams: { [key: string]: string | string[] | undefined }
}) {
  const { value } = searchParams
  if (value === 'foo') {
    // ...
  }
}

export function generateMetadata({ params }: { params: { slug: string } }) {
  const { slug } = params
  return {
    title: `My Page - ${slug}`,
  }
}
```

Transforms into:

```code-block_code__isn_V
// page.tsx
export default async function Page(props: {
  params: Promise<{ slug: string }>
  searchParams: Promise<{ [key: string]: string | string[] | undefined }>
}) {
  const searchParams = await props.searchParams
  const { value } = searchParams
  if (value === 'foo') {
    // ...
  }
}

export async function generateMetadata(props: {
  params: Promise<{ slug: string }>
}) {
  const params = await props.params
  const { slug } = params
  return {
    title: `My Page - ${slug}`,
  }
}
```

> **Good to know:** When this codemod identifies a spot that might require manual intervention, but we aren't able to determine the exact fix, it will add a comment or typecast to the code to inform the user that it needs to be manually updated. These comments are prefixed with **@next/codemod**, and typecasts are prefixed with `UnsafeUnwrapped`.
> Your build will error until these comments are explicitly removed. [Read more](https://nextjs.org/docs/messages/sync-dynamic-apis).

#### [Replace `geo` and `ip` properties of `NextRequest` with `@vercel/functions`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#replace-geo-and-ip-properties-of-nextrequest-with-vercelfunctions)

##### [`next-request-geo-ip`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#next-request-geo-ip)

Terminal

```code-block_code__isn_V
npx @next/codemod@latest next-request-geo-ip .
```

This codemod installs `@vercel/functions` and transforms `geo` and `ip` properties of `NextRequest` with corresponding `@vercel/functions` features.

For example:

```code-block_code__isn_V
import type { NextRequest } from 'next/server'

export function GET(req: NextRequest) {
  const { geo, ip } = req
}
```

Transforms into:

```code-block_code__isn_V
import type { NextRequest } from 'next/server'
import { geolocation, ipAddress } from '@vercel/functions'

export function GET(req: NextRequest) {
  const geo = geolocation(req)
  const ip = ipAddress(req)
}
```

### [14.0](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#140)

#### [Migrate `ImageResponse` imports](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#migrate-imageresponse-imports)

##### [`next-og-import`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#next-og-import)

Terminal

```code-block_code__isn_V
npx @next/codemod@latest next-og-import .
```

This codemod moves transforms imports from `next/server` to `next/og` for usage of [Dynamic OG Image Generation](https://nextjs.org/docs/app/building-your-application/optimizing/metadata#dynamic-image-generation).

For example:

```code-block_code__isn_V
import { ImageResponse } from 'next/server'
```

Transforms into:

```code-block_code__isn_V
import { ImageResponse } from 'next/og'
```

#### [Use `viewport` export](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#use-viewport-export)

##### [`metadata-to-viewport-export`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#metadata-to-viewport-export)

Terminal

```code-block_code__isn_V
npx @next/codemod@latest metadata-to-viewport-export .
```

This codemod migrates certain viewport metadata to `viewport` export.

For example:

```code-block_code__isn_V
export const metadata = {
  title: 'My App',
  themeColor: 'dark',
  viewport: {
    width: 1,
  },
}
```

Transforms into:

```code-block_code__isn_V
export const metadata = {
  title: 'My App',
}

export const viewport = {
  width: 1,
  themeColor: 'dark',
}
```

### [13.2](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#132)

#### [Use Built-in Font](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#use-built-in-font)

##### [`built-in-next-font`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#built-in-next-font)

Terminal

```code-block_code__isn_V
npx @next/codemod@latest built-in-next-font .
```

This codemod uninstalls the `@next/font` package and transforms `@next/font` imports into the built-in `next/font`.

For example:

```code-block_code__isn_V
import { Inter } from '@next/font/google'
```

Transforms into:

```code-block_code__isn_V
import { Inter } from 'next/font/google'
```

### [13.0](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#130)

#### [Rename Next Image Imports](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#rename-next-image-imports)

##### [`next-image-to-legacy-image`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#next-image-to-legacy-image)

Terminal

```code-block_code__isn_V
npx @next/codemod@latest next-image-to-legacy-image .
```

Safely renames `next/image` imports in existing Next.js 10, 11, or 12 applications to `next/legacy/image` in Next.js 13. Also renames `next/future/image` to `next/image`.

For example:

pages/index.js

```code-block_code__isn_V
import Image1 from 'next/image'
import Image2 from 'next/future/image'

export default function Home() {
  return (
    <div>
      <Image1 src="/test.jpg" width="200" height="300" />
      <Image2 src="/test.png" width="500" height="400" />
    </div>
  )
}
```

Transforms into:

pages/index.js

```code-block_code__isn_V
// 'next/image' becomes 'next/legacy/image'
import Image1 from 'next/legacy/image'
// 'next/future/image' becomes 'next/image'
import Image2 from 'next/image'

export default function Home() {
  return (
    <div>
      <Image1 src="/test.jpg" width="200" height="300" />
      <Image2 src="/test.png" width="500" height="400" />
    </div>
  )
}
```

#### [Migrate to the New Image Component](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#migrate-to-the-new-image-component)

##### [`next-image-experimental`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#next-image-experimental)

Terminal

```code-block_code__isn_V
npx @next/codemod@latest next-image-experimental .
```

Dangerously migrates from `next/legacy/image` to the new `next/image` by adding inline styles and removing unused props.

- Removes `layout` prop and adds `style`.
- Removes `objectFit` prop and adds `style`.
- Removes `objectPosition` prop and adds `style`.
- Removes `lazyBoundary` prop.
- Removes `lazyRoot` prop.

#### [Remove `<a>` Tags From Link Components](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#remove-a-tags-from-link-components)

##### [`new-link`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#new-link)

Terminal

```code-block_code__isn_V
npx @next/codemod@latest new-link .
```

Remove `<a>` tags inside [Link Components](https://nextjs.org/docs/app/api-reference/components/link), or add a `legacyBehavior` prop to Links that cannot be auto-fixed.

For example:

```code-block_code__isn_V
<Link href="/about">
  <a>About</a>
</Link>
// transforms into
<Link href="/about">
  About
</Link>

<Link href="/about">
  <a onClick={() => console.log('clicked')}>About</a>
</Link>
// transforms into
<Link href="/about" onClick={() => console.log('clicked')}>
  About
</Link>
```

In cases where auto-fixing can't be applied, the `legacyBehavior` prop is added. This allows your app to keep functioning using the old behavior for that particular link.

```code-block_code__isn_V
const Component = () => <a>About</a>

<Link href="/about">
  <Component />
</Link>
// becomes
<Link href="/about" legacyBehavior>
  <Component />
</Link>
```

### [11](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#11)

#### [Migrate from CRA](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#migrate-from-cra)

##### [`cra-to-next`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#cra-to-next)

Terminal

```code-block_code__isn_V
npx @next/codemod cra-to-next
```

Migrates a Create React App project to Next.js; creating a Pages Router and necessary config to match behavior. Client-side only rendering is leveraged initially to prevent breaking compatibility due to `window` usage during SSR and can be enabled seamlessly to allow the gradual adoption of Next.js specific features.

Please share any feedback related to this transform [in this discussion](https://github.com/vercel/next.js/discussions/25858).

### [10](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#10)

#### [Add React imports](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#add-react-imports)

##### [`add-missing-react-import`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#add-missing-react-import)

Terminal

```code-block_code__isn_V
npx @next/codemod add-missing-react-import
```

Transforms files that do not import `React` to include the import in order for the new [React JSX transform](https://reactjs.org/blog/2020/09/22/introducing-the-new-jsx-transform.html) to work.

For example:

my-component.js

```code-block_code__isn_V
export default class Home extends React.Component {
  render() {
    return <div>Hello World</div>
  }
}
```

Transforms into:

my-component.js

```code-block_code__isn_V
import React from 'react'
export default class Home extends React.Component {
  render() {
    return <div>Hello World</div>
  }
}
```

### [9](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#9)

#### [Transform Anonymous Components into Named Components](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#transform-anonymous-components-into-named-components)

##### [`name-default-component`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#name-default-component)

Terminal

```code-block_code__isn_V
npx @next/codemod name-default-component
```

**Versions 9 and above.**

Transforms anonymous components into named components to make sure they work with [Fast Refresh](https://nextjs.org/blog/next-9-4#fast-refresh).

For example:

my-component.js

```code-block_code__isn_V
export default function () {
  return <div>Hello World</div>
}
```

Transforms into:

my-component.js

```code-block_code__isn_V
export default function MyComponent() {
  return <div>Hello World</div>
}
```

The component will have a camel-cased name based on the name of the file, and it also works with arrow functions.

### [8](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#8)

#### [Transform AMP HOC into page config](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#transform-amp-hoc-into-page-config)

##### [`withamp-to-config`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#withamp-to-config)

Terminal

```code-block_code__isn_V
npx @next/codemod withamp-to-config
```

Transforms the `withAmp` HOC into Next.js 9 page configuration.

For example:

```code-block_code__isn_V
// Before
import { withAmp } from 'next/amp'

function Home() {
  return <h1>My AMP Page</h1>
}

export default withAmp(Home)
```

```code-block_code__isn_V
// After
export default function Home() {
  return <h1>My AMP Page</h1>
}

export const config = {
  amp: true,
}
```

### [6](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#6)

#### [Use `withRouter`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#use-withrouter)

##### [`url-to-withrouter`](https://nextjs.org/docs/app/building-your-application/upgrading/codemods\#url-to-withrouter)

Terminal

```code-block_code__isn_V
npx @next/codemod url-to-withrouter
```

Transforms the deprecated automatically injected `url` property on top level pages to using `withRouter` and the `router` property it injects. Read more here: [https://nextjs.org/docs/messages/url-deprecated](https://nextjs.org/docs/messages/url-deprecated)

For example:

From

```code-block_code__isn_V
import React from 'react'
export default class extends React.Component {
  render() {
    const { pathname } = this.props.url
    return <div>Current pathname: {pathname}</div>
  }
}
```

To

```code-block_code__isn_V
import React from 'react'
import { withRouter } from 'next/router'
export default withRouter(
  class extends React.Component {
    render() {
      const { pathname } = this.props.router
      return <div>Current pathname: {pathname}</div>
    }
  }
)
```

This is one case. All the cases that are transformed (and tested) can be found in the [`__testfixtures__` directory](https://github.com/vercel/next.js/tree/canary/packages/next-codemod/transforms/__testfixtures__/url-to-withrouter).

Was this helpful?

supported.

Send

## Single-Page Applications Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Upgrading](https://nextjs.org/docs/app/building-your-application/upgrading) Single-Page Apps

# Single-Page Applications with Next.js

Next.js fully supports building Single-Page Applications (SPAs).

This includes fast route transitions with prefetching, client-side data fetching, using browser APIs, integrating with third-party client libraries, creating static routes, and more.

If you have an existing SPA, you can migrate to Next.js without large changes to your code. Next.js then allows you to progressively add server features as needed.

## [What is a Single-Page Application?](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#what-is-a-single-page-application)

The definition of a SPA varies. We’ll define a “strict SPA” as:

- **Client-side rendering (CSR)**: The app is served by one HTML file (e.g. `index.html`). Every route, page transition, and data fetch is handled by JavaScript in the browser.
- **No full-page reloads**: Rather than requesting a new document for each route, client-side JavaScript manipulates the current page’s DOM and fetches data as needed.

Strict SPAs often require large amounts of JavaScript to load before the page can be interactive. Further, client data waterfalls can be challenging to manage. Building SPAs with Next.js can address these issues.

## [Why use Next.js for SPAs?](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#why-use-nextjs-for-spas)

Next.js can automatically code split your JavaScript bundles, and generate multiple HTML entry points into different routes. This avoids loading unnecessary JavaScript code on the client-side, reducing the bundle size and enabling faster page loads.

The [`next/link`](https://nextjs.org/docs/app/api-reference/components/link) component automatically [prefetches](https://nextjs.org/docs/app/api-reference/components/link#prefetch) routes, giving you the fast page transitions of a strict SPA, but with the advantage of persisting application routing state to the URL for linking and sharing.

Next.js can start as a static site or even a strict SPA where everything is rendered client-side. If your project grows, Next.js allows you to progressively add more server features (e.g. [React Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components), [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations), and more) as needed.

## [Examples](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#examples)

Let's explore common patterns used to build SPAs and how Next.js solves them.

### [Using React’s `use` within a Context Provider](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#using-reacts-use-within-a-context-provider)

We recommend fetching data in a parent component (or layout), returning the Promise, and then unwrapping the value in a client component with React’s [`use` hook](https://react.dev/reference/react/use).

Next.js can start data fetching early on the server. In this example, that’s the root layout — the entry point to your application. The server can immediately begin streaming a response to the client.

By “hoisting” your data fetching to the root layout, Next.js starts the specified requests on the server early before any other components in your application. This eliminates client waterfalls and prevents having multiple roundtrips between client and server. It can also significantly improve performance, as your server is closer (and ideally colocated) to where your database is located.

For example, update your root layout to call the Promise, but do _not_ await it.

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { UserProvider } from './user-provider'
import { getUser } from './user' // some server-side function

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  let userPromise = getUser() // do NOT await

  return (
    <html lang="en">
      <body>
        <UserProvider userPromise={userPromise}>{children}</UserProvider>
      </body>
    </html>
  )
}
```

While you can [defer and pass a single Promise](https://nextjs.org/docs/app/getting-started/fetching-data#with-the-use-hook) as a prop to a client component, we generally see this pattern paired with a React context provider. This enables easier access from client components with a custom React hook.

You can forward a Promise to the React context provider:

app/user-provider.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client';

import { createContext, useContext, ReactNode } from 'react';

type User = any;
type UserContextType = {
  userPromise: Promise<User | null>;
};

const UserContext = createContext<UserContextType | null>(null);

export function useUser(): UserContextType {
  let context = useContext(UserContext);
  if (context === null) {
    throw new Error('useUser must be used within a UserProvider');
  }
  return context;
}

export function UserProvider({
  children,
  userPromise
}: {
  children: ReactNode;
  userPromise: Promise<User | null>;
}) {
  return (
    <UserContext.Provider value={{ userPromise }}>
      {children}
    </UserContext.Provider>
  );
}
```

Finally, you can call the `useUser()` custom hook in any client component and unwrap the Promise:

app/profile.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { use } from 'react'
import { useUser } from './user-provider'

export function Profile() {
  const { userPromise } = useUser()
  const user = use(userPromise)

  return '...'
}
```

The component that consumes the Promise (e.g. `Profile` above) will be suspended. This enables partial hydration. You can see the streamed and prerendered HTML before JavaScript has finished loading.

### [SPAs with SWR](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#spas-with-swr)

[SWR](https://swr.vercel.app/) is a popular React library for data fetching.

With SWR 2.3.0 (and React 19+), you can gradually adopt server features alongside your existing SWR-based client data fetching code. This is an abstraction of the above `use()` pattern. This means you can move data fetching between the client and server-side, or use both:

- **Client-only:** `useSWR(key, fetcher)`
- **Server-only:** `useSWR(key)` \+ RSC-provided data
- **Mixed:** `useSWR(key, fetcher)` \+ RSC-provided data

For example, wrap your application with `<SWRConfig>` and a `fallback`:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { SWRConfig } from 'swr'
import { getUser } from './user' // some server-side function

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <SWRConfig
      value={{
        fallback: {
          // We do NOT await getUser() here
          // Only components that read this data will suspend
          '/api/user': getUser(),
        },
      }}
    >
      {children}
    </SWRConfig>
  )
}
```

Because this is a server component, `getUser()` can securely read cookies, headers, or talk to your database. No separate API route is needed. Client components below the `<SWRConfig>` can call `useSWR()` with the same key to retrieve the user data. The component code with `useSWR` **does not require any changes** from your existing client-fetching solution.

app/profile.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import useSWR from 'swr'

export function Profile() {
  const fetcher = (url) => fetch(url).then((res) => res.json())
  // The same SWR pattern you already know
  const { data, error } = useSWR('/api/user', fetcher)

  return '...'
}
```

The `fallback` data can be prerendered and included in the initial HTML response, then immediately read in the child components using `useSWR`. SWR’s polling, revalidation, and caching still run **client-side only**, so it preserves all the interactivity you rely on for an SPA.

Since the initial `fallback` data is automatically handled by Next.js, you can now delete any conditional logic previously needed to check if `data` was `undefined`. When the data is loading, the closest `<Suspense>` boundary will be suspended.

|  | SWR | RSC | RSC + SWR |
| --- | --- | --- | --- |
| SSR data |  |  |  |
| Streaming while SSR |  |  |  |
| Deduplicate requests |  |  |  |
| Client-side features |  |  |  |

### [SPAs with React Query](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#spas-with-react-query)

You can use React Query with Next.js on both the client and server. This enables you to build both strict SPAs, as well as take advantage of server features in Next.js paired with React Query.

Learn more in the [React Query documentation](https://tanstack.com/query/latest/docs/framework/react/guides/advanced-ssr).

### [Rendering components only in the browser](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#rendering-components-only-in-the-browser)

Client components are [prerendered](https://github.com/reactwg/server-components/discussions/4) during `next build`. If you want to disable prerendering for a client component and only load it in the browser environment, you can use [`next/dynamic`](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading#nextdynamic):

```code-block_code__isn_V
import dynamic from 'next/dynamic'

const ClientOnlyComponent = dynamic(() => import('./component'), {
  ssr: false,
})
```

This can be useful for third-party libraries that rely on browser APIs like `window` or `document`. You can also add a `useEffect` that checks for the existence of these APIs, and if they do not exist, return `null` or a loading state which would be prerendered.

### [Shallow routing on the client](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#shallow-routing-on-the-client)

If you are migrating from a strict SPA like [Create React App](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app) or [Vite](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite), you might have existing code which shallow routes to update the URL state. This can be useful for manual transitions between views in your application _without_ using the default Next.js file-system routing.

Next.js allows you to use the native [`window.history.pushState`](https://developer.mozilla.org/en-US/docs/Web/API/History/pushState) and [`window.history.replaceState`](https://developer.mozilla.org/en-US/docs/Web/API/History/replaceState) methods to update the browser's history stack without reloading the page.

`pushState` and `replaceState` calls integrate into the Next.js Router, allowing you to sync with [`usePathname`](https://nextjs.org/docs/app/api-reference/functions/use-pathname) and [`useSearchParams`](https://nextjs.org/docs/app/api-reference/functions/use-search-params).

```code-block_code__isn_V
'use client'

import { useSearchParams } from 'next/navigation'

export default function SortProducts() {
  const searchParams = useSearchParams()

  function updateSorting(sortOrder: string) {
    const urlSearchParams = new URLSearchParams(searchParams.toString())
    urlSearchParams.set('sort', sortOrder)
    window.history.pushState(null, '', `?${urlSearchParams.toString()}`)
  }

  return (
    <>
      <button onClick={() => updateSorting('asc')}>Sort Ascending</button>
      <button onClick={() => updateSorting('desc')}>Sort Descending</button>
    </>
  )
}
```

Learn more about how [routing and navigation](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#how-routing-and-navigation-works) work in Next.js.

### [Using Server Actions in client components](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#using-server-actions-in-client-components)

You can progressively adopt Server Actions while still using client components. This allows you to remove boilerplate code to call an API route, and instead use React features like `useActionState` to handle loading and error states.

For example, create your first Server Action:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

export async function create() {}
```

You can import and use a Server Action from the client, similar to calling a JavaScript function. You do not need to create an API endpoint manually:

app/button.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { create } from './actions'

export function Button() {
  return <button onClick={() => create()}>Create</button>
}
```

Learn more about [mutating data with Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations).

## [Static export (optional)](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#static-export-optional)

Next.js also supports generating a fully [static site](https://nextjs.org/docs/app/building-your-application/deploying/static-exports). This has some advantages over strict SPAs:

- **Automatic code-splitting**: Instead of shipping a single `index.html`, Next.js will generate an HTML file per route, so your visitors get the content faster without waiting for the client JavaScript bundle.
- **Improved user experience:** Instead of a minimal skeleton for all routes, you get fully rendered pages for each route. When users navigate client side, transitions remain instant and SPA-like.

To enable a static export, update your configuration:

next.config.ts

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  output: 'export',
}

export default nextConfig
```

After running `next build`, Next.js will create an `out` folder with the HTML/CSS/JS assets for your application.

> **Note:** Next.js server features are not supported with static exports. [Learn more](https://nextjs.org/docs/app/building-your-application/deploying/static-exports#unsupported-features).

## [Migrating existing projects to Next.js](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications\#migrating-existing-projects-to-nextjs)

You can incrementally migrate to Next.js by following our guides:

- [Migrating from Create React App](https://nextjs.org/docs/app/building-your-application/upgrading/from-create-react-app)
- [Migrating from Vite](https://nextjs.org/docs/app/building-your-application/upgrading/from-vite)

If you are already using a SPA with the Pages Router, you can learn how to [incrementally adopt the App Router](https://nextjs.org/docs/app/building-your-application/upgrading/app-router-migration).

Was this helpful?

supported.

Send

## Next.js Draft Mode
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Configuring](https://nextjs.org/docs/app/building-your-application/configuring) Draft Mode

# Draft Mode

**Draft Mode** allows you to preview draft content from your headless CMS in your Next.js application. This is useful for static pages that are generated at build time as it allows you to switch to [dynamic rendering](https://nextjs.org/docs/app/building-your-application/rendering/server-components#dynamic-rendering) and see the draft changes without having to rebuild your entire site.

This page walks through how to enable and use Draft Mode.

## [Step 1: Create a Route Handler](https://nextjs.org/docs/app/building-your-application/configuring/draft-mode\#step-1-create-a-route-handler)

Create a [Route Handler](https://nextjs.org/docs/app/building-your-application/routing/route-handlers). It can have any name, for example, `app/api/draft/route.ts`.

app/api/draft/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function GET(request: Request) {
  return new Response('')
}
```

Then, import the [`draftMode`](https://nextjs.org/docs/app/api-reference/functions/draft-mode) function and call the `enable()` method.

app/api/draft/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { draftMode } from 'next/headers'

export async function GET(request: Request) {
  const draft = await draftMode()
  draft.enable()
  return new Response('Draft mode is enabled')
}
```

This will set a **cookie** to enable draft mode. Subsequent requests containing this cookie will trigger draft mode and change the behavior of statically generated pages.

You can test this manually by visiting `/api/draft` and looking at your browser’s developer tools. Notice the `Set-Cookie` response header with a cookie named `__prerender_bypass`.

## [Step 2: Access the Route Handler from your Headless CMS](https://nextjs.org/docs/app/building-your-application/configuring/draft-mode\#step-2-access-the-route-handler-from-your-headless-cms)

> These steps assume that the headless CMS you’re using supports setting **custom draft URLs**. If it doesn’t, you can still use this method to secure your draft URLs, but you’ll need to construct and access the draft URL manually. The specific steps will vary depending on which headless CMS you’re using.

To securely access the Route Handler from your headless CMS:

1. Create a **secret token string** using a token generator of your choice. This secret will only be known by your Next.js app and your headless CMS.
2. If your headless CMS supports setting custom draft URLs, specify a draft URL (this assumes that your Route Handler is located at `app/api/draft/route.ts`). For example:

Terminal

```code-block_code__isn_V
https://<your-site>/api/draft?secret=<token>&slug=<path>
```

> - `<your-site>` should be your deployment domain.
> - `<token>` should be replaced with the secret token you generated.
> - `<path>` should be the path for the page that you want to view. If you want to view `/posts/one`, then you should use `&slug=/posts/one`.
>
> Your headless CMS might allow you to include a variable in the draft URL so that `<path>` can be set dynamically based on the CMS’s data like so: `&slug=/posts/{entry.fields.slug}`

3. In your Route Handler, check that the secret matches and that the `slug` parameter exists (if not, the request should fail), call `draftMode.enable()` to set the cookie. Then, redirect the browser to the path specified by `slug`:

app/api/draft/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { draftMode } from 'next/headers'
import { redirect } from 'next/navigation'

export async function GET(request: Request) {
  // Parse query string parameters
  const { searchParams } = new URL(request.url)
  const secret = searchParams.get('secret')
  const slug = searchParams.get('slug')

  // Check the secret and next parameters
  // This secret should only be known to this Route Handler and the CMS
  if (secret !== 'MY_SECRET_TOKEN' || !slug) {
    return new Response('Invalid token', { status: 401 })
  }

  // Fetch the headless CMS to check if the provided `slug` exists
  // getPostBySlug would implement the required fetching logic to the headless CMS
  const post = await getPostBySlug(slug)

  // If the slug doesn't exist prevent draft mode from being enabled
  if (!post) {
    return new Response('Invalid slug', { status: 401 })
  }

  // Enable Draft Mode by setting the cookie
  const draft = await draftMode()
  draft.enable()

  // Redirect to the path from the fetched post
  // We don't redirect to searchParams.slug as that might lead to open redirect vulnerabilities
  redirect(post.slug)
}
```

If it succeeds, then the browser will be redirected to the path you want to view with the draft mode cookie.

## [Step 3: Preview the Draft Content](https://nextjs.org/docs/app/building-your-application/configuring/draft-mode\#step-3-preview-the-draft-content)

The next step is to update your page to check the value of `draftMode().isEnabled`.

If you request a page which has the cookie set, then data will be fetched at **request time** (instead of at build time).

Furthermore, the value of `isEnabled` will be `true`.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
// page that fetches data
import { draftMode } from 'next/headers'

async function getData() {
  const { isEnabled } = await draftMode()

  const url = isEnabled
    ? 'https://draft.example.com'
    : 'https://production.example.com'

  const res = await fetch(url)

  return res.json()
}

export default async function Page() {
  const { title, desc } = await getData()

  return (
    <main>
      <h1>{title}</h1>
      <p>{desc}</p>
    </main>
  )
}
```

If you access the draft Route Handler (with `secret` and `slug`) from your headless CMS or manually using the URL, you should now be able to see the draft content. And, if you update your draft without publishing, you should be able to view the draft.

## Next Steps

See the API reference for more information on how to use Draft Mode.

[**draftMode** \\
API Reference for the draftMode function.](https://nextjs.org/docs/app/api-reference/functions/draft-mode)

Was this helpful?

supported.

Send

## Next.js Internationalization Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Internationalization

# Internationalization

Next.js enables you to configure the routing and rendering of content to support multiple languages. Making your site adaptive to different locales includes translated content (localization) and internationalized routes.

## [Terminology](https://nextjs.org/docs/app/building-your-application/routing/internationalization\#terminology)

- **Locale:** An identifier for a set of language and formatting preferences. This usually includes the preferred language of the user and possibly their geographic region.
  - `en-US`: English as spoken in the United States
  - `nl-NL`: Dutch as spoken in the Netherlands
  - `nl`: Dutch, no specific region

## [Routing Overview](https://nextjs.org/docs/app/building-your-application/routing/internationalization\#routing-overview)

It’s recommended to use the user’s language preferences in the browser to select which locale to use. Changing your preferred language will modify the incoming `Accept-Language` header to your application.

For example, using the following libraries, you can look at an incoming `Request` to determine which locale to select, based on the `Headers`, locales you plan to support, and the default locale.

middleware.js

```code-block_code__isn_V
import { match } from '@formatjs/intl-localematcher'
import Negotiator from 'negotiator'

let headers = { 'accept-language': 'en-US,en;q=0.5' }
let languages = new Negotiator({ headers }).languages()
let locales = ['en-US', 'nl-NL', 'nl']
let defaultLocale = 'en-US'

match(languages, locales, defaultLocale) // -> 'en-US'
```

Routing can be internationalized by either the sub-path ( `/fr/products`) or domain ( `my-site.fr/products`). With this information, you can now redirect the user based on the locale inside [Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware).

middleware.js

```code-block_code__isn_V
import { NextResponse } from "next/server";

let locales = ['en-US', 'nl-NL', 'nl']

// Get the preferred locale, similar to the above or using a library
function getLocale(request) { ... }

export function middleware(request) {
  // Check if there is any supported locale in the pathname
  const { pathname } = request.nextUrl
  const pathnameHasLocale = locales.some(
    (locale) => pathname.startsWith(`/${locale}/`) || pathname === `/${locale}`
  )

  if (pathnameHasLocale) return

  // Redirect if there is no locale
  const locale = getLocale(request)
  request.nextUrl.pathname = `/${locale}${pathname}`
  // e.g. incoming request is /products
  // The new URL is now /en-US/products
  return NextResponse.redirect(request.nextUrl)
}

export const config = {
  matcher: [\
    // Skip all internal paths (_next)\
    '/((?!_next).*)',\
    // Optional: only run on root (/) URL\
    // '/'\
  ],
}
```

Finally, ensure all special files inside `app/` are nested under `app/[lang]`. This enables the Next.js router to dynamically handle different locales in the route, and forward the `lang` parameter to every layout and page. For example:

app/\[lang\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
// You now have access to the current locale
// e.g. /en-US/products -> `lang` is "en-US"
export default async function Page({
  params,
}: {
  params: Promise<{ lang: string }>
}) {
  const { lang } = await params
  return ...
}
```

The root layout can also be nested in the new folder (e.g. `app/[lang]/layout.js`).

## [Localization](https://nextjs.org/docs/app/building-your-application/routing/internationalization\#localization)

Changing displayed content based on the user’s preferred locale, or localization, is not something specific to Next.js. The patterns described below would work the same with any web application.

Let’s assume we want to support both English and Dutch content inside our application. We might maintain two different “dictionaries”, which are objects that give us a mapping from some key to a localized string. For example:

dictionaries/en.json

```code-block_code__isn_V
{
  "products": {
    "cart": "Add to Cart"
  }
}
```

dictionaries/nl.json

```code-block_code__isn_V
{
  "products": {
    "cart": "Toevoegen aan Winkelwagen"
  }
}
```

We can then create a `getDictionary` function to load the translations for the requested locale:

app/\[lang\]/dictionaries.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import 'server-only'

const dictionaries = {
  en: () => import('./dictionaries/en.json').then((module) => module.default),
  nl: () => import('./dictionaries/nl.json').then((module) => module.default),
}

export const getDictionary = async (locale: 'en' | 'nl') =>
  dictionaries[locale]()
```

Given the currently selected language, we can fetch the dictionary inside of a layout or page.

app/\[lang\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { getDictionary } from './dictionaries'

export default async function Page({
  params,
}: {
  params: Promise<{ lang: 'en' | 'nl' }>
}) {
  const { lang } = await params
  const dict = await getDictionary(lang) // en
  return <button>{dict.products.cart}</button> // Add to Cart
}
```

Because all layouts and pages in the `app/` directory default to [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components), we do not need to worry about the size of the translation files affecting our client-side JavaScript bundle size. This code will **only run on the server**, and only the resulting HTML will be sent to the browser.

## [Static Generation](https://nextjs.org/docs/app/building-your-application/routing/internationalization\#static-generation)

To generate static routes for a given set of locales, we can use `generateStaticParams` with any page or layout. This can be global, for example, in the root layout:

app/\[lang\]/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export async function generateStaticParams() {
  return [{ lang: 'en-US' }, { lang: 'de' }]
}

export default async function RootLayout({
  children,
  params,
}: Readonly<{
  children: React.ReactNode
  params: Promise<{ lang: 'en-US' | 'de' }>
}>) {
  return (
    <html lang={(await params).lang}>
      <body>{children}</body>
    </html>
  )
}
```

## [Resources](https://nextjs.org/docs/app/building-your-application/routing/internationalization\#resources)

- [Minimal i18n routing and translations](https://github.com/vercel/next.js/tree/canary/examples/i18n-routing)
- [`next-intl`](https://next-intl.dev/)
- [`next-international`](https://github.com/QuiiBz/next-international)
- [`next-i18n-router`](https://github.com/i18nexus/next-i18n-router)
- [`paraglide-next`](https://inlang.com/m/osslbuzt/paraglide-next-i18n)
- [`lingui`](https://lingui.dev/)

Was this helpful?

supported.

Send

## Next.js Canary Upgrade
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Upgrading](https://nextjs.org/docs/app/building-your-application/upgrading) Canary

# How to upgrade to Next.js Canary

The Next.js canary channel is updated daily with the latest experimental features and bug fixes. It's a great way to try out new features and [give feedback](https://github.com/vercel/next.js/issues) before they are released in a stable version.

To upgrade to canary, make sure you're on the latest version of Next.js and everything is working as expected. See the [upgrade guides](https://nextjs.org/docs/app/building-your-application/upgrading) for more information.

Then, run the following command:

Terminal

```code-block_code__isn_V
npm i next@canary
# or
yarn add next@canary
# or
pnpm i next@canary
```

## [Features available in canary](https://nextjs.org/docs/app/building-your-application/upgrading/canary\#features-available-in-canary)

The following features are currently available in canary:

**Caching**:

- [`"use cache"`](https://nextjs.org/docs/app/api-reference/directives/use-cache)
- [`cacheLife`](https://nextjs.org/docs/app/api-reference/functions/cacheLife)
- [`cacheTag`](https://nextjs.org/docs/app/api-reference/functions/cacheTag)
- [`dynamicIO`](https://nextjs.org/docs/app/api-reference/config/next-config-js/dynamicIO)

**Authentication**:

- [`forbidden`](https://nextjs.org/docs/app/api-reference/functions/forbidden)
- [`unauthorized`](https://nextjs.org/docs/app/api-reference/functions/unauthorized)
- [`forbidden.js`](https://nextjs.org/docs/app/api-reference/file-conventions/forbidden)
- [`unauthorized.js`](https://nextjs.org/docs/app/api-reference/file-conventions/unauthorized)
- [`authInterrupts`](https://nextjs.org/docs/app/api-reference/config/next-config-js/authInterrupts)

Was this helpful?

supported.

Send

## Next.js Caching Overview
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Building Your Application](https://nextjs.org/docs/app/building-your-application) Caching

# Caching in Next.js

Next.js improves your application's performance and reduces costs by caching rendering work and data requests. This page provides an in-depth look at Next.js caching mechanisms, the APIs you can use to configure them, and how they interact with each other.

> **Good to know**: This page helps you understand how Next.js works under the hood but is **not** essential knowledge to be productive with Next.js. Most of Next.js' caching heuristics are determined by your API usage and have defaults for the best performance with zero or minimal configuration. If you instead want to jump to examples, [start here](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching).

## [Overview](https://nextjs.org/docs/app/building-your-application/caching\#overview)

Here's a high-level overview of the different caching mechanisms and their purpose:

| Mechanism | What | Where | Purpose | Duration |
| --- | --- | --- | --- | --- |
| [Request Memoization](https://nextjs.org/docs/app/building-your-application/caching#request-memoization) | Return values of functions | Server | Re-use data in a React Component tree | Per-request lifecycle |
| [Data Cache](https://nextjs.org/docs/app/building-your-application/caching#data-cache) | Data | Server | Store data across user requests and deployments | Persistent (can be revalidated) |
| [Full Route Cache](https://nextjs.org/docs/app/building-your-application/caching#full-route-cache) | HTML and RSC payload | Server | Reduce rendering cost and improve performance | Persistent (can be revalidated) |
| [Router Cache](https://nextjs.org/docs/app/building-your-application/caching#client-side-router-cache) | RSC Payload | Client | Reduce server requests on navigation | User session or time-based |

By default, Next.js will cache as much as possible to improve performance and reduce cost. This means routes are **statically rendered** and data requests are **cached** unless you opt out. The diagram below shows the default caching behavior: when a route is statically rendered at build time and when a static route is first visited.

![Diagram showing the default caching behavior in Next.js for the four mechanisms, with HIT, MISS and SET at build time and when a route is first visited.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fcaching-overview.png&w=3840&q=75)![Diagram showing the default caching behavior in Next.js for the four mechanisms, with HIT, MISS and SET at build time and when a route is first visited.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fcaching-overview.png&w=3840&q=75)

Caching behavior changes depending on whether the route is statically or dynamically rendered, data is cached or uncached, and whether a request is part of an initial visit or a subsequent navigation. Depending on your use case, you can configure the caching behavior for individual routes and data requests.

## [Request Memoization](https://nextjs.org/docs/app/building-your-application/caching\#request-memoization)

Next.js extends the [`fetch` API](https://nextjs.org/docs/app/building-your-application/caching#fetch) to automatically **memoize** requests that have the same URL and options. This means you can call a fetch function for the same data in multiple places in a React component tree while only executing it once.

![Deduplicated Fetch Requests](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fdeduplicated-fetch-requests.png&w=3840&q=75)![Deduplicated Fetch Requests](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fdeduplicated-fetch-requests.png&w=3840&q=75)

For example, if you need to use the same data across a route (e.g. in a Layout, Page, and multiple components), you do not have to fetch data at the top of the tree, and forward props between components. Instead, you can fetch data in the components that need it without worrying about the performance implications of making multiple requests across the network for the same data.

app/example.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
async function getItem() {
  // The `fetch` function is automatically memoized and the result
  // is cached
  const res = await fetch('https://.../item/1')
  return res.json()
}

// This function is called twice, but only executed the first time
const item = await getItem() // cache MISS

// The second call could be anywhere in your route
const item = await getItem() // cache HIT
```

**How Request Memoization Works**

![Diagram showing how fetch memoization works during React rendering.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Frequest-memoization.png&w=3840&q=75)![Diagram showing how fetch memoization works during React rendering.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Frequest-memoization.png&w=3840&q=75)

- While rendering a route, the first time a particular request is called, its result will not be in memory and it'll be a cache `MISS`.
- Therefore, the function will be executed, and the data will be fetched from the external source, and the result will be stored in memory.
- Subsequent function calls of the request in the same render pass will be a cache `HIT`, and the data will be returned from memory without executing the function.
- Once the route has been rendered and the rendering pass is complete, memory is "reset" and all request memoization entries are cleared.

> **Good to know**:
>
> - Request memoization is a React feature, not a Next.js feature. It's included here to show how it interacts with the other caching mechanisms.
> - Memoization only applies to the `GET` method in `fetch` requests.
> - Memoization only applies to the React Component tree, this means:
>   - It applies to `fetch` requests in `generateMetadata`, `generateStaticParams`, Layouts, Pages, and other Server Components.
>   - It doesn't apply to `fetch` requests in Route Handlers as they are not a part of the React component tree.
> - For cases where `fetch` is not suitable (e.g. some database clients, CMS clients, or GraphQL clients), you can use the [React `cache` function](https://nextjs.org/docs/app/building-your-application/caching#react-cache-function) to memoize functions.

### [Duration](https://nextjs.org/docs/app/building-your-application/caching\#duration)

The cache lasts the lifetime of a server request until the React component tree has finished rendering.

### [Revalidating](https://nextjs.org/docs/app/building-your-application/caching\#revalidating)

Since the memoization is not shared across server requests and only applies during rendering, there is no need to revalidate it.

### [Opting out](https://nextjs.org/docs/app/building-your-application/caching\#opting-out)

Memoization only applies to the `GET` method in `fetch` requests, other methods, such as `POST` and `DELETE`, are not memoized. This default behavior is a React optimization and we do not recommend opting out of it.

To manage individual requests, you can use the [`signal`](https://developer.mozilla.org/en-US/docs/Web/API/AbortController/signal) property from [`AbortController`](https://developer.mozilla.org/en-US/docs/Web/API/AbortController). However, this will not opt requests out of memoization, rather, abort in-flight requests.

app/example.js

```code-block_code__isn_V
const { signal } = new AbortController()
fetch(url, { signal })
```

## [Data Cache](https://nextjs.org/docs/app/building-your-application/caching\#data-cache)

Next.js has a built-in Data Cache that **persists** the result of data fetches across incoming **server requests** and **deployments**. This is possible because Next.js extends the native `fetch` API to allow each request on the server to set its own persistent caching semantics.

> **Good to know**: In the browser, the `cache` option of `fetch` indicates how a request will interact with the browser's HTTP cache, in Next.js, the `cache` option indicates how a server-side request will interact with the server's Data Cache.

You can use the [`cache`](https://nextjs.org/docs/app/building-your-application/caching#fetch-optionscache) and [`next.revalidate`](https://nextjs.org/docs/app/building-your-application/caching#fetch-optionsnextrevalidate) options of `fetch` to configure the caching behavior.

**How the Data Cache Works**

![Diagram showing how cached and uncached fetch requests interact with the Data Cache. Cached requests are stored in the Data Cache, and memoized, uncached requests are fetched from the data source, not stored in the Data Cache, and memoized.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fdata-cache.png&w=3840&q=75)![Diagram showing how cached and uncached fetch requests interact with the Data Cache. Cached requests are stored in the Data Cache, and memoized, uncached requests are fetched from the data source, not stored in the Data Cache, and memoized.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fdata-cache.png&w=3840&q=75)

- The first time a `fetch` request with the `'force-cache'` option is called during rendering, Next.js checks the Data Cache for a cached response.
- If a cached response is found, it's returned immediately and [memoized](https://nextjs.org/docs/app/building-your-application/caching#request-memoization).
- If a cached response is not found, the request is made to the data source, the result is stored in the Data Cache, and memoized.
- For uncached data (e.g. no `cache` option defined or using `{ cache: 'no-store' }`), the result is always fetched from the data source, and memoized.
- Whether the data is cached or uncached, the requests are always memoized to avoid making duplicate requests for the same data during a React render pass.

> **Differences between the Data Cache and Request Memoization**
>
> While both caching mechanisms help improve performance by re-using cached data, the Data Cache is persistent across incoming requests and deployments, whereas memoization only lasts the lifetime of a request.

### [Duration](https://nextjs.org/docs/app/building-your-application/caching\#duration-1)

The Data Cache is persistent across incoming requests and deployments unless you revalidate or opt-out.

### [Revalidating](https://nextjs.org/docs/app/building-your-application/caching\#revalidating-1)

Cached data can be revalidated in two ways, with:

- **Time-based Revalidation**: Revalidate data after a certain amount of time has passed and a new request is made. This is useful for data that changes infrequently and freshness is not as critical.
- **On-demand Revalidation:** Revalidate data based on an event (e.g. form submission). On-demand revalidation can use a tag-based or path-based approach to revalidate groups of data at once. This is useful when you want to ensure the latest data is shown as soon as possible (e.g. when content from your headless CMS is updated).

#### [Time-based Revalidation](https://nextjs.org/docs/app/building-your-application/caching\#time-based-revalidation)

To revalidate data at a timed interval, you can use the `next.revalidate` option of `fetch` to set the cache lifetime of a resource (in seconds).

```code-block_code__isn_V
// Revalidate at most every hour
fetch('https://...', { next: { revalidate: 3600 } })
```

Alternatively, you can use [Route Segment Config options](https://nextjs.org/docs/app/building-your-application/caching#segment-config-options) to configure all `fetch` requests in a segment or for cases where you're not able to use `fetch`.

**How Time-based Revalidation Works**

![Diagram showing how time-based revalidation works, after the revalidation period, stale data is returned for the first request, then data is revalidated.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Ftime-based-revalidation.png&w=3840&q=75)![Diagram showing how time-based revalidation works, after the revalidation period, stale data is returned for the first request, then data is revalidated.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Ftime-based-revalidation.png&w=3840&q=75)

- The first time a fetch request with `revalidate` is called, the data will be fetched from the external data source and stored in the Data Cache.
- Any requests that are called within the specified timeframe (e.g. 60-seconds) will return the cached data.
- After the timeframe, the next request will still return the cached (now stale) data.
  - Next.js will trigger a revalidation of the data in the background.
  - Once the data is fetched successfully, Next.js will update the Data Cache with the fresh data.
  - If the background revalidation fails, the previous data will be kept unaltered.

This is similar to [**stale-while-revalidate**](https://web.dev/articles/stale-while-revalidate) behavior.

#### [On-demand Revalidation](https://nextjs.org/docs/app/building-your-application/caching\#on-demand-revalidation)

Data can be revalidated on-demand by path ( [`revalidatePath`](https://nextjs.org/docs/app/building-your-application/caching#revalidatepath)) or by cache tag ( [`revalidateTag`](https://nextjs.org/docs/app/building-your-application/caching#fetch-optionsnexttags-and-revalidatetag)).

**How On-Demand Revalidation Works**

![Diagram showing how on-demand revalidation works, the Data Cache is updated with fresh data after a revalidation request.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fon-demand-revalidation.png&w=3840&q=75)![Diagram showing how on-demand revalidation works, the Data Cache is updated with fresh data after a revalidation request.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fon-demand-revalidation.png&w=3840&q=75)

- The first time a `fetch` request is called, the data will be fetched from the external data source and stored in the Data Cache.
- When an on-demand revalidation is triggered, the appropriate cache entries will be purged from the cache.
  - This is different from time-based revalidation, which keeps the stale data in the cache until the fresh data is fetched.
- The next time a request is made, it will be a cache `MISS` again, and the data will be fetched from the external data source and stored in the Data Cache.

### [Opting out](https://nextjs.org/docs/app/building-your-application/caching\#opting-out-1)

If you do _not_ want to cache the response from `fetch`, you can do the following:

```code-block_code__isn_V
let data = await fetch('https://api.vercel.app/blog', { cache: 'no-store' })
```

## [Full Route Cache](https://nextjs.org/docs/app/building-your-application/caching\#full-route-cache)

> **Related terms**:
>
> You may see the terms **Automatic Static Optimization**, **Static Site Generation**, or **Static Rendering** being used interchangeably to refer to the process of rendering and caching routes of your application at build time.

Next.js automatically renders and caches routes at build time. This is an optimization that allows you to serve the cached route instead of rendering on the server for every request, resulting in faster page loads.

To understand how the Full Route Cache works, it's helpful to look at how React handles rendering, and how Next.js caches the result:

### [1\. React Rendering on the Server](https://nextjs.org/docs/app/building-your-application/caching\#1-react-rendering-on-the-server)

On the server, Next.js uses React's APIs to orchestrate rendering. The rendering work is split into chunks: by individual routes segments and Suspense boundaries.

Each chunk is rendered in two steps:

1. React renders Server Components into a special data format, optimized for streaming, called the **React Server Component Payload**.
2. Next.js uses the React Server Component Payload and Client Component JavaScript instructions to render **HTML** on the server.

This means we don't have to wait for everything to render before caching the work or sending a response. Instead, we can stream a response as work is completed.

> **What is the React Server Component Payload?**
>
> The React Server Component Payload is a compact binary representation of the rendered React Server Components tree. It's used by React on the client to update the browser's DOM. The React Server Component Payload contains:
>
> - The rendered result of Server Components
> - Placeholders for where Client Components should be rendered and references to their JavaScript files
> - Any props passed from a Server Component to a Client Component
>
> To learn more, see the [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components) documentation.

### [2\. Next.js Caching on the Server (Full Route Cache)](https://nextjs.org/docs/app/building-your-application/caching\#2-nextjs-caching-on-the-server-full-route-cache)

![Default behavior of the Full Route Cache, showing how the React Server Component Payload and HTML are cached on the server for statically rendered routes.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Ffull-route-cache.png&w=3840&q=75)![Default behavior of the Full Route Cache, showing how the React Server Component Payload and HTML are cached on the server for statically rendered routes.](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Ffull-route-cache.png&w=3840&q=75)

The default behavior of Next.js is to cache the rendered result (React Server Component Payload and HTML) of a route on the server. This applies to statically rendered routes at build time, or during revalidation.

### [3\. React Hydration and Reconciliation on the Client](https://nextjs.org/docs/app/building-your-application/caching\#3-react-hydration-and-reconciliation-on-the-client)

At request time, on the client:

1. The HTML is used to immediately show a fast non-interactive initial preview of the Client and Server Components.
2. The React Server Components Payload is used to reconcile the Client and rendered Server Component trees, and update the DOM.
3. The JavaScript instructions are used to [hydrate](https://react.dev/reference/react-dom/client/hydrateRoot) Client Components and make the application interactive.

### [4\. Next.js Caching on the Client (Router Cache)](https://nextjs.org/docs/app/building-your-application/caching\#4-nextjs-caching-on-the-client-router-cache)

The React Server Component Payload is stored in the client-side [Router Cache](https://nextjs.org/docs/app/building-your-application/caching#client-side-router-cache) \- a separate in-memory cache, split by individual route segment. This Router Cache is used to improve the navigation experience by storing previously visited routes and prefetching future routes.

### [5\. Subsequent Navigations](https://nextjs.org/docs/app/building-your-application/caching\#5-subsequent-navigations)

On subsequent navigations or during prefetching, Next.js will check if the React Server Components Payload is stored in the Router Cache. If so, it will skip sending a new request to the server.

If the route segments are not in the cache, Next.js will fetch the React Server Components Payload from the server, and populate the Router Cache on the client.

### [Static and Dynamic Rendering](https://nextjs.org/docs/app/building-your-application/caching\#static-and-dynamic-rendering)

Whether a route is cached or not at build time depends on whether it's statically or dynamically rendered. Static routes are cached by default, whereas dynamic routes are rendered at request time, and not cached.

This diagram shows the difference between statically and dynamically rendered routes, with cached and uncached data:

![How static and dynamic rendering affects the Full Route Cache. Static routes are cached at build time or after data revalidation, whereas dynamic routes are never cached](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fstatic-and-dynamic-routes.png&w=3840&q=75)![How static and dynamic rendering affects the Full Route Cache. Static routes are cached at build time or after data revalidation, whereas dynamic routes are never cached](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fstatic-and-dynamic-routes.png&w=3840&q=75)

Learn more about [static and dynamic rendering](https://nextjs.org/docs/app/building-your-application/rendering/server-components#server-rendering-strategies).

### [Duration](https://nextjs.org/docs/app/building-your-application/caching\#duration-2)

By default, the Full Route Cache is persistent. This means that the render output is cached across user requests.

### [Invalidation](https://nextjs.org/docs/app/building-your-application/caching\#invalidation)

There are two ways you can invalidate the Full Route Cache:

- **[Revalidating Data](https://nextjs.org/docs/app/building-your-application/caching#revalidating)**: Revalidating the [Data Cache](https://nextjs.org/docs/app/building-your-application/caching#data-cache), will in turn invalidate the Router Cache by re-rendering components on the server and caching the new render output.
- **Redeploying**: Unlike the Data Cache, which persists across deployments, the Full Route Cache is cleared on new deployments.

### [Opting out](https://nextjs.org/docs/app/building-your-application/caching\#opting-out-2)

You can opt out of the Full Route Cache, or in other words, dynamically render components for every incoming request, by:

- **Using a [Dynamic API](https://nextjs.org/docs/app/building-your-application/caching#dynamic-apis)**: This will opt the route out from the Full Route Cache and dynamically render it at request time. The Data Cache can still be used.
- **Using the `dynamic = 'force-dynamic'` or `revalidate = 0` route segment config options**: This will skip the Full Route Cache and the Data Cache. Meaning components will be rendered and data fetched on every incoming request to the server. The Router Cache will still apply as it's a client-side cache.
- **Opting out of the [Data Cache](https://nextjs.org/docs/app/building-your-application/caching#data-cache)**: If a route has a `fetch` request that is not cached, this will opt the route out of the Full Route Cache. The data for the specific `fetch` request will be fetched for every incoming request. Other `fetch` requests that do not opt out of caching will still be cached in the Data Cache. This allows for a hybrid of cached and uncached data.

## [Client-side Router Cache](https://nextjs.org/docs/app/building-your-application/caching\#client-side-router-cache)

Next.js has an in-memory client-side router cache that stores the RSC payload of route segments, split by layouts, loading states, and pages.

When a user navigates between routes, Next.js caches the visited route segments and [prefetches](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#2-prefetching) the routes the user is likely to navigate to. This results in instant back/forward navigation, no full-page reload between navigations, and preservation of React state and browser state.

With the Router Cache:

- **Layouts** are cached and reused on navigation ( [partial rendering](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#4-partial-rendering)).
- **Loading states** are cached and reused on navigation for [instant navigation](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming#instant-loading-states).
- **Pages** are not cached by default, but are reused during browser backward and forward navigation. You can enable caching for page segments by using the experimental [`staleTimes`](https://nextjs.org/docs/app/api-reference/config/next-config-js/staleTimes) config option.

> **Good to know:** This cache specifically applies to Next.js and Server Components, and is different to the browser's [bfcache](https://web.dev/bfcache/), though it has a similar result.

### [Duration](https://nextjs.org/docs/app/building-your-application/caching\#duration-3)

The cache is stored in the browser's temporary memory. Two factors determine how long the router cache lasts:

- **Session**: The cache persists across navigation. However, it's cleared on page refresh.
- **Automatic Invalidation Period**: The cache of layouts and loading states is automatically invalidated after a specific time. The duration depends on how the resource was [prefetched](https://nextjs.org/docs/app/api-reference/components/link#prefetch), and if the resource was [statically generated](https://nextjs.org/docs/app/building-your-application/rendering/server-components#static-rendering-default):
  - **Default Prefetching** ( `prefetch={null}` or unspecified): not cached for dynamic pages, 5 minutes for static pages.
  - **Full Prefetching** ( `prefetch={true}` or `router.prefetch`): 5 minutes for both static & dynamic pages.

While a page refresh will clear **all** cached segments, the automatic invalidation period only affects the individual segment from the time it was prefetched.

> **Good to know**: The experimental [`staleTimes`](https://nextjs.org/docs/app/api-reference/config/next-config-js/staleTimes) config option can be used to adjust the automatic invalidation times mentioned above.

### [Invalidation](https://nextjs.org/docs/app/building-your-application/caching\#invalidation-1)

There are two ways you can invalidate the Router Cache:

- In a **Server Action**:
  - Revalidating data on-demand by path with ( [`revalidatePath`](https://nextjs.org/docs/app/api-reference/functions/revalidatePath)) or by cache tag with ( [`revalidateTag`](https://nextjs.org/docs/app/api-reference/functions/revalidateTag))
  - Using [`cookies.set`](https://nextjs.org/docs/app/api-reference/functions/cookies#setting-a-cookie) or [`cookies.delete`](https://nextjs.org/docs/app/api-reference/functions/cookies#deleting-cookies) invalidates the Router Cache to prevent routes that use cookies from becoming stale (e.g. authentication).
- Calling [`router.refresh`](https://nextjs.org/docs/app/api-reference/functions/use-router) will invalidate the Router Cache and make a new request to the server for the current route.

### [Opting out](https://nextjs.org/docs/app/building-your-application/caching\#opting-out-3)

As of Next.js 15, page segments are opted out by default.

> **Good to know:** You can also opt out of [prefetching](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#2-prefetching) by setting the `prefetch` prop of the `<Link>` component to `false`.

## [Cache Interactions](https://nextjs.org/docs/app/building-your-application/caching\#cache-interactions)

When configuring the different caching mechanisms, it's important to understand how they interact with each other:

### [Data Cache and Full Route Cache](https://nextjs.org/docs/app/building-your-application/caching\#data-cache-and-full-route-cache)

- Revalidating or opting out of the Data Cache **will** invalidate the Full Route Cache, as the render output depends on data.
- Invalidating or opting out of the Full Route Cache **does not** affect the Data Cache. You can dynamically render a route that has both cached and uncached data. This is useful when most of your page uses cached data, but you have a few components that rely on data that needs to be fetched at request time. You can dynamically render without worrying about the performance impact of re-fetching all the data.

### [Data Cache and Client-side Router cache](https://nextjs.org/docs/app/building-your-application/caching\#data-cache-and-client-side-router-cache)

- To immediately invalidate the Data Cache and Router cache, you can use [`revalidatePath`](https://nextjs.org/docs/app/building-your-application/caching#revalidatepath) or [`revalidateTag`](https://nextjs.org/docs/app/building-your-application/caching#fetch-optionsnexttags-and-revalidatetag) in a [Server Action](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations).
- Revalidating the Data Cache in a [Route Handler](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) **will not** immediately invalidate the Router Cache as the Route Handler isn't tied to a specific route. This means Router Cache will continue to serve the previous payload until a hard refresh, or the automatic invalidation period has elapsed.

## [APIs](https://nextjs.org/docs/app/building-your-application/caching\#apis)

The following table provides an overview of how different Next.js APIs affect caching:

| API | Router Cache | Full Route Cache | Data Cache | React Cache |
| --- | --- | --- | --- | --- |
| [`<Link prefetch>`](https://nextjs.org/docs/app/building-your-application/caching#link) | Cache |  |  |  |
| [`router.prefetch`](https://nextjs.org/docs/app/building-your-application/caching#routerprefetch) | Cache |  |  |  |
| [`router.refresh`](https://nextjs.org/docs/app/building-your-application/caching#routerrefresh) | Revalidate |  |  |  |
| [`fetch`](https://nextjs.org/docs/app/building-your-application/caching#fetch) |  |  | Cache | Cache |
| [`fetch` `options.cache`](https://nextjs.org/docs/app/building-your-application/caching#fetch-optionscache) |  |  | Cache or Opt out |  |
| [`fetch` `options.next.revalidate`](https://nextjs.org/docs/app/building-your-application/caching#fetch-optionsnextrevalidate) |  | Revalidate | Revalidate |  |
| [`fetch` `options.next.tags`](https://nextjs.org/docs/app/building-your-application/caching#fetch-optionsnexttags-and-revalidatetag) |  | Cache | Cache |  |
| [`revalidateTag`](https://nextjs.org/docs/app/building-your-application/caching#fetch-optionsnexttags-and-revalidatetag) | Revalidate (Server Action) | Revalidate | Revalidate |  |
| [`revalidatePath`](https://nextjs.org/docs/app/building-your-application/caching#revalidatepath) | Revalidate (Server Action) | Revalidate | Revalidate |  |
| [`const revalidate`](https://nextjs.org/docs/app/building-your-application/caching#segment-config-options) |  | Revalidate or Opt out | Revalidate or Opt out |  |
| [`const dynamic`](https://nextjs.org/docs/app/building-your-application/caching#segment-config-options) |  | Cache or Opt out | Cache or Opt out |  |
| [`cookies`](https://nextjs.org/docs/app/building-your-application/caching#cookies) | Revalidate (Server Action) | Opt out |  |  |
| [`headers`, `searchParams`](https://nextjs.org/docs/app/building-your-application/caching#dynamic-apis) |  | Opt out |  |  |
| [`generateStaticParams`](https://nextjs.org/docs/app/building-your-application/caching#generatestaticparams) |  | Cache |  |  |
| [`React.cache`](https://nextjs.org/docs/app/building-your-application/caching#react-cache-function) |  |  |  | Cache |
| [`unstable_cache`](https://nextjs.org/docs/app/api-reference/functions/unstable_cache) |  |  | Cache |  |

### [`<Link>`](https://nextjs.org/docs/app/building-your-application/caching\#link)

By default, the `<Link>` component automatically prefetches routes from the Full Route Cache and adds the React Server Component Payload to the Router Cache.

To disable prefetching, you can set the `prefetch` prop to `false`. But this will not skip the cache permanently, the route segment will still be cached client-side when the user visits the route.

Learn more about the [`<Link>` component](https://nextjs.org/docs/app/api-reference/components/link).

### [`router.prefetch`](https://nextjs.org/docs/app/building-your-application/caching\#routerprefetch)

The `prefetch` option of the `useRouter` hook can be used to manually prefetch a route. This adds the React Server Component Payload to the Router Cache.

See the [`useRouter` hook](https://nextjs.org/docs/app/api-reference/functions/use-router) API reference.

### [`router.refresh`](https://nextjs.org/docs/app/building-your-application/caching\#routerrefresh)

The `refresh` option of the `useRouter` hook can be used to manually refresh a route. This completely clears the Router Cache, and makes a new request to the server for the current route. `refresh` does not affect the Data or Full Route Cache.

The rendered result will be reconciled on the client while preserving React state and browser state.

See the [`useRouter` hook](https://nextjs.org/docs/app/api-reference/functions/use-router) API reference.

### [`fetch`](https://nextjs.org/docs/app/building-your-application/caching\#fetch)

Data returned from `fetch` is _not_ automatically cached in the Data Cache.

The default caching behavior of `fetch` (e.g., when the `cache` option is not specified) is equal to setting the `cache` option to `no-store`:

```code-block_code__isn_V
let data = await fetch('https://api.vercel.app/blog', { cache: 'no-store' })
```

See the [`fetch` API Reference](https://nextjs.org/docs/app/api-reference/functions/fetch) for more options.

### [`fetch options.cache`](https://nextjs.org/docs/app/building-your-application/caching\#fetch-optionscache)

You can opt individual `fetch` into caching by setting the `cache` option to `force-cache`:

```code-block_code__isn_V
// Opt into caching
fetch(`https://...`, { cache: 'force-cache' })
```

See the [`fetch` API Reference](https://nextjs.org/docs/app/api-reference/functions/fetch) for more options.

### [`fetch options.next.revalidate`](https://nextjs.org/docs/app/building-your-application/caching\#fetch-optionsnextrevalidate)

You can use the `next.revalidate` option of `fetch` to set the revalidation period (in seconds) of an individual `fetch` request. This will revalidate the Data Cache, which in turn will revalidate the Full Route Cache. Fresh data will be fetched, and components will be re-rendered on the server.

```code-block_code__isn_V
// Revalidate at most after 1 hour
fetch(`https://...`, { next: { revalidate: 3600 } })
```

See the [`fetch` API reference](https://nextjs.org/docs/app/api-reference/functions/fetch) for more options.

### [`fetch options.next.tags` and `revalidateTag`](https://nextjs.org/docs/app/building-your-application/caching\#fetch-optionsnexttags-and-revalidatetag)

Next.js has a cache tagging system for fine-grained data caching and revalidation.

1. When using `fetch` or [`unstable_cache`](https://nextjs.org/docs/app/api-reference/functions/unstable_cache), you have the option to tag cache entries with one or more tags.
2. Then, you can call `revalidateTag` to purge the cache entries associated with that tag.

For example, you can set a tag when fetching data:

```code-block_code__isn_V
// Cache data with a tag
fetch(`https://...`, { next: { tags: ['a', 'b', 'c'] } })
```

Then, call `revalidateTag` with a tag to purge the cache entry:

```code-block_code__isn_V
// Revalidate entries with a specific tag
revalidateTag('a')
```

There are two places you can use `revalidateTag`, depending on what you're trying to achieve:

1. [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) \- to revalidate data in response of a third party event (e.g. webhook). This will not invalidate the Router Cache immediately as the Router Handler isn't tied to a specific route.
2. [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations) \- to revalidate data after a user action (e.g. form submission). This will invalidate the Router Cache for the associated route.

### [`revalidatePath`](https://nextjs.org/docs/app/building-your-application/caching\#revalidatepath)

`revalidatePath` allows you manually revalidate data **and** re-render the route segments below a specific path in a single operation. Calling the `revalidatePath` method revalidates the Data Cache, which in turn invalidates the Full Route Cache.

```code-block_code__isn_V
revalidatePath('/')
```

There are two places you can use `revalidatePath`, depending on what you're trying to achieve:

1. [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) \- to revalidate data in response to a third party event (e.g. webhook).
2. [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations) \- to revalidate data after a user interaction (e.g. form submission, clicking a button).

See the [`revalidatePath` API reference](https://nextjs.org/docs/app/api-reference/functions/revalidatePath) for more information.

> **`revalidatePath`** vs. **`router.refresh`**:
>
> Calling `router.refresh` will clear the Router cache, and re-render route segments on the server without invalidating the Data Cache or the Full Route Cache.
>
> The difference is that `revalidatePath` purges the Data Cache and Full Route Cache, whereas `router.refresh()` does not change the Data Cache and Full Route Cache, as it is a client-side API.

### [Dynamic APIs](https://nextjs.org/docs/app/building-your-application/caching\#dynamic-apis)

Dynamic APIs like `cookies` and `headers`, and the `searchParams` prop in Pages depend on runtime incoming request information. Using them will opt a route out of the Full Route Cache, in other words, the route will be dynamically rendered.

#### [`cookies`](https://nextjs.org/docs/app/building-your-application/caching\#cookies)

Using `cookies.set` or `cookies.delete` in a Server Action invalidates the Router Cache to prevent routes that use cookies from becoming stale (e.g. to reflect authentication changes).

See the [`cookies`](https://nextjs.org/docs/app/api-reference/functions/cookies) API reference.

### [Segment Config Options](https://nextjs.org/docs/app/building-your-application/caching\#segment-config-options)

The Route Segment Config options can be used to override the route segment defaults or when you're not able to use the `fetch` API (e.g. database client or 3rd party libraries).

The following Route Segment Config options will opt out of the Full Route Cache:

- `const dynamic = 'force-dynamic'`

This config option will opt all fetches out of the Data Cache (i.e. `no-store`):

- `const fetchCache = 'default-no-store'`

See the [`fetchCache`](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config#fetchcache) to see more advanced options.

See the [Route Segment Config](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config) documentation for more options.

### [`generateStaticParams`](https://nextjs.org/docs/app/building-your-application/caching\#generatestaticparams)

For [dynamic segments](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes) (e.g. `app/blog/[slug]/page.js`), paths provided by `generateStaticParams` are cached in the Full Route Cache at build time. At request time, Next.js will also cache paths that weren't known at build time the first time they're visited.

To statically render all paths at build time, supply the full list of paths to `generateStaticParams`:

app/blog/\[slug\]/page.js

```code-block_code__isn_V
export async function generateStaticParams() {
  const posts = await fetch('https://.../posts').then((res) => res.json())

  return posts.map((post) => ({
    slug: post.slug,
  }))
}
```

To statically render a subset of paths at build time, and the rest the first time they're visited at runtime, return a partial list of paths:

app/blog/\[slug\]/page.js

```code-block_code__isn_V
export async function generateStaticParams() {
  const posts = await fetch('https://.../posts').then((res) => res.json())

  // Render the first 10 posts at build time
  return posts.slice(0, 10).map((post) => ({
    slug: post.slug,
  }))
}
```

To statically render all paths the first time they're visited, return an empty array (no paths will be rendered at build time) or utilize [`export const dynamic = 'force-static'`](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config#dynamic):

app/blog/\[slug\]/page.js

```code-block_code__isn_V
export async function generateStaticParams() {
  return []
}
```

> **Good to know:** You must return an array from `generateStaticParams`, even if it's empty. Otherwise, the route will be dynamically rendered.

app/changelog/\[slug\]/page.js

```code-block_code__isn_V
export const dynamic = 'force-static'
```

To disable caching at request time, add the `export const dynamicParams = false` option in a route segment. When this config option is used, only paths provided by `generateStaticParams` will be served, and other routes will 404 or match (in the case of [catch-all routes](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes#catch-all-segments)).

### [React `cache` function](https://nextjs.org/docs/app/building-your-application/caching\#react-cache-function)

The React `cache` function allows you to memoize the return value of a function, allowing you to call the same function multiple times while only executing it once.

Since `fetch` requests are automatically memoized, you do not need to wrap it in React `cache`. However, you can use `cache` to manually memoize data requests for use cases when the `fetch` API is not suitable. For example, some database clients, CMS clients, or GraphQL clients.

utils/get-item.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { cache } from 'react'
import db from '@/lib/db'

export const getItem = cache(async (id: string) => {
  const item = await db.item.findUnique({ id })
  return item
})
```

Was this helpful?

supported.

Send

## Next.js Route Groups
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Route Groups

# Route Groups

In the `app` directory, nested folders are normally mapped to URL paths. However, you can mark a folder as a **Route Group** to prevent the folder from being included in the route's URL path.

This allows you to organize your route segments and project files into logical groups without affecting the URL path structure.

Route groups are useful for:

- [Organizing routes into groups](https://nextjs.org/docs/app/building-your-application/routing/route-groups#organize-routes-without-affecting-the-url-path) e.g. by site section, intent, or team.
- Enabling [nested layouts](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates) in the same route segment level:
  - [Creating multiple nested layouts in the same segment, including multiple root layouts](https://nextjs.org/docs/app/building-your-application/routing/route-groups#creating-multiple-root-layouts)
  - [Adding a layout to a subset of routes in a common segment](https://nextjs.org/docs/app/building-your-application/routing/route-groups#opting-specific-segments-into-a-layout)
- [Adding a loading skeleton to specific route in a common segment](https://nextjs.org/docs/app/building-your-application/routing/route-groups#opting-for-loading-skeletons-on-a-specific-route)

## [Convention](https://nextjs.org/docs/app/building-your-application/routing/route-groups\#convention)

A route group can be created by wrapping a folder's name in parenthesis: `(folderName)`

## [Examples](https://nextjs.org/docs/app/building-your-application/routing/route-groups\#examples)

### [Organize routes without affecting the URL path](https://nextjs.org/docs/app/building-your-application/routing/route-groups\#organize-routes-without-affecting-the-url-path)

To organize routes without affecting the URL, create a group to keep related routes together. The folders in parenthesis will be omitted from the URL (e.g. `(marketing)` or `(shop)`.

![Organizing Routes with Route Groups](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Froute-group-organisation.png&w=3840&q=75)![Organizing Routes with Route Groups](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Froute-group-organisation.png&w=3840&q=75)

Even though routes inside `(marketing)` and `(shop)` share the same URL hierarchy, you can create a different layout for each group by adding a `layout.js` file inside their folders.

![Route Groups with Multiple Layouts](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Froute-group-multiple-layouts.png&w=3840&q=75)![Route Groups with Multiple Layouts](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Froute-group-multiple-layouts.png&w=3840&q=75)

### [Opting specific segments into a layout](https://nextjs.org/docs/app/building-your-application/routing/route-groups\#opting-specific-segments-into-a-layout)

To opt specific routes into a layout, create a new route group (e.g. `(shop)`) and move the routes that share the same layout into the group (e.g. `account` and `cart`). The routes outside of the group will not share the layout (e.g. `checkout`).

![Route Groups with Opt-in Layouts](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Froute-group-opt-in-layouts.png&w=3840&q=75)![Route Groups with Opt-in Layouts](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Froute-group-opt-in-layouts.png&w=3840&q=75)

### [Opting for loading skeletons on a specific route](https://nextjs.org/docs/app/building-your-application/routing/route-groups\#opting-for-loading-skeletons-on-a-specific-route)

To apply a [loading skeleton](https://nextjs.org/docs/app/building-your-application/routing/loading-ui-and-streaming) via a `loading.js` file to a specific route, create a new route group (e.g., `/(overview)`) and then move your `loading.tsx` inside that route group.

![Folder structure showing a loading.tsx and a page.tsx inside the route group](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Froute-group-loading.png&w=3840&q=75)![Folder structure showing a loading.tsx and a page.tsx inside the route group](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Froute-group-loading.png&w=3840&q=75)

Now, the `loading.tsx` file will only apply to your dashboard → overview page instead of all your dashboard pages without affecting the URL path structure.

### [Creating multiple root layouts](https://nextjs.org/docs/app/building-your-application/routing/route-groups\#creating-multiple-root-layouts)

To create multiple [root layouts](https://nextjs.org/docs/app/building-your-application/routing/layouts-and-templates#root-layout-required), remove the top-level `layout.js` file, and add a `layout.js` file inside each route group. This is useful for partitioning an application into sections that have a completely different UI or experience. The `<html>` and `<body>` tags need to be added to each root layout.

![Route Groups with Multiple Root Layouts](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Froute-group-multiple-root-layouts.png&w=3840&q=75)![Route Groups with Multiple Root Layouts](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Froute-group-multiple-root-layouts.png&w=3840&q=75)

In the example above, both `(marketing)` and `(shop)` have their own root layout.

* * *

> **Good to know**:
>
> - The naming of route groups has no special significance other than for organization. They do not affect the URL path.
> - Routes that include a route group **should not** resolve to the same URL path as other routes. For example, since route groups don't affect URL structure, `(marketing)/about/page.js` and `(shop)/about/page.js` would both resolve to `/about` and cause an error.
> - If you use multiple root layouts without a top-level `layout.js` file, your home `page.js` file should be defined in one of the route groups, For example: `app/(marketing)/page.js`.
> - Navigating **across multiple root layouts** will cause a **full page load** (as opposed to a client-side navigation). For example, navigating from `/cart` that uses `app/(shop)/layout.js` to `/blog` that uses `app/(marketing)/layout.js` will cause a full page load. This **only** applies to multiple root layouts.

Was this helpful?

supported.

Send

## Images and Fonts
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [Getting Started](https://nextjs.org/docs/app/getting-started) Images and Fonts

# How to optimize images and fonts

Next.js comes with automatic image and font optimization for better performance and user experience. This page will guide you through how to start using them.

## [Handling static assets](https://nextjs.org/docs/app/getting-started/images-and-fonts\#handling-static-assets)

You can store static files, like images and fonts, under a folder called `public` in the root directory. Files inside `public` can then be referenced by your code starting from the base URL ( `/`).

![Folder structure showing app and public folders](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Flight%2Fpublic-folder.png&w=3840&q=75)![Folder structure showing app and public folders](https://nextjs.org/_next/image?url=https%3A%2F%2Fh8DxKfmAPhn8O0p3.public.blob.vercel-storage.com%2Fdocs%2Fdark%2Fpublic-folder.png&w=3840&q=75)

## [Optimizing images](https://nextjs.org/docs/app/getting-started/images-and-fonts\#optimizing-images)

The Next.js [`<Image>`](https://nextjs.org/docs/app/building-your-application/optimizing/images) component extends the HTML `<img>` element to provide:

- **Size optimization:** Automatically serving correctly sized images for each device, using modern image formats like WebP.
- **Visual stability:** Preventing [layout shift](https://web.dev/articles/cls) automatically when images are loading.
- **Faster page loads:** Only loading images when they enter the viewport using native browser lazy loading, with optional blur-up placeholders.
- **Asset flexibility:** Resizing images on-demand, even images stored on remote servers.

To start using `<Image>`, import it from `next/image` and render it within your component.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Image from 'next/image'

export default function Page() {
  return <Image src="" alt="" />
}
```

The `src` property can be a [local](https://nextjs.org/docs/app/getting-started/images-and-fonts#local-images) or [remote](https://nextjs.org/docs/app/getting-started/images-and-fonts#remote-images) image.

### [Local images](https://nextjs.org/docs/app/getting-started/images-and-fonts\#local-images)

To use a local image, `import` your `.jpg`, `.png`, or `.webp` image files from your [`public` folder](https://nextjs.org/docs/app/getting-started/images-and-fonts#handling-static-assets).

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Image from 'next/image'
import profilePic from './me.png'

export default function Page() {
  return (
    <Image
      src={profilePic}
      alt="Picture of the author"
      // width={500} automatically provided
      // height={500} automatically provided
      // blurDataURL="data:..." automatically provided
      // placeholder="blur" // Optional blur-up while loading
    />
  )
}
```

Next.js will automatically determine the intrinsic [`width`](https://nextjs.org/docs/app/api-reference/components/image#width) and [`height`](https://nextjs.org/docs/app/api-reference/components/image#height) of your image based on the imported file. These values are used to determine the image ratio and prevent [Cumulative Layout Shift](https://web.dev/articles/cls) while your image is loading.

### [Remote images](https://nextjs.org/docs/app/getting-started/images-and-fonts\#remote-images)

To use a remote image, you can provide a URL string for the `src` property.

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import Image from 'next/image'

export default function Page() {
  return (
    <Image
      src="https://s3.amazonaws.com/my-bucket/profile.png"
      alt="Picture of the author"
      width={500}
      height={500}
    />
  )
}
```

Since Next.js does not have access to remote files during the build process, you'll need to provide the [`width`](https://nextjs.org/docs/app/api-reference/components/image#width), [`height`](https://nextjs.org/docs/app/api-reference/components/image#height) and optional [`blurDataURL`](https://nextjs.org/docs/app/api-reference/components/image#blurdataurl) props manually. The `width` and `height` attributes are used to infer the correct aspect ratio of image and avoid layout shift from the image loading in.

Then, to safely allow images from remote servers, you need to define a list of supported URL patterns in [`next.config.js`](https://nextjs.org/docs/app/api-reference/config/next-config-js). Be as specific as possible to prevent malicious usage. For example, the following configuration will only allow images from a specific AWS S3 bucket:

next.config.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextConfig } from 'next'

const config: NextConfig = {
  images: {
    remotePatterns: [\
      {\
        protocol: 'https',\
        hostname: 's3.amazonaws.com',\
        port: '',\
        pathname: '/my-bucket/**',\
        search: '',\
      },\
    ],
  },
}

export default config
```

## [Optimizing fonts](https://nextjs.org/docs/app/getting-started/images-and-fonts\#optimizing-fonts)

The [`next/font`](https://nextjs.org/docs/app/api-reference/components/font) module automatically optimizes your fonts and removes external network requests for improved privacy and performance.

It includes **built-in automatic self-hosting** for _any_ font file. This means you can optimally load web fonts with no layout shift.

To start using `next/font`, import it from [`next/font/local`](https://nextjs.org/docs/app/getting-started/images-and-fonts#local-fonts) or [`next/font/google`](https://nextjs.org/docs/app/getting-started/images-and-fonts#google-fonts), call it as a function with the appropriate options, and set the `className` of the element you want to apply the font to. For example:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Geist } from 'next/font/google'

const geist = Geist({
  subsets: ['latin'],
})

export default function Layout({ children }: { children: React.ReactNode }) {
  return (
    <html lang="en" className={geist.className}>
      <body>{children}</body>
    </html>
  )
}
```

### [Google fonts](https://nextjs.org/docs/app/getting-started/images-and-fonts\#google-fonts)

You can automatically self-host any Google Font. Fonts are included in the deployment and served from the same domain as your deployment, meaning no requests are sent to Google by the browser when the user visits your site.

To start using a Google Font, import your chosen font from `next/font/google`:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Geist } from 'next/font/google'

const geist = Geist({
  subsets: ['latin'],
})

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en" className={geist.className}>
      <body>{children}</body>
    </html>
  )
}
```

We recommend using [variable fonts](https://fonts.google.com/variablefonts) for the best performance and flexibility. But if you can't use a variable font, you will **need to specify a weight**:

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { Roboto } from 'next/font/google'

const roboto = Roboto({
  weight: '400',
  subsets: ['latin'],
})

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en" className={roboto.className}>
      <body>{children}</body>
    </html>
  )
}
```

### [Local fonts](https://nextjs.org/docs/app/getting-started/images-and-fonts\#local-fonts)

To use a local font, import your font from `next/font/local` and specify the `src` of your local font file in the [`public` folder](https://nextjs.org/docs/app/getting-started/images-and-fonts#handling-static-assets).

app/layout.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import localFont from 'next/font/local'

const myFont = localFont({
  src: './my-font.woff2',
})

export default function RootLayout({
  children,
}: {
  children: React.ReactNode
}) {
  return (
    <html lang="en" className={myFont.className}>
      <body>{children}</body>
    </html>
  )
}
```

If you want to use multiple files for a single font family, `src` can be an array:

```code-block_code__isn_V
const roboto = localFont({
  src: [\
    {\
      path: './Roboto-Regular.woff2',\
      weight: '400',\
      style: 'normal',\
    },\
    {\
      path: './Roboto-Italic.woff2',\
      weight: '400',\
      style: 'italic',\
    },\
    {\
      path: './Roboto-Bold.woff2',\
      weight: '700',\
      style: 'normal',\
    },\
    {\
      path: './Roboto-BoldItalic.woff2',\
      weight: '700',\
      style: 'italic',\
    },\
  ],
})
```

## API Reference

Learn more about the features mentioned in this page by reading the API Reference.

[**Font** \\
Optimizing loading web fonts with the built-in \`next/font\` loaders.](https://nextjs.org/docs/app/api-reference/components/font) [**Image** \\
Optimize Images in your Next.js Application using the built-in \`next/image\` Component.](https://nextjs.org/docs/app/api-reference/components/image)

Was this helpful?

supported.

Send

## Next.js File Conventions
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[App Router](https://nextjs.org/docs/app) [API Reference](https://nextjs.org/docs/app/api-reference) File Conventions

# File Conventions

[**default.js** \\
API Reference for the default.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/default) [**error.js** \\
API reference for the error.js special file.](https://nextjs.org/docs/app/api-reference/file-conventions/error) [**forbidden.js** \\
API reference for the forbidden.js special file.](https://nextjs.org/docs/app/api-reference/file-conventions/forbidden) [**instrumentation.js** \\
API reference for the instrumentation.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/instrumentation) [**layout.js** \\
API reference for the layout.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/layout) [**loading.js** \\
API reference for the loading.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/loading) [**mdx-components.js** \\
API reference for the mdx-components.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/mdx-components) [**middleware.js** \\
API reference for the middleware.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/middleware) [**not-found.js** \\
API reference for the not-found.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/not-found) [**page.js** \\
API reference for the page.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/page) [**route.js** \\
API reference for the route.js special file.](https://nextjs.org/docs/app/api-reference/file-conventions/route) [**Route Segment Config** \\
Learn about how to configure options for Next.js route segments.](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config) [**template.js** \\
API Reference for the template.js file.](https://nextjs.org/docs/app/api-reference/file-conventions/template) [**unauthorized.js** \\
API reference for the unauthorized.js special file.](https://nextjs.org/docs/app/api-reference/file-conventions/unauthorized) [**Metadata Files** \\
API documentation for the metadata file conventions.](https://nextjs.org/docs/app/api-reference/file-conventions/metadata)

Was this helpful?

supported.

Send

## Incremental Static Regeneration
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Data Fetching](https://nextjs.org/docs/app/building-your-application/data-fetching) Incremental Static Regeneration (ISR)

# Incremental Static Regeneration (ISR)

Examples

- [Next.js Commerce](https://vercel.com/templates/next.js/nextjs-commerce)
- [On-Demand ISR](https://on-demand-isr.vercel.app/)
- [Next.js Forms](https://github.com/vercel/next.js/tree/canary/examples/next-forms)

Incremental Static Regeneration (ISR) enables you to:

- Update static content without rebuilding the entire site
- Reduce server load by serving prerendered, static pages for most requests
- Ensure proper `cache-control` headers are automatically added to pages
- Handle large amounts of content pages without long `next build` times

Here's a minimal example:

app/blog/\[id\]/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
interface Post {
  id: string
  title: string
  content: string
}

// Next.js will invalidate the cache when a
// request comes in, at most once every 60 seconds.
export const revalidate = 60

// We'll prerender only the params from `generateStaticParams` at build time.
// If a request comes in for a path that hasn't been generated,
// Next.js will server-render the page on-demand.
export const dynamicParams = true // or false, to 404 on unknown paths

export async function generateStaticParams() {
  const posts: Post[] = await fetch('https://api.vercel.app/blog').then((res) =>
    res.json()
  )
  return posts.map((post) => ({
    id: String(post.id),
  }))
}

export default async function Page({
  params,
}: {
  params: Promise<{ id: string }>
}) {
  const { id } = await params
  const post: Post = await fetch(`https://api.vercel.app/blog/${id}`).then(
    (res) => res.json()
  )
  return (
    <main>
      <h1>{post.title}</h1>
      <p>{post.content}</p>
    </main>
  )
}
```

Here's how this example works:

1. During `next build`, all known blog posts are generated (there are 25 in this example)
2. All requests made to these pages (e.g. `/blog/1`) are cached and instantaneous
3. After 60 seconds has passed, the next request will still show the cached (stale) page
4. The cache is invalidated and a new version of the page begins generating in the background
5. Once generated successfully, Next.js will display and cache the updated page
6. If `/blog/26` is requested, Next.js will generate and cache this page on-demand

## [Reference](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#reference)

### [Route segment config](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#route-segment-config)

- [`revalidate`](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config#revalidate)
- [`dynamicParams`](https://nextjs.org/docs/app/api-reference/file-conventions/route-segment-config#dynamicparams)

### [Functions](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#functions)

- [`revalidatePath`](https://nextjs.org/docs/app/api-reference/functions/revalidatePath)
- [`revalidateTag`](https://nextjs.org/docs/app/api-reference/functions/revalidateTag)

## [Examples](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#examples)

### [Time-based revalidation](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#time-based-revalidation)

This fetches and displays a list of blog posts on `/blog`. After an hour, the cache for this page is invalidated on the next visit to the page. Then, in the background, a new version of the page is generated with the latest blog posts.

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
interface Post {
  id: string
  title: string
  content: string
}

export const revalidate = 3600 // invalidate every hour

export default async function Page() {
  const data = await fetch('https://api.vercel.app/blog')
  const posts: Post[] = await data.json()
  return (
    <main>
      <h1>Blog Posts</h1>
      <ul>
        {posts.map((post) => (
          <li key={post.id}>{post.title}</li>
        ))}
      </ul>
    </main>
  )
}
```

We recommend setting a high revalidation time. For instance, 1 hour instead of 1 second. If you need more precision, consider using on-demand revalidation. If you need real-time data, consider switching to [dynamic rendering](https://nextjs.org/docs/app/building-your-application/rendering/server-components#dynamic-rendering).

### [On-demand revalidation with `revalidatePath`](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#on-demand-revalidation-with-revalidatepath)

For a more precise method of revalidation, invalidate pages on-demand with the `revalidatePath` function.

For example, this Server Action would get called after adding a new post. Regardless of how you retrieve your data in your Server Component, either using `fetch` or connecting to a database, this will clear the cache for the entire route and allow the Server Component to fetch fresh data.

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { revalidatePath } from 'next/cache'

export async function createPost() {
  // Invalidate the /posts route in the cache
  revalidatePath('/posts')
}
```

[View a demo](https://on-demand-isr.vercel.app/) and [explore the source code](https://github.com/vercel/on-demand-isr).

### [On-demand revalidation with `revalidateTag`](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#on-demand-revalidation-with-revalidatetag)

For most use cases, prefer revalidating entire paths. If you need more granular control, you can use the `revalidateTag` function. For example, you can tag individual `fetch` calls:

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
export default async function Page() {
  const data = await fetch('https://api.vercel.app/blog', {
    next: { tags: ['posts'] },
  })
  const posts = await data.json()
  // ...
}
```

If you are using an ORM or connecting to a database, you can use `unstable_cache`:

app/blog/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { unstable_cache } from 'next/cache'
import { db, posts } from '@/lib/db'

const getCachedPosts = unstable_cache(
  async () => {
    return await db.select().from(posts)
  },
  ['posts'],
  { revalidate: 3600, tags: ['posts'] }
)

export default async function Page() {
  const posts = getCachedPosts()
  // ...
}
```

You can then use `revalidateTag` in a [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations) or [Route Handler](https://nextjs.org/docs/app/building-your-application/routing/route-handlers):

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { revalidateTag } from 'next/cache'

export async function createPost() {
  // Invalidate all data tagged with 'posts' in the cache
  revalidateTag('posts')
}
```

### [Handling uncaught exceptions](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#handling-uncaught-exceptions)

If an error is thrown while attempting to revalidate data, the last successfully generated data will continue to be served from the cache. On the next subsequent request, Next.js will retry revalidating the data. [Learn more about error handling](https://nextjs.org/docs/app/building-your-application/routing/error-handling).

### [Customizing the cache location](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#customizing-the-cache-location)

Caching and revalidating pages (with Incremental Static Regeneration) use the same shared cache. When [deploying to Vercel](https://vercel.com/docs/incremental-static-regeneration?utm_source=next-site&utm_medium=docs&utm_campaign=next-website), the ISR cache is automatically persisted to durable storage.

When self-hosting, the ISR cache is stored to the filesystem (on disk) on your Next.js server. This works automatically when self-hosting using both the Pages and App Router.

You can configure the Next.js cache location if you want to persist cached pages and data to durable storage, or share the cache across multiple containers or instances of your Next.js application. [Learn more](https://nextjs.org/docs/app/building-your-application/deploying#caching-and-isr).

## [Troubleshooting](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#troubleshooting)

### [Debugging cached data in local development](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#debugging-cached-data-in-local-development)

If you are using the `fetch` API, you can add additional logging to understand which requests are cached or uncached. [Learn more about the `logging` option](https://nextjs.org/docs/app/api-reference/config/next-config-js/logging).

next.config.js

```code-block_code__isn_V
module.exports = {
  logging: {
    fetches: {
      fullUrl: true,
    },
  },
}
```

### [Verifying correct production behavior](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#verifying-correct-production-behavior)

To verify your pages are cached and revalidated correctly in production, you can test locally by running `next build` and then `next start` to run the production Next.js server.

This will allow you to test ISR behavior as it would work in a production environment. For further debugging, add the following environment variable to your `.env` file:

.env

```code-block_code__isn_V
NEXT_PRIVATE_DEBUG_CACHE=1
```

This will make the Next.js server console log ISR cache hits and misses. You can inspect the output to see which pages are generated during `next build`, as well as how pages are updated as paths are accessed on-demand.

## [Caveats](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#caveats)

- ISR is only supported when using the Node.js runtime (default).
- ISR is not supported when creating a [Static Export](https://nextjs.org/docs/app/building-your-application/deploying/static-exports).
- If you have multiple `fetch` requests in a statically rendered route, and each has a different `revalidate` frequency, the lowest time will be used for ISR. However, those revalidate frequencies will still be respected by the [Data Cache](https://nextjs.org/docs/app/building-your-application/caching#data-cache).
- If any of the `fetch` requests used on a route have a `revalidate` time of `0`, or an explicit `no-store`, the route will be [dynamically rendered](https://nextjs.org/docs/app/building-your-application/rendering/server-components#dynamic-rendering).
- Middleware won't be executed for on-demand ISR requests, meaning any path rewrites or logic in Middleware will not be applied. Ensure you are revalidating the exact path. For example, `/post/1` instead of a rewritten `/post-1`.

## [Version history](https://nextjs.org/docs/app/building-your-application/data-fetching/incremental-static-regeneration\#version-history)

| Version | Changes |
| --- | --- |
| `v14.1.0` | Custom `cacheHandler` is stable. |
| `v13.0.0` | App Router is introduced. |
| `v12.2.0` | Pages Router: On-Demand ISR is stable |
| `v12.0.0` | Pages Router: [Bot-aware ISR fallback](https://nextjs.org/blog/next-12#bot-aware-isr-fallback) added. |
| `v9.5.0` | Pages Router: [Stable ISR introduced](https://nextjs.org/blog/next-9-5). |

Was this helpful?

supported.

Send

## Next.js Redirecting Guide
Menu

Using App Router

Features available in /app

Using Latest Version

15.2.3

Using App Router

Features available in /app

Using Latest Version

15.2.3

[Building Your Application](https://nextjs.org/docs/app/building-your-application) [Routing](https://nextjs.org/docs/app/building-your-application/routing) Redirecting

# Redirecting

There are a few ways you can handle redirects in Next.js. This page will go through each available option, use cases, and how to manage large numbers of redirects.

| API | Purpose | Where | Status Code |
| --- | --- | --- | --- |
| [`redirect`](https://nextjs.org/docs/app/building-your-application/routing/redirecting#redirect-function) | Redirect user after a mutation or event | Server Components, Server Actions, Route Handlers | 307 (Temporary) or 303 (Server Action) |
| [`permanentRedirect`](https://nextjs.org/docs/app/building-your-application/routing/redirecting#permanentredirect-function) | Redirect user after a mutation or event | Server Components, Server Actions, Route Handlers | 308 (Permanent) |
| [`useRouter`](https://nextjs.org/docs/app/building-your-application/routing/redirecting#userouter-hook) | Perform a client-side navigation | Event Handlers in Client Components | N/A |
| [`redirects` in `next.config.js`](https://nextjs.org/docs/app/building-your-application/routing/redirecting#redirects-in-nextconfigjs) | Redirect an incoming request based on a path | `next.config.js` file | 307 (Temporary) or 308 (Permanent) |
| [`NextResponse.redirect`](https://nextjs.org/docs/app/building-your-application/routing/redirecting#nextresponseredirect-in-middleware) | Redirect an incoming request based on a condition | Middleware | Any |

## [`redirect` function](https://nextjs.org/docs/app/building-your-application/routing/redirecting\#redirect-function)

The `redirect` function allows you to redirect the user to another URL. You can call `redirect` in [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components), [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers), and [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations).

`redirect` is often used after a mutation or event. For example, creating a post:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { redirect } from 'next/navigation'
import { revalidatePath } from 'next/cache'

export async function createPost(id: string) {
  try {
    // Call database
  } catch (error) {
    // Handle errors
  }

  revalidatePath('/posts') // Update cached posts
  redirect(`/post/${id}`) // Navigate to the new post page
}
```

> **Good to know**:
>
> - `redirect` returns a 307 (Temporary Redirect) status code by default. When used in a Server Action, it returns a 303 (See Other), which is commonly used for redirecting to a success page as a result of a POST request.
> - `redirect` internally throws an error so it should be called outside of `try/catch` blocks.
> - `redirect` can be called in Client Components during the rendering process but not in event handlers. You can use the [`useRouter` hook](https://nextjs.org/docs/app/building-your-application/routing/redirecting#userouter-hook) instead.
> - `redirect` also accepts absolute URLs and can be used to redirect to external links.
> - If you'd like to redirect before the render process, use [`next.config.js`](https://nextjs.org/docs/app/building-your-application/routing/redirecting#redirects-in-nextconfigjs) or [Middleware](https://nextjs.org/docs/app/building-your-application/routing/redirecting#nextresponseredirect-in-middleware).

See the [`redirect` API reference](https://nextjs.org/docs/app/api-reference/functions/redirect) for more information.

## [`permanentRedirect` function](https://nextjs.org/docs/app/building-your-application/routing/redirecting\#permanentredirect-function)

The `permanentRedirect` function allows you to **permanently** redirect the user to another URL. You can call `permanentRedirect` in [Server Components](https://nextjs.org/docs/app/building-your-application/rendering/server-components), [Route Handlers](https://nextjs.org/docs/app/building-your-application/routing/route-handlers), and [Server Actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations).

`permanentRedirect` is often used after a mutation or event that changes an entity's canonical URL, such as updating a user's profile URL after they change their username:

app/actions.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use server'

import { permanentRedirect } from 'next/navigation'
import { revalidateTag } from 'next/cache'

export async function updateUsername(username: string, formData: FormData) {
  try {
    // Call database
  } catch (error) {
    // Handle errors
  }

  revalidateTag('username') // Update all references to the username
  permanentRedirect(`/profile/${username}`) // Navigate to the new user profile
}
```

> **Good to know**:
>
> - `permanentRedirect` returns a 308 (permanent redirect) status code by default.
> - `permanentRedirect` also accepts absolute URLs and can be used to redirect to external links.
> - If you'd like to redirect before the render process, use [`next.config.js`](https://nextjs.org/docs/app/building-your-application/routing/redirecting#redirects-in-nextconfigjs) or [Middleware](https://nextjs.org/docs/app/building-your-application/routing/redirecting#nextresponseredirect-in-middleware).

See the [`permanentRedirect` API reference](https://nextjs.org/docs/app/api-reference/functions/permanentRedirect) for more information.

## [`useRouter()` hook](https://nextjs.org/docs/app/building-your-application/routing/redirecting\#userouter-hook)

If you need to redirect inside an event handler in a Client Component, you can use the `push` method from the `useRouter` hook. For example:

app/page.tsx

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
'use client'

import { useRouter } from 'next/navigation'

export default function Page() {
  const router = useRouter()

  return (
    <button type="button" onClick={() => router.push('/dashboard')}>
      Dashboard
    </button>
  )
}
```

> **Good to know**:
>
> - If you don't need to programmatically navigate a user, you should use a [`<Link>`](https://nextjs.org/docs/app/api-reference/components/link) component.

See the [`useRouter` API reference](https://nextjs.org/docs/app/api-reference/functions/use-router) for more information.

## [`redirects` in `next.config.js`](https://nextjs.org/docs/app/building-your-application/routing/redirecting\#redirects-in-nextconfigjs)

The `redirects` option in the `next.config.js` file allows you to redirect an incoming request path to a different destination path. This is useful when you change the URL structure of pages or have a list of redirects that are known ahead of time.

`redirects` supports [path](https://nextjs.org/docs/app/api-reference/config/next-config-js/redirects#path-matching), [header, cookie, and query matching](https://nextjs.org/docs/app/api-reference/config/next-config-js/redirects#header-cookie-and-query-matching), giving you the flexibility to redirect users based on an incoming request.

To use `redirects`, add the option to your `next.config.js` file:

next.config.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import type { NextConfig } from 'next'

const nextConfig: NextConfig = {
  async redirects() {
    return [\
      // Basic redirect\
      {\
        source: '/about',\
        destination: '/',\
        permanent: true,\
      },\
      // Wildcard path matching\
      {\
        source: '/blog/:slug',\
        destination: '/news/:slug',\
        permanent: true,\
      },\
    ]
  },
}

export default nextConfig
```

See the [`redirects` API reference](https://nextjs.org/docs/app/api-reference/config/next-config-js/redirects) for more information.

> **Good to know**:
>
> - `redirects` can return a 307 (Temporary Redirect) or 308 (Permanent Redirect) status code with the `permanent` option.
> - `redirects` may have a limit on platforms. For example, on Vercel, there's a limit of 1,024 redirects. To manage a large number of redirects (1000+), consider creating a custom solution using [Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware). See [managing redirects at scale](https://nextjs.org/docs/app/building-your-application/routing/redirecting#managing-redirects-at-scale-advanced) for more.
> - `redirects` runs **before** Middleware.

## [`NextResponse.redirect` in Middleware](https://nextjs.org/docs/app/building-your-application/routing/redirecting\#nextresponseredirect-in-middleware)

Middleware allows you to run code before a request is completed. Then, based on the incoming request, redirect to a different URL using `NextResponse.redirect`. This is useful if you want to redirect users based on a condition (e.g. authentication, session management, etc) or have [a large number of redirects](https://nextjs.org/docs/app/building-your-application/routing/redirecting#managing-redirects-at-scale-advanced).

For example, to redirect the user to a `/login` page if they are not authenticated:

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextResponse, NextRequest } from 'next/server'
import { authenticate } from 'auth-provider'

export function middleware(request: NextRequest) {
  const isAuthenticated = authenticate(request)

  // If the user is authenticated, continue as normal
  if (isAuthenticated) {
    return NextResponse.next()
  }

  // Redirect to login page if not authenticated
  return NextResponse.redirect(new URL('/login', request.url))
}

export const config = {
  matcher: '/dashboard/:path*',
}
```

> **Good to know**:
>
> - Middleware runs **after** `redirects` in `next.config.js` and **before** rendering.

See the [Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware) documentation for more information.

## [Managing redirects at scale (advanced)](https://nextjs.org/docs/app/building-your-application/routing/redirecting\#managing-redirects-at-scale-advanced)

To manage a large number of redirects (1000+), you may consider creating a custom solution using Middleware. This allows you to handle redirects programmatically without having to redeploy your application.

To do this, you'll need to consider:

1. Creating and storing a redirect map.
2. Optimizing data lookup performance.

> **Next.js Example**: See our [Middleware with Bloom filter](https://redirects-bloom-filter.vercel.app/) example for an implementation of the recommendations below.

### [1\. Creating and storing a redirect map](https://nextjs.org/docs/app/building-your-application/routing/redirecting\#1-creating-and-storing-a-redirect-map)

A redirect map is a list of redirects that you can store in a database (usually a key-value store) or JSON file.

Consider the following data structure:

```code-block_code__isn_V
{
  "/old": {
    "destination": "/new",
    "permanent": true
  },
  "/blog/post-old": {
    "destination": "/blog/post-new",
    "permanent": true
  }
}
```

In [Middleware](https://nextjs.org/docs/app/building-your-application/routing/middleware), you can read from a database such as Vercel's [Edge Config](https://vercel.com/docs/storage/edge-config/get-started?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) or [Redis](https://vercel.com/docs/storage/vercel-kv?utm_source=next-site&utm_medium=docs&utm_campaign=next-website), and redirect the user based on the incoming request:

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextResponse, NextRequest } from 'next/server'
import { get } from '@vercel/edge-config'

type RedirectEntry = {
  destination: string
  permanent: boolean
}

export async function middleware(request: NextRequest) {
  const pathname = request.nextUrl.pathname
  const redirectData = await get(pathname)

  if (redirectData && typeof redirectData === 'string') {
    const redirectEntry: RedirectEntry = JSON.parse(redirectData)
    const statusCode = redirectEntry.permanent ? 308 : 307
    return NextResponse.redirect(redirectEntry.destination, statusCode)
  }

  // No redirect found, continue without redirecting
  return NextResponse.next()
}
```

### [2\. Optimizing data lookup performance](https://nextjs.org/docs/app/building-your-application/routing/redirecting\#2-optimizing-data-lookup-performance)

Reading a large dataset for every incoming request can be slow and expensive. There are two ways you can optimize data lookup performance:

- Use a database that is optimized for fast reads, such as [Vercel Edge Config](https://vercel.com/docs/storage/edge-config/get-started?utm_source=next-site&utm_medium=docs&utm_campaign=next-website) or [Redis](https://vercel.com/docs/storage/vercel-kv?utm_source=next-site&utm_medium=docs&utm_campaign=next-website).
- Use a data lookup strategy such as a [Bloom filter](https://en.wikipedia.org/wiki/Bloom_filter) to efficiently check if a redirect exists **before** reading the larger redirects file or database.

Considering the previous example, you can import a generated bloom filter file into Middleware, then, check if the incoming request pathname exists in the bloom filter.

If it does, forward the request to a [Route Handler](https://nextjs.org/docs/app/building-your-application/routing/route-handlers) which will check the actual file and redirect the user to the appropriate URL. This avoids importing a large redirects file into Middleware, which can slow down every incoming request.

middleware.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextResponse, NextRequest } from 'next/server'
import { ScalableBloomFilter } from 'bloom-filters'
import GeneratedBloomFilter from './redirects/bloom-filter.json'

type RedirectEntry = {
  destination: string
  permanent: boolean
}

// Initialize bloom filter from a generated JSON file
const bloomFilter = ScalableBloomFilter.fromJSON(GeneratedBloomFilter as any)

export async function middleware(request: NextRequest) {
  // Get the path for the incoming request
  const pathname = request.nextUrl.pathname

  // Check if the path is in the bloom filter
  if (bloomFilter.has(pathname)) {
    // Forward the pathname to the Route Handler
    const api = new URL(
      `/api/redirects?pathname=${encodeURIComponent(request.nextUrl.pathname)}`,
      request.nextUrl.origin
    )

    try {
      // Fetch redirect data from the Route Handler
      const redirectData = await fetch(api)

      if (redirectData.ok) {
        const redirectEntry: RedirectEntry | undefined =
          await redirectData.json()

        if (redirectEntry) {
          // Determine the status code
          const statusCode = redirectEntry.permanent ? 308 : 307

          // Redirect to the destination
          return NextResponse.redirect(redirectEntry.destination, statusCode)
        }
      }
    } catch (error) {
      console.error(error)
    }
  }

  // No redirect found, continue the request without redirecting
  return NextResponse.next()
}
```

Then, in the Route Handler:

app/api/redirects/route.ts

TypeScript

JavaScriptTypeScript

```code-block_code__isn_V
import { NextRequest, NextResponse } from 'next/server'
import redirects from '@/app/redirects/redirects.json'

type RedirectEntry = {
  destination: string
  permanent: boolean
}

export function GET(request: NextRequest) {
  const pathname = request.nextUrl.searchParams.get('pathname')
  if (!pathname) {
    return new Response('Bad Request', { status: 400 })
  }

  // Get the redirect entry from the redirects.json file
  const redirect = (redirects as Record<string, RedirectEntry>)[pathname]

  // Account for bloom filter false positives
  if (!redirect) {
    return new Response('No redirect', { status: 400 })
  }

  // Return the redirect entry
  return NextResponse.json(redirect)
}
```

> **Good to know:**
>
> - To generate a bloom filter, you can use a library like [`bloom-filters`](https://www.npmjs.com/package/bloom-filters).
> - You should validate requests made to your Route Handler to prevent malicious requests.

## Next Steps

[**redirect** \\
API Reference for the redirect function.](https://nextjs.org/docs/app/api-reference/functions/redirect) [**permanentRedirect** \\
API Reference for the permanentRedirect function.](https://nextjs.org/docs/app/api-reference/functions/permanentRedirect) [**Middleware** \\
Learn how to use Middleware to run code before a request is completed.](https://nextjs.org/docs/app/building-your-application/routing/middleware) [**redirects** \\
Add redirects to your Next.js app.](https://nextjs.org/docs/app/api-reference/config/next-config-js/redirects)

Was this helpful?

supported.

Send

