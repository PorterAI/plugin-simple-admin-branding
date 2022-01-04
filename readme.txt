=== Simple Admin Branding ===
Contributors: PorterAI
Tags: custom login, login, admin branding, login branding, customizer
Requires at least: 4.3
Tested up to: 5.8
Stable tag: trunk
Requires PHP: 5.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html
Donate link: https://www.paypal.com/donate/?hosted_button_id=T96GUHGVDQ4EY

Lightweight plugin to brand the WordPress login page using the built-in site icon assets.

== Description ==

Lightweight plugin to brand the WordPress login page using the built-in site icon assets.

== FAQ ==

= Why does WordFence (and other WAF's) flag this file as a vulnerability?

The file `/wp-toolbelt/modules/spam-blocker/blocklist.txt` is used by the spam blocker to check comments for spam phrases. It is regularly updated.

As such it contains lots of spammy words, and constantly changes. Both things that could trigger a vulnerability warning.

The best thing to do is mark this file (and only this file) as 'Ignore Always'. This will stop you from getting warnings for this one file whilst monitoring the rest of the plugin for suspicious changes.

= Why one plugin and not separate plugins? =

I am making this because it's something I want to use. I like the simplicity of installing Jetpack and letting it do it's thing. But Jetpack is not designed for speed or elegance, so I am trying to address that with my own plugin.

I am making the plugin as developer friendly as I can. Things can be tweaked using WordPress filters, and I will add more of these as I go.

= Do you have any documentation? =

The [docs are on Github](https://github.com/BinaryMoon/wp-toolbelt/wiki). They are a constant work in progress.

= Can I contribute/ report a problem? =

Yes please! You can [submit issues](https://github.com/BinaryMoon/wp-toolbelt/issues) on Github or add questions to the support forum. I'd be happy to accept pull requests as well.

= What features will you add next? =

I don't know. I'm open to suggestions (ping me on [Twitter](https://twitter.com/binarymoon)), but mostly I'll add things as I need them.

== Installation ==

1. Install and activate the plugin through the plugins page.
2. From WordPress Admin, goto Appearance > Customizer > Simple Admin Branding.

== Changelog ==

= 1.0 - 3rd January 2022 =