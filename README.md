![Frontend Mentor](https://img.shields.io/badge/Frontend%20Mentor-Challenge-4BC0F0?logo=frontendmentor&logoColor=white) ![#7](https://img.shields.io/badge/%237-red) [![Live Preview](https://img.shields.io/badge/Live-Preview-green)](https://svitlanarudova.github.io/four-card-feature-section/)

# Frontend Mentor - Four card feature section
![Design preview for the QR code component coding challenge](./preview.jpg)

## Project Overview 📋 

This is my solution to the Four card feature section challenge on Frontend Mentor.
This project helped me practice responsive design techniques and modern CSS approaches.

## Built With 🛠️

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox and Grid
- **`clamp()` function** for responsive typography and spacing
- **Component-based approach** to organizing styles
- Logical CSS properties (`inline-size`, `block-size`, `margin-block`)
- Mobile-first workflow

##  What I Learned💡

1. **Responsive Design with `clamp()`**: I learned to use `clamp()` for fluid scaling of spacing and sizes without media queries:
```css
padding-inline: clamp(var(--padding-md), 1.092rem + 8.143vw, var(--padding-lg));
```

2. **Local CSS Variables**: I applied local CSS variables for each component instead of global ones, which improves encapsulation and reusability

3. **Component-Based Approach**: 

   -- I organized styles following a component principle with BEM-like methodology, making the code modular and easy to maintai
   
   -- Each component has its own scoped variables and styles, which prevents conflicts and makes the codebase more scalable


## Challenges I Faced 🚧

I’m still learning how to build a clear and scalable variable system — using meaningful names and keeping the code clean and easy to maintain.

##  Acknowledgments 🙏
Thanks to Frontend Mentor for providing this challenge and to the community for their helpful feedback and resources on modern CSS techniques.

