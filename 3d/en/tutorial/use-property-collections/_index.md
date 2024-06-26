---
title: Aspose.3D Use property collections
weight: 7700
limit: 
description: Learn how to use property collections
keywords: [3d scene, use, property, collections]
url: /tutorial/use-property-collections
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}


//ExSummary: Please check the following code to find out how to use 3d property collections, you can modify the code and run it directly in your browser.
//ExStepSummary:0: The following code shows how to create a new 3D scene.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Create a cylinder in the scene and place the property of the node in the PropertyCollection object.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Put the properties of the material in the PropertyCollection object and get the value from it through the property name.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;
using Aspose.ThreeD.Utilities;

//Create a new 3D scene
Scene scene = new Scene();

//ExStep:1-
//Create a cylinder in the scene
var cylinder = new Cylinder();
var node = scene.RootNode.CreateChildNode(cylinder);

//Put the node properties into a PropertyCollection object
PropertyCollection props = node.Properties;

//ExStep:2-

props["Custom-Vector"] = new Vector3(1.0, 2.0, 3.0);
props["Custom-Scalar"] = 1.0;


//ExStep:0-
scene.Save("fbx-with-user-props.fbx", FileFormat.FBX7400ASCII);
scene.Save("usd-with-user-props.usd", new UsdSaveOptions() { ExportMetaData = true} );


//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

In this tutorial, we'll learn how to use 3d property collections.

We first create a new scene using the <a href="https://www.nuget.org/packages/Aspose.3D">Aspose.3D library</a>, and then create a cylinder in the 3D scene. We create a material object, we use the PropertyCollection object to collect the properties of the material object, and then take out the properties according to the name. We can clearly see the changes in the material.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [API PbrMaterial](https://reference.aspose.com/3d/net/aspose.threed.shading/pbrmaterial/)
* [API PropertyCollection](https://reference.aspose.com/3d/net/aspose.threed/propertycollection/)
* [API Vector3](https://reference.aspose.com/3d/net/aspose.threed.utilities/vector3/)
* [API Cylinder](https://reference.aspose.com/3d/net/aspose.threed.entities/cylinder/)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}

