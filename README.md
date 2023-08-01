# SF Gov Icons Extension For Quarto

## Installing

```bash
quarto install extension SFOEWD/sficons
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

TO embed an icon, use the `{{< sficon ...>}}` shortcode. Some examples:

```bash
{{< sficon wip >}}
{{< sficon alert >}}

```

The full list of available icons is available on [the San Francisco Design System website.](https://design-system.sf.gov/components/icons/)

## Customizing

Control the color and size of the icons:

```bash
{{< sficon arrow-right color=firebrick >}}

{{< sficon globe color=green size=5em >}}
```

## Acknowledging

The lua code was adapted from [bsicons.](https://github.com/shafayetShafee/bsicons)
