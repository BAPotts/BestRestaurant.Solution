# Best Restaurants

#### By Deryck Jackson and Beverly Potts

## Description

Restaurant website for tracking restaurants by cuisine type

## Specifications

1. **Behavior:** User will be able to add a Restaurant with a name and description property
    * **Input Example:** Restaurant { name: Joe's Pasta, desc: In downtown }
    * **Output Example:** Joe's Pasta has been added to the list

2. **Behavior:** User will be able to add a Cuisine type with a name property
    * **Input Example:** Cuisine { Name: Italian }
    * **Output Example:** Italian Cuisine has been added to the list

3. **Behavior:** User will be able to add a Cuisine type to a when they create a new Restaurant
    * **Input Example:** Restaurant { Name: Joe's Pasta, Cuisine: Italian }
    * **Output Example:** Joe's Pasta has been added to the list with a cuisine type of Italian

4. **Behavior:** User will be able to search for Restaurants by Cuisine type
    * **Input Example:** Italian
    * **Output Example:** Joe's Pasta

## Setup and Installation

Software Requirements
1. .NET framework
2. A code editor (Visual Studio Code, Atom, etc.)

Acquire The Repo:
1. Click the 'Clone or Download Button
2. Alternately, Clone via Bash/GitBash: `git clone {repo}`

Editting the Code Base:
1. Open the project in your code editor; with Bash, this is done by navigating to the project directory, then `code .`
2. If you wish to run testing, you'll need the testing packages: navigate into the .Tests folder, and run `dotnet restore`

Running the program:
1. To run the program, you'll need to compile the code: `dotnet build`. This will create a compiled application in the bin/ folder.
2. Alternately, you can run the program directly with `dotnet run`.

## Bugs

No bugs

## Tech used

* C#
* ASP.NET MVC

### License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

Copyright (c) 2020 Deryck Jackson
