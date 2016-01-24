# Handlebars support for TextMate
This [TextMate][] bundle adds preliminary support for [Handlebars][]. It has a (working, but incomplete) language definition and adds a few tab-triggered snippets. Cmd+/ also works. Adapted for TextMate from the [Sublime Text package for Handlebars][st] by [Daniel Demmel][dd].

[textmate]:https://macromates.com/
[handlebars]:http://handlebarsjs.com/
[st]:https://github.com/daaain/Handlebars
[dd]:http://danieldemmel.me/

## Installation
[Download][] and extract the ZIP archive, then rename the extracted directory to `Handlebars.tmbundle` and double-click it.

[download]:https://github.com/hlvnst/handlebars.tmbundle/archive/master.zip

### Manual installation
Clone this repository in the right place and make TextMate reload its bundles. For TextMate 2:

    mkdir -p ~/Library/Application\ Support/Avian/Pristine\ Copy/Bundles
    cd ~/Library/Application\ Support/Avian/Pristine\ Copy/Bundles
    git clone https://github.com/hlvnst/Handlebars.tmbundle.git
    osascript -e 'tell app "TextMate" to reload bundles'

For TextMate 1.x, change `Avian` to `TextMate` in the first two lines.

## Known issue
* The language definition is incomplete. See the `Test/template.hbs` file inside the bundle for `TODO`'s and `FIXME`'s.

## Contributing
Pull requests are welcome!

## License
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
