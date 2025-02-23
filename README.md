# Zettelkasten
A continuation of Luhmann for Obsidian

Commands for handling a zettelkasten with Luhmann-style IDs (e.g: 12a56g) as filenames

As it stands I believe the in-built features of Obsidian are enough to create zettelkasten-style notes by using links. The ID's generated are useful with an analog setup but with a digital system like Obsidian, many of the benefits for such a system are moot. 

## Commands

### Create child notes

Creates a note **under** the current note, e.g: If run from "23f3.md", "12f3a.md" (or the next available sibling) will be created. 

If you have text selected, that will be used as the title for your new note. Otherwise, you will be prompted to enter a title.

### Create sibling note

Creates a note **next to** the current note, e.g: If run from "23f3.md", "12f4.md" (or the next available sibling) will be created. 

If you have text selected, that will be used as the title for your new note. Otherwise, you will be prompted to enter a title.

### Open zettel

Allows you to search for files by their inner markdown title (i.e: the first H1 found within the note)

### Insert Zettel link

Lets you search by markdown titles like the "Open zettel" command above, but inserts a link to the file instead of opening it.

## Usage
Ensure that links are preserved by enabling `Automatically update internal links` found in the settings under `Files & Links` near the top.

