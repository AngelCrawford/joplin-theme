<img width="64" src="https://raw.githubusercontent.com/laurent22/joplin/dev/Assets/LinuxIcons/256x256.png" align="left" style="padding:0 1em 1em 0" />

**My private style for [Joplin](https://joplinapp.org).**<br />
It's build on top of the integrated "Dark" Theme included in Joplin.

![Screenshot Joplin](/assets/screenshot1.png)

# Usage

1. Install the "Font Awesome Free" Font to your PC. [Download here](https://fontawesome.com/how-to-use/on-the-web/setup/hosting-font-awesome-yourself), open the Webfonts folder and install the three .ttf files inside
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

I even created a [template](https://joplinapp.org/#note-templates) for every message in my Joplin.

Copy all the files under the `templates` folder from here to your local templates folder. Then you can insert the messages as templates.

You can find your Template folder here `C:\Users\<username>\.config\joplin-desktop\templates` under Windows.

![Template Messages](/assets/template_messages.png)

# Mermaid Dark modes

Mermaid diagrams are look like this in dark mode.
![Template Messages](/assets/SimpleDark.png)

For better view add following line at the starting of mermaid syntax.

```
%%{init: { "theme": "dark" } }%%
```

And same view will get change like below. You can create a template for the same line.
![Template Messages](/assets/ReadyMadeDark.png)

**Syntax**

> <span>```</span>mermaid <br/>
> %%{init: { "theme": "dark" } }%% <br/>
> graph TD <br/>
> direction BT <br/>
> User --> |Insert| id1[(OLTP)] <br/>
> User --> |Update| id1[(OLTP)] <br/>
> User --> |Delete| id1[(OLTP)] <br/>
> User --> |Select| id2[(OLAP)] <br/>
> id1 -.-> Normalization,-Reduce_Redundancy <br/>
> id2 -.-> De-Normalization <br/>
>
> <p>```</p>

# Used Plugins

I use the following Plugins which are already designed by me:

- [Copy Anchor Link](https://github.com/hieuthi/joplin-plugin-copy-anchor-link)
- [Markdown Table: Colorize](https://github.com/hieuthi/joplin-plugin-markdown-table-colorize)
- [Note Tabs](https://github.com/benji300/joplin-note-tabs)
- [Outline](https://github.com/cqroot/joplin-outline)
- [Templates](https://github.com/joplin/plugin-templates)

## Outline Plugin Design

If you want to use my Outline Plugin style from the images, then add the following CSS line to Tools > Options > Outline > "Show Advanced Settings" > "User Style".

```css
.outline-content {background:#2E3138; padding:5px 0;} .toc-item-link {font-size:13px; display:flex !important; align-items:center; text-indent:-20px;} .toc-item-link > * {padding:0 0 0 12px;} .toc-item-link:hover {font-weight:normal; text-decoration:none; background:#4E4E4E; cursor:default;} a#header {color:#ffffff; height:30px; line-height:30px; padding:0 0 0 6px;} a#header::before {content:"\e917"; font-family:"icomoon" !important; font-size:18px; color:#ffffff; margin:0 8px 0 0; font-weight:300; top:3px; position:relative;}
```

# Question

I found the design for the headers in another project, but forgot to save the source. If someone knows from whom this was, I would be really glad to add a source link 😊
