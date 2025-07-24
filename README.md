[![StandWithPalestine](https://github.com/Safouene1/support-palestine-banner/blob/master/StandWithPalestine.svg)](https://github.com/Safouene1/support-palestine-banner)

# بنر حمایت از فلسطین

این مخزن در برگیرنده چند نوع بنر فلسطین برای نمایش در سایت شما است که کد آن به راحتی قابل استفاده میباشد و فقط کافی است آن را کپی و در وبسایت خود جایگذاری کنید.

# جدول محتواها
1. [روش استفاده](https://github.com/Safouene1/support-palestine-banner#how-to-use)
2. [بج و بنر ها](https://github.com/Safouene1/support-palestine-banner#badges-and-banners)
3. [کامپوننت بنر برای React, NextJs 13, Vue (V2 & V3) with Tailwind](https://github.com/Safouene1/support-palestine-banner#banner-components-for-react-nextjs-13-vue-v2--v3-with-tailwind)
4. [نصب بنر وبسایت](https://github.com/Safouene1/support-palestine-banner#website-banner-installation)
5. [وب کامپوننت های دیگر بنر](https://github.com/Safouene1/support-palestine-banner#banner-custom-web-component)
6. [نحوه همکاری](https://github.com/Safouene1/support-palestine-banner#how-to-contribute)
7. [عیب یابی](https://github.com/Safouene1/support-palestine-banner#troubleshooting)
8. [استفاده شده توسط](https://github.com/Safouene1/support-palestine-banner#used-by)
9. [لایسنس](https://github.com/Safouene1/support-palestine-banner#license)

# نحوه استفاد

**آموزش استفاده از بنر حمایت از فلسطین در پروژه های شما--**

1. بنری که دوست دارید رو از قسمت زیر انتخاب کنید.
  
2. کد بنر مورد انتخاب را در پروژه خود داخل فایل README یا هر فایلی که Markdown را پشتیبانی میکنید کپی پیست کنید.

3. برای نمایش بنر در سایت, please make sure to copy the HTML snippet from the "Website Banner Installation" section and paste it right after the opening `<body>` تگ در فایلHTML e.

4.اگر دوست دارید لینک های داخل بنر پشتیبانی رو شخصی سازی کنید, به راحتی لینک خود را جایگزین لینک قبلی داخل کد کنید.
   
5. بنر بلافاصله بعد از ذخیره تغییرات باید نمایش داده شود. لطفا در صورت وقوع مشکل از "Troubleshooting" در زیر بازدید کنید.

# بج ها و بنرها

### بج بنر

[![با فلسطین میمانیم](https://github.com/Safouene1/support-palestine-banner/blob/master/StandWithPalestine.svg)](./Markdown-pages/Support.md)

```md
[![StandWithPalestine](https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/StandWithPalestine.svg)](https://github.com/Safouene1/support-palestine-banner/blob/master/Markdown-pages/Support.md)
```

### ReadMe Banner

<div align="center"><a href="https://github.com/Safouene1/support-palestine-banner/blob/master/Markdown-pages/Support.md"><img src="https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/banner-support.svg" alt="Support Palestine" style="width: 100%;"></a></div>

```html
<div align="center"><a href="https://github.com/Safouene1/support-palestine-banner/blob/master/Markdown-pages/Support.md"><img src="https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/banner-support.svg" alt="Support Palestine" style="width: 100%;"></a></div>
```

### ReadMe Banner for Projects

<div align="center"><a href="https://github.com/Safouene1/support-palestine-banner/blob/master/Markdown-pages/Support.md"><img src="https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/banner-project.svg" alt="Support Palestine" style="width: 100%;"></a></div>

```html
<div align="center"><a href="https://github.com/Safouene1/support-palestine-banner/blob/master/Markdown-pages/Support.md"><img src="https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/banner-project.svg" alt="Support Palestine" style="width: 100%;"></a></div>
```

# Banner Components for React ,NextJs 13, Vue (V2 & V3) with Tailwind

### Sample of Mobile with dark mode

![example images mobile dark mode](React-Components/example-images/mobile-dark-mode.png)

### Sample of Desktop with light mode

![example images desktop light mode](React-Components/example-images/desktop-light-mode.png)

این کامپوننت ها بیرون باکس پشتیبانی هستند

|     | قابلیت ها                    |
| --- | --------------------------- |
| ✅  | جاوا اسکریپت                 |
| ✅  | تایپ اسکریپت                 |
| ✅  | کامپوننت های سرور           |
| ✅  | ریسپانسیو                |
| ✅  | Closeable                   |
| ✅  | Position Sticky or Relative |

اگر شما از Tailwind استفاده نمیکنید, این فایل Css را درون ریزی کنید: [banner.css](React-Components/banner.css)

کامپوننت ها اینجا یافت میشوند [here](https://github.com/Safouene1/support-palestine-banner/tree/master/React-Components)

# نصب بنر وبسایت

Use this snippet to show your support for Palestinians on the top of your website. Installing it takes minutes.

![image](https://github.com/Safouene1/support-palestine-banner/assets/22036449/bfbfe6de-0e2f-4d6d-8e7e-fd47ea00ddf2)

### About the Website Banner

This code adds a small black banner on top of your website with Palestinian flag and support message. It links to islamic-relief's donation site but you can change the link to point to a support channel of your choice.

![image](https://github.com/Safouene1/support-palestine-banner/assets/22036449/269d2610-7025-4b69-a3b1-00fbfc2a949a)

### Installation Banner

Installation is dead simple. Just copy this code to your template right after the opening `<body>` tag.

```html
<style>
  body {
    margin-top: 35px;
  }
  .support-palestine,
  .support-palestine:visited {
    position: absolute;
    left: 0;
    top: 0;
    right: 0;
    background: rgb(0, 0, 0);
    display: flex;
    justify-content: center;
    padding-top: 5px;
    padding-bottom: 5px;
    z-index: 10000;
    text-decoration: none;
    font-family: arial;
  }
  .support-palestine:hover,
  .support-palestine:active {
    background: black;
    display: flex;
    background: rgb(80, 80, 80);
    text-decoration: none;
  }
  .support-palestine__flag {
    margin-right: 10px;
  }

  .support-palestine__label {
    color: white;
    font-size: 12px;
    line-height: 24px;
  }
  .background {
    background: darkgreen;

    height: 21px;
  }
  .top {
    background: black;
    width: 40px;
    height: 8px;
    z-index: 1;
  }
  .middle {
    background: white;
    width: 100%;
    height: 8px;
    z-index: 1;
  }
  .triangle {
    background: auto;
    border-top: 12px solid transparent;
    border-bottom: 12px solid transparent;
    border-left: 20px solid red;
    z-index: 2;
    position: relative;
    top: -16px;
    left: 0;
  }
</style>
<a
  class="support-palestine"
  href="https://www.islamic-relief.org.uk/giving/appeals/palestine/"
  target="_blank"
  rel="nofollow noopener"
  title="Donate to support palestine"
>
  <div
    class="support-palestine__flag"
    role="img"
    aria-label="Flag of palestine"
  >
    <div class="background">
      <div class="top"></div>
      <div class="middle"></div>
      <div class="triangle"></div>
    </div>
  </div>
  <div class="support-palestine__label">Donate to support Palestine</div>
</a>
```

# Banner Custom Web Component

Read more about the custom web component [here](Web-component/README.md).

# How to Contribute

Contributions to this project are welcome! If there is anything you would like to add to this repository, click [here](CONTRIBUTING.md) for contribution guidelines.

# Troubleshooting

**If the banner doesn't appear on your website?**    
*Solution:* Double check and make sure that you inserted the desired HTML code immediately following the opening `<body>` tag. Then, check for any conflicting CSS errors in styling.

**اگر متن بنر خوانا نیست؟**    
*راه حل:* Locate the pasted HTML code and edit the CSS properties for color of text and background to improve contrast.


# استفاده شده توسط

- [satr14's corner](https://new.sx9.is-a.dev/)

- [LGU timetable](https://www.lgutimetable.online/)

- [Safouen Turki](https://safouen.me)

- [Amin Boulouma](https://github.com/aminblm)

- [Awesome #FreePalestine🇵🇸 Support Kit](https://github.com/aminblm/awesome-free-palestine-support-kit/tree/main)

- [envio CLI](https://github.com/envio-cli/envio)

- [Bixat.dev](https://bixat.dev)

# لایسنس
این پروژه هم اکنون تحت لایسنس MITهست. برای جزئیات این فایل را ببینید. [LICENSE](LICENSE) .
