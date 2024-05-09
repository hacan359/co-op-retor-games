## Contribution Guidelines

Thank you for your interest in contributing to our project! Here are some guiding principles to help you become part of
the team.

## Getting Started

### 1. Fork the repository on GitHub and clone your fork to your development environment

```
git clone git@github.com:YOUR-GITHUB-USERNAME/co-op-retro-games.git
```

### 2. Add the main co-op-retro-games repository as an additional git remote called "upstream"

Change to the directory where you cloned project, normally, "co-op-retro-games". Then enter the following command:

```
git remote add upstream https://github.com/hacan359/co-op-retro-games
```

### 3. Pull the latest code from the main branch

```
git pull upstream main
```

### 4. Create a new branch for your feature based on the current main branch

> That's very important since you will not be able to submit more than one pull request from your account if you'll use
> master.

Branch name have free format. Example

```
git checkout upstream/main
git checkout -b add-nes-game-tmnt
```

### 5. Do your magic, write your code

Add new Roms ADD NEW Platform etc

### 6. Update the CHANGELOG.md

```
Add Tenage Mutant Ninga Turtles nes rom
```

### 7. Commit your changes

add the files/changes you want to commit to the [staging area](https://git.github.io/git-reference/basic/#add) with

```
git add path/to/my/file.php
```

You can use the `-p` option to select the changes you want to have in your commit.

```
git commit -m "add new ROMs"
```

### 8. Pull the latest code from upstream into your branch

```
git pull upstream main
```

### 9. Having resolved any conflicts, push your code to GitHub

```
git push -u add-nes-game-tmnt
```

### 10. Open a [pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) against upstream.

Go to your repository on GitHub and click "Pull Request", choose your branch on the right and enter some more details
in the comment box


## Suggestions and Fixes

If you couldn't find a particular ROM in the collection, you can add it yourself or create an Issue for its addition.

## Rules for adding new ROMs (also applies to new platforms):

* The ROM must be compatible with RetroAchievements. Compatibility can be checked on the
  website https://retroachievements.org/.
* The game should support CO-OP for 2 or more players.
* Images must be added. Images are stored in the `thumbnails` folder.

  `thumbnails/PLATFORMNAME/Named_Snaps` - Gameplay image
  `thumbnails/PLATFORMNAME/Named_Titles` - Game menu images

## Community

Be friendly and respectful to other project participants.
Answer questions and help other participants in their work.
Remember that different people may have different points of view. Be prepared for constructive criticism and
discussions.
