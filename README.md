# PenoSnippet

======================

Chrome/Chromium extension that allows easy CSS+HTML extraction of specific DOM element. Created snippet can be then exported to CodePen, jsFiddle or JS Bin with one click or copy and use HTML/CSS code in your project!

Other features:

- cleans up HTML (removing unnecessary attributes, fixing indentation)
- optimizes CSS to make it readable
- fully configurable (all filters can be turned off)
- nice UI thanks to Bootstrap & Flat-UI projects
- works with :before and :after pseudo elements

## Installation

------------

Download the extension and manually load it as an 'Unpacked extension' via the extensions page.

## Usage

Open Developer Tools, you should see the new PenoSnippet tab. Inspect an element on the page and switch to the new tab, you will see options for settings and exporting the code for the element you selected.

## Bugs and Features

If you found a bug or have a feature request, please create an issue here on GitHub.

<https://github.com/penobit/PenoSnippet/issues>

## Changelog

### 0.5 ###

- [#13](https://github.com/penobit/PenoSnippet/issues/13) IFrames support (by @crdev)
- [#19](https://github.com/penobit/PenoSnippet/issues/19) Prefixing/namespacing CSS IDs

### 0.4 ###

- [#8](https://github.com/penobit/PenoSnippet/issues/8) Extract DOM and CSS up to the root element (by @crdev)
- [#15](https://github.com/penobit/PenoSnippet/issues/15) Preserve settings (by @crdev)
- Fix for [#7](https://github.com/penobit/PenoSnippet/issues/7) bug where shorthand property values were sometimes invalid
- Workarounds for buggy 'content' property

### 0.3 ###

- JS Bin support (by @remy)
- temporary workaround for `getComputedStyle` bug in `border-radius` property (issue [#4](https://github.com/penobit/PenoSnippet/issues/4), thanks to @zessx for spotting this)

## Special thanks to

+ [crdev](https://github.com/crdev) for all top-notch contributions, advice and help with Chrom(ium) bugs
- [qntmfred](https://github.com/qntmfred) for [inspiration](http://stackoverflow.com/questions/4911338/tools-to-selectively-copy-htmlcssjs-from-existing-sites)

## Author

**Konrad Dzwinel**

- <https://github.com/penobit>
- <https://twitter.com/penobit>
- <http://www.linkedin.com/pub/konrad-dzwinel/53/599/366/en>

## License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
