=======================
Project Management Plan
=======================

.. contents:: Table of Contents

Identification
--------------

Document Overview
~~~~~~~~~~~~~~~~~

This document outlines the manner in which the project will be planned 
and executed. It describes the project’s development process: how and 
when different activities will be undertaken, when stakeholders will be 
consulted, how and when the software will be released, and how changes 
to the software will be tracked. It contains additional information on 
development tools that the team will use. As requirements analysis and 
further project planning is performed, this document will describe the 
work performed (and to be performed) on the project.

Abbreviations and Glossary
~~~~~~~~~~~~~~~~~~~~~~~~~~

PO
  Product owner; main stakeholder of the project.

  
References
~~~~~~~~~~

.. Provide references to all internal and external documents. External
.. references will include industrial standards.   Document identifier 
.. Document title

+--------------+--------------------+------------------------------------------------+
| **Document** | **Document Title** | **URL**                                        |
| **ID**       |                    |                                                |
+==============+====================+================================================+
| [pep8]       | PEP-8: Python      | http://www.python.org/dev/peps/pep-0008/       |
|              | Enhancement        |                                                |
|              | Proposal 8: Style  |                                                |
|              | Guide for Python   |                                                |
|              | Code               |                                                |
+--------------+--------------------+------------------------------------------------+
| [ipy]        | The IPython        | http://ipython.org/notebook.html               |
|              | Notebook — IPython |                                                |
+--------------+--------------------+------------------------------------------------+
| [tpope]      | A Note About Git   | http://tbaggery.com/2008/04/19/a-note-about-gi |
|              | Commit Messages    | t-commit-messages.html                         |
+--------------+--------------------+------------------------------------------------+

Project Management
~~~~~~~~~~~~~~~~~~

.. This section provides the organizational structure of HMSC and the
.. responsibilities assigned to the various members of the team.

Team and Responsibilities
-------------------------

.. Describe the team, possibly with a diagram of its organization.

Two members make up the HMSC team. We mutually share most analysis,
development, and testing tasks. Their responsibilities are listed 
in detail below.

In addition to the project team, we have a project supervisor, Dr
Otso Ovaskainen. He is the one of the PI of the Digital Twins project.

+----------------+------------+-----------------------+
| **Title**      | **Name**   | **Responsibilities**  | 
+================+============+=======================+
| Team Member    | Gleb       | Software Development, |
|                | Tikhonov   | Documentation,        |
|                |            | Testing               |
+----------------+------------+-----------------------+
| Team Member    | Anis U     | Software Development, |
|                | Rahman     | Documentation,        |
|                |            | Testing               |
+----------------+------------+-----------------------+

.. _orgchart:

.. figure:: images/orgchart.png
  :align: center

  Team organization
   
Work Breakdown Structure, Tasks and Planning
--------------------------------------------

.. Through a table or otherwise, describe the tasks involved in the
.. development of your project. Through a diagram, describe your activity
.. planning.

Work Breakdown Structure and Task Estimation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. list-table:: WBS
  :header-rows:1

  * - **\#**
    -  **Work**
    -  **Estimated effort (hrs)**
  * - **1.**
    -  **PROJECT INTIALIZATION**
    -  
  * - 1.1.
    -  Project Proposal
    -  5
  * - **2.**
    -  **PROJECT PROPOSAL**
    -  
  * - 2.1.
    -  Project Management Plan
    -  5
  * - 2.2.
    -  Vision Document
    - 5
  * - 2.2.1.
    -  Perform competitive analysis
    -  5
  * - 2.2.2.
    -  Research joint species distribution modeling
    -  5
  * - 2.3.
    -  Risk Management Plan
    -  5
  * - 2.4.
    -  Activity Plan
    -  5
  * - **3.**
    -  **REQUIREMENT GATHERING**
    -  
  * - 3.1.
    -  Software Requirements Specification
    -  5
  * - 3.2.
    -  Data Gathering
    -  5
  * - 3.2.1.
    -  Research existing joint species distribution modeling
    -  5
  * - 3.2.2.
    -  Research end-to-end machine learning
    -  5
  * - 3.2.3.
    -  Research high-performance computing for machine learning
    -  5
  * - 3.3.
    -  Interview End-users
    -  5
  * - 3.4.
    -  Research Similar Solutions
    -  5
  * - **4.**
    -  **DESIGN**
    -  
  * - 4.1.
    -  Software Architecture Design
    -  150
  * - 4.1.1.
    -  Design adapter to support git
    -  3
  * - 4.1.2.
    -  Step 1: Setting the model structure and fitting the model
    -  Step 2: Examining MCMC convergence
Step 3: Evaluating model fit
Step 4: Exploring parameter estimates
Step 5: Making predictions
    -  3
  * - 4.1.3.
    -  Design cell based diff algorithm
    -  6
  * - 4.1.5.
    -  Design header based diffs
    -  3
  * - 4.1.6.
    -  Design html for diff prototype
    -  2
  * - 4.1.16.
    -  Design nbdiff.org
    -  10
  * - 4.1.17.
    -  Design selective staging
    -  3
  * - 4.1.22.
    -  Design Bitbucket integration
    -  20
  * - 4.2.
    -  User Interface Design
    - 
  * - 4.2.1.
    -  Create UI mockups
    -  10
  * - 4.2.2.
    -  Design UI for cell based diffs
    -  3
  * - **5.**
    -  **PROTOTYPE**
    -  
  * - 5.1.1.
    -  Design prototype version of diff algorithm
    -  5
  * - 5.1.3.
    -  Design UI for diff prototype
    -  3
  * - 5.1.5.
    -  Design tests for js for diff prototype
    -  4
  * - 5.1.7.
    -  Implement protype version of diff algorithm
    -  15
  * - 5.1.9.
    -  Implement html for merge prototype
    -  2
  * - 5.1.11.
    -  Implement tests for js for merge prototype
    -  2
  * - 5.1.13.
    -  Perform usability testing of prototype
    -  5
  * - **6.**
    -  **SOFTWARE DEVELOPMENT**
    -  
  * - 6.1.
    - Development
    -  
  * - 6.1.1.
    -  Implement nbdiff.org
    -  20
  * - **7.**
    -  **TESTING AND QUALITY ASSURANCE**
    -  
  * - 7.1.
    -  Test Plan
    -  
  * - 7.1.1.
    -  Design tests for adapter to support git
    -  5
  * - 7.2.
    -  Unit Testing
    -  
  * - 7.2.1.
    -  Implement tests for adapter to support git
    -  12
  * - 7.3.
    -  User Interface Testing
    -  
  * - 7.3.1.
    -  Perform usability testing
    -  20
  * - **8.**
    -  **INTEGRATION**
    -  
  * - 8.1.
    -  Integration Testing
    -  25
  * - **9.**
    -  **DEPLOYMENT/ROLLOUT**
    -  
  * - 9.1.
    -  Define Configuration and Readme Files
    -  4
  * - 9.2.
    -  Define Online Help
    -  
  * - 9.2.1.
    -  Documentation for nbdff-docs.readthedocs.org
    -  25
  * - 9.3.
    -  Installation and User Guide
    -  
  * - 9.3.1.
    -  Document installation instructions
    -  12
  * - 9.3.2.
    -  Document user guide
    -  10
  * - 9.4.
    -  Maintain and Update Documentation
    -  69
  * - **10.**
    - **PROJECT PLANNING**
    - 
  * - 10.1.
    -  Team Meetings
    -  196
  * - 10.2.
    -  Stakeholder Meetings
    -  98

Activity Planning
~~~~~~~~~~~~~~~~~

At the beginning of each release cycle (see “Software Development
Process” below) we will work with our stakeholder to determine the
features that will be developed in that cycle. They will be chosen based
on stakeholder opinion, and their relative value and risk;
high-risk/high-value features will be developed before
low-risk/low-value features.

We will incorporate feedback from each release of our software into the
planning for our next release, adjusting the project requirements
accordingly.

The general approach to activity planning is described in the following
diagram; it should not be taken as an outline of our specific project.

.. _gantt:

.. figure:: images/iidevgantt.png
  :align: center

Activity planning and development model example (image from
http://upload.wikimedia.org/wikipedia/commons/0/05/Development-iterative.gif)

See the *Activity Plan*

Planned Effort and Earned Value
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. list-table:: WBS
  :header-rows:1

  * - 
    - **M1**
    - **M2** 
    - **M3**
    - **M4** 
    - **M5** 
    - **M6** 
  * - Planned effort (hrs)
    - 196.5
    - 378
    - 217
    - 358
    - 245
    - 215
  * - Actual effort (hrs)
    - 295
    - 337
    - 247
    - 358
    - 452
    - 396
  * - Earned value (hrs)
    - 196.5
    - 378
    - 192
    - 202
    - 359
    - 282
    
See *Hour Tracking* for detailed breakdown of Actual Effort
    
Resource Identification
-----------------------

No additional resources beyond the project team’s effort and the
resources granted to us by the capstone course are needed.

Relationships with project stakeholders
---------------------------------------

End-User Involvement
~~~~~~~~~~~~~~~~~~~~

.. Describe how end-users are involved in the development of the software:
.. meetings, reviews, feedback etc.

As our project will be an open source project, many end-users will
choose to give feedback on the GitHub issue tracker and mailing list,
before and after releases. We will also solicit feedback from the
IPython community while establishing our requirements and throughout the
development process — this will be done through the IPython mailing
list.

However, not all users are connected to the online IPython community —
particularly the ones that our stakeholder Greg Wilson would like to
target (scientists with little skill in software engineering). We will
involve these users once we have a release of the software. In
particular, we will involve them in a usability test (which we will
describe in our test plan document.)

Greg Wilson also uses the IPython Notebook himself, so the information
he provides us with will be similar to that of other end-users.

Communication
-------------

Meetings
~~~~~~~~

.. What meetings you organize during development and what is expected to
.. happen during them.

-  Initial PO meeting: We will meet our PO in person and discuss project
   requirements and goals.
-  Weekly PO meeting: We will discuss the project’s progress weekly with
   our PO in a remote meeting. We will discuss the features in progress;
   our progress towards the next release; and perform requirements
   analysis.
-  Post-release meeting: We will discuss a release of the software after
   it is published.

Reviews
~~~~~~~

.. Describe what kinds of reviews are organized during the project such as
.. design reviews, tests, code reviews etc. and what happens in these
.. reviews.

-  Code Review: Code review will be done on every pull request (i.e.,
   code change).

   -  At least one developer other than the author will review the code
      change.
   -  The reviewer(s) will annotate the code with their comments.
   -  The developer will revise their pull request to satisfy the
      reviewer.
   -  The reviewer will merge the code change into the main repository.

-  Design Review: New features will be discussed in the GitHub issue
   tracker. Feedback will be solicited from interested stakeholders.
-  Release Candidates (RCs): before each release, a release candidate
   version will be provided to the public for review. This will provoke
   feedback of various kinds.

Training
~~~~~~~~

.. Describe the training, if any, of the people involved in the project.

We started training during the summer to learn both python and
javascript by assigning two to three chapter from both programming
languages to be read by set deadlines. We would have meetings to review
the topics that had been covered in the readings and discuss if we had
any difficulties. We intend to continue this training throughout the
semester to ensure that we continue to learn both programming languages
so that we produce high quality code.

System Requirements and Project Input Data
------------------------------------------

Configuration Management
-----------------------------

Software Configuration Management
---------------------------------

.. What kind of configuration management tool is used, how and when the
.. database is saved etc

We will use Git for software configuration management. Each change to
the software will be captured in a commit on the developer’s computer.
These changes will then be uploaded to GitHub for review and merging
into the master branch.

Each commit contains a description of the change. We will follow the
recommendations found on Tim Pope’s blog post on the
subject \ `[tpope] <http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html>`__ and
enforce the rules during code review.

Documentation Configuration Management
--------------------------------------

.. Describe how you manage all documents produced, received and delivered
.. during the project.

We will use Git and GitHub
(https://github.com/tarmstrong/nbdiff-docs) to track our documents as we
produce and receive them. This will also track changes to the documents.

Software Development Management
-------------------------------

Software Development Process
----------------------------

.. Describe and justify the development model you will adopt. Include a
.. (tentative) list of minor and major milestones. For SOEN490 you are
.. expected to deliver an interim report upon reaching a major milestone.*

Our development process will be based on an iterative and incremental
model. The rationale for this choice is:

-  We wish to release functioning subsets of the final system to
   stakeholders early in the project.
-  We wish to gather feedback from stakeholders in order to adjust our
   requirements and design.
-  We wish to improve project quality by revisiting previously released
   artifacts including source code and documentation.
-  We wish to reduce project risk by implementing high-risk, high-value
   requirements first or based on the order our stakeholder prefers.

We have split the project into six major milestones spaced 5 weeks
apart. These will have equal portions of the budget allocated to them.
Each milestone will consist of a (public) release of the functioning
software and a release of updated documents to the course coordinator.
Minor milestones will be one week before each major milestone and the
output will be a release candidate of the software.

+-----------------+----------------------+
| **Milestone**   | **Milestone Date**   |
+=================+======================+
| M1              | 2013-10-21           |
+-----------------+----------------------+
| M2              | 2013-11-25           |
+-----------------+----------------------+
| M3              | 2013-12-23           |
+-----------------+----------------------+
| M4              | 2014-02-03           |
+-----------------+----------------------+
| M5              | 2014-03-03           |
+-----------------+----------------------+
| M6              | 2014-03-31           |
+-----------------+----------------------+

Software Development Tools
--------------------------

.. Describe  the environment (hardware and software, such as IDE), the
.. software configuration and all other tools (and their versions) that you
.. deploy in this project. For SOEN490: Because of the nature of this
.. exercise, there are restrictions on what you are allowed to reuse. For
.. example, you may reuse libraries, but you may not reuse entire services.
.. Please confirm with your instructor.

The following is a list of the main tools we will use while developing
this project. We will add tools to this document as we discover which
are effective for our process.

-  Git: Git is a distributed version control system for source code.
-  GitHub: is a hosting service for Git that provides a web-based
   interface to various Git features, and includes issue trackers and
   release hosting.
-  Python: is the programming language that the IPython notebook is
   written in. In order to be compatible with the Notebook’s development
   process, we will also adopt Python for our tool.

   -  Nosetests: is a unit testing tool for Python.
   -  PyFlakes: is a tool for automatically checking our Python code
      against the PEP-8 standard [pep8].
   -  Mock: is a library for mocking objects in unit tests for Python.

-  JavaScript: is the programming language supported by all major web
   browsers. Since our interface will likely be web-based, we will need
   to use this language to provide an interactive UI.

   -  Chrome Developer Tools provide a Javascript debugger and a log.
   -  PhantomJS provides a headless testing environment that mimics a
      web browser.
   -  Selenium will be used to test the web-based UI.
   -  QUnit is a unit-testing framework for Javascript.
   -  JSLint for JS quality control: http://www.jslint.com/ .

-  Chrome: Our web-based UI will targeted towards Chrome.
-  Documentation:

   -  `Epydoc <http://epydoc.sourceforge.net/>`__ is a tool to
      automatically generate API documentation from Python source code.
   -  Sphinx: is a widely-used documentation system for Python. This
      will be useful for manually written documentation (including
      installation instructions, tutorials, etc.)

-  TravisCI (https://travis-ci.org/): is a free, online continuous
   integration service that runs automated tests, checks code coverage,
   and checks code quality every time a patch is submitted to a project.
   This will be used to provide automatic verification of pull requests
   to aid reviewers.
-  GitHub: is a free, online service for code hosting, code review,
   issue/bug tracking, and release management.

Software Development Rules and Standards
----------------------------------------

For our source code (both functional code and test code), we will adhere
to the following standards. Where possible, we will use a tool to
automatically verify that our code adheres to the standard. We will also
verify this through our code reviews.

-  Coding standard for Python: PEP-8 [pep8]
-  Enforced by PyFlakes: https://pypi.python.org/pypi/pyflakes
-  JavaScript JSLint coding standard
-  Enforced by the JSLint tool: http://www.jslint.com/

For architectural documentation, we will use the Unified Modeling
Language (UML).

Test Phases Management
----------------------

Unit tests
~~~~~~~~~~

New patches to the system will be required to include unit tests where
appropriate. Patches related to bugs will be required to include
regression tests where appropriate.

Our coverage goals are:

-  Python: statement coverage of at least 60%
-  JavaScript: code coverage tools for JavaScript are immature. Thus we
   will not track our JavaScript code coverage numerically. We will
   instead use our judgement when reviewing additions to the code base
   and request additional tests when necessary.

Integration Tests
~~~~~~~~~~~~~~~~~

To test multiple components of the software, we will use the unit
testing frameworks listed above when the integration is between
components in a shared language. In the case of testing integration
between JavaScript and Python components, we will use Selenium, a
browser automation tool.

System Tests
~~~~~~~~~~~~

Before each release of our software, we will perform manual testing of
the full system on the target platforms. This will be described in our
test plan document.

Where possible, system tests will be scripted with Selenium to ensure
reproducible results.

Verification Tests
~~~~~~~~~~~~~~~~~~

.. Describe how verification tests are (will be) managed. For example you
.. may split verification tests in two phases: alpha and beta.

A week before each release of our software, we will release a “Release
Candidate” (RC) version of our release in order to solicit early
feedback before publishing the final release. This will provide users a
chance to test the tool in their own environments.

Usability Tests
~~~~~~~~~~~~~~~

We will perform usability tests according to our test plan document.

Problem Resolution
------------------

.. Describe how feature requests, change requests, bug reports, questions
.. nd generally anything that is originating outside the team will be
.. handled.

We will use GitHub’s issue tracking to handle all feature requests,
change requests, inquiries, questions as well as to report bugs.
Using GitHub’s tracking feature, issues will be opened when a matter is
raised. GitHub allows us to create custom categories to easily classify
our issues. This will allow us to filter through the different requests,
inquiries and/or bugs. We will also be able to assign issues to
different individuals based on who is more qualified to handle the given
issue. Comments can be left on issues, allowing for discussion and
problem solving among other team members, as well as status updates on
the given issue. Finally, once an issue is resolved, the issue can be
closed, allowing us to easily track which issues remain.

Project architecture
--------------------

.. _orgchart:

.. figure:: source/hmsc-arch.png
  :align: center


Folder structure
----------------

The directory structure of your new project looks like this: 

```
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io
```
