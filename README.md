# tmpLuaLaTeX
A temporary repository for AskTheCode interaction

Problem:

Emulating \XeTeXglyph in LuaLaTeX


I need LuaLaTeX because I want to use color font, but I want to use
also \XeTeXglyph for accessing glyphs not available in a different
way.

I use \XeTeXglyph emulation from tb136prod.ltx. I use practically
identical code in CANCELlua.tex but it doesn't work.

In CANCELlua.tex I use a different font than in tb136prod.ltx, but
CANCELxe.tex proved the specified characters really exist in the font.