# Helix Ultimate custom.scss
 
В файле ./scss/theme.scss исправлен 
```
:root {
  --header_height: $header_height;
}
```

В файле ./scss/responsive.scss  исправлен ```--header_height: $header_height_sm;``` и аналогичные моменты

В файле ./scss/presets.scss убран лишний код за счет переопределения CSS-переменных

Все переопределения CSS-переменных перемещены в файл scss-custom/global/_helix-ultimate.scss


