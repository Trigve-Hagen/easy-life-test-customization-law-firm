# Easy Life Test Customization — Law Firm

One real, standalone Site Customization Package for
[easy-life-test-website](https://github.com/Trigve-Hagen/easy-life-test-website),
themed as a small family law and estate planning practice — a complete,
filled-in manifest for the
[Easy Life Content Installer](https://github.com/Trigve-Hagen/easy-life-content-installer)
standard.

`manifest.json` sits at the root of this repo on purpose — that's the
address a listing pointing at this repo resolves the customization from
directly, with no subfolder to know about.

Try installing it yourself:

```
git clone https://github.com/Trigve-Hagen/easy-life-content-installer
git clone https://github.com/Trigve-Hagen/easy-life-test-website
git clone https://github.com/Trigve-Hagen/easy-life-test-customization-law-firm

python3 easy-life-content-installer/content_installer.py install \
  easy-life-test-website \
  easy-life-test-customization-law-firm/manifest.json \
  -o law-firm-installed

open law-firm-installed/index.html
```

## License

MIT — see `LICENSE`.
