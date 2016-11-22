#2016 Tools Rundown - Asana/Trello

This post is slightly different from others, in that I have presented similar components to other posts, with the introduction of Asana or Trello for issue management.

Other features of a well-integrated collaboration stack can be seen in this example; GitLab (interchangeable with GitHub, Bitbucket or other Git/SVN/Mercurial solution). F/OSS tools from the previous post are represented as well; Gerrit, MediaWiki.

Slack features as the live chat interface of this example, though another interface can be interchanged.

![](foss.png)

### Distributed Source Code Management

GitLab offers distributed version control with Git, as well as orchestration and continuous integration - a newly added feature. This example focuses on GitLab's implementation of these two items.

GitLab's web interface offers many of the same features found in similar tools; GitHub, Bitbucket, GitBucket; repository creation, some degree of user management, SSH keys, etc.

The differentiating factors with GitLab include Public and Private repositories and the new CI feature, driving automatied build and release from within GitLab.

There is a cost associated with GitLab's Private hosted offerings, (check on whether GL can be installed on-prem)

----
### Issue Tracking

The key points of this post are the two issue management tools; Asana and Trello. Many common features are found in these apps:

- Kanban
- Issues
- Multiple projects
- Integrations with third-party tools and products

Differences exist between them, to be sure. An exhaustive list is beyond the scope of this post, so I recommend an evaluation of both. This is an excellent opportunity to look at [Zapier's](https://zapier.com/zapbook/asana/trello/) integration and automation features, keeping tasks in sync between the two.

Some things to consider:

- Issue ownership: multiple or single assignees?
- Issue creation process: email driven? API? Interface only?
- Transition states: Are they customizable or configurable to your workflows?
- Does your team need Kanban?

----
### Collaborative Documentation

As the largest, most widely used collaboration platform on Earth, the Mediawiki Foundation's 'Wikipedia' product is well-known, and offers a familiar interface for the creation and access of a broad variety of content, including images, LaTeX, diagrams, code and other types of information.

Integration with Trello or Asana is non-existant. This meanslinks to documentation spaces are created manually and are independent of the behavior of Asana or Trello. An advantage may be in the platform agnostic nature of these federated tools, making it easy to test or migrate to alternative platforms.

----
### Automation

GitLab introduced CI in October, 2016. This new feature compares with Bitbucket Pipelines and the integration of external tools like Jenkins or Bamboo.

It can manage VM's, spinning them up/down as needed for builds. and can be integrated with Slack to communicate status.

----
### Review

Gerrit's code review is featured in this example. A F/OSS project, Gerrit is used by the WMF to review the large, collaboratively developed codebase of Wikipedia.

Readily connected to git or subversion repositories, Gerrit provides a team review facility for individual commits, merges and delivers attribution through a bare-bones interface.

----
### Chat
Slack offers integration with GitLab through a number of bots, providing in-channel updates on commit activity, build status and a means of communication between individuals and teams. Providing access to external users requires the creation of an account tied to an email domain associated with the Slack instance. This may be a drawback, compared to tools like IRC, which can operate on a public server network, or with HipChat, which both allow outside users to join channels, using a username/password scheme.

Slack does not offer an on-premise or behind-the-firewall implementation, and is 100% SaaS.

---

## Other things to consider

This heterogeneous solution combines some of the less technically demanding offerings in these categories, with Trello ranking quite low on the complexity scale, offering a low barrier of entry to collaboration on issues. Fittingly, Trello's simplicity limits its utility and extensibility. Extensions are handled differnently with Trello's model, relying on API access rather than the plugin/addon model employed by Asana and JIRA means many additional features are delivered as a browser extension.

