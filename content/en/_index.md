
---
title: "Multiplatform Kickstarter Documentation"
linkTitle: "Documentation"
type: "docs"
tags: ["intro"]
weight: 20

cascade:
- _target:
    path: "/blog/**"
  type: "blog"
  # set to false to include a blog section in the section nav along with docs
  toc_root: true
- _target:
    path: "/**"
    kind: "page"
  type: "docs"
- _target:
    path: "/**"
    kind: "section"
  type: "docs"
- _target:
    path: "/**"
    kind: "section"
  type: "home"
---

{{% pageinfo %}}
Multiplatform Kickstarter provides Kotlin multiplatform boilerplate templates
to allow you to develop applications for Android, iOS and Web in a fast way.
{{% /pageinfo %}}


This section is where the user documentation for your project lives - all the information your users need to understand and successfully use your project. 

For large documentation sets we recommend adding content under the headings in this section, though if some or all of them don’t apply to your project feel free to remove them or add your own. You can see an example of a smaller Docsy documentation site in the [Docsy User Guide](https://docsy.dev/docs/), which lives in the [Docsy theme repo](https://github.com/google/docsy/tree/master/userguide) if you'd like to copy its docs section. 

Other content such as marketing material, case studies, and community updates should live in the [About](/about/) and [Community](/community/) pages.

Find out how to use the Docsy theme in the [Docsy User Guide](https://docsy.dev/docs/). You can learn more about how to organize your documentation (and how we organized this site) in [Organizing Your Content](https://docsy.dev/docs/best-practices/organizing-content/).

