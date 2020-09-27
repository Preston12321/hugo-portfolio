---
title: "Password Manager"
date: 2020-09-18T13:23:18-05:00
featured: true
# description: "Created a password manager with a unique audio mechanism for password strenth feedback."
description: "<ul><li>Used Qt C++ to create a password manager with an auditory mechanism for password strength feedback</li><li>Optimized algorithm for substring checking of entered passwords against popular password dictionaries</li><li>Implemented integrity-checking during the decryption of the password database</li></ul>"
tags: ["Qt","C++","Security","Algorithms"]
image: "img/password-manager.png"
link: "https://github.com/Preston12321/password-manager"
fact: "Password manager with an audio feedback mechanism for password strength"
weight: 500
sitemap:
  priority : 0.8
---

A partner and I created this application for our Computer Security and Privacy course as our final project.
The goal was to implement a basic password manager that could properly encrypt/decrypt information, as well
as provide feedback to the user about the strength of each password. I implemented most of the functionality,
including data storage and encryption, as well as the optimized algorithm for checking passwords against
pre-existing dictionaries of insecure passwords.

We created a 5-point rating system designed to be comparable to those of other typical password rating systems,
such those seen in other password managers and on account creation forms online. However, instead of simply
showing the usual color-based feedback associated with password strength meters, our program also plays sounds
typically associated with either negative or positive emotions and feelings.
