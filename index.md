# Surfer's Spot

## Table of contents

* [Overview](#overview)
* [Team](#team)

## Overview

Idea from [Constantine Peros](https://cperos.github.io/essays/final-project-idea.html)

BowFolios is an example web application that provides pages to view and (in some cases) modify profiles, projects, and interests. It illustrates various technologies useful to ICS software engineering students, including:

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

It also provides code that implements a variety of useful design concepts, including:

* Three primary collections (Profiles, Projects, Interests) as well as three "join" Collections (ProfilesInterests, ProfilesProjects, and ProjectsInterests) that implement many-to-many relationships between them.
* Top-level index pages (Profiles, Interests, and Projects) that show how to manipulate these six collections in various ways.
* Initialization code to define default Profiles, Interests, and Projects and relations between them.
* A simple Filter page to illustrate how to perform simple queries on the database and display the results.
* Use of Meteor Methods to illustrate how to simplify implementation of multiple collection updates.
* Use of indexes to enforce uniqueness of certain fields in the collections, enabling them to serve as primary keys.
* Authentication using the built-in Meteor accounts package along with Sign Up and Sign In pages.
* Authorization examples: certain pages are public (Profiles, Projects, Interests), while other pages require login (AddProject, Filter).
* Use of Meteor Assets to initialize the database (helpful when initialization exceeds settings file size limits).

<div class="ui medium rounded images">
  <img height="500px" align="center" class="ui image" src="../images/mock-example-page.png">
</div>

## Team

Surfers Spot is designed, implemented, and maintained by Kristi Chinen, Victor Ho, Micheal Lavers, Brennan Lincoln, and Aaron Thomas.







