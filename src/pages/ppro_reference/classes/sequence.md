---
id: "sequence"
title: "Sequence"
sidebar_label: "Sequence"
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

# Sequence

## Properties

| Name | Type | Access | Min Version | Description |
| :------ | :------ | :------ | :------ | :------ |
| name | *string* | R | 23.0 | The sequence name. |
| id | *Guid* | R | 23.0 | The unique identifier of the sequence. |


## Methods

### getVideoTrackCount
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*number*

Get video track count from this sequence


___

### getAudioTrackCount
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*number*

Get audio track count from this sequence


___

### getCaptionTrackCount
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*number*

Get caption track count from this sequence


___

### getVideoTrack
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Get video track from track index

#### Parameters
| Name | Type |
| :------ | :------ |
| TrackIndex | *number* |
    
___

### getAudioTrack
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Get audio track from track index

#### Parameters
| Name | Type |
| :------ | :------ |
| TrackIndex | *number* |
    
___

### getCaptionTrack
<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

Get caption track from track index

#### Parameters
| Name | Type |
| :------ | :------ |
| TrackIndex | *number* |
    
___




