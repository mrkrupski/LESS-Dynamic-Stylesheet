LESS DSS (dynamic stylesheet)
=============

It's a set of useful mixins for LESS, the CSS pre-processor: <a href="http://lesscss.org" target="_blank">lesscss.org</a>.
<br/>I recommend a "<a href="http://incident57.com/codekit/" target="_blank">CodeKit</a>" app for the auto compress (OS X).

<b>Examples how to use the functions contained in "less.dss" (v1.8.1) file:</b>

 <ul>
   <h3>Backgrounds Group</h3>
   <hr/>

   <li><b>.gradient-h</b></li>
   <code>.gradient-h ( #fff, #aaa );</code>

   <li><b>gradient-v</b></li>
   <code>.gradient-v ( #fff, #aaa );</code>

   <li><b>.gradient-vline</b></li>
   <code>.gradient-vline ( #fff, #ddd, #aaa, #ddd );</code>

   <li><b>.gradient-v3colors</b></li>
   <code>.gradient-v3colors ( #00b3ee, #7a43b6, 50%, #c3325f );</code>

   <li><b>.gradient-radial</b></li>
   <code>.gradient-radial ( #fff, #aaa );</code>

   <li><b>.gradient-direction</b></li>
   <code>.gradient-direction ( #fff, #aaa, 120 );</code>

   <li><b>.bg-clip</b></li>
   <code>.bg-clip ( border-box );</code>
   <br/>
   <code>.bg-clip ( border );</code>

   <li><b>.bg-size</b></li>
   <code>.bg-size ( 100%, 50% );</code>

   <br/>
   <h3>Box Group</h3>
   <hr/>

   <li><b>.box-align</b></li>
   <code>.box-align ( baseline );</code>

   <li><b>.box-direction</b></li>
   <code>.box-direction ( normal );</code>

   <li><b>.box-orient</b></li>
   <code>.box-orient ( horizontal );</code>

   <li><b>.box-pack</b></li>
   <code>.box-pack ( center );</code>

   <li><b>.box-sizing</b></li>
   <code>.box-sizing ( content-box );</code>

   <li><b>.box-shadow</b></li>
   <code>.box-shadow ( "0 0 5px blue, inset 2px 2px 10px rgba (0,0,0, .2), 0 1px 4px #000" );</code> (multi)
   <br/>
   <code>.box-shadow ( in, 0 1px 4px #ddd );</code> (inset)
   <br/>
   <code>.box-shadow ( out, 0 1px 4px rgba(0,0,0, .5) );</code> (outset)
   <br/>
   <code>.box-shadow ( 0 1px 4px, #ccc, 45% );</code> (alpha)

   <br/>
   <h3>Border Group</h3>
   <hr/>

   <li><b>.border-image</b></li>
   <code>.border-image ( "../img/picture.img", 30 30 repeat );</code>

   <li><b>.rounded</b></li>
   <code>.rounded ( 10px );</code>
   <br/>
   <code>.rounded ( 3px 2px 4px 10px );</code>
   <br/>
   <code>.rounded ( top, 5 );</code>
   <br/>
   <code>.rounded ( right, 5 );</code>
   <br/>
   <code>.rounded ( bottom, 5 );</code>
   <br/>
   <code>.rounded ( left, 5 );</code>

   <br/>
   <h3>Transform Group</h3>
   <hr/>

   <li><b>.transform</b></li>
   <code>.transform ( perspective(0) translate3d(50px, 40px, 80px) scale3d(1, 2, 0) rotate3d(0, 1, 0, 45deg) );</code>

   <li><b>.matrix</b></li>
   <code>.matrix ( 0.9, 0.2, -0.5, 0.9, 0, 0 );</code>

   <li><b>.matrix3d</b></li>
   <code>.matrix3d ( "1, 0, 0, 0, 0, 0.60, 0, -0.0009, 0, 0, 1, 0, 0, 0, 0, 1" );</code>

   <li><b>.rotate</b></li>
   <code>.rotate ( 45 );</code>
   <br/>
   <code>.rotate ( x, 45 );</code>
   <br/>
   <code>.rotate ( y, 45 );</code>
   <br/>
   <code>.rotate ( z, 45 );</code>

   <li><b>.rotate3d</b></li>
   <code>.rotate ( 15, 10, 5, 45 );</code>
   
   <li><b>.scale</b></li>
   <code>.scale ( 0.8 );</code>
   <br/>
   <code>.scale ( x, 0.4 );</code>
   <br/>
   <code>.scale ( y, 1.3 );</code>
   <br/>
   <code>.scale ( z, .7 );</code>

   <li><b>.scale3d</b></li>
   <code>.scale3d ( .4, .5, 1.2 );</code>

   <li><b>.translate</b></li>
   <code>.translate ( 20, 40 );</code>
   <br/>
   <code>.translate ( x, 20 );</code>
   <br/>
   <code>.translate ( y, 40 );</code>
   <br/>
   <code>.translate ( z, 60 );</code>

   <li><b>.translate3d</b></li>
   <code>.translate3d ( 20, 40, 60 );</code>

   <li><b>.skew</b></li>
   <code>.skew ( 30, 4 );</code>
   <br/>
   <code>.skew ( x, 20 );</code>
   <br/>
   <code>.skew ( y, -30 );</code>

   <li><b>.perspective</b></li>
   <code>.perspective ( 250 );</code>
   <br/>
   <code>.perspective ( 250, px );</code>

   <li><b>.perspective-origin</b></li>
   <code>.perspective-origin ( 50% 50% );</code>

   <li><b>.transform-origin</b></li>
   <code>.transform-origin ( 30%, 40%, 0 );</code>

   <li><b>.transform-style</b></li>
   <code>.transform-style ( preserve-3d );</code>

   <br/>
   <h3>Transition</h3>
   <hr/>

   <li><b>.transition</b></li>
   <code>.transition ( width, .7s );</code>
   <br/>
   <code>.transition ( property, 0.2s, ease-out, 0 );</code>

   <br/>
   <h3>Animation Group</h3>
   <span>(checkout: http://daneden.me/animate/)</span>
   <hr/>

   <li><b>.animate</b></li>
   <code>.animate ( wobble );</code>
   <br/>
   <code>.animate ( wobble, 2s, ease, 0, 1, normal );</code>

   <li><b>.animation-state</b></li>
   <code>.animation-state ( running );</code>

   <br/>
   <h3>Column</h3>
   <hr/>

   <li><b>.columns</b></li>
   <code>.columns ( 2, normal );</code>

   <br/>
   <h3>Misc Group</h3>
   <hr/>

   <li><b>.opacity</b></li>
   <code>.opacity ( 0.7 );</code>

   <li><b>.font</b></li>
   <code>.font ( italic, normal, bold, 14px, 1, "'Lucida Grande', Helvetica, Arial, Verdana, sans-serif" );</code>

   <li><b>.font-face</b></li>
   <code>.font-face ( MyFontName, "../assets/fonts/sofia-pro" );</code>

   <li><b>.size</b></li>
   <code>.size ( 400, 200 );</code>

   <li><b>.square</b></li>
   <code>.square ( 400 );</code>

   <li><b>.resizable</b></li>
   <code>.resizable ( vertical );</code>

   <li><b>.hide-text</b></li>
   <code>.hide-text;</code>

   <li><b>.center-block</b></li>
   <code>.center-block;</code>

   <li><b>.clearfix</b></li>
   <code>.clearfix;</code>
</ul>