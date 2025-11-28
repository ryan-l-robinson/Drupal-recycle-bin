## Overview

Update: as GitPod has transitioned to Ona, combined with me having a better local Docker setup for my developer environments, I will no longer be maintaining any of the GitPod-dependent projects.

This provides a base Drupal site that can function within [GitPod](https://gitpod.io), with the addition of a soft delete / recycle bin system

## Related Blog Post

For more on how this was implemented, see [the related blog post](https://ryanrobinson.technology/websites/drupal/recycle-bin/).

## Key Files

The relevant configuration files to implement these features are:

- core.base_field_override.node.recyclable_content_type_.promote.yml
- core.entity_form_display.node.recycle_content_type_.default.yml
- core.entity_view_display.node.recycle_content_type_.default.yml
- core.entity_view_display.node.recycle_content_type_.teaser.yml
- field.field.node.recycle_content_type_.body.yml
- field.field.node.recycle_content_type_.field_flag_for_delete.yml
- field.storage.node.field_flag_for_delete.yml
- node.type.recycle_content_type_.yml
- system.action.user_add_role_action.admin.yml
- system.action.user_remove_role_action.admin.yml
- user.role.admin.yml
- views.view.content.yml

## GitPod Usage

1. Install GitPod and sign up for an account with your GitLab, GitHub, or Bitbucket account, if you haven't already. Add the browser extension.
1. Click the "GitPod" button that now appears beside this repository or your own repository.
1. Optionally launch Visual Studio Code to edit from the desktop app instead of the browser.

## Default Admin User

Username: admin
Password: ZNB*ufm1tyz4rwc@yzk
