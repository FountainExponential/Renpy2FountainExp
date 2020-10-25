# Renpy2FountainExp
A tool that converts stories written in Ren'Py to Fountain Exponential 

Fountain Exponential and Ren'Py are very similar, but where Ren'Py focuses on simplicity, Fountain Exponential focuses on readability. This means that Ren'Py abreviates things to keep the writing short. This is specifically so with Ren'Py dialog where every line is preceded by the character saying it, but is by convention abrreviated to a single letter. Fountain Exponential has the notion of multiple lines said by a single character, by having a preceding line denote the character by name, probably in all caps as is common in Hollywood scripts and optionaly prepended with @ for clarity. 

Technicaly Ren'Py is a Visual Novel (VN) engine running on Python, hence the Py in the name. It is marketed as a Python extension, but it has it's own syntax specificly around dialog and lets Python handle the rest. The difference between the text and code is not explicit and Fountain Exponential could be better in that regard.

From a usage point Ren'Py is meant for short stories supported by images. It's quick and easy to start and things can grow considerably, but at scale thing will get chaotic as there is little management of code. Although the scene around Ren'Py is active there are no conventions for maimtaining a large project. Fountain Exponential has scenes and other section that whould make maintaining a large project easier.

## Technical approach
The project eugeniusfox/vgprompter is a C# library which parses an extended subset of Ren'Py script syntax and allows to iterate over the lines.
It can probably be used as a basis for a conversion of Ren'Py to Founctain exponential in combination with the earlier developed C# elements for the Ink conversion.
