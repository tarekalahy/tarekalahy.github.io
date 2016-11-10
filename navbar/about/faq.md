---
layout: page
navtitle: FAQ
title: FAQ
permalink: /faq/
---

Readium.org Frequently-Asked Questions (FAQ)
Below FAQs are divided into categories (General, Readium Foundation, Readium.js, Readium Chrome Extension and the Cloud Reader, Readium SDK, and Readium LCP).

General FAQs

How can I help the Readium projects?

There are many ways to help the Readium projects. You don’t have to be a C++ developer or JavaScript guru.  If you have these skills and want to help, you are of course very welcome!  But we also have great needs for testers, documentation, translators and many other areas.  If you want to help please contact us!

 

FAQs about the Readium Foundation (Readium.org)

What is the relationship between Readium Foundation and IDPF?

Readium began as a project of IDPF, and IDPF helped instigate the Readium Foundation. But the Readium Foundation is a completely independent non-profit corporation, governed by its members. Readium Foundation is focusing specifically on open source implementation, complementary to IDPF's mission as a trade and standards organization. IDPF is a member of the Readium Foundation and is currently providing some administrative support for the Foundation as part of its contributions (and IDPF Executive Director Bill McCoy is currently the chairman of the Readium board.)

Will Readium.org support vendor extensions to EPUB?

Readium.org's initial focus is on accelerating full adoption of complete and consistent implementations of the EPUB 3 standard. Support for extensions that are not officially part of EPUB will therefore be discouraged in Readium.org projects. However, as an open source community, extensions that are widely supported may be adopted. For example, Readium Chrome Extension already supports the Apple extension for specifying fixed-layout EPUB metadata (META-INF/com.apple.ibooks.display-options.xml, etc.)

 

FAQs About the Readium.js Project

What is the status of cross-browser support in Readium.js?

Readium.js is architected to work on any modern (HTML5) browser. The Readium Chrome Extension obviously only functions in the Google Chrome browser. However, the Readium Cloud Reader is a full EPUB 3 implementation that runs in Google Chrome, Firefox, Safari, Microsoft Edge and Opera on essentially all platforms supported by those browsers.  However, given the huge matrix of browsers and platforms, Readium is working hard to ensure that the functionality is equivalent across all the platforms.  That is very difficult and Readium welcomes all who would report problems or, even better, help us make our support more complete.

 

FAQs About the Readium Chrome Extension and the Cloud Reader

Is the Readium Chrome Extension a consumer-grade EPUB reading system?

The original intent of the Readium Chrome extension was  to be used primarily by authors, publishers, and developers creating and testing EPUB 3 content and tools. However the Readium Chrome Extension now has almost 600,000 active users (as of February 2016) and has been translated into 11 languages with the help of our contributors, so clearly we have exceeded that expectation.  That said, there is more to be done to make it a full-fledged EPUB reader.  While RCE supports almost all of the EPUB 3.0.1 standard, there are still some missing features (e.g. a sortable library, annotations, search, etc.), but  the Readium Foundation intends to continue expanding and supporting it in the future..

Will the Readium Chrome Extension or Cloud Reader open DRM-protected eBooks?

At this time there are no plans for Readium Chrome Extension to support DRM-protected eBooks.

Will the Readium Chrome Extension or Cloud Reader support other publication formats besides EPUB?

Not at this time. We have considered supporting PDF, but as an open-source effort we are dependent on volunteers to provide the resources for such undertaking.  At present, such an effort is not in our scope.

Are the Readium Chrome Extension and Cloud Reader accessible?

Yes! Basic accessibility support has been implemented.  We are continuing to work actively on improving that support.  Readium welcomes all reports of areas where we can improve our support and especially welcome any contribution to its development and testing.

Are the Readium Chrome Extension and the Cloud Reader localized to languages besides English?

Yes, 11 languages are currently available for both the Chrome Extension and the Cloud Reader. Contributions of translation assistance are very welcome, as an internationalization infrastructure is in place.  If you wish to help, please contact us by email.

Do the Readium Chrome Extension, Cloud Reader and Readium SDK share source code?

Yes, the Cloud Reader and the Chrome Extension share almost all their source code, the primary difference being that the Chrome Extension is naturally packaged as a Chrome Extension. The Chrome Extension, Cloud Reader and SDK also share a large section of their code, written in JavaScript.

Can I deploy the Cloud Reader on my own site?

Yes!  And it is very easy.  Please see the instructions here.  If you have problems or questions, please contact us via email or find us on Slack (instructions here).

 

FAQs About the Readium SDK

Do I have to buy a commercial license to use the Readium SDK?

It depends. If you are going to use the SDK for a non-commercial case, then you don’t need to get a commercial license as it is licensed under the user-friendly BSD license.  HOWEVER, if you intend to build a commercial application then yes, you must obtain a commercial license as such usage is available only under the terms of the Gnu Affero license. You can find much more info on this here.

Does the SDK support DRM?

Yes, it does but the SDK is DRM-agnostic. This means the SDK has been developed so it can be used with many different kinds of DRM-encrypted books or no DRM at all.  No DRM at all is the default.  Readium will of course support Readium LCP (see below).  This support should be added very soon (spring 2016). For other DRMs, the support must be added by the vendor and is specific to their particular application,

Does the SDK support other book formats than EPUB?

Not at this time. We have considered supporting PDF, but as an open-source effort we are dependent on volunteers to provide the resources for such undertaking.  At present, such an effort is not in our scope.

 

FAQs About Readium LCP

What is Readium LCP?

Readium LCP (Licensed Content Protection) is a DRM system for protecting EPUBs that is being developed by the Readium Foundation and its contributors.  The effort is being led by the European Digital Reading Lab (EDRL), which is a joint venture of the IDPF, Readium and funded largely by the French government. LCP should be available in the spring of 2016.  For more information, please contact EDRL via their website.

Is LCP an open standard?

It will be.  The specification is in the final stages of development.  We will post a link to the public specification as soon as it is available.

Will the implementation be available as open-source?

Yes, with some caveats.  The source code for both the server and the client side implementation will be available through Readium on github.  However, companies, organizations or individuals who wish to use LCP tp protect their content will need to obtain the proper licensing from the Readium Foundation. More information on the details of this process will be available soon. Finally, those licensed companies, organizations or individuals will receive, in a very secure process, certain secret “keys” which will enable the operation of the DRM.  Those keys will be distributed in a very secure way by a third party - NOT the Readium Foundation.

Will LCP be interoperable?

Yes!  Assuming that the organization implementing and using LCP operates it as specified and has a conformant implementation then you will be able to read your LCP-protected books from any source on your devices or applications.