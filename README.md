Download Link: https://assignmentchef.com/product/solved-web322-assignment-1
<br>
In this assignment, you will <strong>ONLY</strong> focus on building views for your website/web application. <strong>No database connectivity is required for Assignment 1.</strong>




<table width="602">

 <tbody>

  <tr>

   <td width="602">REMINDER:All back-end functionality <strong>MUST </strong>be done using <strong>Node JS and Express</strong>.Your views <strong>MUST</strong> be created with <strong>Express-Handlebars</strong> </td>

  </tr>

 </tbody>

</table>







Specifically, you are<strong> ONLY </strong>required to implement the following:

<strong> </strong>

<h1>Features</h1>

<h1></h1>

<h1>Express web server set up</h1>




Create an Express web server that listens to incoming HTTP requests.




<h1>Route Handlers Implementation</h1>




Ensure that you create route handlers that will direct users to specific views when they navigate to the following routes:

<ul>

 <li>Home</li>

 <li>Meals Package Page</li>

 <li>Customer Registration</li>

 <li>Login</li>

</ul>




<h2>Home Page</h2>




You are required to build a <strong>well-designed</strong> home page that consists of the following sections:




<ul>

 <li><strong>Header – </strong>The header <strong>MUST</strong> contain the logo of your website and could contain the navigation bar and any other content you deem necessary.</li>

</ul>




<ul>

 <li><strong>A Navigation bar</strong> – The navigation bar can be within the header or defined as an entirely new area. It <strong>MUST </strong>have links that navigate visitors to a sign-up page and the login page. Please note, <strong>instead of creating a separate page for the sign-up page and the login page, you can render it as modal pop-up boxes</strong>.</li>

</ul>




<ul>

 <li><strong>A Hero Section</strong>– The section must have a prominent image or video element that is placed at the top of your pages, below the header and navigation section. Example:</li>

</ul>




<strong>Figure 1.1</strong>




<ul>

 <li><strong>Content Section(s) </strong>– The sections <strong>MUST </strong>use a combination of grids, words, headings, and images with the sole purpose of highlighting some selling features of the website and the stellar service that they provide. See the below example:</li>

</ul>




<strong>Figure 1.2</strong>




<ul>

 <li> – This section must display at least four (4) top meal packages, as shown in figure 1.3. Please note, for this Assignment, Assignment 1, the data for this section must be static, i.e. it will not be pulled from a database. However, you are required to define the data in a separate module (JavaScript file). Each meal package must display an image, title, price.</li>

</ul>




<strong>Figure 1.3</strong>




<ul>

 <li>Footer – This section <strong>must </strong>include footer menu items, social media links, and any other information you deem necessary.</li>

</ul>




<h2>Meal Package Listing page</h2>




You are required to build a <strong>well-designed</strong> meal package listing page. This page must have at least <strong>4 sample meal packages</strong><strong> within a 4 column grid layout,</strong> as shown in the below image:




<strong><u> </u></strong>

<strong><u>Figure 1.4</u></strong>

<strong>Note, every meal package must have an image, title, price, food category, number of meals in the package, synopsis of the content within the meals and a boolean attribute indicating if it is a top package or not. </strong>This view must also have a header, navigation, hero section, and footer like the home page.




Like the Top Meal Package section, for this Assignment, Assignment 1, the data for this section must be static, i.e. it will not be pulled from a database. However, you are required to define the data in a separate module (JavaScript file).

<u> </u>

Please be advised, you must create one separate module file to encapsulate all the static data “fake database data” for the Meal Package Listing page, and for the Top listing. This module/JavaScript file is going to represent the Model for your MVC application.

<h2></h2>

<h2></h2>

<h2>Registration Page</h2>




You are required to build a <strong>well-designed</strong> user registration form as shown in<strong><u> Figure1.5</u></strong> . This can be implemented as an entirely new page or as a pop-up modal. In the event you implement this as a new page then you must ensure that the page maintains consistency regarding its structure, header, nav, hero section, footer, and etc as the home page.




<strong><u>Figure 1.5</u></strong>




<h2></h2>







<h2></h2>

<h2></h2>

<h2>Login Page</h2>




You are required to build a <strong>well-designed</strong> login form as shown in<strong><u> Figure1.6</u></strong> . This can be implemented as an entirely new page or as a pop-up modal. In the event you implement this as a new page then you must ensure that the page maintains consistency regarding its structure, header, nav, footer, and etc as the home page.

<strong><u>Figure1.6</u></strong>







Reminder: All back-end functionality <strong>MUST </strong>be done using <strong>Node JS and Express</strong>.

Your views <strong>MUST</strong> be created with <strong>Express-Handlebars</strong><strong>.  You must create one Model (JavaScript file) </strong>to encapsulate the static data (“fake database data”) for the<strong> Meal Package Listing Page, and the Top Meal Package section</strong> located on the home page<strong>.</strong>