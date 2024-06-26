---
title: Aspose.3D Boolean operations on meshes
weight: 7700
limit: 
description: Learn how to do Boolean operation on meshes
keywords: [3d scene, text, font, extrusion]
url: /tutorial/boolean-operation-on-meshes
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}

{{< app/3d/tutorial-example >}}

//ExSummary: Please check the following code to find out how to create a box and attach it to a scene, you can modify the code and run it directly in your browser.
//ExFile: NotoSans-Regular.ttf:/3d/tutorial/NotoSans-Regular.ttf
//ExStepSummary:0: The following code shows how to create a scene with two overlapped meshes.
//ExStepSummary:1: The following code shows how to merge two overlapped meshes into a single manifold mesh.
//ExPostExecuteCommand:shading:wireframe
//ExStart
//ExStep:0-
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Shading;
using Aspose.ThreeD.Profiles;
using Aspose.ThreeD.Utilities;


//This feature has trial limits, turn the exception off temporarily(limits will not be lifted).
TrialException.SuppressTrialException = true;

var scene = new Scene();

//Here create a scene without using Boolean, the scene actually contains two meshes but overlapped together:
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();

//ExStep:0-0
scene.RootNode.CreateChildNode(box1);
scene.RootNode.CreateChildNode(box2);

//ExStep:1-

//Now we use `|` operator to merge them into a single manifold mesh, it is possible to be used in 3D printing:
Mesh merged = box1 | box2;
scene.RootNode.CreateChildNode(merged);



//ExStep:0-
scene
//ExEnd
{{< /app/3d/tutorial-example >}}

{{% app/3d/tutorial-main summary="You can write code here to use Aspose.3D and run the code in browser to see how it works." %}}

Aspose.3D is a powerful library for working with 3D models in various formats, providing developers with extensive features to manipulate, create, and render 3D scenes. This document outlines one of the notable features of Aspose.3D as demonstrated by the provided code snippet.

The following code snippet demonstrates how to create a scene containing two meshes without using Boolean operations, and then merge them into a single manifold mesh using the | operator:

We'll start by creating two overlapped meshes, then we merge two meshes using our operator `|` overload, finally we'll render this to your browser. 

Aspose.3D provides developers with the capability to create complex 3D scenes and manipulate meshes efficiently. The ability to merge meshes without using Boolean operations offers flexibility and ease of use, particularly in scenarios such as 3D printing where manifold meshes are required. This feature enhances the capabilities of Aspose.3D, making it a valuable tool for 3D graphics development and manipulation.

* [Installation of Aspose.3D](https://docs.aspose.com/3d/net/installation/)
* [3D Editor](https://products.aspose.app/3d/editor/)
* [API operator `|`](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/op_bitwiseor/)
* [API operator `&`](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/op_bitwiseand/)
* [API operator `-`](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/op_subtraction/)
* [API DoBoolean](https://reference.aspose.com/3d/net/aspose.threed.entities/mesh/doboolean)
* [API Scene](https://reference.aspose.com/3d/net/aspose.threed/scene/)

{{% /app/3d/tutorial-main %}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}