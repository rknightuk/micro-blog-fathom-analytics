## Fathom Analytics for Micro.blog

This plugin adds [Fathom Analytics](https://usefathom.com/ref/IXCLSF) to your hosted Micro.blog site.

> Fathom is a Google Analytics alternative that doesn’t compromise visitor privacy for data

## Installation

1. Find [Fathom Analytics](https://micro.blog/account/plugins/view/86) in the plug-in directory
2. Install to the site you want to install to and press install
3. Ta-da! It's installed

### Configuration

1. Go to _plug-ins_ and pressing settings next to _Fathom Analytics_
2. Set your Fathom site tracking code
3. Click _Update Settings_

If your theme already includes the code below in the `head.html` file then everything should just work. If not, you can include the partial manually by adding the following to your `head.html` file under `Design > Edit Custom Themes > Your Theme`:

```
{{ partial "fathom.html" . }}
```
