# CSS-Only Animations

Simple, reusable CSS animations using custom attributes.

## Usage

1. Include the CSS file in your project:

   ```html
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/austin-thesing/quick-web-animations@latest/dist/css-only/css-anim.min.css" />
   ```

2. Add the `css-anim` attribute to elements you want to animate.

Example:

```html
<div css-anim="slide-up">I'll animate immediately</div>
```

## Available Animations

- Slide Up: `css-anim="slide-up"`
- Slide Left: `css-anim="slide-left"`
- Slide Right: `css-anim="slide-right"`
- Slide Down: `css-anim="slide-down"`
- Fade In: `css-anim="fade-in"`
- Flip: `css-anim="flip"`

## Delayed Animations\*

- Slide Up: `css-anim="slide-up-300"` (300ms delay)
- Fade In: `css-anim="fade-in-500"` (500ms delay)
- Flip: `css-anim="flip-200"` (200ms delay)

\*Delays available in 100ms increments up to 700ms.
