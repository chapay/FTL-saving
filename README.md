# FTL-saving
[Faster Than Light](http://www.ftlgame.com/) — is a great game, but from the box it doesn't provide a possibility to save your game.
Sometimes you want to try flying different ways or make different decisions.

Fortunately you can just backup your savings in the safe place with this small script.

## Install

1. Copy `save.sh` wherever you want.
2. Configure your FTL path and path for your savings
3. Don't forget to grant execution permissions: `sudo chmod +x save.sh`

## Usage

1. List your savings:

    ```
    ./save.sh list
    ```
2. Back up your saving:

    ```
    ./save.sh save [tag]
    ```
    All your savings can be tagged with specific name or with consistent numbers by default.
3. Restore your saving:

    ```
    ./save.sh load <tag>
    ```
4. Retag your backup:

    ```
    ./save.sh tag <oldtag> <newtag>
    ```
5. Restore last saving:

    ```
    ./save.sh restore
    ```

## License

Copyright (c) 2015 Andrey Sobkanyuk

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished
to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.