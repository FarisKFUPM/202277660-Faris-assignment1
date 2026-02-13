# AI Usage Report

## Tools Used & Use Cases

### ChatGPT (OpenAI)

I used ChatGPT throughout the development of this portfolio project as a **learning and productivity assistant**. Below are the specific ways I used it:

1. **Design Planning & Procedure**
   - I described my assignment requirements to ChatGPT and asked for a step-by-step procedure on how to approach building a responsive portfolio from scratch.
   - It helped me break down the work into manageable phases: project setup, HTML structure, CSS styling, JavaScript interactivity, and documentation.
   - *Example prompt*: "I need to build a responsive portfolio with About Me, Projects, and Contact sections. What's the best order to implement these?"

2. **Implementation Guidance**
   - For each section (hero, about, projects, contact), I asked ChatGPT how to structure the HTML semantically and which CSS techniques (Flexbox, Grid, media queries) to use for responsive layouts.
   - *Example*: I asked how to create a dark/light mode toggle that persists using `localStorage`, and ChatGPT explained the concept. I then implemented it step by step, adapting the logic to fit my own design.

3. **Error Fixing & Debugging**
   - When my profile image wasn't displaying correctly (file extension case mismatch between `.JPG` and `.jpg`), I described the issue to ChatGPT, which helped me identify that file paths are case-sensitive on web servers.
   - When my Git repository was accidentally initialized in the home directory, ChatGPT helped me understand the issue and provided the correct cleanup commands.

4. **Explaining Concepts**
   - I asked ChatGPT to explain CSS concepts like `object-fit: cover` for circular profile images, CSS variables for theming, and how media queries work at different breakpoints.
   - It also explained how `DOMContentLoaded` works and why it's important for ensuring the DOM is ready before running JavaScript.

5. **Rubric Review**
   - After completing each section, I shared the rubric criteria with ChatGPT and asked it to check if my implementation met the requirements. This helped me catch missing items and ensure completeness.

---

## Benefits & Challenges

### Benefits
- **Structured Workflow**: ChatGPT helped me plan the project step by step instead of jumping in randomly. This made the development process smoother and more organized.
- **Faster Debugging**: Instead of spending hours searching StackOverflow, I could describe my exact error and get a targeted explanation with a solution.
- **Learning While Building**: Every suggestion came with an explanation, so I wasn't just copying code — I was understanding *why* each piece works.
- **Quality Assurance**: Using ChatGPT to review my work against the rubric helped ensure I didn't miss any requirements.

### Challenges
- **Generic Suggestions**: Some initial suggestions were too generic and didn't match my personal style. I had to refine my prompts to get more specific and relevant output.
- **Context Limitations**: ChatGPT doesn't see my actual project files, so I had to describe my code structure clearly. Sometimes the suggestions didn't perfectly fit my existing code and needed manual adjustment.
- **Over-reliance Risk**: It was tempting to ask for full code blocks, but I made a conscious effort to ask for explanations and concepts first, then write the code myself.

---

## Learning Outcomes

1. **CSS Variables & Theming**: I learned how to use CSS custom properties (`:root` variables) to create a consistent color scheme that can switch between light and dark modes with a single class toggle. This is far more maintainable than hardcoding color values throughout the stylesheet.

2. **Responsive Design Techniques**: Through ChatGPT's explanations, I understood the mobile-first approach and how to use media queries at `768px` and `480px` breakpoints. I learned the difference between Flexbox (for one-dimensional layouts) and Grid (for two-dimensional layouts).

3. **JavaScript DOM Manipulation**: I gained practical experience with `localStorage` for persisting user preferences, `addEventListener` for handling user interactions, and dynamic content updates based on the time of day.

4. **Semantic HTML**: I reinforced the importance of using tags like `<header>`, `<main>`, `<section>`, `<article>`, and `<footer>` for accessibility and SEO rather than using generic `<div>` elements everywhere.

5. **Git Workflow**: I learned how to properly initialize a repository, make meaningful commits, and push to GitHub. I also learned to troubleshoot common Git issues like accidental repository initialization in wrong directories.

---

## Responsible Use & Modifications

I used ChatGPT as a **guide and reviewer**, not as a code generator. Here is how I ensured responsible use:

- **Understanding Before Implementing**: For every suggestion, I asked ChatGPT to explain the reasoning behind it before adding it to my project. I didn't accept any code without understanding what it does.
- **Personal Customization**: All content (About Me text, project descriptions, tagline) was written by me. ChatGPT only helped with structuring the HTML and CSS around my personal content.
- **Code Review & Testing**: After receiving any guidance, I manually tested the code in my browser at different screen sizes, verified the dark mode toggle, and checked the contact form behavior.
- **Iterative Improvement**: I didn't use ChatGPT's first suggestion blindly. For example, the initial CSS color scheme was too plain, so I iterated on it to create a more polished, professional look that matched my vision.
- **Rubric Compliance**: I cross-referenced all AI suggestions against the assignment rubric to ensure they met the specific requirements, rather than implementing features that looked good but weren't required.

All work submitted is my own, enhanced and verified with the assistance of AI tools as permitted by the assignment guidelines.
