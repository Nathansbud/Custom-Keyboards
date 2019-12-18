<h1>Custom Keyboards</h1>

<p>Honestly, this is just a quick way for me to host my Keylayouts, without worrying about messing them up or forgetting how my layouts usually look.</p>
 
<p>I will update this README if I make any more major changes/new additions. Since keylayout files are just fancy XML, feel free to tinker with them as you see fit. I'm using <a href="http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele">Ukelele</a> in order to generate/modify keylayout files which I would highly recommend doing. That said, Ukelele is very prone to crashing, so, watch for that—I tend to use Ukelele for the heavy lifting, then switch into a text editor for modifications thereafter (shoutout to VSCode).</p>

<h2>Current Keyboards</h2>
<ul>
	<li>Super Cute<ul><li>My supercharged personal keylayout, taking advantage of dead key states in order to embed emotes, emoji, greek letters, and handy shortcuts into a single super-keylayout</li></ul></li>
	<li>Cute<ul><li>My (buggy) personal keylayout, including all emotes, some handy shortcuts, and the removal of all "useless" keys</li></ul></li>
  <li>Emoji<ul><li>A QWERTY keyboard designed with emoji in mind, alt-keys all output various emoji!</li></ul></li>
	<li>Template<ul><li>A blank English keyboard layout, with no alt keys filled in. Used as a base keyboard when making new keyboard layouts</li></li></ul>
  <li>Science<ul><li>An unfinished keylayout intended for science/math usage (greek characters for variables)</li></li></ul>
</ul>
 
<h2>Known Issues</h2>
<ul>
  <li>Keys cannot output more than 20 keys at a time<ul><li>Easiest solution is to just use text replacement (under System Preferences > Keyboard > Text) in order to handle paragraphs/sentences)</li></ul></li>
  <li>Ukelele cannot handle a maxout value >8 for any key—any key outputting >8 characters will crash Ukelele on save<ul><li>Crash is not 100% certain (can just keep trying until it doesn't crash), but makes editing the keyboard supremely unstable...</li></ul></li>  
</ul>
