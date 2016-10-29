# Milan - Starter stylesheet structure

* Folder structure follow [ITCSS](http://itcss.io/)
* Naming convention follow BEM

## Folder structure

* settings (variables and typography)
  * \_all.css
* tools (mixins and functions)
  * \_all.css
  * \_mixins.css
* generic (normalize, global rules)
  * \_all.css
  * \_normalize.css
  * \_reboot.css
* components (UI components)
  * \_all.css
* trumps (utilities, highest specificity styles)
  * \_all.css
* main.css

## Stylelint

Stylesheet must passes [Stylelint](http://stylelint.io/)

Rules config follow [GitHub's CSS](https://github.com/primer/stylelint-config-primer) with some overrides. See .stylelintrc for more details.

## Notes

* All colors passes AA level - [colorsafe](http://colorsafe.co/)
* Using PostCSS for writing stylesheet

## Resources

* [Building a Maintainable and Scalable CSS Codebase with ITCSS](https://medium.okgrow.com/building-a-maintainable-and-scalable-css-codebase-with-itcss-ceda5b2f495b#.1ghibj1q7)
