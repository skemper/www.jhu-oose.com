Toolbox
=======
{:.no_toc}

<figure markdown="1">
![Toolbox](toolbox.png){:width="386"}
</figure>

The Toolbox is a collection of tools curated by the course staff for programming assignments and group projects.

How to Read
-----------
{:.no_toc}

**First Read.** Read the rest of this introduction and go through the list of tools following the instructions on the sections named **Where to Get it**. *If you have installed one of these tools in the past, you must update it.*

**Second Read.** Read the sections named **What it is** and **Our Choice**.

**Third Read.** Refer to [TODOOSE](/todoose) for an example of the tools in action and follow the instructions in the sections named **How to Learn it**. Don’t try to learn everything at once—it’s *a lot* of material.

Architecture: Web Application
-----------------------------
{:.no_toc}

The tools in the Toolbox form the foundation of a web application. This architecture is the most common for modern applications, and it illustrates good software-engineering principles, for example, separation of concerns, segregation of interfaces, and so forth. The two main components of a web application are the *server* and the *client* (which typically is a web browser). The tools in the Toolbox cover the whole stack, from end to end, including server and client.

Reasons to Reach for Tools that aren’t in the Toolbox
-----------------------------------------------------
{:.no_toc}

While you’re restricted to the tools in the Toolbox for the programming assignments, on your group project you’re free to reach for other tools. Here’s why you may want to do that:

**The Project Needs it.** This is probably the best reason. Say your project is about music, for example, then you probably need a library for processing sound, which you won’t find in the Toolbox. Also, you may decide to build something other than a [web application](#architecture-web-application), like a mobile application for iOS or Android, in which case you need something like Swift or React Native.

**Fun.** If you and your teammates are more experienced, it may be fun to reach for new and unusual tools. This is fine and good, as long as you’re willing to [pay the price](#reasons-to-stick-with-the-tools-in-the-toolbox).

**Profit.** If you and your teammates already have a clear idea of the career path you want to take, you may benefit from having more experience with certain tools that aren’t in the Toolbox. This course is a great opportunity to build a real-world project using these tools to show to a potential employer in the future.

Reasons to Stick with the Tools in the Toolbox
----------------------------------------------
{:.no_toc}

**Familiarity**. You and your teammates already know the tools in the Toolbox from the programming assignments.

**Cost.** You must spend some time to learn a tool that isn’t in the Toolbox, and to make it work with the rest of the tools, and so forth.

**You’re on your Own.** We may not know how to help you if you get stuck.

**No Extra Points.** We evaluate projects based on their technical merits rather than on what tools they use.

Criteria for Curating the Tools
-------------------------------
{:.no_toc}

**Minimalism.** The fewer tools, the better.

**Multiplatform.** The tools must work on macOS, Linux, and Windows.

**Beginner-Friendly.** The tools must be relatively easy to install and to use, they must be well documented, and they must demonstrate good software-engineering principles.

**Integration.** The tools must work well together.

**Industry Standard.** The tools must not be only pedagogical toys, but actually be used in industry.

Tools in the Toolbox
--------------------
{:.no_toc}

* TOC
{:toc}

Development Tools
=================

Integrated Development Environment (IDE): IntelliJ IDEA
-------------------------------------------------------

<figure markdown="1">
![IntelliJ IDEA](intellij-idea.png){:width="344"}
</figure>

**What is it.** An IDE allows you to edit source code, invoke the compiler, interact with the debugger, and so forth.

**Our Choice.** IntelliJ IDEA is the modern industry standard for [Java](#programming-language-java), after it [*eclipsed*](https://www.eclipse.org) the competition. It makes it easier to use the other tools in the Toolbox, including [Git](#version-control-systemvcs-git), [JavaScript](#programming-language-javascript), [Markdown](#authoring-language-markdown), and [SQLite](#database-management-systemdbms-sqlite). Also, it’s the foundation of Android Studio.

**Where to Get it.** [Follow these instructions](https://www.jetbrains.com/idea/download/). Install the *Ultimate* edition, not the *Community* one. The Ultimate edition a commercial product, so [apply for a student license](https://www.jetbrains.com/student/). The Ultimate edition includes features that the Community doesn’t and that are useful in the course, for example, support for [JavaScript](#programming-language-javascript) and [database tools](#database-management-systemdbms-sqlite).

**How to Learn it.** First, fiddle with it for a couple of hours. If after that you still want some help, refer to the [documentation](https://www.jetbrains.com/idea/documentation/).

Application Programming Interface (API) Development Environment (ADE): Postman
------------------------------------------------------------------------------

<figure markdown="1">
![Postman](postman.png){:width="348"}
</figure>

**What is it.** An API establishes *what* functionalities the server provides to the client and *how* it provides them. Once the API is designed, different people may work on the server and on the client independently, maybe even in parallel, and as long as both sides follow the API, the application will work in the end. An ADE helps you design the API, document it, test it, interact with it, and so forth.

**Our Choice.** Postman invented the idea of an ADE; it is the industry standard in this area and stands with little competition.

**Where to Get it.** [Follow these instructions](https://www.getpostman.com/downloads/). You may have installed Postman as a browser extension in the past, but the browser extension has been discontinued, so switch to the standalone version.

**How to Learn it.** First, fiddle with it for a couple of hours. After doing that, [visit the Postman Learning Center](https://learning.getpostman.com). In particular, read the sections about testing, which include the [Postman Sandbox](https://learning.getpostman.com/docs/postman/scripts/postman_sandbox) and its [API Reference](https://learning.getpostman.com/docs/postman/scripts/postman_sandbox_api_reference/) (this is the reference for Postman Sandbox’s API for testing, not to be confused with the application API which is the thing you design in Postman). Postman tests are written in [JavaScript](#programming-language-javascript) using the [Chai](https://www.chaijs.com/api/bdd/) library for expectations. To run Postman tests in the [CI Server](#continuous-integrationci-server-travisci), invoke them from the command line with [Newman](https://learning.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman/).

Browser: Google Chrome
----------------------

<figure markdown="1">
![Google Chrome](google-chrome.png){:width="350"}
</figure>

**What is it.** I bet you know what a browser is, because you’re reading this in one right now. So what is this doing in the Toolbox? Well, typically a web application is expected to work in any browser, but in the interest of keeping things simple, we test your application in only one browser. This is a somewhat realistic constraint because modern browsers are becoming more alike.

**Our Choice.** Google Chrome is the most popular browser and it has some of the most advanced developer tools.

**Where to Get it.** Chances are that you’re already reading this in Google Chrome. If you aren’t, [follow these instructions](https://www.google.com/chrome/).

**How to Learn it.** Of course you already know how to use a web browser, but you must also learn how to use the [developer tools](https://developers.google.com/web/tools/chrome-devtools/), which include an [HTML/CSS](#user-interface-hypertext-markup-languagehtml--cascading-style-sheetscss)/[JavaScript](#programming-language-javascript) inspector, a network inspector, a JavaScript console, a JavaScript debugger, and much more.

Version Control System (VCS): Git
---------------------------------

<figure markdown="1">
![Git](git.png){:width="356"}
</figure>

**What is it.** A VCS is like a time machine for your code base: the VCS can save the state of the code base over time and help you navigate in its history. Also, a VCS lets you coordinate your work with other people on the same code base.

**Our Choice.** Git is the most used VCS and is also one of the most sophisticated.

**Where to Get it.** [Follow these instructions](https://git-scm.com/downloads) to install Git. Then, to configure it:

1. Let Git know your [name](https://help.github.com/en/articles/setting-your-username-in-git#setting-your-git-username-for-every-repository-on-your-computer) and [email](https://help.github.com/en/articles/setting-your-commit-email-address-in-git#setting-your-email-address-for-every-repository-on-your-computer), which will be used to identify your contributions to the code base. Use an email that will belong to you forever, not, for example, your university email. You may use a different email from the one on your account on [GitHub](#project-management-github).

2. Create [a global `.gitignore`](https://help.github.com/en/articles/ignoring-files#create-a-global-gitignore), which lists the kinds of files that must never be versioned with Git because they don’t belong to a project, but to your machine, for example, the `.DS_Store` files generated by Finder on macOS. A minimal `.gitignore` includes the following:

   ```
   # Ignore the project configuration files generated by IntelliJ IDEA
   # because they’re different for every machine.
   .idea
   # Ignore the files generated by Finder if you’re running macOS.
   .DS_Store
   ```

3. [Create an SSH key if you don’t have one already](https://help.github.com/en/articles/connecting-to-github-with-ssh).

**How to Learn it.** Use Git from within the [IDE](#integrated-development-environmentide-intellijidea). For more advanced topics, or to learn about using Git from the command line, refer to [*Pro Git*](https://git-scm.com/book).

Project Management: GitHub
--------------------------

<figure markdown="1">
![GitHub](github.png){:width="264"}
</figure>

**What is it.** A project management tool tracks what needs to be done in the project, who’s working on what, and so forth. It also hosts the canonical [version](#version-control-systemvcs-git) of the code base.

**Our Choice.** GitHub is the most popular Git host. Its project-management tools are simple but cover everything you need for the group projects.

**Where to Get it.** [Follow these instructions to create an account](https://github.com/join), and [add to your account the SSH key](https://help.github.com/en/articles/adding-a-new-ssh-key-to-your-github-account) you created when configuring [Git](#version-control-systemvcs-git).

**How to Learn it.** Go through the exercises in the [GitHub Learning Lab](https://lab.github.com) and the [GitHub Guides](https://guides.github.com).

Wireframing & Diagramming: Paper & Pencil
-----------------------------------------

<figure markdown="1">
![Paper & Pencil](paper-and-pencil.png){:width="283"}
</figure>

**What is it.** A wireframe is a rough sketch of the user interface. A diagram is a visual representation of the application’s *technical* design (not to be confused with its *graphic* design), for example, its classes and how they communicate.

**Our Choice.** Paper & Pencil helps to keep things simple. Wireframes should not be concerned with font choices, colors, and so forth. Diagrams should not include too many classes, attributes, methods, and so forth, particularly those that can be inferred from context, for example, getters and setters.

**Where to Get it.** I trust you can figure this one out by yourself.

**How to Learn it.** There is no set of rules on how to wireframe, but there is [a common language that people tend to use](https://www.usability.gov/how-to-and-tools/methods/wireframing.html). The kinds of diagrams in which we’re interested in this course, however, *do* follow a set of rules, the so-called Unified Modeling Language (UML). UML defines how certain elements, for example, classes and inheritance, should look on the page. UML defines many kinds of diagrams, but in this course we’re mainly interested in one: [class diagrams](https://www.ibm.com/developerworks/rational/library/content/RationalEdge/sep04/bell/index.html).

Server
======

Programming Language: Java
--------------------------

<figure markdown="1">
![Java](java.png){:width="205"}
</figure>

**What is it.** The programming language for the server side of your application.

**Our Choice.** Java is the quintessential modern object-oriented programming language, it is widely used in industry, and you probably already know it from previous courses.

**Where to Get it.** [Follow these instructions](https://www.oracle.com/technetwork/java/javase/downloads/index.html). Install the latest Java Development Kit (JDK) for the Java Platform, Standard Edition (SE).

**How to Learn it.** Refer to an introductory Java book, for example, [Core Java](https://horstmann.com/corejava/index.html), if you want to brush up on the basics: syntax, classes, objects, inheritance, interfaces, exceptions, generics, polymorphism, method overloading and overriding, invoking the compiler, and so forth. Beyond the basics, learn about [lambdas](https://medium.freecodecamp.org/learn-these-4-things-and-working-with-lambda-expressions-b0ab36e0fffc) and [local type inference](https://www.journaldev.com/19871/java-10-local-variable-type-inference).

Build System: Gradle
--------------------

<figure markdown="1">
![Gradle](gradle.png){:width="491"}
</figure>

**What is it.** A build system invokes the compiler for all the files in your project, it downloads and installs the third-party libraries in which your project depends, and so forth.

**Our Choice.** Gradle is one of the most popular and widely used build systems for Java, though this space is crowded and fractured. Gradle is relatively easy to use, for example, its configuration files are simpler than the XML-based ones in [Maven](https://maven.apache.org), which is another popular build system for Java. Gradle is also the build system used by default in Android projects.

**Where to Get it.** The [IDE](#integrated-development-environmentide-intellijidea) gets it for you.

**How to Learn it.** Find packages to install at the [The Central Repository](https://search.maven.org): look for the package name to find its latest version, and follow the instructions for Gradle. Use the [IDE](#integrated-development-environmentide-intellijidea) to run the basic tasks, for example, compiling, and running the [automated tests](#testing-framework-junit). Use `gradlew` (or `gradlew.bat` if you’re on Windows) to run Gradle tasks from the command line. If you need to dive deeper, refer to the [Gradle Documentation](https://docs.gradle.org/).

Web Server: Javalin
-------------------

<figure markdown="1">
![Javalin](javalin.png){:width="434"}
</figure>

**What is it.** A [Java](#programming-language-java) library for developing web servers.

**Our Choice.** Javalin abstracts the low-level aspects of the communication between server and client while avoiding abstractions that would obscure how things work and confuse beginners.

**Where to Get it.** Add `io.javalin:javalin` as a dependency—the [build system](#build-system-gradle) takes care of the rest. Besides Javalin itself, also add a logger, [Simple Logging Facade for Java (SLF4J)](https://www.slf4j.org) (`org.slf4j:slf4j-simple`), so that Javalin can log important information while it’s running.

**How to Learn it.** [Read the documentation](https://javalin.io/documentation).

JSON Mapper: Jackson
--------------------

<figure markdown="1">
![Jackson](jackson.png){:width="600"}
</figure>

**What is it.** A [Java](#programming-language-java) library for mapping back and forth between Java data structures and [JSON](#data-interchange-format-javascript-object-notationjson).

**Our Choice.** Jackson is the default JSON mapper for [Javalin](#web-server-javalin).

**Where to Get it.** Add `com.fasterxml.jackson.core:jackson-databind`  as a dependency—the [build system](#build-system-gradle) takes care of the rest.

**How to Learn it.** Read the [documentation](https://github.com/FasterXML/jackson-databind) and the [wiki](https://github.com/FasterXML/jackson-databind/wiki).

Testing Framework: JUnit
------------------------

<figure markdown="1">
![JUnit](junit.png){:width="355"}
</figure>

**What is it.** A testing framework allows you to write automated tests, which are small programs that check that your application is behaving correctly. Writing tests often helps you figure out what that correct behavior should be. Also, the tests serve as a form of low-level executable documentation. Finally, the tests prevent future modifications from breaking the application.

**Our Choice.** JUnit is the most popular and straightforward testing framework for Java.

**Where to Get it.** Add `org.junit.jupiter:junit-jupiter-engine` as a dependency and configure the project to use JUnit following [the example project for Gradle and Java](https://junit.org/junit5/docs/current/user-guide/#overview-getting-started-example-projects).

**How to Learn it.** [Read the User Guide](https://junit.org/junit5/docs/current/user-guide/).

Database Management System (DBMS): SQLite
-----------------------------------------

<figure markdown="1">
![SQLite](sqlite.png){:width="600"}
</figure>

**What is it.** When we turn the server off, it *forgets* all the Java objects that existed in memory. If the application data was stored in those objects only, it would be lost. A DBMS persists the application data across server runs. Also, a database preserves data integrity and consistency, for example, it may enforce the constraint that all users in your application must have a phone number.

**Our Choice.** Typically a web application would use a DBMS with a client–server architecture (this is a client–server architecture with respect to the DBMS, in which the DBMS is the server and the application server is actually the client). The most popular DBMS with a client–server architecture is [PostgreSQL](https://www.postgresql.org). A client–server architecture scales better, particularly when multiple server components need to communicate with a central DBMS. But in this course we prefer SQLite precisely because it is serverless: the database is just stored in a regular file, which makes SQLite easier to install and manage. But there are some issues with [deploying SQLite to Heroku](#platform-heroku), and if you want to avoid them, you have to switch to PostgreSQL.

**Where to Get it.** Add `org.xerial:sqlite-jdbc` as a dependency—the [build system](#build-system-gradle) takes care of the rest. This Java library contains not only the driver that the server needs to connect to SQLite, but also SQLite itself.

**How to Learn it.** Manage SQLite with the database tools in the [IDE](#integrated-development-environmentide-intellijidea). In your application, the server communicates with SQLite using a language called Structured Query Language (SQL). If you’re new to SQL, start with this [course](https://www.codecademy.com/learn/learn-sql). Once you understand SQL, you must learn some things particular to SQLite, which you may find in [the documentation](https://www.sqlite.org/docs.html). In particular, learn about [SQLite’s data types and its dynamic type system](https://www.sqlite.org/datatype3.html), and [the particularities of SQLite’s SQL dialect](https://www.sqlite.org/lang.html).

Client
======

Programming Language: JavaScript
--------------------------------

<figure markdown="1">
![JavaScript](javascript.png){:width="381"}
</figure>

**What is it.** The programming language for the client side of your application.

**Our Choice.** JavaScript is the native programming language for the browser.

**Where to Get it.** It comes with [the browser](#browser-googlechrome).

**How to Learn it.** To begin with, read the [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript) and [this tutorial](https://javascript.info). These should give you a fair notion of the basics of JavaScript, but the language is evolving fast and in this course we use the latest features, so read [this tutorial](https://babeljs.io/docs/en/learn.html) on what changed recently. Finally, keep up with the updates by searching the web for articles on ECMAScript 5, ECMAScript 6 (2015), ECMAScript 7 (2016),  ECMAScript 8 (2017), and so forth. ECMAScript is the standard on which JavaScript is based. (Isn’t it fun that ECMAScript is updated every year but the version numbers *don’t* match the release year, for example, ECMAScript **8** was released in 201**7**?)

User Interface: Hypertext Markup Language (HTML) & Cascading Style Sheets (CSS)
-------------------------------------------------------------------------------

<figure markdown="1">
![HTML & CSS](html-and-css.png){:width="510"}
</figure>

**What is it.** HTML is the language in which to define the *contents* of the user interface. CSS is the language in which to define the *looks* of the user interface.

**Our Choice.** HTML and CSS are the native languages for user interfaces in the browser.

**Where to Get it.** It comes with [the browser](#browser-googlechrome).

**How to Learn it.** Read the MDN Web Docs on [HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML) and [CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS).

User-Interface Builder: React
-----------------------------

<figure markdown="1">
![React](react.png){:width="305"}
</figure>

**What is it.** A [JavaScript](#programming-language-javascript) library for rendering the [user interface](#user-interface-hypertext-markup-languagehtml--cascading-style-sheetscss) and keeping it up to date when the data changes.

**Our Choice.** This is a hot space in the software engineering world—there are many tools competing to solve the same issue. React is among the most popular, it is relatively easy to learn, and it’s based on simple ideas.

**Where to Get it.** Add React to the application using [the simplest method](https://reactjs.org/docs/add-react-to-a-website.html), including support for JSX with Babel. To make your application work locally even if your computer is offline, download the scripts instead of using the versions at `unpkg.com`. This quick-and-dirty method wouldn’t be good for applications that have hundreds of users, or applications that must to be as fast as possible, but it’s simple enough: it requires just a couple of `script` tags, instead of a JavaScript runtime (for example, Node.js) and a JavaScript build system (for example, webpack). Also install the [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) for [Google Chrome](#browser-googlechrome).

**How to Learn it.** Go through [the tutorial](https://reactjs.org/tutorial/tutorial.html) and read [the documentation](https://reactjs.org/docs/getting-started.html), including the sections on [JSX](https://reactjs.org/docs/introducing-jsx.html).

Client–Server Communication
===========================

Data-Interchange Format: JavaScript Object Notation (JSON)
----------------------------------------------------------

<figure markdown="1">
![JSON](json.png){:width="400"}
</figure>

**What is it.** The server and the client communicate with a protocol based on plain text (HTTP), but they need to exchange data that is more structured than plain text, for example, objects, lists, and so forth. A Data-Interchange Format is a convention on how to format structured data in plain text.

**Our Choice.** JSON is an industry standard. It is simpler and more lightweight than the other popular alternatives, for example, XML.

**Where to Get it.** You don’t *install* JSON the same way you install, say, Java, because JSON is just a convention on how to format data. But while it may be possible to map back and forth between data structures in a programming language and JSON just by manipulating strings, you must use tools to streamline these tedious and error-prone tasks. On the server side, use a [Java library](#json-mapper-jackson); on the client side, use JavaScript, which already supports JSON natively (unsurprisingly, if you recall what JSON stands for).

**How to Learn it.** [Follow this tutorial](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON).

Deployment
==========

Platform: Heroku
----------------

<figure markdown="1">
![Heroku](heroku.png){:width="494"}
</figure>

**What is it.** A platform to run the server and make it available to anyone on the Internet.

**Our Choice.** Heroku is among the simplest platforms for deployment, because it favors *convention over configuration*. It provides many important features so seamlessly that you won’t even notice that they’re there, for example, Continuous Delivery (CD), a domain, HTTPS support, and so forth.

**Where to Get it.** [Create an account](https://www.heroku.com).

**How to Learn it.** [Read the documentation](https://devcenter.heroku.com). In particular, read the instructions for [Deploying Gradle Apps on Heroku](https://devcenter.heroku.com/articles/deploying-gradle-apps-on-heroku) and the [Application plugin for Gradle](https://docs.gradle.org/current/userguide/application_plugin.html). Also, note that there’s an issue with [SQLite](#database-management-systemdbms-sqlite) on Heroku: any time Heroku restarts your application, it does so in a fresh file system (a so-called *ephemeral* file system), wiping your SQLite database in the process. And Heroku restarts your application frequently: on every deployment and every time your application becomes idle for longer than 30 minutes. To work around this, seed your database with data on server startup, or switch to [PostgreSQL](https://devcenter.heroku.com/articles/heroku-postgresql).

Continuous Integration (CI) Server: Travis CI
---------------------------------------------

<figure markdown="1">
![Travis CI](travis-ci.png){:width="600"}
</figure>

**What is it.** At its simplest, a CI Server grabs the code base from [GitHub](#project-management-github), runs the automated tests, and reports on the results. In general, you may configure a CI Server to execute any task, for example, packaging the application for distribution, deploying the application, and so forth.

**Our Choice.** Travis CI integrates nicely with [GitHub](#project-management-github), and it’s among the most popular CI Servers on the market.

**Where to Get it.** Visit [`travis-ci.`**`com`**](https://www.travis-ci.com), not [`travis-ci.`**`org`**](https://www.travis-ci.org) (which is the [legacy platform](https://blog.travis-ci.com/2018-05-02-open-source-projects-on-travis-ci-com-with-github-apps)), and use the credentials from [GitHub](#project-management-github).

**How to Learn it.** [Read the documentation](https://docs.travis-ci.com). Configure Travis CI to run not only the [JUnit tests](#testing-framework-junit), but also the [Postman tests](#application-programming-interfaceapi-development-environmentade-postman).

Documentation
=============

Authoring Language: Markdown
----------------------------

<figure markdown="1">
![Markdown](markdown.png){:width="388"}
</figure>

**What is it.** A language in which to write the project documentation, including the README, the CHANGELOG, and so forth.

**Our Choice.** Markdown is lightweight, simple, and supported everywhere in [GitHub](#project-management-github).

**Where to Get it.** The [IDE](#integrated-development-environmentide-intellijidea) already supports Markdown and provides a nice preview window of the rendered document.

**How to Learn it.** Markdown isn’t exactly a language, but a *family* of languages. There are *many* implementations of Markdown, and while they tend to implement the core features the same way, each provides different extended features. For this course, we use [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
