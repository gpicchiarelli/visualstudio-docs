---
title: "Creating new Projects and Solutions"
description: "This article describes how to create projects and solutions in Visual Studio for Mac"
author: heiligerdankgesang 
ms.author: dominicn
manager: dominicn
ms.date: 02/28/2022
ms.topic: how-to
---
# Create a new project in Visual Studio for Mac

 [!INCLUDE [Retirement announcement for Visual Studio for Mac](includes/vsmac-retirement.md)]

## Opening the project creation dialog

There are a few ways to create a new project in Visual Studio for Mac. When you first open Visual Studio for Mac, the start window is shown. From here, you can select **New** which takes you to the project creation screen.

> [!TIP]
> Additionally, from the start window, you can also open and search for recent projects and solutions. You can also open recent projects by going to the menu bar and choosing **File > Recent Solutions**

![Start window with create new project](media/first-run-project.png)

If Visual Studio for Mac is already open with a solution loaded, you can create a new solution by going to the menu bar and choosing **File > New Solution**. Creating a new solution this way closes the solution that is already loaded.

## Creating a new project

The **New Project** dialog, by default, will show your recently used templates sorted by *most recently used*.

If you don't want to use a recent template, you can choose from the categories on the left of the dialog. Each category contains several project templates for you to choose from. Clicking on a project type allows you to see a description on the right side of the screen.

![New project screen](media/project-creation-screen.png)

## Configuring your new project

Once you have chosen a project template, the following screens will take you through any configuration steps required to set up the project; which can vary by project type.

All projects require a new project, along with a location to store the files. If the project is part of a new solution, rather than adding it to an existing solution, a solution name will also be required.

Optionally, at this stage you can also configure Git source control options. The following image is an example of the final configuration step for a .NET Core project:

![Configuring a new project](media/configure-new-project.png)

## Adding additional projects to a solution

You can add additional projects to a solution by right-clicking the solution in the **Solution Window** and choosing either **Add > Add New Project** or **Add > Add Existing Project**.

Adding a new project will take you through project creation, as shown in [Configuring Your New Project](#configuring-your-new-project).

Choosing to add an existing project will allow you to browse for an existing project on your machine and add it to the solution.

## See also

- [Create solutions and projects (Visual Studio on Windows)](/visualstudio/ide/creating-solutions-and-projects)
