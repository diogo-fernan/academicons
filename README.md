# academicons

## Description

The `academicons` package provides access in (La)TeX  to 146 high quality icons of online academic profiles included in the free *Academicons* font. This package works with both Xe(La)TeX or Lua(La)TeX by using `fontspec` to load the included font, as well as with pdf(La)TeX by loading a Type 1 converted format of the original font.

The *Academicons* font was designed by James Walsh and released[^1] under the open SIL Open Font License[^2]. This package is a redistribution of the free *Academicons* font with specific bindings for (La)TeX. It is inspired and based on the `fontawesome`[^3] package.

## Usage

<table>
    <tr>
        <td><code>\aiicon</code></td>
        <td>
            The generic <code>\aiicon</code> macro takes as mandatory argument the <code>⟨name⟩</code> of the desired icon. Icons can also be accessed directly by their respective macro. For example, <code>\aiicon{googlescholar}</code> yields the same result as <code>\aiGoogleScholar</code>. The full list of icons with their respective names and direct commands can be found in the manual.
        </td>
    </tr>
</table>

academicons (La)TeX package\
<https://www.ctan.org/pkg/academicons>\
Version: 1.9.4\
License: LaTeX Project Public License, version 1.3c

[^1]: See <http://jpswalsh.github.io/academicons/>\
[^2]: Available at <http://scripts.sil.org/OFL>\
[^3]: Available at <http://www.ctan.org/pkg/fontawesome>
