# Changelog

All notable changes to this project will be documented in this file.


## [1.0.0] - 2025-05-04
- Update version to 1.0.0 and enhance installation instructions in README. Added new scripts for version bumping and changelog generation in package.json. Updated GitHub Actions workflow to automate versioning and changelog creation. Improved installation steps in install.html for clarity and user guidance. (3fdd1a1)
- Implement IndexedDB caching for profile performance data and enhance data fetching logic. Added functions to store and retrieve daily profile data, improving efficiency and reducing API calls. Updated the watch script in package.json for continuous monitoring during development. (a292ead)
- Update default date range for chart display and implement cleanup function for UI. Changed the default date range from '90' to '7' for improved user experience. Added a cleanup function to remove existing chart elements before re-injecting, ensuring a fresh UI state during updates. (53aa058)
- Update manifest description for clarity and replace icon files with new versions. This change refines the extension's description and refreshes the icon assets for improved visual representation. (df240a5)
- Update GitHub Actions workflow to prepare and publish the public_dist folder. This change modifies the directory structure for deployment, ensuring that all necessary files are included in the public distribution for the extension. (2198689)
- Update GitHub Actions workflow to use personal_token for deployment. This change ensures proper authentication for pushing documentation to the gh-pages branch of the public repository. (b94a4e7)
- trigger ci (18cb44f)
- Implement user preferences for chart display and data filtering. Added options for users to customize chart types and filter metrics based on specific criteria. Enhanced storage management for saving user settings and improved UI elements for better accessibility and responsiveness. (661df40)
- Remove deprecated files and update project structure. Deleted unused background scripts, content scripts, and HTML files to streamline the extension. Updated .gitignore to exclude build artifacts and logs. Adjusted TypeScript configuration for improved output management. Enhanced README for clearer setup instructions and added new build scripts for development and production. (171a086)
- Improve performance data visualization and user interaction. Added tooltip functionality for detailed metric insights on hover. Enhanced loading indicators for smoother transitions and updated chart legends for clarity. Refined responsive design elements to ensure consistent user experience across devices. (68f15be)
- Refactor performance data handling and enhance chart display. Updated data structure to store both 'This Period' and 'Last Period' metrics. Improved UI with a compare toggle for performance analysis and added loading overlays for better user experience. Enhanced chart datasets to include historical comparisons, ensuring responsive design and accessibility. (34f38b2)
- Enhance chart functionality and options page. Added y2 axis ticks callback for percentage display in charts. Updated chart styles for better accessibility and responsiveness. Implemented user-selectable default date range for performance data in options page, with storage integration for persistence. (a1ee05f)
- initial implementatnion with working charts (bf6e052)


## [1.0.250504.51885+00c6753] - 2025-05-04
- Enhance GitHub Actions workflow (00c6753)
