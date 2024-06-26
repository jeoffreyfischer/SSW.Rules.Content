---
seoDescription: Your SharePoint site should have a favicon to enhance user experience and professionalism. By adding a small icon file, you can differentiate your site from others and make it more memorable for users.
type: rule
archivedreason:
title: Do you have a favicon on your SharePoint site?
guid: c9198979-7771-4526-b3ee-fb05d2024b36
uri: does-your-sharepoint-site-have-a-favicon
created: 2009-04-21T03:40:52.0000000Z
authors:
  - title: John Liu
    url: https://ssw.com.au/people/john-liu
  - title: Adam Cogan
    url: https://ssw.com.au/people/adam-cogan
related:
  - favicon
redirects: []
---

All websites should be following [the favicon rule](/favicon).

A Favicon is a small image file included on nearly all professional developed sites. When a browser hits your website and a user bookmarks that site then the `favicon.ico` graphic will be displayed in the browser’s URL/address line upon subsequent visits to that site.

<!--endintro-->

Let's see how it's done for SharePoint:

::: greybox

&lt;head runat="server"&gt;
    &lt;meta name="GENERATOR" content="Microsoft SharePoint"&gt;
    &lt;meta http-equiv="Content-Type" content="text/html; charset=utf-8"&gt;
    &lt;!--Placeholder for additional overrides--&gt;
    &lt;asp:ContentPlaceHolder ID="PlaceHolderAdditionalPageHead" runat="server" /&gt;
    <mark>&lt;link rel=&quot;shortcut icon&quot; href=&quot;~/Style Library/Images/SSW/Rules/ssw.ico&quot; type=&quot;image/x-icon&quot; /&gt;</mark>
&lt;/head&gt;

:::
**Figure: One line of HTML lets you add your company's icon to your SharePoint site**
