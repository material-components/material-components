# Components Request Policy

This document explains how the Material Components team handles requests for new components, as
well as requests for changes to the UX of existing components. UX changes include any change which
alters the appearance, behavior, or end-user interaction with a component.

By understanding the guidelines in this document the requester, as well as the Material Components
team, will save time and energy spent handling these types of requests.

## General Policy

If a new component, or addition / modification to an existing component, is not documented within
the [Material Design guidelines](https://material.google.com/), we will not officially accept it (if needed, we will consult the
Material Design core UX team for clarifications). This is to guarantee a consistent, common
baseline between all of our platforms.

There are of course exceptions to this policy. Exceptions could include platform-specific
components or behavior, such as those specific to iOS. These will be handled on a case-by-case
basis using the procedure described below.

## How We Handle UX-Related Feature Requests

When a component request is identified as being an exception to our General Policy, we will take
the following steps:

First, an engineer will discuss the feature request with their team and the requester, in order
determine whether or not a UX change is appropriate. If the engineer decides a UX change is not the
most appropriate solution, they will suggest an alternative solution or workaround.

If the engineer decides a UX change is appropriate, they will surface the request with the Material
Design UX team, and await their feedback and guidance, looping in the engineering leads for all of
the different platform teams (iOS, Android, and web) on the discussion.

Once a consensus is made by the Material Design team, the engineer will approve or close the GitHub
issue for the request. If the request is approved, the change will be integrated into the codebase
of the repo where the issue was originally opened. Furthermore, if the team decides it appropriate
to implement the change across all platforms, that work will be done as well.

## Building External Components

There may be instances where we decide we cannot incorporate a new component—or UX changes to an
existing component—directly into our codebase, yet you still feel it would be beneficial to the
community.

**In these cases we encourage you to build an external component that can integrate well with your
platform’s core component codebase.**

## Extending Existing Components

In certain instances, you may simply want to modify existing components to suit your use-case,
rather than build new ones. Each team may choose to provide guidance on how to achieve this, but in
general you are advised to follow the conventions of your platform. This could mean either
subclassing the component, overriding the component’s styles via your platform’s styling mechanism,
or some other means.

- - -

## Useful Links
- [Contributing](CONTRIBUTING.md)
- [Filing an Issue](ISSUE_TEMPLATE.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Stack Overflow](https://www.stackoverflow.com/questions/tagged/material-components) (external site)
- [Material.io](https://www.material.io) (external site)
- [Material Design Guidelines](https://material.google.com) (external site)
