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

To use this grid, simply include the file with the number of grids 12, 16 or 24 that you want to use, in the `<head>` HTML page.

```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/candy-grid-system/1.0.0/12-candygs.min.css">
```

Add classes to set your default layout, fixed or responsive. You can choose from 17 different options

* **candygs** : essential to set the values of the layout and grids, to use the candy grid system

```html
<body>
	<div id="page" class="page candygs"></div>
</body>
```

* **mobile** : sets a responsive layout 0 to 100%
* **small** : sets a responsive layout 720 px to 100%
* **medium** : sets a responsive layout 960 px to 100%

```html
<body>
	<div id="page" class="page candygs mobile"></div>
</body>
```

* **showgs** : By inserting this class you have the visibility of the grids in the background

```html
<body>
	<div id="page" class="page candygs mobile showgs"></div>
</body>
```

You can also choose to have a layout with a **max-width** choosing between these classes
* **candygs-container** : Set a "max-width" container for each resolution - 720px - 960px - 1200px - 1560px - 1920px
..* **candygs-container-max-xl-large** : Set a "max-width" container that will be no larger than 1560px
..* **candygs-container-max-large** : Set a "max-width" container that will be no larger than 1200px
..* **candygs-container-max-medium** : Set a "max-width" container that will be no larger than 960px
..* **candygs-container-max-small** : Set a "max-width" container that will be no larger than 720px

```html
<body>
	<div id="page" class="page candygs mobile candygs-container showgs"></div>
</body>
```

Now you can set your grids, which behave according to the choice of your layout

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

You can also choose to have different values, depending on the resolution
* **grid-** : For all resolutions
* **grid-xs-** : Only for mobile `@media (max-width: 767px)```
* **grid-sm-** : ```css @media (min-width: 768px)```
* **grid-md-** : ```css @media (min-width: 992px)```
* **grid-lg-** : ```css @media (min-width: 1200px)```
* **grid-xl-** : ```css @media (min-width: 1560px)```
* **grid-xxl-** : ```css @media (min-width: 1920px)```

```html
<body>
	<div id="page" class="page candygs mobile candygs-container showgs">
		<div class="grid-xs-8 grid-sm-8 grid-md-7 grid-lg-6 grid-xl-5 grid-xxl-4"></div>
		<div class="grid-xs-4 grid-sm-4 grid-md-5 grid-lg-6 grid-xl-7 grid-xxl-8"></div>
	</div>
</body>
```

In addition to the **grid-** class, you can use **prefix-**, **suffix-**, **push-**, **pull-**, depending on what you need, with the same variants as the **grid-**

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
[Lorenzo Pezzali](https://github.com/lpwebit) for his contribution to the development of the project
