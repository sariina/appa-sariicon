<div lang="fa" dir="rtl">
<h1>آپا ساریکان</h1>
برای ساخت وب‌اپلیکیشن <a href="http://payamsms.com">پیام‌اس‌ام‌اس</a>، نیاز به استفاده از نشانه‌های بصری بود و به طبع، به دلیل پیچیدگی و اختصاصی بودن مفاهیم چنین نرم‌افزاری، یافتن نشانه‌های مناسب از بین ابزارهای آماده سخت و زمان‌بر بود.
تصمیم گرفتیم تا وب‌فونت آیکون‌هایی اختصاصی برای این محصول طراحی و تولید کنیم.
</div>
<strong dir="ltr">http://code.sariina.com/appa-sariicon/</strong>

# Appa Sariicon
Appa Sariicon is a collection of 147 webfont icons that are carefully designed by [Sariina](http://sariina.com) to use in complex Web Application UIs.

[**View Demo in Here**](http://code.sariina.com/appa-sariicon)

## Add Appa Sariicon to your project

1. Create a new file called *bower.json* (if you don't have one already).

2. Add a new line for the Octicon dependency, pointing to the correct repository:

  ``` json
  {
    "name": "my_great_project",
    "dependencies": {
      "appa-sariicon": "*"
    }
  }
  ```

3. Run `bower install`. The Octicons styles will be downloaded to *bower_components/appa-sariicon*.

4. Link to the `appa-sariicon.css` stylesheet in the `<head>` of your `<html>` page:

There are two kinds of CSS files in this repo:
- **appa-sariicon-embeded** which has "Appa Sariicon" embedded inside the CSS in base64
- **appa-sariicon.min** or **appa-sariicon** which is a normal @font-face with eot,svg,ttf and woff files


  ``` html
  <link rel="stylesheet" href="bower_components/appa-sariicon/appa-sariicon.min.css">
  ```

4. Use "**i**" tags and add classes with "sar sar-[name]" pattern:

  ``` html
	<i class="sar sar-env"></i>
	<i class="sar sar-shortnumber-add"></i>
	<i class="sar sar-text-pro"></i>
  ```


# License
- The Appa Sariicon font is licensed under the SIL OFL 1.1:
http://scripts.sil.org/OFL
- Appa Sariicon CSS files are licensed under the MIT License:
http://opensource.org/licenses/mit-license.html

# Changelog
- 2.0 Redesigned from ground up in 16*16 square base
- 1.0 Initial release