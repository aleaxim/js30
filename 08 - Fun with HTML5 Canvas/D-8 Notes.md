### Day 8 | 04.17.22

1. [2D Context](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D)

    * lineJoin
    * lineCap

    * You don't draw directly to the canvas element but rather in the context (can be 2D or 3D)

2. [lineJoin](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineJoin)
    - shape to join two lines
    - `round`, `bevel`, and `miter`. The default is `miter`.

3. [lineCap](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineCap)
    - shape of the end points of a line 
    - `butt`(default), `round`, `square`

4. beginPath()
    - a method of context that is always called to begin a new path 

5. What's the difference between offsetX, offsetY and lastX, lastY?
    - lastX/Y are your user defined variables that stores the previous offset coordinates 
    - offset coordinates is the new position of the mouse pointer
    - there are other similar properties such as [`clientX`](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent/clientX) that reference the viewport instead of the page's coordinates. You can read more here: [HTML DOM MouseEvent](https://www.w3schools.com/jsref/obj_mouseevent.asp)

6. stroke()
    - the method that outlines the path/line

7. destructuring an array example: 
    ```javascript
        lastX = e.offsetX;
        lastY = e.offsetY;

        [lastX, lastY] = [e.offsetX, e.offsetY];
    ```

8. [hsl](https://mothereffinghsl.com/)
    - hue 0-360, saturation %, lightness %, alpha (0-1)