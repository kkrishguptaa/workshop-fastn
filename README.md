# 📑 How to `fastn`?

This workshop is a part of the [EduHub Roadshow Jaipur](https://lu.ma/college-roadshow) organized [EduHub Community](https://eduhubcommunity.tech)

The `README.md` is intentional to assist you the explorer on their way to explore their project *while* or after the workshop!

## 📂 File Structure

### 💻 Project Files

```
FASTN/
-- ds.ftd - contains some configuration like the typography for the pages, add a button component
-- data.ftd - contains the data that populates the website
-- types.ftd - contains custom record types for the website

index.ftd - the source code for the home page

FASTN.ftd - package management file
```

### ⚙️ Other Files

```
.github/
-- workflows/
---- deploy.yml - github pages deployment action

.vscode/
-- settings.json - contains some vscode settings

.editorconfig - contains basic editor config

.gitignore - mentions the files that ignored by git

renovate.json - created by github app `renovate`, used for dependency upgrades in nodejs and other languages, does nothing in fastn!

README.md - the file you are reading right now!
```

## 💻 Technology Used

This project is built to demonstrate the [`fastn`](https://fastn.com) framework and uses the FTD (fifth try document) language since fastn supports it!

It also uses GitHub Actions and GitHub Pages for deployment.

## 🫣 Demo

[![Fullpage Screenshot of Website](https://github.com/xkrishguptaa/workshop-fastn/assets/135469703/c26b69c8-f2f2-4251-bcd5-1c4f8404ed3c)](https://xkrishguptaa.github.io/workshop-fastn)

View live demo - [xkrishguptaa.github.io/workshop-fastn](https://xkrishguptaa.github.io/workshop-fastn/)

## 🛠️ Workshop

- Go to [xkrishguptaa/workshop-fastn](https://github.com/xkrishguptaa/workshop-fastn)

  ![Screenshot of GitHub Repo xkrishguptaa/workshop-fastn](https://github.com/xkrishguptaa/workshop-fastn/assets/135469703/c26b69c8-f2f2-4251-bcd5-1c4f8404ed3c)

- Use this template and then create a new repo!

  ![screenshot of you doing that](https://github.com/xkrishguptaa/workshop-fastn/assets/135469703/0d2a50e6-a6ac-42ad-9081-af847f5cbd7f)

- Select the owner to be yourself and the repo name as `workshop-fastn`

  ![screenshot of you doing that](https://github.com/xkrishguptaa/workshop-fastn/assets/135469703/041bbf05-8faf-4a5a-8a37-ca81ddfe8040)

- Now, Click on `Code` and then the `Codespace` Tab, after that click on the `+` icon to create a new codespace
  ![screenshot of you doing that](https://github.com/xkrishguptaa/workshop-fastn/assets/135469703/d7fcac4e-d310-47b0-b67d-ff757336f415)

- Now you have VSCode on the web to work on this repo 🎉

- Go to `FASTN.ftd` file

  This file is the package manager, if you gave the repo name anything other than `workshop-fastn` please update all the times `workshop-fastn` is written to your repository's name for it to work!

- Open the terminal (`CTRL` + `\``) and run:

  ```bash
  bash
  source <(curl -fsSL https://fastn.com/install.sh) # installs fastn on the codespace
  # restart terminal or run "source ~/.bashrc" on linux
  fastn serve # this will start the fastn server which you can view with the link provided
  ```

- Go to `FASTN/data.ftd` file

- Have a look around the code, try to change the texts and links to make them all yours ✨

- Look at the running version of fastn server and see how it looks 🤓

- Now have a look at `index.ftd`! This is the real fastn code, the other is just variables. Read it out and I'm sure you'll understand what it is

- Boom! 🔥 you made your very own fastn website

- Now open the terminal again, click on the plus icon (top right of the terminal) to create a new instance

- Run the following commands to commit your changes:

  ```bash
  git add .
  git commit -m "my small mini link in bio"
  git push
  ```

- Now go back to your GitHub Repository, on the settings tab, then the `pages` button on the menu

  ![](https://github.com/xkrishguptaa/workshop-fastn/assets/135469703/8a123c6a-a71c-4d97-83cc-6825a39dc3b1)

- Now open the select option for the branch and select `gh-pages`

  ![](https://github.com/xkrishguptaa/workshop-fastn/assets/135469703/ac88830a-1986-4dd9-ad20-0953b1e4ac56)

- Save and you are done! Your website will soon be live at `YOUR_USERNAME.github.io/workshop-fastn`

## 🔥 Beyond the workshop

- Star the [fastn repository](https://dub.sh/krish-fastn-github)
- Join the [fastn discord](https://dub.sh/krish-fastn-discord)
- Read the [`fastn` for geeks article](https://dub.sh/krish-fastn-geeks)

## 🎉 Hope you enjoyed!

That's it for this workshop! Feel free to contact [me](https://biodrop.io/xkrishguptaa) for any doubts or to show of what you made! 😃
