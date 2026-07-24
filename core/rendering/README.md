# Rendering

## Responsibility

### What problem does Rendering solve?

Transforms application state into a visible user interface. *(Turns data into what users see.)*

### Why does Rendering exist?

To display data and user interactions on the screen. *(Makes the application visible and usable.)*

### When is Rendering needed?

Whenever the UI is first displayed or updated. *(Every screen load or state change.)*

---

## Concepts

### Declarative UI

Describe what the UI should look like for a given state. *(Describe the destination, not the steps.)*

### Virtual DOM

An in-memory representation of the real DOM. *(A working copy before real changes.)*

### Reconciliation

The process of comparing the old and new Virtual DOM. *(Find what changed.)*

### Rendering Pipeline

The sequence of steps from state change to pixels on the screen. *(The journey from data to display.)*

### Browser Rendering

The browser process of layout, paint, and compositing. *(How the browser draws the page.)*

### Rendering Lifecycle

The stages a component goes through while rendering. *(A component's rendering journey.)*

### Hydration

Attaches JavaScript to server-rendered HTML. *(Makes static pages interactive.)*

---

## Patterns

### Client-Side Rendering (CSR)

The browser renders the application. *(Browser builds the UI.)*

### Server-Side Rendering (SSR)

The server renders the initial HTML. *(Server builds the first page.)*

### Static Site Generation (SSG)

Pages are generated during build time. *(Build once, serve many.)*

### Incremental Static Regeneration (ISR)

Static pages are regenerated after deployment. *(Static pages that stay fresh.)*

### Streaming Rendering

UI is sent to the browser in chunks. *(Show content as it becomes ready.)*

### Suspense

Displays fallback content while waiting for data or components. *(Show something while waiting.)*

### Virtualization

Render only visible items in large lists. *(Render only what's on screen.)*

### Memoization

Reuse previous render results when nothing changes. *(Avoid unnecessary work.)*

---

## Tools

### Frameworks

- React *(Declarative UI framework.)*
- Next.js *(React framework with multiple rendering strategies.)*
- Vue *(Progressive UI framework.)*
- Angular *(Full-featured frontend framework.)*
- Svelte *(Compiler-based UI framework.)*

### Libraries

- React DOM *(Renders React components to the DOM.)*
- React Window *(Virtualizes large lists.)*
- TanStack Virtual *(Efficient list virtualization.)*

### Utilities

- React DevTools *(Inspect component rendering.)*
- Chrome DevTools *(Analyze browser rendering and performance.)*
- Lighthouse *(Measure rendering performance and Web Vitals.)*

---

## Laboratory

- Lab 01 – Basic Rendering