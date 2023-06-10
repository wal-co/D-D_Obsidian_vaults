---
{"dg-publish":true,"permalink":"/using-obsidian/obsidian/","tags":["ObsidianMD, Tutorial"],"noteIcon":""}
---

# What is this?

ObsidianMD is a powerful Markdown File wrapper. Basically put, all these files related to D&D are on your computer, but it works like a personal wiki without needing internet connection.<br><br>I have provided information that is both general to D&D as well as information that is specific to today's one-shot. If we decide to continue this in the future it will be fairly easy for me to add new information to your vault, so you can track our play from week to week while also having easy access to all the books and materials

# How do I navigate?

```ad-note
title: Navigation on a Tablet
collapse: closed
I did not write this help doc with tablets in mind. If you are using an iPad I can help you navigate. If you are using an android tablet I can *try* to help you.
```


- There is an icon in the top left corner that looks like a page with a column. This is your side bar and will be how you see the files and folders
	- There are other options in this side menu, you can explore what they are on your own
- Beneath the File Tree there is a dice roller. you *may* use this to roll dice by clicking on the needed die and then clicking the roll icon. You do not *have* to use this, I find physically rolling dice to be more fun but figured I would give you all the option
	- 🤓 Technically 🤓 using this feature is not truly random because it uses a `psuedorandom number generator`, some DMs will not like this type of digital dice, I am fine with it, that's why I provided it
- There is a similar icon in the upper right corner that will pull up an outline of the current note you are in based on `Heading Level`
	- There are also other options here, you can explore what they are on your own
- You can also press `Mod + o` to pull up a search bar to find a note or tag
	- On Mac the Mod key is `command`
	- On Windows the Mod key is `ctl`


# How do I write here?

Obsidian is what is known as a "modal editor", which is not as scary as that sounds. It simply means there are a few "modes" the app takes depending on what you want to do

## Reading Mode

- This is the mode that I have set to automatically load when you click a link
- You should see a pencil in the upper right corner next to three dots
	- Clicking that pencil will take you into Editing Mode
- Makes your notes look pretty!
- Hover over a link to preview it
- Click an existing link to go to it
- Right-click an existing link for options about the link
- Click a non-existing link to create it.
- When in Editing Mode, this mode can be entered with `Mod + e` or clicking the book
## Editing Mode

- This mode can be entered with `Mod + e` or clicking the pencil from Reading Mode
- You should see an open book in the upper right corner next to three dots
	- Clicking that book will take you into Reading Mode
- Merges Markdown Syntax with the prettified reader mode
- Hold `Mod` while hovering over an existing link to preview it
- Write notes just like normal typing
	- Most word keybindings work
		- Ex. `Command + i` will automatically add the Markdown Syntax for italics
		- This is secretly what Microsoft is doing in the background anytime you write in word. Their syntax is a little different though
	- If you want to learn how to make your notes pretty quickly and with just normal typing, I have included a [[Using Obsidian/Markdown Syntax Guide\|Markdown Syntax Guide]] that you can look at outlining the Obsidian implementation of Markdown Language. This is not necessary to use the software. You can type notes normally and it will be fine

```ad-bug
title: Help! I'm in Editing Mode but Can't Type!
collapse: closed
First, double check you are in editing mode. Modal editors can be tricky to get used to. If you are certain you are in the right mode... 

You probably went around and played with some settings didn't you? That's fine, I encourage you to make this vault your own, my prefrences don't have to match yours.

You accidentally enabled "Vim Mode" which is based off another Modal Editor used by some programmers (including myself). I don't know how you turned it on since it requires knowing a Vim command, but you probably did. Just go into Settings -> Editor and toggle the "Vim key bindings" setting at the bottom of the page.

```

```ad-warning
title: Sometimes I type something and it doesn't look how I want
collapse: closed
Since Obsidian creates .md files, the markdown syntax is followed by default.<br><br>Unfourtunately this does mean that certain characters are `keywords` and need to be escaped.<br><br>If you find you are trying to type and it is not looking as expected simply add `\` infront of the offending character. Yes this can be frustrating when it happens, but you will learn what causes it fairly quickly.

```


## Source Mode

- You don't want to be in this mode. It ***will*** confuse you
	- Even if you know markdown, things can get complicated looking fast, particularly with annotations or the L<sup>a</sup>T<sub>E</sub>X Math notation I use in the provided documentation
- I will walk you through how to get into, and out of, Source Mode so that you know what it is when you see it and how to get out of it if you accidentally get there.
```ad-question
title: Why Does It Exist?
collapse: closed
You may be wondering why source mode exists if you don't want to use it. Nerds like me who use Obsidian as a power tool often need to edit code blocks or other specific note functions. You do not need to worry about this

```

# How do I make a new note or delete a note?

- Press `Mod + n` at any time to make a new note in your current folder
	- This option can be changed, I will show you how if you want me to
- Right click on a file in your file manager to get more options
	- Move the note
	- Delete the note
	- Rename the note
	- etc

# Tagging notes

Individual notes can be tagged based on what they are about. I have provided some example tags using `YAML frontmatter`, however you can also tag things like you would on twitter.
- `#tag` will create a new tag
	- tags can be inline or at the top of a file
	- tags can have subtags for further categorization

```ad-warning
title: Illegal Tags
collapse: closed
Tags can not be two words. If you try `#my tag` only "my" will become a tag. In order to have multiple words in a tag pick a delimiter and stick with it. I use `_`, but you could use `-` or `:`, or whatever really
```

```ad-tip
title: Making your tags invisible
collapse: closed
If you want to have your tags hidden in Read Mode you will have to use a Markup Language known as `YAML`. It is not hard to use, I use it in this vault if you want an example. You will ***need*** to use it if you want to make your own notes with annotated PDFs. I will show you how to use it outside of our session time.
```


# I kinda hate the way this looks

Obsidian is ***HIGHLY*** customizable. In this vault I have hand picked a theme *I personally* enjoy and some plugins that will help us in the game. There is nothing stopping you from changing the theme, I can show you how outside of our session time. If you find you like this piece of software nothing is stopping you from just adding your new notes to this vault.

```ad-warning
title: Use Caution When Changing Themes
collapse: closed
There are some elements that will look very different or just not work with other themes. This is not an issue with the theme or the app, it is just part of the nature of highly customizable software

```


# Why are we using this if online tools already exist?

✨You do not have to!✨<br><br>I was in the process of making my own vault for DMing and realized that it would not be that much of a hassle to create a vault for you guys to use as well. You are more than welcome to use any other note keeping system you desire. I just have found this software to be *literally* life changing in how I organize my notes and projects, so am sharing the option to use this with you. I have, however, prepared this session with all of us using this in mind. Trust me, I went through and outlined the 300 page player handbook for you with the major points needed to get us started as well as some general rules so *you don't have to read it if you don't want to*. I ***tried*** to hit the major topics you may have questions about as well as tagging important parts of the [[Players Handbook/Player Handbook\|Player Handbook]]. Of course it is always there for you to reference. After all --  while, as DM, I am ***basically*** this world's god -- I am not infallible and will make mistakes. That's why I made one for the DM rules for myself.

# Getting Started

Alright, if nobody has questions about this app and you guy's are ready to go, let's [[Player Handbook \| "Roll" on into it]]! 🎲🐉