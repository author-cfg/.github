#  Integratons

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

Integration requires configuration files (JSON & optional brand assets) for each app. These are maintained in monitored app repositories within this organization. Verified app owners submit pull requests to modify their app configuration/integration. PRs are instantly approved upon automated validation.

> [!IMPORTANT]
> Widely used software may already have an AI-managed repository. These are created automatically in a best-effort to support community needs. They may contain mistakes. Owner-managed configurations are marked as such in the Author application with the intent of increasing end user confidence in owner-maintained software.

## Geting Started

1. Add `.author.cfg` to your repository root, or within the `.github` directory. This file contains the GitHub users you trust to maintain your integration.

```js
// .author.cfg
github_username_1
github_username_2
...
```

2. Install the [Author Software Integration GitHub App](https://github.com/apps/author-software-integration) on your repository. 
   
   _⚠️ This application only has one permission on your repo: to read the `.author.cfg` file._

3. The users in the `.author.cfg` file will receive an invitation to the repository for your app.

4. Accept the invtiation and follow the instructions in the repo.
