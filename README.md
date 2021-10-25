# Vivaldi Material Theme

The minimal dark theme inspired by [Material Theme][material-web] for [Vivaldi][vivaldi] web browser.

## Install

### Manual

1. Open Vivaldi's Settings
   1. **Linux**: Menu > Tools > Settings (`Ctrl+F12`)
   2. **Windows**: Tools Menu > Settings (`Ctrl+F12`)
   3. **MacOS**: Menu > Preferences (`Command+,`)
2. Select `Themes` in the panel
3. Click the `+` and enter a name (e.g., Material)
4. Copy the theme's `.json` values to the Vivaldi theme

For example, if I want the traditional Material theme, use the colors from [material.json](material.json)

- Background: `#263238`
- Foreground: `#b0bec5`
- Highlight: `#546e7a`
- Accent: `#546e7a`

See [Colors](#colors) for recommended Vivaldi-Material color/setting combinations.

### Automatic

*This feature is not currently implemented.*

*If you have ideas how to automatically generate/update/sync Vivaldi themes, please see [Contributing](#contributing). I would love to have this feature.*

## Colors

The material theme colors were obtained from [material-theme.com](material-theme-colors).

My recommendation is to use the following values for the Vivaldi settings
| Vivaldi Setting | Theme Color |
|-----------------|-------------|
| Background      | background  |
| Foreground      | foreground  |
| Highlight       | comment     |
| Accent          | selection   |

> Note: `highlight` and `accent` material colors can be difficult to see with their corresponding Vivaldi settings.

If you like a **pop of color** in your theme, I would substitute the `Accent` Vivaldi setting for the Material `accent` color. Below is an example with the default Material Theme.


<!-- ## Customize

You may generate a new theme `.json` from an existing theme color palette.

```python theme.py --create material --accent selection``` -->

## Contributing

If you have any suggestions or features you would like to see included in this project, see [Contributing](CONTRIBUTING.md) for more information.

## License

See the [license] for more information.

<!-- links -->
[vivaldi]: https://vivaldi.com
[material-web]: https://material-theme.site
[material-theme-colors]: https://material-theme.com/docs/reference/color-palette/
[default-material-png]:
[color-material-png]:
[license]: 
