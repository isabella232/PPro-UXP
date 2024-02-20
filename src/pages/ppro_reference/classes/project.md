---
id: "project"
title: "Project"
sidebar_label: "Project"
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

# Project

## Properties

| Name | Type | Access | Min Version | Description |
| :------ | :------ | :------ | :------ | :------ |
| name | *string* | R | 23.0 | The project name. |
| id | *string* | R | 23.0 | The unique identifier of the project. |


## Methods

### getActiveSequence
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Get the active sequence of the project


___

### setActiveSequence
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*boolean*

Set the active sequence of the project

#### Parameters
| Name | Type |
| :------ | :------ |
| Sequence | *object* |
    
___

### createSequence
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*Sequence*

Create a new sequence with a given name and preset path

#### Parameters
| Name | Type |
| :------ | :------ |
| name | *string* |
| presetPath | *string* |
    
___

### createSequenceFromMedia
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*Sequence*

Create a new sequence with a given name and medias

#### Parameters
| Name | Type |
| :------ | :------ |
| name | *string* |
| clipProjectItems | *Array* |
| targetBin | [*ProjectItem*](/ppro_reference/classes/projectitem/) |
    
___

### createProject
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Create a new project

#### Parameters
| Name | Type |
| :------ | :------ |
| path | *string* |
    
___

### importFiles
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*boolean*

Import files in root/target bin of the project

#### Parameters
| Name | Type |
| :------ | :------ |
| filePaths | *Array* |
| suppressUI | *boolean* |
| targetBin | [*ProjectItem*](/ppro_reference/classes/projectitem/) |
| asNumberedStills | *boolean* |
    
___

### open
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Open a project

#### Parameters
| Name | Type |
| :------ | :------ |
| path | *string* |
| openProjectOptions | [*OpenProjectOptions*](/ppro_reference/classes/openprojectoptions/) |
    
___

### close
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*boolean*

Close a project

#### Parameters
| Name | Type |
| :------ | :------ |
| closeProjectOptions | [*CloseProjectOptions*](/ppro_reference/classes/closeprojectoptions/) |
    
___

### getSequence
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Get sequence by id from the project

#### Parameters
| Name | Type |
| :------ | :------ |
| guid | *object* |
    
___

### getActiveProject
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Currently active project.


___

### getProject
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Get project referenced by given UID

#### Parameters
| Name | Type |
| :------ | :------ |
| projectGuid | *object* |
    
___

### getSequences
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*Array*

Get an array of all sequences in this project.


___

### getRootItem
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

The root item of the project which contains all items of the project on the lowest level.


___

### executeTransaction
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*boolean*

Execute undoable transaction by passing compount action

#### Parameters
| Name | Type |
| :------ | :------ |
| callback | *any* |
| undoString? | *any* |
    
___




