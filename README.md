<img width="64" src="https://raw.githubusercontent.com/laurent22/joplin/dev/Assets/LinuxIcons/256x256.png" align="left" style="padding:0 1em 1em 0" />

**My private style for [Joplin](https://joplinapp.org).**<br />
It's build on top of the integrated "Dark" Theme included in Joplin.

![Screenshot Joplin](/assets/screenshot1.png)

# Usage
1. Install the "Font Awesome Free" (Version 5) Font to your PC. [Download here](https://fontawesome.com/v5/docs/web/setup/host-font-awesome-yourself), open the Webfonts folder and install the three .ttf files inside
2. Open your `userchrome.css` and paste the content from this repository. Do the same with `userstyle.css`
3. Please be sure to use the integraded "Dark" Theme from Joplin. Have a look for this under `Tools > Options > Appearance`

## Bullet Journal usage
![Screenshot Joplin](/assets/screenshot4.png)

1. If you want to use my Bullet Journal style, create a new file in the same folder where the `userstyles.css` is lying. Name the file `userstyle-bujo.css`
2. Paste the content from this repository, don't forget to install the "Font Awesome Free" font to your local PC
3. At the end of every note, where you want to use this extra style, add this line `<style>@import url(C:/Users/<username>/.config/joplin-desktop/userstyle-bujo.css);</style>`

## Message usage
![Screenshot Joplin](/assets/screenshot3.png)

To use this message boxes, copy this to your note in Joplin.

```html
<b-notice>
  <b>NOTICE:</b> This is a <b-notice></b-notice> box
</b-notice>

<b-help>
  <b>HELP:</b> This is a <b-help></b-help> box
</b-help>

<b-success>
  <b>SUCCESS:</b> This is a <b-success></b-success> box
</b-success>

<b-warning>
  <b>WARNING:</b> This is a <b-warning></b-warning> box
</b-warning>

<b-error>
  <b>ERROR:</b> This is a <b-error></b-error> box
</b-error>

<b-construction>
  <b>CONSTRUCTION:</b> This is a <b-construction></b-construction> box.
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
