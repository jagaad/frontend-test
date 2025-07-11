# Frontend Coding Challenge 🚀

## ⚠️ AI Usage Policy ⚠️

**❌ PROHIBITED:** Using AI tools (ChatGPT, GitHub Copilot, etc.) to generate complete solutions. Any AI-generated submissions will be **immediately disqualified**.

**✅ ALLOWED:** Using AI for learning concepts or debugging specific issues, but you must write the actual code yourself.

---

Welcome to our frontend coding challenge! This is a great opportunity for you to showcase your frontend skills.
We're excited to see what you come up with! 🎨🖥️

## Overview 🌐

Your task is to create a simple e-commerce-like application that fetches product data
from a provided JSON file on GitHub and displays them with some interactive features.

Use any modern frontend framework/library (e.g., React, Vue, Angular, Nuxt, Next) with TypeScript.
Any styling solution is accepted.

## Data Source 📊

You will be fetching the product data from the [`mock-products.json`](mock-products.json) raw JSON file hosted in this repository.
Here's the link to the JSON file:

```text
https://raw.githubusercontent.com/jagaad/frontend-test/main/mock-products.json
```

> The data was generated using [`@faker-js/faker`](https://fakerjs.dev/)

Each product in the JSON file has the following fields:

- `image`: URL to the product image (string, url)
- `title`: Name of the product (string)
- `description`: Brief description of the product (string)
- `price`: Price of the product (string)
- `currency` Currency of the price (string, ISO 4217)

## Requirements 📝

### 1. Home Page 🏠

- Display 10 products at a time.
- Each product should show the `image`, `title`, `description`, `price` and `currency`.
- Ensure the design is responsive and looks good on both desktop and mobile.

### 2. Pagination 📄

- Implement client-side pagination for the products.
- Users should be able to navigate through different pages to view all the products.

### 3. Client-Side Cart 🛒

- Users should be able to add products to their cart.
- Display a cart icon with a counter indicating the number of items and total sum of the cart.
- Users should be able to view their cart and remove items if needed.

### 4. Client-Side Wish List 💖

- Users should be able to add products to their wish list.
- Display a heart or star icon indicating the wish list.
- Users should be able to view their wish list and remove items if needed.

## Bonus Points 🌟

Add anything that you consider would impress us. Example:

- Write documentation how to get started with the project
- Use Conventional Commits
- Add animations or transitions for better user experience.
- Consider using Server Side Rendering (SSR)
- Use `Intl` API to render `price` and `currency`
- Implement a search functionality to filter products.
- Add a CHANGELOG with version releases.
- Create a Dockerfile that makes the project a ready image for deploy.
- Deploy it somewhere (e.g. Vercel, Netlify) as a static website.
- Add some unit or E2E tests.
- Use a library such as CSS Modules, Styled Components, Bootstrap, Tailwind CSS, or Material-UI for styling.
- Make use of Prettier, ESLint, Stylelint or Commitlint.
- Configure git hooks to format code at commit.

## Submission Guidelines 📮

- Create a public repository on any platform of GitHub or GitLab platform.
- Push the code in the repository.
- Contact the HR with the link to the repository to be reviewed.
- The challenge is designed to be moderately challenging, striking a balance between simplicity and complexity.
- This challenge is expected to be done in approximately one day.

## Evaluation Criteria 🧐

- Code quality and organization.
- Responsiveness and design.
- Functionality and user experience.
- Bonus features implemented.

## Wrapping Up 🎁

We hope you enjoy this challenge! Remember, it's not just about getting it done, but also about showcasing your creativity, skills, and approach to problem-solving. Happy coding! 🎉👩‍💻👨‍💻

---

**Note**: Please make sure to test your application thoroughly before submitting. If you have any questions or need clarifications, feel free to reach out.
