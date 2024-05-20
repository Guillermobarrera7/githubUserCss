# Setting Up Custom GitHub Styles with Stylus

Follow these steps to install and customize the GitHub styles using the Stylus extension:

## Step 1: Download the Stylus Extension

- **Chrome:** [Get Stylus for Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
- **Firefox:** [Get Stylus for Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
- **Edge:** [Get Stylus for Edge](https://microsoftedge.microsoft.com/addons/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)

## Step 2: Manage Styles

1. Click on the Stylus extension icon in your browser.
2. Select **Manage** to go to the Stylus management page.

## Step 3: Write a New Style

1. Click on **Write new style** to open the style editor.
2. In the editor, select **Everything** from the dropdown menu to apply the style universally.

## Step 4: Paste the Contents from the GitHub File

1. Copy the contents from the GitHub file starting from line 11:
   [GitHub Styles File](https://github.com/Guillermobarrera7/githubUserCss/blob/main/github.user.css)

2. Paste the copied contents into the Stylus editor.

## Step 5: Replace with Your GitHub Username

1. Replace `line 18` and `line 43` with your own GitHub username.
   ```css
   :root {
       ...
       --githubUsername: "your-github-username"; /* Replace with your GitHub username */
       ...
   }

   #js-issues-search.subnav-search-input:not([value*="your-github-username"]) { /* Replace with your GitHub username */
       color: red;
   }
