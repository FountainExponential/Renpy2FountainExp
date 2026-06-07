# Renpy2FountainExp
A tool that converts stories written in Ren'Py to Fountain Exponential 

Fountain Exponential and Ren'Py are very similar, but where Ren'Py is the Python programming language with additions for writing dialog, Fountain Exponential is the Fountain markup language with additions for branching the dialog and adding programming, styling and data blocks. 

Ren'Py's Python programming language origines show in abreviating things to keep the writing short. This is specifically so with Ren'Py dialog where every line is preceded by the character saying it, but is by convention abreviated to a single letter. Fountain has the notion of multiple lines said by a single character, by having a preceding line denote the character by name, probably in all caps as is common in Hollywood scripts, because in a Hollywood script is the basis for filming a scene that is often done out of context and out of chonology, as availability of actors and locations impacts the schedule. Fountain Exponential recognizes that game developers and translators often face the same difficulty as film makers and builds oppon the foundation of Fountain to enable branching narrative.

Technicaly Ren'Py is a Visual Novel (VN) engine running on Python, hence the Py in the name. It is marketed as a Python extension, but it has it's own syntax specificly around dialog and lets Python handle the rest. It's starting point is python instructions to a game engine and adds a domain specific language for dialog on top of that. Fountain Exponential starts with scenes happening on a location where action takes place and dialog is said and add's game logic, styling and data to that.

From a usage point Ren'Py is meant for short stories supported by images. It's quick and easy to start and things can grow considerably, but at scale thing will get chaotic as there is little management of code. Although the community around Ren'Py is active there do not seem to be conventions for maintaining a large project. Fountain Exponential has features for maintaining a large project easier like sections and redirection to specific files. 

## Technical approach
The project eugeniusfox/vgprompter is a C# library which parses an extended subset of Ren'Py script syntax and allows to iterate over the lines.
It can probably be used as a basis for a conversion of Ren'Py to Founctain exponential in combination with the earlier developed C# elements for the Ink conversion.
