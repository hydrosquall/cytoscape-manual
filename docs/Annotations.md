<a id="network_annotations"> </a>
# Network Annotations

Annotations in the form of shapes, images or text can be added to the network canvas. 

The network canvas is made up of three transparent layers:

- Foreground layer

- Network layer

- Background layer

The middle Network layer contains nodes, edges and charts. The Foreground and Background 
layers contain Annotations.

![layers.png](_static/images/Annotations/layers.png)


## Types of Annotations

There are five types of annotations available:

1. Images (loaded from image files)

2. Shapes (rectangles, triangles, etc...)

   ![type_shape.png](_static/images/Annotations/type_shape.png)

3. Text

   ![type_text.png](_static/images/Annotations/type_text.png)

4. Bounded Text (combines text with a surrounding shape)

   ![type_bounded_text.png](_static/images/Annotations/type_bounded_text.png)

5. Arrows (connects other annotations or nodes)

   ![type_arrow.png](_static/images/Annotations/type_arrow.png)

 
## The Annotations Panel

The Annotations panel shows the annotations that are currently present on the foreground and 
background layers. The panel allows you to create and delete annotations, select annotations, 
move annotations up and down, move annotations between layers, and group annotations.

![annotations_panel.png](_static/images/Annotations/annotations_panel.png)


## Creating Annotations

At the top of the a Annotations Panel there are five buttons for creating each type of annotation. 
Start by clicking the button for the type of annotation you would like to add. 

![annotations_panel_buttons.png](_static/images/Annotations/annotations_panel_buttons.png)

Alternatively, right click on the network canvas and select the annotation type under the **Add** menu.

![add_menu.png](_static/images/Annotations/add_menu.png)

### Shape, Bounded Text, Image
- Click the button for shape, bounded text or image annotation.
- Click the general location on the network canvas where the annotation should be placed.
- A dialog will appear that allows editing of the annotation properties. These properties can be edited 
  again after the annotation is created.
- Click the **Ok** button in the dialog.
- The annotation will appear on the canvas. 
- The mouse cursor is automatically moved to the canvas and the annotation is in resize mode. 
- Move the mouse cursor to resize the annotation. The annotation can be resized again later.
- Click the mouse again to stop resizing.

### Text
- Click the button for text annotation.
- Click the general location on the network canvas where the annotation should be placed.
- A dialog will appear that allows editing of the text.
- Click the **Ok** button in the dialog.
- The annotation will appear on the canvas. 

### Arrow
- Creating an arrow annotation requires there to be at least one other annotation on the network canvas.
- Click the button for arrow annotation.
- Click on an annotation on the canvas, this will be the source annotation.
- Click on another annotation on the canvas or a node, this will be the destination.
- An arrow annotation appears connecting the source and destination.


## Selecting Annotations

One or more annotations can be selected in the Annotations panel by clicking on them. 

To be able to select annotations in the network canvas
**Annotation Selection Mode** must be enabled. Toggle the 
![button_annotation_selection.png](_static/images/Annotations/button_annotation_selection.png)
button at the bottom of the network view to enable/disable annotation selection mode.

![annotation_selection_mode.png](_static/images/Annotations/annotation_selection_mode.png)

When an annotation is selected it is surrounded by a yellow selection rectangle and 8 resize 
handles are visible. The annotation can be moved by clicking on it with the mouse and dragging. 
The annotation can be resized by clicking and dragging one of the handles.

![selected.png](_static/images/Annotations/selected.png)

It is possible to select multiple annotations at the same time. Hold Ctrl on Windows, 
or Command on Mac, while clicking on each of the annotations you would like to select. 
This works both in the Annotations panel and on the network canvas. When multiple annotations 
are selected they can be moved and resized at the same time.



## Moving Annotations Backwards and Forwards

![annotations_panel_selected.png](_static/images/Annotations/annotations_panel_selected.png)

The Annotations panel displays a list of annotations on the foreground layer and a list of 
annotations on the background layer.

Annotations that are towards the top of a list are drawn above annotations lower in the list. 
To move an annotation within a layer select it and click the 
![button_up.png](_static/images/Annotations/button_up.png) button to move it forward or the
![button_down.png](_static/images/Annotations/button_down.png) button
to move it backward. To move an annotation between layers select it and click the
![button_up_2.png](_static/images/Annotations/button_up_2.png)
to move it to the foreground layer or the
![button_down_2.png](_static/images/Annotations/button_down_2.png)
button to move it to the background layer. 


## Renaming Annotations

Each annotation has a name that is displayed in the Annotations Panel. These names are primarily 
for organizational purposes and do not affect how the annotation is displayed on the canvas. To 
rename an annotation double-click the annotation in the Annotations Panel and enter the new name.


## Editing Annotations

To modify the properties of an annotation (eg, color, text) go to the Annotations panel,
right click the annotation, and select **Modify Annotation...** in the context menu.

![modify_menu.png](_static/images/Annotations/modify_menu.png)


## Deleting Annotations

To delete annotations from the annotations panel select one or more annotations and click the 
![button_trash.png](_static/images/Annotations/button_trash.png) button.

To delete annotations from the network view right click an annotation and select **Edit > Cut**.


## Grouping Annotations

Two or more annotations can be combined into a group. When grouped the annotations move and resize 
as if they were a single annotation. Groups may be nested (a group may contain other groups).

![legend.png](_static/images/Annotations/legend.png)

To create a group select two or more annotations and click the 
![button_group.png](_static/images/Annotations/button_group.png) button. The group will be given a default 
name that can be changed after the group is created. To un-group annotations select the group and click the 
![button_ungroup.png](_static/images/Annotations/button_ungroup.png) button.

A group may contain annotations from the foreground and background canvases. The group will show up in 
both the foreground and background layers in the annotations panel. 

![group_layers.png](_static/images/Annotations/group_layers.png)

Note: Deleting a group will delete all the annotations contained within the group.




