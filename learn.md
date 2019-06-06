# concepts learned in this project
---

### overflow
* overflow property sets what to do when content is too big to fit in its block formatting.

* the options include clipping, adding a scroll bar, or display content flowing out of its container onto the surronding area

* in order for this property to have an effect, container must include a height and width area

> https://developer.mozilla.org/en-US/docs/Web/CSS/overflow


### scroll-behaivor
* how the scrolling will affected when a scrollbar or wheel is used.

* default value is snappy, instant
> auto
* a more graudual look, with a landscape view of the content
> smooth

### scroll-snap-type
* takes in two values:
    * either x or y axis where the snapping is going to take place
    * type of snap
        > proximity
        > mandatory
* proximity not snap if possible, only if there is enough space on both for some content on both blocks are showing, otherwise, it behaves like a mandatory
* mandatory will  snap regardless of the content of each block, which block has more real estate is towards where the snap will happen
* to summerize of syntax:
> x proximity

> y mandatory
## can change amongst