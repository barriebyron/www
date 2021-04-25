# Style Guides

A style guide contains a set of standards for writing and designing content. It helps maintain a consistent style, voice, and tone across your documentation, whether you're a lone writer or part of a huge docs team. A style guide saves documentarians time and trouble by providing a single reference for writing about common topics, features, and more. It can provide guidelines for different documentation deliverables, such as API reference manuals, tutorials, release notes, or overviews of complex technical concepts.

A consistent tone and style makes your content easier to read, reducing your users' [cognitive load](https://en.wikipedia.org/wiki/Cognitive_load) and increasing their confidence in the content's authority.

## Write your own style guide?

A style guide can be something as simple as a list of decisions you've made about how to refer to different items you frequently write about. Or it can be as complicated as the mighty tomes of major publication houses.

You can certainly create a style guide of your own. For the sake of simplicity, this approach might work if you're a lone writer or just starting a small docs group. But neither software nor its documentation operates in a vacuum, so it's a good idea to consult other resources as well. Working from an existing style guide can also help you figure out which things matter in your style guide.

## Style guide resources

Style guides have been around for as long as people have been publishing in any format. Traditional style guides originally intended for specific forms of print publication have become basic standards for many others to refer to, including documentarians:

- The [Chicago Manual of Style](http://www.chicagomanualofstyle.org/book/ed17/frontmatter/toc.html)
- The [AP Stylebook](https://www.apstylebook.com/)

Classics for software documentation include:

- [Microsoft Writing Style Guide](https://docs.microsoft.com/en-us/style-guide/welcome/)
- [Apple Style Guide](https://help.apple.com/applestyleguide/)

Other useful resources:

- [Google developer documentation style guide](https://developers.google.com/style)
- [MongoDB Style Guide](https://docs.mongodb.com/meta/style-guide/)
- [Salesforce Style Guide for Documentation and User Interface Text](https://developer.salesforce.com/docs/atlas.en-us.salesforce_pubs_style_guide.meta/salesforce_pubs_style_guide/overview.htm)
- [The Red Hat Style Guide](http://stylepedia.net/style/)
- [Rackspace Style Guide for Technical Content](https://docs.rackspace.com/docs/style-guide/)
- [18F Content Guide](https://content-guide.18f.gov)
- [SUSE Documentation Style Guide](https://documentation.suse.com/style/current/single-html/docu_styleguide/)
- [gnome Documentation Style Guide](https://developer.gnome.org/gdp-style-guide/2.32/gdp-style-guide.html)

- [What They Don't Tell You About Creating New Style Guides](https://www.writethedocs.org/videos/portland/2018/what-they-don-t-tell-you-about-creating-new-style-guides-thursday-bram/)

## Developer documentation and APIs

Example guides for code samples:

- [Google code samples](https://developers.google.com/style/code-samples)
- [API Documentation Guidelines](http://guides.rubyonrails.org/api_documentation_guidelines.html) by Ruby on Rails
- [Al language snippets](https://bocoup.com/blog/documenting-your-api)

## Command line resources

A command-line interface (CLI) processes commands to a computer program in the form of lines of text. Style guide standards for [command line interface](https://en.wikipedia.org/wiki/Command-line_interface) docs and text include these useful CLI resources:

- [Heroku Dev Center CLI Style Guide](https://devcenter.heroku.com/articles/cli-style-guide)
- Google developer documentation style guide [Documenting command-line syntax](https://developers.google.com/style/code-syntax)
- OSS [Command Line Interface Guidelines](https://clig.dev/#guidelines)
- [10 design principles for delightful CLIs](https://blog.developer.atlassian.com/10-design-principles-for-delightful-clis/)
- [Conventions for writing Linux man pages](https://linux.die.net/man/7/man-pages)
- [CLI Docs to Improve DevX](https://www.youtube.com/playlist?list=PLQiULOUzZJ5hKZGdbC939GKBTLOtPaAyq)

Relevant talks from Write the Docs:

- - [How I learned to stop worrying and love the CLI](http://www.writethedocs.org/videos/portland/2019/how-i-learned-to-stop-worrying-and-love-the-command-line-mike-jang/)

### API documentation

Clear, well-formatted, and detailed API documentation is the key for developers to quickly consume and implement your API. It is also key to helping developers understand what happens when an API call is made, and in the case of failure, understand what went wrong and how to fix it.

From the perspective of a user:

> If a feature is not documented, it does not exist. If a feature is documented incorrectly, then it is broken.

The best API documentation is often the result of a well [designed API](#documentation-driven-design). Documentation cannot fix a poorly designed API. It is best to work on developing the API and the documentation concurrently.

If your API already exists, automated reference documentation can be useful to document the API in its current state. If your API is still being implemented, API documentation can perform a vital function in the design process.

#### Documentation-driven design

If your API isn't built yet, you can create API documentation to help with the design process. The documentation-driven design philosophy comes down to this:

> Documentation changes are cheap. Code changes are expensive.

By designing your API through documentation, you can easily get feedback and iterate your design before development begins.

Some API documentation formats have the added benefit of being machine-readable. These formats open the door to a multitude of additional tools that can help during the entire lifecycle of your API:

- Create a mock server to help during the initial API design
- Test your API before deployment to ensure that the API and the documentation matches
- Create interactive documentation that allows developers to perform demo requests to your API

#### Test-driven documentation

Test-driven documentation aims to improve upon the typical approaches to automated documentation. It allows you to write the bulk of the documentation by hand while also ensuring its accuracy by using your API's tests to generate some content.

Projects such as [Spring REST Docs](https://spring.io/projects/spring-restdocs) use your API's tests to generate small snippets of documentation that you can include in the hand-written API documentation. The accuracy of the documentation is ensured by the tests – if the API's documentation becomes inconsistent with its implementation, the tests that generate the snippets will fail.

#### API resources

- [PayPal's API Design Guidelines](https://github.com/paypal/api-standards/blob/master/api-style-guide.md)
- [Microsoft's REST API Guidelines](https://github.com/microsoft/api-guidelines/blob/vNext/Guidelines.md)
- [Documenting APIs: a guide for technical writers and engineers](https://idratherbewriting.com/learnapidoc/)
- [The Ten Essentials for Good API Documentation](https://alistapart.com/article/the-ten-essentials-for-good-api-documentation/) by A List Apart

## Content guidelines

It's important to create consistency in your content types. Doing so allows you to manage your audience's expectations for what they will learn on any given page.

### FAQs

Frequently Asked Questions (FAQs) exist to educate and guide users through need-to-know information, pointing them to additional resources when necessary. FAQs should be short and limited.

Effective FAQ pages accomplish the following:

- Reflects the audience's needs. This may be derived from understanding search results, which lead to the website or documentation.
- Regularly updated to reflect the changes in user behavior and data.
- Drives users to different parts of the website to deliver more detailed information.
- Cover a broader range of topics that may not otherwise warrant individual pages or pieces of content.

Caveat: Be sure to follow a maintenance plan for FAQs, since many content gets parked here and becomes outdated. Consider finding a relevant content structure for the content outside of the FAQ scope.

### Release notes

Release notes exist to provide users with vital information required to continue to use and benefit from a product. Release notes content is related to new or updated feature releases. Release notes should be brief, linking out to more details as necessary.

Consider the following when creating an entry for your release notes:

1. What is the specific change?

2. Why did we make this change? Why is it important to our users?

  - Improvement in workflow or UI
  - Consistency and feature parity
  - Policy and legal changes
  - Security

3. What is the goal for our users who use this feature?

4. Do our users have all the information they need to move forward?

5. Is there an additional article for users to read and to learn more? Yes? Link to those resources.

6. Would an image be beneficial to help users understand this release?

7. What stakeholders have to approve this content? Does it require the legal team's approval?

Release Notes Style Guide Resources:

- [Release notes guidelines - Rackspace](https://docs.rackspace.com/docs/style-guide/release-notes-guidelines/)
- [Release notes and changelogs - Unity Docs Style Guide](https://unity-docs.gitbook.io/style-guide/style/release-notes)
- [5 excellent product release note examples and how to write your own - Appcues](https://www.appcues.com/blog/release-notes-examples)
- [The Importance of Writing Release Notes - Testlodge](https://blog.testlodge.com/importance-of-writing-release-notes/)
- [Transforming Your Release Notes into Product Announcements - Parlor](https://www.parlor.io/blog/transforming-your-release-notes-into-product-announcements/)
- [The art of writing great release notes - UX Collective](https://uxdesign.cc/the-art-of-writing-great-release-notes-6607e22efae1)
- [How to make release notes count - Opensource](https://opensource.com/article/17/3/how-to-improve-release-notes)
- [The best and the worst app release notes that will inspire you - announcekit](https://announcekit.app/blog/the-best-and-the-worst-app-release-notes-that-will-inspire-you)
- [How to Write Release Notes Your Users Will Actually Read - ProductPlan](https://www.productplan.com/learn/release-notes-best-practices/)

Some example of great release notes:

- [Slack](https://slack.com/release-notes/mac)
- [Jira](https://confluence.atlassian.com/adminjiraserver/upgrade-matrix-966063322.html)
- [Google Ad Manager](https://support.google.com/admanager/answer/10290437)
- [DataStax](https://docs.datastax.com/en/dse/6.8/dse-admin/datastax_enterprise/releaseNotes/releaseNotes.html)
- [Firefox](https://www.mozilla.org/en-US/firefox/releases/)
- [madcap](https://kb.madcapsoftware.com/Content/Flare/General/GEN1066F_-_Flare_2021_Release_Notes.htm)
- [teamwork.](https://www.teamwork.com/roadmap)
- [Unreal Engine](https://docs.unrealengine.com/en-US/WhatsNew/Builds/index.html)

What to Avoid:

- [App Release Notes Are Getting Stupid - TechCrunch](https://techcrunch.com/2015/09/04/app-release-notes-are-getting-stupid/)

Related talks:

- [Learning to love release notes](http://www.writethedocs.org/videos/prague/2018/learning-to-love-release-notes-anne-edwards/) at Write the Docs Prague 2018
- [Alexander Koren - Rethinking Release Notes](https://www.youtube.com/watch?v=SWduFnDPjYg) at Write the Docs Australia 2019

### Error messages

Mistakes in software are unavoidable. Users might click a link that turns out to be broken or they might perform an action only to be met with an error. When a user encounters a problem, it's important to write error messages in a way that doesn't alienate the user.

Here are a few tips on what makes a good error message:

- Provide explicit indication that something has gone wrong.
- Write like a human, not a robot.
- Don't blame the user – be humble.
- Make the message short and meaningful.
- Include precise descriptions of exact problems.
- Offer constructive advice on how to fix the problem.

Related resources:

- [Error Message Guidelines - Microsoft](https://docs.microsoft.com/en-us/windows/win32/debug/error-message-guidelines)
- [Error Message Guidelines – NN Group](https://www.nngroup.com/articles/error-message-guidelines/)
- [How to Write Good Error Messages – UX Planet](https://uxplanet.org/how-to-write-good-error-messages-858e4551cd4)
- [How to write better error messages – opensource.com](https://opensource.com/article/17/8/write-effective-error-messages)
- [How to write better error messages for databases - PostgreSQL](https://www.postgresql.org/docs/current/error-style-guide.html)

## Writing Style

The following style guides focus on writing more generally:

- [The Sense of Style](https://stevenpinker.com/publications/sense-style-thinking-persons-guide-writing-21st-century)
- [Stylish Academic Writing](https://www.hup.harvard.edu/catalog.php?isbn=9780674064485)
- [Mailchimp's Voice and Tone guidelines](https://styleguide.mailchimp.com/voice-and-tone/)

## Other style resources

Rather than reinvent the wheel, here are some resources curated by [Ivan Walsh](http://www.ihearttechnicalwriting.com/style-guide-technical-writing/) (Kudos!):

- [Creative Blog -- Create a website style guide](http://www.creativebloq.com/design/create-website-style-guide-6123030)
- [Gather Content -- Developing a Content style guide](http://blog.gathercontent.com/tone-of-voice-guide)
- [HubSpot -- How to Create a Writing style guide Built for the Web](http://blog.hubspot.com/blog/tabid/6307/bid/31247/The-Simple-Template-for-a-Thorough-Content-Style-Guide.aspx)
- [Meet Content -- Editorial Style for the Web](http://meetcontent.com/blog/elements-of-editorial-style-for-the-web/)
- [Stanford -- Creating a web style guide](https://swsblog.stanford.edu/blog/creating-web-style-guide-cardinal-work)
- [Techwhirl – Developing a Style Guide for Technical Publications](http://techwhirl.com/developing-a-departmental-style-guide/)
