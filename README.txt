Gentzen Mathematics 

This package includes a prototype of the Gentzen Symbol typeface,
which for convenience is packaged with a streamlined version of the a
number of the glyphs found in AMS Euler.  I say streamlined as a
number of minor adjustments have been made based upon FontForge's
"Find Problems" tool.

I say that the font in this release is a prototype because it only
includes a design for a single weight (medium), a single optical size
(10pt), and the glyphs provided are limited to what was necessary to
produce my dissertation. In the long term, the goal is for Gentzen
Symbol to become a properly designed meta-font using the METATYPE1 or
some similar software.

To be clear, the American Mathematical Society holds the copyright on
AMS Euler to ensure that there is only one AMS Euler, and that by
calling the typeface Gentzen Mathematics, I am following the spirit of
what the American Mathematical Society intends.  The following is an
excerpt from http://www.ams.org/tex/type1-fonts.html:

  In order to assure the authenticity of these fonts, copyright will
  be held by the American Mathematical Society. This is not meant to
  restrict in any way the legitimate use of the fonts, such as (but
  not limited to) electronic distribution of documents containing
  these fonts, inclusion of these fonts into other public domain or
  commercial font collections or computer applications, use of the
  outline data to create derivative fonts or faces, etc. However, the
  AMS does require that the AMS copyright notice be removed from any
  derivative versions of the fonts which have been altered in any
  way. In addition, to ensure the fidelity of TeX documents using
  Computer Modern fonts, Professor Donald Knuth, creator of the
  Computer Modern faces, has requested that any alterations which
  yield different font metrics be given a different name.

Installation is not automated, but merely involves making sure that
TeX can file all of the relevant files.  The included file "table.tex"
gives an example of a document that uses that uses the package.


July 2021 Addendum

This should include all the code necessary to use the Gentzen typeface
with LaTeX.  However, it currently does rely on using OMake and my tool
otftofd.  The use of OMake is not particularly essential, though
creating the necessary support files without otftofd could prove
tedious.  However, since this typeface was originally created in 2007,
the handling of fonts in TeX's offspring has advanced considerably.  As
such, it might make more sense to start from scratch with XeTeX or
LuaTeX.
