
This add-on adds the following supplementary formatting buttons to Anki:

* a **code** button that will wrap selected text in a `<code>` (shortcut: <kbd>Ctrl</kbd> + <kbd>,</kbd>). You can specify the CSS class you want to use in combination with `<code>`. For example, we have a CSS class named `c` defined in the *Styling* section of *Cards*:

        .c {
            font-family: droid sans mono;
            background-color: #f2f2f2;
            padding-left: 5px;
            padding-right: 5px;
        }

    In the options *Tools &gt; Supplementary buttons add-on (options) &gt; Alter &lt;code&gt; CSS...* we can specify the class name, so that our `<code>` elements will be automatically transformed to `<code class="c">`.

* an **unordered list** button (shortcut <kbd>Ctrl</kbd> + <kbd>[</kbd>):

    * One
    * Two
    * Three

* an **ordered list** button (shortcut <kbd>Ctrl</kbd> + <kbd>]</kbd>):

    1. One
    2. Two
    3. Three

* an **indent** button (shortcut <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>I</kbd>) to indent text or lists:

    1. One
        * Two
            1. Three

* an **outdent** button (shortcut <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>O</kbd>) to outdent text or lists

* a **strikethrough** button (shortcut <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>5</kbd>):

    ~~strikethrough text example~~

* a **code block** button (shortcut <kbd>Ctrl</kbd> + <kbd>.</kbd>) that creates a `<pre>` block element around the selected element

* a **horizontal rule** button (shortcut <kbd>Ctrl</kbd> + <kbd>H</kbd>) that inserts a horizontal rule after the current position of the cursor

* a **definition list** button (shortcut <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>D</kbd>):

    <dl><dt>definition term</dt><dd>definition description</dd>

    Upon clicking the button, a popup will appear where you can enter your terms and descriptions.

* a **list** button (shortcut <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>3</kbd>):

    header | header
    --- | ---
    content | content
    
    You can select the number of columns and rows.

The buttons can be enabled or disabled individually in *Tools > Supplementary buttons add-on (options)*, so feel free to disable the buttons you don't use.

To add this add-on to Anki, copy the file `extra_buttons.py` to your Anki add-on folder, by default on Linux `$HOME/Anki/addon`.