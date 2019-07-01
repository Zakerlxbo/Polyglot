![](http://uechi-public.s3.amazonaws.com/github/Polyglot/header.png)

[![Join the community on Spectrum](https://withspectrum.github.io/badge/badge.svg)](https://spectrum.chat/polyglot)

Polyglot is a Safari extension that translates selected text into your native
language using Google Translate.

[Download latest version](https://github.com/uetchy/Polyglot/releases/latest)
and double-click `Polyglot.safariextz` to install extension.

# Usage

Visit the extension settings from Safari Preferences and change the target
language to one you prefer and reconfigure keyboard shortcuts as you wish.

- Select word or sentence and right-click then click **Translate**.
- or, Select word or sentence and just type the configured key combination.
- or, Select word or sentence and click **Translate** button on tool bar.

![](http://uechi-public.s3.amazonaws.com/github/Polyglot/screencast1.gif)

# Troubleshooting

#### It seems a new settings have not been applied.

Refresh web pages or restart Safari and try it again. If you continue to face
same problem, please open an issue on GitHub.

#### My key combination didn't work

Some key combinations are preblematic. Try another one.

# Development

Install npm dependencies.

```
npm install
npm start
```

then open up `Developer > Extention Builder` in Safari and add the folder named `Polyglot.safariextention` to the builder panel and press `Install` button.

If you made any changes, press `Reload` to refresh the extention.

# Contributors

list of contributors.

- Yasuaki Uechi
- Sergey Sorokin
- Serhii Dmytruk
- Matt Sephton
