# Dwakof's Tweaks
Divinity: Original Sin 2 mod with tweaks we enjoy.

<details>
  <summary>List of changes</summary>
  
  - Reduced AP requirement for Raining Blood to 1
  - Increased cooldown of Raining Blood to 6 turns
</details>

## Env setup

1. Download "The Divinity Engine 2" from Steam (Tools)
2. Download the "Divinity Engine 2 Data" DLC for the game and ensure you have the `DefEd/Data/Editor` folder and its contents 
3. Open a shell window in the `DefEd/Data` directory of the game (File > Open Windows PowerShell)
4. Run:
```
git init
git remote add origin https://github.com/Dwakof/dwakofs_tweaks
git pull origin main
```
This will pull the repo into your game dir.

## Making changes

Make sure you always have the latest changes pulled before you do any work, otherwise conflicts in this project will be a royal pain to deal with:

```
git pull origin main
```

Once you've changed stuff:

```
# commit all your changes
git commit -a -m "Made some changes"
git push origin main
```

Alternatively, after the initial setup, you might prefer to user [GitHub Desktop](https://desktop.github.com/).
