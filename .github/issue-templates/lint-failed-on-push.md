---
title: |
  [AUTO_LINTER] Lint Failed on commit "{{ env.COMMIT_NAME }}"
labels: bug
---

Lint failed on commit `{{ env.COMMIT_SHA }}`: "{{ env.COMMIT_NAME }}" by {{ env.COMMIT_AUTHOR }}.
Lint summary:
