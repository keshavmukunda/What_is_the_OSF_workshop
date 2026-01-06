**What is the Open Science Framework (OSF)?**

OSF is a free online platform designed to help researchers manage any project (not just 'science') from ideas to sharing results.  Anyone can make an account. It is maintained by the Center for Open Science (cos.io) as a project management system to support collaboration and public accessibility, if needed.

**OSF is organized around 'projects':** for example, a lab, a working group, a large-scale project with several smaller experiments or components, or even simply an individual project. It's highly customizable.

Examples: a simple one is at <https://osf.io/n7263/> and a larger more complex one at <https://osf.io/ezcuj/>

**Project landing page** shows a list of contributors, date created and last updated, description of the project (as a wiki page), DOI, associated files, and smaller components (same structure as the parent project).

**Now let's create a project!** Start by creating an OSF account for yourself: sign up at <https://osf.io/>

**Create a project:** in the Home 'Dashboard', click  ![Create New Project](https://github.com/keshavmukunda/What_is_the_OSF_workshop/blob/main/create_new_project.jpg)

In the storage location options, select _Canada_ (for this workshop, I will create the project and add all of you as contributors).

![Contributors](https://github.com/keshavmukunda/What_is_the_OSF_workshop/blob/main/contributors.jpg) **Add contributors from the left-hand menu**: customize access levels (Administrator, Read+Write, Read) for different members of the project, for different components of the project.

![Add Contributor](https://github.com/keshavmukunda/What_is_the_OSF_workshop/blob/main/add_contributor.jpg) Search for other OSF users and add them; if they're not registered yet, add them by name and email. Checking the 'bibliographic contributors' option includes them in citations. 

(**Note** about 'view-only' links: if you're submitting a project or manuscript for anonymous peer-review, you can create a link to an anonymized _private_ version of your OSF project or individual components.)

**Choose a license (click 'Edit' in the 'Metadata' panel):** plenty of options, from _CC-BY_ to _GNU General Public License_ (or upload your own).

**Create a component (scroll down to the 'Components' panel):** similar to parent projects in terms of functionality. They can be nested, and you can make any number of components. Each component has a separate storage limit that is the same as any other component (see below).

**Wiki:** add content directly to OSF project using Markdown syntax. Collaborative editor so more than one person can add content simultaneously. Wiki also has version tracking.

**Files:** upload and store directly with OSF or use different storage add-ons (details below). OSF currently has a 5GB storage limit for private projects, and 50GB for public projects (this distinction is described later). Note: the OSF storage location cannot be changed after you've created a project, so select Canadian storage at the start (see 'Create a project' above). Plain text file types (e.g., `txt`, `R`, `py`) can be edited within OSF. Other proprietary formats (`docx` or `jpeg` for example) cannot be edited within OSF; use other storage 'add-ons' for these (see below). Versions are tracked by saving full files (not like Git)

**Add-ons (left-hand menu):** connect external storage, including large files stored elsewhere. This is a two-way interaction: file changes made in OSF will be mirrored in the external storage and vice versa. Select 'Additional Storage', find your option, and 'Connect'. You can link to individual folders, one folder for each OSF component. For multiple external folders, create an OSF component for each folder. Add-on contents in one component are not visible in other components. **Note that OSF is not appropriate for sensitive data**. OSF storage uses Google Cloud; data is encrypted by SSL during file transfer to OSF storage and is also encrypted at rest. The OneDrive add-on can't be linked (SFU ITS doesn't allow it :neutral_face:). You can also connect Zotero or Mendeley folders to include any references, but not the full-text files themselves.

**Other features:** OSF is private by default unless you choose to toggle the switch to 'Public Project'. ![Private to Public Project toggle](https://github.com/keshavmukunda/What_is_the_OSF_workshop/blob/main/private_public_project.jpg)

Different components (including nested components) can be public or private. Anything public is readable, and associated files are downloadable. You can get a DOI (in the ‘Metadata’ panel) for each project, component, or registration (see below) if you make it public. You also have the option to add a license to your project. 

Every item (files, components, etc.) in OSF has a unique identifier, and can be cited by others; most popular citation styles are displayed but others are available.

**Duplicate a project or component:**

![Duplicate Project](https://github.com/keshavmukunda/What_is_the_OSF_workshop/blob/main/duplicate_project.jpg)

‘Duplicate project (with files)’ creates a clone or ‘fork’ of the original project and all sub-components, including all files in OSF storage only (not files in the add-ons). You can see who has duplicated a project only if they make their project public (click ‘View duplicates’).

‘Duplicate project (structure only)’ creates a new project from the original structure and text, with no files or add-ons transferred. Example templates that may be useful: <https://help.osf.io/article/585-templates-getting-started-on-osf-faster-and-easier>

**Registration:** A public snapshot or fixed archive of your project at a specific moment in time, which could be cited. Registration of a project increases research accountability (e.g., hypothesis testing vs ‘p-hacking’). Registered version cannot be edited or deleted, but the original project can (if you withdraw a registration then the content is deleted but not the metadata). Create registrations for the same project at different times, and embargo a registered project for a length of time before it becomes public.


**Delete a project or component:** on the left menu, click 'Settings' and then  ![Delete project](https://github.com/keshavmukunda/What_is_the_OSF_workshop/blob/main/delete_project.jpg) 


This is an irreversible step, and also deletes all sub-components (but not anything above in the project hierarchy). Make sure you really want to do this! OSF makes you type a word or phrase to confirm.

**My profile:** under your name at the top right, change your profile information. Add your ORCID iD, GitHub, LinkedIn, X, Google Scholar info, etc. 

**Settings (left-hand menu):** in ‘Account Settings’, change your default storage location (country), change your password, set up two-factor authentication, or deactivate your account. 

**Where to get help?**  
OSF Guides at <http://help.osf.io/> or ask us at SFU Library, email [data-services@sfu.ca](mailto:data-services@sfu.ca)
