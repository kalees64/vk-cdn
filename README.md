# VK CSS Framework via CDN

This is a simple, lightweight CSS framework that helps you style your website quickly. You can easily add this framework to your project by including a CDN link in your HTML file.

## Getting Started

### Installation

To use this framework, add the following `<link>` tag in the `<head>` section of your HTML file:

```html
<link rel="stylesheet" href="https://kalees64.github.io/vk-cdn/vk-cdn.css" />
```

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
