<h1 id="budgetTracker">💰 Budget-Tracker 💰</h1>


<p>Taking a pre-existing budget tracking application, and converting it to a PWA for offline access, and functionality.</p>

<h2>Usage 👨‍🏭</h2>


<p>This is a simple budget tracker application that did not have a deployed URL. After recieving the application, I turned this into a Progressive Web Application (PWA), and created offline functionality and data persistence. For more on PWA's google has a great training <a href="https://developers.google.com/web/ilt/pwa/introduction-to-progressive-web-app-architectures">documentation</a>.</p>


<p>When you go to the deployed application page, input a transaction title and create an expense or a deposit. If you have no internet connection, the data will still persist. The service worker allows for interactivity with the page with no loss of functionality or style. You can visit Web Fundamentals for more information on <a href="https://developers.google.com/web/fundamentals/primers/service-workers">Service Workers</a> (article by: <a href="https://developers.google.com/web/resources/contributors/mattgaunt">Matt Gaunt</a>). The data is stored and then delivered to the MongoDB database when online capabilities return through a Web Storage API technology <a href="https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API">IndexDB</a>.<p>


<h2>Deployment 🛩️</h2>

<p>You can view the live deployment of the application on Heroku at the following URL:</p>

```sh
<a href="https://ancient-thicket-04760.herokuapp.com/">https://ancient-thicket-04760.herokuapp.com/</a>
```

<p>The data is persistant through the MongoDB Atlas cloud (AWS) server.</p>

<h2>Built With 🛠️</h2>

<ul>
<li><strong>Compression</strong></li>
<li><strong>Morgan</strong></li>
<li><strong>JSON</strong></li>
<li><strong>IndexDB</strong></li>
<li><strong>CSS</strong></li>
<li><strong>JavaScript</strong></li>
<li><strong>Node.js</strong></li>
<li><strong>Express.js</strong></li>
<li><strong>Mongoose.js</strong></li>
<li><strong>MongoDB</strong></li>
<li><strong>Markdown</strong> (README.md)</li>
<li><strong>HTML</strong></li>
</ul>

<p>&nbsp</p>

<h2 id="author">Author 👋</h2>

**John Patrick Banas**

- [GitHub Profile 🖥️](https://github.com/JohnBanas)
- [Email 📧](mailto:jbanas9124@gmail.com)
- [Portfolio 💼](https://johnbanas.github.io/portfolio/)

<p>&nbsp</p>

<h2 id="contribute">Contributions 💚</h2>

<h3>Starter Code</h3>

<p>Application starter code:</p>

- [https://github.com/coding-boot-camp/symmetrical-bassoon](https://github.com/coding-boot-camp/symmetrical-bassoon)
- by: [The Coding Bootcamp](https://github.com/coding-boot-camp)

<p>None of this would be possible without the love and support of my wife Sam and our dog Teddy. Thank you to my nephew Mitchell for letting me help him with his homework, and discover that I actually love computer science, I just never knew. The wonderful folks at the Vanderbilt Owen School of Engineering Bootcamp. All the Instructors, TA's, Graders, Tutors, and Admin team who made my journey possible. Also to all the coders out there who teach me something new everyday, through Slack, StackOverflow, GitHub, Dev, Codecademy, Coursera, CodeNewbie, Udemy, Dataquest, and too many others to name here. I am grateful for the knowledge freely given, and I will freely give knowledge in return. Thank you most of all, to <strong><em>YOU</em></strong> for reading this far! <strong>👏 🤣</strong></p>

<p>&nbsp</p>

<h2 id="support">Give Support 👏</h2>

<p>If you would like to contribute, have any commentary, corrections, or suggestions, please feel free to contact me through my email provided in the Author section. If you like the project, I would appreciate giving a ⭐ in support.</p>

[Back To Top of Page](#budgetTracker)




