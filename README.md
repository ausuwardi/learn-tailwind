# Tailwind CSS Tutorial Recap

## Setup

[Link to lesson](https://tailwindcss.com/course/setting-up-tailwind-and-postcss)

1. Install project dependencies:

    - postcss
    - postcss-cli
    - autoprefixer
    - tailwind

2. Create tailwind.config.js with tailwind command
3. Create postcss.config.js that loads tailwind and autoprefixer
4. Create css/tailwind.css that basically loads tailwind's built-ins
5. Generate public/build/tailwind.css (see build script in package.json)
6. public/build/tailwind.css can be used


## The Utility-First Workflow

[Link to lesson](https://tailwindcss.com/course/the-utility-first-workflow)

Tailwind provides utility classes that can be mix-matched to get desired result. Some of notable utilities used in this lesson:

- Background (bg)
- Padding (px, py)
- Height (h)
- Margin (m, mt)
- Rounded edges (rounded)
- Drop shadows (shadow)
- Text (text)
- Font (font, leading, tracking)

## Responsive Design

By adding `max-w-md` and `mx-auto` in the wrapper element, we constrained the width of the page. Further, we can add responsive breakpoints from tailwind `sm, md, lg, xl` for example `md:bg-red-500` to set background color to red-500 on md breakpoint. All utility classes are responsive by prefixing with breakpoints.
