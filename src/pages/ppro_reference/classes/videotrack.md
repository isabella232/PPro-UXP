---
id: "videotrack"
title: "VideoTrack"
sidebar_label: "VideoTrack"
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

# VideoTrack

## Properties

| Name | Type | Access | Min Version | Description |
| :------ | :------ | :------ | :------ | :------ |
| name | *string* | R | 23.0 | Get the name of the track |

## Methods

### getTrackItems

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*Array*

This returns the track items of the specified media type from the given track
#### Parameters

| Name | Type |
| :------ | :------ |
| TrackItemType | *number* |
| includeEmptyTrackItems | *boolean* |

___

### subscribeToEvent

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*boolean*

Propagates the given event on this object.
#### Parameters

| Name | Type |
| :------ | :------ |
| string | *string* |

___

### getMediaType

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*object*

UUID representing the underlying media type of this track

___

### getIndex

<span class="minversion" style="display: block; margin-bottom: -1em; margin-left: 36em; float:left; opacity:0.5;">23.0</span>

*number*

Index representing the track index of this track within the track group.

___

## Events

| Name | Version | Description |
| :------ | :------ | :------ |
| EVENT_TRACK_CHANGED | 23.0 | Event Object for Track changed |
| EVENT_TRACK_INFO_CHANGED | 23.0 | Event Object for Track Info Changed |
| EVENT_TRACK_LOCK_CHANGED | 23.0 | Event Object for Track Lock Changed |
