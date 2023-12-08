# Introduction

Inspired by [this repo](https://github.com/nmn/nextjs-app-dir-stylex/blob/1ae35c91819ece812097186942f0a7096ef81ebc/app/layout.tsx#L4).

Petersan(named after one of my friends), is a starter template with NextJS 14 App router and StyleX integrated. I would normally use Tailwind for styling, just for the sake of easiness. But I do admit writing CSS is more creative than using class based Tailwind.

### Run local

```
bun install
bun run dev
```

> [!Tip]
> The following is what I asked Bard(Gemini Pro) today, it's better than GPT 3.5, no money for GPT 4.0 tho.😑

## StyleX

**Strengths:**

- **Modular and Composable:** Styles are defined in separate files, making them easy to organize and reuse.
- **Themeable:** Easily create different themes for your application.
- **Flexible:** Can be used with other CSS frameworks or libraries.
- **Lightweight:** Adds minimal overhead to your code.

**Weaknesses:**

- **Less Mature:** StyleX is a relatively new library, so it may not be as widely used or have as much community support as Tailwind CSS.
- **Requires More Setup:** Styles need to be defined in separate files, adding some overhead to your project.
- **Less Discoverable:** May be more challenging to find examples of how to use StyleX compared to Tailwind CSS.

## Tailwind CSS

**Strengths:**

- **Utility-First:** Provides a set of utility classes for styling components, which can be faster and more efficient than writing custom CSS.
- **Widely Used:** Large and active community, offering ample documentation, examples, and support.
- **Easy to Learn:** Simple and straightforward syntax makes it easy to pick up.
- **No Need for Separate Style Files:** Write styles directly in HTML or JSX files.

**Weaknesses:**

- **Less Flexible:** Tailwind is opinionated and encourages adherence to its conventions, potentially limiting flexibility for specific design needs.
- **Can Be Verbose:** Class names in Tailwind can be long and verbose, potentially reducing HTML file readability.
- **Larger Bundle Size:** The Tailwind CSS library is relatively large, contributing to increased bundle size.

### Additional Considerations

Here are some extra factors to consider when choosing between StyleX and Tailwind CSS:

- **Size of Your Project:** For small projects, StyleX may be a better choice due to its lightweight nature.
- **Complexity of Your Styles:** If your styles are complex or you require a high degree of flexibility, StyleX may be more suitable.
- **Team's Experience:** If your team is already familiar with Tailwind CSS, it may be more straightforward to use than StyleX.
