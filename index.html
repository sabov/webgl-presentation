<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
  <meta name="viewport" content="width=1480px">

  <title>WebGL</title>

  <link href="http://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700" rel="stylesheet" type="text/css">
  <link href="http://fonts.googleapis.com/css?family=Source+Code+Pro:400,700" rel="stylesheet" type="text/css">

  <!-- Required stylesheet -->
  <link rel="stylesheet" href="deck.js/core/deck.core.css">
  <link rel="stylesheet" media="screen" href="deck.js/extensions/menu/deck.menu.css">
  <link rel="stylesheet" media="screen" href="deck.js/extensions/goto/deck.goto.css">
  <link rel="stylesheet" media="screen" href="deck.js/extensions/status/deck.status.css">
  <link rel="stylesheet" media="screen" href="deck.js/extensions/navigation/deck.navigation.css">
  <link rel="stylesheet" media="screen" href="resources/theme.css">
  <!-- Theme -->
  <link rel="stylesheet" href="resources/layout.css">
  <link rel="stylesheet" href="resources/typography.css">

  <!-- Required Modernizr file -->
  <script src="deck.js/modernizr.custom.js"></script>

  <!-- Typekit fonts -->
  <script type="text/javascript" src="//use.typekit.net/nde6wmn.js"></script>
  <script type="text/javascript">try{Typekit.load();}catch(e){}</script>

  <!-- Required JS files. -->
  <script src="deck.js/jquery.min.js"></script>
  <script src="deck.js/core/deck.core.js"></script>
  <script src="mathbox/vendor/underscore.js"></script>
  <script src="resources/slides.js"></script>

  <!-- MathJax typesetting -->
  <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
      "HTML-CSS": { availableFonts: ["TeX"] },
      extensions: ["tex2jax.js"],
      jax: ["input/TeX","output/HTML-CSS"],
      tex2jax: {inlineMath: [["$","$"],["\\(","\\)"]]},
//      messageStyle: 'none',
    });
  </script>
  <!--<script type="text/javascript" src="../mathjax/MathJax.js?config=TeX-AMS_HTML"></script>-->

  <script type="text/javascript"
    src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
  </script>
</head>
<body>

<div class="deck-container">

<!-- Begin slides. -->
<section class="slide">
  <iframe src="iframes/cube-title.html" frameborder="0" style="height: 80%;"></iframe>
  <div class="page-cover" style="z-index: 100">
    <h1 class="cover-title" style="margin-top: 500px;">WebGL and Three.js</h1>
  </div>
  <h6 style="color: #666; margin-top: 20px;">ITJam Team</h6>
</section>

<section class="slide">
  <video class="spotlight" src="videos/webgl-demos.mp4"></video>
</section>

<section class="slide">
  <iframe src="http://threejs.org/examples/webgl_particles_sprites" frameborder="0"></iframe>
</section>

<section class="slide t-1">
  <h1>What is 3D?</h1>
</section>

<section class="slide zoom">
  <iframe src="iframes/mathbox.html#2" class="mathbox"></iframe>
  <div class="slide"></div>
  <div class="slide"></div>
  <div class="slide"></div>
</section>

<section class="slide t-1">
  <h1>Rendering</h1>
</section>

<section class="slide page-centerfold zoom">
  <iframe src="iframes/mathbox.html#1" class="mathbox"></iframe>
  <div class="slide temp abs-tc"><h3 class="mj">Bresenham Lines</h3></div>
  <div class="slide temp abs-tc"><h3 class="mj">Scanline Rendering</h3></div>
  <div class="slide"></div>
  <div class="slide temp abs-tc"><h3 class="mj">Snap To Pixel</h3></div>
  <div class="slide temp abs-tc"><h3 class="mj">"Anti-Aliasing!"</h3></div>
  <div class="slide temp abs-tc"><h3 class="mj">Sub-Pixel Accuracy</h3></div>
  <div class="slide temp abs-tc"><h3 class="mj">Samples</h3></div>
  <div class="slide temp abs-tl box images delay20" style="width: 1100px">
    <div class="l">
      <h3 class="mj">Vector World</h3>
    </div>
    <div class="r">
      <h3 class="mj">Raster World</h3>
    </div>
    <div class="l cl" style="width: 920px; padding-top: 300px">
      <h3 class="mj">Sampling</h3>
    </div>
  </div>
</section>

<!-- -->

<section class="slide t-1">
  <h1>Shaders</h1>
</section>


<section class="slide zoom">
  <iframe src="iframes/mathbox.html#3" class="mathbox"></iframe>

  <div class="slide delay10 temp inflate">
    <div class="box t1">
      <div class="r"><img src="images/raster-pipeline.png" width="700" alt=""></div>
    </div>    
  </div>
  <div class="slide temp inflate">
    <div class="box">
      <div class="r"><img src="images/raster-pipeline-2.png" width="700" alt=""></div>
    </div>    
  </div>

  <div class="slide temp inflate">
    <div class="abs-tc"><h3 class="mj">Vertex Shader</h3></div><br>
    <pre class="wrap overlay halfR small">
<em>// Global Variables</em>
<span class="mj-blue">uniform</span> mat4 projectionMatrix;
<span class="mj-blue">uniform</span> mat4 viewMatrix;
<span class="mj-blue">uniform</span> mat4 modelMatrix;

<em>// Per Vertex Attributes</em>
<span class="mj-green">attribute</span> vec3 position;

<em>// Per Vertex Code</em>
void main() {
  <span class="mj-red">gl_Position</span> = projectionMatrix
              * viewMatrix
              * modelMatrix
              * vec4(position, 1.0);
}</pre>
  </div>

  <div class="slide temp inflate">
    <div class="abs-tc"><h3 class="mj">Fragment Shader</h3></div><br>
    <pre class="wrap overlay halfR small">
<em>// Global Variables</em>
<span class="mj-blue">uniform</span> vec3 color;
<span class="mj-blue">uniform</span> vec3 direction;

<em>// Interpolated Per-Vertex Quantities</em>
<span class="mj-green">varying</span> vec3 vNormal;

<em>// Per Fragment Code</em>
void main() {
  float diffuse = dot(vNormal, direction);
  <span class="mj-red">gl_FragColor</span> =
    vec4(diffuse * color, 1.0);
}</pre>
  </div>
</section>

<section class="slide t-1">
  <h1>WebGL</h1>
</section>

<section class="slide">
  <h2>WebGL</h2>

  <p>JavaScript API for rendering interactive 2D and 3D graphics<br>
    inside an HTML <code class="language-markup">&lt;canvas&gt;</code> element.</p>
  <div class="slide">
    <h3>Browser Support</h3>
    <img src="images/webgl-browser-support.png" alt="">
  </div>
</section>



<section class="slide">
    <h2>WebGL vs OpenGL</h2>
    <div class="slide" style="color: #33AE43">
        <h3>Advantages</h3>
        <ul>
            <li>+ Browser based OpenGL ES 2.0</li>
            <li>+ HTML5, CSS3</li>
            <li>+ JavaScript</li>
            <li>+ Paste and play</li>
        </ul>
    </div>
    <br>
    <div class="slide" style="color: #9E3433">
        <h3>Disadvantages</h3>
        <ul>
            <li>- Performance</li>
            <li>- Current OpenGL version - 4.5</li>
        </ul>
    </div>
</section>

    <section class="slide">
      <h2>three.js</h2>
      <p class="slide">3D Javascript Library</p>
      <p class="slide">Renderers: WebGL, &lt;canvas&gt;, &lt;svg&gt;, CSS3D / DOM, and more</p>
      <p class="slide">Scenes, Cameras, Geometry, 3D Model Loaders, Lights, Materials,<br>Shaders, Particles, Animation, Math Utilities</p>
    </section>

    <section class="slide">
<pre class="overlay-full language-markup" style="font-size: 28px;"><code style="font-size: 28px;">&lt;!DOCTYPE html&gt;
&lt;html&gt;
  &lt;head&gt;
    &lt;title&gt;Basic Three.js App&lt;/title&gt;
    &lt;style&gt;
      html, body { margin: 0; padding: 0; overflow: hidden; }
    &lt;/style&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;script src="js/three.min.js"&gt;&lt;/script&gt;
    &lt;script&gt;
      // Javascript will go here.
    &lt;/script&gt;
  &lt;/body&gt;
&lt;/html&gt;</code></pre>
    </section>



    <section class="slide" id="scene-required">
      <pre class="overlay-full language-none" style="font-size: 24px;">
<code><span class="scene-required"><span class="token keyword">var</span> scene <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">THREE<span class="token punctuation">.</span>Scene</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span></span>
<span class="token keyword">var</span> aspect <span class="token operator">=</span> window<span class="token punctuation">.</span>innerWidth <span class="token operator">/</span> window<span class="token punctuation">.</span>innerHeight<span class="token punctuation">;</span>
<span class="scene-required"><span class="token keyword">var</span> camera <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">THREE<span class="token punctuation">.</span>PerspectiveCamera</span><span class="token punctuation">(</span> <span class="token number">75</span><span class="token punctuation">,</span> aspect<span class="token punctuation">,</span> <span class="token number">0.1</span><span class="token punctuation">,</span> <span class="token number">1000</span> <span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token keyword">var</span> renderer <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">THREE<span class="token punctuation">.</span>WebGLRenderer</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span></span>
renderer<span class="token punctuation">.</span><span class="token function">setSize<span class="token punctuation">(</span> </span>window<span class="token punctuation">.</span>innerWidth<span class="token punctuation">,</span> window<span class="token punctuation">.</span>innerHeight <span class="token punctuation">)</span><span class="token punctuation">;</span>
document<span class="token punctuation">.</span>body<span class="token punctuation">.</span><span class="token function">appendChild<span class="token punctuation">(</span> </span>renderer<span class="token punctuation">.</span>domElement <span class="token punctuation">)</span><span class="token punctuation">;</span>

<div class="slide" id="scene-object"><span class="scene-object"><span class="token keyword">var</span> geometry <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">THREE<span class="token punctuation">.</span>BoxGeometry</span><span class="token punctuation">(</span> <span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">1</span> <span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token keyword">var</span> material <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">THREE<span class="token punctuation">.</span>MeshNormalMaterial</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token keyword">var</span> cube <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">THREE<span class="token punctuation">.</span>Mesh</span><span class="token punctuation">(</span> geometry<span class="token punctuation">,</span> material <span class="token punctuation">)</span><span class="token punctuation">;</span>
scene<span class="token punctuation">.</span><span class="token function">add<span class="token punctuation">(</span></span> cube <span class="token punctuation">)</span><span class="token punctuation">;</span></span>
camera<span class="token punctuation">.</span>position<span class="token punctuation">.</span>z <span class="token operator">=</span> <span class="token number">5</span><span class="token punctuation">;</span></div>
<div class="slide" id="render-loop"><span class="render-loop"><span class="token keyword">var</span> render <span class="token operator">=</span> <span class="token keyword">function</span> <span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token function">requestAnimationFrame<span class="token punctuation">(</span></span> render <span class="token punctuation">)</span><span class="token punctuation">;</span>
  cube<span class="token punctuation">.</span>rotation<span class="token punctuation">.</span>x <span class="token operator">+</span><span class="token operator">=</span> <span class="token number">0.1</span><span class="token punctuation">;</span>
  cube<span class="token punctuation">.</span>rotation<span class="token punctuation">.</span>y <span class="token operator">+</span><span class="token operator">=</span> <span class="token number">0.1</span><span class="token punctuation">;</span>
  renderer<span class="token punctuation">.</span><span class="token function">render<span class="token punctuation">(</span></span> scene<span class="token punctuation">,</span> camera <span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span></span>

<span class="token function">render<span class="token punctuation">(</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span></div></code></pre>
    </section>

    <section class="slide instant">
      <iframe src="iframes/transforms.html" frameborder="0"></iframe>
      <h2>Object3D Transforms</h2>
      <div class="temp abs-bc"><pre><code>mesh.position.x = 0</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>mesh.position.x = -100</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>mesh.scale.set(2,2,2)</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>mesh.rotation.y = Math.PI / 4</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>mesh.rotation.y = Math.PI * 5 / 4</code></pre></div>
    </section>

    <section class="slide">
      <img class="spotlight" src="images/geometry.png" alt="">
      <div class="page-cover">
        <h1 class="cover-title">Geometry</small></h1>
      </div>
    </section>

    <section class="slide">
      <h2>Geometry</h2>
      <iframe src="iframes/geometry.html" frameborder="0"></iframe>
      <div class="slide temp abs-bc"><pre><code>var geo = new THREE.BoxGeometry( width, height, depth );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>var geo = new THREE.SphereGeometry( 60, 24, 16 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>var geo = new THREE.CylinderGeometry( ... );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>var geo = new THREE.TorusGeometry( ... );</code></pre></div>
    </section>

    <section class="slide">
      <img class="spotlight" src="images/marble.jpg" alt="">
      <div class="page-cover">
        <h1 class="cover-title cover-inverted">Materials</small></h1>
      </div>
    </section>

    <section class="slide">
      <h2>Materials</h2>
      <iframe src="iframes/material.html" frameborder="0"></iframe>
      <div class="slide temp abs-bc"><pre><code>var material = new THREE.MeshBasicMaterial({ ... });</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>var material = new THREE.MeshLambertMaterial({ ... });</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>var material = new THREE.MeshPhongMaterial({ ... });</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>var material = new THREE.MeshNormalMaterial({ ... });</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>var material = new THREE.MeshNormalMaterial({ ... });</code></pre></div>
    </section>

    <section class="slide">
      <h2>Material Properties</h2>
      <iframe src="iframes/material-options.html" frameborder="0"></iframe>
      <div class="temp abs-bc"><pre><code>shading: THREE.SmoothShading</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>shading: THREE.FlatShading</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>shading: THREE.FlatShading // face normals</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>shading: THREE.FlatShading // face normals</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>shading: THREE.SmoothShading // vertex normals</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>color: 0xaaaaaa</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>color: 0x3794cf</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>shininess: 40</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>shininess: 80</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>wireframe: true</code></pre></div>
      <div class="slide temp abs-bc"></div>
      <div class="slide temp abs-bc"><pre><code>transparent: true, opacity: 0.5</code></pre></div>
    </section>

    <div class="slide">
      <h2>UVs</h2>
      <iframe src="iframes/UVs.html" frameborder="0"></iframe>
      <div class="slide"></div>
      <div class="slide"></div>
      <div class="slide"></div>
    </div>

    <section class="slide">
      <h2>Texture Mapping</h2>
      <iframe src="iframes/texture-mapping.html" frameborder="0"></iframe>
      <div class="temp abs-bc"><pre><code>texture = THREE.ImageUtils.loadTexture("color-map.jpg");</code></pre></div>
      <div class="temp slide abs-bc"><pre><code>map: texture</code></pre></div>
      <div class="temp slide abs-bc"><pre><code>normalMap: texture</code></pre></div>
      <div class="temp slide abs-bc"><pre><code>specularMap: texture</code></pre></div>
      <div class="temp slide abs-bc"><pre><code>map: colorMap, specularMap: specMap, normalMap: normalMap</code></pre></div>
      <div class="temp slide abs-bc"><pre><code>var material = new THREE.MeshPhongMaterial({
  color: 0xaaaaaa,
  ambient: 0xaaaaaa,
  specular: 0x333333,
  shininess: 15,
  map: colorMap,
  specularMap: specMap,
  normalMap: normalMap
});</code></pre></div>
    </section>

    <section class="slide">
      <img class="spotlight" src="images/sunny-sky.jpg" alt="">
      <div class="page-cover">
        <h1 class="cover-title cover-inverted">Lights</small></h1>
      </div>
    </section>

    <section class="slide">
      <h2>Lights</h2>
      <iframe src="iframes/lights.html" frameborder="0"></iframe>
      <div class="temp abs-bc"><pre><code>light = new THREE.DirectionalLight( 0xdddddd, 0.8 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light.position.set( -80, 80, 80 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light.position.x = 80;</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light.target.position = 160;</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light.position.x = -80;</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light = new THREE.DirectionalLight( 0xdddddd, 0.8 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light = new THREE.DirectionalLight( 0xb4e7f2, 0.8 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light = new THREE.DirectionalLight( 0xb4e7f2, 0.2 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light = new THREE.DirectionalLight( 0xb4e7f2, 1.5 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light = new THREE.DirectionalLight( 0xb4e7f2, 0.8 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light = new THREE.PointLight( 0xb4e7f2, 0.8 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light = new THREE.PointLight( 0xb4e7f2, 0.8 );</code></pre></div>
      <!-- <div class="slide temp abs-bc"><pre><code>light.distance = 300;</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light.distance = 0;</code></pre></div> -->
      <div class="slide temp abs-bc"><pre><code>light = new THREE.SpotLight( 0xb4e7f2, 0.8 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light.angle = Math.PI / 9;</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light.angle = Math.PI / 5;</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light.exponent = 10;</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light.exponent = 1;</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light.exponent = 20;</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light = new THREE.AmbientLight( 0x444444 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light = new THREE.AmbientLight( 0x000000 );</code></pre></div>
      <div class="slide temp abs-bc"><pre><code>light = new THREE.AmbientLight( 0x444444 );</code></pre></div>
    </section>

    <section class="slide">
      <iframe src="iframes/lights-three-point.html" frameborder="0"></iframe>
      <h2 style="position: relative;">Three Point Lighting</h2>
      <div class="temp abs-bc bc-text outline">Key, Fill, Rim</div>
      <div class="slide temp abs-bc bc-text outline">Key, Fill, Rim</div>
    </section>

    <section class="slide">
      <h2>Model Converter</h2>
      <p>OBJ to JSON converter python tool<br>
        /three.js/utils/converters/obj/convert_obj_three.py</p>
      <p><img src="images/obj-json.png" alt=""></p>
      <div class="temp abs-bc"><pre><code class="language-python">python convert_obj_three.py -i teapot.obj -o teapot.js</code></pre></div>
    </section>

    <section class="slide">
      <iframe src="iframes/loader.html" frameborder="0"></iframe>
      <h2>Model Loader</h2>
<div class="slide temp abs-bc"><pre><code>var loader = new THREE.JSONLoader();

loader.load("teapot.js", function( geometry, materials ) {
  material = new THREE.MeshFaceMaterial( materials );
  mesh = new THREE.Mesh( geometry, material );
  scene.add( mesh );
});</code></pre></div>
    </section>

    <section class="slide">
      <!-- <iframe src="http://threejs.org/examples/webgl_materials_cubemap" frameborder="0"></iframe> -->
      <iframe src="iframes/cubemap.html" frameborder="0"></iframe>
      <div class="slide"></div>
      <div class="slide"></div>
    </section>

    <section class="slide">
      <img class="spotlight" src="images/interaction.png" alt="">
      <div class="page-cover">
        <h1 class="cover-title">Interaction</small></h1>
      </div>
    </section>

    <section class="slide">
      <!-- http://stemkoski.github.io/Three.js/Mouse-Over.html -->
      <!-- http://threejs.org/examples/webgl_interactive_cubes -->
      <!-- http://soledadpenades.com/articles/three-js-tutorials/object-picking/ -->
      <iframe src="http://threejs.org/examples/webgl_interactive_cubes" frameborder="0"></iframe>
    </section>

    <section class="slide instant">
      <iframe src="iframes/interactive-cubes-helpers.html" frameborder="0"></iframe>
      <div class="slide"></div>
      <div class="slide"></div>
    </section>

    <section class="slide">
<pre class="overlay-full language-none" style="font-size: 26px;"><code><span class="interaction1"><span class="token comment" spellcheck="true">// normalized device coordinates
</span>mouse<span class="token punctuation">.</span>x <span class="token operator">=</span> <span class="token punctuation">(</span> event<span class="token punctuation">.</span>clientX <span class="token operator">/</span> window<span class="token punctuation">.</span>innerWidth <span class="token punctuation">)</span> <span class="token operator">*</span> <span class="token number">2</span> <span class="token operator">-</span> <span class="token number">1</span><span class="token punctuation">;</span>
mouse<span class="token punctuation">.</span>y <span class="token operator">=</span> <span class="token operator">-</span> <span class="token punctuation">(</span> event<span class="token punctuation">.</span>clientY <span class="token operator">/</span> window<span class="token punctuation">.</span>innerHeight <span class="token punctuation">)</span> <span class="token operator">*</span> <span class="token number">2</span> <span class="token operator">+</span> <span class="token number">1</span><span class="token punctuation">;</span></span>

raycaster <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">THREE<span class="token punctuation">.</span>Raycaster</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="interaction2"><span class="token keyword">var</span> vector <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">THREE<span class="token punctuation">.</span>Vector3</span><span class="token punctuation">(</span> mouse<span class="token punctuation">.</span>x<span class="token punctuation">,</span> mouse<span class="token punctuation">.</span>y<span class="token punctuation">,</span> <span class="token number">1</span> <span class="token punctuation">)</span><span class="token punctuation">.</span><span class="token function">unproject<span class="token punctuation">(</span></span> camera <span class="token punctuation">)</span><span class="token punctuation">;</span></span>

<span class="interaction3">raycaster<span class="token punctuation">.</span><span class="token keyword">set</span><span class="token punctuation">(</span> camera<span class="token punctuation">.</span>position<span class="token punctuation">,</span> vector<span class="token punctuation">.</span><span class="token function">sub<span class="token punctuation">(</span></span> camera<span class="token punctuation">.</span>position <span class="token punctuation">)</span><span class="token punctuation">.</span><span class="token function">normalize<span class="token punctuation">(</span></span><span class="token punctuation">)</span> <span class="token punctuation">)</span><span class="token punctuation">;</span></span>

<span class="interaction4"><span class="token keyword">var</span> intersects <span class="token operator">=</span> raycaster<span class="token punctuation">.</span><span class="token function">intersectObjects<span class="token punctuation">(</span></span> scene<span class="token punctuation">.</span>children <span class="token punctuation">)</span><span class="token punctuation">;</span>

INTERSECTED <span class="token operator">=</span> intersects<span class="token punctuation">[</span> <span class="token number">0</span> <span class="token punctuation">]</span><span class="token punctuation">.</span>object<span class="token punctuation">;</span></span></code></pre>
      <div class="slide" id="interaction1"></div>
      <div class="slide" id="interaction2"></div>
      <div class="slide" id="interaction3"></div>
      <div class="slide" id="interaction4"></div>
    </section>

<section class="slide" style="margin-top: 250px">
    Diagrams powered by <a href="http://acko.net/blog/making-mathbox" target="_blank">MathBox</a>.<br>
    Based on <a href="https://github.com/unconed/fullfrontal/tree/master/webglmath" target="_blank">Making WebGL Dance</a> presentation by Steven Wittens<br>
    and <a href="https://github.com/davidlyons/frontporch" target="_blank">Intro to WebGL
    with Three.js</a> by David Lyons.
</section>

<section class="slide">
  <h1>Thanks!</h1>
</section>


<!-- End slides. -->
</div>

<div id="message">
  <script type="text/javascript">
  if (!document.createElement('canvas').getContext('experimental-webgl')) {
    document.write('<p class="error"><strong>Sorry! Your browser does not support WebGL, which is required to view this presentation.</strong><br>Video will be made available soon.<!--<br><br>You can <a href="http://www.youtube.com/watch?v=GNO_CYUjMK8">view the video on YouTube</a> instead.<br><br>Or you can use Google Chrome or Mozilla Firefox.</p>-->');
  }
  </script>
</div>

<div id="context">
    Diagrams powered by <a href="http://acko.net/blog/making-mathbox" target="_blank">MathBox</a>.<br>
    Based on <a href="https://github.com/unconed/fullfrontal/tree/master/webglmath" target="_blank">Making WebGL Dance</a> presentation by Steven Wittens<br>
    and <a href="https://github.com/davidlyons/frontporch" target="_blank">Intro to WebGL
    with Three.js</a> by David Lyons.
</div>

</section>


<!-- End slides. -->
</div>

<div id="message">
  <script type="text/javascript">
  if (!document.createElement('canvas').getContext('experimental-webgl')) {
    document.write('<p class="error"><strong>Sorry! Your browser does not support WebGL, which is required to view this presentation.</strong><br>Video will be made available soon.<!--<br><br>You can <a href="http://www.youtube.com/watch?v=GNO_CYUjMK8">view the video on YouTube</a> instead.<br><br>Or you can use Google Chrome or Mozilla Firefox.</p>-->');
  }
  </script>
</div>

<div id="controls">
  <a href="javascript:$.deck('prev')">‹</a>
  <a href="javascript:$.deck('next')">›</a>
</div>

<script type="text/javascript">

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-288349-2']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>

</body>
</html>
