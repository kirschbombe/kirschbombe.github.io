---
layout: default
title: 'Alternative Infrastructures for Digital Projects'
---

*This is a presentation given with Andy Rutkowski at the [DH Infrastructure Symposium](http://www.cdh.ucla.edu/symposium/) at UCLA on February 26, 2016.*

<iframe src="https://docs.google.com/presentation/d/1x6eaOk8WvldAFeg-xnBylnZfAopM23aPUqEziQF32dY/embed?start=true&loop=true&delayms=5000" frameborder="0" width="700" height="420" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Slide 1.  Thank you to CDH for letting us be a part of this day of talks.  My name is Andy Rutkowski.  This is Dawn Childress.  We both work in UCLA’s Digital Library Program.  We will be talking about alternative infrastructures for digital projects.  For this talk we wanted to feature a project that we have been working on here at UCLA using Github in the classroom, then talk more generally about using Github and other alternative environments in the humanities.

Slide 2.  To start off with, last quarter we worked with a set of classes in which the basic assignment was to go into the special collections, pick an archival item, and write something about it which would be shared via an online web map.  The inspiration for the project was a conceptual art piece created by J Michael Walker called a “Lyrical Map of the Concept of Los Angeles.”  Measuring 60” by 290” each foot in the map represented one mile in Los Angeles. Walker used quotations and lyrical images which he superimposed on a conceptual map of Los Angeles.  UCLA Professor Colleen Jaurretche adapted the concept of the lyrical map so that it could be an ongoing project-based assignment within lower division writing classes. Students photograph and research LA-themed objects from UCLA Library Special Collections, write essays, and publish to a map framework that grows with each new class that adds to it.  Here it is: [show the map!](http://citystoriesucla.github.io/lyricalmap/)

Slide 3.  I just want to highlight three things from this process, beyond the fact that we had very little time and resources to create this map.  1) Incredible hands on experience for students working with archival material and thinking through how those materials would be displayed on the web - the project is creating producers of digital content;  2) The students were working collaboratively to create this map;  3) As a result, I was approached this quarter by a faculty member (after the term had already started) who was interested in doing a similar type of mapping project. I was able to show her this framework and we spun it off to fit the needs of her class. Here is the same framework, but adapted to fit a completely different class in an ever shorter amount of time: [Barrio Suburbanism](http://barriosuburbanismucla.github.io/barriosuburbanism/)

Slide 4.  Both “Los Angeles: The City and the Library” and “Barrio Suburbanism” are built on GitHub using “[Boulevardier](https://github.com/kirschbombe/boulevardier)," a lightweight framework for mapping texts and images in GitHub.  For those not familiar, GitHub is a web-based _git_ repository for distributed revision control and source code management - in other words, a place where you can collaborate with others to write and keep track of code.  It’s been adopted and adapted by many, including humanists, for other workflows.  The framework was originally designed and developed for an upper-level French course at Penn State where the students are engaging in a literary cartography project to map Maupassant’s Bel-Ami and other Belle Epoque French novels.  The project started out in Wordpress.  Working in groups, students chose a place in the novel, writing essays exploring the significance of place and space from political, socio-economic, and other perspectives. They also curated contemporary images like paintings, early photos, posters, and playbills to further illustrate their chosen places. Their essays and images took the form of blog posts and students dropped pins on an embedded map of Paris.  

After two semesters of using Wordpress, we wanted something different:  we wanted the map, text, and images to appear together on the page;  the instructor wanted students to start encoding texts for names and concepts;  we thought students could benefit from more hands on with technology;  and we grew tired of WordPress update (we wanted less infrastructure and more flexibility!).  I also thought about what might happen to the project if I were to leave Penn State -- I wanted the project to stay in the hands of the instructor.  With all this in mind, we decided to develop a new framework and host it in GitHub.  GitHub’s collaborative workflow was a good fit, and the fact that it would allow us to expose the framework, develop and publish in one place , and easily change ownership were big pluses.

The instructor wanted students to learn some TEI and other DH technology skills, so the framework was built around these requirements.  I worked with a programmer, Nathan Day, to develop the framework for _Maupassant’s Bel-Ami_ using TEI, XSL, javascript, and json.  We later generalized the framework and made it available via GitHub under the name “Boulevardier”.  The framework is customizable, open source, and easy to fork to start one’s own project.  It does have its issues and is still under development for fixes and enhancements.  We will add Markdown support in addition to the TEI, and plan to add a “digital edition” feature for TEI encoded diaries and historical documents.

Slide 5.  While working on this project, I started thinking more about using environments like GitHub and client-side web technologies instead of thick technology stacks --  How else could we use these? How are humanists using these now? And what else is out there?  We’ll show a few examples that I’ve encountered and find useful or interesting...

Slide 6.  Publishing  scholarship or personal web pages: Many people use GitHub Pages to publish their scholarship, visualizations, datasets, and other products of their research.  Github also supports publishing personal web pages, online profiles, and blogs.  There are many tools, models, and examples to help you build and publish your work via GitHub.  I use it to build and host my own website and project pages, and any other tidbits or visualizations that I want to share on the web. One example is the Translating Networks project.  Here we're using GitHub to host the project website and as a place to publish findings and visualizations.  We are also using GitHub as a repository for the datasets.

Slide 7.  Another great use for GitHub is hosting workshop or classroom materials, especially when there is a collaborative or DH component.  GitHub makes it easy for instructors/students/collaborators to write code or work on datasets together and make the results easily shared, all while keeping track of versions and who did what.  For the upcoming DH2016 workshop, [Building Capacity with Care: Graduate Students and DH work in the Library](http://dhgradlabor.github.io/dh2016workshop/),  we are using GitHub to host the website and we will also make all workshop materials available via the GitHub repository. Participants will be able to download or “fork” the materials to their own GitHub account, or, if they choose, they can contribute their own materials to the repository.  Our hope is that this work will continue in GitHub well beyond the workshop.

Slide 8.  GitHub is also great for collaborative, community, or crowdsourced projects., for example [GitLit](https://github.com/Git-Lit), a project to parse, version control, and create GitHub repositories for British Library scanned documents. GitLit contains the scripts needed to create git repositories from the British Library scanned and OCRed documents. It also hosts the repositories (books), so you can find and read, or do some textual analysis with the materials here.

Slide 9.  Another great GitHub feature is GitBook.  GitBook helps to create and organize documentation or other texts, which can then be read online or downloaded as PDFs or eBooks. A great example is Shawn Graham’s 
[Crafting Digital History: Course Workbook for HIST3907o @Carleton_U](https://www.gitbook.com/book/shawngraham/dh-workbook/details).

Slide 10.  GitHub will, of course, have its own limitations, but there are other options to consider. I’ll touch briefly on a few…  For web apps built using Ruby or Python, Heroku is a good cloud-based option for deploying your projects.  Another option for Python apps is “Python Anywhere.”  Python Anywhere makes it easy to code, host, and run Python in the cloud.  If you were here earlier today, you heard other speakers talk about maintaining consistent environments across machines with VirtualBox and Vagrant, as well as using Docker to build and distribute applications in containers (like a Drupal or an Islandora instance).

Slide 11.  Here are just a few examples of projects deployed to Heroku and Python Anywhere:

* Prism: a tool for collaborative interpretation of text  --  http://prism.scholarslab.org
* The British Library Machine Learning Experiment: part of their Big Data Experiment, a project to improve their search engine through Machine Learning processes --  http://blbigdata.herokuapp.com
* Exquisite Haiku: A digital experiment based on Exquisite Corpse, a classic surrealist parlor game from 1920s Paris that involved a bunch of people sitting around a table, passing around a piece of paper, and writing a poem together.  http://dclure.org/essays/exquisite-haiku/
* Aristotle Metadata Registry: an open source metadata registry representing a new way to manage and federate content --  http://aristotle.pythonanywhere.com/

Slide 12.  So now that you know about all these different environments, what else can you do? That is the really exciting thing here. You are no longer limited by pre-existing applications but you are free to experiment with all types of different tools in order to create and share your projects. Whether it is a visualization, working with texts to annotate or share them on the web, working with data, creating maps, or whatever else you come up with.  I am very quickly going to run through several things...

Slide 13.  Plotly

Slide 14.  Django Girls tutorial

Slide 15.  Annotation Studio

Slide 16.  Ed.

Slide 17.  Monumental Gifts

Slide 18.  Odyssey.js and Geojson.io

Slide 19.  So, what do we see as some of the benefits of these "alternative" infrastructures? Avoiding a thick technology stack can speed up development time and make projects easier to maintain over time. Projects built in GitHub are also more portable (for example, one party can build it, then turn over ownership to an instructor or researcher with ease).  Sites hosted in GitHub pages are also much easier to preserve than say a site created using a CMS like Wordpress or Drupal. 

Aside from these tech-side benefits, environments like GitHub expose the underlying technologies at work and make these available to the average user (no locked down servers, permissions issues, or steep technology curve).  This gives agency and responsibility to instructors and students rather than needing ongoing remediation at the institutional level.  Finally, I would argue that the openness of the platform also encourages those working within it to embrace the open source/open access spirit.  So many of the projects I've encountered, and all the examples we've seen today, encourage others to reuse and learn from what's been build and shared.  

Slide 20.  Thank you!

Slides 21 & 22. Links to sources / resources
