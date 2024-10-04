## Contributing

By contributing you agree to the [LICENSE](LICENSE) and [Code-Of-Conduct](Code-Of-Conduct.md) of this repo.

## Guidelines

* Use only the original colors created by the author. Modifications of pre-existing themes are not accepted unless they're already widely recognized. For example: gruvbox material is accepted though gruvbox exists.
* You're free to add your own color themes unless they're different from pre-existing ones. Anything too similar would not be allowed.
* We only accept hex codes, rgb and hsl unless they're explicitly required in other formats in the config files of a specific app.
* When adding a color to the palettes folder follow this format:
    `<Capitalised Simplest Shade Name>: hex rgb(r, g, b) hsl(what, e, ver)`
    example:
    `Green: #98971a rgb(152, 151, 26) hsl(60, 71%, 35%)`

* You can refer to the following tools for converting hex codes to rgb and hsl:
    [HTML Color codes](https://htmlcolorcodes.com/hex-to-rgb)

* Add an image of the color palette inside images/
* **IMPORTANT:** Add the pic and the palette in 2 different commits 1 for each work.

* The overall md page for palette colors has to follow the following format:

    ```
    ## <Theme name>

    ### Credits
    [Name of Creator(s) (if multiple separate with commas)](link-to-website-or-github-page)

    ### Colors
    `<Capitalised Simplest Shade Name>: hex rgb(r, g, b) hsl(what, e, ver)` {look at the above given example or other themes files for reference}
    
    ### Image
    <img url="images/imagename.png", alt="pic for colortheme", width="700"> {do not change the width}
    ```
* For PRs use the following title convention: 
    (if more than one authors: use a team name or link or name of the major author)
    * When adding palettes: `Added themename by author`
    * When adding configs for utilities: `Added themename by author for utilityname`
    * When adding your own palette: `Added themename by author (my own)`

* Search the repo thoroughly to avoid reposting themes that already exist in the repo.