# 100 Days Of Code - Log

### Day 001: May 10, 2018

**Today's Progress**: Updated an old sass/compass css styles

**Thoughts:** Had some issues with the `transform-origin`, end up being missing a third value. Somehow compass autogenerate the value but using CodeKit doesn't. I don't recall how the perspective and origin position works exactly, but next time I will find out and add a script to generate css.

**Link to work:** [CSS3-3D-Flip-Cards](https://github.com/WellingGuzman/CSS3-3D-Flip-Cards)

### Day 002: May 11, 2018

**Today's Progress**:

- Fixed some issues with CSS `transform` property on Firefox.
- Add unit to perspective value.
- Removed specific demo style from the core styles.

**Thoughts:**

I didn't need `transform-origin` z-axis to make it work properly and it doesn't support percentage values.

`backface-visibility` has a known bug on Firefox (Ref: https://stackoverflow.com/a/32421734). Solution: add `transform: rotateX(0deg);`



**Link to work:** [CSS3-3D-Flip-Cards](https://github.com/WellingGuzman/CSS3-3D-Flip-Cards/commit/58e72e265d68cdedf356f8e9b7e98913f6d0e043)

### Day 003: May 12, 2018

**Today's Progress**:

- Rewrite my old experiment with camera+canvas+effect manipulating the pixels of the canvas.

**Thoughts:**

- Using the web camera stream and not playing result in a video autoplay with a low performance. Solution: add `autoplay` attribute or play the video with `video.play()`.
- There's a lot of fun stuff to do with the camera and canvas element. There will be more!

**Link to work:** [Duotone web camera](https://codepen.io/wellingguzman/pen/XqYKyy)

### Day 004: May 13, 2018

**Today's Progress**:

- Playing around with glitch.com (express, jquery, ajax) and codepen.io

**Thoughts:**

- Express is not bundled with bodyParser neither methodOverride anymore.
- Using jQuery after a while. use the `dataType: 'json'` to make sure jQuery.ajax parse the output as JSON.

**Link to work:** https://valley-patio.glitch.me

### Day 005: May 14, 2018

**Today's Progress**:

- Starting to recall how to use `XMLHttpRequest` and make basic request.

**Thoughts:**

- It was hard trying to set this up when you are used to more easy to use libraries that does almost all the work for you.

**Link to work:** https://scratch-skate.glitch.me

### Day 006: May 15, 2018

**Today's Progress**:

- Accept `json` as the request body using `XMLHttpRequest`.
- Add success and error callback.

**Thoughts:**

- You need to open the request before adding headers.

**Link to work:** https://scratch-skate.glitch.me

### Day 007: May 16, 2018

**Today's Progress**:

- Add Promise support
- Cleaned the function a bit more.
- Removed the `dataType` param, and depends on the `Content-Type` header.

**Thoughts:**

- _Nothing_

**Link to work:** https://scratch-skate.glitch.me

### Day 008: May 17, 2018

**Today's Progress**:

- Took the duotone demo from day 003 and starting wrap functions to create an app similar to https://duotones.co

**Thoughts:**

- Draging the color picker in the color input super slow, and I need to fix it or create a different picker.

**Link to work:** https://axiomatic-stock.glitch.me
