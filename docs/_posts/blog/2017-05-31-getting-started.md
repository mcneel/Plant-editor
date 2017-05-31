---
layout: post
title: "Getting Started"
author: scott_davidson
modified:
categories: blog
excerpt:
tags: []
image:
  feature:
date: 2017-05-31
typora-root-url: ..\..\images
---

The Accurender Plant Editor is a standalone application to design, create and insert fractal based plants.

## Workflow Overview

The general workflow is as follows:

1. Open the AccuRender Plant editor.
2. Open a new template plant or existing plant that is close to the style plant you would like to make.
3. Edit the branches.
4. Edit leaves.
5. Save the plant as an AR Plant.
6. Export the plant as a Rhino (3DM), FBX or OBJ file to be inserted in any 3d product.

## Open Plant Editor

The plant editor will be under the application list in Windows: 

![{{site.url}}/images/ar-plant-editor-programs.png]({{site.url}}/images/ar-plant-editor-programs.png){: width="40%"}

The application .exe may also be found at: C:\Program Files\AccuRender Studio\ArPlantGenerator.exe

![{{site.url}}/images/blank-editor.png]({{site.url}}/images/blank-editor.png){: width="80%"}

## Open a new template plant

Plant definition can be complicated.  It is normally best to start with an existing plant that is similiar to the plant that is being modeled. To open a new template got to the File pulldown
and select New:

![{{site.url}}/images/new-template.png]({{site.url}}/images/new-template.png){: width="80%"}

Select a template plant. Then give the plant a new common name and an optional botanical name.

![{{site.url}}/images/new-plant-name.png]({{site.url}}/images/new-plant-name.png){: width="60%"}

## Editing the branches

A plant is made up of a trunk, a series of branches, then finish with leaves.  There may be many nested branches in a tree.While it can become complex to control plants, the best way to edit a try is to try a few options to see how they affect the shape of a tree. For instance click on a branch level and click on the Size > Elongation control.  Then use the mouse wheel to adjust the value.  The preview will show the results.

It is best to experiment with the values and see how they affect the tree's shape.

Materials for braches are bitmaps wrapped around the branch cylinders.  The default location for the basic textures for trunks can be found here: 

``` ....Documents\AccuRender Libraries\Plants\Bark```



## Creating Leaves

Leaves can be placed along a branch or at the end of a branch.  A leaf begins as a simple rectangular mesh.

![{{site.url}}/images/leaves-mesh.jpg]({{site.url}}/images/leaves-mesh.jpg){: width="80%"}

Applied to the mesh is a leaf bitmap that includes a transparent alpha mask channel.  The This will leave the leaf visible with the mesh being invisible during rendering.

The default location for the basic textures for trunks can be found here: 

```....Documents\AccuRender Libraries\Plants\Leaves```



## Save the plant

The default format for plants in the .ARplant format.  Save the plant in .Arplant to return to it later.



## Export the plant

To use the plant in other applications, export the plant to the Rhino (3DM), FBX or OBJ file. Go to the File pulldown > Export.

