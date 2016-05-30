# Candy grid system

## Table of contents

* [Quick start](#quick-start)
* [Usage Html](#html)
* [Usage Less](#less)
* [Usage Sass](#sass)
* [Contributing](#customization)
* [Author](#author)
* [Copyright and license](#copyright-and-license)

## Quick start

* [Download the latest release](https://github.com/andreamariotti83/candy-grid-system/archive/v1.0.0.zip).
* Clone the repo: `git clone https://github.com/andreamariotti83/candy-grid-system.git`.

### What's included

```
candy-grid-system/
├── dist/
│   ├── 12-candygs.css
│   ├── 12-candygs.min.css
│   ├── 12-candygs-rtl.css
│   ├── 12-candygs-rtl.min.css
│   ├── 16-candygs.css
│   ├── 16-candygs.min.css
│   ├── 16-candygs-rtl.css
│   ├── 16-candygs-rtl.min.css
│   ├── 24-candygs.css
│   ├── 24-candygs.min.css
│   ├── 24-candygs-rtl.css
│   ├── 24-candygs-rtl.min.css
```

### HTML:

To use the Grid, you need to include the file with Grid number **12**, **16** or **24** that you want to use in the section `<head>` of the page.

```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/candy-grid-system/1.0.0/12-candygs.min.css">
```

Add the class to set up your default layout, whether fixed or responsive. You can choose the layout among **17 different options** and  setting up any up to 8 classes.

* **candygs** : this is necessary to set up the values of your layout and Grid, in order to use the Candy Grid System.

```html
<body>
	<div id="page" class="page candygs"></div>
</body>
```

First, decide whether the layout will be set to, **small** to high, or **medium** to high, responsive **mobile** mode;
* **mobile** : sets up a responsive layout of 0 to 100%.
* **small** : sets up a responsive layout  of 720px to 100% `min-width: 720px`
* **medium** : sets up a responsive layout of 960px to 100% `min-width: 960px`

```html
<body>
	<div id="page" class="page candygs mobile"></div>
</body>
```

* **showgs** : This class enables you to visualize the Grid in the background

```html
<body>
	<div id="page" class="page candygs mobile showgs"></div>
</body>
```

Then, set up a container for the layout with class **candygs-container** and its variables; a *max-width*, by selecting one of 5 options
* **candygs-container** : Set up a *max-width* container for each resolution - 720px - 960px - 1200px - 1560px - 1920px
  * **candygs-container-max-xl-large** : Set up a *max-width* container that will be no larger than 1560px
  * **candygs-container-max-large** : Set up a *max-width* container that will be no larger than 1200px
  * **candygs-container-max-medium** : Set up a *max-width* container that will be no larger than 960px
  * **candygs-container-max-small** : Set up a *max-width* container that will be no larger than 720px

```html
<body>
	<div id="page" class="page candygs mobile candygs-container showgs"></div>
</body>
```

Now you can set up the Grids, which operate in accordance with the chosen layout.

```html
<body>
	<div id="page" class="page candygs mobile candygs-container showgs">
		<div class="grid-8">
			<div class="row">
				<div class="grid-6"></div>
				<div class="grid-6"></div>
			</div>
		</div>
		<div class="grid-4"></div>
	</div>
</body>
```

You can also choose different values, depending on the pixel resolution.
* **grid-** : For all resolutions
* **grid-xs-** : Only for mobile `@media (max-width: 767px)`
* **grid-sm-** : `@media (min-width: 768px)`
* **grid-md-** : `@media (min-width: 992px)`
* **grid-lg-** : `@media (min-width: 1200px)`
* **grid-xl-** : `@media (min-width: 1560px)`
* **grid-xxl-** : `@media (min-width: 1920px)`

```html
<body>
	<div id="page" class="page candygs mobile candygs-container showgs">
		<div class="grid-xs-8 grid-sm-8 grid-md-7 grid-lg-6 grid-xl-5 grid-xxl-4"></div>
		<div class="grid-xs-4 grid-sm-4 grid-md-5 grid-lg-6 grid-xl-7 grid-xxl-8"></div>
	</div>
</body>
```

In additon to the class **grid-**, you can select:

* **prefix-** 
* **suffix-**
* **push-**
* **pull-**

Depending on your needs, choose the same variables as the **grid-**.

### LESS:
Coming soon

```

```

### SASS:
Coming soon

```

```

##  Contributing




## Author

Created by Andrea Mariotti. See the official site for more info: http://...

* https://github.com/andreamariotti83


## Copyright and license

Code and documentation copyright 2016 Andrea Mariotti 
Code released under [the MIT license](https://github.com/andreamariotti83/candy-grid-system/blob/master/LICENSE).


## Thanks
