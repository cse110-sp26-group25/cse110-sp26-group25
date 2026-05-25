# Group 21 Peer Review

## Strengths
Early Implementation of CI/CD: The inclusion of .github/workflows and the recent commit adding test steps to GitHub Actions shows a strong commitment to DevOps best practices early in the development cycle.
Modular Programming: The project uses a lot of modular programming, with several different JavaScript files put in place for various functionalities. It’s allowed for the index.html file to be very clean, which is super nice. Great job there!

## Improvements 
Project Documentation: Currently, the README.md serves more as a landing page for links rather than technical documentation. It would be beneficial to add a "Getting Started" section that lists prerequisites (like Node.js version) and the exact commands (e.g., npm install, npm run dev) needed to run the project locally. It’s also important to note that there isn’t much documentation for what is actually going on in the code. This could end up looking like a document of updates or comments (such as javadoc commenting) before functions that would help a lot with reading and understanding the program.
Issue Tracking: While there is a high commit volume (168 commits), the GitHub "Issues" tab currently only has 3 open items. It could be utilized more effectively by mapping those commits to specific features or bugs, providing better visibility into the team's workload distribution.

## Questions
Mobile Usability: Have you considered how this game will translate for mobile devices? Will it function both vertically and horizontally? Are there certain features which will need adjusting or on screen buttons/additions due to the lack of keyboard / external input?

## Suggestions
Maintain the Changelog: Since you already have a CHANGELOG.md file, consider using it to document major milestones (e.g., "MVP 1.0 - Basic Issue Creation") so that viewers can easily track progress without reading the full commit history. While there is pretty good documentation within the commits made so far, having such a large amount has been burying some important information that we think could be helpful in the future. (ie. there was a journey map made with a commit message for it, but it has since been buried after being made 2 weeks ago)
