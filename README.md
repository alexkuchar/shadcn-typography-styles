# ShadCN Typography Styles - Copy-Paste Ready

```css
@layer base {
    h1 {
        @apply scroll-m-20 text-4xl font-extrabold tracking-tight lg:text-5xl;
    }
    h2 {
        @apply scroll-m-20 pb-2 text-3xl font-semibold tracking-tight first:mt-0;
    }
    h3 {
        @apply scroll-m-20 text-2xl font-semibold tracking-tight;
    }
    h4 {
        @apply scroll-m-20 text-xl font-semibold tracking-tight;
    }
    p {
        @apply leading-7 [&:not(:first-child)]:mt-6;
    }
    blockquote {
        @apply mt-6 border-l-2 pl-6 italic;
    }
    ul {
        @apply my-6 ml-6 list-disc [&>li]:mt-2;
    }
    code {
        @apply relative rounded bg-muted px-[0.3rem] py-[0.2rem] font-mono text-sm font-semibold;
    }
    .lead {
        @apply text-xl text-muted-foreground;
    }
    .large {
        @apply text-lg font-semibold;
    }
    small {
        @apply text-sm font-medium leading-none;
    }
    .muted {
        @apply text-sm text-muted-foreground;
    }
}
```