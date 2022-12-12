# Mastodon Mods
This repo contains all the minor changes that I made for my instance, [Sakurajima](https://sakurajima.moe). This includes additional footer link and a extra button on the logged out view.

# Custom Themes
There are two custom themes at present with more coming. They are:
- mastodon-sakura - A Sakura-themed Mastodon Theme
- mastodon-gekka - A gekka (月下美人) themed Mastodon theme.

I appreciate that if you use these themes to link them back to the [creator](https://sakurajima.moe/@chikorita157).

# Adobe Fonts Compatibility
The application.scss and the content_security_policy.rb are modified so Adobe fonts can work. In the application.scss, add the font CSS of your project from Adobe fonts. Then specify the font name in the custom CSS. Here is an example.

```css
body {
	font-family: myriad-pro, sans-serif !important;
}
```

Replace myriad-pro with the font you have in the Adobe Fonts project, unless you are actually using that font.