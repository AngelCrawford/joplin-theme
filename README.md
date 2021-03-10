<img width="64" src="https://raw.githubusercontent.com/laurent22/joplin/dev/Assets/LinuxIcons/256x256.png" align="left" style="padding:0 1em 1em 0" />

**My private style for [Joplin](https://joplinapp.org).**<br />
It's build on top of the integrated "Dark" Theme included in Joplin.

![Screenshot Joplin](/assets/screenshot1.png)

# Usage
1. Install the "Font Awesome Free" Font to your PC. [Download here](https://fontawesome.com/how-to-use/on-the-web/setup/hosting-font-awesome-yourself), open the Webfonts folder and install the three .ttf files inside
2. Open your `userchrome.css` and paste the content from this repository. Do the same with `userstyle.css`
3. Please be sure to use the integraded "Dark" Theme from Joplin. Have a look for this under `Tools > Options > Appearance`

## Bullet Journal usage
![Screenshot Joplin](/assets/screenshot2.png)

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

# Question
I found the design for the headers in another project, but forgot to save the source. If someone knows from whom this was, I would be really glad to add a source link 😊