# P5.js Bundle for Sublime Text

A [P5.js](http://p5js.org/) bundle for [Sublime Text](http://www.sublimetext.com/), based on the [Processing](https://github.com/b-g/processing-sublime)language syntax plugin.

## Installation
There are ~~3~~ 2 easy ways to install the Processing Bundle:

~~### Using Sublime Package Control
If you are using [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install the Processing Bundle via the `Sublime Text -> Preferences -> Package Control: Install Package` menu item.~~ Not yet.

### Using Git
Alternatively you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

Go to your Sublime Text `Packages` directory and clone the theme repository using the command below:

`cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages`

`git clone https://github.com/sergiomajluf/p5.js-sublime/ "P5"`

### Download Manually
- Download the files using the GitHub .zip download option
- Unzip the files and rename the folder to `P5`
- Copy the folder to your Sublime Text `Packages` directory e.g. OS X: `~/Library/Application Support/Sublime Text 2/Packages/P5`

## Usage
- Select Processing Syntax

## Acknowledgements
- This bundle is very much based on [Processing TextMate Bundle by Leon Hong](http://www.onebitwonder.com/projects/processing/), thanks for all the good work!
- I used the [textmate-to-sublime-converter](https://github.com/srbs/textmate-to-sublime-converter) to convert the snippets from the original Processing TextMate Bundle to Sublime Text speak.
- Syntax highlighting tweaking [Mark Brand](https://github.com/ignism)
- Linux build script and testing [Julien Deswaef](http://xuv.be/)
- Windows build script and documention [Ralf Baecker](http://github.com/rlfbckr)
- Error console capturer [Greger Stolt Nilsen](http://gregerstoltnilsen.net/)
- Master of the syntax definition. Whitespace and indentation cleanup. Processing reference vs. sublime [diff tool](https://github.com/ybakos/processing-sublime-util). [Yong Joseph Bakos](http://yongbakos.com/).
