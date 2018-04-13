---
title: Service Account
id: service-account
date: 2018-04-12
full-link: /docs/tasks/configure-pod-container/configure-service-account/
tags:
- fundamental
- core-object
short_description: >
  Provides an identity for processes that run in a {{< glossary_tooltip text="Pod" term_id="pod" >}}.

---

When processes inside Pods access the cluster, they are authenticated by the API server as a particular service account, for example, `default`. When you create a Pod, if you do not specify a service account, it is automatically assigned the default service account in the same namespace {{< glossary_tooltip text="Namespace" term_id="namespace" >}}.

