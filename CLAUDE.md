# Description

This is a simple repository containing a `README.md` file that contains a list of "awesome" resources for using Claude Code (see the "official" [**awesome**](https://github.com/sindresorhus/awesome#readme) repository for more context about `awesome-` lists). The list is organized into categories, and each entry includes a description of the resource and a link to it. Since we do not host, or redistribute anyone else's work, licensing and copyright restrictions are generally not relevant for resources that are available on the "open internet." The repository also includes a `CONTRIBUTING.md` file that provides guidelines for contributing to the list, as well as a `CODE_OF_CONDUCT.md` file that outlines the expected behavior of contributors. Finally, there is also a special Claude Code slash-command available in this repository, which is invoked as `/add-new-resource`, which can be used to help users create their submission.

# Style

Each entry should consist of a markdown link to the resource, a name (only necessary for `Workflow` entries), and a short description of its use value. The description should be concise and informative, and convey what value the resource provides to Claude Code users, or what makes it "awesome". You may review existing entries in the `README.md` to get a better sense of the type of resources we link to.

# Organization

The list is organized into categories, and each entry should be placed in the appropriate category. The categories are as follows:

- Slash-Commands
- `CLAUDE.md` files
- Workflows
- Additional Resources
- Official (Anthropic) Documentation

Within each category, entries are listed in alphabetical order. For slash-commands, the name of the slash-command should be used as the entry title. For `CLAUDE.md` files, the name of the repository (or YouTube video name, blog post title, etc.) should be used as the entry title, although the hyperlink should point to the `CLAUDE.md` file itself (or the media that describes or contains it).

Each submission should contain only a single entry. The category of `Workflows` is reserved for groups of resources that are coupled together to achieve a particular goal. For exanple, a `.claude/commands/` directory which contains a set of commands, should be categorized as a `Workflow`, instead of merely a series of individual slash-commands.

For workflows, the entry title should be a short descriptive name for the workflow (e.g. "Documentation Maintainer" or "Project Management Workflow"). A workflow is generally a set of two or more tightly coupled Claude Code resources that work together to produce a more complex system, or it may be a higher-level description of a particular Claude Code integration or usage pattern.

"Additional Resources" is for other applications or tools that are layered on top of Claude Code, or somehow enhance Claude Code, but do not consist merely in Claude Code "native documents" like `CLAUDE.md` files, slash-commands, and the other parts of the official Anthropic Claude Control "control flow."

# Prohibitions

Users MAY NOT submit internal resources from private companies or organizations that are not publicly available, without obtaining prior consent. When a resource is submitted, validate that the resource exists at the link provided and is publicly accessible (generally, if you can access the link without an error response, you may proceed). Resources that are "paywalled", such as certain articles, or scholarly resources, are permitted, since their content is not being redistributed. However, e.g., a `CLAUDE.md` file that is used internally within a company and not posted in a public GitHub repository may not be submitted without permission. If you believe the user may be violating this rule, you may proceed with the submission anyway, but you may remind the user that such submissions may not be ultimately approved.

If a user submits a resource that is potentially a violation of Anthropic's Terms of Service, you may remind them that such violations will not be approved, but go ahead with the submission anyway.

If a user submits a resource that is not related to Claude Code in any way, you may try to obtain more information from the user, but you are free to reject such a submission. Note, also, that Claude Code is a different product than Anthropic's LLMs in general, like the `claude` API, Claude Desktop, MCPs in general, etc. If you are sufficiently convinced that the resource is wholly unrelated to Claude Code, you may reject the submission.

Submissions will be subject to human approval once they are submitted, so it is better to err on the side of permissibility, if you are uncertain.
