#  Integrations

Are you an app owner/vendor who wants to integrate your application with Author Software? If so, you've found the starting point.

## Why Integrate?

Runtime is an Author application providing end users the ability to control how applications are used on their local computer. 

TODO: Complete this section.

<!--
Users manage their own preferences, such as default flags, arguments, and environment variables applied to applications (globally/user-defined context). 

- Secrets
- Telemetry
- Auditing
- Policy Enforcement (Enterprise)
-->

## How it Works

Integration requires configuration files (JSON & optional brand assets) for each app. These are maintained in monitored app repositories within this GitHub organization. Verified app owners submit pull requests to manage their app configuration/integration. PRs are instantly approved upon automated validation. Access to these repositories is granted through an automated owner verification process (see Verify Ownership).

> [!IMPORTANT]
> Widely used software may already have an AI-managed repository. These are created automatically in a best-effort to support community needs. They may contain mistakes. Owner-managed configurations are marked as such in the Author application with the intent of increasing end user confidence in owner-maintained software.

## Verify Ownership

Follow these steps to be invited to your private author-community configuration repository.

### 1. Install the [Integration App](https://github.com/apps/author-software-integration) on _your own repository_.
   
This application has no permission on your repo. It only verifies ownership. 

### 2. Accept invitation.

You should receive an invitation from GitHub to a new `author-community/owner_repo` private repository within a few minutes. Accept the invtiation and follow the instructions in the new repo. 

> [!TIP]
> The README in your new repo provides instructions to automatically add/remove trusted maintainers.

### 3. (Optional) Uninstall the GitHub App

Once verified, the Auuthor Software Integration GitHub App is no longer necessary and may be safely uninstalled from your repository.
