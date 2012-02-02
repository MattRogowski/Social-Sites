Name: Social Sites
Description: Add which social sites you're a member of so you can find eachother on social networking sites.
Website: http://mattrogowski.co.uk
Author: MattRogowski
Authorsite: http://mattrogowski.co.uk
Version: 0.2.2
Compatibility: 1.6.x
Files: 5 (plus 16 initial social site icons)
Templates added: 6
Template changes: 4
Settings added: 2
Database changes: 1 new table, 1 new column to 1 default table.

To Install:
Upload ./inc/plugins/socialsites.php to ./inc/plugins/
Upload ./admin/modules/config/socialsites.php to ./admin/modules/config/
Upload ./inc/languages/english/socialsites.lang.php to ./inc/languages/english/
Upload ./inc/languages/english/admin/config_socialsites.lang.php to ./inc/languages/english/admin/
Upload ./images/usercp/group_link.png to ./images/usercp/
Upload ./images/socialicons/ and its contents to ./images/
Open ./files/socialsites_css_additions.css and add the code inside to the bottom of usercp.css for your themes, by going to ACP > Templates & Style > **choose theme** > usercp.css > Edit Stylesheet: Advanced Mode > scroll down and add the CSS to the bottom.
Go to ACP > Plugins > Install and Activate
Go to ACP > Configuration > Social Sites Settings > Configure Settings.
Go to ACP > Configuration > Social Sites (left menu) > manage social sites.

Information:
This plugin will allow your users to add their username/id for any social sites you setup.

The icons will show in the postbit and on profiles, and will link to the user's profile on the social site.

Images credited to Komodo Media. Source and icons download: http://www.komodomedia.com/blog/2009/06/social-network-icon-pack/

Change Log:
21/11/10 - v0.1 -> Initial beta release.
21/01/11 - v0.1 -> v0.2 -> The social sites are now cached instead of being queried on the showthread and profile pages. Fixed a bug where the icons wouldn't show up when adding a reply with quick reply, which may also have caused a PHP error. Fixed a bug where the icons wouldn't be displayed in post previews, PMs or forum announcements. To upgrade, deactivate Social Sites, reupload ./inc/plugins/socialsites.php and ./admin/modules/config/socialsites.php, activate Social Sites.
07/02/11 - v0.2 -> v0.2.1 -> Added a Who's Online List location for when a user is editing their social sites. Added a breadcrumb navigation link to the Social Sites page in the User CP. To upgrade, reupload ./inc/plugins/socialsites.php and ./admin/modules/config/socialsites.php
03/12/11 - v0.2.1 -> v0.2.2 -> Made compatible with MyBB 1.6.5. To upgrade, reupload ./inc/plugins/socialsites.php

Copyright 2011 Matthew Rogowski

 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at

 ** http://www.apache.org/licenses/LICENSE-2.0

 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.