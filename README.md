### Custom CSS Framework - Custom Tailwind

## Description

A custom CSS framework built with Sass providing a consistent theme for HTML elements and utility classes for common styling needs.

## Installation

#   Clone the repository:
```bash
git clone https://github.com/yourusername/custom-css-framework.git

```
#   Navigate to the project directory:
```bash
cd custom-css-framework

```
#   Install dependencies:
```bash
npm install
```
#   Compile the Sass files to CSS:
```bash
npm run build-css
```
#   Include the compiled main.css file in your HTML:
```html

    <link rel="stylesheet" href="path/to/css/main.css">
```

## Usage

Use the provided classes to style your HTML elements. Below are some examples:

#   Buttons
```html
<button class="button primary">Primary Button</button>
<button class="button secondary">Secondary Button</button>
<button class="button danger">Danger Button</button>
```
#   Form
```html
<form>
  <div class="form-group">
    <label for="inputEmail">Email address</label>
    <input type="email" class="form-control" id="inputEmail" placeholder="Enter email">
  </div>
  <div class="form-group">
    <label for="inputPassword">Password</label>
    <input type="password" class="form-control" id="inputPassword" placeholder="Password">
  </div>
  <button type="submit" class="button primary">Submit</button>
</form>
```

#   Cards
```html
<div class="card">
  <h3 class="card-header">Card Title</h3>
  <p>This is a card with some content.</p>
  <button class="button primary">Read More</button>
</div>
```
#   Grid
```html
<div class="d-flex">
  <div class="p-3 m-2 bg-primary text-white">Flex Item 1</div>
  <div class="p-3 m-2 bg-secondary text-black">Flex Item 2</div>
  <div class="p-3 m-2 bg-danger text-white">Flex Item 3</div>
</div>
```

#   Table
```html
<table class="table">
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
      <th>City</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="table-primary">John Doe</td>
      <td>28</td>
      <td>New York</td>
    </tr>
    <tr>
      <td class="table-secondary">Jane Smith</td>
      <td>34</td>
      <td>San Francisco</td>
    </tr>
    <tr>
      <td class="table-danger">Mike Johnson</td>
      <td>45</td>
      <td>Los Angeles</td>
    </tr>
  </tbody>
</table>
```
##   Customization

Modify the variables in _variables.scss to customize the theme. For example:
#   Colors
```scss
$colors: (
  "primary": #3490dc,
  "secondary": #ffed4a,
  "danger": #e3342f,
  "success": #38c172,
  "warning": #f6993f,
  "info": #6cb2eb,
  "light": #f8f9fa,
  "dark": #343a40,
  "gray": #6c757d,
  "white": #ffffff,
  "black": #000000,
  "purple": #6f42c1,
  "pink": #e83e8c,
  "orange": #fd7e14,
  "teal": #20c997,
);
```

#   Spacing
```sccs
$spacings: (
  0: 0,
  1: 0.25rem,
  2: 0.5rem,
  3: 1rem,
  4: 1.5rem,
  5: 2rem,
  6: 2.5rem,
  7: 3rem,
  8: 3.5rem,
  9: 4rem,
  10: 5rem,
);
```

#   Fonts
```sccs
$font-sizes: (
  "xs": 0.75rem,
  "sm": 0.875rem,
  "base": 1rem,
  "lg": 1.125rem,
  "xl": 1.25rem,
  "2xl": 1.5rem,
  "3xl": 1.875rem,
  "4xl": 2.25rem,
  "5xl": 3rem,
);

$font-weights: (
  "light": 300,
  "normal": 400,
  "medium": 500,
  "bold": 700,
);

$font-family-base: 'Helvetica, Arial, sans-serif';
```

Customize these variables to change the default theme according to your preferences.
