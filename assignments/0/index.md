# Assignment 0: Project Proposal

# Onboarding

**Welcome to OOSE!**

One of the points of this course is that we aren’t using only pedagogical tools, but tools actually used by software engineers. To bring this point home, we run the course similar to how a software project is run, using the tools that software engineers use to coordinate their work. You’ll use [GitHub](https://github.com) throughout the course to submit assignments, ask questions, collaborate with the other members of your group in the [group projects](/group-projects), and so forth. If you don’t have a GitHub account, [create one now](https://github.com/join). Then register for the course using the form below:

<form method="POST" action="https://roboose.herokuapp.com/roboose/students">
<fieldset markdown="1">

<legend>Student Registration</legend>

<label>
GitHub Identifier  
<input type="text" name="github" required pattern="[A-Za-z0-9][A-Za-z0-9-]*[A-Za-z0-9]">  
</label>
<small>
Don’t include an `@` sign at the beginning—this isn’t a [mention](https://help.github.com/en/articles/basic-writing-and-formatting-syntax#mentioning-people-and-teams).  
</small>

<label>
Hopkins Identifier (6-Character)  
<input type="text" name="hopkins" required pattern="[A-Z0-9]{6}">  
</label>
<small>
This is called “Hopkins ID” in [SIS](https://sis.jhu.edu/). It _isn’t_ your email.
</small>

<button>Register</button>

</fieldset>
</form>

If you run into problems, send and email to <student-registration@jhu-oose.com>. Include all the information from the form above.

After you register, you are invited via email to the GitHub organization for the course, [`jhu-oose`](https://github.com/jhu-oose), joining the team `jhu-oose/{{site.course}}-students`, which grants you access to the [Students Area](https://github.com/jhu-oose/{{site.course}}-students){:data-proofer-ignore="true"} <small title="You must a student logged into GitHub to see this.">🔒</small>, where you may find a public forum (visible only to other students in the course), announcements, videos of the lectures, and so forth.

After you register, you are also invited via email to a repository at `https://github.com/jhu-oose/{{site.course}}-student-<identifier>`. This is your individual repository in which you’ll submit the [assignments](/#individual-assignments), receive grades, ask questions visible only to the staff, and so forth.

## Profile

<small>
Submit your profile as a [Markdown](/toolbox#authoring-language-markdown) document at `README.md` in the `master` branch of your personal repository at `https://github.com/jhu-oose/{{site.course}}-student-<identifier>`.
</small>

Fill in the template below (parts marked with `<!-- -->` are placeholders that you must fill in):

```
# <!-- Name -->

![Profile Picture](<!-- Show your face, because the purpose of the profile picture is to be able to recognize you, see for example the pictures at https://www.jhu-oose.com/staff -->)

**Personal Pronoun (Optional):** <!-- See https://www.mypronouns.org to understand more about this question. Answer (if you wish) in the form of a link, for example, [She/her](https://www.mypronouns.org/she-her) -->

# Background

<!-- Are you fresh out of a data structures course? Do you have years of experience in industry? What technologies do you usually work with? What are your interests? And anything else you want to share. -->

# Expectations

<!-- Why did you sign up for the course? What do you expect to learn? And anything else you want to share. -->
```

# Project Ideas

Come up with at least 3 [project ideas](/lectures/0#project-ideas). They may be silly—in fact, it may be better if they are.

# Project Proposal

Choose one of your [project ideas](#project-ideas) and develop it into a [project proposal](/iterations/0#project-proposal). Your project proposal doesn’t have to be fully developed, but you definitely need more than something at level of [the sample project proposal we did in Lecture 0](/lectures/0#the-project-proposal-we-wrote-together-in-class). Also, you must acknowledge the parts that are missing by saying, for example, “My project requires integration with the [GitHub API](https://developer.github.com/v3/), but I don’t know yet if it has all the features I need—further study required.”

Your goal is to have something solid enough to discuss with your group members when you start working on your [group project](/group-projects).

# Software Engineering

We didn’t have the time to cover this in class, but see [the corresponding lecture notes](/lectures/0#welcome-to-oose)

Answer the following questions:

1. Do you see software engineering as a science or an art? Or a mix of both? If so, to what degree?

2. What makes a software engineer? Do you feel you are a software engineer?

# Technology

<video src="https://archive.org/download/todoose/todoose--getting-started.mp4" controls preload="none"></video>

1. Go through the tools in the [Toolbox](/toolbox) and install them.

2. Visit [TODOOSE](https://github.com/jhu-oose/todoose) and play with the [live version](https://todoose.herokuapp.com){:data-proofer-ignore="true"} to learn how the application works (it’s a simple to-do application).

3. Import TODOOSE as a project in [IntelliJ IDEA](/toolbox#integrated-development-environmentide-intellijidea).

4. Run the server.

5. Interact with the application locally in [Google Chrome](/toolbox#browser-googlechrome). **Take a screenshot of the application open locally in Google Chrome and include in your submission (for example, see the screenshot below).**

   ![Running locally in Google Chrome](running-locally-in-google-chrome.png)

6. Run the [JUnit](/toolbox#testing-framework-junit) tests in IntelliJ IDEA. **Take a screenshot of the tests passing locally and include in your submission (for example, see the screenshot below).**

   ![JUnit tests](junit-tests.png)

7. Open the API specification in [Postman](/toolbox#application-programming-interfaceapi-development-environmentade-postman).

8. Run the Postman tests. **Take a screenshot of the tests passing and include in your submission (for example, see the screenshot below).**

   ![Postman tests](postman-tests.png)

9. See the [tests running](https://travis-ci.com/jhu-oose/todoose) on [Travis CI](/toolbox#continuous-integrationci-server-travisci).

10. Deploy the application to [Heroku](/toolbox#platform-heroku) with the application name `todoose-<identifier>`. For example, if you were [`jhu-oose-example-student`](https://github.com/jhu-oose-example-student) on GitHub, then your application name would be `todoose-jhu-oose-example-student`. **We’ll look at your deployed version when grading, so make sure you get the name right and don’t remove the application from Heroku until after you received your grade.**

11. Start watching the [video series showing us buidling TODOOSE](/todoose). You have about one month before we’ll dive deeper into the implementation, and by then you must have a fair understanding of the technology. One or two videos every day will get you there.

# Submission

**<small>🚧</small>  Work in Progress  <small>🚧</small>**

You’re trying to submit your assignment before we could setup the submission infrastructure. Good for you. Please come back tomorrow and excuse us while we’re working to make OOSE better for you 😀
