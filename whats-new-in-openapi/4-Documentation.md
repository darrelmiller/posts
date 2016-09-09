
## Documentation
The successful interop of existing tooling based around the previous versions of the OpenAPI specification proves that it was successful in conveying the necessary information to tool builders.  We hope to not only continue that success but with the increased particpation of the members of the TDC and community members, we hope to make the specification even more accessible, clear, precise and unambiguous.

### Table of Contents
Adding a table of contents to the specification will help provide new readers an overview of the document structure and will provide links to quickly reference relevant parts of the specification. This is work that still remains to be done, but its inclusion has been agreed upon. 

### Common Mark
The current specification refers to using Github Markdown for providing rich text descriptions of various API objects.  Unfortunately there is no specification for how exactly Github Markdown works and some of its features only work for content hosted on Github.  In order to enable tooling to be more consistently with their implementation of markdown rendering, the latest OpenAPI specification [has adopted the CommonMark format](https://github.com/OAI/OpenAPI-Specification/pull/720).  It is largely compatible with Github markdown so it should have minimal affect on existing documentation, however, there is a detailed specification that describes exactly how the markdown should behave.  

In the next post we will talk about the issues raised by the community that are still outstanding. 