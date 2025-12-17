# Lesson 3: Making Open Code

## Navigation
* [Overview](#overview)
* [Learning Objectives](#learning-objectives)
* [How do We Plan for Making Code?](#how-do-we-plan-for-making-code)
* [Importance of Version Control](#importance-of-version-control)
* [Describing Our Code to Others](#describing-our-code-to-others)
* [What License Should We Choose for Our Code?](#what-license-should-we-choose-for-our-code)
* [Programming Best Practices](#programming-best-practices)
* [Lesson 3: Summary](#lesson-3-summary)
* [Lesson 3: Knowledge Check](#lesson-3-knowledge-check)

## Overview

In this lesson, you will learn about the practical steps to make code openly available. Large volume and well-established software have different needs than an incipient project. For example, a script written to create a simple plot has different requirements than a software package that models the Earth's climate. The size of a research team can also determine the steps required to make code open access. This lesson covers the process to make code usable to other researchers through documentation, considerations around licenses, and software development best practices.

## Learning Objectives

After completing this lesson, you should be able to:

- Describe the key considerations when planning a new open software project.
- List three reasons for projects to use version control.
- Explain the purpose and recall general information typically included in a README file.
- Be able to select a license for your code and list the differences between permissive and protective open-source software licenses.
- Explain best practices in software development that support transparency, reproducibility and collaboration.

## How do We Plan for Making Code?

Code is written to solve a challenge. This can range from producing a plot, to data-processing Earth observations, to modeling the Universe. The challenges associated with writing code can differ in difficulty as well, from simpler tasks such as the use of spreadsheets, or more complex activities like the creation of extensive libraries and use of high-performance cloud computing. Code can be developed as an individual, team, or a community. Once written, code might be used for decades or only for a specific research query.

When starting a research project, it is useful to consider the following questions:

1. What problem am I trying to solve, and are others in my scientific community facing it as well?
2. Are there existing solutions? (In Lesson 2, we explored how to look for existing solutions.)
3. Did you find code that was close to what you wanted but didn't quite meet your needs?
4. You could potentially contribute to existing code rather than writing something new.

Though, even if a solution already exists, there may be good reasons to develop your own code. Instances include:

- The code is written in a different programming language than you are familiar with.
- The license is not open enough to adopt it.
- To try new techniques or to develop a deeper understanding of the problem.

<img src="../images/media/image333.jpg" style="width:350px;height:auto;" />

It might take more time to start a new project or integrate someone else's code rather than writing your own. You will have to make that call.

For the purposes of this lesson, let's pretend that we are working on a research project and that we've looked for existing code. Although we found a few available options, we've decided that our needs are unique enough that nothing available will support our work. We will need to start a new project!

### Starting a New Project

When starting a new project, consider these key elements:

- Define the project scope, its primary features and any limitations, and the intended audience.
- Consider resources required for the code or software to run. Will it be on a personal computer, a high-performance computing server, or on the cloud?
- How will it be managed?

This lesson focuses predominantly on the question of how to manage open access code.

Who will be working on the project? What are some of the development best practices? How will you share the project openly? How will it be licensed?

### Organizing a Project

<img src="../images/media/image353.png" style="width:250px;height:auto;" />
Image Credit: Photo by XKCD is licensed under a Creative Commons Attribution-NonCommercial 2.5 License

---

Software projects can be organized in a variety of ways, each of which involve unique considerations for how to begin. Many projects start out as a single script that was only intended for a one-time use. However, a script can grow into a much larger project with unforeseen applications in its original, or new, field of research. Other projects can start with formal requirements and standards.

**Making code public has many advantages:**

- It enables open collaboration
- It invites constructive feedback that contributes to a code's accuracy and robustness
- Those with less programming experience can learn from those with more programming experience as they improve the code
- It provides an intermediate product that can still be cited

When naming a project, conduct a quick search of the envisioned name to see what shows up. Avoid names with many other uses as this will make it difficult for others to discover the code. Also, do not choose embarrassing, unprofessional, or trademarked names.

Hosting the product on a version control platform ensures the permanence of your project. If the code only exists on your computer, it may disappear if the computer is damaged or is lost.

Documenting the production and management of your code benefits both you and those that might use your code in the future. You are your own best collaborator. Documentation can save you from a future headache should you reuse the code in six months or attempt to recall meticulous details about your process later on.

**Questions to consider when choosing a programming language:**

- Will potential collaborators be able to contribute in the chosen language?
- Which languages are you most experienced with?
- Are there any limitations from your computing environment that would impede your ability to write or manage this code?
- Languages have strengths and weaknesses; which is more important to consider for your project?

**Before someone else can use your code, they're going to ask some questions:**

- Where can I find your code?
- Is your code documented?
- In what ways am I allowed to use your code?
- Will you accept changes to your code? If I find a bug, what do I do?
- How do I trust that your code works?
- How do I know if the code will be supported long-term?

## Importance of Version Control

Your code will change significantly over the lifetime of your project. Just as we can appreciate the ability to track earlier versions of documents or versions created by different people, inevitably someone will want to be able to revert, compare, and synthesize changes in code.

The most popular tool for version control is Git, a system that tracks changes in computer files. It's similar to Google Docs or SharePoint, but more applicable to code script. Git is usually used in conjunction with a version control platform such as GitHub, GitLab, or Bitbucket. These tools were covered in Module 2 (General Tools for Open Science).

Version control enables the following:

- Helps developers keep track of changes to a project's code (as well as supplemental files and documentation) over the entire course of a project's evolution.
- Revisions to a project's files can be tracked, including contributions made by different people.
- Undesirable changes (like errors or bugs) can be reverted at any time.

Version control is a good practice for coding, even if you are not immediately sharing the code. You can use version control with your code privately on your computer, or use the private mode on hosting services (e.g. GitHub and GitLab). By setting up version control early on, you prepare your code for intended and unforeseen future use.

**Further Resources on version control**

- [Software Carpentry Version Control with Git](https://swcarpentry.github.io/git-novice/) (external link)
- [The Turing Way, Version Control](https://the-turing-way.netlify.app/reproducible-research/vcs.html) (external link)
- [Use a publicly available repository with version control: guidance for FAIR software](https://fair-software.eu/recommendations/repository/) (external link)

## Describing Our Code to Others

### README

The first stop for a user when they approach a new project should be the README file. Aptly named, this file contains orientation information that will help a user understand a project's purpose, provides examples for how it can be used, and lists other important information that the creator deems pertinent.

At the minimum, a README should contain the name of the project and a very short paragraph of what the code is. It should be limited to two to three sentences in a plain-language style that does not make assumptions about the reader. After all, it's the elevator pitch for the project.

|  |  |
|---|---|
| **Bad** README example | "This code recomputes the fundamental permutation factor of the downward flow (for J < 10, obviously)." |
| **Good** README example | "LeapKitten. This Python software package takes any picture of a kitten (JPEG, PNG) and uses artificial intelligence to output what it would look like leaping into the air. In addition, the code takes leap years into account on the timestamp on the image." |

In addition, the following information is helpful to add to the README, especially if they are not listed elsewhere:

- A list of any code dependencies the software has, e.g. "Numpy, kitten-rng, and human-readable must be installed to run this software."
- How to install and a brief description of how to run the software.
- Detailed description of the software, especially if there is no external documentation.
- Examples of how to use the software.
- Acknowledgement of team members or sources of support.

As seen in these examples, README files can be useful for a [collection of scripts supporting a publication](https://github.com/granttremblay/Tremblay2018_Code) (external link) or an [extensively developed software package](https://github.com/MillionConcepts/lhorizon)(external link).

### Contributor Guidelines

The CONTRIBUTING file gives information about how to contribute to the project. It details how the contribution process works and what type of contributions are needed. While not every project has a CONTRIBUTING file, the existence of one is a clear indicator that contributions are welcomed.

You'll need to decide for yourself when your project has progressed enough to consider inviting contributors. When it has reached that point, create a document called CONTRIBUTING at the top level of your report.

The [Astropy contributing guidelines](https://github.com/astropy/astropy/blob/main/CONTRIBUTING.md) (external link) and [Numpy contributing guidelines](https://numpy.org/devdocs/dev/index.html) (external link) provide two examples.

**Bonus Tip: Even if you are developing your code publicly, this does not mean you have to accept contributions from others or maintain your code forever. The contributing guidelines or README are a good places to indicate what your expectations are for your code. This can clarify that the code is not maintained or not accepting contributions.**

### Code of Conduct

The code of conduct sets ground rules for participants' behavior and helps to facilitate a friendly, welcoming environment. While not every project has a CODE_OF_CONDUCT file, its presence signals that this is a welcoming project to contribute to.

### Code Documentation

**Code Level Documentation for the Developer**

Your software should be documented within the source code. Each function should have comments at the start that briefly state, in plain language, what the function is for. This is not only for other developers, but for your future self if you've forgotten those details.

> **Example**
>
> \# This function takes the image array and crops it from the center to 50% of the original size.
>
> Without going into details of the data type, calling parameters, etc., this description immediately puts someone looking at the code into the context of what the function aims to accomplish. They can then explore the details.
>
> While you should consider placing a description at the start of a function, use your discretion on where you put similar descriptions of code. At the start of a complex loop or analysis would be a good idea. Don't go overboard - things like this aren't useful:
>
> \# set x to 17 
>
> x = 17
>
> Descriptive variable, class, and function names can make your code very readable. Sometimes even great coders will work fast and will name variables 'a', 'temp', or other unclear names that probably won't make a lot of sense in a week or two when they come back to something they were working on. Names like 'baking_time' or 'velocity' are more clear. Variable names should be easy to understand and clearly represent what they are.
>
> Ideally, someone who doesn't write in the software language of the code should be able to read the comments in the file and have a rough idea of what is happening.
>
> Use the comments to put URLs that reference the code and/or software you implement, such as an algorithm (e.g. Stack Overflow) or a formula from a journal paper.

### Code Level Documentation for the User

If you are developing code that you expect others to use, produce a manual on how to use the code. As code constantly develops, it is much easier to document while, or even before, you write any code.

If you write your documentation within the code itself, there are pieces of software that can then extract the code, format it, and then present it as a polished manual. Examples of documentation generated from the code can be seen for [Astropy](https://docs.astropy.org/en/latest/) (external link) or [NumPy](https://numpy.org/doc/stable/) (external link).

They look fancy, but very similar too. These sites were completely generated from comments and documents written in the source code. Different from the comments written for developers of the code above, these comments were written specifically for the audience of external users of the code: they are the user manual.

While there are multiple software packages for automatic documentation generation, the most commonly ones used are [Sphinx](https://www.sphinx-doc.org/en/master/) (external link) for Python and [Doxygen](https://www.doxygen.nl/index.html) (external link) for almost everything else. [Markdown](https://www.markdownguide.org/) (external link) is also a popular choice for the formatting language for documentation.

### Programming and Documenting

**Establishing a Development Environment** - Establishing an appropriate development environment will help you write good, clean code and will help you maintain the project as it evolves.

- Configure any necessary tools for writing the code. Perhaps an IDE (Integrated Development Environment) or text editor. Some popular examples include VS Code, Pycharm, R Studio, and Xcode.
- Set up a package manager. For example, for Python, one could use 'anaconda' or 'poetry.'
- Create a virtual environment specific to your project to isolate its dependencies (and their versions) from those used for other projects.

**Structuring Files and Folders** - Start your work in an organized manner. How you structure the files in your project will contribute to the success of the final results.

Different programming languages have different standard folder structures. Familiarize yourself with the standards before starting as it will help others collaborate and will likely save you from difficulties later.

There are a variety of sample code structures that can be used to get started. For example, for Python there is Cookiecutter and an Astropy package template.

## What License Should We Choose for Our Code?

### Licensing Considerations when Using Open Software

[IMG: https://drive.google.com/file/d/1oE19mkXbN5LJZPjP5u1KCvbtiyfI5J_U/view?usp=drive_link]
Image Credit: NASA

Open source software licenses are the basis for how scientists use, make, and share code and software. Understanding some of the nuances of these licenses is important because it will affect how your project can license and share code.

A software license is a legal document that states the rights of the developer and user of a piece of software.

An open source license is a type of software license, approved by the Open Source Initiative (OSI) as compliant with the [Open Source Definition](https://opensource.org/osd) (external link). An open source license grants permissions for anyone to inspect, use, modify, and distribute the software's source code for any purpose.

Licenses ensure that developers receive credit and control over how their work is used. Without a license, software is assumed copyrighted and without permission. Programmers include licenses to allow reuse.

Licenses take various forms in order to outline:

- Contractual obligations (if any exist) between the developer and user.
- What the user may do with the software.
- To whom the user may distribute the software (if any such right exists).
- Length of time the user has the right to use the software.

### Some Common Types of Software License

*Click '+' to travel more information.*

<img style="width:100%;height:auto;" src="../images/media/commonsoftwarelicenses.png">
Image Credit: NASA

**Public Domain**

Anyone free to use.

**Lesser General Domain**

Can link to open source libraries, and code can be licensed under any license type.

**Permissive**

Gives users wide but not complete latitude to reuse/relicense.

**Non-permissive**

Allows users to reuse, but also gives users the responsibility to share their changes with the community.

**Copyleft**

Can be distributed or modified if all the code involved is licensed under the same license.

**Proprietary**

Cannot be copied, modified, or distributed.

---

Before you choose a license, first check with your organization or employer. They may have specific guidelines about what software license you are allowed to use. Your research grant may also stipulate permissible license types. The software management plan should specify what license you plan to use.

If a license is not shared with a code, a creative work is assumed to be copyrighted by default in the United States. It does not need to be registered, and it is assumed to be automatically protected by copyright the moment it is created. (Copyright in General, n.d.)

For software, the license is shared in a file called LICENSE at the top of the repository. It's a standard location people will know to check. It's not bad practice to put a one-line version of the license at the top of each file of code as well, with a pointer to where one can find the full license.

### Types of Open-Source Software Licenses

There are two main types of open-source licenses: permissive and protective (sometimes referred to as copy-left). The difference in these types of licenses is primarily related to the type of license that users are allowed to apply to their derivative works.

<table>
  <thead>
    <tr>
        <th>PERMISSIVE LICENSE &#9745;</th>
        <th>PROTECTIVE LICENSE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>The Open Source Initiative defines a permissive software license as a license that guarantees the freedoms to use, modify, redistribute, and create derivative works. An example of this type of license is the Apache 2.0 license by the Apache Software Foundation. It is the most popular and widely-used permissive license.</p>
            <p>Users have wide latitude for reuse under this license. They are generally free to incorporate the code into their project or use it how they wish. A user of permissive-license open source in a product could redeploy the open source software with a wide range of licenses, including proprietary closed source software.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>PERMISSIVE LICENSE</th>
        <th>PROTECTIVE LICENSE &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Protective (copy-left) licenses are a legal technique of granting certain freedoms over copies of copyrighted works with the requirement that the same rights be preserved in derivative works. This allows users to reuse the work, but it also requires users to share their changes with the community using the same license. An example of a protective license is the General Public License (GPL), which ensures users have the freedom and responsibility to share their changes with the community. It is the most widely-used protective license. These types of licenses can result in less reuse by users who may prefer or be required to only use permissive licenses.</p>
        </td>
    </tr>
  </tbody>
</table>

### Common Licenses for Open Software

Some of the most popular licenses used in open software are:

<table>
  <thead>
    <tr>
        <th>PERMISSIVE &#9745;</th>
        <th>PROTECTIVE/ COPYLEFT</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>(CAN APPLY ANY LICENSE TO DERIVATIVE WORKS)</p> 
            <ul>
              <li><a href="https://opensource.org/license/apache-2-0/">Apache License</a> (external link)</li>
              <li><a href="https://opensource.org/license/mit/">MIT license</a> (external link)</li>
              <li><a href="https://opensource.org/license/bsd-3-clause/">BSD License</a> (external link)</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>PERMISSIVE</th>
        <th>PROTECTIVE/ COPYLEFT &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>(ALL DERIVATIVE WORKS MUST DISTRIBUTE ALL ITS SOURCE CODE UNDER THE SAME LICENSE)</p>
            <ul>
              <li>GNU General Public License (<a href="https://opensource.org/license/gpl-2-0/">GPL</a>)(external link)</li>
              <li><a href="https://opensource.org/license/mpl-2-0/">Mozilla</a> Public License (external link)</li>
              <li>Common Development and Distribution License (<a href="https://opensource.org/license/cddl-1-0/">CDDL</a>) (external link)</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

For more information on different types of licenses please refer to the [Open Source Initiative OSI](https://opensource.org/licenses/category) (external link).

### Activity 3.1: Licenses

In this activity, you are asked to answer whether the following statements are true or false:

**Statement 1:**

A software license states the rights of the developer and user for a piece of software.

- True
- False

**Statement 2:**

Without a license, software is assumed copyrighted and without permissions.

- True
- False

**Statement 3:**

Anyone is free to use software with a "permissive" license with minimal restriction.

- True
- False

**Statement 4:**

Users are not allowed to copy and modify any software with a copyleft license.

- True
- False

## Programming Best Practices

In this section, you will learn some developmental phase best practices related to code review, testing, security, and availability. These best practices will improve the quality of code, reproducibility of results, and security of a project. Combined, these actions help improve the robustness of open access code and help to meet the unique challenges that can arise with multiple contributors and revisions that occur over an extended period of time.

### Code Review

Code benefits from peer review in the same way as science. Having someone else read over your code and test it can be one of the best ways to improve the quality of the code.

Many version control platforms have built-in tools that enable developers to review, comment, and iterate on each other's code. These can be done in the open and allow anyone to comment.

Here is a great example of the discussion that can happen when the original creator of an algorithm [comments on a Python implementation made by a first-time contributor to the Astropy project](https://github.com/astropy/astropy/pull/4301) (external link). The open and constructive discussion led to a better implementation of the algorithm along with possible future improvements.

Software packages can be reviewed as their own products as well. Many scientific publications now accept papers focused on software. There are entities like [PyOpenSci](https://www.pyopensci.org/about-peer-review/index.html) (external link) and the [Journal of Open Source Software](https://joss.theoj.org/) (external link) that provide open peer review of scientific packages. See more details about JOSS in the next lesson on sharing your code.

### Testing

A proven method to evaluate the reproducibility of your code is through testing. There are many types of testing, ranging from testing the smallest parts of a code to verifying if a code works as a whole under different scenarios. Code testing can include a wide range of different techniques. The following section provides only a brief introduction to the topic.

The main objective of code testing is to evaluate if a code does what its authors intended it to do. Comprehensively testing code can be very difficult as it involves testing the code for generating expected outputs as well as for failing when it should.

<table>
  <thead>
    <tr>
        <th>SCIENTIFIC VALIDATION &#9745;</th>
        <th>REPRODUCI-BILITY TESTING</th>
        <th>BUILT IN TESTS</th>
        <th>AUTOMATED TESTING</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Whether producing a script or an entire data processing pipeline, the validation of software is critical to ensuring the quality and trustworthiness of the scientific results. This could mean manually calculating the results to check the output of the code, comparing it to previously-produced results, or even having another team member test it.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>SCIENTIFIC VALIDATION</th>
        <th>REPRODUCI-BILITY TESTING &#9745;</th>
        <th>BUILT IN TESTS</th>
        <th>AUTOMATED TESTING</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Given the same inputs and parameters, can the same results be produced? Making the configuration files, input data, etc. openly available so users can easily run and produce the same published results is a critical way to increase trust in your code.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>SCIENTIFIC VALIDATION</th>
        <th>REPRODUCI-BILITY TESTING</th>
        <th>BUILT IN TESTS &#9745;</th>
        <th>AUTOMATED TESTING</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Unit tests enable software developers to bolster their confidence in their code's ability to perform as expected. Unit tests are small functions that sit outside the code base and test a specific function or run a specific test. For example, if a function takes an image and flips it horizontally, one test might check that the resulting image is the same size. Another compares the output using a known image with the expected result. Another checks that a new image is returned.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>SCIENTIFIC VALIDATION</th>
        <th>REPRODUCI-BILITY TESTING</th>
        <th>BUILT IN TESTS</th>
        <th>AUTOMATED TESTING &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Built-in tests can usually be run both manually and automatically. Most version control platforms offer services for running tests automatically. When run this way, code can be checked to see if changes raise any issues. This process of checking the code automatically as it is developed is called continuous development or continuous integration (CD/CI). If a small change made in one part of the code results in an unexpected change in another part, running the tests will uncover this immediately.</p>
        </td>
    </tr>
  </tbody>
</table>

### Minimizing the Risk of Security Vulnerabilities

Whether using open source, closed source, or commercial software, it is important to consider the security risks inherent in the development of software.

- Ensure minimal, DRY (Don't Repeat Yourself) code - this is easier to maintain and fix.
- Use global variables or key managers for credentials. Never include credentials in your code.
- Use well-tested and maintained dependencies in packages that you maintain. Keep the list of dependencies up to date.
- Create software with tools that provide automated scanning and auditing.
- If there are unsupported dependencies that you rely on, assess them to determine how they might introduce security risks and whether it would be appropriate to switch to a different package.

<table>
  <thead>
    <tr>
        <th>SECURITY TOOLS AND SECURITY VULNERABILITIES &#9745;</th>
        <th>TEST COMPONENTS AND DEPENDENCIES</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Commercial and open source tools have been developed to address the challenge of identifying the security vulnerabilities in different source components. If you do not have any technology to secure your open-source usage, you can consider using the Dependabot or <a href="https://owasp.org/">OWASP</a> (external link) dependency check tools.</p>
            <p>The Open Web Application Security Project (OWASP), is an online community that produces free tools and technologies in the field of web application security. OWASP dependency check is a utility created for developers, which identifies project dependencies and checks if they contain any known, publicly disclosed, open-source vulnerabilities.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>SECURITY TOOLS AND SECURITY VULNERABILITIES</th>
        <th>TEST COMPONENTS AND DEPENDENCIES &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Testing the security of the open source components you are using is the best way to ensure the safety of your applications and your organization. Your commitment to timely and frequent analysis of open source components should be the same as to your proprietary code.</p>
            <p>This is especially true as the component in question may have unknown security vulnerabilities or dependencies that differ with each use case. It is possible for a component to be secure in a particular application but vulnerable in another.</p>
        </td>
    </tr>
  </tbody>
</table>

### Creating FAIR Software

<table>
  <thead>
    <tr>
        <th>FINDABLE &#9745;</th>
        <th>ACCESSIBLE</th>
        <th>INTEROPERABLE</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Software includes a persistent and unique identifier and rich metadata, so it is easy for humans and machines to find.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FINDABLE</th>
        <th>ACCESSIBLE &#9745;</th>
        <th>INTEROPERABLE</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Software is retrievable from its identifier via standard communication protocols.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FINDABLE</th>
        <th>ACCESSIBLE</th>
        <th>INTEROPERABLE &#9745;</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Software interoperates with other software; it exchanges data and/or metadata via community standards.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FINDABLE</th>
        <th>ACCESSIBLE</th>
        <th>INTEROPERABLE</th>
        <th>REUSABLE &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Fully described metadata with provenance, meeting community standards. License permits reuse.</p>
        </td>
    </tr>
  </tbody>
</table>

### Additional Helpful Tips

Here are some further suggestions on how to make your code more openly available, reproducible, and transparent:

|  |  |
|---|---|
| **Descriptive Names** | Variables, functions, and similar entities should be given descriptive names as opposed to vague names. Descriptive names instantly give other programmers an idea of what the variable or function is. For example, the variable name colorOfCat is a good name because it describes what it intends to do, which is to encompass the color of a cat. |
| **Metadata File** | Consider including a metadata file for your software to make it more discoverable. A ‘codemeta.json’ can be created using [Code Meta's generator](https://codemeta.github.io/codemeta-generator/) (external link) to include with your package. |
| **Operation Documentation** | Share details about how you are running the code. For example, document the version of a software library you are using, or the version of the compiler. These are often shared in an 'environment.yml' file. |
| **Automation** | Consider the following scenario:<br><br>You are getting ready to publish your paper that includes seventeen plots that all depend on a dataset released by a mission. Right before you are about to submit, the mission releases an updated version of the dataset.<br><br> How easy will it be to recreate those plots?<br><br> Software allows you to automate the running of scripts and alert programmers when written so that input files are not hardcoding. This allows programmers to easily rerun code if an initial parameter changes. |
| **Using Standards** | Most languages have their own coding style adopted by their respective scientific communities. Following those conventions makes it easier for others to contribute to your code and makes your project more collaborative. |
| **Portability** | Allows individuals the ability to transfer their personal data between platforms. |
| **Naming** | Many historical terms used in software have negative connotations depending on the context. When considering different terms or naming, consider how different audiences may react to those terms. |

## Lesson 3: Summary

In this lesson, you learned:

- Planning a new project requires programmers to define a clear purpose, acknowledge any resource limitations, and envision a data management plan.
- Using a repository with version control allows developers to track changes across time and from multiple contributors, which can help with troubleshooting for errors and with managing a team of programers.
- A README file should include the name of a project and a short but clear description of the software.
- Licenses ensure that developers receive credit and control over how their work is used. Without a license, software is assumed copyrighted and without permissions.
- Testing, labeling, and implementing security measures are examples of programming best practices that support open science.

In addition to learning how to share your code in the next lesson, you will also have some opportunities to put this lesson into practice.

## Lesson 3: Knowledge Check

Answer the following questions to test what you have learned so far.

*Question*

**01/05**

Which of the following should be considered when planning an open software project? Select all that apply.

- The intended user audience.
- What protocol will be used to sync changes between individual contributors and the central repository.
- The programming language to be used.
- Who will financially benefit from sales of the software.

*Question*

**02/05**

Which of the following is a benefit of using a version control system in your software?

- New changes are automatically tracked.
- Different contributors can add or edit code at the same time.
- Undesirable changes can be quickly reverted.
- All of the above.

*Question*

**03/05**

Select two items that are considered best practice to include in a README file from the list below:

- A description of how to install and run the software.
- Code development history
- The most important portions of the code
- A short, plain-language paragraph about what the software is.

*Question*

**04/05**

Which of the following licenses allows users to reuse, but also requires users to share their changes with the community using the same license?

- Public Domain
- Lesser general domain
- Permissive
- Protective License
- Commercial

*Question*

**05/05**

Which of the following practices can help enhance collaboration within your project?

- Including a Code of Conduct.
- Referencing historical events in the name of your project.
- Following standards for the programming language being used.
- Developing the project privately.
- Including a Guideline for Contributors.

### References Cited

- Copyright in General. (n.d.). U.S Copy Right Office FAQ. [https://www.copyright.gov/help/faq/faq-general.html](https://www.copyright.gov/help/faq/faq-general.html) (external link)
