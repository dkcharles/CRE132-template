# CRE132 game project

This is your own private repository (repo) for your CRE132 2D game. It keeps every version of your project safe on GitHub, so you can work on it at uni and at home, and your lecturer can see your progress.

> **Haven't made your repo yet?** [Create your CRE132 repo](https://github.com/new?template_owner=dkcharles&template_name=CRE132-template&name=CRE132-my-game&visibility=private&description=CRE132%202D%20game%20project). Change the name to `CRE132-` followed by your game's name, with no spaces (e.g. `CRE132-SpaceDodge`). Keep it **Private** and click **Create repository**.

You need: a GitHub account, [GitHub Desktop](https://desktop.github.com/), and Unity Hub with **Unity 6000.3.11f1**.

## Set up (once)

1. **Fill in `coursework.yml`.** On your repo's GitHub page, click `coursework.yml`, then the pencil icon. Add your B number, name and game title, then click **Commit changes**.
2. **Invite your lecturer.** Go to **Settings → Collaborators → Add people**, type `dkcharles` and send the invitation.
3. **Copy the repo to your computer.** In GitHub Desktop, choose **File → Clone repository**, pick your `CRE132-…` repo and click **Clone**. Note the folder it uses, usually `Documents\GitHub\CRE132-…`. If GitHub Desktop asks to initialise Git LFS, click **Initialize**.
4. **Make your Unity project inside that folder.** In Unity Hub, click **New project**, choose editor **6000.3.11f1** and the **Universal 2D** template. Set **Location** to your repo folder from step 3, give the project a name and click **Create project**. Unity puts it in a subfolder of the repo, which is fine.
5. **Save it to GitHub.** In GitHub Desktop, type a summary such as "New Unity project", click **Commit to main**, then **Push origin**.

   Before you commit, check the list of changed files. You should see `Assets`, `Packages` and `ProjectSettings`, but **no `Library` or `Temp` folder**. If you see one, stop and ask your lecturer.

## Every time you work

| When | Do this |
|---|---|
| **Starting** (at uni or at home) | Open GitHub Desktop, select your repo and click **Fetch origin**, then **Pull origin** if it appears. *Then* open Unity. |
| **While working** | Commit whenever something works: a new mechanic, a level, some art. Use a short summary like "Player can jump". |
| **Finishing** | Save in Unity and close it. In GitHub Desktop, **Commit to main**, then **Push origin**. |
| **On a uni PC** | When you're done, sign out of GitHub Desktop: **File → Options → Accounts → Sign out**. |

Never work on two computers without pushing on one and pulling on the other in between. Otherwise you'll get conflicting versions.

## Good to know

- **Big files** (images, Aseprite files, sounds, music, fonts) are stored with Git LFS automatically; you don't need to do anything. Keep raw video recordings and other huge files out of the project.
- **Your repo must stay private.** Don't make it public or add anyone else unless your lecturer says so.
- **You can replace this README** with a description of your game whenever you like. Keep `coursework.yml`.

## Problems?

- **"Library" or "Temp" shows up in GitHub Desktop:** don't commit. Your Unity project is probably more than one folder deep. Ask your lecturer.
- **Push rejected, or "newer commits on remote":** click **Pull origin** first, then push again.
- **Unity asks to upgrade the project:** close it and open the project with **6000.3.11f1** instead.
