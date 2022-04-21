# ![](https://avatars.githubusercontent.com/u/102614006?s=20&v=4) ROSE PSE documents
[ROSE](https://github.com/road-system-editor/rose) was created as a group
project in the
["Praxis der Softwareentwicklung" (*Software Engineering Practice*)](https://pp.ipd.kit.edu/lehre/WS202122/pse/?lang=en)
course at the Karlsruhe Institute of Technology.
The goal of PSE is to build a useful application using the
[waterfall model](https://en.wikipedia.org/wiki/Waterfall_model).
This repository contains the documents that we submitted for the
different phases of the project.

Please note that the documents have not been modified since their submission and
will not be updated if ROSE is modified in the future.
Thus, they are only available in German and contain mistakes that have not been
and will not be corrected.

We hope that these documents will be useful as an example for future PSE teams
and that they provide a detailed and clear insight into the purpose and
design and development process of ROSE.

*In addition to our submissions, we included the slides for our colloquium
presentations and for our final presentation.
Since we exported the slides into the PDF format, all moving parts
(screen recordings etc.) are incomplete.
The sole purpose of these slides is to provide visual and structural aid to our
presentation and they do not reflect the content of our presentation
completely.
They do however show which topics we chose to present and how much time we
allocated for the different topics.*


## Contained Documents
1. **Planning**:
    [**`Pflichtenheft-ROSE.pdf`**](./Pflichtenheft-ROSE.pdf) describes the goals
    of this project through functional and non-functional requirements.
    It details the interactions with the system through scenarios, use case
    diagrams and user interface mockups.
    Global test cases and further test methods are specified to determine whether an
    implementation meets the expectations for the project.

    *Colloquium presentation slides:
    [`Planungsphase-slides.pdf`](./Planungsphase-slides.pdf)*

2. **Design**:
    [**`Entwurf-ROSE.pdf`**](./Entwurf-ROSE.pdf) describes the software
    architecture of the project. 
    The document specifies the object-oriented design of ROSE both through an
    object model (class and package diagrams) and through a dynamic model
    (activity, sequence and state UML diagrams).

    *Colloquium presentation slides:
    [`Entwurfsphase-slides.pdf`](./Entwurfsphase-slides.pdf)*

3. **Implementation**:
    [**`Implementierungsbericht-ROSE.pdf`**](./Implementierungsbericht-ROSE.pdf)
    describes our approach to implementing the system that we specified in the
    planning and design phases.
    We depict our schedule through a Gantt chart and describe our workflow which
    was assisted by peer-reviews and automated testing tools.
    The document also states which requirements have been implemented and what
    changes we made to our design.

    *Colloquium presentation slides:
    [`Implementierungsphase-slides.pdf`](./Implementierungsphase-slides.pdf)*

4. **Testing**:
    [**`Qualitaetssicherungsbericht-ROSE.pdf`**](./Qualitaetssicherungsbericht-ROSE.pdf)
    lays out our quality assurance process.
    In detail, we describe our automated unit tests, GUI tests and code quality
    test as well as our supervised user test and survey.
    Every bug that has been found in the process is described and analyzed.
    We also documented whether and how this bug has been or could be fixed.

    *Colloquium presentation slides:
    [`Qualitaetssicherungsphase-slides.pdf`](./Qualitaetssicherungsphase-slides.pdf)*

5. **Final presentation**:
    No document was submitted for the final presentation.

    *Final presentation slides:
    [`Abschlusspraesentation-slides.pdf`](./Abschlusspraesentation-slides.pdf)*

## License
(c) 2022 Cristian Gorun, Jannes Wagner, Max Schweikart, Philipp Seidel and Yannik Sproll

These documents licensed under the GNU General Public License v3.
The license text can be found in [`./LICENSE`](./LICENSE).

If you have used ROSE or its source code for something cool,
[we would love to hear about it](mailto:hello@maxschweik.art,contact@philipp-seidel.de?subject=I%20used%20ROSE%20for%20something%20cool!)!
