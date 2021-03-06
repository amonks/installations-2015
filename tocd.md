<h1 id="andrewmonksinstallationwork2015">Andrew Monks&#8217; Installation Work // 2015</h1>

<h2 id="contents">Contents</h2>

<ul>
<li><a href="#stereo">Stereo</a>
<ul><li><a href="#initial-headmounteddisplaybased-ideas">Initial Head-Mounted-Display-Based Ideas</a>
<ul><li><a href="#water">Water</a></li></ul></li>
<li><a href="#stereoscopic-splitting">Stereoscopic Splitting</a></li></ul></li>
<li><a href="#new-major-theme-surveillance">New Major Theme: Surveillance</a>
<ul><li><a href="#literal-surveillance-room-proposal">Literal Surveillance 2-room Proposal</a>
<ul><li><a href="#materials">Materials</a></li></ul></li></ul></li>
<li><a href="#sellforg">Sellf.org</a>
<ul><li><a href="#private-statement">Private Statement</a></li>
<li><a href="#installation-sellforg-promotional-seminar">Installation: Sellf.org Promotional Seminar</a>
<ul><li><a href="#first-round">First Round</a></li>
<li><a href="#next-round">Next Round</a></li>
<li><a href="#materials">Materials</a></li>
<li><a href="#publicfacing-statement">Public-Facing Statement</a>
<ul><li><a href="#for-sellers">For Sellers:</a></li>
<li><a href="#for-buyers">For buyers:</a></li></ul></li></ul></li>
<li><a href="#references">References</a>
<ul><li><a href="#tactical-media-angle">Tactical media angle</a></li>
<li><a href="#data-collection-angle">Data collection angle</a></li>
<li><a href="#data-liberation-angle">Data liberation angle</a></li>
<li><a href="#misc">misc</a></li></ul></li>
<li><a href="#thoughts">thoughts</a>
<ul><li><a href="#what-happens-to-data-collected-online-anyway">What happens to data collected online anyway?</a></li>
<li><a href="#im-not-sure-who-to-address-on-the-buy-page">I&#8217;m not sure who to address on the <code>buy</code> page.</a>
<ul><li><a href="#option-">option 1</a></li>
<li><a href="#option-">option 2</a></li></ul></li></ul></li></ul></li>
</ul>

<!-- end toc -->

<h2 id="stereo">Stereo</h2>

<p>Head-mounted displays like the <a href="https://www.oculus.com/">Oculus Rift</a> are trending super hard right now, and they were the first direction I explored this year. I made a <a href="https://www.google.com/get/cardboard/">Google Cardboard</a> and set to work.</p>

<h3 id="initialhead-mounted-display-basedideas">Initial Head-Mounted-Display-Based Ideas</h3>

<p>I&#8217;m interested in the unique power of stereoscopic head-mounted displays to completely replace what we perceive, especially to create visual input which would be impossible otherwise. For example, what would it be like to <a href="http://cl.ly/ZiLS">see the world upside-down </a>.</p>

<p>This almost sounds obvious, but in time, I realized that the most fundamentally new experience that stereoscopic displays can provide is showing different images to each eye. In the real world, no matter what kind of wonderfully transformative things you see, you&#8217;ll always see them through two cameras facing the same direction from a few inches apart. But what if one of your eyes was somewhere else?</p>

<h4 id="water">Water</h4>

<p><img id="water" src="water.png" alt="water " title="" /></p>

<p>In this <a href="http://cl.ly/ZhtF">installation </a>, the viewer would wear a head-mounted display with a front-facing camera. Software would detect the walls of the room in each frame of that camera feed, and create two altered versions: in each, the walls would be replaced by video of a different body of water. Each altered image would then be displayed to one of the viewer&#8217;s eyes.</p>

<h3 id="stereoscopicsplitting">Stereoscopic Splitting</h3>

<p><img id="stereovisiontests" src="stereo.png" alt="stereo vision tests" title="" /></p>

<p>In order to test this uncharted territory as thoroughly as possible, I decided to make a configurable tool for showing different animation to different eyes. Starting as simply as alternating solid black and white light, and moving through objects rotating in opposite directions and realtime video filtered in different colors.</p>

<p><img id="wife.cool" src="wife.cool.png" alt="wife.cool" title="" /></p>

<p>I quickly outgrew the <a href="http://ss.cx/~ajm/s/config.html">first tool</a> I made for these tests, and I&#8217;ve been adapting and growing it into a useful product in its own right: a fully-customizable framework for running visual code in the browser, with support for live-coding and collaboration. That project is currently undergoing <a href="http://github.com/amonks/vjjs">rapid development</a>.</p>

<p>Clearly this wasn&#8217;t going to be presentable any time soon, so I needed a new project.</p>

<h2 id="newmajortheme:surveillance">New Major Theme: Surveillance</h2>

<h3 id="literalsurveillance2-roomproposal">Literal Surveillance 2-room Proposal</h3>

<p>For my installation in the two rooms on 13, I would like to create a surveillance center  in the larger room using live camera footage and data from the smaller room.</p>

<p>I&#8217;ll use several raspberry pi with cameras, each mounted directly on the walls or ceiling, with wires exposed. Using another raspberry pi with an attached kinect, I&#8217;ll also take a depth camera feed, and with another raspberry pi with a large wifi antenna I&#8217;ll run a <code>tcpdump</code>. all of these raspberry pi will connect via Ethernet to a wireless router, and will send the information to a matching router in the larger room. This router will connect to two laptops  in opposite corners of the floor of the room, placed as if casually in use. The laptops will each be placed next to a projector, also on the floor  The laptops will be projecting and displaying a different combination of feeds from the other room.</p>

<h4 id="materials">Materials</h4>

<ul>
<li>x 4 raspberry pi</li>
<li>4 picam</li>
<li>6 Ethernet cables</li>
<li>x large antenna</li>
<li>x kinect</li>
<li>2 routers</li>
<li>2 power strips</li>
<li>2 projectors</li>
</ul>

<h2 id="sellf.org">Sellf.org</h2>

<p><a href="http://sellf.org">sellf.org</a></p>

<p><img id="sellf.orgwebsite" src="sellf-website.png" alt="sellf.org website" title="" /></p>

<h3 id="privatestatement">Private Statement</h3>

<p><code>sellf.org</code> is a company that explores the ramifications of the commodification of personal data, by operating a free for-sale-by-owner data market. The premise: &#8220;Who&#8217;s better equipped to sell your data than you are?&#8221;</p>

<p>By revealing the market value of consumer data, <code>sellf.org</code> creates and investigates a world where consumerism can be self supporting. Can you make a living by publishing how you spend that living?</p>

<p>More importantly, <code>sellf.org</code> seeks to attack the current form of the relationship between Big Data Collection and the public.</p>

<h3 id="installation:sellf.orgpromotionalseminar">Installation: Sellf.org Promotional Seminar</h3>

<p>http://sellf.org tactically interjects itself into the online space to ask people critical questions about surveillance and create much-needed discourse. The <em>Sellf.org Promotional Seminar</em> brings that same interjection to the physical space.</p>

<p>In the installation, one or two representatives from Sellf.org set up a display in a public space, and give a presentation informing the public about data surveillance and soliciting them to start harvesting and selling their own data.</p>

<p>By engaging the public through a commercial, rather than an art context, the company seeks to surface the conversation about personal commoditization.</p>

<p>It forces people to consider questions personally that an art-framed piece couldn&#8217;t (&#8216;what am I getting paid for?&#8217; &#8216;What will happen if I sell this?&#8217; &#8216;How much will I sell my data for?&#8217; &#8216;What is my privacy worth?&#8217;) by making the public examine the potential repercussions of a conscious contract rather than a passive one.</p>

<p>By using a &#8216;tip-of-the-iceberg&#8217; approach, and giving people enough information so that they might explore the website on their own, the seminar adds to the mythology around sellf.org, making it seem perhaps larger.</p>

<h4 id="firstround">First Round</h4>

<p>I tried a trial round of this installation on March 2, 2015.</p>

<p><img id="pictureofinitialpresentation" src="sellf-1304.jpg" alt="picture of initial presentation " title="" /></p>

<p><iframe src="https://player.vimeo.com/video/123594829" width="500" height="375" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe></p>

<h4 id="nextround">Next Round</h4>

<p><img id="modelofsecondroundofinstallation" src="sellf-sketchup.png" alt="model of second round of installation " title="" /></p>

<p>I&#8217;ll do another round of the installation on May 2, 2015 at <a href="http://wunder.xyz">Wunder </a></p>

<h4 id="materials">Materials</h4>

<ul>
<li>assistant</li>
<li>1 potted plant</li>
<li>2 folding tables</li>
<li>1 laptop with PowerPoint</li>
<li>1 short-throw projector, with floor-mount</li>
<li>1 folding projector screen (on tripod)</li>
<li>1 cart of catered coffee</li>
<li>2 binders</li>
<li>Many sign-up forms[?] for buyers</li>
<li>Many contact forms for sellers</li>
<li>Many take-away info pamphlets</li>
<li>Many sellf.org business cards</li>
<li>Several sellf.org branded pens[?]</li>
</ul>

<h4 id="public-facingstatement">Public-Facing Statement</h4>

<p>The following text is appropriate for display in the gallery alongside the installation.</p>

<h5 id="forsellers:">For Sellers:</h5>

<blockquote>
  <p>There&#8217;s an enormous market for data about you—your location, your purchasing habits, your interests. Many of the websites and services you use, the stores you visit, and the devices you carry are constantly scrambling to collect this data and sell it to the highest bidder.</p>

<p>But nobody has more access to valuable data about you than you do.</p>

<p>With Sellf, you can create a data product far more valuable than what anyone else could collect. Companies like Facebook and Google put millions of dollars into correlating datasets together, but you can sell all of your data as a single package. Google and Facebook can&#8217;t compete.</p>
</blockquote>

<h5 id="forbuyers:">For buyers:</h5>

<blockquote>
  <p>Data mining allows us to advertise more cheaply and effectively than ever thought possible. Don&#8217;t just target demographics, target conditions: <code>just stopped at atm</code>, <code>good mood</code>, <code>drunk</code>. Or, even, <code>recently looked at a competitor's product</code>, <code>looked at shoes online earlier but didn't buy</code>, <code>spent 20 minutes in the kitchen section at Macy's, then left empty handed</code>, or <code>didn't eat enough protein with breakfast</code></p>

<p>By collecting all of a consumer&#8217;s data from every source with consent, <code>sellf.org</code> offers a revolutionary data resolution, enabling you to sell many times more for every advertising dollar.</p>
</blockquote>

<h3 id="references">References</h3>

<h4 id="tacticalmediaangle">Tactical media angle</h4>

<ul>
<li>critical art ensemble, GenTerra, BioCom</li>
<li>steve kurtz</li>
<li>http://biogenfutur.es/</li>
</ul>

<h4 id="datacollectionangle">Data collection angle</h4>

<ul>
<li>http://en.wikipedia.org/wiki/Behavioral_retargeting</li>
<li>https://www.adroll.com/getting-started/retargeting</li>
<li>https://www.adroll.com/</li>
<li>https://www.quantcast.com/</li>
<li>http://www.marketo.com/</li>
<li>ghostery</li>
<li>list of data collection companies: https://www.ghosteryenterprise.com/company-database/</li>
<li>google, facebook, amazon, &#8230;</li>
</ul>

<h4 id="dataliberationangle">Data liberation angle</h4>

<ul>
<li>http://en.wikipedia.org/wiki/Google_Data_Liberation_Front</li>
<li>https://www.facebook.com/help/212802592074644</li>
<li>https://www.moves-app.com/faq iphone app collecting location data</li>
</ul>

<h4 id="misc">misc</h4>

<ul>
<li>quantify your worth on twitter // third party account resale value calculator</li>
<li>migumi igorashi: selling vagina scan</li>
<li><p>million dollar homepage</p></li>
<li><p>http://dismagazine.com/issues/73298/sara-m-watson-metaphors-of-big-data/</p></li>
<li>http://www.katecrawford.net/</li>
<li><p>http://lauren-mccarthy.com/</p></li>
<li><p>http://harpers.org/archive/2015/01/come-with-us-if-you-want-to-live/</p></li>
<li>http://en.wikipedia.org/wiki/The_Californian_Ideology</li>
<li>http://www.e-flux.com/journal/return-of-the-gothic-digital-anxiety-in-the-domestic-sphere/</li>
<li>http://thenewinquiry.com/essays/the-anxieties-of-big-data/</li>
<li>http://www.technologyreview.com/news/517346/the-paradox-of-wearable-technologies/</li>
<li>https://modelviewculture.com/pieces/tech-workers-political-speech-and-economic-threat</li>
</ul>

<h3 id="thoughts">thoughts</h3>

<h4 id="whathappenstodatacollectedonlineanyway">What happens to data collected online anyway?</h4>

<p><img id="retargeting" src="sellf-retargeting.jpg" alt="retargeting " title="" /></p>

<p>I honestly expected to be able to go online and find some page where I could buy a huge dataset from facebook or something. I haven&#8217;t been able to find anything of the kind. Data collectors monetize their data through ad platforms.</p>

<h4 id="imnotsurewhotoaddressonthebuypage.">I&#8217;m not sure who to address on the <code>buy</code> page.</h4>

<h5 id="option1">option 1</h5>

<p>I could position sellf.org as a traditional marketing data sales company, selling huge datasets to corporate interests.</p>

<p>This approach most directly engages with the current personal data market. On the other hand, as far as I&#8217;ve turned up, most of the huge data collectors (amazon, google, facebook) sell data indirectly via an advertising platform rather than as a dataset.</p>

<p>A person has many datagrams which are (can be?) sold together. A buyer makes an order like &#8220;the cheapest hundred people who spend more than 100k per year and offer location and purchase data with >90% completeness&#8221;, and it&#8217;s filled based on how sellers set their prices.</p>

<h5 id="option2">option 2</h5>

<p>On the other hand, it would be interesting to create a data market targeted more towards artists + hobbyists rather than marketing departments. Allowing people to submit arbitrary types/sets of data will help the ecosystem grow autonomously.</p>
