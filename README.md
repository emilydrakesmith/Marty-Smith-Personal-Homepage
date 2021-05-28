<a id='top'></a>

# Introduction
My personal homepage.  Welcome!

This is the first webpage I ever built and as such it consists of static HTML, CSS, and no scripts whatsoever.  In the future I plan to completely rebuild this content into a 2.0 version with either `Next.js` or `Gatsby`, but until I have the time it will remain a static HTML page.

# Table of Contents

1. [Version Notes](#version-notes)
2. [Tech Framework](#tech-framework)
3. [Future Plans](#future-plans)
4. [Contribute](#contribute)
5. [Special Thanks](#contribute)

[Back to Page Top](#top)
<a id='version-notes'></a>

# Version Notes

The version of my website currently live is **1.0.7**.  In cases where I update the README without any updates to the website itself I do not update the version number or use branches for my work.  Each version number will lack a commit number until the next version is uploaded.  The commit number is always added retroactively as it's generated at the time that I commit the project to the host.  In general, for version number format X.Y.Z:
* X: increases in this number represent a complete overhaul of some section of the website or source code
* Y: increases in this number represent a major functional change/aesthetic change to the website
* Z: increases in this number represent changes that are relatively minor but still warrant a new commit

Please note that I have made significant updates to how I record version notes since the initial build of this website in September 2020.  Version notes for commits prior to May 2021 were largely build from limited information available via `git log` and are not comprehensive.

#### v 0.0.1 | 15 Sept 2020 | commit e58db13c65dc7b4e0396aab7dc81a7f36e061a9e | Initial Commit
* Initial Commit.

#### v 0.0.2 | 15 Sept 2020 | commit 1bd616e25d492f0d2cb051830bccac9202752e5e
* Imported *Manrope* font from Google Fonts.

#### v 0.0.2 | 15 Sept 2020 | commit 4d79e46ef5dc679f7cb961fbd54a3f6e5f6383fa
* Added a custom favicon.

#### v 1.0.0 | 15 Sept 2020 | commit 4d3d985e7a466ed809c7ef866d439017422104ec
* First uploaded version at MVP.

#### v 1.0.0.1 | 15 Sept 2020 | commit d73e0aae1c9faf1ddd1262ee56f36af67000224e
* Uploaded `style.css` to the repo as this was somehow missed in the v 1.0.0 commit.

#### v 1.0.1 | 15 Sept 2020 | commit a2f42f3f4e805c1fc6b8b4110c2e89a30f52a79f
* Created `CNAME` file to have site hosted at the martysmith.tech URL.

#### v 1.0.2 | 16 Sept 2020 | commit d41ba1dc691563a3e76e1b08f4a303ed51a76057
* Linked scripts for Google Analytics.

#### v 1.0.3 | 16 Sept 2020 | commit 3aef48a28fc1683507721e67971e668ff39eeea6
* Various updates to `index.html` data.

#### v 1.0.4 | 16 Sept 2020 | commit 27088ae97719c125054f3b01cd186c632b64dd41
* Updated HTML on anchor tags to open external links in new tabs.

#### v 1.0.4.1 | 16 Sept 2020 | commit e412e676ab650472e1eaa1f5effe883fd07fa211
* Fixed a syntax error in the previous commit.

#### v 1.0.5 | 17 Sept 2020 | commit 04656f72e677756b78a4189e5726daf452a1fe2b
* Added a Twitter link in the `Contact Me` section.

#### v 1.0.5.1 | 17 Sept 2020 | commit 04ffc4abf352a6c89209c40d0bc9eda97436a390
* Uploaded Twitter logo to accompany the link.

#### v 1.0.5.2 | 17 Sept 2020 | commit b6978cc74fbfba4897f1f46f55ebc923d0c3bc57
* Created CSS to replace the Twitter `<li>` bullet point with the Twitter logo.
* Minor changes to personal information to improve readability.

#### v 1.0.6 | 24 Sept 2020 | commit 265b39f09e37c26f3c071c26a799becf131136e9
* Wrote out the initial build of this `README.md` file.

#### v 1.0.7 | 24 Sept 2020 | commit d7ca429393518a8cafeadcb716638abf9dcfad51
* Created additional sections in `index.html` and `style.css` for more content.

#### v 1.0.8 | 24 Sept 2020 | commit a2ad6b8a071b89f478318b08c8aa33eb2c55b0d0
* Completed mobile formatting for `<header>` section.

#### v 1.0.8.1 | 24 Sept 2020 | commit 11d08ae33728d3da7cf1a20e0b8beb8bde3719b0
* Completed mobile formatting for `<footer>` section.

#### v 1.1.0 | 25 Sept 2020 | commit 13b3b1950e2d2fb59460520dc6511d0f10941ed6
* This version will reformat the site layout using Flexbox and a mobile-first design.
* Added `"initial-scale=1"` to HEAD for better scaling on different devices.
* Added `lang='en'` attribute to the `<HTML>` tag.
* Updated `README.md` for better use of markdown formatting.
* Updated page title to include *Software Engineer*.
* Added page-section navigation links to `<header>`.
* Changed `<footer>` text from `<h3>` to `<p>` and updated CSS accordingly.
* Added a *Portfolio* section with placeholder content.  Will later be replaced with samples of my work.
* Added a contact form to *Contact* section.
* Added Google Maps Columbia, SC to *Contact* section.
* Added a contact form to *Contact* section.
* Moved basic personal information from *About Me* to *Introduction*.
* Removed `<hr>` elements, now using differential background color for visible seaparation of sections.

#### v 1.1.1 | 26 Sept 2020 | commit c1cc25dcfa302c29006f4d81288e9addf8b83254
* Minor edits to appease Thinkful grading staff.

#### v 1.1.1 | 05 Oct 2020 | commit f502e98ace4db10c67caec024189fd5060155f34
* Additional minor edits to appease Thinkful grading staff who really need to chill.
* Said edits will be reverted after they approve this project because they're stupid.

#### v 1.0.2 | 25 May 2021 | commit 41f88f205314cac7025a9a13a393fce7be0bf51b
* Fix syntax errors in `style.css` which oddly weren't breaking anything.
* Update portfolio with information about and links to ScriptStud.io.
* Add technologies and other proficiencies to the *About Marty* section.
* Various minor edits for spelling, grammar, etc.

#### v 1.0.3 | 26 May 2021 | commit 2500cf2cfce59d2962ecf8dc9baa19fe93211c4f
* Built out `Version Notes` section of this `README.md` using commit notes accessed via `git log` in the CLI.
  * With the exception of commits `13b3b1950e2d2fb59460520dc6511d0f10941ed6` and `41f88f205314cac7025a9a13a393fce7be0bf51b`, all commits prior to this were written from `git log` records and were not made contemporarily.  They should be considered limited in scope and not all-inclusive of changed/additions that commit represents.
* Added a *Table of Contents* section to this `README.md` file.
* Added *Back to Page Top* links to section footers in this `README.md` file.

#### v 1.0.4 | 26 May 2021 | commit 7c98e1f14db2d3c0374c46837a1a852a77e8a8c7
* Minor formatting changes to old version notes in `README.md` for stylistic consistency.
* Removed link to `scripts.js` from bottom of `index.html` file.  I don't have any scripts presently and it was throwing errors.
* Text for Portfolio Item #2 is now left-justified.
* Fixed bug with unequal image sizing for portfolio items.  However, they no longer dynamically resize; need to fix this later.

#### v 1.0.5 | 27 May 2021 | commit fa23c253e1ebfc03579a0adc38c9a5c73953afae
* Changed stylying on *Version Control* sub-headers in `README.md` from boldface (`**[Content]**`) to `h4` (`#### [Content]`).
* Added *Job Hound* to the *Portfolio* section of the webpage.

#### v 1.0.6 | 27 May 2021 | commit 80b6d901e32bebb7a811f5fe92b01fde67b6e53d
* Added *SoQuiz.me* to the *Portfolio* section of the webpage.

#### v 1.0.6.1 | 28 May 2021 | commit 97007e970161445e33ab531a45987cd2c328129a
* Updated preview image for *Job Hound* to reflect new styling on the app.
* Fixed filepath error with *Job Hound* preview image.

#### v 1.0.7 | 28 May 2021 | commit TBD | Current Version
* Added *Tic Tac Toe* to the *Portfolio* section of the webpage.
* Added `target='_blank'` attribute to several `<a>` hyperlinks it was missing from.

[Back to Page Top](#top)
<a id='tech-framework'></a>

# Tech Framework

**This app uses:**
* HTML5 and CSS3
* JavaScript ES6

**I built this app using:**
* [VSCode](https://code.visualstudio.com/) 1.49.2
* Chrome 85 (for display and DevTools)
* [Git-Bash](https://git-scm.com/) 2.28.0.1
* [GitHub](https://github.com/) (online portal, not desktop)
* Windows 10 Pro v1909

**This app is stored at:**
* [GitHub Repo](https://github.com/mhsmith321/Marty-Smith-Personal-Homepage)
* Primary Domain: https://martysmith.tech/
* Other domains I control: https://martysmith.dev/
                           https://martysmith.io/
                           https://martysmith.cloud/
                           https://martysmith.co/

For an easy time reading the code files I recommend using a text editor wrapping at no less than 160 characters.

[Back to Page Top](#top)
<a id='future-plans'></a>

# Future Plans
### Major
* Rebuild website from the ground up, likely using Gatsby.
* Utilize a dark scheme with higher-contract color choices.

### Minor
* Alter `.git` repo to use a `main` rather than a `master` branch.
* Wrap text around & below an image as screen size changes.
* Replace social media text links with graphics.
* I can clean up the CSS a lot by using more `<div>` containers and `id` attribute tags.
* Make different sections of the website switch to desktop variants at different widths.
* Make portfolio images resize dynamically based on parent-container width.
* Lock header at top of screen.
* Style portfolio items and *image-right* and *image-left* instead of by `id` attribute.

[Back to Page Top](#top)
<a id='contribute'></a>

# Contribute

Although I'm always interested in meeting new collaborators I prefer to keep this an individual project as a skills demonstrator.

I'm happy to let anyone reuse my code so long as you contact me for advance permission and give attribution where appropriate.

If you'd like to learn more about the developer, please reference my digital footprint:
* [My Website](https://martysmith.tech/) (ie the site this `README.md` file references)
* [GitHub Profile](https://github.com/mhsmith321)
* [LinkedIn](https://www.linkedin.com/in/the-marty-smith/)

[Back to Page Top](#top)
<a id='special-thanks'></a>

# Special Thanks

* General Assembly for giving me the education and support to build and deploy this site.
* In particular, my instructors: Ben Manley, David Stinson, and Shahzad Khan.
* Colors were found through use of the [Coolors Color Scheme Generator](https://coolors.co/).
* Generating a mobile-first responsive web app was much easier using the [Multi-Screen Test Tool](http://whatismyscreenresolution.net/multi-screen-test) at [WhatIsMyScreenResolution](http://whatismyscreenresolution.net/).
* Placeholder text was provided free by [Bacon Ipsum](https://baconipsum.com/)
* Thanks to the creators of the font [Manrope](https://github.com/sharanda/manrope)
* Created my favicon for free with the help of [favicon.io](https://favicon.io/)
* Additional sources I consulted for troubleshooting include [Stack Overflow](https://stackoverflow.com/), [W3Schools](https://www.w3schools.com/), [Codecademy](https://www.codecademy.com/learn), [CSS-Tricks](https://css-tricks.com/), and of course [Google](https://www.google.com/).
* Jennifer and Natalie Smith (the programmer's wife and mother, respectively) provided moral support and beta testing.

[Back to Page Top](#top)