# HTML_CSS_MidTerm

## Topic: Flex

[Preview Page <img src="images/landings.svg" width="45">](https://zura-papiashvili.github.io/HTML_CSS_MidTerm/)


#### Tree Structure:
```bash
├── HTML_CSS__MidTerm
│   ├── css
│   │   ├── **/*.css
│   ├── fonts
│   │   ├── **/*.ttf/eot/otf/svg/woff
│   ├── images
│   │   ├── **/*.png/jpg/svg
│   ├── index.html
│   ├── README.md
```
### index.html
Contains three section build with flex property


#### Flex property
Using flex together with media queries to create a different layout for different screen sizes/devices:

``` css
/* style */
.flex-container {
  display: flex;
  background-color: DodgerBlue;
}
.flex-container > div {
    background-color: #f1f1f1;
    margin: 10px;
    padding: 20px;
    font-size: 30px;
}

```
A Flexible Layout must have a parent element with the display property set to flex.

Direct child elements(s) of the flexible container automatically becomes flexible items.

``` html
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>  
</div>
```

### Source:[www.w3schools.com](https://www.w3schools.com/css/tryit.asp?filename=trycss3_flexbox)




