## Contributing

By contributing you agree to the [LICENSE](LICENSE) and [Code-Of-Conduct](Code-Of-Conduct.md) of this repo.

## Guidelines

* Use only the original colors created by the author. Modifications of pre-existing themes are not accepted unless they're already widely recognized. For example: gruvbox material is accepted though gruvbox exists.
* You're free to add your own color themes unless they're different from pre-existing ones. Anything too similar would not be allowed.
* We only accept hex codes, rgb and hsl unless they're explicitly required in other formats in the config files of a specific app.
* When adding a color to the palettes folder follow this format:

    `<Simple Shade Name>: hex`

    example:
    `Green: #98971a`

* You can refer to the following tools for converting hex codes to rgb and hsl and vice versa:
    * [HTML Color codes](https://htmlcolorcodes.com/hex-to-rgb)

* ~~Add an image of the color palette inside images/~~
* ~~**IMPORTANT:** Add the pic and the palette in 2 different commits 1 for each work.~~

* The overall md page for palette colors has to follow the following format:

    ```
    ## <Theme name>

    ### Credits
    [Name of Creator(s) (if multiple separate with commas)](link-to-website-or-github-page)

    ### Colors
    `<Simple Shade Name>: hex` {look at the above given example or other themes files for reference}

    ### Sample Image
    <img src="images/themename.png" alt="themename pic" width="500">
    ```

* Generate a sample pic using [richcolors](https://github.com/Rizen54/richcolors)
    * Use the command in the `color-themes/` folder: `richcolors themes/themename.md images/themename.png`
    * Enter img width as `500`
    * Enter img height as `250`

* The md file should be named `themename.md` for eg: `gruvbox.md`
* The pic file should be named `themename.png` for eg: `gruvbox.png`
* For PRs use the following title convention: 
    (if more than one authors: use a team name or link or name of the major author)
    * When adding palettes: `Added themename by author`
    * When adding configs for utilities: `Added themename by author for utilityname`
    * When adding your own palette: `Added themename by author (my own)`

* Search the repo thoroughly to avoid reposting themes that already exist in the repo.
* For themes for other apps/utilities: Use the configuration format and extension for the specific theme and **provide a way to use it.**
