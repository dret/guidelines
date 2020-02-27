# API Guidelines: Creating and Managing Guidance for a Successful API Journey

## Outline

1. Part I: Why API Guidelines
 1. Audience: Who is this Book for?
 
    This book is for two main audiences: (1) People involved in API programs, which often are teams that have roles within the overall API initiative and journey of organizations. These people often are organized in teams with names such as *API team*, *API platform team*, *API Center of Excellence*, or *API Center for Enablement*. (2) People involved in API products who want to better understand how to participate in and contribute to the API practice of their organization. Typically, this might include people both with more background from the business side (asking: "how can we build better APIs so that they will be more successful?") as well as the technical side (asking: "how can we make it as easy as possible for API product teams to design and develop APIs that fit well into the organizational landscape?").

 1. The Big Picture: Digital Transformation, API Strategy, API Programs, and API Guidelines

    This chapter sets the stage for the book: Big orgs want to become faster, understand that for this to happen they need to decouple and decentralize with more autonomous teams, and that to make this work at the tech level, the new value chains that they are enabling will be based on APIs. Teams need to understand that APIs matter, they need to understand what matters when they produce and consume APIs, and they need to be supported so that they can focus on creating value. API programs are put into place to create a culture of API production and consumption, and to build an API platform that teams contribute to, and that can be used by both internal and external consumers. API guidelines are the part of the API program that provide guidance why things are done, what is being done, and how it can be done.
 
 1. API Guidelines as Emerging and Evolving Practice

    APIs are the language of digital transformation. API guidelines help to design those languages, so that the API landscape of an organization is more coherent than a random collection of APIs. API guidelines help API producers to be more effective, because they can build on established practices and don't have to reinvent the wheel. API guidelines help API consumers because it becomes easier to consume APIs when they are coherently designed. API guidelines help to reduce cost because they make it easier to establish practices that then can be supported with infrastructure and tooling. API guidelines should be participatory (bottom-up) instead of authoritarian (top-down). A good start is to observe the existing landscape ("API archaeology") and to use the results as a starting point. API guidelines should be thought of as a living document where all API practitioners are contributors, and a few people are editors and manage a well-defined contribution process.
 
 1. Helping Teams on their API Journeys

1. Part II: API Guidelines as a Product
 1. Release Early, Release Often, Listen to your Users
 
    Guidelines should be treated as a product. Start with a minimal set of guidelines distilled from existing practice (i.e., it reflects reality) and a minimal process. Build the product focusing on DX (i.e., your API product teams are the product users), making it easy to find guidelines, to get a view that fits their needs, to understand how the product works (how can they contribute?), and to contribute to the guidelines.
 
 1. From MVP to User-Driven Development
 
    Release simple guidelines as soon as possible. There are many to choose from. You probably should cover the following areas to make sure that everybody feels represented: Technical design, ... Monitor usage and utility of the guidelines as much as possible. Ideally, API products can reference guidelines and this can be made part of the description and the deployment pipeline. Then you have a link between API guidelines and API products, allowing to explore how guidelines are used by teams (Requirement: stable identifiers for guidelines).
    
 1. Focusing on Participation and DX
 
    (( More research needed here in terms of what organizations have done to measure and improve guideline adoption and utility. There are various interviews lined up and I plan to use these as the foundation for this chapter. ))

1. Part III: Structuring Guidelines
 1. Coverage: What Guidance is Necessary?
 
    This part will talk about the various areas covered by typical guidelines. I am planning an analysis of the guidelines that I have collected at https://dret.github.io/guidelines/ and create some "buckets" that talk about which areas are typically covered by guidelines. This chapter will also discuss the tension between volume and utility: Too much guidance can be overwhelming and complex to navigate. This can be part of the natural evolution, though: Start classifying and creating "views" for roles when utility seems to be compromised by volume.
 
 1. Good is Better than Best

    There are no "best practices". There are "good practices", and they go through a lifecycle of being proposed, being used experimentally (maybe mention Google's AIP model here), being an accepted good practice, and at some point being deprecated and then retired. API products will be designed and built according to the good practices at the time, so it is important to see guidelines as something living and evolving, and to build this into the way how they are managed.
  
 1. Why, What, How, and Test: The Structure of a Guideline
 
    Guidelines should have a clear structure because this helps understanding them, and it also helps evolving them. Each guideline must clearly state why it exists (problem statement), and there must be a process how guidelines can simply be retired. The next part is what is proposed as a way to address the problem; there can be various ways (see previous chapter). The next part is how to put this proposed solution into practice, which can be a choice of a standard, a technology, a tool, or whatever helps to follow the guideline; there can be various ways (see previous chapter). The final part is how to validate that the guideline has been followed. Ideally, there may be automated tests, but oftentimes there might be a process in place that also depends on the maturity of the API product, and the intended consumers (again, possible reference to Google AIP model here).
 
 1. Additional Metadata for Better Guideline Management

1. Part IV: Sharing and Managing Guidelines
 1. Guidelines as a Shared Resource
 1. Contributing and Commenting
 1. The Editorial Role for Guideline Management
 
1. Part V: Platforms and Processes
 1. Using GitHub as API Guideline Platform
 1. Managing Guideline Contributions on GitHub
 1. From Editorial Models to Open Source
