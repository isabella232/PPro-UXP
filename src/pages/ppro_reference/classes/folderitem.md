---
id: "folderitem"
title: "FolderItem"
sidebar_label: "FolderItem"
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

# FolderItem

## Properties

| Name | Type | Access | Min Version | Description |
| :------ | :------ | :------ | :------ | :------ |
| name | *string* | R | 23.0 | Get name of project item object |


## Methods

### createBinAction
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Returns an action that lets users create a new bin.

#### Parameters
| Name | Type |
| :------ | :------ |
| name | *string* |
| makeUnique | *boolean* |
    
___

### createBin
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Creates a new bin with given name and returns the Folder object. If second param (makeUnique) is true, we make sure the newly created bin has a unique name.

#### Parameters
| Name | Type |
| :------ | :------ |
| name | *string* |
| makeUnique | *boolean* |
    
___

### createSmartBinAction
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Creates a smart bin with given name and returns the Folder object

#### Parameters
| Name | Type |
| :------ | :------ |
| name | *string* |
| searchQuery | *string* |
    
___

### createRenameBinAction
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Rename the Bin and return true if it's successful

#### Parameters
| Name | Type |
| :------ | :------ |
| undefined | *string* |
    
___

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

### getItems
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*Array*

Collection of child items of this folder.


___

### createRemoveItemAction
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Creates an action that removes the given item from this folder.

#### Parameters
| Name | Type |
| :------ | :------ |
| item | [*ProjectItem*](/ppro_reference/classes/projectitem/) |
    
___

### removeItem
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Removes the given item from provided folder and returns a promise

#### Parameters
| Name | Type |
| :------ | :------ |
| item | [*ProjectItem*](/ppro_reference/classes/projectitem/) |
    
___

### createMoveItemAction
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Creates an action that moves the given item to the provided folder item newParent.

#### Parameters
| Name | Type |
| :------ | :------ |
| item | [*ProjectItem*](/ppro_reference/classes/projectitem/) |
| newParent | [*FolderItem*](/ppro_reference/classes/folderitem/) |
    
___

### moveItem
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Moves the given project item to the provided folder item and returns a promise

#### Parameters
| Name | Type |
| :------ | :------ |
| item | [*ProjectItem*](/ppro_reference/classes/projectitem/) |
| newParent | [*FolderItem*](/ppro_reference/classes/folderitem/) |
    
___




