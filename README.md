# Renpy2FountainExp
A tool that converts stories written in Ren'Py to Fountain Exponential 

Ren'Py is a Visual Novel (VN) engine running on Python, but it has it's own syntax and is thus a seperate scripting language.
The Py in Ren'Py actualy stands for Python and it is advertised that most Python works in Ren'Py.
There is a lexer that converts the VN specific format into Python.
The format of Ren'Py looks similar to that used in stageplay, but is simplyfied to a point that starting a project is easy, but maintaining a large project gets hard.
For instance every dialog line is preceded by the actor saying it, but the actor is generaly abreviated to a single letter.
A movie script of 110 pages would be very difficult to read in Ren'Py format.


The project eugeniusfox/vgprompter is a C# library which parses an extended subset of Ren'Py script syntax and allows to iterate over the lines.
It can probably be used as a basis for a conversion of Ren'Py to Founctain exponential in combination with the earlier developed C# elements for the Ink conversion.
