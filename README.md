# Confluence User Macros

[![Velocity](https://img.shields.io/badge/Language-Velocity-informational.svg)](https://velocity.apache.org/)
[![Support](https://img.shields.io/badge/Supported-yes-009900.svg)](https://github.com/glewe/confluence-user-macros/issues)

## What are Confluence User Macros ?

If you run your own Confluence instance (Server or Data Center) you can create custom “User Macros”, little scripts 
that can be included in pages creating content on the fly. With those macros you can create simple HTML code snippets 
as well as utilize Velocity code accessing information from your Confluence database.

I will not address the basics of writing a user macro here. That is well documented in the Confluence documentation 
[here](https://confluence.atlassian.com/doc/writing-user-macros-4485.html).

## My User Macros

Along my work as a Confluence administrator I ran into several situations where native Confluence Server features did 
not offer what admins or users needed. Plugins were not available either or too expensive for the purpose. In many of 
those cases I found that a user macro was just the right solution to the challenge. The Confluence user community 
helped me a lot writing them. Here are my most useful ones as my contribution back to that community.

---

### [Anonymous Access](/src/anonymous-access)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/anonymous-access/kgpg-32.png?raw=true" align="left" alt=""/>
This Confluence user macro lists all spaces for which 'Anonymous' has at least view permission.

---

### [Audio Control](/src/audio-control)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/audio-control/arts-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds an HTML5 audio control element to your page that can play MP3, OGG and WAV files.

---

### [Blockquote](/src/blockquote)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/blockquote/info-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a styled blockquote to your page.

---

### [Bootstrap Button](/src/bootstrap-button)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/bootstrap-button/bootstrap-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a Bootstrap 3 styled button, supporting different colors and sizes, and linking to a URL.

---

### [Bootstrap Progress Bar](/src/bootstrap-progress-bar)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/bootstrap-progress-bar/bootstrap-32.png?raw=true" align="left" alt=""/>
This set of two Confluence user macros adds a Bootstrap like progress to your page, offering different coloring and animation options.

---

### [ChartJs v2](/src/chartjsv2)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/chartjsv2/kchart-32.png?raw=true" align="left" alt=""/>
This set of Confluence user macros adds animated diagrams to your page based on Chart.js v2.

---

### [Colored Panel](/src/colored-panel)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/colored-panel/window_list-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a headed panel to your page with several coloring options.

---

### [Confluence Users Access](/src/confluence-users-access)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/confluence-users-access/kgpg-32.png?raw=true" align="left" alt=""/>
This macro lists all spaces for which the group 'confluence-users' has at least view permission.

---

### [Expand All](/src/expand-all)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/expand-all/folder_orange_open-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a button group that toggles/expands/collapses all Expand sections on your page.

---

### [Group Members](/src/group-members)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/group-members/kdmconfig-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a sorted table with numbered rows for each member of a given group.

---

### [Hide If](/src/hide-if)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/hide-if/hideif-32.png?raw=true" align="left" alt=""/>
This Confluence user macro allows to hide content from users, groups or permissions.

---

### [Hide Sections](/src/hide-sections)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/hide-sections/file_locked-32.png?raw=true" align="left" alt=""/>
This Confluence user macro hides different Confluence sections of your page.

---

### [Horizontal Ruler](/src/horizontal-ruler)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/horizontal-ruler/kruler-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a customizable HR element to your page.

---

### [Legend](/src/legend)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/legend/template_source-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a legend box to the top right of the page.

---

### [Local Time](/src/local-time)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/local-time/clock-32.png?raw=true" align="left" alt=""/>
This Confluence user macro displays the user's local date and time offering several options. Use once per page.

---

### [Marquee](/src/marquee)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/marquee/knewsticker-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds an HTML5 marquee element to your page.

---

### [Page Font](/src/page-font)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/page-font/font-32.png?raw=true" align="left" alt=""/>
This Confluence user macro allows you to set a different font incl. size and color for your page.

---

### [Page Permissions](/src/page-permissions)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/page-permissions/kgpg-32.png?raw=true" align="left" alt=""/>
This Confluence user macro lists space permissions and page restrictions for the current page.

---

### [Profile Info](/src/profile-info)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/profile-info/vcard-32.png?raw=true" align="left" alt=""/>
This Confluence user macro displays a panel with the profile info of a single user or all users of a group.

---

### [Risk Matrix](/src/risk-matrix)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/risk-matrix/risk-matrix-icon-32.png?raw=true" align="left" alt=""/>
Creates a risk matrix based on an issue type, likelihood field and impact field from a linked Jira instance.

---

### [Show If](/src/show-if)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/show-if/showif-32.png?raw=true" align="left" alt=""/>
This Confluence user macro allows to show content only to certain users, groups or permissions.


---

### [Space Permissions](/src/space-permissions)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/space-permissions/kgpg-32.png?raw=true" align="left" alt=""/>
This Confluence user macro lists users and groups having permissions to the current or given space.

---

### [Spacer](/src/spacer)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/spacer/kget_list-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds a vertical space into your page.

---

### [Telephone Link](/src/telephone-link)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/telephone-link/chat-32.png?raw=true" align="left" alt=""/>
This Confluence user macro adds an HTML telephone link to your page.

---

### [Tiny Link](/src/tinylink)
<img src="https://github.com/glewe/confluence-user-macros/raw/master/src/tinylink/browser-32.png?raw=true" align="left" alt=""/>
This Confluence user macro displays a link to the Tiny URL of the current page.

