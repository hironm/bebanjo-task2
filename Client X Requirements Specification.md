|||
|-|-|
|Target Release| 1.0 |
| Epic | Client X New YouView Metadata Exporter Features |
|Document status|Draft proposal|
|TAM|Hiron Miah|
|Designer/Architect|TBC|
|Developer|TBC|
|QA|TBC|

## Objective

Client X is planning to launch a new service that showcases **foreign language TV content** (e.g. episodic Scandinavian crime drama). The client would like to **include additional metadata** stored in Movida and then **publish to YouView** for this content. The content will be presented in its original language with subtitles.<br>
**NOTE** - none of their existing content is subtitled.

## Features

| # | User Story Title | User Story Description | Priority | Acceptance Criteria | Notes |
|--|--|--|--|--|--|
| 1 | Audio Track Language | Include the language used for the audio track | High |Information about the source language of the contents audio available to users|Specific details can be found in YouView specification document 4300-CP-Provision-of-Metadata-by-Content-Providers-1.4-E.pdf, **see section 6.7**|
| 2 | Content Subtitle Information | Include the details of the subtitles provided for the content |High|Associated subtitle information is available to users|Specific details can be found in YouView specification document 4300-CP-Provision-of-Metadata-by-Content-Providers-1.4-E.pdf, **see section 8.2.1**|
|3|Production Information|Details of where the content was produced|High|Production details for source content is available to users|Specific details can be found in YouView specification document 4300-CP-Provision-of-Metadata-by-Content-Providers-1.4-E.pdf, **see section 6.9**.<br><br>**Note - Production Location values are not presented currently within the YouView UI**. You can only specify a production location for Editorial Versions.|

## Delivery Deadline

The client hasn't specified a deadline for delivery, however, it would be prudent to plan this work into upcoming sprints to ensure we're ready for delivery once the client establishes the delivery timeline.
