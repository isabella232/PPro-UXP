---
id: "clipprojectitem"
title: "ClipProjectItem"
sidebar_label: "ClipProjectItem"
repo: "uxp-premierepro"
product: "premierepro"
keywords:
  - Creative Cloud
  - API Documentation
  - UXP
  - Plugins
  - JavaScript
  - ExtendScript
  - SDK
  - C++
  - Scripting
  - Premiere Pro
---

# ClipProjectItem

## Properties

| Name | Type | Access | Min Version | Description |
| :------ | :------ | :------ | :------ | :------ |
| name | *string* | R | 23.0 | Get name of project item object |


## Methods

### getParent
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Get the root item of the project which contains all items of the project on the lowest level


___

### getProject
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Get the root item of the project which contains all items of the project on the lowest level.


___

### getContentType
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*any*

Get content type of the Project item


___

### getSequence
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*Sequence*

Get the sequence of the Project item


___

### getInPoint
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*TickTime*

Get the in point of the Project item

#### Parameters
| Name | Type |
| :------ | :------ |
| mediaType | *object* |
    
___

### getOutPoint
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*TickTime*

Get the out point of the Project item

#### Parameters
| Name | Type |
| :------ | :------ |
| mediaType | *object* |
    
___

### getMediaFilePath
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*string*

Get the media file path of the Project item.


___

### setInOutPoints
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*boolean*

Set the in or out point of the Project item

#### Parameters
| Name | Type |
| :------ | :------ |
| inPoint | [*TickTime*](/ppro_reference/classes/ticktime/) |
| outPoint | [*TickTime*](/ppro_reference/classes/ticktime/) |
    
___

### clearInOutPoints
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*boolean*

Clear the in or out point of the Project item


___




