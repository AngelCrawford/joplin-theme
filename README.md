<img width="64" src="https://raw.githubusercontent.com/laurent22/joplin/dev/Assets/LinuxIcons/256x256.png" align="left" style="padding:0 1em 1em 0" />

**My private style for [Joplin](https://joplinapp.org).**<br />
It's build on top of the integrated "Dark" Theme included in Joplin.

![Screenshot Joplin](/assets/screenshot5.png)

# Usage
1. Install the "Font Awesome Free" (Version 6) Font to your PC. [Download here](https://use.fontawesome.com/releases/v6.4.0/fontawesome-free-6.4.0-web.zip), open the Webfonts folder and install the three .ttf files inside (you don't need to install the `fa-v4compatibility.ttf`)
2. Open your `userchrome.css` and paste the content from this repository. Do the same with `userstyle.css`. You will find these files under `C:\Users\<username>\.config\joplin-desktop`.
3. Please be sure to use the integraded "Dark" Theme from Joplin. Have a look for this under `Tools > Options > Appearance`

## Bullet Journal usage
![Screenshot Joplin](/assets/screenshot6.png)

1. If you want to use my Bullet Journal style, create a new file in the same folder where the `userstyles.css` is lying. Name the file `userstyle-bujo.css`
2. Paste the content from this repository, don't forget to install the "Font Awesome Free" font to your local PC
3. At the end of every note, where you want to use this extra style, add this line `<style>@import url(C:/Users/<username>/.config/joplin-desktop/userstyle-bujo.css);</style>`

### Bullet Journal Calendar usage
![Screenshot Calendar](/assets/bujo-calendar-2.png)

Add this code to create a table calendar in you BuJo note.

```markdown
<div class="calendar">

| May |  Mo. |  Tu. |  We. |  Th. |  Fr. |  Sa. |  Su. |
| --: | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| #40 | *3* <i>💉</i> <m>May</m> | *4* | *5* <i>🚗</i> | *6* | *7* <i>🩰</i> | *8* <i>🛒🩰</i> | *9* |
| [#41](:/Joplin_Internal_Link) | *10* <i>🎂</i> | *11* | *12* | *13* <i>🍣</i> | *14* | *15* <i>🥂🩰</i> | *16* |
| #42 | *17* | *18* | *19* <i>🎂</i> | *20* | *21* <i>🍵</i> | *22* <i>🩰</i> | *23* |
| #43 | *24* | *25*<i>🌴🎷</i> | *26* | *27* | *28* <d>🌴</d> | *29* <d>🌴</d> | *30* <d>🌴</d> |
| #44 | *31* <i>🛋️</i> | **1** <m>April</m> | **2** <d>🌴</d> | **3** | **4** |  **5** | **6** |
</div>
```

## Message usage
![Screenshot Joplin](/assets/screenshot7.png)

To use this message boxes, copy this to your note in Joplin.

```html
<b-notice>
  <b>NOTICE:</b> This is a notice box
</b-notice>

<b-help>
  <b>HELP:</b> This is a help box
</b-help>

<b-success>
  <b>SUCCESS:</b> This is a success box
</b-success>

<b-warning>
  <b>WARNING:</b> This is a warning box
</b-warning>

<b-error>
  <b>ERROR:</b> This is a error box
</b-error>

<b-construction>
  <b>CONSTRUCTION:</b> This is a construction box.
</b-construction>
```

## Mermaid Dark mode usage
![Nermaid Dark mode](/assets/mermaid-dark-mode.png)

For better view add following line at the starting of mermaid syntax.
(Thanks to https://github.com/KedarGhadge for this addition.)

```
%%{init: { "theme": "dark" } }%%
```

# Used Plugins

I use the following Plugins which are already designed by me:

- [Copy Anchor Link](https://github.com/hieuthi/joplin-plugin-copy-anchor-link)
- [Markdown Table: Colorize](https://github.com/hieuthi/joplin-plugin-markdown-table-colorize)
- [Note Tabs](https://github.com/benji300/joplin-note-tabs)
- [Outline](https://github.com/cqroot/joplin-outline)
- [Templates](https://github.com/joplin/plugin-templates)

## Templates Plugin
![Template Messages](/assets/template_messages.png)

* Install the Plugin and restart Joplin
* Create a new note, insert one message code from above to the note and add the `template`-tag

## Outline Plugin

If you want to use my Outline Plugin style from the images, then add the following CSS line to Tools > Options > Outline > "Show Advanced Settings" > "User Style".

```css
.outline-content {background:#2E3138; padding:5px 0;} .toc-item-link {height:30px, font-size:13px; display:flex !important; align-items:center; text-indent:-20px;} .toc-item-link > * {padding:0 0 0 12px;} .toc-item-link:hover {font-weight:normal; text-decoration:none; background:#4E4E4E; cursor:default;} a#header {color:#ffffff; height:30px; line-height:30px; padding:0 0 0 6px;} a#header::before {content:"\e917"; font-family:"icomoon" !important; font-size:18px; color:#ffffff; margin:0 8px 0 0; font-weight:300; top:3px; position:relative;}
```

# Question

I found the design for the headers in another project, but forgot to save the source. If someone knows from whom this was, I would be really glad to add a source link 😊
