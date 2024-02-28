---
id: "closeprojectoptions"
title: "CloseProjectOptions"
sidebar_label: "CloseProjectOptions"
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

# CloseProjectOptions

## Properties

| Name | Type | Access | Min Version | Description |
| :------ | :------ | :------ | :------ | :------ |
| promptIfDirty | *boolean* | R | 23.0 | Get whether a prompt is shown if a project is dirty on project open/close |
| showCancelButton | *boolean* | R | 23.0 | Get whether the cancel button is shown on project open/close |
| isAppBeingPreparedToQuit | *boolean* | R | 23.0 | Get whether the app is prepared to quit when open/closing a project |
| saveWorkspace | *boolean* | R | 23.0 | Get whether your workspaces are saved when opening/closing a project |

## Methods

### setPromptIfDirty

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Set whether to prompt if a project is dirty on project open/close

#### Parameters

| Name | Type |
| :------ | :------ |
| inPromptIfDirty | *boolean* |

___

### setShowCancelButton

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Set whether to show the cancel button on project open/close

#### Parameters

| Name | Type |
| :------ | :------ |
| inShowCancelButton | *boolean* |

___

### setIsAppBeingPreparedToQuit

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Set whether the app should be prepared to quit when open/closing a project

#### Parameters

| Name | Type |
| :------ | :------ |
| inIsAppBeingPreparedToQuit | *boolean* |

___

### setSaveWorkspace

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Set whether to save your workspaces when opening/closing a project

#### Parameters

| Name | Type |
| :------ | :------ |
| inIsAppBeingPreparedToQuit | *boolean* |

___
