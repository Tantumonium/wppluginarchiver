# WP Plugin Archiver
(Based on The Hack Repair Guy’s Plugin Archiver, by Jim Walker @HackRepair.com)

The WP Plugin Archiver allows you to quickly deactivate & archive WordPress Plugins by moving them out of the WordPress **Plugins** list, while still keeping them readily available for re-installation or re-activation later.

<!--
[![Download Plugin](https://img.shields.io/badge/Download_on-WordPress.org-blue.svg)](https://wordpress.org/plugins/hackrepair-plugin-archiver/)
-->

##Why use the WP Plugin Archiver?

* This plugin **moves the selected plugin(s)** into an archive folder, eliminating accidental reactivations and keeping your plugin list clean.
* Maybe you have a set of plugins that you would like to install in all of your WordPress sites, but would rather not have them listed within Plugins (until you need them).
* Maybe you’ve run into a buggy or possibly compromised plugin, that when activated breaks or causes harm to your website. the WP Plugin Archiver plugin will allow you to simply archive plugins, preventing accidental activation.
* Maybe you wish to test sets of plugins, pulling different sets of plugins into your plugin list as you need them; all with just a few clicks.
* Maybe you share management with another administrator who believes the “Activate” link is an invitation to “click it!”
* With the WP Plugin Archiver, you may even upload or move plugins to your own custom archive directory.
* Deactivated plugins remain visible in the WordPress Plugins list, easily reactivated by another admin and potentially altering or breaking the website.


## 🚀 Features

- Archive plugins to hide them from the active list.
- Prevent accidental re-activation of broken or unnecessary plugins.
- Manage "plugin sets" for staging or development purposes.
- Maintain plugin settings without deleting them.
- Easy upload to and retrieval from custom archive directories.

## 📥 Installation

### From WordPress Admin

1. Go to **Plugins → Add New**
2. Search for `WP Plugin Archiver`
3. Click **Install**
4. Click **Activate**

### Manual Installation

1. Download a copy of `wp-plugin-archiver.zip` from the [GitHub Repo](https://github.com/Tantumonium/wppluginarchiver)
2. Unzip the downloaded file
3. Upload the `wp-plugin-archiver` folder to your site's `/wp-content/plugins/` directory
4. Activate the plugin from the WordPress Admin Panel

## ❓ Frequently Asked Questions

#### What happens if I deactivate or remove the plugin?

> Nothing happens to your archived plugins. They remain in the archive directory until you choose to restore them manually or via the plugin UI.

#### Will you add a “Restore All” or “Unarchive All” feature?

> No. The plugin supports version-aware archiving. Restoring all plugins at once would reintroduce version ambiguity and potential site breakage.

#### Why archive instead of delete?

> Deleting a plugin can erase its settings or database entries. Archiving preserves plugin state and settings while hiding it from your active list.

<!-- 
## 📚 Resources

- [WordPress Plugin Page](https://wordpress.org/plugins/hackrepair-plugin-archiver/)
- [Support Forum](https://wordpress.org/support/hackrepair-plugin-archiver)

## ☕ Support the Plugin

If this plugin has saved your bacon (or coffee), consider [buying Jim a coffee](https://hackrepair.com/donations/buy-jim-a-coffee).

Every contribution helps plugin developers like us stay caffeinated and continue improving the tools you love!
-->
## 📄 License

[GPLv2 or later](https://www.gnu.org/licenses/gpl-2.0.html) — free as in freedom.
