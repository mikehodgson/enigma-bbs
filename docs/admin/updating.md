---
layout: page
title: Updating
---
## Updating your Installation
Updating ENiGMA½ can be a bit of a learning curve compared to other systems. Especially when running off of a development branch (such as `0.0.9-alpha` being the recommended branch as of this writing), you'll want frequent updates.

## Steps
In general the steps are as follows:
1. `cd /path/to/enigma-bbs`
2. `git pull`
3. Merge updates to `config/menu_template.hjson` to your `config/yourbbsname-menu.hjson` file.
4. If there are updates to the `art/themes/luciano_blocktronics/theme.hjson` file and you have a custom theme, you way wan to look at them as well.

Visual diff tools such as [DiffMerge](https://www.sourcegear.com/diffmerge/downloads.php) (free, works on all major platforms) can be very helpful here.
