---
meta.Title: "Contribute to Umbraco CMS"
meta.Description: "An explanation of how you can contribute to the Umbraco Documentation, what the process is and what things to keep in mind when contributing."
---
# Contribute to the Umbraco Documentation

The Umbraco Documentation is presented here on [Our Umbraco](https://our.umbraco.com/documentation), however it is also a [GitHub repository](https://github.com/umbraco/UmbracoDocs) and is as open source as the [Umbraco CMS](https://github.com/umbraco/Umbraco-CMS)!

You can contribute to the documentation if something is missing or outdated, all you need to do it is a GitHub account.

In this section you can learn more about how to contribute.

## How to get started

There are many ways in which you can contribute to the Umbraco Documentation. The approach you choose to take, depends on what you want to achieve with your contribution.

* Request a quick / minor change to an article by submitting a [Pull Request](Pull-Requests/#option-1-creating-a-pr-directly-on-github)
* Submit a more extensive update / change by [forking the Documentation repository](Pull-Requests/#options-2-creating-a-pr-through-a-fork)
* Raise a question, start a discussion or report an issue on the [Issue Tracker](Issues/)
* Help improve readability of the documentation by verifying articles against our [Style Guide](Style-Guide/#test-the-docs-yourself).

## [Style guide](Style-Guide/index.md)

We have a few rules to follow when writing documentation and we have some tools you can use to help.

## [Format, naming conventions and files](Markdown-Conventions)

The Umbraco Documentation is written using the MarkDown markup language. We've put together [an article where you can learn more about MarkDown](https://our.umbraco.com/Documentation/Contribute/Markdown-Conventions). You will also find an overview of the folder and file structure we use.

## Multi version documentation

Whenever a new version of Umbraco is released, the previous way of doing things may change. This means that there will have to be multiple articles on the same topic, but with different variations.

Therefore we've introduced **versioned documentation**, which includes 2 different mechanisms:

1. The [YAML meta data](Adding-Metadata/index.md) describing `versionFrom` and `versionTo`.
2. The possibility to [add multiple files about the same topic](File-Naming-Conventions/index.md)

## [Adding meta data](Adding-Metadata/index.md)

You can add meta data to any article in the Umbraco Documentation. This includes `meta title` and `meta description` as well as information on the versioning of the article.

## Labels

On both Issues and Pull Requests we use labels to categorize the requests and submissions.

Here's a quick explanation of the labels groups (colors) we use:

* **Category** (e.g. `category/missing-documentation`, `category/umbraco-cloud`, `category/pending-release`)
* **Community** (e.g. `community/pr`, `help wanted`)
* **State** (e.g. `state/hq-discussion`)
* **Status** (e.g. `status/awaiting-feedback`, `status/idea`)
* **Type** (e.g. `type/bug`)

Labels will be added to your Pull Request or Issue once it has been reviewed.

## Documentation Curators

All the work of adding labels, going through Issues & Pull Requests and managing the Documentation repository is done by the Umbraco Documentation Curators team. If you wish to know more about who they are and how they work there is more information about them here: https://our.umbraco.com/get-involved/the-documentation-curators/

## Contribution badge

If your Pull Request to any Umbraco repository gets merged, you'll receive a Contributor badge on your profile on [Our Umbraco](https://our.umbraco.com):

![Contributor badge on Our](images/c-trib-badge.png)

The Documentation Curators team will search for your profile when merging your Pull Request and add the badge.
If you do not receive your badge, write a comment with your profile's URL on the Pull Request and we'll look into it.
