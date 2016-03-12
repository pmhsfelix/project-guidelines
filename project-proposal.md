# Guideline for the project proposal

The project proposal should include the following items.

* The project title, students names and contacts (phone and email), as well as the supervisor's names.

* An brief introduction stating the project goals and motivation.
    * The introduction should be followed by the proposal's chapter/section structure. 

* A "state of the art" section, comparing the proposed project with similar systems. 

* The project requirements
    * For projects with a user interface, we recommend the use of [user stories](https://en.wikipedia.org/wiki/User_story)
        * Each user story should have an unique identifier, so that it can be cross-referenced from other project documentation, such as the deliverables.
        * The user stories should use a language that is understandable by the users. Namely, some user stories can be written by potential users.
        * The user story list can be quite big. Select a relevant subset for inclusion on the main proposal. Have the complete requirement list in the online documentation.
    * The project requirements can also include a first version of the domain model, identifying entities and relations between them. The domain description can be informal at this phase.
        
* The project planned weekly schedule
    * A table with a row per week, numbered from 1 to `N`, where `N` is the length of the project in weeks (e.g. 22)
    * Each row should describe the week's activities as well as the planned deliverables
        * Each deliverable should be mapped into a concrete artifact or deployment, such as source code files, documentation. 
            * "Define the database schema", "Identify and document the possible replication strategies" are examples of adequate deliverables.
            * "Study MongoDB" is an example of an inadequate deliverable.
        * The project online documentation should include a copy of this weekly schedule with links to the completed deliverables.
    * The schedule should also include the project proposal creation. Namely, the project proposal should be the first delivery in the schedule. 
     
* Depending on the time available for creating the project proposal, it can already contain the project's _high level design_ (HLD).
    * The HLD contains the high-level component architecture, identifying the components and their relations. Examples are:
        * Android native application, using the HTTP API.
        * Single Page Application, using the HTTP API.
        * HTTP API implementing the domain logic and using a RDBMS.
        * RDBMS with all the stored domain data, accessed exclusively by the HTTP API.
    * The HLD can also map the components into concrete technologies, including the choice rationale. Familiarity with a technology is a valid reason for choosing it.
    * If the HLD is not completed until the project proposal delivery, then it should be the first thing to complete in the schedule.

* The project proposal should be available in the online project documentation.




