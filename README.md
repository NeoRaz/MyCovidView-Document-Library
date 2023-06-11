# MyCovidView Document Library
The Document Library is designated to store Project Plans, SQA Plans, Testing Plans, and other related documents.

Only authorized members of the project team, including the project manager, quality assurance lead, and designated document owners, have the permission to change any document in the Document Library. These authorized members can create new documents, make edits to existing documents, and delete outdated or irrelevant documents as necessary. This approach allows for efficient collaboration and ensures that the document content remains up to date.

The decision to restrict access to the Document Library is based on the importance of maintaining version control and traceability for critical project documentation. By limiting access to authorized members, we can minimize the risk of accidental changes or unauthorized modifications. Additionally, this control measure enables us to track and assign responsibility for any changes made to the documents, which is crucial for compliance and audit purposes.


#Flow of documenting

Add the Document to the Repository:
Navigate to the desired location within the repository where the document should be stored.
Upload the .doc file to the repository using the "Add file" or "Upload files" feature on GitHub.
Provide a meaningful and descriptive filename for the document.

Collaborate and Review:
Share the document's GitHub repository link with the team members involved.
Encourage team members to review and provide feedback on the document.
Utilize GitHub's collaboration features such as pull requests, comments, and issue tracking to facilitate discussions and revisions.

Document Version Control:
Consider using Git branches to manage different versions or variations of the document.
Encourage team members to make edits and updates on separate branches.
Merge approved changes into the main branch to maintain an up-to-date version.

Document Approval and Finalization:
Establish a process for document approval, such as requiring a certain number of team members to review and sign off on the document.
Once approved, make any necessary final edits or revisions to the document.
Update the document's version number and date to reflect the final version.

Document Access and Distribution:
Determine who should have access to the document repository.
Set appropriate permissions and access levels for team members.
Share the repository link or document file with relevant stakeholders or external parties as needed.

Document Maintenance:
Regularly review and update the document as required.
Utilize GitHub's version control capabilities to track changes and document the revision history.
Communicate any updates or changes to the team members who need to be aware of them.



#Tags

In Git, it is possible to tag a repository at any moment. A tag is simply a reference to the repository at a certain point in time, with a label. You can list all tags that are present in a repository and easily revert to the point in time the tag was made. GitHub even shows all tags in a drop down menu on the website, so browsing the repository at the time a tag was created is easy. We use this feature to tag the repository whenever a new version of a CI is created.

The repository project-docs will only contain documentation and thus only tags of the form [title abbreviation]-[version];
