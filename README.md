<div align="center">

<img src="assets/favicon.svg" alt="Unstruction" width="50"/>

# Unstruction
An open-source web template built with [Shoelace](https://shoelace.style/) for setting up a simple and easy **website under construction** page.

</div>

## Features
- 😊 No installation or fancy setup; just add the website name and contact details!
- ⏱️ Displays a countdown timer until the website launch date! 
- ⚡ Uses [Shoelace](https://shoelace.style/), a powerful web component library!

## Usage
The first step is to click the **Use this template** button above the file list to create a new repository.

### Add website name and URL
Go to [line 92](https://github.com/digitalmalayalistudio/unstruction/blob/main/index.html#L92) in `index.html` file and add website name:

```html
<strong>Unstruction</strong>
```

Make sure to change the [meta](https://github.com/digitalmalayalistudio/unstruction/blob/main/index.html#L13) URL as well:

```html
<meta property="og:url" content="https://digitalmalayalistudio.github.io/unstruction/">
```

### Change image
Add an image with a minimum width of 350px to assets folder replacing [preview.webp](https://github.com/DigitalMalayaliStudio/unstruction/blob/main/assets/preview.webp). 

### Add website launch date
You can change the date in [line 126](https://github.com/digitalmalayalistudio/unstruction/blob/main/index.html#L126) of `index.html`. Make sure to use the long date format as shown in the example:

```js
const target = new Date('Jan 1, 3000, 00:00:00').getTime();
```