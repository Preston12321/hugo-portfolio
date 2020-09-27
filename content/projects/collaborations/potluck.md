---
title: "PotLuck"
date: 2020-02-16T11:17:57-06:00
featured: true
# description: "Delegated development tasks, researched and recommended technologies, and designed mobile and cloud architecture."
description: "<ul><li>Used Flutter, a Node.js backend, a Firestore NoSQL database, and a JSON-based REST API to create a social ingredient-tracking recipe search app</li><li>Coordinated the Agile development tasks of the team throughout the semester</li><li>Designed an application architecture that left room for redesign, scalability, and future additions</li></ul>"
tags: ["Flutter", "Firebase", "Dart", "Mobile", "Cloud", "Architecture"]
image: "img/potluck.png"
link: "https://github.com/mariecrane/PotLuck"
fact: "Coordinated development efforts for a semester-long project."
weight: 500
sitemap:
  priority : 0.8
---

PotLuck is a cross-platform mobile application that helps people find recipes based on the ingredients they already have.
You can cook alone or with friends, and the app allows you to pool together your group's available ingredients.
By removing the guesswork out of knowing what what's needed vs what you already have, PotLuck makes it easy to decide what to cook.

The app was implemented using Flutter for the UI and Firebase for the user authentication, data storage (Cloud Firestore),
and recipe search backend (Cloud Functions/Node.js). PotLuck relies heavily on the [Spoonacular Recipe API](https://spoonacular.com/food-api),
a JSON-based REST API that provides search-by-ingredient capabilities and other food-related data.
