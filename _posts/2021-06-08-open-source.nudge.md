---
layout: post
title:  "Nudging towards a better default for open source project ownership"
author: sharan
categories: [ community, open-practices ]
image: https://images.unsplash.com/photo-1533985062386-ef0837f31bc0?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1650&q=80
featured: false
---
**By [Malvika Sharan](https://malvikasharan.github.io/), [Andrew Brown](http://web.am.qub.ac.uk/wp/largo/members/andrew-brown/), Warrick Ball and [Ben Krikler](https://www.software.ac.uk/about/fellows/benjamin-krikler).**

_This blog post is part of our Collaborations Workshop 2021 [speed blog series](https://www.software.ac.uk/tags/cw21-speed-blog-posts)._

The open source and open research movements allow anybody to use, study, modify, and distribute software or research projects freely and [for any purpose](https://opensource.org/osd). Volunteer contributions are central to the success of open source projects and take many diverse forms. Therefore, ‘shared ownership’ is important for motivating contributors to collaborate but, unfortunately, the ownership model is not always described in the projects. Here we explore what project ownership means in an open source world. 

### Open source project ownership

Software shared without any license is assumed to be copyright by default, meaning only the author can decide who can use the code. Best practice for sharing software is to add an open source license defining the way the existing codebase can be used and shared. But an open source project is more than just the code and documents. A major part of a project is about the people involved, how they interact and share responsibilities, and how they are recognised for their contributions - none of which is regulated by the license. By defining the project ownership, we can address these concerns, going beyond the software license itself. 

Similar to the copyright default of software, **if ownership in a project is not defined, it is not shared.** Shared ownership for an open source project should include the following aspects:

-   **‘Who’** are the project contributors?
-   **‘What’** motivates them to collaborate and contribute, and what do their contributions look like?
-   **‘How’** are they recognised for their contributions?
-   **‘Why’** will they take responsibilities and accountability as a contributor to the project?
-   **‘Where’** can they learn about the project ownership in detail?

#### Example of “shared ownership” models

**Roles Based on Contributor Access to the Project Repository:** For GitHub users, a  familiar set of roles for code ownership includes access levels: [“Read -> Triage -> Write -> Maintain -> Admin”](https://docs.github.com/en/organizations/managing-access-to-your-organizations-repositories/managing-team-access-to-an-organization-repository). The different access levels define the increasing order of rights and responsibilities a contributor has in a project.

![GitHub contributor roles: “Read -> Triage -> Write -> Maintain -> Admin”](https://www.software.ac.uk/sites/default/files/roles.png)

_GitHub contributor roles_

**Open Source Leadership and Governance:** A more intentional approach can be taken to formalise roles. This allows contributors with specific interest or availability to step into the project. The [Open Source Guides](https://opensource.guide/leadership-and-governance/) project provides a basic framework for setting roles for maintainers, contributors and committers. In larger communities it can also include members of committees, working groups, special interest groups, mentors, trainers and community managers. Governance also covers the decision-making processes - how different stakeholders are involved and how decisions are transparently communicated.

**Defining Roles and Pathways for Contributors:** Roles can be developed based on tasks, responsibilities or skill requirements, and can be contractual or informal, taken by paid or non-paid volunteers, and supported by legal or social policies. These roles and pathways for engagement can be understood using “[Mountain of Engagement](https://docs.google.com/presentation/d/1ipIUc1t6ogOpyK9gU_PPgD-UvW0Gs73pMIAdCLOG72Y/present?token=AC4w5VhpTqbOWqPsxwOsnzqMG_DYvAqvGA%3A1596111012295&includes_info_params=1&eisi=CJfzpO_49OoCFYbTJAodKr0HAQ#slide=id.p)” as described by [Mozilla Open Leadership](https://mozilla.github.io/open-leadership-training-series/articles/building-communities-of-contributors/) and [Open Life Science](https://openlifesci.org/). The purpose is to identify levels of engagement of contributors as they move from their roles as “observers”, “endorsers”, “contributors”, “leaders” and finally “owners”.

![Five steps for developing a “Mountain of Engagement” for Open Source project contributors](https://www.software.ac.uk/sites/default/files/mountain%20of%20engagement_0.png)

_Five steps for developing a “Mountain of Engagement” for Open Source project contributors_

### Nudging for a better default

Research has shown that humans making decisions have a strong tendency to go along with the status quo or [default option](https://www.imperial.ac.uk/nudgeomics/about/what-is-nudge-theory/). In the absence of an actively defined default, the prevailing cultural or institutional norm becomes the de-facto option of choice. And hence, the default options for ongoing and new projects should nudge strongly towards adopting a shared ownership model. 

The minimum default for an open source project should include the following documents:

1.  **Open Source License by default:** This can be applied by stakeholders in the research ecosystem: funders can require that code produced by a grant is openly licensed and, similarly, publishers can require that code associated with a publication is openly licensed (open research _data_ is already [required by funders in the UK](https://www.ukri.org/about-us/policies-standards-and-data/good-research-resource-hub/open-research/); this could easily be extended to cover software). The companies that host repositories can - as some do - make it easy to add a license, and gently encourage users to do so by adding a license by default.   
      
    **Call to action:** Plan your project from the beginning to be open throughout the lifecycle of your research.  When using personal or identifiable data, clearly state what measures are taken to ensure privacy and data security. For everything else in your work, choose an open source license and add it to your repository (see [https://choosealicense.com/](https://choosealicense.com/)).   
     
2.  **Ways to acknowledge contributions:** Ownership should be more accurately shared by ensuring that the means of contributing and recognising contributions are properly defined in the project. There are many ways to acknowledge all contributors, including those who do not code or write documentation. For example, we can learn from open source metrics like [CHAOSS](https://chaoss.community/) or [CRediT - Contributor Roles Taxonomy](https://casrai.org/credit/), recognise the hidden labour using frameworks defined by [HiddenREF](https://hidden-ref.org/) or, as in [The Turing Way](https://the-turing-way.netlify.app/community-handbook/acknowledgement.html), allow people to capture their contributions in a way that is most meaningful for them.  
      
    **Call to action:** Recognising contributors by recording their names in visible locations (like a contributors file) should be added to the admins’ or maintainers’ workflows. GitHub actions or bots can be set up to automate the process. For example, you can install the all-contributors bot by [https://allcontributors.org](https://allcontributors.org) to your repository, which can help you recognise contributions including those that don’t involve pushing code.  
     
3.  **Sharing project ownership with the community:** In the case of shared ownership, the community builds the project and hence should be attributed as such. One way to do this is to have essential community documents demonstrating the commitment to fairly acknowledge and share ownership of the project with all contributors.  
      
    **Call to action:** Describe explicitly how someone can cite an open source project by giving credit to the community of contributors instead of attributing individuals administering the project. For example, use “Community” as the first author [as practised by](https://the-turing-way.netlify.app/welcome.html#citing-the-turing-way) _[The Turing Way](https://the-turing-way.netlify.app/welcome.html#citing-the-turing-way). _As a simple first step, consider adding contribution guidelines, a Code of Conduct (see [Open Source Guide for reference](https://opensource.guide/building-community/)), and a ‘contributors’ page to your project repository to display the names of all the contributors.

---

A longer version of this post is added to The Turing Way as a chapter in this Pull Request: [https://github.com/alan-turing-institute/the-turing-way/pull/1858](https://github.com/alan-turing-institute/the-turing-way/pull/1858). We invite you to join the discussion, add your thoughts on this topic or review the chapter.

*[Cover image](https://unsplash.com/photos/YNM4KStg78I) by Saad Chaudhry on [Unsplash](https://unsplash.com/@saadchdhry)*
