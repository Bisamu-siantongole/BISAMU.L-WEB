Q2.(1)  .<table>(with<thead>, <tbody>, <tfoot>, <tr>, <th>, <td>): contructing a multi-column pricing and logistics schedule required careful management of row and column alignment using purery HTML attributses without CSS styling.
.<form>: Coording multiple nested input types (text, email, tel, date, radio, checkbox, textarea) while maintaining semantic clarity and native browser validation required exact attribute binding.
.<details> and <summary>:Creating a fuctional, interactive Frequently Asked Questions (FAQ) accordion purely in HTML without using javascript proved challenging to structure cleanly.
.<picture> (with <source> and <img>): Implementating responsive image fallback logic using native HTML elements required proper mime-type and media query specifications directly in markup.

(2) .<header>: Encloses the Bisamu Logistics tittle, header logo, and primary site navigation.
.<nav>: Holds all internal jump links to core section (Servicces, Fleet, Tracking, Contact).
.<main>: Contians the central operational content of the website, isolating it from headers and footers.
.<section>: Categorizes distinct topic blocks as 'Abbout Bisamu ', 'Services Offered' and 'Track shipment'.
.<article>: Wraps standaone content units, such as individual logistics case studies and client testimonial.
.<aside>: Displays secondary contextual content including live fuel surcharge updates and driver safety.
.<footer>: Houses corporate copyright details, instructor metadata, and quick contact links.

(3) .The <section> element was the mmost useful for layout organization. It provide distinct logical boundaries for each major module of the Bisamu Logistics portal. This logical grouping allowed the document structure to remain clear, readable, and easy to navvigate even without CSS styling.

Q3. (1) .href (usd with <a>): Crucial for linking navigation items to internal section IDs and linking external resources.
.src (used with <img>, <video>, <audio>): Essential for embedding multimeedia fleet assets and company media into the website.
.type (used with <input>): Critical for defining form field behaviors (e.g., text, number, date, email, radio) and enforcing native HTML5 browser validations.

(2) .In Bisamu Logistics codebase, the id attribute was used as a unique anchor idetifier assigned to specific single elements on the page (e.g., id='tracking-section', id='contact-form'), allowing smooth jump navigation. The class attribute was applied to multiple recurring element sharing common structural charecteristics (e.g., class='service-card', class='btn-submit') to group semantic types together.

(3) .The placeholder attribute combined with required on form input filds improved user experience the most. It gave instant visual context on expected in formats (e.g., 'Enter tracking ID: BBSM-109283') and prevented incomplete form submissions through clint-side validation without needing javascript.

Q4. (1) Planning structure: prior to writing HTML, a visual wireframe treee was drawn on paper mapping out all 25 required HTML tags and 15 attributes across semantic sections (Header, Nav, Main, Sections, Tables, Forms, Footer).
(2) .Testing and Debugging: Testing was conducted locally across Google Chrome, Mozilla firefox, and Microsoft Edge. Validation was performed using the official W3C markup validation service to check for unclosed tags or syntax errors.
(3) .Challenges Overcome: Ensuring pure HTML interactivity without CSS styling was tough. Using semantic tags like <details>, <mark>, <fieldset>, and <legend> solved layout grouping and fuctional accordion requirement cleanly.

Q5. (1) Essential git commands used:
git init
git add index.html README.md
git commit -m 'fear: initial commit with semantic structure'
git remote add origin https: //github.com/[Bisamu-siantongole]/bisamu-logistics.git
git branch -m main
git push -u origin main

(2) .Commits and strategy: A total of 8 incremental commits were made. The strategy followed conventional commit guidelines (e.g., fear: add tracking form, docs: update README with assignment answers, fix: correct table nesting)

(3) .Importance of version control: Version control enables tracking changes, rolling back buggy revisions, maintaining project history, and collaborating smoothly with reviewers and instructors.

Q6. 
. validation: The code passed the W3C HTML validator with zero errors and zero warnings.
. Best practices: Proper tag indintation, lowercase tag/attribute naming, UTF-8 charset declaration, standard HTML5 doctype, and eplicit alt attribute on all images.
. Future improvements: if allowed, adding external CSS3 flexbox/grid styling and javascript for dynamic tracking lookup fuctionality.