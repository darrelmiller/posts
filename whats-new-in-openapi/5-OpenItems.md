
## Remaining Items
There is still a reasonable amount of work still to do before the TDC will be ready declare this version baked.  You don't get very many opportunities to make the significant level of changes that are being made in this release so it is important not to rush out with something that is not ready. 

### Security
There are a number of outstanding requests regarding the description of API security and hopefully the TDC will be able to address these soon.

### Path Definition
The path object has a key value that defines a set of path segments of the URL that along with the schema, host, basepath and query parameters make up the URL that will map to the contained set of operations. There have been many requests to make various aspects of the URL definition more flexible.  Unfortunately, there is always a cost to the flexilibility.  Usually that cost is increased complexity of tooling, or ambiguity in the instance document.  The working group is currently reviewing the capabilities provided by URI Templates as defined by RFC 6570, to identify what features from that specification can be adopted with the minimum of new issues.  

### Non-Json Data
One fairly significant challenge that remains is how OpenAPI should enable the description of non-JSON data.  Currently the schema language is heavily biased towards describing JSON data.  Some customizations have been introduced to support minimal aspects of other formats, and the proposed removal of the form data parameter has introduced a need to be able to describe the schema of that payload. An open question remains, what is the complexity cost of supporting non-JSON formats and what percentage of APIs does that benefit?     

## Summary 
In the comming months the TDC will continue working with community members to resolve the remaining open issues.  Progress so far suggests that the next version of OpenAPI will be easier to understand, will address more user scenarios and be capable of driving more useful documentation, and more extensive validation, with minimal additional burden on tooling authors. With the formal structure of the Linux foundation, the financial support of member companies and the continued participation of the community, OpenAPI can look forward to an even brighter future.
