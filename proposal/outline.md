# API Guidelines: Creating and Managing Guidance for a Successful API Journey

## Outline

1. Part I: Why API Guidelines
 1. Audience: Who is this Book for?
 
    This book is for two main audiences: (1) People involved in API programs, which often are teams that have roles within the overall API initiative and journey of organizations. These people often are organized in teams with names such as *API team*, *API platform team*, *API Center of Excellence*, or *API Center for Enablement*. (2) People involved in API products who want to better understand how to participate in and contribute to the API practice of their organization. Typically, this might include people both with more background from the business side (asking: "how can we build better APIs so that they will be more successful?") as well as the technical side (asking: "how can we make it as easy as possible for API product teams to design and develop APIs that fit well into the organizational landscape?").

 1. The Big Picture: Digital Transformation, API Strategy, API Programs, and API Guidelines

    This chapter sets the stage for the book: Big orgs want to become faster, understand that for this to happen they need to decouple and decentralize with more autonomous teams, and that to make this work at the tech level, the new value chains that they are enabling will be based on APIs. Teams need to understand that APIs matter, they need to understand what matters when they produce and consume APIs, and they need to be supported so that they can focus on creating value. API programs are put into place to create a culture of API production and consumption, and to build an API platform that teams contribute to, and that can be used by both internal and external consumers. API guidelines are the part of the API program that provide guidance why things are done, what is being done, and how it can be done.
 
 1. API Guidelines as Emerging and Evolving Practice

    APIs are the language of digital transformation. API guidelines help to design those languages, so that the API landscape of an organization is more coherent than a random collection of APIs. API guidelines help API producers to be more effective, because they can build on established practices and don't have to reinvent the wheel. API guidelines help API consumers because it becomes easier to consume APIs when they are coherently designed. API guidelines help to reduce cost because they make it easier to establish practices that then can be supported with infrastructure and tooling. API guidelines should be participatory (bottom-up) instead of authoritarian (top-down). A good start is to observe the existing landscape ("API archaeology") and to use the results as a starting point. API guidelines should be thought of as a living document where all API practitioners are contributors, and a few people are editors and manage a well-defined contribution process.
 
 1. Helping Teams on their API Journey
 
    APIs are the connective fabric of digital transformation. Ideally, teams collaborate through APIs meaning that APIs become an essential organizational communications mechanism that is far more important that just establishing technical connectivity. This means that helping with APIs goes beyond syntax conventions and technology choices. Essentially, caring about API design means being a good citizen in a digital transformation scenario: There are assumptions how to contribute and participate in the evolving landscape of digital capabilities, and if everybody plays along the ecosystems benefits.
    
  1. Concrete Guidelines: Some Examples
  
     This chapter talks a bit about concrete guidelines and introduces both https://dret.github.io/guidelines/ and a few example guidelines that will be used as examples throughout the book. There should be some visual way of marking those sections in the book, so that it becomes clear how these examples are used throughout the book to clearly show how to create and manage guidelines.

1. Part II: API Guidelines as a Product
 1. Release Early, Release Often, Listen to your Users
 
    Guidelines should be treated as a product. Start with a minimal set of guidelines distilled from existing practice (i.e., it reflects reality) and a minimal process. Build the product focusing on DX (i.e., your API product teams are the product users), making it easy to find guidelines, to get a view that fits their needs, to understand how the product works (how can they contribute?), and to contribute to the guidelines.
 
 1. From MVP to User-Driven Development
 
    Release simple guidelines as soon as possible. There are many to choose from. You probably should cover the following areas to make sure that everybody feels represented: Technical design, external/internal standards... Monitor usage and utility of the guidelines as much as possible. Ideally, API products can reference guidelines and this can be made part of the description and the deployment pipeline. Then you have a link between API guidelines and API products, allowing to explore how guidelines are used by teams (Requirement: stable identifiers for guidelines).
    
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
 
    It's good to start minimal, but it's also good to start with extensible designs so that the guidelines can evolve. One possible way is to go with a structure that's similar to what Jekyll uses: A YAML preamble and then MD, where the MD probably also needs to follow certain conventions. In the end, guidelines will be a highly structured document with various consumers and processes around them, and the way they are managed should reflect this need for machine-readability.

1. Part IV: Sharing and Managing Guidelines
 1. Guidelines as a Shared Resource

    Guidelines are a shared resource and thus should be managed like this. Ideally, they follow the spirit of open source projects with open code and tooling, and a core team of contributors that has special roles and tasks. It seems that GitHub is the de-facto platform for guidelines today, and that makes a lot of sense because everybody knows it and thus knows how to participate. There may be some additional tooling on top for processing and readability (maybe discuss the Adidas example which uses Gitbooks, a GitHub-based publishing toolkit).
 
 1. Contributing and Commenting

    With guidelines being the "shared API practices", there probably are two main forms of communications they should facilitate. One is to talk *about* the guidelines (exchanging experiences and opinions), and the other is to *work on* the guidelines (with the goal of making changes). Both processes should be supported and well documented, so that both forms of participation are possible and actively encouraged. Fancier versions of this could even consider topics such as "subscribing to a guideline" and then being informed of any changes to it (this may be possible with GitHub and the newer features, I still have to investigate).
 
 1. The Editorial Role for Guideline Management
 
    The value of guidelines largely depends on their utility. In order to make them useful, two main roles are necessary: One is to monitor and improve the way in which guidelines are written, managed, published, and updated. It is unlikely that the same processes will remain useful for a very long time. The second important role is to work on the subject matter and make sure that the guidelines are managed well. There may be simple editorial roles such as cleaning up contributions. But there also are processes such as deciding whether experimental guidelines are becoming accepted practice or not. For this it makes sense to have an "API guild" or to use whatever else an existing organizational structure has to involve practice leaders throughout the organization.
  
1. Part V: Platforms and Processes
 1. Using GitHub as API Guideline Platform
 
    This chapter takes a deeper dive on using GitHub as a platform. I will select one example from https://dret.github.io/guidelines/ that uses GitHub in a very simple way by just managing a set of markdown documents. The second step is to look at using an publishing platform such as Gitbooks or Jekyll that allows nicer publishing but in its simplest form still is just a generic structured document. The most sophisticated version is to use specific tooling for managing the guidelines: Google's AIP is one example for this, and so is the project that will is being developed for this book.
 
 1. Managing Guideline Contributions on GitHub
    
    This chapter goes into more details of how a specific platform can help with managing guidelines in a better way. It will be based on the project developed for the book, and will look at various scenarios and how they are supported in that system.
 
 1. From Editorial Models to Open Source
 
    This final chapters encourages readers to progress along an evolutionary path. Start with a simple set of guidelines that are machine-readable so that they can be used by tooling. Make sure that this initial approach is extensible and focuses on some of the current pain points in your organization. Then consider moving to a platform that better supports the specific processes around guideline management and contributions. Finally if that platform is open source, then consider building on it whatever else you need. These may be simple tweaks to the platform's features, or integrations with other tooling and platforms that you have.
