# What is this

This a repository containing mods for [Hangman Forever](https://notexplosive.itch.io/hangman), a competetive hangman games. Mods for the game include puzzle phrases (aka: Hangman "prompts") for players to enjoy.

# How do I download a mod?

Download mod by doing the following:

- Right click a link below
- Click "Save link as" then hit "Save"
- Once downloaded, move the file into your Hangman Forever `Mods` directory, next to `base-game.hmm`.

## Wheel of Fortune Mod

[Download](https://raw.githubusercontent.com/notexplosive/hangman-mods/main/wof-31-32-33.hmm)

Puzzles aggregated from the Wheel of Fortune Compendium. Includes puzzles from seasons 31, 32, and 33.

## Game Grumps Mod

[Download](https://raw.githubusercontent.com/notexplosive/hangman-mods/main/game-grumps.hmm)

Puzzles designed by NotExplosive. Meant to be enjoyed by Game Grumps fans.

## More Mods

Want more mods? Or do you have a mod you want shared on this page? [Post and issue!](https://github.com/notexplosive/hangman-mods/issues)

# How do I make a mod?

Creating your own mod is easy, mods follow a very simple file format.

First create a text file and populate it like so:

```
My Cool Mod
A mod that I made all by myself
Coolguy McCool

> Food
Steamed Broccoli
Chopped Carrots
Roasted Potatoes

> Drinks
Americanno
Almond Latte
Chai Tea
```

Save this as a `.hmm` file and... you're done! You have a complete Hangman Forever mod. Move that file into your `Mods` directory in your Hangman Forever game files (next to `base-game.hmm`) and you're ready to roll!

The first 3 lines of the file are the "Header" of the mod, this specifies metadata about the mod. All lines after that are content contained within the mod.

- Line 1 is the title of your mod
- Line 2 is a description
- Line 3 is the byline, put the author's name here!

Any subsequent line must follow this format:

- Precede a line with a `>` to start a category. For example `>Proper Name`. You can put spaces after the `>` if you want (eg: `> Proper Name`)
- Once you've declared a category, any subsequent line is a puzzle under that category.

A few caveats:

- A puzzle can only be a maximum of 54 characters. Any longer and it won't fit on the screen.
- You may use non-alphanumeric characters (eg: punctuation) but they will be automatically filled in since they can't be guessed.
