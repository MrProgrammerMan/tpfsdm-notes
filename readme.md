# The Purely Functional Software Deployment Model - Notes
This repo is a notebook for the p.hd thesis by Eelco Dolstra which resultet in Nix, NixOS and nixpkgs. As a software engineering student I take great interest in this, as I believe these tools provide a better way of deploying software, eliminating a lot of common problems.

## Why
I've been spending time learning about deployment and deployment automation. It's become clear to me that this is a part of the software development field that is often not considered as much as developing the software itself. It seems to me that many commercial projects end up being semi-manually deployed, and often face issues with deployment. Furthermore, deplyment is a topic one generally doesn't concern oneself with as a junior software engineer. Therefore, I want to invest time into learning about deployment, and perhaps some ways deployment could be optimised and improved over current methods in use. This could save time, both on the developers as well as the users part, and also be vital for scenarios where rolling back to a stable version or updating dependencies are important.

## The material
After researching the topic brifly, it seems the best way to learn the details of Nix is to read the original p.hd. It's also important, as with any part of the software field, to use Nix. I will be taking notes from the p.hd., as well as doing excercises with NixOS and the Nix language.

## Notes structure
The notes are organized as a Zettelkasten(with some slight modifications to my preferances). All notes are markdown files divided into the following directories:

1. 01-literature-notes: This directory includes notes taken from part of the p.hd.-thesis.
2. 02-permanent-notes: This directory includes notes for a specific topic. These are self-contained, detailed notes.
3. 03-structure-notes: This directory contains notes that bind together the permanent notes. This are short, and should contain little information within themselves.

There are also 2 more directories:

1. 00-resources: This directory contains resources used in the notes. For example, the ph.d.-thesis has an entry here. Any images, links, etc. that is referenced in other files are represented here.
2. 04-excercises: This directory contains excercises I do to learn abuot Nix hands-on. They won't function as notes to be reviewed, but as a way to store the practical projects used for learning along with the notes.

## Reviewing the notes
If you wish to review the notes, I highly recommend you do so using Zettlr. This is the markdown-based that I personally use. The reason is that the notes contain a large amount of Zettlr-flavoured internal links. These allow you to click through the notes and create visualizations of them. Viewing the notes without Zettlr is chaotic.