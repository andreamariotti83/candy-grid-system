# Candy grid system

## Quick start

* [Download the latest release](https://github.com/andreamariotti83/candy-grid-system/archive/v2.0.zip).
* Clone the repo: `git clone https://github.com/andreamariotti83/candy-grid-system.git`.
* Install with [Composer](https://getcomposer.org): `composer require candygs/candy-grid-system`.

### HTML:

To use the Grid, you need to include the file with Grid number **12**, **16** or **24** that you want to use in the section `<head>` of the page.

```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/candy-grid-system/2.0/12-candygs.min.css">
```
```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/candy-grid-system/2.0/16-candygs.min.css">
```
```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/candy-grid-system/2.0/24-candygs.min.css">
```

***candygs*** : This class is required to use to set the values of the grids.

```html
<body class="candygs">
    <div class="container">
        <div class="..."></div>
    </div>
</body>
```

***fluid*** : This class is required to have a fluid layout, setting the width of the container to 100%.

```html
<body class="candygs fluid">
    <div class="container">
        <div class="..."></div>
    </div>
</body>
```

***container*** : It has a default width for each resolution - 720px - 960px - 1200px - 1560px - 1920px

```html
<body class="candygs">
    <div class="container">
        <div class="..."></div>
    </div>
</body>
```

It is possible to set a minimum width and / or maximum container
* ***min-widht container*** :
    * ***mim-sm*** : Set up a **min-width** to the container, which will be no smaller than 720px
    * ***min-md*** : Set up a **min-width** to the container, which will be no smaller than 960px

* ***max-widht container*** :
    * ***max-sm*** : Set up a **max-width** to the container, which will be no larger than 720px
    * ***max-md*** : Set up a **max-width** to the container, which will be no larger than 960px
    * ***max-lg*** : Set up a **max-width** to the container, which will be no larger than 1200px
    * ***max-xl*** : Set up a **max-width** to the container, which will be no larger than 1560px

```html
<body class="candygs min-sm max-lg">
    <div class="container">
        <div class="..."></div>
    </div>
</body>
```

Now you can set the grids depending on your needs.

```html
<body class="candygs">
	<div class="container">
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

You can also choose different values, depending on the screen resolution.
* ***grid-*** : For all resolutions
* ***grid-xs-*** : Only for mobile `@media (max-width: 767px)`
* ***grid-sm-*** : `@media (min-width: 768px)`
* ***grid-md-*** : `@media (min-width: 992px)`
* ***grid-lg-*** : `@media (min-width: 1200px)`
* ***grid-xl-*** : `@media (min-width: 1560px)`
* ***grid-xxl-*** : `@media (min-width: 1920px)`

```html
<body class="candygs">
	<div class="container">
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
### PSD:
[Download psd templates](https://github.com/andreamariotti83/candy-grid-system/releases/download/v1.2.0/candy-grid-system-psd.zip).

## Author

Created by Andrea Mariotti. See the official site for more info: http://candygridsystem.com

* https://github.com/andreamariotti83

## Copyright and license

Code and documentation copyright 2016 Andrea Mariotti 
Code released under [the MIT license](https://github.com/andreamariotti83/candy-grid-system/blob/master/LICENSE).

## Thanks
