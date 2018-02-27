<h1>Custom Keyboards</h1>

<p>Honestly, this is just a quick way for me to host my Keylayouts, without worrying about messing them up or forgetting how my layouts usually look.</p>

<p>Currently, the layouts I have are as follows:</p>
 <ul>
  <li>Cute
    <ul><li>This keyboard is my personal keyboard layout. Will likely split into "Cute" and "Cuter," once I work on Maeve's</li></ul>
  </li>
  <li>Singhal
     <ul><li>This keyboard is for Abhay, and replaces most alt-keys with greek letters (with some other misc additions)</li></ul>
   </li>
 </ul>
 
 <p>I will update this README if I make any more major changes/new additions. Since .keylayout files are just XML, feel free to tinker with them as you see fit. I'm using <a href="http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele">Ukelele</a> in order to generate .keylayout files and modify things, which I would highly recommend doing. That said, Ukelele is very prone to crashing, so, watch for that—I tend to use Ukelele for the heavy lifting, then switch into a text editor for modifications thereafter (shoutout to VSCode).</p>
 
 <h2>Setup</h2>
 
 Setting up a custom .keylayout is very simple—all you need to do is drag the intended file to ~/Library/Input Sources (Command-G also speeds this up), and open it from System Preferences. After adding it, open it from System Preferences > Keyboard > Input Sources, and select it. It should be under "Others." I would also recommend enabling the keyboard shortcut for switching keyboard, I use Command-ESC, but I think you can set it to whatever. This is because, occasionally, your input source will be changed by a document, or your computer won't recognize it properly. It happens infrequently, but it's good to be able to switch if need be.
 
 <h2>Known Issues (& Workarounds)</h2>

<ul>
  <li>Keys cannot output more than 20 keys at a time<ul><li>Easiest solution is to just use text replacement (under System Preferences > Keyboard > Text) in order to handle paragraphs/sentences)</li></ul>
  </li>
</ul>
