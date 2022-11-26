# Safari/WebKit CSS Filter Update Bug

Open [index.html](./index.html) in Safari, or visit <https://rdela.github.io/safari-css-filter-update/>

Open Web Inspector and watch the buttons aria-selected attributes values change while clicking them. Observe how the CSS filter [grayscale(100%) unless aria-selected is true, then 0%] is not applied consistently when the values change. Try the same in Chromium and Firefox browsers. Oddly, in Safari, display only seems to update to the correct value when window focus changes or when Web Inspector is opened or closed.
