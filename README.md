## Research:

**Stage 1**: Chrome doesn't respect the height set in `vh` on mobile when the width of an element is larger than the viewport.

https://mehdyhafayd.github.io/chrome-device-100vh-bug/

```css
        body {
            margin: 0;
        }

        div {
            background: lightblue;
            height: 100vh;
            width: 200vw;
        }
```