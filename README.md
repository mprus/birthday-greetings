# birthday-greetings
Kata for hexagonal architecutre

http://matteo.vaccari.name/blog/archives/154

Purpose

To learn about the hexagonal architecture, which is a good way to structure an application, and how to shield your domain model from external apis and systems.
Prerequisites

This is not a basic exercise. I suppose you are already familiar with TDD and refactoring. You will need a computer with Java ≥ 1.5 and a Java IDE (I assume you will use Eclipse).
Ingredients

This kata can be done in two ways; if you want to try the refactoring way, then import in Eclipse the base code (update: the up-to-date version of the exercise code is on Github). If you want to try the TDD way, start with a blank Java project.
Problem: write a program that

    Loads a set of employee records from a flat file
    Sends a greetings email to all employees whose birthday is today

The flat file is a sequence of records, separated by newlines; this are the first few lines:

last_name, first_name, date_of_birth, email
Doe, John, 1982/10/08, john.doe@foobar.com
Ann, Mary, 1975/09/11, mary.ann@foobar.com

The greetings email contains the following text:

Subject: Happy birthday!

Happy birthday, dear John!

with the first name of the employee substituted for “John”


