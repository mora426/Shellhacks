# Shellhacks
4 Projects: StateFarm, Vanguard, Cafe Cultura, Google

**State_Farm**
*Making Insurance Easy*
Hey students! Want to change how insurance works? Check out our State Farm hackathon challenge! We're looking for your cool ideas to make insurance easier. Imagine making insurance claims simple or getting tips on your phone or desktop to stay safe. Your job is to make a hack that makes insurance simple and helpful for students like you. Be part of reinventing insurance for young people. Your hack could make a big difference! Let's make insurance easy and smart together with State Farm!


**Vanguard**
Take a stand for all communities. Hack on any topic that you’re passionate about which impacts minority communities.

*Potential Ideas:*

- Increasing Financial Literacy
- Access to Educational Resources (Pre-K, K-12, Post-Secondary, ESL)
- Healthy Dietary Options


**Cafe_Cultura**
*Latine' Heritage Month Digital Divide Challenge*
In celebration of Latine Heritage Month, we would like to challenge the Shellhacks community to design a product that connects Latine' community to each other using new technology. For example, you may want to connect Latine' small businesses to consumers with similar backgrounds who may be  looking their services. Feel free to get creative and think about ways we can close the digital divide in Latine' communities.

Your Product may be B2B, B2C or B2B2C.


**Google**
Google has many products and services including Search, Gmail, Maps, Cloud, Chrome, YouTube, Android, Meet, Nest, Pixel, and more. But did you know Google has a philanthropic organization, http://google.org/? The non-profit's mission is to apply Google's innovation, research, and resources to promote progress and expand opportunity for everyone. With that mission in mind, **implement any tool (website, an app, an API, or a medium of your choice) that promotes social good.**



**Code Templates** 
SADGRL: https://goblin-heart.net/sadgrl/projects/layout-builder/
SADGRL AGAIN: https://goblin-heart.net/sadgrl/webmastery/layouts/
RIBO: https://ribo.zone/free/layouts/
Repth: https://repth.neocities.org/theme

**Creds to Sadgrl’s layout builder**
        <div id="container"><div id="header" style="height: 253px;"></div>
            <div id="headerArea">
                
                <nav id="navbar" style="margin-bottom: 0px;">
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                        <li><a href="#">Link</a></li>
                    </ul>
                </nav>
            </div>

            <div id="flex">
                <aside id="leftSidebar" style="margin-right: 0px;">
                    <h2>Updates</h2>
                    <div class="box">
                        <p>I have recently updated this tool as of August 2022!</p>
                        <ul style="padding-left:10px;">
                            <li>Rewrote the JS to generate cleaner code</li>
                            <li>Rewrote the CSS in a way that hopefully makes much more sense to edit</li>
                            <li>Added a couple of new features!</li>
                            <li>Old version is still available <a href="old.html" target="_blank">here</a></li>
                        </ul>
                    </div>
                    <h2>Hi there!</h2>
                    <h3>Other Tools</h3>
                    <ul>
                        <li><a href="https://sadgrlonline.github.io/html-cheatsheet/" target="_blank">HTML Cheatsheet</a>
                        </li><li><a href="/sadgrl/webmastery/webmaster-links.html" target="_blank">Webmaster Links</a></li>
                        <li><a href="/sadgrl/webmastery/downloads/tiledbgs.html" target="_blank">Tiled BGs</a></li>
                        <li><a href="/sadgrl/webmastery/downloads/fonts.html" target="_blank">Fonts</a></li>
                        <li><a href="/sadgrl/projects/ideas/" target="_blank">Site Ideas</a></li>
                    </ul>
                </aside>
                <main>
                    <h1>Welcome to my Layout Maker!</h1>
                    <p><strong>Please read this first!</strong></p>
                    <p>This tool generates a layout that is responsive, which means it looks great on phones! Use dropdowns above to customize your layout's general features. Click the button to generate your HTML and CSS, and paste it into a file on Neocities.</p>
                    <p>Then you can replace all of the text with your own. For more customization, the CSS code has comments to explain what each part changes. Please read through the code - even if you have no idea what it means.</p>
                    <p>If you're feeling up for a challenge, I put together <a href="/sadgrl/learn/understanding-tweaking-my-layout-maker/" target="_blank">a guide</a> which goes over the structure of how this layout is built, along with some specific tips on how to edit it in certain ways.</p>
                    <p>Check the links in the sidebar for more resources to build your own website!</p>

                    <p> - Cat Ipsum - </p>
                    <p>Rub my belly hiss swipe at owner's legs sniff catnip and act crazy growl at dogs in my sleep sit on the laptop for hiss at vacuum cleaner i like to spend my days sleeping and eating fishes that my human fished for me.</p>

                    <p>Head nudges eat my own ears. Hey! you there, with the hands why can't i catch that stupid red dot, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff, or roll over and sun my belly curl up and sleep on the freshly laundered towels.</p>


                </main>
                
            </div>
            <footer id="footer" style="margin-top: 0px;">CC0 Public Domain, 2022</footer>
        </div>
        <!-- THIS IS THE CSS !-->
        <style>
            /* user styles */

            /* styles are what change the color and sizes of stuff on your site. */

            /* these are variables that are being used in the code
    these tended to confuse some people, so I only kept 
    the images as variables */

            :root {
                --header-image: url('https://sadhost.neocities.org/images/layouts/wp.jpeg');
                --body-bg-image: url('https://sadhost.neocities.org/images/tiles/purplesky.gif');

                /* colors */
                --content: #43256E;
            }

            /* if you have the URL of a font, you can set it below */
            /* feel free to delete this if it's not your vibe */

            /* this seems like a lot for just one font and I would have to agree 
    but I wanted to include an example of how to include a custom font.
    If you download a font file you can upload it onto your Neocities
    and then link it! Many fonts have separate files for each style
    (bold, italic, etc. T_T) which is why there are so many!
    
    */

            @font-face {
                font-family: Nunito;
                src: url('https://sadhost.neocities.org/fonts/Nunito-Regular.ttf');
            }

            @font-face {
                font-family: Nunito;
                src: url('https://sadhost.neocities.org/fonts/Nunito-Bold.ttf');
                font-weight: bold;
            }

            @font-face {
                font-family: Nunito;
                src: url('https://sadhost.neocities.org/fonts/Nunito-Italic.ttf');
                font-style: italic;
            }

            @font-face {
                font-family: Nunito;
                src: url('https://sadhost.neocities.org/fonts/Nunito-BoldItalic.ttf');
                font-style: italic;
                font-weight: bold;
            }

            body {
                font-family: 'Nunito', sans-serif;
                margin: 0;
                background-color: #08031A;
                /* you can delete the line below if you'd prefer to not use an image */
                background-size: 65px;
                color: #fceaff;
                background-image: var(--body-bg-image);
            }

            * {
                box-sizing: border-box;
            }

            /* below this line is CSS for the layout */

            /* this is a CSS comment
    to uncomment a line of CSS, remove the * and the /
    before and after the text */


            /* the "container" is what wraps your entire website */
            /* if you want something (like the header) to be Wider than
    the other elements, you will need to move that div outside
    of the container */
            #container {
                max-width: 900px;
                /* this is the width of your layout! */
                /* if you change the above value, scroll to the bottom
      and change the media query according to the comment! */
                margin: 0 auto;
                /* this centers the entire page */
            }

            /* the area below is for all links on your page
    EXCEPT for the navigation */
            #container a {
                color: #ED64F5;
                font-weight: bold;
                /* if you want to remove the underline
      you can add a line below here that says:
      text-decoration:none; */
            }

            #header {
                width: 100%;
                background-color: #5e4e8c;
                /* header color here! */
                height: 150px;
                /* this is only for a background image! */
                /* if you want to put images IN the header, 
      you can add them directly to the <div id="header"></div> element! */
                background-image: var(--header-image);
                background-size: 100%;
            }

            /* navigation section!! */
            #navbar {
                height: 40px;
                background-color: #13092D;
                /* navbar color */
                width: 100%;
            }

            #navbar ul {
                display: flex;
                padding: 0;
                margin: 0;
                list-style-type: none;
                justify-content: space-evenly;
            }

            #navbar li {
                padding-top: 10px;
            }

            /* navigation links*/
            #navbar li a {
                color: #ED64F5;
                /* navbar text color */
                font-weight: 800;
                text-decoration: none;
                /* this removes the underline */
            }

            /* navigation link when a link is hovered over */
            #navbar li a:hover {
                color: #a49cba;
                text-decoration: underline;
            }

            #flex {
                display: flex;
            }

            /* this colors BOTH sidebars
    if you want to style them separately,
    create styles for #leftSidebar and #rightSidebar */
            aside {
                background-color: #241445;
                width: 200px;
                padding: 20px;
                font-size: smaller;
                /* this makes the sidebar text slightly smaller */
            }


            /* this is the color of the main content area,
    between the sidebars! */
            main {
                background-color: #43256E;
                flex: 1;
                padding: 20px;
                order: 2;
            }

            /* what's this "order" stuff about??
    allow me to explain!
    if you're using both sidebars, the "order" value
    tells the CSS the order in which to display them.
    left sidebar is 1, content is 2, and right sidebar is 3! */

            */ #leftSidebar {
                order: 1;
            }

            #rightSidebar {
                order: 3;
            }

            footer {
                background-color: #13092D;
                /* background color for footer */
                width: 100%;
                height: 40px;
                padding: 10px;
                text-align: center;
                /* this centers the footer text */
            }

            h1,
            h2,
            h3 {
                color: #ED64F5;
            }

            h1 {
                font-size: 25px;
            }

            strong {
                /* this styles bold text */
                color: #ED64F5;
            }

            /* this is just a cool box, it's the darker colored one */
            .box {
                background-color: #13092D;
                border: 1px solid #ED64F5;
                padding: 10px;
            }

            /* CSS for extras */

            #topBar {
                width: 100%;
                height: 30px;
                padding: 10px;
                font-size: smaller;
                background-color: #13092D;
            }


            /* BELOW THIS POINT IS MEDIA QUERY */

            /* so you wanna change the width of your page? 
    by default, the container width is 900px.
    in order to keep things responsive, take your new height,
    and then subtrack it by 100. use this new number as the 
    "max-width" value below
    */

            @media only screen and (max-width: 800px) {
                #flex {
                    flex-wrap: wrap;
                }

                aside {
                    width: 100%;
                }

                /* the order of the items is adjusted here for responsiveness!
      since the sidebars would be too small on a mobile device.
      feel free to play around with the order!
      */
                main {
                    order: 1;
                }

                #leftSidebar {
                    order: 2;
                }

                #rightSidebar {
                    order: 3;
                }

                #navbar ul {
                    flex-wrap: wrap;
                }
            }
        </style>

   







