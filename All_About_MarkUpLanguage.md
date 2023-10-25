# What Is HTML5?
HTML5 is the fifth version of the hypertext markup language (HTML), used by web browsers to visualize code. It features several improvements in website capabilities, web content development, and more.

# Evolution of HTML
In the early days of the World Wide Web, leading web browser creators such as Microsoft Internet Explorer and Mosaic Netscape developed browser-specific elements to enhance web page appearance for their browsers. By the late 1990s, they had created distinct versions of websites for Internet Explorer and Netscape.

It was in 1996 that the newly formed World Wide Web Consortium (W3C) recommended the creation of HTML 3.2. This standard covered the commonly used HTML elements of the time. It also included presentational extensions to HTML, such as the center elements and fonts created during the Internet Explorer-Netscape ‘browser wars’.

Soon came HTML 4.0 (1998) and HTML 4.01 (1999), emphasizing the separation of presentation and structure while enhancing accessibility. These upgrades transferred presentation elements under the newly created cascading style sheets (CSS) standard.

# Advent of HTML5
Shortly after the turn of the millennium, representatives from Mozilla, Opera, and Apple teamed up to establish the Web Hypertext Application Technology Working Group (WHATWG). The goal of this entity, which was distinct from W3C, was to enhance HTML development in a way that enabled the language to fulfill new demands arising from real-world authoring practices and browser behavior. Web Applications 1.0 and Web Forms 1.0, the initial documents of WHATWG, were combined to establish HTML5.

Today, WHATWG maintains a ‘living’ HTML standard that is not classified using numbers. WHATWG’s work has also served as the basis for W3C to set up its own HTML5 Working Group. HTML5 formally received the status of a ‘Recommendation’ in October 2014.

Specifications for the HTML5 standard are maintained by both organizations alongside each other, which occasionally gives rise to slight inconsistencies. Most browser devs rely on the WHATWG version for implementation reference.

HTML 4.01 Strict, the version without presentation-based elements and other deprecated attributes, served as the basis for HTML5. This has led to most HTML5 being created using the same browser-compatible elements used for years prior. It has also introduced many new elements and global attributes and made many deprecated attributes and elements from HTML 4.01 obsolete. A key feature of HTML5 is the inclusion of a standard protocol for handling legacy and malformed markup by browsers.

# What sets HTML5 apart
Before this upgrade, HTML focused on the elements used for marking up content for the visualization of web pages. HTML5 takes things ahead by offering numerous new methods for completing tasks. In the case of previous HTML versions, these tasks would require specific programming or proprietary plug-ins such as Silverlight or Flash.

HTML5 features include markup and scripting elements, as well as application programming interfaces (APIs) for functionalities such as adding video and audio on a page, local data storage, offline operations, and location data usage. With HTML5 addressing standard web development functions, dev teams don’t need to create functionality from scratch for every application and can instead rely on built-in browser capabilities.

# Elements of HTML5
HTML5 has introduced numerous new elements supported by most major web browsers. Listed below are the key elements of HTML5.

1. <article>
This new sectioning element is used to mark specific content as being part of an article. This content is then treated independently from other content on the website, even though there may be overlaps.

2. <aside>
This element defines content aside from the content that is contained within. It is often used in document sidebars. While this element does not render in a specific form in a browser, one can use CSS to style it.

This element aims to identify content related to the page’s primary content but not a part of its main intent. For instance, one can use it to outline author information and ‘see more’ links.

3. <audio>
This element allows users to embed a page’s sound content, such as music or audio streams. The <audio> tag is used with one or more <source> tags to demarcate audio sources. The browser will run the first supported source. Supported audio formats include MP3, OGG, and WAV. If a browser does not support this element, it will display the text between the <audio> and </audio> tags.

4. <bdi>
The name of this element stands for bi-directional isolation. Its function is to isolate a text segment that one might format in a direction different from the text outside the element. <bdi> helps embed user-generated content that features text with unknown directional formatting.

5. <canvas>
This element uses JavaScript to draw graphics (boxes, paths, gradients, text) and add images to a page. Borders and text are not included by default, and the tags are transparent and only serve as a container for drawn graphics. These graphics can be generated using a script distinct from the element. If the element is not supported or JavaScript is disabled in a browser, it will show any text inside the <canvas> tags.

6. <data>
This element is used to add machine-readable information to content. The machine-readable value is provided by data processors, while a human-readable value is also offered for web browsers to render.

7. <datalist>
This element provides an ‘autocomplete’ feature for the <input> element by specifying a dropdown list of preset options that the browser will present to users as data is inputted. The id attribute of the <datalist> element has to be equal to the list attribute of the <input> element to bind them.

8. <details> and <summary>
The content contained within this element is initially hidden and only displayed once the user wants to see it. It can include any content. 

An interactive widget that the user can open or close is created for this purpose. This widget is closed by default and expands once opened to display the content within.

The <summary> tag defines the visible heading of the <details> widget, which can be interacted with to view or hide the content.

9. <dialog>
This element defines a dialog box or subwindow, making it easy to generate popup dialogs and modal windows on a web page.

10. <embed> 
This element is used to embed third-party applications that generally take the form of multimedia content such as video or audio. It serves as a container for users to embed plugins such as Flash animation. Only the starting tag is required for implementing this element in HTML5. You should note that many modern browsers no longer support Java Plug-ins and Applets, ActiveX controls, or Shockwave Flash, limiting the usability of this element.

11. <figure> and <figcaption>
This element is used to specify self-contained content such as diagrams, illustrations, code listings, and photos. Its content is related to the main flow; however, its position does not rely on the main flow, and the page flow generally remains unaffected if the element is removed. The <figcaption> element allows users to add a caption for <figure>.

12. <footer>
This element defines a footer for a section or a page. It typically contains information on the author, contact details, copyrights, ‘back to top’ links, sitemap, related reading, and so on. A single document can contain several <footer> elements. Contact details are typically inserted inside this element’s <address> tag.

13. <header> 
This element generally contains information related to the heading and title of the page. Typically, it outlines a container for introductory information or navigational links. It is also helpful for visualizing one or more heading elements (classified from <h1> to <h6>), logos, icons, and authors. This element can even be used to wrap a search form or the table of contents for a section. While a single document can contain numerous <header> elements, <header> tags cannot be placed within an <address>, <footer>, or other <header> element.

14. <keygen>
This element is used in forms to specify a key-pair generator field. Its purpose is to provide users with a secure authentication method. Once the form is submitted, public and private keys are generated. The latter is stored locally, while the former is transmitted to the server and used to create client certificates for authenticating the user in the future. The element is also helpful for creating and verifying digital signatures.

15. <main>
This element outlines the main content of the page, which should be unique to that specific document. Content repeated across documents, such as navigation links, sidebars, site logos, search forms, and copyright data, should not be contained within this element. A single document cannot have more than one <main> element, and this element cannot be a descendant of an <aside>, <article>, <header>, <footer>, or <nav> element.

16. <mark>
This element defines the text that must be highlighted or marked within a paragraph.

17. <meter> 
Also known as a gauge, this element is used to define scalar measurements within a predefined range and fractional values. For instance, <meter> can determine disk usage or query result relevance.

18. <nav>
This element outlines sections of the website that are typically dedicated to navigational links that lead to either another spot on the current page or a different page. Common <nav> elements include tables, menus, and indexes.

One must not include every link within a document inside an <nav> element; rather, it is meant only for larger navigation link blocks. Screen readers and browsers with similar features can use <nav> to know when the initial content rendering can be skipped.

19. <output>
This element represents the output of a calculation, such as one performed by JavaScript or another script. Its attributes include for (for specifying the relationship between the calculation result and the elements used during the calculation), form (for specifying the form that the output element belongs to), and name (for naming the output element).

20. <progress>
This element visualizes the progress of a task, such as the amount of work completed or the duration of downloads. It is generally used along with JavaScript.

21. <ruby>, <rt>, and <rp>
This element is used to specify ruby annotations, i.e., extra text in a tiny font attached to the main text. The purpose of the ruby text is to guide users in the meaning or pronunciation of characters (generally used for Japanese content).

<ruby> is regularly used together with <rt> and <rp>. <ruby> contains characters that require an explanation, <rt> contains the information to be given, and optional <rp> tags are used to define the content to be shown in the case of browsers that cannot support regular ruby annotations.

22. <section> 
This element defines specific sections of web pages, including headers and footers. It is used to divide a page into sections and subsections, especially when more than one header, footer, or other section marker is required. It groups generic blocks of related content.

23. <svg>
This element creates a container for SVG graphics. It has numerous methods for drawing boxes, paths, circles, graphic images, and text.

24. <time>
This element displays the date and time in a human-readable format and is also used for encoding date and time data in a machine-readable format. Its applications include birthday reminders, scheduling calendar events, and enhancing the quality of search engine results.

25. <video>
This element is used to embed video content in a webpage. It should contain <source> tags to outline the different video sources, and the browser will play the first supported source. Supported video formats include MP4, OGG, and WebM. If the browser does not support this element, it will display the text between the <video> and </video> tags instead.

26. <wbr>
The name of this element stands for word break opportunity. It specifies the spots within a text line where a line break can be added if required. This is useful when words that are too long are used and might be broken at the wrong place by the browser.

# Benefits of HTML5
We’ve already seen how the elements introduced in HTML5 ease the integration of multimedia content and enhance semantic value. Now we’ll take a closer look at the benefits of HTML5.

1. Semantic enrichment
Semantic markup describes markup that is associated with a specific meaning rather than simply creating a particular visual output. For instance, the <h1> tag clearly demarcates the main headline of the webpage. While one could achieve the same output by making the headline text bold and large using the relevant formatting tags instead of the <h1> tag, the semantic meaning would not be retained.

Previous versions of HTML also had semantic markup such as heading tags, link rel, and doc metadata. However, common structural elements such as navigation menus, page headers, and main content sections were not semantically differentiated. Instead, they all used the <div> tag.

HTML5 addresses this with a host of new semantic elements, such as <header>, <main>, <section>, <nav>, <aside>, <article>, and <footer>. Additionally, new inline semantic elements such as <address> and <time> help online services such as search engines quickly locate relevant data on a page. Existing inline markups such as bold, italic, and underline have also been refined and are now associated with specific semantic meanings.

2. Rich media experiences without plugins
With internet speeds becoming faster, rich media has become a core part of the online experience. While HTML originally served as a markup language for hypertext documents (and maybe a few images), HTML5 inherently supports rich media through elements such as <video> and <audio>.

Apart from being functional and convenient for developers, this feature has another benefit: doing away with plugins. Some disadvantages of plugins such as Java and Flash include poor performance, fewer user options, security flaws, and lack of search engine visibility.

Additionally, HTML5 provides users with new form elements and superior integration with CSS and JavaScript, simplifying the creation of full-scale rich media web applications without relying on plugins.

3. XML compatibility
Thanks to the XML serialization of HTML5 (also known as XHTML5), code can be written using the ‘stricter’ XML syntax. This is useful for developers who prefer the neatness offered by well-formed XHTML, including quoted attribute values, lowercase element names, and the closure of all elements. In cases where code is expected to work with other XML applications, HTML5 documents must be served as XML.

4. Design and content separation
Apart from encouraging semantic markup, HTML5 discourages non-meaningful markup that is only intended to help the browser visualize stuff (think declarations for font, text color, text alignment, and so on). This standard has deprecated many elements that enabled such visualization, and the few supported features display ‘not a recommended practice’ warnings.

Separating design and content simplifies website maintenance and redesign, as CSS handles style declarations. Also, design decisions that look good on one platform (say, a desktop) won’t necessarily look good on another (mobile). HTML5 addresses this by providing semantic context and allowing for content adaptation.

5. Accessibility and design responsiveness
Early iterations of HTML were not seamlessly compatible with modern technology’s numerous screen sizes and aspect ratios. This includes mobile phones, tablets, e-readers, assistive technologies such as text-to-speech converters, screen readers that suppress styling while boosting text magnification and contrast, and braille interpreters. These technologies were held back by markup that attempted to ‘hard-code’ styling and design into page content.

However, thanks to semantic tags and accessible rich internet applications (ARIA), creating accessible and responsive websites is much simpler with HTML5. For instance, screen readers can interpret HTML5 content more easily, making online browsing easier for visually impaired persons.

6. Application programming interfaces
Earlier HTML specifications only documented the elements, values, and attributes allowed in the language. This worked for simple text sites but didn’t do much to help create web-based applications that needed programming and scripting.

HTML5 has made a great leap by defining numerous new APIs that simplify communication with applications. It introduces APIs for functionality that earlier needed plugins or customized code, including web storage, drag and drop, geolocation, and microdata.

This has helped standardize specific mechanics, simplifying otherwise complex coding tasks and allowing developers to add functionality that works on browsers across platforms seamlessly. 

7. Persistent local storage
HTML5 supports local browser storage that serves as a hybrid between cookies and client databases. This feature allows browsers to support storage across numerous windows simultaneously, enhancing security and performance and ensuring data persistence even after the browser is closed.

Persistent local storage enables offline operations and prevents cookie deletion from adversely affecting browser operations, as client-side data storage powered by HTML5 is now supported on most modern browsers. It also allows applications that use HTML5 functionality instead of third-party plugins to operate smoothly.
