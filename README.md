# PWD

PWD is a sign up website for women to join a pilates class, it has some basic information on the classes that are taught and times and locations on where they are held. The website is targeted to women of all ages and aims to show women on when they can attend the classes. PWD also has specilaist classes with an option to sign up for them.

![PWD displayed on different devices][def4]

## Design Decisions
* The site uses a soft neutal colour scheme. This was chosen to entice the target audience to the site. Original colour schemes consited of pinks and baby blues. This was changed to not exclude any women who are not attracted to the traditionally more femanim colours. As the name suggests the site is for ALL women and the colours represent this.
* The site has a easy to navigate layout that allows the user to use intuitive descion making to guid their way around the pages. This simplicity encourages the audience to explore the page with confidence. 
* The pictures used are all of women to encourage the user excatly of the sites target audience. Each picture represents either the site or the lessons that are taught.

## features

* header
  * The header section houses the logo and picture of a pilates mat indicating to the user what that site is for pilates
  * On larger veiwports the header holds a informative box that shows the un-abbreviated name (Pilates For Women)
  * The top navigational links and logo are the same on every page on the website.
  * This section gives a clear visual for the user that the site is for women.

![header][def5]

* footer
  * the footer holds links to social media pages with icons to represent each website.
  * The footer is the same for every page. 
  * This section allows the user to easily access the social media accounts for the owner of the site.

![footer](assets/images/Screenshot%202022-12-30%20at%2023.42.57.png)

* What we offer section
  * the what we offer section holds three different session boxes with Two links.
  * Each box is titled with a session name.
  * the first session box is for all women which has a background image of a group of women all sat together.
  * the second session box is for pre/post natal women it has a background image of pregnant women.
  * the third session box is for a hot room pilates session it has a background image of a woman sweating.
  * this section allows the user to see the differnt sessions and have a brief visual of what they consist off.

![what we offer section][def6]

* About
  * The about me page holds three session boxes That have a brief summery on each session and why they can be benificial.
  * The session boxes have times and location of each session for the user.
  * Each session box has a background image relating to what each session is about.
  * This page is important for the user to have access to all of the right information.

![about page][def8]

* join
  * The join page has a form to allow users to sign up to the coresponding classes fill out the information boxes and send of the information.
  * The background image is off a woman rolling up a pilates mat.
  * The sign up form is easy to understand and fill out.

![signup form][def7]

* navigation
  * Shown at the top of the page, the PWD logo is a navigational link to the home page.
  * The three links stationed to the right hand side of the header all navigate to the corresponding pages (home, about and join)
  * All navigational link text will show as bold when hovered over.
  * All session boxes below the header have two navigational links (about and join).
  * The about navigation links in the session boxes will take the user to the specific session information on the about page.
  * All navigation is easy to understand gives a very clear information on what each link will do.

## Testing
* Tested the navigation bar on large and small (320px) screens to make sure the links are visible and work across all devices.
* Website is responsive, working on devices from small (320px) to large.
* The sign up form requires all boxes to be completed and the email box requires an email address.
* The contrast of the text on various backgrounds (images and background colours) is tested across all screen sizes.

## Validator testing

* html
  * No errors encountered (W3C Validator)
* css
  * No errors encountered (Jigsaw Validator)
* LightHouse test 
  * All colors and fonts are easy to read and understand (Chrome Lighthouse devtools)
  * The performace section comes back withe a low score of 43

![lighthouse test][def9]

## Bugs

* During testing a bug was dicovered. On mobile screen sizes the navigational links located at the top of the page would become unusable. To combat this I used the chrome devtools and used the element selctor tool, moved the sites demsions from the larger to smaller veiw ports. while scanning the site I found that the slogon box would cover the naviagtion selction. Despite visable on larger screens when the viewport was smaller is would become transparent, invisible, change position and cover the buttons. I fixed this bug by changing the demntions of the slogan box to 0 and the font size to 0 on smaller screen sizes.

## Deployment 

* The site was deployed to GitHub pages. The steps to deploy are as follows:
  * In the GitHub repository, navigate to the Settings tab.
  * Look to the Code and automation section on the left hand side and select pages.
  * In the build and deployment section change the branch to main.
  * Once you have pressed save the page link will appear below the Github Pages header.

The live link can be found here -  https://pacey2706.github.io/P-F-W/

## Credits 

### Contents 
* The footer  and sign up form was taken from [Love Running Project][def]
* Text for the about pages was generated from [Copymatic][def2]

### Media
* All images are from [Pexels][def3]


[def]: https://pacey2706.github.io/love-running/
[def2]: https://copymatic.ai/app/paragraph-generator/
[def3]: https://www.pexels.com/
[def4]: assets/images/Screenshot%202022-12-30%20at%2023.01.18.png
[def5]: assets/images/Screenshot%202022-12-30%20at%2023.41.39.png
[def6]: assets/images/Screenshot%202022-12-30%20at%2023.42.26.png
[def7]: assets/images/Screenshot%202022-12-30%20at%2023.44.13.png
[def8]: assets/images/Screenshot%202022-12-30%20at%2023.43.35.png
[def9]: assets/images/Screenshot%202022-12-30%20at%2023.47.01.png
