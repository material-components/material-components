Want to contribute? Great! First, read this page (including the [small print](#the-small-print)).

# Contributing

Material Components is intended to be a full open source project that accepts contributions
from community members.

- [GitHub Issues](https://github.com/material-components/material-components-ios/issues)
  <!--{: .icon-github }-->

- [Stack Overflow "material-components-ios"](http://stackoverflow.com/questions/tagged/material-components-ios)
  <!--{: .icon-stackoverflow }-->
<!--{: .icon-list }-->

- - -

## Community Structure

Members of the core team are engineers from Google, Inc. responsible for the strategic direction of
Material Components and appointment of technical leaders from the community. The Core Team will
work with the community to accept contributions in line with the [material design
spec](http://www.google.com/design/spec).

- - -

## Questions?

If you have questions about how to use Material Components for iOS:

- Search previous questions that have been answered by visiting [Stack
  Overflow](http://stackoverflow.com/questions/tagged/material-components-ios).
- Please post questions to Stack Overflow with the tag `material-components-ios`.

- - -

## Found an Issue?

If you find a bug in the source code or a mistake in the documentation, you can help us by
[submitting an issue](https://github.com/material-components/material-components-ios/issues) to our GitHub
repository. Even better: send a fix as a [pull request](https://github.com/material-components/material-components-ios/compare/)!

- - -

## Feature Requests

You can request a new feature by [submitting an
issue](https://github.com/material-components/material-components-ios/issues) to our GitHub repository. If you
would like to implement a new feature then consider what kind of change it is:

- Major changes that you wish to contribute to the project should be discussed first on our [dev
  mailing list](https://groups.google.com/forum/#!forum/material-components-ios-discuss) so that we
  can better coordinate our efforts, prevent duplication of work, and help you to craft the change
  so that it is successfully accepted into the project.
- Small changes can be crafted and submitted to the GitHub Repository as a [pull request]
(https://github.com/material-components/material-components-ios/compare/).

- - -

## Signing the CLA

Please sign our Contributor License Agreement (CLA) before sending pull requests. For any code
changes to be accepted, the CLA must be signed. It's a quick process, we promise!

- For individuals we have a [simple click-through form]
(http://code.google.com/legal/individual-cla-v1.0.html).
- For corporations we'll need you to sign a different [agreement]
(http://code.google.com/legal/corporate-cla-v1.0.html).

- - -

## Pull requests

For major changes, it's worthwhile discussing the idea on our [mailing
list](https://groups.google.com/forum/#!forum/material-components-ios-discuss)—that way you'll get
early feedback on your idea and find out if the approach has been tried before or if someone else
is working on it. [Search our GitHub](https://github.com/material-components/material-components-ios/issues)
issues to see if anyone has proposed the idea before, too. Feature requests and bug fixes should be
tracked with issues, so file one early on and assign it to yourself once you have started it.

### Conventions

MDC follows certain [coding styles and conventions](code-conventions.md) for its code to help
everyone easily read, review, and understand our code. Please follow these conventions when
submitting pull requests.

### Tips for a good pull request

Pull requests can be hard to review if they try to tackle too many things
at once. Phabricator's
"[Writing Reviewable Code](https://secure.phabricator.com/book/phabflavor/article/writing_reviewable_code/)"
provides a set of guidelines that help increase the likelihood of your
pull request getting merged.

In short (slightly modified from the original article):

- A pull request should be as small as possible, but no smaller.
- The smallest a pull request can be is a single cohesive idea: don't
  make pull requests so small that they are meaningless on their own.
- Turn large pull requests into small pull requests by dividing large
  problems into smaller problems and solving the small problems one at
  a time.
- Write sensible pull request descriptions.

Our additions:

- A pull request should affect as few components as possible.
- Pull requests must include a modification to the CHANGELOG.md summarizing the
  change.

### Code reviews

All submissions, including submissions by project members, require review. We
allow pull requests to be filed, but we perform code reviews on codereview.cc.

### The small print

Contributions made by corporations are covered by a different agreement than
the one above, the
[Software Grant and Corporate Contributor License Agreement](https://cla.developers.google.com/about/google-corporate).

### Submitting a [Pull Request](https://github.com/material-components/material-components-ios/compare/)

Once you have code that is ready to share, please create a [pull request](https://github.com/material-components/material-components-ios/compare/) against our [GitHub
repo](https://github.com/material-components/material-components-ios). See [GitHub's documentation about pull
requests](https://help.github.com/articles/using-pull-requests) for more information.

### Subject Format
We use a simple format for titles:

- Start the title with `[ComponentName]` to identify which component a change affects. Use
  `[ComponentName|OtherComponentName]` for commits affecting multiple components, which should be
rare.
- Use `[ComponentName]!` to indicate that a change introduce a breakage: removing/renaming an
  element of the public API.
- Use `[ComponentName]?` to indicate that a change (deliberately) introduces warnings. For example
  when we mark an API deprecated.

A good example of a title is:

~~~ objective-c
[FooBar]! Removes the deprecated fooWithBar:(Bar*)bar method.
~~~

When referencing GitHub issues, use the full URL:
`https://github.com/material-components/material-components-ios/issues/nnn` instead of the shorthand `#nnn`.

Pull requests will be reviewed in [Phabricator's Differential code review
tool](http://codereview.cc) instead of directly in GitHub. When you submit your pull request, a bot
will reply with a link to the code review discussion. If you haven't done so before, create a new
account on Phabricator and join the discussion of your changes.

- - -

## License

Apache License

Version 2.0, January 2004

[http://www.apache.org/licenses](http://www.apache.org/licenses)

[https://github.com/material-components/material-components-ios/blob/develop/LICENSE](https://github.com/material-components/material-components-ios/blob/develop/LICENSE)

Copyright and License in Source Code

All source files hosted on Material Components for iOS GitHub repo must contain a comment block at
the top of the file declaring the license and copyright that applies. This text may be part of a
larger header. The wording for the license and copyright portion must be copied as follows, with
the appropriate years applied:

~~~ text

Copyright 2016-present the Material Components for iOS authors. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use
this file except in compliance with the License. You may obtain a copy of the
License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.

~~~