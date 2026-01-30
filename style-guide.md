:root {
  /* Colors */
  --white: hsl(0, 0%, 100%);

  --stone-100: hsl(30, 54%, 90%);
  --stone-150: hsl(30, 18%, 87%);
  --stone-600: hsl(30, 10%, 34%);
  --stone-900: hsl(24, 5%, 18%);

  --brown-800: hsl(14, 45%, 36%);

  --rose-800: hsl(332, 51%, 32%);
  --rose-50: hsl(330, 100%, 98%);

  /* Typography */
  --font-body: "Outfit", sans-serif;
  --font-heading: "Young Serif", serif;
  --font-size-body: 16px;
}

/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Body */
body {
  font-family: var(--font-body);
  font-size: var(--font-size-body);
  line-height: 1.6;
  background-color: var(--stone-100);
  color: var(--stone-600);
  padding: 2rem 1rem;
}

/* Main Card */
main {
  background-color: var(--white);
  max-width: 736px;
  margin: 0 auto;
  padding: 2rem;
  border-radius: 24px;
}

/* Image */
main img {
  width: 100%;
  display: block;
  border-radius: 12px;
  margin-bottom: 1.5rem;
}

/* Headings */
h1 {
  font-family: var(--font-heading);
  font-size: 2.5rem;
  color: var(--stone-900);
  margin-bottom: 1rem;
}

h2 {
  font-family: var(--font-heading);
  font-size: 1.75rem;
  color: var(--brown-800);
  margin: 2rem 0 1rem;
}

h3 {
  font-size: 1.125rem;
  color: var(--rose-800);
  margin-bottom: 0.75rem;
}

/* Text */
p {
  margin-bottom: 1.25rem;
}

/* Preparation Section */
.prep {
  background-color: var(--rose-50);
  padding: 1.5rem;
  border-radius: 12px;
  margin: 1.5rem 0;
}

.prep ul {
  padding-left: 1.25rem;
}

.prep li {
  margin-bottom: 0.5rem;
}

/* Lists */
ul,
ol {
  padding-left: 1.5rem;
}

li {
  margin-bottom: 0.5rem;
}

ol li::marker {
  color: var(--brown-800);
  font-weight: 700;
}

/* Nutrition */
.nutrition p {
  margin-bottom: 1rem;
}

.nutrition .row {
  display: flex;
  justify-content: space-between;
  padding: 0.75rem 0;
  border-bottom: 1px solid var(--stone-150);
}

.nutrition .row span:last-child {
  color: var(--brown-800);
  font-weight: 700;
}

/* Mobile (375px) */
@media (max-width: 375px) {
  body {
    padding: 0;
  }

  main {
    border-radius: 0;
    padding: 1.5rem;
  }
}
