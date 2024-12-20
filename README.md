# VK CSS Framework via CDN

This is a simple, lightweight CSS framework that helps you style your website quickly. You can easily add this framework to your project by including a CDN link in your HTML file.

## Getting Started

### Installation

To use this framework, add the following `<link>` tag in the `<head>` section of your HTML file: [including tailwind css]

```html
<link rel="stylesheet" href="https://kalees64.github.io/vk-cdn/vk-cdn.css" />
```

(or)

To use this framework, add the following `<link>` tag in the `<head>` section of your HTML file: [without tailwind css]

```html
<link rel="stylesheet" href="https://kalees64.github.io/vk-cdn-output/vk-cdn.css" />
```

(or)

To use this framework, add the following `@import url()` tag in the CSS file:

```css
@import url("https://kalees64.github.io/vk-cdn/vk-cdn.css");
```

## Documentation

visit below link for the documentation

[VK-CSS-DOCUMENT](https://kalees64.github.io/vk-cdn)

visit below link for samble outputs

[VK-CSS-COMPONENTS](https://vk-cdn.vercel.app/)

## Usage/Examples

### Button

```html
<button class="vk-btn">Button</button>
<button class="vk-btn-red">Button</button>
<button class="vk-btn-red-r">Button</button>
<button class="vk-btn-outline-red">Button</button>
<button class="vk-btn-outline-red-r">Button</button>
<button class="vk-btn-red-g">Button</button>
<button class="vk-btn-red-g-r">Button</button>
```

### Badge

```html
<span class="vk-badge-red">Danger</span>
<span class="vk-badge-blue">Danger</span>
<span class="vk-badge-green">Danger</span>
<span class="vk-badge-yellow">Danger</span>
<span class="vk-badge-cyan">Danger</span>
<span class="vk-badge-teal">Danger</span>
<span class="vk-badge-purple">Danger</span>
<span class="vk-badge-lime">Danger</span>
```

### Card

```html
<div class="w-64 vk-card">
  <h1 class="vk-card-title">Card Title</h1>
  <p class="vk-card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa cupiditate commodi minima molestias assumenda unde maiores perspiciatis consequuntur. Corporis cumque rerum doloribus illum?</p>
</div>
```

### Links

```html
<a href="#" class="vk-link">Link</a>
<a href="#" class="vk-link-dark">Link</a>
<a href="#" class="vk-link-blue">Link</a>
<a href="#" class="vk-link-cyan">Link</a>
<a href="#" class="vk-link-light">Link</a>
<a href="#" class="vk-link-blue-d">Link</a>
<a href="#" class="vk-link-cyan-d">Link</a>
<a href="#" class="vk-link-blue-cd">Link</a>
<a href="#" class="vk-link-cyan-cd">Link</a>
<a href="#" class="vk-link-blue-cw">Link</a>
<a href="#" class="vk-link-cyan-cw">Link</a>
```

### Links with Underline

```html
<a href="#" class="vk-link-u">Link</a>
<a href="#" class="vk-link-dark-u">Link</a>
<a href="#" class="vk-link-blue-u">Link</a>
<a href="#" class="vk-link-cyan-u">Link</a>
<a href="#" class="vk-link-light-u">Link</a>
<a href="#" class="vk-link-blue-d-u">Link</a>
<a href="#" class="vk-link-cyan-d-u">Link</a>
<a href="#" class="vk-link-blue-cd-u">Link</a>
<a href="#" class="vk-link-cyan-cd-u">Link</a>
<a href="#" class="vk-link-blue-cw-u">Link</a>
<a href="#" class="vk-link-cyan-cw-u">Link</a>
```

### Table

```html
<table class="vk-table">
  <thead>
    <tr>
      <th>S.no</th>
      <th>Class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Button</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Badge</td>
    </tr>
  </tbody>
</table>
```

### Table Dark

```html
<table class="vk-table-dark">
  <thead>
    <tr>
      <th>S.no</th>
      <th>Class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Button</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Badge</td>
    </tr>
  </tbody>
</table>
```

### Table Hover

```html
<table class="vk-table-dark vk-table-hover">
  <thead>
    <tr>
      <th>S.no</th>
      <th>Class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Button</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Badge</td>
    </tr>
  </tbody>
</table>
```

### Borderless Table

```html
<table class="vk-table-borderless">
  <thead>
    <tr>
      <th>S.no</th>
      <th>Class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Button</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Badge</td>
    </tr>
  </tbody>
</table>
```

### Spinner

```html
<span class="vk-spinner"></span>
<span class="vk-spinner-dark"></span>
<span class="vk-spinner-blue"></span>
<span class="vk-spinner-red"></span>
<span class="vk-spinner-yellow"></span>
<span class="vk-spinner-green"></span>
<span class="vk-spinner-cyan"></span>
<span class="vk-spinner-teal"></span>
<span class="vk-spinner-purple"></span>
<span class="vk-spinner-lime"></span>
<span class="vk-spinner-pink"></span>
```

```html
<span class="vk-spinner-md"></span>
<span class="vk-spinner-dark-md"></span>
<span class="vk-spinner-blue-md"></span>
<span class="vk-spinner-red-md"></span>
<span class="vk-spinner-yellow-md"></span>
<span class="vk-spinner-green-md"></span>
<span class="vk-spinner-cyan-md"></span>
<span class="vk-spinner-teal-md"></span>
<span class="vk-spinner-purple-md"></span>
<span class="vk-spinner-lime-md"></span>
<span class="vk-spinner-pink-md"></span>
```

### Placeholder

```html
<span class="vk-placeholder size-32"></span>
<span class="vk-placeholder w-32 h-2"></span>
<span class="vk-placeholder h-32"></span>
<span class="vk-placeholder w-40 h-6"></span>
<span class="vk-placeholder h-32 w-6"></span>
<span class="vk-placeholder h-32 w-64"></span>
```

### Form Inputs

```html
<input type="text" class="vk-form-input" placeholder="Text " />
<input type="text" class="vk-form-input-invalid" placeholder="Text Invalid" />
<input type="text" class="vk-form-input-valid" placeholder="Text Valid" />
```

### Form Labels

```html
<label class="vk-form-label">Label</label>
<label class="vk-form-label-red">Label</label>
<label class="vk-form-label-green">Label</label>
<label class="vk-form-label-yellow">Label</label>
<label class="vk-form-label-blue">Label</label>
```

### Alerts

```html
<span class="vk-alert-red">Alert</span>
<span class="vk-alert-green">Alert</span>
<span class="vk-alert-yellow">Alert</span>
<span class="vk-alert-blue">Alert</span>
```

```html
<span class="vk-alert-red-md">Alert</span>
<span class="vk-alert-green-md">Alert</span>
<span class="vk-alert-yellow-md">Alert</span>
<span class="vk-alert-blue-md">Alert</span>
```

```html
<span class="vk-alert-red-lg">Alert</span>
<span class="vk-alert-green-lg">Alert</span>
<span class="vk-alert-yellow-lg">Alert</span>
<span class="vk-alert-blue-lg">Alert</span>
```

### Alert Boxes

```html
<span class="vk-alert-red-box">Alert</span>
<span class="vk-alert-green-box">Alert</span>
<span class="vk-alert-yellow-box">Alert</span>
<span class="vk-alert-blue-box">Alert</span>
```

### Headings

```html
<h1 class="vk-h1">Heading 1</h1>
<h1 class="vk-h2">Heading 2</h1>
<h1 class="vk-h3">Heading 3</h1>
<h1 class="vk-h4">Heading 4</h1>
<h1 class="vk-h5">Heading 5</h1>
<h1 class="vk-h6">Heading 6</h1>
```

### Sidebar Links

```html
<div class="flex gap-2 flex-wrap">
  <div class="flex flex-col gap-2 bg-white p-3 basis-64 rounded">
    <a href="#" class="vk-sidebar-link">Home</a>
    <a href="#" class="vk-sidebar-link">Home</a>
    <a href="#" class="vk-sidebar-link">Home</a>
  </div>
  <div class="flex flex-col gap-2 bg-black p-3 basis-64 rounded">
    <a href="#" class="vk-sidebar-link-dark">Home</a>
    <a href="#" class="vk-sidebar-link-dark">Home</a>
    <a href="#" class="vk-sidebar-link-dark">Home</a>
  </div>
  <div class="flex flex-col gap-2 bg-blue-600 p-3 basis-64 rounded">
    <a href="#" class="vk-sidebar-link-blue">Home</a>
    <a href="#" class="vk-sidebar-link-blue">Home</a>
    <a href="#" class="vk-sidebar-link-blue">Home</a>
  </div>
  <div class="flex flex-col gap-2 bg-red-600 p-3 basis-64 rounded">
    <a href="#" class="vk-sidebar-link-red">Home</a>
    <a href="#" class="vk-sidebar-link-red">Home</a>
    <a href="#" class="vk-sidebar-link-red">Home</a>
  </div>
  <div class="flex flex-col gap-2 bg-green-600 p-3 basis-64 rounded">
    <a href="#" class="vk-sidebar-link-green">Home</a>
    <a href="#" class="vk-sidebar-link-green">Home</a>
    <a href="#" class="vk-sidebar-link-green">Home</a>
  </div>
</div>
```

### Navbar Brand

```html
<div class="flex gap-2 flex-wrap">
  <h1 class="vk-nav-brand">Brand</h1>
  <h1 class="vk-nav-brand-light">Brand</h1>
  <h1 class="vk-nav-brand-red">Brand</h1>
  <h1 class="vk-nav-brand-blue">Brand</h1>
  <h1 class="vk-nav-brand-green">Brand</h1>
</div>
<div class="flex gap-2 flex-wrap">
  <h1 class="vk-nav-brand-md">Brand</h1>
  <h1 class="vk-nav-brand-light-md">Brand</h1>
  <h1 class="vk-nav-brand-red-md">Brand</h1>
  <h1 class="vk-nav-brand-blue-md">Brand</h1>
  <h1 class="vk-nav-brand-green-md">Brand</h1>
</div>
```

### Navbar Logo

```html
<div class="flex gap-2 flex-wrap items-baseline">
  <img src="favicon.png" alt="Logo" class="vk-logo" />
  <img src="favicon.png" alt="Logo" class="vk-logo-md" />
  <img src="favicon.png" alt="Logo" class="vk-logo-lg" />
  <img src="favicon.png" alt="Logo" class="vk-logo-xl" />
</div>
<br />
<div class="flex gap-2 flex-wrap items-baseline">
  <img src="rect.png" alt="Logo" class="vk-logo-rect" />
  <img src="rect.png" alt="Logo" class="vk-logo-rect-md" />
  <img src="rect.png" alt="Logo" class="vk-logo-rect-lg" />
  <img src="rect.png" alt="Logo" class="vk-logo-rect-xl" />
</div>
<br />
<div class="flex gap-2 flex-wrap items-baseline">
  <img src="square.png" alt="Logo" class="vk-logo-round" />
  <img src="square.png" alt="Logo" class="vk-logo-round-md" />
  <img src="square.png" alt="Logo" class="vk-logo-round-lg" />
  <img src="square.png" alt="Logo" class="vk-logo-round-xl" />
</div>
```

### Card Wigets

```html
<div class="flex gap-2 flex-wrap">
  <div class="vk-card-widget w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-red w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-blue w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-green w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-yellow w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-orange w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-pink w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-teal w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-purple w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-lime w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-dark w-52">
    <p class="vk-card-widget-value">64</p>
    <p class="vk-card-widget-text">Total Tasks</p>
  </div>
</div>
<br /><br />
<div class="flex gap-2 flex-wrap">
  <div class="vk-card-widget-md w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-md-red w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-md-blue w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-md-green w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-md-yellow w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-md-orange w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-md-pink w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-md-teal w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-md-purple w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-md-lime w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
  <div class="vk-card-widget-md-dark w-64">
    <p class="vk-card-widget-md-value">64</p>
    <p class="vk-card-widget-md-text">Total Tasks</p>
  </div>
</div>
```

### Header

```html
<header class="vk-header">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link-blue-cd">Link</a>
        <a href="#" class="vk-link-blue-cd">Link</a>
        <a href="#" class="vk-link-blue-cd">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link-blue-cd">Link</a>
        <a href="#" class="vk-link-blue-cd">Link</a>
        <a href="#" class="vk-link-blue-cd">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username">Name</a>
        </div>
        <button class="vk-btn max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-link-blue-cd vk-header-navmenu">Link</a>
      <a href="#" class="vk-link-blue-cd vk-header-navmenu">Link</a>
      <a href="#" class="vk-link-blue-cd vk-header-navmenu">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-link-blue-cd vk-header-navmenu">Link</a>
      <a href="#" class="vk-link-blue-cd vk-header-navmenu">Link</a>
      <a href="#" class="vk-link-blue-cd vk-header-navmenu">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn lg:hidden">Logout</button>
    </div>
  </div>
</header>

<header class="vk-header-dark">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand-light">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username-dark">Name</a>
        </div>
        <button class="vk-btn-dark max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-dark">Link</a>
      <a href="#" class="vk-header-navmenu-dark">Link</a>
      <a href="#" class="vk-header-navmenu-dark">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-dark">Link</a>
      <a href="#" class="vk-header-navmenu-dark">Link</a>
      <a href="#" class="vk-header-navmenu-dark">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn-dark lg:hidden">Logout</button>
    </div>
  </div>
</header>

<header class="vk-header-blue">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username">Name</a>
        </div>
        <button class="vk-btn-blue max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-blue">Link</a>
      <a href="#" class="vk-header-navmenu-blue">Link</a>
      <a href="#" class="vk-header-navmenu-blue">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-blue">Link</a>
      <a href="#" class="vk-header-navmenu-blue">Link</a>
      <a href="#" class="vk-header-navmenu-blue">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn-blue lg:hidden">Logout</button>
    </div>
  </div>
</header>

<header class="vk-header-red">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username">Name</a>
        </div>
        <button class="vk-btn-red max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-red">Link</a>
      <a href="#" class="vk-header-navmenu-red">Link</a>
      <a href="#" class="vk-header-navmenu-red">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-red">Link</a>
      <a href="#" class="vk-header-navmenu-red">Link</a>
      <a href="#" class="vk-header-navmenu-red">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn-red lg:hidden">Logout</button>
    </div>
  </div>
</header>

<header class="vk-header-yellow">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username-yellow">Name</a>
        </div>
        <button class="vk-btn-yellow max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-yellow">Link</a>
      <a href="#" class="vk-header-navmenu-yellow">Link</a>
      <a href="#" class="vk-header-navmenu-yellow">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-yellow">Link</a>
      <a href="#" class="vk-header-navmenu-yellow">Link</a>
      <a href="#" class="vk-header-navmenu-yellow">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn-yellow lg:hidden">Logout</button>
    </div>
  </div>
</header>

<header class="vk-header-orange">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username-orange">Name</a>
        </div>
        <button class="vk-btn-orange max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-orange">Link</a>
      <a href="#" class="vk-header-navmenu-orange">Link</a>
      <a href="#" class="vk-header-navmenu-orange">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-orange">Link</a>
      <a href="#" class="vk-header-navmenu-orange">Link</a>
      <a href="#" class="vk-header-navmenu-orange">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn-orange lg:hidden">Logout</button>
    </div>
  </div>
</header>

<header class="vk-header-teal">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username-teal">Name</a>
        </div>
        <button class="vk-btn-teal max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-teal">Link</a>
      <a href="#" class="vk-header-navmenu-teal">Link</a>
      <a href="#" class="vk-header-navmenu-teal">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-teal">Link</a>
      <a href="#" class="vk-header-navmenu-teal">Link</a>
      <a href="#" class="vk-header-navmenu-teal">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn-teal lg:hidden">Logout</button>
    </div>
  </div>
</header>

<header class="vk-header-cyan">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username-cyan">Name</a>
        </div>
        <button class="vk-btn-cyan max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-cyan">Link</a>
      <a href="#" class="vk-header-navmenu-cyan">Link</a>
      <a href="#" class="vk-header-navmenu-cyan">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-cyan">Link</a>
      <a href="#" class="vk-header-navmenu-cyan">Link</a>
      <a href="#" class="vk-header-navmenu-cyan">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn-cyan lg:hidden">Logout</button>
    </div>
  </div>
</header>

<header class="vk-header-pink">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username-pink">Name</a>
        </div>
        <button class="vk-btn-pink max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-pink">Link</a>
      <a href="#" class="vk-header-navmenu-pink">Link</a>
      <a href="#" class="vk-header-navmenu-pink">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-pink">Link</a>
      <a href="#" class="vk-header-navmenu-pink">Link</a>
      <a href="#" class="vk-header-navmenu-pink">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn-pink lg:hidden">Logout</button>
    </div>
  </div>
</header>

<header class="vk-header-lime">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username-lime">Name</a>
        </div>
        <button class="vk-btn-lime max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-lime">Link</a>
      <a href="#" class="vk-header-navmenu-lime">Link</a>
      <a href="#" class="vk-header-navmenu-lime">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-lime">Link</a>
      <a href="#" class="vk-header-navmenu-lime">Link</a>
      <a href="#" class="vk-header-navmenu-lime">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn-lime lg:hidden">Logout</button>
    </div>
  </div>
</header>

<header class="vk-header-purple">
  <nav>
    <div class="vk-header-flex">
      <div class="vk-header-flex">
        <img src="favicon.png" alt="Logo" class="vk-logo" />
        <h1 class="vk-nav-brand">Brand</h1>
      </div>
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
    </div>
    <div class="vk-header-flex">
      <div class="vk-header-flex max-lg:hidden">
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
        <a href="#" class="vk-link">Link</a>
      </div>
      <div class="vk-header-flex">
        <div class="vk-header-flex">
          <img src="favicon.png" alt="Logo" class="vk-logo" />
          <a href="#" class="vk-header-username-purple">Name</a>
        </div>
        <button class="vk-btn-purple max-lg:hidden">Logout</button>
      </div>
      <div class="vk-header-flex lg:hidden">
        <button type="menu" class="rotate-90 font-bold">|||</button>
      </div>
    </div>
  </nav>
  <div class="lg:hidden">
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-purple">Link</a>
      <a href="#" class="vk-header-navmenu-purple">Link</a>
      <a href="#" class="vk-header-navmenu-purple">Link</a>
    </div>
    <div class="flex flex-col gap-2 pt-2 lg:hidden">
      <a href="#" class="vk-header-navmenu-purple">Link</a>
      <a href="#" class="vk-header-navmenu-purple">Link</a>
      <a href="#" class="vk-header-navmenu-purple">Link</a>
    </div>
    <div class="vk-header-flex pt-2">
      <button class="w-full vk-btn-purple lg:hidden">Logout</button>
    </div>
  </div>
</header>
```

### Card Actions

```html
<div class="vk-card-with-actions">
  <div>
    <h1 class="vk-card-with-actions-title">Books List</h1>
    <div class="flex gap-4 items-center">
      <button class="vk-card-with-actions-button">+</button>
      <button class="vk-card-with-actions-button rotate-90">...</button>
    </div>
  </div>
  <div class="w-full h-40 bg-blue-500"></div>
</div>
<div class="vk-card-with-actions-blue">
  <div>
    <h1 class="vk-card-with-actions-title text-white">Books List</h1>
    <div class="flex gap-4 items-center">
      <button class="vk-card-with-actions-button text-white">+</button>
      <button class="vk-card-with-actions-button rotate-90 text-white">...</button>
    </div>
  </div>
  <div class="w-full h-40 bg-white"></div>
</div>

<div class="vk-card-with-actions-dark">
  <div>
    <h1 class="vk-card-with-actions-title text-white">Books List</h1>
    <div class="flex gap-4 items-center">
      <button class="vk-card-with-actions-button text-white">+</button>
      <button class="vk-card-with-actions-button rotate-90 text-white">...</button>
    </div>
  </div>
  <div class="w-full h-40 bg-white"></div>
</div>
```

### Colors

```html
<div class="vk-bg-body w-full h-6" title="vk-bg-body"></div>
<div class="vk-bg-white w-full h-6" title="vk-bg-white"></div>
<div class="vk-bg-black w-full h-6" title="vk-bg-black"></div>
<div class="vk-bg-blue w-full h-6" title="vk-bg-blue"></div>
<div class="vk-bg-cyan w-full h-6" title="vk-bg-cyan"></div>
<div class="vk-bg-sky w-full h-6" title="vk-bg-sky"></div>
<div class="vk-bg-red w-full h-6" title="vk-bg-red"></div>
<div class="vk-bg-rose w-full h-6" title="vk-bg-rose"></div>
<div class="vk-bg-pink w-full h-6" title="vk-bg-pink"></div>
<div class="vk-bg-purple w-full h-6" title="vk-bg-purple"></div>
<div class="vk-bg-violet w-full h-6" title="vk-bg-violet"></div>
<div class="vk-bg-teal w-full h-6" title="vk-bg-teal"></div>
<div class="vk-bg-green w-full h-6" title="vk-bg-green"></div>
<div class="vk-bg-lime w-full h-6" title="vk-bg-lime"></div>
<div class="vk-bg-yellow w-full h-6" title="vk-bg-yellow"></div>
<div class="vk-bg-orange w-full h-6" title="vk-bg-orange"></div>
<div class="vk-bg-gray w-full h-6" title="vk-bg-gray"></div>
```

### Gradient Colors

```html
<div class="vk-bg-body-g w-full h-6" title="vk-bg-body-g"></div>
<div class="vk-bg-white-g w-full h-6" title="vk-bg-white-g"></div>
<div class="vk-bg-black-g w-full h-6" title="vk-bg-black-g"></div>
<div class="vk-bg-blue-g w-full h-6" title="vk-bg-blue-g"></div>
<div class="vk-bg-cyan-g w-full h-6" title="vk-bg-cyan-g"></div>
<div class="vk-bg-sky-g w-full h-6" title="vk-bg-sky-g"></div>
<div class="vk-bg-red-g w-full h-6" title="vk-bg-red-g"></div>
<div class="vk-bg-rose-g w-full h-6" title="vk-bg-rose-g"></div>
<div class="vk-bg-pink-g w-full h-6" title="vk-bg-pink-g"></div>
<div class="vk-bg-purple-g w-full h-6" title="vk-bg-purple-g"></div>
<div class="vk-bg-violet-g w-full h-6" title="vk-bg-violet-g"></div>
<div class="vk-bg-teal-g w-full h-6" title="vk-bg-teal-g"></div>
<div class="vk-bg-green-g w-full h-6" title="vk-bg-green-g"></div>
<div class="vk-bg-lime-g w-full h-6" title="vk-bg-lime-g"></div>
<div class="vk-bg-yellow-g w-full h-6" title="vk-bg-yellow-g"></div>
<div class="vk-bg-orange-g w-full h-6" title="vk-bg-orange-g"></div>
<div class="vk-bg-gray-g w-full h-6" title="vk-bg-gray-g"></div>
```

### Light Colors

```html
<div class="vk-bg-body-light w-full h-6" title="vk-bg-body-light"></div>
<div class="vk-bg-white-light w-full h-6" title="vk-bg-white-light"></div>
<div class="vk-bg-black-light w-full h-6" title="vk-bg-black-light"></div>
<div class="vk-bg-blue-light w-full h-6" title="vk-bg-blue-light"></div>
<div class="vk-bg-cyan-light w-full h-6" title="vk-bg-cyan-light"></div>
<div class="vk-bg-sky-light w-full h-6" title="vk-bg-sky-light"></div>
<div class="vk-bg-red-light w-full h-6" title="vk-bg-red-light"></div>
<div class="vk-bg-rose-light w-full h-6" title="vk-bg-rose-light"></div>
<div class="vk-bg-pink-light w-full h-6" title="vk-bg-pink-light"></div>
<div class="vk-bg-purple-light w-full h-6" title="vk-bg-purple-light"></div>
<div class="vk-bg-violet-light w-full h-6" title="vk-bg-violet-light"></div>
<div class="vk-bg-teal-light w-full h-6" title="vk-bg-teal-light"></div>
<div class="vk-bg-green-light w-full h-6" title="vk-bg-green-light"></div>
<div class="vk-bg-lime-light w-full h-6" title="vk-bg-lime-light"></div>
<div class="vk-bg-yellow-light w-full h-6" title="vk-bg-yellow-light"></div>
<div class="vk-bg-orange-light w-full h-6" title="vk-bg-orange-light"></div>
<div class="vk-bg-gray-light w-full h-6" title="vk-bg-gray-light"></div>
```

### Dark Colors

```html
<div class="vk-bg-body-dark w-full h-6" title="vk-bg-body-dark"></div>
<div class="vk-bg-white-dark w-full h-6" title="vk-bg-white-dark"></div>
<div class="vk-bg-black-dark w-full h-6" title="vk-bg-black-dark"></div>
<div class="vk-bg-blue-dark w-full h-6" title="vk-bg-blue-dark"></div>
<div class="vk-bg-cyan-dark w-full h-6" title="vk-bg-cyan-dark"></div>
<div class="vk-bg-sky-dark w-full h-6" title="vk-bg-sky-dark"></div>
<div class="vk-bg-red-dark w-full h-6" title="vk-bg-red-dark"></div>
<div class="vk-bg-rose-dark w-full h-6" title="vk-bg-rose-dark"></div>
<div class="vk-bg-pink-dark w-full h-6" title="vk-bg-pink-dark"></div>
<div class="vk-bg-purple-dark w-full h-6" title="vk-bg-purple-dark"></div>
<div class="vk-bg-violet-dark w-full h-6" title="vk-bg-violet-dark"></div>
<div class="vk-bg-teal-dark w-full h-6" title="vk-bg-teal-dark"></div>
<div class="vk-bg-green-dark w-full h-6" title="vk-bg-green-dark"></div>
<div class="vk-bg-lime-dark w-full h-6" title="vk-bg-lime-dark"></div>
<div class="vk-bg-yellow-dark w-full h-6" title="vk-bg-yellow-dark"></div>
<div class="vk-bg-orange-dark w-full h-6" title="vk-bg-orange-dark"></div>
<div class="vk-bg-gray-dark w-full h-6" title="vk-bg-gray-dark"></div>
```
