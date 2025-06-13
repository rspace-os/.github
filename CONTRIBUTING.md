# Contributing to the RSpace open-source project

Thank you for your interest in contributing to RSpace! Your contributions are valuable and help us advance our mission of fostering open and collaborative scientific research and the FAIRification of research data. This document will guide you through the process of contributing to RSpace. If you have any questions, concerns, or ideas how we can improve, don't hesitate to reach out to us 🙏.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Licensing](#licensing)
- [Contributor License Agreement (CLA)](#contributor-license-agreement-cla)
- [Ways to Contribute](#ways-to-contribute)
  - [Code Contributions](#code-contributions)
  - [UX and Design Contributions](#ux-and-design-contributions)
  - [Bug Reports and Feature Requests](#bug-reports-and-feature-requests)
  - [Other Contributions](#other-contributions)
- [Communication and Support](#communication-and-support)
- [Conclusion](#conclusion)

## Code of Conduct

Before getting started, please familiarize yourself with our [Code of Conduct](CODE_OF_CONDUCT.md). We expect all contributors to abide by our code of conduct to ensure a respectful and inclusive community environment.

## Licensing

Our project is licensed under the GNU Affero General Public License (AGPL) version 3.0. By contributing to our project, you agree to license your contributions under the same license. It's important to ensure that your contributions comply with the AGPL 3.0 license and do not infringe upon the rights of others. For non-code contributions we encourage the use of the Creative Commons license [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.en).

## Contributor License Agreement (CLA)

To protect the interests of both contributors and the project, we require contributors to sign a Contributor License Agreement (CLA) before their contributions can be accepted. The CLA ensures that the project has the necessary rights to use and distribute the contributed code.

- Individual contributors should sign our [Individual Contributor License Agreement](CLA.md).
- Corporate contributors should additionally sign our [Corporate Contributor License Agreement](CCLA.md).

When submitting your contributions, you will be provided with instructions on how to sign the appropriate CLA.

## Ways to Contribute

There are many ways to contribute to the RSpace project beyond just writing code. We value all types of contributions that help improve the project and its ecosystem.

### Code Contributions

To contribute code to the project, follow these general steps:

1. **⚠️ Reach Out to the Maintainers**: Before diving into work on a contribution, it is strongly recommended to reach out to the project maintainers to discuss your idea or proposed changes. This will help ensure that your efforts are aligned with the project's goals and [roadmap](https://github.com/orgs/rspace-os/projects/4). You can contact the maintainers through the communication channels listed here or in the project [wiki](https://github.com/rspace-os/rspace-web/wiki).
2. **Fork the Repository**: Start by forking the project repository to your own GitHub account. This will create a copy of the project under your account.
3. **Set Up Your Development Environment**: Set up your local development environment by following the instructions provided [here](DevDocs/DeveloperNotes/GettingStarted/GettingStarted.md). This may include installing dependencies, configuring the project, and running any necessary initialization steps.
4. **Choose an Issue**: Browse the project's issue tracker or [board](https://github.com/orgs/rspace-os/projects/10) to find an issue you would like to work on. ⚠️ Please check in with the project maintainers before diving into any work (see Step 1).
5. **Create a Branch**: Create a new branch in your forked repository to work on the chosen issue. Give the branch a descriptive name that reflects the purpose of your changes.
6. **Make Changes**: Make the necessary changes to the codebase to address the issue or implement the new feature. Ensure that your changes adhere to the project's coding style and [coding standards](https://github.com/rspace-os/rspace-web/blob/e4dc2419b7fae43a3f1d648567443ed4cce7afda/DevDocs/DeveloperNotes/GettingStarted/CodingStandards.md).
7. **Test your changes** according to the [testing requirements](https://github.com/rspace-os/rspace-web/blob/e4dc2419b7fae43a3f1d648567443ed4cce7afda/DevDocs/DeveloperNotes/GettingStarted/CodingStandards.md#testing)
8. **Commit and Push**: Commit your changes with clear and descriptive commit messages. Push your branch to your forked repository.
9. **Submit a Pull Request**: Once your changes are ready, submit a pull request (PR) from your branch to the main project repository. Provide a detailed description of the changes, including any relevant context or reasoning.
10. **Review and Iterate**: The project maintainers will review your PR and provide feedback or request changes if necessary. Engage in constructive discussions and address the feedback accordingly. Iterate on your changes until they meet the project's quality standards.
11. **Merge and Release**: Once your PR is approved, it will be merged by the core team into the main project repository. Your contribution will be included in future releases of the project.

### UX and Design Contributions

We highly value UX contributions to make RSpace more intuitive, accessible, and effective for researchers. Your UX expertise goes beyond improving a single application – it helps advance the usability of research tools and research data management (RDM) workflows across the scientific community.

#### Impact of Your UX Contributions

By contributing to RSpace's UX, you're helping to:

- Improve how researchers manage and interact with their data across the research lifecycle
- Shape more efficient workflows between RSpace and other research tools, services, and infrastructure
- Establish best practices for research software that can benefit the entire open science ecosystem
- Make FAIR (Findable, Accessible, Interoperable, Reusable) data principles more accessible through intuitive interfaces
- Reduce the learning curve for researchers adopting digital tools in their work

Besides all the above, we'll proactively look for opportunities for you to showcase your contribution in the RDM community through blog posts, conferences, and publications.

#### Types of UX Contributions

- **User Research**: Help us understand user needs through interviews, surveys, or usability studies
- **UX Design**: Create wireframes, mockups, user flows, or prototypes for new features or improvements
- **Accessibility Reviews**: Identify and suggest improvements for accessibility issues
- **Usability Testing**: Plan and conduct tests to evaluate specific aspects of RSpace and research data management workflows
- **Information Architecture**: Help organize content and functionality in logical, intuitive ways
- **Visual Design**: Improve the visual aspects of the interface while maintaining consistency

#### UX Contribution Workflow

1. **Understand the Product**: Spend some time exploring RSpace to understand its core functionality and user flows. The [documentation](https://documentation.researchspace.com) and our [community server](https://community.researchspace.com) can be a good start and but if you need access to a demo instance with complete functionality, please contact us at opensource[@]researchspace.com. Also, review the [issue tracker](https://github.com/rspace-os/rspace-web/labels/RDM%20UX) for any open UX issues which are typically labelled "RDM UX".

2. **Choose an Area to Contribute**: Please check the issue tracker for any open UX projects, feature requests, [UX research projects](https://github.com/rspace-os/rspace-web/wiki/UX-research) etc. that you could contribute to. We welcome UX contributions in several key areas:
   - Helping establish and develop our open source design system
   - Conducting usability reviews of specific features
   - Proposing design improvements for challenging interfaces
   - Establishing UX best practices for future contributors
   - Continuously developing and refining UX resources for the RSpace project

3. **Reach Out**: Contact the maintainers at opensource[@]researchspace.com to discuss your UX contribution ideas. We're especially interested in your initial thoughts and approach and explore how it fits into the development roadmap.

4. **Contribute**: For UX contributions, we typically work with:
   - Wireframes, mockups, prototypes or other design artifacts in any standard format (our preferred tool is the open-source tool [Penpot](https://penpot.app), but you can use any tool you are familiar with: Figma, Sketch, Adobe XD, or PDF).
   - Research findings as documents or presentations
   - Written reports on usability issues with screenshots and/or recordings

5. **Submit**: Share your UX contribution with the community work by:
   - Creating a new issue with your findings and attaching relevant files or attaching to relevant existing issues
   - Label your issue with the "RDM UX" tag to help categorize it properly
   - For larger design files or research materials, please contact us for the best way to share

### Bug Reports and Feature Requests

Bug reports and feature requests are valuable contributions to the project. To submit a bug report or feature request:

1. **Check Existing Issues**: Before submitting a new issue, check the existing issues to avoid duplicates.
2. **Create a New Issue**: If your bug or feature request is not already reported, create a new issue using the appropriate issue template.
3. **Provide Details**: For bug reports, provide clear steps to reproduce, expected vs. actual behavior, and any relevant screenshots or logs. For feature requests, describe the feature in detail and explain why it would be valuable to the project.
4. **Engage in Discussion**: Be ready to engage in discussions about your issue to help clarify details or explore potential solutions.

### Other Contributions

We're open to other types of contributions that can help improve the RSpace project and its community. If you have ideas for contributions not covered above, please reach out to the project maintainers to discuss your ideas.

## Communication and Support

If you have any questions, encounter issues, or need assistance during the contribution process, we encourage you to reach out for support. You can reach out to the project maintainers directly via opensource[@]researchspace.com or the contributor community as described [here](https://github.com/rspace-os/rspace-web/wiki/Contact).

## Security Issues

If you discover a security vulnerability, please DO NOT disclose it publicly in the issue tracker. Instead, follow the security reporting guidelines outlined in our [Security Policy](SECURITY.md).

## Trademarks

Please be aware of our [Trademark and Brand Usage Policy](TRADEMARKS.md) when using Research Space trademarks in your contributions or related materials.

## Conclusion

We appreciate your interest in contributing to the RSpace project. Before starting your contributions, make sure to reach out to the project maintainers to ensure alignment with the project's goals. Your contributions play a significant role in facilitating FAIR data workflows, open science and collaborative research. Please remember that you will be prompted to sign the Contributor License Agreement (CLA) before being able to submit your contributions. We look forward to working with you and building a vibrant and inclusive project community!
