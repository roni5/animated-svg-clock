<h1 align="center">
Animated SVG clock
</h1>

<p align="center">
<img src="https://github.com/tomchen/svg-clock/raw/master/clock.svg" alt="Clock" title="Clock">
</p>

## Technical details

SMIL-based animation

Use JavaScript to set the current time

## GitHub usage

JavaScript code of an SVG in `<img>` will not be executed, the [SMIL](https://developer.mozilla.org/en-US/docs/Web/SVG/SVG_animation_with_SMIL) or CSS-based animation is fine, therefore, **what you see on GitHub README.md page is an animated clock starting from 00:00**, it basically counts the time you stayed on the page.

Even if you open the GitHub-hosted raw SVG file directly in your browser, the JavaScript code will still not be executed due to "[Content Security Policy](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP): sandbox" header.

In order to execute the JavaScript code, you can download the SVG file, then open it directly in your browser, the animated clock should start from the current time.

It should also work if you embed it directly (not via `<img>`) in your website or any website that does not have strict Content Security Policy header and does not sanitize custom JavaScript code.

Use it (Markdown, can't set width and height):

```markdown
![Clock](https://github.com/tomchen/svg-clock/raw/master/clock.svg "Clock")
```

Use it (HTML, with width and height set):

```html
<img src="https://github.com/tomchen/svg-clock/raw/master/clock.svg" alt="Clock" title="Clock" height="200px" width="200px">
```

## Design

Yes it's highly similar to a [Swiss railway clock](https://en.wikipedia.org/wiki/Swiss_railway_clock) whose design [IS COPYRIGHTED](https://www.businessinsider.fr/us/apple-paid-21-million-for-swiss-railways-clock-2012-11).

## Credits

By Tom Chen

Inspired by SVG animation: by HackaLittleBit (https://commons.wikimedia.org/wiki/File:Swiss_railway_clock_1.svg), CC-by-sa 4.0, whose original SVG is: by Jahoe (https://commons.wikimedia.org/wiki/File:Swiss_railway_clock.svg), CC-by-sa 3.0 & GFDL

(The current SVG code has significate code change comparing to HackaLittleBit's work, and is using the permissive MIT license)

## License

MIT license for the code, but Swiss railway clock **DESIGN IS COPYRIGHTED**.
