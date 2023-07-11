# 1st IT Services
## About
This is a company page that provides different IT services in the field of SAP authorizations. They are present for more then 15 years and need a new website.
### Strategy
The main goal of this website is to provide future clients with information about the company and what company can offer. 
### Target
This is B2B business. Company is offering services for small, large business or big corporations. 
## User stories
1. As a first-time user, I want to be able to easily navigate through the website, so that I can find the content.
2. As a user, I want to know how to navigate through the page, so that I can easily explore the website.
3. As a user, I want to know how to navigate through the page, so that I can easily explore the website.</td>
4. As a user, I want to know what services the company is offering, so that I can see if they can help my company solve the problem.</td>
5. As a user, I want to know more about the company, so that I can see if I can trust them.</td>
6. As a user, I want to have an easy way to contact them, so that I can directly send the company a message.</td>
7. As a user, I want to see the company's email, phone, and address, so that I am sure there is a legit company behind.</td>
8. As a user, I want to see the company's email, phone, and address, so that I am sure there is a legit company behind.</td>
9. As a user, I want to see a thank you page once I submit the contact form, so that I know my message was received.</td>
10. As a user, I want to see the company's social media links, so that I can follow them there.</td>
## Design
### Inspiration
I took inspiration from company Institue VZ from Slovenia https://www.institut-vz.si/</p>
### Wireframe
The idea for the page was to create onepager. When user click on any of the menu item, user is scroll down to this page. The last wireframe just show how it will look like when user will scroll on the bottom of the page. Note that end design got changed a bit - map is moved above contact form because of visual reasons - looks nicer.
### Color palette
Colour palette is taken from the company current visual identity.
### Typography
Typography is taken from the company currenty typography. Used for headings and parahraphs - font Ubunto</p>
## Features
### Navigation
### Main
#### Services
#### About
#### Contact
##### Map
##### Contact Form
### Footer
### Thank you
### Impressum
## Testing
### Validator testing
HTML - no errors were retured when passing through the official W3C validator.
CSS - no errors were retured when passing through the official (Jigsaw) validator.
Accessibility - I confirm that the colours and fonts chosen are easy to read and accessible by running it through lighthouse in devtools. *NOTE - footer colour I needed to take a shade darker gray from the colour pallete because of accessibility reasons.
### Manual testing
      <th>ID</th>
      <th>User Action</th>
      <th>Expected Result</th>
      <th>Test Executed on desktop, tablet and mobile device</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>#1</td>
      <td>Click on logo</td>
      <td>Page reload and land on the landing page</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
    <tr>
      <td>#2</td>
      <td>Click on "Home" in the menu</td>
      <td>Page reload and land on the landing page</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
    <tr>
      <td>#3</td>
      <td>Click on "Services" in the menu</td>
      <td>Scroll down to "Services" page.</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
    <tr>
      <td>#4</td>
      <td>Click on "About"</td>
      <td>Scroll down to "About" page</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
    <tr>
      <tr>
      <td>#5</td>
      <td>Click on "Contact"</td>
      <td>Scroll down to "Contact" page</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
    </tr>
    <tr>
       <td>#6</td>
      <td>Click on plus and minus on the map</td>
      <td>Map zoom in and zoom out</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
    <tr>
       <td>#7</td>
      <td>Click on "Your name" input field.</td>
      <td>Input field get active, user can start typing</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
    <tr>
      <td>#8</td>
      <td>Click on "Email" input field</td>
      <td>Input field get active, user can start typing</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
    <tr>
      <td>#9</td>
      <td>Click on "Message" textarea field</td>
      <td>Textarea get active, user can start typing</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
     <tr>
      <td>#9</td>
      <td>User type name, email address and message in textarea and click on "Submit" CTA</td>
      <td>User is let to thank you page.</td>
       <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
     <tr>
      <td>#10</td>
      <td>Happy path: User type name in the input field, email address in the input field and message in textarea and click on "Submit" CTA</td>
      <td>User is let to thank you page.</td>
       <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
   <tr>
      <td>#11</td>
      <td>Unhappy path: user type invalid email address and tap on "Submit" CTA</td>
      <td>Error message appears stating @ is missing.</td>
     <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
     <tr>
      <td>#12</td>
      <td>Unhappy path: user type correct email address and message and tap on "Submit" CTA</td>
      <td>Error message appears that name is mandatory field.</td>
       <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
    <tr>
      <td>#13</td>
      <td>User hover over menu items</td>
      <td>Menu items change colour - only text</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
  <tr>
      <td>#14</td>
      <td>User click on legal page in footer</td>
      <td>Open new page with long text. Menu on top and footer on the bottom of the screen</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
     <tr>
      <td>#15</td>
      <td>User click on legal page in footer</td>
      <td>Open new page with long text. Menu on top and footer on the bottom of the screen</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
    <tr>
      <td>#16</td>
      <td>User click on Xing link in footer</td>
      <td>Open new page in new tap and land on Xing company page.</td>
      <td>Desktop: Y/N, Tablet: Y/N, Mobile: Y/N</td>
    </tr>
  </tbody>
</table>

<h1>Credits</h1>
<h3>Image source</h3>
<p>Image of a ceo taken from ceo image taken from the https://pixabay.com/photos/consulting-hiring-board-executive-4405260/</p>
<p>IMage of a hero image take from hero image was taken from: https://www.freepik.com/free-photos-vectors/pixel-hero</p>
<h3>Navigation</h3>
<p>For navigation I reuse the code that I found here https://codepen.io/tedib/pen/mdypQbg.</p>
<p>How to fix the nav position I found on this forum resource for this https://stackoverflow.com/questions/40772841/how-to-position-fixed-the-navbar-when-using-flexbox</p>
<h3>Hero image</h3>
<p>For hero image CSS I used styling from "Love Running project"</p>
<h3>Pages</h3>
All pages are styled with Flexbox and used the knowledge from these tutorials https://www.youtube.com/watch?v=hwbqquXww-U&list=PL4-IK0AVhVjMSb9c06AjRlTpvxL3otpUd&index=1
<h3>Footer</h3>
<p>Footer CSS style, I used the code from here https://materializecss.com/footer.html</p>
