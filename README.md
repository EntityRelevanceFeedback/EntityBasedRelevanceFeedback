# Entity-Based Relevance Feedback

Using crowdsourcing we collected term and entity relevance feedback for ROBUST and ClueWeb datasets. 
The resultant annotated dataset is the largest reported in the literature for term relevance feedback, and the first for entity relevance feedback, to the best of our knowledge. We published our annotated dataset, corpus entity statistics and the initial document list for further academic use.

## Data Format
The annotated file format is tab-separated as follows: 

<strong>Term relevance feedback</strong>

`<Query Id>`  `<stemmed token>` `<token>` `<context(for the term + sentence interface)>`  `<Worker Id>` `<annotation>`

<strong>Entity relevance feedback</strong>

`<Query Id_Entity Id>`  `<Wikipedia title>` `<context(for the entity + sentence and entity + abstract interfaces)>`  `<Worker Id>` `<annotation>`
