---
title: Security Context
id: security-context
date: 2018-04-12
full-link: /docs/tasks/configure-pod-container/security-context/
tags:
- security
short_description: >
  The securityContext field defines privilege and access control settings for a Pod or Container, including the runtime UID and GID.

---

The securityContext field in a {% glossary_tooltip term_id="pod" %} (applying to all containers) or container is used to set the user (runAsUser) and group (fsGroup), capabilities, privilege settings, and security policies (SELinux/AppArmor/Seccomp) that container processes use.

