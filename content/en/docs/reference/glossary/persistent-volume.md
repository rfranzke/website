---
title: Persistent Volume
id: persistent-volume
date: 2018-04-12
full-link: /docs/concepts/storage/persistent-volumes/
tags:
- core-object
- storage
short_description: >
  An API object that represents a piece of storage in the cluster. Available as a general, pluggable resource that persists beyond the lifecycle of any individual {{< glossary_tooltip text="Pod" term_id="pod" >}}.

---

PersistentVolumes (PVs) provide an API that abstracts details of how storage is provided from how it is consumed.
PVs are used directly in scenarios where storage can be created ahead of time (static provisioning).
For scenarios that require on-demand storage (dynamic provisioning), PersistentVolumeClaims (PVCs) are used instead.

