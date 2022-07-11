<h1 class="gap">0x01. AirBnB clone - Web static</h1>
<h2>Background Context</h2>

<h3>Web static, what?</h3>

<p>Now that you have a command interpreter for managing your AirBnB objects, it&rsquo;s time to make them alive!</p>

<p>Before developing a big and complex web application, we will build the front end step-by-step. </p>

<p>The first step is to &ldquo;design&rdquo; / &ldquo;sketch&rdquo; / &ldquo;prototype&rdquo; each element:</p>

<ul>
<li>Create simple HTML static pages</li>
<li>Style guide</li>
<li>Fake contents</li>
<li>No Javascript</li>
<li>No data loaded from anything</li>
</ul>

<p>During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be the first thing to write. CSS is the styling of your page, the design. I really encourage you to fix your HTML part before starting the styling. Indeed, without any structure, you can&rsquo;t apply any design.</p>

<p>Before starting, please fork or clone the repository <code>AirBnB_clone</code> from your partner if you were not the owner of the previous project.</p>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/qq7qrSgdVRuD1kPd_jf7Fw" title="Learn to Code HTML &amp; CSS" target="_blank">Learn to Code HTML &amp; CSS</a> (<em>until &ldquo;Creating Lists&rdquo; included</em>)</li>
<li><a href="/rltoken/xW69RnLZMt3AusI1SDvr8g" title="Inline Styles in HTML" target="_blank">Inline Styles in HTML</a> </li>
<li><a href="/rltoken/sO3wz-QbhwYdKJqvokC4PA" title="Specifics on CSS Specificity" target="_blank">Specifics on CSS Specificity</a> </li>
<li><a href="/rltoken/NvqQf3dgY64bb-QWC5Cueg" title="CSS SpeciFishity" target="_blank">CSS SpeciFishity</a> </li>
<li><a href="/rltoken/STaxnOI5qv1enUuwIALelw" title="Introduction to HTML" target="_blank">Introduction to HTML</a> </li>
<li><a href="/rltoken/g-uj9Azx1rALX49xCZHK0w" title="CSS" target="_blank">CSS</a> </li>
<li><a href="/rltoken/El1BHRNNO2hPEcOt_XwF-Q" title="MDN" target="_blank">MDN</a> </li>
<li><a href="/rltoken/HI0qRNDq20cgICIhO18kUQ" title="center boxes" target="_blank">center boxes</a> </li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/O8BWXDOfoda19l0QdcprUg" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What is HTML</li>
<li>How to create an HTML page</li>
<li>What is a markup language</li>
<li>What is the DOM</li>
<li>What is an element / tag</li>
<li>What is an attribute</li>
<li>How does the browser load a webpage</li>
<li>What is CSS</li>
<li>How to add style to an element</li>
<li>What is a class</li>
<li>What is a selector</li>
<li>How to compute CSS Specificity Value</li>
<li>What are Box properties in CSS</li>
</ul>

<h2>Requirements</h2>

<h3>General</h3>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your files should end with a new line</li>
<li>A <code>README.md</code> file, at the root of the folder of the project, is mandatory</li>
<li>Your code should be W3C compliant and validate with <a href="/rltoken/4dtXqWSyIeSCFVqQ9Eo6NA" title="W3C-Validator" target="_blank">W3C-Validator</a></li>
<li>All your CSS files should be in <code>styles</code> folder</li>
<li>All your images should be in <code>images</code> folder</li>
<li>You are not allowed to use <code>!important</code> and <code>id</code> (<code>#...</code> in the CSS file)</li>
<li>You are not allowed to use tags <code>img</code>, <code>embed</code> and <code>iframe</code></li>
<li>You are not allowed to use Javascript</li>
<li>Current screenshots have been done on <code>Chrome 56</code> or more. </li>
<li>No cross browsers </li>
<li>You have to follow all requirements but some <code>margin</code>/<code>padding</code> are missing - you should try to fit as much as you can to screenshots</li>
</ul>

<h2>More Info</h2>

<p><img src="https://s3.amazonaws.com/intranet-projects-files/concepts/74/hbnb_step1.png" alt="" style="" /></p>

  </div>
</div>

<h2 class="gap">Tasks</h2>
<h3 class="panel-title">
      0. Inline styling
    </h3>

<p>Write an HTML page that displays a header and a footer.</p>

<p>Layout:</p>

<ul>
<li>Body:

<ul>
<li>no margin</li>
<li>no padding</li>
</ul></li>
<li>Header:

<ul>
<li>color #FF0000 (red)</li>
<li>height: 70px</li>
<li>width: 100%</li>
</ul></li>
<li>Footer:

<ul>
<li>color #00FF00 (green)</li>
<li>height: 60px</li>
<li>width: 100%</li>
<li>text <code>Best School</code> center vertically and horizontally</li>
<li>always at the bottom at the page</li>
</ul></li>
</ul>

<p>Requirements:</p>

<ul>
<li>You must use the <code>header</code> and <code>footer</code> tags</li>
<li>You are not allowed to import any files</li>
<li>You are not allowed to use the <code>style</code> tag in the <code>head</code> tag</li>
<li>Use inline styling for all your tags</li>
</ul>

<p><img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2021/12/9b4481f4cfe46adc8fbf48e31c0b24236f597653.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220711%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220711T152211Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d0b0d845a44e88d6bb57f165718a679311a8c51bd1d89e23b6cc480cf48cd178" alt="" style="width: 100%" /></p>

  </div>

  <div class="list-group">
<h3 class="panel-title">
      1. Head styling
    </h3>
<p>Write an HTML page that displays a header and a footer by using the <code>style</code> tag in the <code>head</code> tag (same as <code>0-index.html</code>)</p>

<p>Requirements:</p>

<ul>
<li>You must use the <code>header</code> and <code>footer</code> tags</li>
<li>You are not allowed to import any files</li>
<li>No inline styling</li>
<li>You must use the <code>style</code> tag in the <code>head</code> tag</li>
</ul>

<p>The layout must be exactly the same as <code>0-index.html</code></p>

  </div>
 <h3 class="panel-title">
      2. CSS files
    </h3>

	<p>Write an HTML page that displays a header and a footer by using CSS files (same as <code>1-index.html</code>)</p>

<p>Requirements:</p>

<ul>
<li>You must use the <code>header</code> and <code>footer</code> tags</li>
<li>No inline styling</li>
<li>You must have 3 CSS files:

<ul>
<li><code>styles/2-common.css</code>: for global style (i.e. the <code>body</code> style)</li>
<li><code>styles/2-header.css</code>: for header style</li>
<li><code>styles/2-footer.css</code>: for footer style</li>
</ul></li>
</ul>

<p>The layout must be exactly the same as <code>1-index.html</code></p>

  </div>

  <div class="list-group">

 <h3 class="panel-title">
      3. Zoning done!
    </h3>

  <p>Write an HTML page that displays a header and footer by using CSS files (same as <code>2-index.html</code>)</p>

<p>Layout:</p>

<ul>
<li>Common:

<ul>
<li>no margin</li>
<li>no padding</li>
<li>font color: #484848</li>
<li>font size: 14px</li>
<li>font family: <code>Circular,&quot;Helvetica Neue&quot;,Helvetica,Arial,sans-serif;</code></li>
<li><a href="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/icon.png" title="icon" target="_blank">icon</a> in the browser tab</li>
</ul></li>
<li>Header:

<ul>
<li>color: white</li>
<li>height: 70px</li>
<li>width: 100%</li>
<li>border bottom 1px #CCCCCC</li>
<li><a href="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/logo.png" title="logo" target="_blank">logo</a> align on left and center vertically (20px space at the left)</li>
</ul></li>
<li>Footer:

<ul>
<li>color white</li>
<li>height: 60px</li>
<li>width: 100%</li>
<li>border top 1px #CCCCCC</li>
<li>text <code>Best School</code> center vertically and horizontally</li>
<li>always at the bottom at the page</li>
</ul></li>
</ul>

<p>Requirements:</p>

<ul>
<li>No inline style</li>
<li>You are not allowed to use the <code>img</code> tag</li>
<li>You are not allowed to use the <code>style</code> tag in the <code>head</code> tag</li>
<li>All images must be stored in the <code>images</code> folder</li>
<li>You must have 3 CSS files:

<ul>
<li><code>styles/3-common.css</code>: for the global style (i.e <code>body</code> style)</li>
<li><code>styles/3-header.css</code>: for the header style</li>
<li><code>styles/3-footer.css</code>: for the footer style</li>
</ul></li>
</ul>

<p><img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2021/12/14f2c84c49affbb865ff84a3292d2e76a211993c.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220711%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220711T152211Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0eac11f05c9c232368728b2121bc1b055490a40d9328d625555aacc3b40d16e5" alt="" style="width: 100%" /></p>

  </div>
 <h3 class="panel-title">
      4. Search!
    </h3>
 <p>Write an HTML page that displays a header, footer and a filters box with a search button.</p>

<p>Layout: (based on <code>3-index.html</code>)</p>

<ul>
<li>Container:

<ul>
<li>between <code>header</code> and <code>footer</code> tags, add a <code>div</code>:

<ul>
<li>classname: <code>container</code></li>
<li>max width 1000px</li>
<li>margin top and bottom 30px - it should be 30px under the bottom of the <code>header</code> (screenshot)</li>
<li>center horizontally</li>
</ul></li>
</ul></li>
<li>Filter section: 

<ul>
<li>tag <code>section</code></li>
<li>classname <code>filters</code></li>
<li>inside the <code>.container</code></li>
<li>color white</li>
<li>height: 70px</li>
<li>width: 100% of the container</li>
<li>border 1px #DDDDDD with radius 4px</li>
</ul></li>
<li>Button search:

<ul>
<li>tag <code>button</code></li>
<li>text <code>Search</code></li>
<li>font size: 18px</li>
<li>inside the section filters</li>
<li>background color #FF5A5F</li>
<li>text color #FFFFFF</li>
<li>height: 48px</li>
<li>width: 20% of the section filters</li>
<li>no borders</li>
<li>border radius: 4px</li>
<li>center vertically and at 30px of the right border</li>
<li>change opacity to 90% when the mouse is on the button</li>
</ul></li>
</ul>

<p>Requirements:</p>

<ul>
<li>You must use: <code>header</code>, <code>footer</code>, <code>section</code>, <code>button</code> tags</li>
<li>No inline style</li>
<li>You are not allowed to use the <code>img</code> tag</li>
<li>You are not allowed to use the <code>style</code> tag in the <code>head</code> tag</li>
<li>All images must be stored in the <code>images</code> folder</li>
<li>You must have 4 CSS files:

<ul>
<li><code>styles/4-common.css</code>: for the global style (<code>body</code> and <code>.container</code> styles)</li>
<li><code>styles/3-header.css</code>: for the header style</li>
<li><code>styles/3-footer.css</code>: for the footer style</li>
<li><code>styles/4-filters.css</code>: for the filters style</li>
</ul></li>
<li><code>4-index.html</code> <strong>won&rsquo;t be W3C valid</strong>, don&rsquo;t worry, it&rsquo;s temporary</li>
</ul>

<p><img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2021/12/3798a756663ec485f194f5c5e1b55b15326174f3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220711%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220711T152211Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=43fc5cf14da94f590b782923536ea8a929c59b4a2610c092a8fe97e61b3d557e" alt="" style="width: 100%" /></p>

  </div>
 <h3 class="panel-title">
      5. More filters
    </h3>
 <p>Write an HTML page that displays a header, footer and a filters box.</p>

<p>Layout: (based on <code>4-index.html</code>)</p>

<ul>
<li>Locations and Amenities filters:

<ul>
<li>tag: <code>div</code></li>
<li>classname: <code>locations</code> for location tag and <code>amenities</code> for the other</li>
<li>inside the section filters (same level as the <code>button</code> Search)</li>
<li>height: 100% of the section filters</li>
<li>width: 25% of the section filters</li>
<li>border right #DDDDDD 1px only for the first left filter</li>
<li>contains a title:

<ul>
<li>tag: <code>h3</code></li>
<li>font weight: 600<br></li>
<li>text <code>States</code> or <code>Amenities</code></li>
</ul></li>
<li>contains a subtitle:

<ul>
<li>tag: <code>h4</code></li>
<li>font weight: 400<br></li>
<li>font size: 14px</li>
<li>text with fake contents</li>
</ul></li>
</ul></li>
</ul>

<p>Requirements:</p>

<ul>
<li>You must use: <code>header</code>, <code>footer</code>, <code>section</code>, <code>button</code>, <code>h3</code>, <code>h4</code> tags</li>
<li>No inline style</li>
<li>You are not allowed to use the <code>img</code> tag</li>
<li>You are not allowed to use the <code>style</code> tag in the <code>head</code> tag</li>
<li>All images must be stored in the <code>images</code> folder</li>
<li>You must have 4 CSS files:

<ul>
<li><code>styles/4-common.css</code>: for the global style (<code>body</code> and <code>.container</code> styles)</li>
<li><code>styles/3-header.css</code>: for the header style</li>
<li><code>styles/3-footer.css</code>: for the footer style</li>
<li><code>styles/5-filters.css</code>: for the filters style</li>
</ul></li>
</ul>

<p><img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2021/12/66ddfafd5fd59f06be3d55ea96cc6ad11a7f1ca9.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220711%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220711T152211Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=dec2dedf07a00a8089b0cd4e805d9d82966c4a48c1d743f930d52505cae82bd1" alt="" style="width: 100%" /></p>

  </div>
 <h3 class="panel-title">
      6. It&#39;s (h)over
    </h3>
<p>Write an HTML page that displays a header, footer and a filters box with dropdown.</p>

<p>Layout: (based on <code>5-index.html</code>)</p>

<ul>
<li>Update Locations and Amenities filters to display a contextual dropdown when the mouse is on the filter <code>div</code>: 

<ul>
<li>tag <code>ul</code></li>
<li>classname <code>popover</code></li>
<li>text should be fake now</li>
<li>inside each <code>div</code></li>
<li>not displayed by default</li>
<li>color #FAFAFA</li>
<li>width same as the <code>div</code> filter</li>
<li>border #DDDDDD 1px with border radius 4px</li>
<li>no list display</li>
<li>Location filter has 2 levels of <code>ul</code>/<code>li</code>:

<ul>
<li>state -&gt; cities</li>
<li>state name must be display in a <code>h2</code> tag (font size 16px)</li>
</ul></li>
</ul></li>
</ul>

<p>Requirements:</p>

<ul>
<li>You must use: <code>header</code>, <code>footer</code>, <code>section</code>, <code>button</code>, <code>h3</code>, <code>h4</code>, <code>ul</code>, <code>li</code> tags</li>
<li>No inline style</li>
<li>You are not allowed to use the <code>img</code> tag</li>
<li>You are not allowed to use the <code>style</code> tag in the <code>head</code> tag</li>
<li>All images must be stored in the <code>images</code> folder</li>
<li>You must have 4 CSS files:

<ul>
<li><code>styles/4-common.css</code>: for the global style (<code>body</code> and <code>.container</code> styles)</li>
<li><code>styles/3-header.css</code>: for the header style</li>
<li><code>styles/3-footer.css</code>: for the footer style</li>
<li><code>styles/6-filters.css</code>: for the filters style</li>
</ul></li>
</ul>

<p><img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2021/12/36dd43123192ce96110b28c8a23ea9fbf851da0c.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220711%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220711T152211Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a1ba96cadaeb85a2184312d915ce8f828e682605e4db087d664dc28c9e18fdd5" alt="" style="width: 100%" />
<img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2021/12/9867494d8697023e5f50a90871003ac55e95eedb.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220711%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220711T152211Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b8f63fe5b1fac04796ec201e4a06b93f312522f310f16c77a8572fc22f4b1564" alt="" style="width: 100%" /></p>

  </div>
 <h3 class="panel-title">
      7. Display results
    </h3>
  <p>Write an HTML page that displays a header, footer, a filters box with dropdown and results.</p>

<p>Layout: (based on <code>6-index.html</code>)</p>

<ul>
<li>Add Places section:

<ul>
<li>tag: <code>section</code></li>
<li>classname: <code>places</code></li>
<li>same level as the filters section, inside <code>.container</code></li>
<li>contains a title:

<ul>
<li>tag: <code>h1</code></li>
<li>text: <code>Places</code></li>
<li>align in the top left</li>
<li>font size: 30px</li>
</ul></li>
<li>contains multiple &ldquo;Places&rdquo; as listing (horizontal or vertical) describe by:

<ul>
<li>tag: <code>article</code></li>
<li>width: 390px</li>
<li>padding and margin 20px</li>
<li>border #FF5A5F 1px with radius 4px</li>
<li>contains the place name:

<ul>
<li>tag: <code>h2</code></li>
<li>font size: 30px</li>
<li>center horizontally</li>
</ul></li>
</ul></li>
</ul></li>
</ul>

<p>Requirements:</p>

<ul>
<li>You must use: <code>header</code>, <code>footer</code>, <code>section</code>, <code>article</code>, <code>button</code>, <code>h1</code>, <code>h2</code>, <code>h3</code>, <code>h4</code>, <code>ul</code>, <code>li</code> tags</li>
<li>No inline style</li>
<li>You are not allowed to use the <code>img</code> tag</li>
<li>You are not allowed to use the <code>style</code> tag in the <code>head</code> tag</li>
<li>All images must be stored in the <code>images</code> folder</li>
<li>You must have 5 CSS files:

<ul>
<li><code>styles/4-common.css</code>: for the global style (i.e. <code>body</code> and <code>.container</code> styles)</li>
<li><code>styles/3-header.css</code>: for the header style</li>
<li><code>styles/3-footer.css</code>: for footer style</li>
<li><code>styles/6-filters.css</code>: for the filters style</li>
<li><code>styles/7-places.css</code>: for the places style</li>
</ul></li>
</ul>

<p><img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2021/12/cb69b56a70528eeb3c52b4f0154a64b3f68d4fb6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220711%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220711T152211Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7a034ee36a34dddeb3ed30f57e20cc5f978741a4c81be3b3be7a4de14d988b23" alt="" style="width: 100%" /></p>

  </div>
  <h3 class="panel-title">
      8. More details
    </h3>
 <p>Write an HTML page that displays a header, a footer, a filter box (dropdown list) and the result of the search.</p>

<p>Layout: (based on <code>7-index.html</code>)</p>

<p>Add more information to a Place <code>article</code>:</p>

<ul>
<li>Price by night:

<ul>
<li>tag: <code>div</code></li>
<li>classname: <code>price_by_night</code></li>
<li>same level as the place name</li>
<li>font color: #FF5A5F</li>
<li>border: #FF5A5F 4px rounded</li>
<li>min width: 60px</li>
<li>height: 60px</li>
<li>font size: 30px</li>
<li>align: the top right (with space)</li>
</ul></li>
<li>Information section:

<ul>
<li>tag: <code>div</code></li>
<li>classname: <code>information</code></li>
<li>height: 80px</li>
<li>border: top and bottom #DDDDDD 1px</li>
<li>contains (align vertically):

<ul>
<li>Number of guests:

<ul>
<li>tag: <code>div</code></li>
<li>classname: <code>max_guest</code></li>
<li>width: 100px</li>
<li>fake text</li>
<li><a href="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/icon_group.png" title="icon" target="_blank">icon</a></li>
</ul></li>
<li>Number of bedrooms:

<ul>
<li>tag: <code>div</code></li>
<li>classname: <code>number_rooms</code></li>
<li>width: 100px</li>
<li>fake text</li>
<li><a href="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/icon_bed.png" title="icon" target="_blank">icon</a></li>
</ul></li>
<li>Number of bathrooms:

<ul>
<li>tag: <code>div</code></li>
<li>classname: <code>number_bathrooms</code></li>
<li>width: 100px</li>
<li>fake text</li>
<li><a href="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/icon_bath.png" title="icon" target="_blank">icon</a></li>
</ul></li>
</ul></li>
</ul></li>
<li>User section:

<ul>
<li>tag: <code>div</code></li>
<li>classname: <code>user</code></li>
<li>text <code>Owner: &lt;fake text&gt;</code></li>
<li><code>Owner</code> text should be in bold</li>
</ul></li>
<li>Description section:

<ul>
<li>tag: <code>div</code></li>
<li>classname: <code>description</code></li>
</ul></li>
</ul>

<p>Requirements:</p>

<ul>
<li>You must use: <code>header</code>, <code>footer</code>, <code>section</code>, <code>article</code>, <code>button</code>, <code>h1</code>, <code>h2</code>, <code>h3</code>, <code>h4</code>, <code>ul</code>, <code>li</code> tags</li>
<li>No inline style</li>
<li>You are not allowed to use the <code>img</code> tag</li>
<li>You are not allowed to use the <code>style</code> tag in the <code>head</code> tag</li>
<li>All images must be stored in the <code>images</code> folder</li>
<li>You must have 5 CSS files:

<ul>
<li><code>styles/4-common.css</code>: for the global style (i.e. <code>body</code> and <code>.container</code> styles)</li>
<li><code>styles/3-header.css</code>: for the header style</li>
<li><code>styles/3-footer.css</code>: for the footer style</li>
<li><code>styles/6-filters.css</code>: for the filters style</li>
<li><code>styles/8-places.css</code>: for the places style</li>
</ul></li>
</ul>

<p><img src="https://holbertonintranet.s3.amazonaws.com/uploads/medias/2021/12/bd1088cbd5c50fd80b8f2027b88fc0b80b8c4d96.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220711%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220711T152211Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e593fa92a3f64d088ad5d971346bee3ee915c4b40d739ec80453e702341a01e0" alt="" style="width: 100%" /></p>

  </div>
<h4 class="modal-title">Markdown Guide</h4>
        </div>
        <div class="modal-body">
            <h4>Emphasis</h4>
<pre>**<strong>bold</strong>**
*<em>italics</em>*
~~<strike>strikethrough</strike>~~</pre>
<h4>Headers</h4>
<pre># Big header
## Medium header
### Small header
#### Tiny header</pre>
<h4>Lists</h4>
<pre>* Generic list item
* Generic list item
* Generic list item

1. Numbered list item
2. Numbered list item
3. Numbered list item</pre>
<h4>Links</h4>
<pre>[Text to display](http://www.example.com)</pre>
<h4>Quotes</h4>
<pre>> This is a quote.
> It can span multiple lines!</pre>
<h4>Images</h4>
<p>CSS style available: <code>width, height, opacity</code></p>
<pre>![](http://www.example.com/image.jpg)
![](http://www.example.com/image.jpg | width: 200px)
![](http://www.example.com/image.jpg | height: 124px | width: 80px | opacity: 0.6)
</pre>
<h4>Tables</h4>
<pre>| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John     | Doe      | Male     |
| Mary     | Smith    | Female   |

<em>Or without aligning the columns...</em>

| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John | Doe | Male |
| Mary | Smith | Female |
</pre>
<h4>Displaying code</h4>
<pre>`var example = "hello!";`

<em>Or spanning multiple lines...</em>

```
var example = "hello!";
alert(example);
```</pre>
        </div>
    </div>
  </div>
</div>


<script>
	(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
	(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
	m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
	})(window,document,'script','//www.google-analytics.com/analytics.js','ga');

		ga('create',
		'UA-67152800-6',
		'auto', {
			userId: '4520'
		}
		);

	ga('send', 'pageview');

	$(document).ready(function() {
		ga(function(tracker) {
		var clientId = tracker.get('clientId');
		$('.ga-client-id').val(clientId);
		});
	});	
</script>




