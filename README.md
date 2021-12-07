# An example of meta tags

This is just a basic file with examples and descriptions of the different meta tags you can use.

This example does not include every meta tag available - there are some wild ones out there! This repo gives you an example of the basic (and not-so-basic) meta tags that you can use to help make your projects shine - both on your website, and on social media!

![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Social debuggers

Facebook - https://developers.facebook.com/tools/debug/
LinkedIn - https://www.linkedin.com/post-inspector/
Twitter - https://cards-dev.twitter.com/validator 

## Tools from the slides

Lighthouse - https://developers.google.com/web/tools/lighthouse 
Accessibility DOM - Go into Devtools on Chrome, Settings, Experiments, tick the box by ‘Enable full accessibility tree view in the Elements panel’
Spectrum extension - https://chrome.google.com/webstore/detail/spectrum/ofclemegkcmilinpcimpjkfhjfgmhieb?hl=en 
Web disability simulator extension - https://chrome.google.com/webstore/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla?hl=en 
WAVE - https://wave.webaim.org/ 
WebAIM colour contrast checker - https://webaim.org/resources/contrastchecker/ 

## References from the information on the slides

https://usability.yale.edu/web-accessibility/articles/readability
https://css-tricks.com/essential-meta-tags-social-media/ 
https://axesslab.com/disabled-buttons-suck/
https://www.youtube.com/watch?v=V1yoOLhx_qA
https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion
https://web.dev/prefers-reduced-motion/
https://css-tricks.com/almanac/selectors/a/after-and-before/
https://codersblock.com/blog/diving-into-the-before-and-after-pseudo-elements/
https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements
https://dev.to/stephencweiss/hover-vs-focus-pgg
https://wunder.io/wunderpedia/accessibility/accessible-uis/hover-focus-active/
https://medium.com/design-code-repository/a-vs-button-b859547cae4d
https://medium.com/@zacdicko/size-matters-accessibility-and-touch-targets-56e942adc0cc
https://www.w3.org/TR/wai-aria/#aria-label
https://a11y-101.com/design/button-vs-link
https://www.digitala11y.com/links-vs-buttons-a-perennial-problem/
https://www.youtube.com/watch?v=_GfelgpDLwI
https://storage.googleapis.com/a11y-io/moving-buttons/html/index.html
https://uxdesign.cc/is-it-ok-to-grey-out-disabled-buttons-8afa74a0fae
https://www.deque.com/blog/accessible-aria-buttons/
https://css-tricks.com/making-disabled-buttons-more-inclusive/
https://sean-elliott.medium.com/a11y-tips-disabled-buttons-and-colour-contrast-f8824d5e9610  

I've included a more extensive list of meta tags. While the more important ones are in the index.html file, if you'd like to dive into meta tags more, this list is below. There are also links to further references and resources at the bottom.

This list has been copied from [http://code.lancepollard.com/complete-list-of-html-meta-tags/](http://code.lancepollard.com/complete-list-of-html-meta-tags/)

## Basic HTML Meta Tags

``` html
<meta name="keywords" content="your, tags"/>
<meta name="description" content="150 words"/>
<meta name="subject" content="your website's subject">
<meta name="copyright"content="company name">
<meta name="language" content="ES">
<meta name="robots" content="index,follow" />
<meta name="revised" content="Sunday, July 18th, 2010, 5:15 pm" />
<meta name="abstract" content="">
<meta name="topic" content="">
<meta name="summary" content="">
<meta name="Classification" content="Business">
<meta name="author" content="name, email@hotmail.com">
<meta name="designer" content="designer's name, or designers names">
<meta name="copyright" content="copyright owner's name">
<meta name="reply-to" content="email@hotmail.com">
<meta name="owner" content="">
<meta name="url" content="http://www.websiteaddress.com">
<meta name="identifier-URL" content="http://www.websiteaddress.com">
<meta name="directory" content="submission">
<meta name="category" content="">
<meta name="coverage" content="Worldwide">
<meta name="distribution" content="Global">
<meta name="rating" content="General">
<meta name="revisit-after" content="7 days">
<meta http-equiv="Expires" content="0">
<meta http-equiv="Pragma" content="no-cache">
<meta http-equiv="Cache-Control" content="no-cache">
```

## OpenGraph Meta Tags

``` html
<meta name="og:title" content="The Rock"/>
<meta name="og:type" content="movie"/>
<meta name="og:url" content="http://www.imdb.com/title/tt0117500/"/>
<meta name="og:image" content="http://ia.media-imdb.com/rock.jpg"/>
<meta name="og:site_name" content="IMDb"/>
<meta name="og:description" content="A group of U.S. Marines, under command of..."/>

<meta name="fb:page_id" content="43929265776" />

<meta name="og:email" content="me@example.com"/>
<meta name="og:phone_number" content="650-123-4567"/>
<meta name="og:fax_number" content="+1-415-123-4567"/>

<meta name="og:latitude" content="37.416343"/>
<meta name="og:longitude" content="-122.153013"/>
<meta name="og:street-address" content="1601 S California Ave"/>
<meta name="og:locality" content="Palo Alto"/>
<meta name="og:region" content="CA"/>
<meta name="og:postal-code" content="94304"/>
<meta name="og:country-name" content="USA"/>

<meta property="og:type" content="game.achievement"/>
<meta property="og:points" content="POINTS_FOR_ACHIEVEMENT"/>

<meta property="og:video" content="http://example.com/awesome.swf" />
<meta property="og:video:height" content="640" />
<meta property="og:video:width" content="385" />
<meta property="og:video:type" content="application/x-shockwave-flash" />
<meta property="og:video" content="http://example.com/html5.mp4" />
<meta property="og:video:type" content="video/mp4" />
<meta property="og:video" content="http://example.com/fallback.vid" />
<meta property="og:video:type" content="text/html" />

<meta property="og:audio" content="http://example.com/amazing.mp3" />
<meta property="og:audio:title" content="Amazing Song" />
<meta property="og:audio:artist" content="Amazing Band" />
<meta property="og:audio:album" content="Amazing Album" />
<meta property="og:audio:type" content="application/mp3" />
```

## Create Custom Meta Tags

Use custom meta tags to store data that you need in javascript, instead of hard-coding that data into your javascript.  I store my Google Analytics code in meta tags.  Here's some examples:

``` html
<meta name="google-analytics" content="1-AHFKALJ"/>
<meta name="disqus" content="abcdefg"/>
<meta name="uservoice" content="asdfasdf"/>
<meta name="mixpanel" content="asdfasdf"/>
```

## Company/Service Meta Tags

### ClaimID

``` html
<meta name="microid" content="mailto+http:sha1:e6058ed7fca4a1921cq91d7f1f3b8736cd3cc1g7" />
```

### Apple Meta Tags

``` html
<meta name="apple-mobile-web-app-capable" content="yes">
<meta content="yes" name="apple-touch-fullscreen" />
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta name="format-detection" content="telephone=no">
<meta name="viewport" content="width = 320, initial-scale = 2.3, user-scalable = no">
```

### Internet Explorer Meta Tags

``` html
<meta http-equiv="Page-Enter" content="RevealTrans(Duration=2.0,Transition=2)" />
<meta http-equiv="Page-Exit" content="RevealTrans(Duration=3.0,Transition=12)" />
<meta name="mssmarttagspreventparsing" content="true">
<meta http-equiv="X-UA-Compatible" content="chrome=1">
<meta name="msapplication-starturl" content="http://blog.reybango.com/about/"/>
<meta name="msapplication-window" content="width=800;height=600"/>
<meta name="msapplication-navbutton-color" content="red"/>
<meta name="application-name" content="Rey Bango Front-end Developer"/>
<meta name="msapplication-tooltip" content="Launch Rey Bango's Blog"/>
<meta name="msapplication-task" content="name=About;action-uri=/about/;icon-uri=/images/about.ico" />
<meta name="msapplication-task" content="name=The Big List;action-uri=/the-big-list-of-javascript-css-and-html-development-tools-libraries-projects-and-books/;icon-uri=/images/list_links.ico" />
<meta name="msapplication-task" content="name=jQuery Posts;action-uri=/category/jquery/;icon-uri=/images/jquery.ico" />
<meta name="msapplication-task" content="name=Start Developing;action-uri=/category/javascript/;icon-uri=/images/script.ico" />
<link rel="shortcut icon" href="/images/favicon.ico" />
```

### TweetMeme Meta Tags

``` html
<meta name="tweetmeme-title" content="Retweet Button Explained" />
```

### Blog Catalog Meta Tags

``` html
<meta name="blogcatalog" />
```

### Rails Meta Tags

``` html
<meta name="csrf-param" content="authenticity_token"/>
<meta name="csrf-token" content="/bZVwvomkAnwAI1Qd37lFeewvpOIiackk9121fFwWwc="/>
```

### Apple Tags

``` html
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta name="format-detection" content="telephone=no">
<meta name= "viewport" content = "width = 320, initial-scale = 2.3, user-scalable = no">
<meta name= "viewport" content = "width = device-width">
<meta name = "viewport" content = "initial-scale = 1.0">
<meta name = "viewport" content = "initial-scale = 2.3, user-scalable = no">
<link rel="apple-touch-icon" href="touch-icon-iphone.png" />
<link rel="apple-touch-icon" sizes="72x72" href="touch-icon-ipad.png" />
<link rel="apple-touch-icon" sizes="114x114" href="touch-icon-iphone4.png" />
<link rel="apple-touch-startup-image" href="/startup.png">

<link rel="apple-touch-icon" type="image/png" href="/apple-touch-icon.png" />
```

## HTML Link Tags

``` html
<link rel="alternate" type="application/rss+xml" title="RSS" href="http://feeds.feedburner.com/martini" />
<link rel="shortcut icon" type="image/ico" href="/favicon.ico" />
<link rel="fluid-icon" type="image/png" href="/fluid-icon.png" />
<link rel="me" type="text/html" href="http://google.com/profiles/thenextweb"/>
<link rel='shortlink' href='http://blog.unto.net/?p=353' />
<link rel='archives' title='May 2003' href='http://blog.unto.net/2003/05/' />
<link rel='index' title='DeWitt Clinton' href='http://blog.unto.net/' />
<link rel='start' title='Pattern Recognition 1' href='http://blog.unto.net/photos/pattern_recognition_1_about/' />
<link rel='prev' title='OpenSearch and OpenID?  A sure way to get my attention.' href='http://blog.unto.net/opensearch/opensearch-and-openid-a-sure-way-to-get-my-attention/' />
<link rel='next' title='Not blog' href='http://blog.unto.net/meta/not-blog/' />
<link rel="search" href="/search.xml" type="application/opensearchdescription+xml" title="Viatropos" />

<link rel="self" type="application/atom+xml" href="http://www.syfyportal.com/atomFeed.php?page=3"/>
<link rel="first" href="http://www.syfyportal.com/atomFeed.php"/>
<link rel="next" href="http://www.syfyportal.com/atomFeed.php?page=4"/>
<link rel="previous" href="http://www.syfyportal.com/atomFeed.php?page=2"/>
<link rel="last" href="http://www.syfyportal.com/atomFeed.php?page=147"/>

<link rel='shortlink' href='http://smallbiztrends.com/?p=43625' />
<link rel="canonical" href="http://smallbiztrends.com/2010/06/9-things-to-do-before-entering-social-media.html" />
<link rel="EditURI" type="application/rsd+xml" title="RSD" href="http://smallbiztrends.com/xmlrpc.php?rsd" />
<link rel="pingback" href="http://smallbiztrends.com/xmlrpc.php" />
<link media="only screen and (max-device-width: 480px)" href="http://wordpress.org/style/iphone.css" type="text/css" rel="stylesheet" />
```

## Other Resources

- [Dublic Core Meta Tags](http://www.seoconsultants.com/meta-tags/dublin/)
- [Apple Meta Tags](http://developer.apple.com/safari/library/documentation/appleapplications/reference/safarihtmlref/articles/metatags.html)
- [OpenGraph Meta Tags](http://opengraphprotocol.org/)
- [Link Tag Meaning](http://intertwingly.net/wiki/pie/LinkTagMeaning)
- [Google Chrome HTML5 Tags](http://www.html5rocks.com/)
- [Set the viewport](https://web.dev/responsive-web-design-basics/#set-the-viewport)
- [nositelinkssearchbox](https://www.seroundtable.com/google-nositelinkssearchbox-19348.html)
- [Google docs](https://developers.google.com/search/docs/advanced/crawling/special-tags)
- [Rating tag](https://www.metatags.org/all-meta-tags-overview/meta-name-rating/#:~:text=If%20you%20wish%20to%20rate,will%20get%20banned%20for%20life)
