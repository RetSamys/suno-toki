This is a font, crudely drawn by hand, for a [video tutorial on how to make a sitelen pona font](https://www.youtube.com/watch?v=6Emk0nvFFVw). 

* Features you might expect from other sitelen pona fonts that are included in this font:
  * UCSUR-compatible
  * monospaced
  * supports cartouches
  * supports ligatures (conversion of words typed in ASCII/Latin into sitelen pona characters)
* Features that might be more interesting:
  * Colours! Except for cartouche lines, glyphs are coloured in violet, ocre, red, green, pink and teal, in that order, starting with the glyphs originally drawn by Sonja Lang from A to Z and then namako, kin, oko, tonsi, kijetesantakalu. This is using the OpenType SVG standard, so it doesn't work everywhere (for example, in browsers, it works with Firefox, but Chrome and Edge onyl show the glyphs in the default colour).
  * Auto-cartouching! Type a name with ASCII starting with a capital letters to start a cartouche and it will be converted automatically (example: `Toki` will become [tenpo oko kulupu insa], or a different combination of glyphs, but `toki` will become the sitelen pona glyph for "toki"). Which glyph is used for which letter is random-ish (through the OpenType `rand` function). I'm not sure what exactly happens if that function doesn't work in a program, but there's an underlying base glyph for each letter, as a copy of a sitelen pona glyph: a->ala, e->en, i->ijo, j->jo, k->kon, l->lupa, m->mi, n->nanpa, o->pini, s->suli, t->tu, u->uta, w->wan. The goal was to find the glyphs most easily confusable with ASCII characters (which wasn't always possible), based on a suggestion by waso Keli.

![glyph drawings](sunotoki.png)