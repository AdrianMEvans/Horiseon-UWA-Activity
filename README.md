# Horiseon-UWA-Activity

## Introduction
**Horiseon** is a Digital Marketing Agency and have launched a website containing the following sections:
1. Navigation Element with 3 links:
  * Link to _Search Engine Optimisation_ Section
  * Link to _Online Reputation Management_ Section
  * Link to _Social Media Marketing_ Section
2. Hero Section
  * This area contains a large image.
3. Main Element consisting of 3 Sections:
  * _Search Engine Optimisation_ Section
  * _Online Reputation Management_ Section
  * _Social Media Marketing_ Section
4. Aside Section
  * This lists 3 benefits of Digital Marketing in general.
5. Footer Section
  * This section contains some general footer and copyright information.

  ## Objectives
  **Horiseon** ("_Customer_") has identified a need to improve their current site. They feel that they are potentially losing out on many sales opportunities because their website does not comply with the latest accessibility standards to aid users with visual, audio or other disabilities to obtain easy access to their site.

  The customer has requested that the site meet the following minimum criteria for accessibility standards:
  1. Latest HTML Semantics to aid in identifying sections. 
  2. HTML elements must be placed in a logical order.
  3. Image elements must all have alt attributes to aid in identifying what is displayed.
  4. Headings should be in sequential order.
  5. Add a Concise and Descriptive title to the page.

  In addition it was also decided to investigate additional tools to test accesibility criteria and see what additional improvements could be put forward. Also to improve accesibility and page loading the HTML code will be inspected for any missing or broken links and the CSS for any potential improvements or consolidation.

  ## Execution

  ### _Customer Requirements_
  A new repository was created in Git Hub - [Horiseon Repository](https://github.com/AdrianMEvans/Horiseon-UWA-Activity.git). The Repository was then cloned to a folder on my harddrive. I added the customer's existing files and started with my initial commit. I subsequently made several changes to meet the 5 criteria set by the customer.
  - [x] Semantics were updated to latest HTML 5 naming conventions.
  - [x] HTML elements were placed in a logical order for accessibility.
  - [x] Alt Attributes were added to all images.
  - [x] Headings were placed in Sequential order
  - [x] Title of the page changed to consicely describe the customer business.

 ### _Additional implementations_ :punch::punch::punch:
 On inspection it was noted that the Navigation link to _Search Engine Optimisation_ Section were not functioning. It was found that the ID for that section was not inserted so it had no point for the reference. This was corrected.

 We also made use of an online evaluation tool to test our accesibility. [WAVE](https://wave.webaim.org/) is a suite of evaluation tools that helps authors make their web content more accessible to individuals with disabilities. WAVE can identify many accessibility and Web Content Accessibility Guideline (WCAG) errors, but also facilitates human evaluation of web content. See screenshot of the homepage of the tool below (as at 12 Nov 2020)

![Image of WAVE by WebAIM's homepage](https://github.com/AdrianMEvans/Horiseon-UWA-Activity/blob/main/assets/images/WAVE.jpg?raw=true)
 
 **We did an initial run with the tool and received a detailed list of errors, alerts and correct items.**

![Image of Detailed list of errors](https://github.com/AdrianMEvans/Horiseon-UWA-Activity/blob/main/assets/images/Wave-Errors-Details.jpg?raw=true)

**Below is a list and screengrabs illustrating the initial WAVE report with errors and alerts.**

1. ### Summary of Errors 
  * ![Image of Detailed list of errors](https://github.com/AdrianMEvans/Horiseon-UWA-Activity/blob/main/assets/images/Wave-Error-Summary.jpg?raw=true)
2. ### Structural Errors 
  * ![Image of Detailed list of errors](https://github.com/AdrianMEvans/Horiseon-UWA-Activity/blob/main/assets/images/Wave-Error-Structure.jpg?raw=true)
3. ### Contrast Error 
  * ![Image of Detailed list of errors](https://github.com/AdrianMEvans/Horiseon-UWA-Activity/blob/main/assets/images/Wave-Error-Contrast.jpg?raw=true)

We then implemented the customer requirements which sorted most of the issues identified by WAVE. We added a "back to top" button to each section for improved navigation for persons with disabilities. We also changed the aside element from the blue to a white background and then changed the text to match the blue of the main section. This fits in with the color scheme of the website while giving the aside element a seperate identity that is more accessible for users with disability. 

**Below is the list and screengrabs illustrating the WAVE report after customer criteria had been met and our suggested changes implemented.**

1. ### Summary of Errors Cleared
  * ![Image of Detailed list of errors](https://github.com/AdrianMEvans/Horiseon-UWA-Activity/blob/main/assets/images/Wave-Corrected-Summary.jpg?raw=true)
2. ### Structural Errors Cleared
  * ![Image of Detailed list of errors](https://github.com/AdrianMEvans/Horiseon-UWA-Activity/blob/main/assets/images/Wave-Corrected-Structure.jpg?raw=true)
3. ### Contrast Errors Cleared
  * ![Image of Detailed list of errors](https://github.com/AdrianMEvans/Horiseon-UWA-Activity/blob/main/assets/images/Wave-Corrected-Contrast.jpg?raw=true)

## Conclusion
This final outcome of the revisions is a site that looks virtually identical to the original site. The functionality has been improved and the site is now more accessible to users with disabilities. 

Please have a look at the **[new Horiseon site](https://adrianmevans.github.io/Horiseon-UWA-Activity/)** and let us know if there are any questions. We welcome constructive critisism and if you have any suggestions please contact us via the details below.

:bellhop_bell: 
Contact | Mobile | E-mail
------------ | ------------- | ------------
Adrian Evans | 0424 064 104 | adrian@polywhiz.com