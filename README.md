LESS DSS (dynamic stylesheet)
=============

A set of useful mixins for LESS, the CSS pre-processor: <a href="http://lesscss.org" target="_blank">lesscss.org</a>
<br/>I recommend '<a href="http://incident57.com/codekit/" target="_blank">CodeKit</a>' app for auto compress (not only for less) ;) (OS X)
<br/>
List of all functions is on: <a href="http://mrkrupski.github.com/LESS-Dynamic-Stylesheet/" target="_blank">mrkrupski.github.com/LESS-Dynamic-Stylesheet/</a>

   <b>Examples how to use functions contained in the less.dss file:</b>

 <ul>
   <h3>CSS Backgrounds</h3>
   <hr/>
   <li><b>.gradient-h</b>           - CSS3 - Horizontal background gradient.</li>
   <code>.gradient-h(#fff, #aaa);</code>

   <li><b>.gradient-hline</b>       - CSS3 - Horizontal-linear background gradient.</li>
   <code>.gradient-hline(#fff, #ddd, #aaa, #ddd);</code>

   <li><b>gradient-v</b>            - CSS3 - Vertical background gradient.</li>
   <code>.gradient-v(#fff, #aaa);</code>

   <li><b>.gradient-v3colors</b>    - CSS3 - Three-color background gradient.</li>
   <code>.gradient-v3colors(#00b3ee, #7a43b6, 50%, #c3325f);</code>

   <li><b>.gradient-radial</b>      - CSS3 - Radial background gradient.</li>
   <code>.gradient-radial(#fff, #aaa);</code>

   <li><b>.gradient-direction</b>   - CSS3 - Directional background gradient (type only the value - extension is added automatically).</li>
   <code>.gradient-direction(#fff, #aaa, 120);</code>

   <li><b>.background-clip</b>      - Crop the backgroud of an element (border-box | padding-box | content-box).</li>
   <code>.background-clip(border-box);</code>

   <li><b>.background-size</b>      - Control the size of background images via CSS3.</li>
   <code>.background-size(100%, 50%);</code>

   <br/>
   <h3>CSS3 Borders</h3>
   <hr/>
   <li><b>.box-shadow</b>           - CSS3 - The box-shadow property attaches one or more drop-shadows to the box (always add <b>"</b> before and after values - thanks to that you can use many shadows at the same time).</li>
   <code>.box-shadow("0 0 5px blue");</code>
   <br/>
   <code>.box-shadow("0 0 5px blue, inset 2px 2px 10px rgba(0,0,0, .2), 0 1px 4px #000");</code>

   <li><b>.border-image</b>         - CSS3 - Define an image to be used instead of the normal border of an element.</li>
   <code>.border-image(url(picture.img));</code>
   <br/>
   <code>.border-image(url(picture.img), 100%, 1, 0, stretch);</code>

   <li><b>.rounded</b>              - CSS3 - Round the corners of an element. Can be a single value or four space-separated values.</li>
   <code>.rounded(10px);</code>

   <li><b>.box-sizing</b>           - Change the box model for an element (e.g., border-box for a full-width input).</li>
   <code>.box-sizing(border-box);</code>

   <li><b>.tab-size</b>             - CSS3 - The tab-size CSS property is used to customize the width of a tab character.</li>
   <code>.tab-size(8);</code>

   <br/>
   <h3>CSS3 2D Transforms</h3>
   <hr/>
   <li><b>.translate</b>            - CSS3 - With the translate() method, the element moves from its current position (X-axis - left, Y-axis - top).</li>
   <code>.translate(20, 40);</code>

   <li><b>.rotate</b>               - CSS3 - With the rotate() method, the element rotates clockwise at a given degree (type only the value - extension is added automatically).</li>
   <code>.rotate(3);</code>

   <li><b>.scale</b>                - CSS3 - With the scale() method, the element increases or decreases the size.</li>
   <code>.scale(.8);</code>

   <li><b>.skew</b>                 - CSS3 - With the skew() method, the element turns in a given angle (X-axis - horizontal, Y-axis - vertical) (type only the value - extension is added automatically).</li>
   <code>.skew(30, 4);</code>

   <li><b>.matrix</b>               - CSS3 - The matrix() method combines all of the 2D transform methods into one.</li>
   <code>.matrix(0.9, 0.2, -0.5, 0.9, 0, 0);</code>

   <br/>
   <h3>CSS3 3D Transforms</h3>
   <hr/>
   <li><b>.rotateX</b>              - CSS3 - With the rotateX() method, the element rotates around its X-axis at a given degree (type only the value - extension is added automatically).</li>
   <code>.rotateX(180);</code>

   <li><b>.rotateY</b>              - CSS3 - With the rotateY() method, the element rotates around its Y-axis at a given degree (type only the value - extension is added automatically).</li>
   <code>.rotateY(40);</code>

   <li><b>.translate3d</b>          - CSS3 - Is the same that the 'translate' option but we have at our disposal 3 values (X-axis, Y-axis, Z-axis).</li>
   <code>.translate3d(8, 5, 4);</code>

   <li><b>.perspective</b>          - CSS3 - Defines a perspective view for a 3D transformed element.</li>
   <code>.perspective(140);</code>

   <br/>
   <h3>CSS3 2D & 3D Transforms</h3>
   <hr/>
   <h6><i>(they are acting only in steam with other functions from "2D & 3D Transforms" group)</i></h6>
   <li><b>.transform-origin</b>           - The transform-origin property allows you to change the position on transformed elements.</li>
   <code>.transform-origin(50%, 50%, 0);</code>

   <li><b>.transform-style</b>           - CSS3 - The transform-style property specifies how nested elements are rendered in 3D space.</li>
   <code>.transform-style(preserve-3d);</code>

   <br/>
   <h3>CSS3 Transitions</h3>
   <hr/>
   <li><b>.transition</b>           - CSS3 - Add an effect when changing from one style to another.</li>
   <code>.transition(width, .7s);</code>

   <br/>
   <h3>CSS3 Animations</h3>
   <hr/>
   <li><b>.animate</b>              - CSS3 - Create animations (checkout: http://daneden.me/animate/ - pack of done animations).</li>
   <code>.animate(wobble);</code>
   <br/>
   <code>.animate(fadeIn, 0, ease, 2s, 1, normal, running);</code>

   <br/>
   <h3>CSS3 Multiple Columns</h3>
   <hr/>
   <li><b>.columns</b>              - CSS3 - Create multiple columns for laying out text (like in newspapers).</li>
   <code>.columns(auto 2, normal, medium none black);</code>

   <br/>
   <h3>CSS Misc</h3>
   <hr/>
   <li><b>.clearfix</b>             - Add to any parent to clear floats within (value = none).</li>
   <code>.clearfix;</code>

   <li><b>.font</b>                 - Font-size, line-height and weight.</li>
   <code>.font(28, 34, bold);</code>

   <li><b>.size</b>                 - Quickly set the height and width on one line (you can enter only the values) (type only the value - extension is added automatically).</li>
   <code>.size(200, 100);</code>

   <li><b>.square</b>               - Use this if height and width have the same values (type only the value - extension is added automatically).</li>
   <code>.square(400);</code>

   <li><b>.opacity</b>              - Elements transparency (full = 1 not 100).</li>
   <code>.opacity(.5);</code>

   <li><b>.less-button</b>          - Quickly create a customize button <i>(background-color, border-color, text color, text-shadow, font-weight, padding, rounded corners)</i>.</li>
   <code>.less-button(#ccc, #999, #444, 0 1px 0 rgba(255,255,255,0.40), normal, 6px 18px, 4px);</code>
</ul>