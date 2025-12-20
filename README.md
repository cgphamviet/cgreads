# Blogger Theme Assets

Collection of XML, CSS, and JavaScript files for customizing Blogger themes.

## Project structure

## Usage

1. Go to Blogger → Theme → Edit HTML
2. Replace the existing XML with `index.xml` or `clean-install.xml`
3. Add CSS and JS files from the `assets` directory as needed

/
├─ README.md
├─ CHANGELOG.md
├─ LICENSE
│
├─ template/
│  ├─ cgreads.xml
│  └─ cgreads-dev.xml        (nếu có bản test)
│
├─ assets/
│  ├─ css/
│  │  ├─ base.css
│  │  ├─ layout.css
│  │  ├─ typography.css
│  │  └─ theme.css
│  │
│  ├─ js/
│  │  ├─ main.js
│  │  ├─ typography.js
│  │  └─ utils.js
│  │
│  ├─ img/
│  │  ├─ logo.svg
│  │  └─ placeholder.webp
│  │
│  └─ font/
│     ├─ inter-regular.woff2
│     └─ inter-bold.woff2
│
└─ docs/
   ├─ install.md
   ├─ structure.md
   └─ customization.md

## Loại bỏ hoàn toàn chủ đề cũ

```
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateUrl='clean-install.xml' b:templateVersion='0.0.1' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'><b:attr name='xmlns' value=''/><b:attr name='xmlns:b' value=''/><b:attr name='xmlns:expr' value=''/><b:attr name='xmlns:data' value=''/><head><b:if cond='false'><b:skin><![CDATA[]]></b:skin></b:if></head><body><b:section id='_' maxwidgets='1' showaddelement='false'/></body></html>
```

## License

[MIT](https://choosealicense.com/licenses/mit/)

