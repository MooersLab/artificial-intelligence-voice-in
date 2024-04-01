![Version](https://img.shields.io/static/v1?label=artificial-intelligence-voice-in=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# artificial-intelligence-voice-in

## Introduction
This repo contains voice commands about artificial-intelligence for the speech recognition software Voice In Plus.
The utilization of these custom commands requires a subscription to Voice In Plus.
These commands can be used in the text area of most websites opened in Google Chrome.
They can be used during the dictation of manuscripts about artificial intelligence.
This topic includes inside its envelope the topics of machine learning and deep learning.
Some of the commands including equations that are represented as LaTeX math.
These short snippets of LaTeX are recognized and rendered correctly by most markdown type setting languages, including org-mode--an enhanced form of Markdown that is best used from inside Emacs.

## Usage
You can utilize the commands immediately after they have been uploaded.
I toggle Voice In on and off by using a keyboard shortcut.
I then dictate the command.
See the Voice In plug-in documentation to learn how to configure keyboard shortcuts.

## Installation
Each command is paired with the inserted text on a single line in a comma-separated value file (ai.csv).
You can use the **bulk add** button in Voice In Plus to upload these commands to your collection of custom commands.

## Contents of the library ai.csv

- Acronyms used in artificial intelligence, including machine learning and deep learning.
- Key equations typeset in LaTeX.
- URLs of key websites.
- Names of key people in the field to ensure the correct spelling of their name.

## Related repositories
See [Voice Computing section of landing page](https://github.com/MooersLab/MooersLab?tab=readme-ov-file#voice-computing)

## Rules for developing voice commands

### Pick word combinations rarely used in normal prose
The basic rule for developing a voice command is to pick a word combination that is very unlikely to be used in one's prose.
This choice can avoid the accidental insertion of an unintended set of words.

### Pick word combinations that do not contain other commands
If you pick a word combination with a subset of words already assigned to another command, the commands will collide, and you will not get the intended effect.
It is better to pick a synonym for the new command than include the old one.

### Use verbs are prefaces
I use the verb `insert` in front of the name of the computer code or equation that I want to insert.
I use the verb `expand` to expand acronyms.
I use `url` to insert a URL.

## Status
Ready to use but still under development.
