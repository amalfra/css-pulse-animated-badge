CSS pulse animation badge
=========================

A quick experiment to create a badge with pulse animation using CSS. It is implemented using CSS3 animations.

![screenshot](https://raw.githubusercontent.com/amalfra/css-pulse-animated-badge/main/demo.gif)

## How it works

The CSS required to add the effect(which are only few lines) are available in ```badge-pulse-animation.css``` file. Below is a brief explanation:

* First we will define ```@keyframes``` rule which is used to define what styles the element will have at certain times of animation.
The style that a frame of animation will apply to the element will be scale function of transformation property. So each frame of animation will scale the element size by defined factor. A filter styles is also applied at somepoints to have blur effect.
* A pseudo element positioned over the badge element with border will be added. It's this border that get's scaled during animation.
* Now define the animation property with 1s duration and easing. The animation iteration count will be defined as infinte so that this keeps looping. Thus it will create the effect of pulse.

## Development

Questions, problems or suggestions? Please post them on the [issue tracker](https://github.com/amalfra/css-pulse-animated-badge/issues).

You can contribute changes by forking the project and submitting a pull request. Feel free to contribute :heart_eyes:

UNDER MIT LICENSE
=================

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
