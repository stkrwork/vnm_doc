---
layout: default
title: Scene Background Hide
parent: Nodes Reference
---
# Scene Background Hide

![Scene Background Hide Node Visual]({{ site.baseurl }}/assets/images/NodeReference/scene-background-hide.png)

## Pins

### Input

| Name | Type | Description |
| --- | --- | --- |
| Execution Line In | Execution | Execution Line Input |

### Output

| Name | Type | Description |
| --- | --- | --- |
| Execution Line Out | Execution | Execution Line Output |

## On-Node Properties

| Name | Description |
| --- | --- |
| Cg | The Id of the CG to which to add the layer |

## Additional Properties

| Name | Type | Description |
| --- | --- | --- |
| Transition Event | Transition Event | How should the scene background be hidden |
| Custom Transition Event Name | FString | The name of the animation to use if Transition Event is set to Custom |
| Dont Wait For Transition To Finish | Boolean | If set to true then the dialog will automatically continue, while the scene background finishes its transition |