Hello! Thank you for choosing to help contribute to one of SendGrid's open source projects. There are many ways you can contribute and help is always welcome.  We simply ask that you follow the following contribution policies.

- [CLAs, CCLAs and DCOs](#cla-dco)
- [Roadmap & Milestones](#roadmap)
- [Feature Request](#feature-request)
- [Submit a Bug Report](#submit-a-bug-report)
- [Improvements to the Codebase](#improvements-to-the-codebase)
- [Understanding the Code Base](#understanding-the-codebase)
- [Testing](#testing)
- [Style Guidelines & Naming Conventions](#style-guidelines-and-naming-conventions)
- [Creating a Pull Request](#creating-a-pull-request)
- [Code Reviews](#code-reviews)

<a name="roadmap"></a>

Please see the [Roadmap]((https://github.com/thinkingserious/sendgrid-ibm-index-open-source-workshop/blob/master/README.md#roadmap) in the README and please feel free to grab an issue. Please indicate that you have begun work on it to avoid collisions. Once a PR is made, community review, comments, suggestions and additional PRs are welcomed and encouraged.

<a name="cla-dco"></a>
## CLAs, CCLAs and DCOs

Before you get started, SendGrid requires that a SendGrid Contributor License Agreement (CLA) be filled out by every contributor to a SendGrid open source project.

Our goal with the CLA is to clarify the rights of our contributors and reduce other risks arising from inappropriate contributions.  The CLA also clarifies the rights SendGrid holds in each contribution and helps to avoid misunderstandings over what rights each contributor is required to grant to SendGrid when making a contribution.  In this way the CLA encourages broad participation by our open source community and helps us build strong open source projects, free from any individual contributor withholding or revoking rights to any contribution.

SendGrid does not merge a pull request made against a SendGrid open source project until that pull request is associated with a signed CLA. Copies of the CLA are available [here](https://gist.github.com/SendGridDX/98b42c0a5d500058357b80278fde3be8#file-sendgrid_cla).

When you create a Pull Request, after a few seconds, a comment will appear with a link to the CLA. Click the link and fill out the brief form and then click the "I agree" button and you are all set. You will not be asked to re-sign the CLA unless we make a change.

If you are unable to sign a CLA or CCLA, please [email us](mailto:dx@sendgrid.com) so that we may consider a DCO.

For the purpose of IBM Index 2018, we will make an exception to this rule if you simply add a comment saying that you agree to the [CLA](https://gist.github.com/SendGridDX/98b42c0a5d500058357b80278fde3be8#file-sendgrid_cla).

There are a few ways to contribute, which we'll enumerate below:

<a name="feature-request"></a>
## Feature Request

If you'd like to make a feature request, please read this section.

The GitHub issue tracker is the preferred channel for project feature requests, but please respect the following restrictions:

- Please **search for existing issues** in order to ensure we don't have duplicate bugs/feature requests.
- Please be respectful and considerate of others when commenting on issues

<a name="submit-a-bug-report"></a>
## Submit a Bug Report

Note: DO NOT include your credentials in ANY code examples, descriptions, or media you make public.

A software bug is a demonstrable issue in the code base. In order for us to diagnose the issue and respond as quickly as possible, please add as much detail as possible into your bug report.

Before you decide to create a new issue, please try the following:

1. Check the Github issues tab if the identified issue has already been reported, if so, please add a +1 to the existing post.
2. Update to the latest version of this code and check if issue has already been fixed
3. Copy and fill in the Bug Report Template we have provided below

### Please use our Bug Report Template

In order to make the process easier, we've included a [sample bug report template]((https://github.com/thinkingserious/sendgrid-ibm-index-open-source-workshop/.github/ISSUE_TEMPLATE)) (borrowed from [Ghost](https://github.com/TryGhost/Ghost/)). The template uses [GitHub flavored markdown](https://help.github.com/articles/github-flavored-markdown/) for formatting.

<a name="improvements-to-the-codebase"></a>
## Improvements to the Codebase

We welcome direct contributions to the sendgrid-ibm-index-open-source-workshop code base. Thank you!

<a name="understanding-the-codebase"></a>
## Understanding the Code Base

**__main__.py**

The entry point for this application. Use `args.get` to obtain any paramaters passed into the application.

**app.py**

The code to send an email is here, it is called by the `__main__.py` module.

<a name="testing"></a>
## Testing

All PRs require passing tests before the PR will be reviewed.

All test files are in the [`test`](https://github.com/thinkingserious/sendgrid-ibm-index-open-source-workshop/test) directory.

For the purposes of contributing to this repo, please update the [`test_app.py`](https://github.com/thinkingserious/sendgrid-ibm-index-open-source-workshop/tree/master/test/test_app.py) file with unit tests as you modify the code.

```bash
python -m unittest discover -v
```
