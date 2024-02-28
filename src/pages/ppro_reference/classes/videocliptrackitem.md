---
id: "videocliptrackitem"
title: "VideoClipTrackItem"
sidebar_label: "VideoClipTrackItem"
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

# VideoClipTrackItem

## Methods

### createAddVideoTransitionAction

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*Action*

Create add transition action for sequence

#### Parameters

| Name | Type |
| :------ | :------ |
| Transition | *object* |
| AddTransitionOptionsProperties | [*AddTransitionOptions*](/ppro_reference/classes/addtransitionoptions/) |

___

### createRemoveVideoTransitionAction

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*Action*

Returns true if trackItem has transition

#### Parameters

| Name | Type |
| :------ | :------ |
| TransitionPosition | *number* |

___

### getComponentChain

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*VideoComponentChain*

Returned Promise will be fulfilled with the value of component chain associated with this track item


___

### getStartTime

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*TickTime*

Timecode representing the start of this track item relative to the sequence start.


___

### getEndTime

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*TickTime*

Timecode representing the end of this track item relative to the sequence start.


___

### getDuration

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*TickTime*

Timecode representing the duration of this track item relative to the sequence start.


___

### getType

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*number*

Index representing the type of this track item.


___

### getMediaType

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

UUID representing the underlying media type of this track item


___

### getTrackIndex

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*number*

Index representing the track index of the track this track item belongs to


___

### getProjectItem

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

The project item for this track item.


___
