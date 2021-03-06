## Overview
The purpose of the Story Pitch Management System is to provide an organized pipeline for story pitches so that more new and creative stories can be given the opportunity to be published. 

- # Authors can submit story pitches
    - Different types of work have different weights
        - ***Maximum point total of 100***
        - Novels: 50 points
        - Novellas: 25 points
        - short stories: 20 points
        - articles: 10 points
    - If an author attempts to submit a story that they do not have sufficient points for, the submission is put on hold until enough points are available.
    
    ### **Story Pitch Form**
    - Must include the following information:
        - basic information about the author
        - tentative story title
        - tentative completion date
        - story type (based on length, **chosen by the system?**)
        - genre
        - tag line
        - detailed description
    - Optional inclusions:
        - attachments regarding any research or images related to the story
        - any .msg (Outlook Email) files that feature any discussion with any of our agents or external sources (especially in the case of non-fiction, research-based works)
    - Form should have a field that calculates whether the author currently has sufficient points to submit the request, or if it will be saved for later submission (as described above)

    ### **Business Rules**
    - Story types and genres each pulled from reference tables.
        - Story type reflects number of points author will have availabe whilst the story is pending.
        - Story type also determines the approval process (see below)
        - Genre determines whom the story will be managed by.
        - Each genre has a group of editors with specialization in that genre.
- # Approval Process
    - ## Assistant Editor Approval
        - An assistant in the relevant genre committee must approve the story pitch.
        - The assistant can request more informaiton from the author before approving the pitch, if desired.
        - If the request is denied, a reason must be provided to the author.
        - If the assistant takes too much time to approve the pitch, it is marked as **high priority** and must be processed before other pending requests.
        - If the relevant genre committee does not have an Assistant Editor, this step is skipped.
    - ## General Editor Approval
        - After approval from the Assistant Editor, an editor who is **NOT** in the relevant genre committee must then approve the request.
        - This editor can request more information from either the author or the Assistant Editor that approved the pitch, if desired.
        - If denied, a reason must be provided to the author.
        - If the editor takes too much time, the request is marked as **high priority** and must be processed before other pending requests.
    - ## Senior Editor Approval
        - A senior editor from the relevant genre committee must then approve the request.
        - This editor can request more information from the author, as well as information from any other editors that have approved the request, if desired.
        - This editor also has the ability to change the tentative title, tag line, or completion date.
            - If any of this information is changed, the author should be notified, and should have an opportunity to approve the changes or cancel the request.
        - If the editor takes too much time, the request should be marked as **high priority** and should be shown at the top of the list of pending requests, but this should not prevent other requests from being processed.
- # Completed Story Upload
    - Once the author's request has been approved, a completed draft of the story must be submitted for proofreading.
        - Depending on story type (length), the draft must be proofread and approved by a variable number of individuals.
        - Proofreaders can request that changes be made to the draft.
        - If changes are requested, the author should be notified, and the pitch will remain pending until an updated draft is submitted.
    - ## Proofreaders Based on Story Type (length)
        - **Articles:** Draft only needs approval from the Senior Editor
        - **Short Stories:** Draft must be approved by the Senior Editor, as well as one other editor from the relative genre committee.
        - **Novellas and Novels:** Draft must be approved by a majority of editors in the genre committee.
    - Drafts should only be viewable by the author and editors within the relevant genre committee, as well as the editor that is not in the committee that approved the pitch.
- # Miscellaneous
    - Editors can be in multiple genre committees.
    - A genre committee should have at least 3 editors and at least 1 senior editor, with a maximum of 2 senior editors per committee.

## Technology used
- Java
- JavaScript
- HTML
- CSS
- Hibernate
- PostgreSQL
- JDBC
- JUnit4
- Maven
- Postman
