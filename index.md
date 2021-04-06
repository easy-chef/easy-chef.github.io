## Table of contents

* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Development History & Milestones](#development-history)
* [Team](#team)

## Overview

Easy Chef is an example web application that provides pages to view and (in some cases) modify profiles, recipes, and vendors. The goal is provide an application that the UH community will use in order discover simple and affordable recipes for their meals.  It illustrates various technologies including:

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

The following is what is currently planned for what the system will eventually provide:

* Three primary collections (Profiles, Recipes, Vendors) as well as two "join" Collections (ProfilesRecipes, VendorItems) that implement many-to-many relationships between them.
* Top-level index pages (Profiles, Recipes, Vendors) that show how to manipulate these five collections in various ways.
* Initialization code to define default Profiles, Recipes, Vendors and relations between them.
* Use of Meteor Methods to illustrate how to simplify implementation of multiple collection updates.
* Use of indexes to enforce uniqueness of certain fields in the collections, enabling them to serve as primary keys.
* Authentication using the built-in Meteor accounts package along with Sign Up and Sign In pages.
* Authorization examples: certain pages are public (SearchRecipes, Vendors, Profiles), while other pages require login (AddRecipe, EditProfile, EditVendor, MyRecipes).
* Use of Meteor Assets to initialize the database (helpful when initialization exceeds settings file size limits).

## Deployment

A live deployment of Easy Chef is soon to be available.

## User Guide

This section is soon to be available.

## Development History & Milestones

The development process for EasyChef utilized  [Issue Driven Project Management](http://courses.ics.hawaii.edu/ics314f19/modules/project-management/) practices. This development process consits of

* Development consists of a sequence of Milestones.
* Each Milestone is specified as a set of tasks.
* Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
* Tasks should typically consist of work that can be completed in 2-4 days.
* The work for each task is accomplished with a git branch named "issue-XX", where XX is replaced by the issue number.
* When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master.
* The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.

In order to record the development history, various Milestones will be docuemnted which is presented below.

### Milestone 1: Mockup development

Mockup development currently in progress

## Team

BowFolios is designed, implemented, and maintained by Makana Lacson-Garrett, Joshua Paino, Karen Wong, and Kat Shimomura.







