#2016 Tools Rundown - GitHub

In this post, we will take a look at an integrated tools stack using a popular configuration with GitHub as SCM.

### Distributed Source Code Management

GitHub. With 38+ million projects hosted in 9 years, it has grown from concept to mission-critical infrastructure.

It is also the leading platform for collaborative software development.

----
### Issue Tracking

In this model, we show [GitHub Issues](https://guides.github.com/features/issues/), a relatively new tool from GitHub that provides some of the powerful features found in third-party products like JIRA:

- Milestones
- Labels

----
### Collaborative Documentation

GitHub Pages and Wiki exist as a convenient way to capture and collaborate on documentation for projects and components. Hosted and versioned with GitHub, they require no additional infrastructure or license.

Markdown is the native language of content in GitHub, and the Wiki provides an in-browser experience, much like Wikipedia.

The GitHub Wiki is limited in that there are no facilities for rich content, apart from what is available in Markdown, and there is no concept of feature or behavior through Add on or Plugin components.

Simple, powerful documentation can be presented, however, access control is limited to (paid) Private teams.

----
### Automation

We show Jenkins in our diagram. GitHub integrations are well-studied and [implemented in Jenkins](https://wiki.jenkins-ci.org/display/JENKINS/GitHub+Plugin) through a variety of Plugins. Triggers, automated branching and release tagging are available,

Jenkins can run behind the firewall (as can GitHub Enterprise), or the cloud-hosted CloudBees Jenkins service can be leveraged for a full SaaS Collaboration Stack.

----
### Review

GitHub Reviews are another newly introduced feature in the GitHub model, allowing collaborative review in connection with Issues.
 
----
### Chat

Keeping with the SaaS model of this example, we show Slack in use as the Chat facility.

GitHub integration with Slack is a three-step affair, and can be configured to model the team structure associated with other projects.


----

## Other things to consider

Single Sign On and Identity Management are available in the GitHub Enterprise (paid) products, and can be leveraged with CAS and SAML, or LDAP.

Jenkins and Slack can also be configured to use a SAML provider like OneLogin, Okta or similar service.




----

