LESS DSS (dynamic stylesheet)
=============

A set of useful mixins for LESS, the CSS pre-processor: <a href="http://lesscss.org" target="_blank">lesscss.org</a>
<br/>I recommend '<a href="http://incident57.com/codekit/" target="_blank">CodeKit</a>' app for best work results :) (only OS X)

   <b>Features:</b>
   
   <ul>
   <li><b>.gradient-h</b>            - CSS3 - horizontal gradient (works also on IE)</li>
   <code>.gradient-h(#fff, #fbfbfb);</code>

   <li><b>.gradient-hline</b>         - CSS3 - horizontal-linear gradient (works also on IE)</li>
   <code>.gradient-h(#B0BAC5, #9DA7B2, #919CA8, #7E8A98);</code>

   <li><b>.gradient-v</b>            - CSS3 - veritical gradient (works also on IE)</li>
   <code>.gradient-v(#fff, #fbfbfb);</code>
   
   <li><b>.gradient-radial</b>       - CSS3 - radial gradient (works also on IE9+)</li>
   <code>.gradient-radial(#fff, #fbfbfb);</code>

   <li><b>.gradient-direction</b>    - CSS3 - radial gradient (works also on IE9+)</li>
   <code>.gradient-direction(#fff, #fbfbfb, 45deg);</code>

   <br/>

   <li><b>.bordered</b>              - custom borders color and size style</li> 
   <code>.bordered(#EEE, #CCC, #999, #333, 1px);</code>

   <br/>

   <li><b>.alpha-shadow</b>          - CSS3 - transparent black shadow</li>
   <code>.alpha-shadow(0 0 4px, 0.6);</code>

   <li><b>.outer-shadow</b>          - CSS3 - outher element shadow</li>
   <code>.outer-shadow(0px 0px 0.83em, #333);</code>
   
   <li><b>.inner-shadow</b>          - CSS3 - shadow inside the element</li>
   <code>.inner-shadow(0px 0px 1px, #fbfbfb);</code>
   
   <li><b>.io-shadow</b>             - CSS3 - inner & outer shadow</li>
   <code>.io-shadow(0px 1px 0px rgba(255, 255, 255, 0.4), 0px 1px 2px rgba(0, 0, 0, 0.3));</code>
   
   <br/>

   <li><b>.rounded</b>               - CSS3 - rounded corners</li>
   <code>.rounded(4px);</code> or <code>.rounded(4px 2px 3px 0);</code>
   
   <li><b>.box-sizing</b>            - box-model fixes</li>
   <code>.box-sizing();</code>
   
   <br/>

   <li><b>.opacity</b>               - transparency for the elements</li>
   <code>.opacity(0.5);</code>
   
   <li><b>.font</b>                  - font size, line-height and weight</li>
   <code>.font(1em, 1.25em, bold);</code>
   
   <br/>

   <li><b>.rotate</b>                - CSS3 - simple rotate elements</li>
   <code>.rotate(5deg);</code>

   <li><b>.scale</b>                 - CSS3 - the elements scaling</li>
   <code>.scale(1.5);</code>

   <li><b>.skew</b>                  - CSS3 - the elements turns in a given angle</li>
   <code>.skew(20deg, 40deg);</code>

   <li><b>.transition</b>            - CSS3 - transition effects</li>
   <code>.transition(all, 0.2s, ease-out, 1s);</code>

   <li><b>.animation</b>             - CSS3 - simple add animation (required: <http://daneden.me/animate/> but you also can create your own animation)</li>
   <code>.animation(fadeOut);</code> or <code>.animation(fadeIn, 0, ease, 2s, 1, normal, running);</code>

   <li><b>.translate</b>             - CSS3 - transform elements (works also on IE9+)</li>
   <code>.translate(10, 0);</code>

   <br/>

   <li><b>.columns</b>               - CSS3 - text management</li>
   <code>.columns(250, 0, 50, #EEE, solid, 1px);</code>

   <li><b>.size</b>                  - CSS3 - simple determination 'width & height' of elements</li>
   <code>.size(40px, 50px);</code>
   
   <li><b>.clearfix</b>              - CSS3 - clearing floats</li>
   <code>.clearfix;</code>

   <li>
   <b>.less-button</b>               - quickly create your own buttons (background color, border color, text color, text shadow, font weight, padding, rounded corners)
   </li>
   <code>.less-button(#ccc, #999, #444, 0 1px 0 rgba(255,255,255,0.40), normal, 6px 18px, 4px)</code>
 </ul>
