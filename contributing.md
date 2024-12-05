# Contributing

First setup the project according to the [readme.md](readme.md)

## Contributing to the project

Currently we are only accepting pull requests from organization members in this stage of development.

## Issue Tracking

Currently we are using Jira to track issues across both software and hardware development. For any code change there should be an associated Jira issue being worked.

## Organization Pull Requests

This is the general process organization members should follow.

- Mark your issue as in progress
- Create a new branch
  - Name should relate to the change
- Work changes on your branch
  - At this point if you are working a substantive change you are encouraged to open a pull request as a draft and request feedback during development
- Once you are ready to begin bringing your changes into master create a pull request (or unmark draft) to the `master` branch
- Resolve all merge conflicts
- Once CI is passing
  - Mark issue as resolved
  - Assign at least one reviewer or request one be assigned for you in the ticket comments
- Address any issues during review
- Once you have at least one reviwer approve and CI is passing you may merge to `master`
- Once master CI has passed, close the issue

## External Pull Requests

We are currently not accepting outside changes. If you have questions or notice something feel free to open an issue so we can discuss further.