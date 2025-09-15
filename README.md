# academicons

## Description

The *academicons* package provides access in (La)TeX  to 146 high quality icons of online academic profiles included in the free *Academicons* font. This package requires either the Xe(La)TeX or Lua(La)TeX engine to load the *Academicons* font from the system, which requires installing the bundled *academicons.ttf* font file.

> [!WARNING]
> As new releases come out, it is recommended to install the bundled font version as there may be differences between the package and previous font versions or newest font versions not yet contemplated in the package.

The *Academicons* font was designed by James Walsh and released[^1] under the open SIL Open Font License[^2]. This package is a redistribution of the free *Academicons* font with specific bindings for (La)TeX. It is inspired and based on the *fontawesome*[^3] package.

## Usage

<table>
    <tr>
        <td><code>\aiicon</code></td>
    <td>The academicons package provides the generic <code>\aiicon</code> command to access icons, which takes as mandatory argument the name of the desired icon. It also provides individual direct commands for each specific icon. The full list of icons and their respective names and direct commands can be found in the manual. For example, <code>\aiicon{googlescholar}</code> yields the same result as <code>\aiGoogleScholar</code>.</td>
    </tr>
</table>

academicons (La)TeX package\
<https://www.ctan.org/pkg/academicons>\
Version: 1.9.4
License: LaTeX Project Public License, version 1.3c

## Author

[@dfernan__](https://twitter.com/dfernan__)

[^1]: See <http://jpswalsh.github.io/academicons/>
[^2]: Available at <http://scripts.sil.org/OFL>
[^3]: Available at <http://www.ctan.org/pkg/fontawesome>
