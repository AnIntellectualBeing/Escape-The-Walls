# Escape the Walls Privacy Policy

This folder is a complete Escape the Walls mini-site and privacy policy, ready to publish with GitHub Pages.

## Before publishing

The policy currently assumes:

- the game does not require an account;
- game progress and preferences are stored locally;
- Google AdMob is the only third-party SDK that processes user data;
- the game does not currently sell in-app products; and
- the game is not specifically directed to children under 13.

If the app uses Firebase Analytics, Crashlytics, another ad network, cloud saves, login, analytics, or any other SDK, update the policy before publishing.

## Publish using your GitHub repository

1. Open your repository: https://github.com/AnIntellectualBeing/Escape-The-Walls
2. Upload `index.html`, `privacy_policy.html`, `styles.css`, `.nojekyll`, and the complete `assets` folder to the root of the repository.
3. Open the repository's **Settings**.
4. Select **Pages** under **Code and automation**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main**, folder **/(root)**, and then **Save**.
7. Wait a few minutes for GitHub Pages to publish.

Your URL should be:

```text
https://AnIntellectualBeing.github.io/Escape-The-Walls/
```

Open the URL in an incognito/private window. It must load without requiring a GitHub login.

## Add it to Google Play Console

1. Open your app in Google Play Console.
2. Go to **Policy and programs > App content**.
3. Under **Privacy policy**, select **Start** or **Manage**.
4. Paste the direct privacy-policy URL:

```text
https://AnIntellectualBeing.github.io/Escape-The-Walls/privacy_policy.html
```
5. Save.

Also place a clickable Privacy Policy link inside the game's Settings or About screen when required by your app's data practices and target audience.

## Future changes

Update the policy before releasing features that change data handling, including:

- Google Play Billing or in-app purchases;
- account login;
- cloud saves;
- Firebase Analytics or Crashlytics;
- additional advertising networks;
- multiplayer, leaderboards, or social features; or
- a change to the app's intended age audience.

After editing the policy, change the **Last updated** date in `privacy_policy.html`.
