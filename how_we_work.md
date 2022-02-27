# How we organize our work

## Types of information we deal with

### field project information
  - we develop specifications for field projects using either 
    - a google doc stored in the project's folder on the shared google drive
  - the project repository's readme should point to the project's google drive
  - after we have finished a field season we should also keep the most important files in the project's github repository.
  - those specs can be used for testing - remember that changes during the testing and development process must reflect back to the specs so that they are kept the single source of truth.
  - a dream: those specs can be handed out to members of those field projects so that they understand the workflow and conventions
  
### typical specs
  - workflow(s) in the field, lab, and post-season
  - reporting forms
    
### software documentation / user's manual
  - we keep dokuwiki for documentation for the time being
  - for the user's manual we will create a new, empty wiki
  - Lutz will still do some research on publishing documentation via GitHub Pages, but that mustn't keep us from working on it in the wiki.
  - documentation for developers will be kept in our main wiki for the time being.
  - new content for documentation comes from tickets that are labeled "user manual" or "developer manual". Remember, that those tickets are usually closed.
   
### tickets / issues
   - we use a single communal repository "arch-kiosk-office" for all software related tickets (including projects). That repo must be public so that issues can have more than one assignee.
   - Every field-project will have its own project; whenever a ticket is somehow specific to a project it should be added to that project (but still kept in the communal repo). We don't use labels anymore for that purpose. 
   - we'll keep project management a separate repository for issues related only to general management of the project (thinking about grants, finding collaborators, organizing workflows etc.)
   - Lutz is using a separate repo to keep tasks and files for research
   - project-management tickets that are related to a certain field project (e.g. a task like "schedule next meeting for ustp") must be assigned to that project and should be labeled "project-management" so that it is easier to filter them out of the normal ticket list. They may be kept in the project management repo if you remember it.

### files (samples, blueprints, logos)
  - field-project related files will be kept in the field folder on the shared google drive. Once a field season or certain milestone has been reached the most important files should also becopied to the repo.
  - ton of photos, stuff to look at temporarily etc. we keep whereever and get via whatever way a project prefers. We just need to keep the google drive clean and curated. The files in the google drive should be accompanied by a ticket that links them to the development or testing process.



