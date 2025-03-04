---
title: 'Edit XML Files'
ms.date: 11/04/2016
description: Explore how to use the XML editor in Visual Studio to edit many different file types, including files that contain XML or DTD content.
ms.topic: how-to
author: dzsquared
ms.author: drskwier
manager: jmartens
ms.technology: vs-xml-tools
---
# Edit XML files

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]

The XML editor is the new editor for XML files. It can be used on a stand-alone XML file, or on a file associated with a Visual Studio project. The XML editor is associated with the following file extensions: *.config*, *.dtd*, *.xml*, *.xsd*, *.xdr*, *.xsl*, *.xslt*, and *.vssettings*. The XML editor is also associated with any other file type that has no specific editor registered, and that contains XML or DTD content.

> [!NOTE]
> XHTML documents are handled by the HTML Editor.

To edit an XML file, open the file you want to edit.

## Add a new XML file to a project

1. From the **Project** menu, select **Add New Item**.

2. Select **XML File** from the **Templates** pane.

3. Enter the filename in the **Name** field and press **Add**.

   The XML file is added to the project and opens in the XML editor. The file contains the default XML declaration, `<?xml version="1.0" encoding="utf-8" ?>`.

## Add an existing XML file to a project

1. From the **Project** menu, select **Add Existing Item**.

   The **Add Existing Item** dialog box appears.

2. Select an XML file and press **Add**.

## Create a new XML or XSLT file

1. From the **File** menu, select **New**.

   The **New File** dialog box appears.

2. Select **XML File** to create a new XML file; or, select **XSLT File** to create a new XSLT style sheet.

3. Select **Open**.

## Create an empty project for XML files

1. From the **File** menu, select **New** > **Project**.

2. Enter **Empty Project** in the template search box, select the **Empty Project (.NET Framework)** template, and then select **Next**.

3. Select **Create**.

4. Add XML files to the project.

   The XML editor finds the schemas you add to this project and uses them for validation and IntelliSense in any XML, schema, or XSLT files that you edit while this project is open.

## See also

- [XML editor](../xml-tools/xml-editor.md)
- [XML document properties, properties window](../xml-tools/xml-document-properties-properties-window.md)
- [How to: Create an XML schema from an XML document](../xml-tools/how-to-create-an-xml-schema-from-an-xml-document.md)
