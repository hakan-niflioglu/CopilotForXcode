# <img align="center" height="70" src="./Docs/AppIcon.png"/> GitHub Copilot For Xcode

<img alt="Demo of GitHub Copilot for Xcode" src="./Docs/demo.gif" width="577" />

GitHub Copilot for Xcode is macOS application and Xcode extension that enables
using GitHub Copilot code completions in Xcode.

## Beta Preview Policy

As per [GitHub's Terms of Service](https://docs.github.com/en/github/site-policy/github-terms-of-service#j-beta-previews) we want to remind you that:

> Beta Previews may not be supported or may change at any time. You may receive confidential information through those programs that must remain confidential while the program is private. We'd love your feedback to make our Beta Previews better.


## Requirements

- macOS 12+
- Xcode 8+
- A GitHub Copilot subscription. To learn more, visit [https://github.com/features/copilot](https://github.com/features/copilot).

## Getting Started

1. Download the latest `dmg` from: https://github.com/github/copilot-xcode/releases/latest/download/GitHubCopilotForXcode.dmg
   Updates can be downloaded and installed by the app.

1. Open the `dmg` and drag the `GitHub Copilot for Xcode.app` into the `Applications` folder.
   <br>
   <img alt="Screenshot of opened dmg" src="./Docs/dmg-open.png" width="468" />

1. On the first opening the application it will warn that it was downloaded from the internet. Click `Open` to proceed.
   <br>
   <img alt="Screenshot of downloaded from the internet warning" src="./Docs/downloaded-from-internet.png" width="372" />

1. A background item will be added for the application to be able to start itself when Xcode starts.
   <br>
   <img alt="Screenshot of background item" src="./Docs/background-item.png" width="370" />

1. Two important permissions are required for the application to operate well: `Accessibility` and `Xcode Source Editor Extension`. The first time the application is run these permissions should be requested. You may need to click `Refresh` in the settings if not prompted.
   <br>
   <img alt="Screenshot of accessibility permission request" src="./Docs/accessibility-permission-request.png" width="529" />
   <img alt="Screenshot of accessibility permission" src="./Docs/accessibility-permission.png" width="827" />
   <img alt="Screenshot of extension permission" src="./Docs/extension-permission.png" width="827" />

1. After granting the extension permission, please restart Xcode so the `Github Copilot` menu is available under the Xcode `Editor` menu.
    <br>
    <br>
    <img alt="Screenshot of Xcode Editor GitHub Copilot menu item" src="./Docs/xcode-menu.png" width="703" />

1. To sign into GitHub Copilot, click the `Sign in` button in the settings application. This will open a browser window and copy a code to the clipboard. Paste the code into the GitHub login page and authorize the application.
   <br>
   <img alt="Screenshot of sign-in popup" src="./Docs/device-code.png" width="372" />

1. To install updates, click `Check for Updates` from the menu item or in the settings application. After installing a new version, Xcode must be restarted to use the new version correctly. New versions can also be installed from `dmg` files downloaded from the releases page. When installing a new version via `dmg`, the application must be run manually the first time to accept the downloaded from the internet warning.
   <br>
   <image alt="Screenshot of update message" src="./Docs/update-message.png" width="372" />

## License

This project is licensed under the terms of the MIT open source license. Please
refer to [MIT](./LICENSE.txt) for the full terms.

## Support

We’d love to get your help in making GitHub Copilot better!  If you have
feedback or encounter any problems, please reach out on our [Feedback
forum](https://github.com/orgs/community/discussions/categories/copilot).

## Acknowledgement

Thank you to @intitni for creating the original that this project is based on.