# Contribution guidelines

Please follow the [code of conduct](code-of-conduct.md).

Only add YouTubers that are **awesome**! *"After all, it's a curation, not a collection"*. [What is awesome?](https://github.com/sindresorhus/awesome/blob/main/awesome.md#only-awesome-is-awesome)

<details>
  <summary>Guide for new GitHub users</summary>
  <ol>
    <li>Go to the <a href="https://github.com/JoseDeFreitas/awesome-youtubers/blob/main/readme.md">readme.md</a> file in this repository.</li>
    <li>Click on the "edit" button (the one with a pencil icon).</li>
    <li>Add the new YouTuber (following the format below and at the bottom of the proper section) and click "Commit".</li>
    <li>Click on the green button "Create pull request", fill out the template and click on the green "Create pull request" button again.</li>
    <p>That's all... it's that easy!</p>
  </ol>
</details>

## Add the YouTuber following this format

```html
[<img align="left" height="94px" width="94px" alt="Channel's avatar" src="LINK_TO_THE_AVATAR_OF_THE_YOUTUBE_CHANNEL"/>](LINK_TO_THE_CHANNEL_MAIN_PAGE)

[**NAME_OF_THE_CHANNEL**](LINK_TO_THE_CHANNEL_MAIN_PAGE) [<img height="16px" width="16px" alt="Badge for verified YouTube channels" src="badges/badge-verified.svg" title="Is a verified YouTube channel"/>](badges/README.md#verified-youtube-channel) [<img height="16px" width="16px" alt="Badge for YouTubers that upload videos weekly" src="badges/badge-weekly.svg" title="Uploads videos weekly"/>](badges/README.md#weekly-video-upload) \
Content about: EXAMPLE, EXAMPLE, EXAMPLE \
Featured playlists: `PLAYLIST 1`, `PLAYLIST 2`, `PLAYLIST 3`, `PLAYLIST 4`. \
<br/>
```

<details>
  <summary>Example:</summary>

[<img align="left" height="94px" width="94px" alt="GitHub channel's avatar" src="https://yt3.ggpht.com/a/AATXAJzVBGU-QyENevFp8etYX1iEak8Y7KEjUPsucWAvAA=s100-c-k-c0xffffffff-no-rj-mo"/>](https://www.youtube.com/user/github)

[**GitHub**](https://www.youtube.com/user/github) [<img height="16px" width="16px" alt="Badge for YouTuber that upload videos weekly" src="badges/badge-weekly.svg" title="Uploads videos weekly"/>](badges/README.md#weekly-video-upload) \
Content about: Open Source, Security, App development \
Featured playlists: `Open Source Friday`, `GitHub Satellite 2020 - Work`, `Public Roadmap`, `GitHub Artic Code Vault`.
</details>

**Only edit the words that are in ALL UPPER CASE. Leave all the other things as they are. Considerations below.**

- In the example, you see the two badges were added (verified YouTube and weekly upload badges). If the channel doesn't meet one of these requirements, remove the badge. More information on the [badges file](badges/README.md).
- If the "Featured playlists" section is shorter than 124 characters, add a `\` symbol and a `<br/>` tag on the line below. Otherwise, don't do it.
- Pay attention to all the other characters: dots, commas, asterisks, etc.
- Before making the pull request, make sure the layout looks good.

## Create the pull request content following this format

*Appears automatically when you create the pull request.*

```markdown
- **Name of the YouTuber:**
- **What is the channel about? (eg. web development, design, ...)**:
- **Which section is the channel in? (if you created a section, please specify why)**:
- **Why do you consider the YouTuber deserves a place in this list? *What does make it awesome?***:
```

<details>
  <summary>Example:</summary>

- **Name of the YouTuber**: GitHub
- **What is the channel about? (eg. web development, design, ...)**: Software Development Platform for storing repositories.
- **Which section is the channel in? (if you created a section, please specify why)**: Open Source.
- **Why do you consider the YouTuber deserves a place in this list? *What does make it awesome?***: The youtuber uploads videos every day with general-tech tutorials. These tutorials include securing your organization, finding vulnerabilities, using GitHub actions, and more. It also has pretty useful playlists where you can find talks from professionals that teach you diverse topics.
</details>
