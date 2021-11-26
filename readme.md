# Search Engine Optimization (SEO) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A helpful checklist / collection of Search Engine Optimization (SEO) tips and techniques.

## Contents

- [URL](#url)
- [Accessibility](#accessibility)
- [Meta Information](#meta-information)
- [Keywords](#keywords)
- [Content](#content)
- [Images](#images)
- [Videos](#videos)
- [Links](#links)
- [Mobile](#mobile)
- [Sitemap](#sitemap)
- [Social Media](#social-media)

## URL

- Descriptive URLs: Use a descriptive page url, which should reflect your targeted keyword.
- [File extension](https://www.youtube.com/watch?v=dSG6C33GwsE) - Do not strip out the file extension on URLs.
- [HTTPS](https://webmasters.googleblog.com/2014/08/https-as-ranking-signal.html) - Security is a top priority for Google.
- [Hyphens](https://www.youtube.com/watch?v=AQcSFsQyct8) - Split words using hyphens.
- [Localisation](https://support.google.com/webmasters/answer/62399) - Choose a country-specific domain, for better local search results.
- [Subdomain or subfolder](https://www.youtube.com/watch?v=_MswMYk05tk) - Subdomains are seen as separate domains.
- [URL builder](https://support.google.com/analytics/answer/1033867) - Use this tool to add custom campaign parameters to your URLs.

## Accessibility

- 403: Provide a 403 - Access denied page.
- [Custom Search](https://developers.google.com/structured-data/slsb-overview) - With Google Sitelink search box, people can reach your content more quickly.
- Layout: Use `divs` instead of `tables` for layout. Using `tables` is not semantically correct.
- Moving a website: Redirect all your links to the new location via `.htaccess`.
- [Pagination](https://support.google.com/webmasters/answer/1663744) - Implement the `rel="next"` and `rel="prev"` attributes to links.
- [Performance](https://developers.google.com/webmasters/mobile-sites/mobile-seo/common-mistakes/slow-mobile-pages) - Performance and loading time is important.
- Redirects: Avoid redirects if possible. Use 301 redirect instead of 302.
- [RichSnippets](https://schema.org/) - Markup your code with rich snippets, they show up on the search results page.
- [Robots](https://en.wikipedia.org/wiki/Robots_exclusion_standard) - Block pages which should not be indexed via the `robots.txt` file or
  `<meta name="robots" content="">`.
- Validation: Write valid code ([HTML Validator](https://validator.w3.org/) [CSS Validator](https://jigsaw.w3.org/css-validator/)).
- [WAI-Aria](https://www.w3.org/TR/wai-aria/) - Use WAI-Aria tags to help machines understand your code.

## Meta Information

- [Description](https://www.youtube.com/watch?v=W4gr88oHb-k) - Each page should have a unique description (max. 160 characters)
  `<meta name="description" content="">`.
- Title: Each page should have a unique speaking title (60 - 100 characters) `<title>Website Title</title>`.

## Keywords

- Content: Keyword should appear in ~3% of article length.
- Heading: Keyword should appear in headings.
- [Meta Tag](https://www.youtube.com/watch?v=jK7IPbnmvVU) - You can ommit the `<meta name="keywords" content="">`,
  search engines do not use this meta tag.
- Research: Rank for keywords with high traffic and less competition.
- Single: Every page should have a single unique targeted keyword.
- Title: Keyword should appear in page title.
- [URL](https://www.youtube.com/watch?v=rAWFv43qubI) - Keyword should appear in URL name.

## Content

- Content: Content matters the most in SEO.
- Flash: Avoid Flash content and Flash pages. They are not accessible on mobile phones and will be ranked lower.
- Freshness: New content is important. Updating pages or posting regularly is recommended.
- Headings: Clear structure `H1` -`H6` max. 70 characters long.
- Length: Article should be at least 300 words.
- Strong: Use `strong` tag to highlight your targeted keyword.
- [Uniqueness](https://www.youtube.com/watch?v=mQZY7EmjbMA) - Do not provide duplicated content, use unique content types.

## Images

- [Alt tag](https://support.google.com/webmasters/answer/114016) - Add an alt-tag this a description of the image (60 - 70 characters).
- Dimensions: Add the `width=""` and `height=""` attributes to the image.
- [File name](https://www.youtube.com/watch?v=h2SWuUobbr0) - Use a short descriptive name.
- [Optimization](https://imageoptim.com/) - Optimize images by removing some meta information.
- [Responsive Images](https://www.w3.org/TR/html-picture-element/) - Serve the most optimized image corresponding to the window size.
- Size: keep the filesize as low as possible.

## Videos

- Controls: Add controls to playback and control your video.
- Embed: Allow others to embed your videos.
- Transcriptions: Use transcriptions for indexing, usability & content.
- [Unplayable content](https://developers.google.com/webmasters/mobile-sites/mobile-seo/common-mistakes/unplayable-content) - Avoid unplayable video content. Use HTML5 `<video>` tag instead of Flash.

## Links

- Backlinks: Only add external links if you got a backlink to your site.
- Internal links: Add ~3 internal links to your content.
- [Languages](https://moz.com/learn/seo/hreflang-tag) - The hreflang tag tells Google which language you are using on a specific page, so the search engine can serve that result to users searching in that language
  `<link rel="alternate" href="example.com/fr/" hreflang="fr-fr" />`.
- Naming: Use a descriptive link name: “Click here” or “Read more” are bad link text. Better “Read more about SEO and Web Accessibility”.
- [nofollow](https://support.google.com/webmasters/answer/96569) - Add `rel="nofollow"` attribute to external links only to prevent spam and bad links.
- Title: add the title attribute to links.

## Mobile

- [AppLinks](http://applinks.org/documentation/) - Apps that link to your content can then use this metadata to deep-link into your app.
- [mobile friendly](https://googlewebmastercentral.blogspot.be/2014/11/helping-users-find-mobile-friendly-pages.html) - Mobile optimized sites are marked in search results. Test for [mobile friendly site](https://www.google.com/webmasters/tools/mobile-friendly/).
- [Smart App Banner](https://developer.apple.com/library/ios/documentation/AppleApplications/Reference/SafariWebContent/PromotingAppswithAppBanners/PromotingAppswithAppBanners.html) - Safari has a Smart App Banner feature that provides a standardized method of promoting apps on the App Store from a website.
- [Tap targets](https://developers.google.com/speed/docs/insights/SizeTapTargetsAppropriately) - Clickable links should not be too small.
- Viewport: Tell browsers how to adjust the page's dimensions and scaling to suit the device
  `<meta name="viewport" content="width=device-width, initial-scale=1">`

## Sitemap

- [HTML sitemap](https://www.youtube.com/watch?v=hi5DGOu1uA0) - A HTML sitemap allows site visitors to easily navigate a website.
- [Image sitemap](https://support.google.com/webmasters/answer/178636) - Increase that your images can be found in Image Search results.
- [Mobile sitemap](https://support.google.com/webmasters/answer/6082207) - For feature phones, you can create a mobile sitemap.
- [Video sitemap](https://support.google.com/webmasters/answer/80471) - Make sure, search engines know about all the video content on your site.
- [XML sitemap](https://support.google.com/webmasters/answer/183668) - Help search engines to index your pages.

## Social Media

- Authorship information.
- [Facebook](https://developers.facebook.com/docs/sharing/best-practices) - Sharing Best Practices for Websites & Mobile Apps.
- [OpenGraph](http://ogp.me/) - The Open Graph protocol enables any web page to become a rich object in a social graph.
- [Social Profiles](https://developers.google.com/webmasters/structured-data/customize/social-profiles) - Add social profiles to your Google search results.
- Social Shares: Provide sharing options for your site.
- [Twitter](https://dev.twitter.com/cards/getting-started) - With Twitter cards, you can attach photos, videos and media experience to you Tweets.
