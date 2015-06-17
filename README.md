# Handlebars support for TextMate
This [TextMate][] bundle adds preliminary support for [Handlebars][]. It has a (working, but incomplete) language definition and adds a few tab-triggered snippets. Cmd+/ also works. Adapted for TextMate from the [Sublime Text package for Handlebars][st] by [Daniel Demmel][dd].

[textmate]:https://macromates.com/
[handlebars]:http://handlebarsjs.com/
[st]:https://github.com/daaain/Handlebars
[dd]:http://danieldemmel.me/

## Installation
[Download][] and extract the ZIP archive, then rename the extracted directory to `Handlebars.tmBundle` and double-click it.

[download]:https://github.com/hlvnst/handlebars.tmbundle/archive/master.zip

### Manual installation

Clone this repository in the right place and make TextMate reload its bundles. For TextMate 2:

    mkdir -p ~/Library/Application\ Support/Avian/Pristine\ Copy/Bundles
    cd ~/Library/Application\ Support/Avian/Pristine\ Copy/Bundles
    git clone https://github.com/hlvnst/handlebars.tmbundle.git Handlebars.tmBundle
    osascript -e 'tell app "TextMate" to reload bundles'

For TextMate 1.x, change `Avian` to `TextMate` in the first two lines.

## Known issue
* The language definition is incomplete. See the `Test/template.hbs` file inside the bundle for TODO's.

## Contributing
Pull requests are welcome!