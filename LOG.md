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
