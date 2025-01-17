---
title: "Cognitive Accessibility at W3C"
parent: "/standards-guidelines/"
permalink: /cognitive/
lang: en
github:
  repository: w3c/wai-cognitive
  path: content/index.md
last_updated: 2022-03-22  
  
ref: /cognitive/   # translators do not change 
feedbackmail: wai@w3.org
footer: >
  <p><strong>Date:</strong> Updated 22 March 2022. First published March 2019.</p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: Steve Lee and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>.</p>
  <p>Developed with input from the Cognitive and Learning Disabilities Accessibility Task Force (<a href="https://www.w3.org/WAI/PF/cognitive-a11y-tf/">COGA</a>). Developed with support of the <a href="http://www.easyreading.eu/">Easy Reading Project</a>, a European Commission (EC) co-funded project, Horizon 2020 Program (780529).<p>

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page introduces:
* accessibility for people with cognitive and learning disabilities ("cognitive accessibility")
* existing standards from the World Wide Web Consortium (W3C) Web Accessibility Initiative (WAI)
* informative guidance beyond the standards
* on-going work on cognitive accessibility support at W3C WAI

Quick link to informative guidance:
* **[Cognitive Accessibility Guidance](/WCAG2/supplemental/#cognitiveaccessibilityguidance)** &mdash; short design patterns,  explained briefly in [About Supplemental Guidance](/WCAG2/supplemental/about/)
* [Making Content Usable for People with Cognitive and Learning Disabilities](https://www.w3.org/TR/coga-usable/) ("Content Usable") Working Group Note &mdash; long document that covers many different aspects for many different roles

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## About Accessibility for People with Cognitive and Learning Disabilities

Cognitive and learning disabilities impact how people process information. For example, they can affect people's perception, memory, language, attention, problem solving, and comprehension. Terminology for categories and conditions varies, and includes intellectual disabilities, developmental disabilities; attention deficit hyperactivity disorder (ADHD), autism, dementia, dyslexia, and more.

Technology provides opportunities for people to interact with content and to process information in ways that are more usable to them. For example, people can:
* navigate web content using different strategies
* access information in text, audio, or other formats
* change the presentation of the content according to their individual needs or preferences

There are many things that designers and developers can do to:
* avoid accessibility barriers that exclude people from using their products
* optimize the user experience of people with cognitive and learning disabilities

Specific examples of cognitive and learning disabilities and examples of accessibility barriers are in this section of "How People with Disabilities Use the Web: Diverse Abilities and Barriers": [Cognitive and learning](https://www.w3.org/WAI/people-use-web/abilities-barriers/#cognitive).

## Cognitive Accessibility in W3C Standards

Existing and developing standards from the W3C Web Accessibility Initiative (WAI) address many aspects of cognitive accessibility. For example, Web Content Accessibility Guidelines ([WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/)) includes requirements that address cognitive accessibility. The requirements (called “success criteria”) are in these and other guidelines:

* [Guideline 1.3 Adaptable](https://www.w3.org/WAI/WCAG21/Understanding/adaptable): Create content that can be presented in different ways (for example simpler layout) without losing information or structure.
* [Guideline 1.4 Distinguishable](https://www.w3.org/WAI/WCAG21/Understanding/distinguishable): Make it easier for users to see and hear content including separating foreground from background.
* [Guideline 2.2 Enough Time](https://www.w3.org/WAI/WCAG21/Understanding/enough-time): Provide users enough time to read and use content.
* [Guideline 2.4 Navigable](https://www.w3.org/WAI/WCAG21/Understanding/navigable): Provide ways to help users navigate, find content, and determine where they are.
* [Guideline 3.1 Readable](https://www.w3.org/WAI/WCAG21/Understanding/readable): Make text content readable and understandable.
* [Guideline 3.2 Predictable](https://www.w3.org/WAI/WCAG21/Understanding/predictable): Make Web pages appear and operate in predictable ways.
* [Guideline 3.3 Input Assistance](https://www.w3.org/WAI/WCAG21/Understanding/input-assistance): Help users avoid and correct mistakes.

Additional guidance on cognitive accessibility is include in the WCAG Understanding documents and Techniques, including Advisory Techniques. These documents are introduced in a section of the WCAG Overview: [What is in the WCAG 2 Documents](https://www.w3.org/WAI/standards-guidelines/wcag/#whatis2).

## Additional Support for Cognitive Accessibility

Some cognitive accessibility user needs are not addressed in existing W3C standards.

W3C is actively working to provide additional guidance on cognitive accessibility, including:

* updating "supplemental guidance" beyond what fits into accessibility standards now
* developing additional requirements to be included in future versions of WCAG
* developing standards for [personalization](https://www.w3.org/WAI/personalization/), which is a key aspect of cognitive accessibility

### Supplemental Guidance

Supplemental guidance provides additional ways to improve accessibility beyond what is required by WCAG 2. Following the guidance is not required to meet WCAG.

We encourage you to follow the guidance to meet more user needs. The accessibility issues addressed in this guidance are essential for people with certain disabilities to be able to use digital technology.

**[Cognitive Accessibility Guidance](/WCAG2/supplemental/#cognitiveaccessibilityguidance)** in <cite>Supplemental Guidance to WCAG 2</cite> provides brief "Objectives" and "Design Patterns" that include:
* what to do to improve accessibility
* how it helps when applied
* examples

[Making Content Usable for People with Cognitive and Learning Disabilities](https://www.w3.org/TR/coga-usable/) (“Content Usable”) is a much long document. It is an informative Working Group Note (not a W3C standard). It includes:
* aims and objectives for usable content
* design patterns (ways) to make content usable _(these are the same as in [Cognitive Accessibility Guidance](/WCAG2/supplemental/#cognitiveaccessibilityguidance) linked above)_
* including users in design and testing activities
* personas (user stories) and user needs

We welcome comments for the next version of Content Usable. To comment, please open a new issue in the [COGA GitHub repository](https://github.com/w3c/coga/issues/new) or send comments in e-mail to: public-coga-comments@w3.org

## Cognitive Accessibility Work at W3C

Current work on cognitive accessibility at W3C WAI is mostly focused in the following Task Forces under the Accessibility Guidelines Working Group ([AG WG](https://www.w3.org/WAI/GL/)) and the Accessible Platform Architectures ([APA](https://www.w3.org/WAI/APA/)) Working Group:

* [Cognitive and Learning Disabilities Accessibility Task Force (COGA)](https://www.w3.org/WAI/PF/cognitive-a11y-tf/) &mdash; Resources in development are listed in the [COGA wiki main page](https://www.w3.org/WAI/PF/cognitive-a11y-tf/wiki/Main_Page).
* [Personalization Task Force](https://www.w3.org/WAI/APA/task-forces/personalization/) &mdash; Resources in development are introduced in the **[Personalization Overview](https://www.w3.org/WAI/personalization/)**.

## Get Updates, Get Involved

To get notices of opportunities for review and comment on WAI documents, see [Get WAI News](https://www.w3.org/WAI/news/subscribe/).

Opportunities for contributing to cognitive accessibility and other WAI work are introduced in [Participating in WAI](https://www.w3.org/WAI/about/participating/).

If you would like to be more involved in the Task Force work, please send information about your interests and time availability:

* For the Cognitive and Learning Disabilities Accessibility Task Force (COGA), [e-mail Task Force Facilitator Lisa Seeman and Rain Michaels, and W3C Staff (wai@w3.org)](mailto:lisa.seeman@zoho.com,rainb@google.com,ran@w3.org,cooper@w3.org?cc=wai@w3.org&subject=Cognitive%20Accessibility%20Task%20Force%20Inquiry).
* For the Personalization Task Force, [e-mail Task Force Facilitators Lionel Wolberger and Sharon Snider, and W3C Staff (wai@w3.org)](mailto:lionel@userway.org,snidersd@us.ibm.com,ran@w3.org?cc=wai@w3.org&subject=Personalization%20Task%20Force%20Inquiry).
