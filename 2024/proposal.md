# Google Season of Docs 2024 Proposal for Open Science Labs

Open Science Labs has been working promoting open-source development and open
science principles. Through our Incubator Program, we support the development of
innovative open source projects that contribute the community in different
areas. Effective documentation is crucial for the success and adoption of these
projects. By participating in Google Season of Docs, we aim to elevate our
documentation standards, making our projects more accessible and easier to
contribute to. As a final deliverable, this knowledge and best-practices
standards will be compiled into a project template project, SciCookie, so any
new project created with that will automatically use this new structure.

## About Open Science Labs

**Open Science Labs (OSL)** is at the forefront of advancing scientific research
through collaboration, innovation, and education. With a mission centered on
creating a more inclusive, transparent, and accessible scientific community, OSL
aims to empower researchers, educators, and students to contribute meaningfully
to the progress of science. Through initiatives such as project incubation,
partnership, and Internship Program, OSL provides a platform for collaboration,
innovation, and learning within the scientific community. Guided by the
principles of collaboration, innovation, and openness, OSL is committed to
providing the necessary tools, resources, and support to advance science and
technology in an open and accessible manner.

## About the project

### Project's problem

Keep project's documentation in good shape is a hard task, but it is also hard
when we are starting a new project and create the initial structure for the
documentation for the project.

SciCookie is a project template tool (uses cookieninja, a cookiecutter fork, as
a backend) that helps to create a good initial structure for new projects.
SciCookie also uses recommendations from pyOpenSci to improve the project
template structure and options for libraries in order to implement best
practices for new projects.

Currently, SciCookie has just a few initial structure for documentation, but it
would be also valuable to add a guideline for documentation writers, that will
guide contributors to improve the documentation quality and efficiency.

### Project's Scope

The project aims to create a guideline, and improve the initial structure
offered by SciCookie template. Additionally, it aims to improve at least one
project in the OSL Incubator as a pilot for prove the recommendations and maybe
improve back some items to the initial guide.

#### Deliverables

1. **Documentation Guideline**: Create a guidelines for writing effective and
   comprehensive documentation for Python projects.
2. **mkdocs Guideline**: Create a guideline for recommendations for creating
   mkdocs with material (https://squidfunk.github.io/mkdocs-material/). This
   guideline should have recommendations for configuring menus, sub-menus, table
   of contents, and blog posts.
3. **Pilot Project Implementation**: Apply the documentation and mkdocs
   guidelines to at least one selected incubator project, serving as pilot
   implementation.
4. **Update SciCookie**: Apply the documentation and mkdocs guidelines to the
   **SciCookie** template.


## How would we measure success?

We plan to publish a survey on google-forms and ask a few questions about the work
that will be in progress. The feedback we will be used to improve the results.

At the end, it would be expected to have at least 75% of good feedback from the
survey.

The questions will be focused on the quality of content, if there are any
missing information, and the aesthetical and functional, accessibility aspect of
the documentation page.

## Requirements

### Requirements for technical writer

Required:

- Proficiency in written English
- Experience with documentation organization or information architecture
- Communicating with community members
- Comfortable with Git, Github and pull request-driven workflows

Nice to have:

- Knowledge about Python, and mkdocs

### For Web Dev (?)

TBD

## Volunteers

@xmnlab - Main point of contact. Ivan has been contributing to the projects on
the OSL Incubator Program, and have helped writing documentation and
configuration the documentation engine for all the projects in incubation.

## Timeline

We expect that the technical writer will spend 6 months on the project, between
May and November 2024, working 10 hours per week on average. During these hours,
the technical writer will also:

- Attend OSL community meetings, specific for documentation
- Publish and spread awareness of the project

| **Dates** | **Action Items**                                                                                                                                                                                                                                                                                                                                                               |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| May       | Technical writer is hired. Orientation phase.                                                                                                                                                                                                                                                                                                                                  |
| June      | Review navigation of docs of other Open Source projects. Draft a new proposal for the docs structure ([statement of interest](https://developers.google.com/season-of-docs/docs/tech-writer-statement)). Create a PR, ask the team and community for feedback. First monthly evaluation period                                                                                 |
| July      | Finish navigation, test redirects and see if there are broken links. Talk to the OSL team to figure out contention points and common questions of new users. Review flow of "docs". Second monthly evaluation period                                                                                                                                                           |
| August    | Analyse the project "docs". Create a plan for where core concepts should go into more detail. Work with OSL maintainers and contributors to enhance the core concepts documentation.                                                                                                                                                                                           |
| September | Integrate work and ask for feedback from the community. Celebrate success so far - get a nice blog post on the website! Third monthly evaluation period                                                                                                                                                                                                                        |
| October   | Review overlap between Install docs, and use-cases. Compared with other projects. (Hopefully with what's been done in June, it will be easier to distinguish Day 1 from Day 2 tasks.) If there is a lot more work to be done to e.g. break up pieces into "tasks", maybe focus on low-hanging fruit instead. Ask for feedback again, publish. Fourth monthly evaluation period |
| November  | Tidy up loose ends. Celebrate with another blog post on the website!                                                                                                                                                                                                                                                                                                           |

## Project budget

We are aiming for a commitment of an average of 15 hours per week over the six
month period, although the scope can be adjusted as necessary to fit into the
budget, at $30 USD/hr rate.

| Budget Item        | Quantity | Amount      | Running Total   |
| ------------------ | -------- | ----------- | --------------- |
| Technical writer   | 1        | 7200.00 USD | 7200.00 USD     |
| Volunteer stipends | 2        | 500.00 USD  | 1000.00 USD     |
| **Sub-total**      | -        | -           | **8200.00 USD** |
| OC Overhead        | -        | 10%         | 820.00 USD      |
| **TOTAL**          | -        | -           | **9020.00 USD** |

## How to apply

If you are interested in participating in Google Season of Docs as a technical
writer, please do the following:

- Join the Open Science Labs channel on
  [discord](https://opensciencelabs.org/discord)
- Familiarize yourself with the
  [documentation page](https://osl-incubator.github.io/scicookie/). Particularly
  the sections
  [Contributing](https://osl-incubator.github.io/scicookie/install/),
  [User Guide](https://osl-incubator.github.io/scicookie/guide/),
  [Installation](https://osl-incubator.github.io/scicookie/install/). Getting a
  general sense of the documentation structure of the organization will be of
  help as well.
- You will need some familiarity with python and documentation technologies such
  as [mkdocs](https://www.mkdocs.org/),
  [quarto](https://quarto.org/docs/extensions/) so you can more easily
  understand the problems and background of users.
- Talk to us in **discord**, introduce yourself - we are happy to tell you more.

## Contact info

Technical writers interested in working on this project should send an email to
team@opensciencelabs.org. Please include links to your technical writing work or
portfolio/résumé/CV. Note: The application cut-off for this proposal is 10 May
2024, 23:59 UTC. We will announce the chosen applicant by 18 May.

If you have any questions, feel free to ask in our Discord server:
https://opensciencelabs.org/discord