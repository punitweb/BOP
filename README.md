# bop
BOP - Beauty of Popups is a cross platform pure CSS popups framework. Easy implementation for good looking , responsive popups.

<p>
<h3>Step 1 // Link The CSS</h3>
<code>
&#060;link rel="stylesheet" href="../bop.css" media="screen" title="no title"&#062;
</code>
<p>
<h3>Step 2 // Link The Javascript <b>(inside the body)</b></h3>
<code>
&#060;script type="text/javascript" src="../bop-js.js""&#062;&#060;/script&#062;
</code>
<p>
<h3>Step 3 // Finally the HTML</h3><br>
<h8>Each id represents a different popup</h8><br>
<h8> the triggers are at the bottom</h8>
<code>

&#060;!-- the windows --&#062;
  &#060;div id="material-light"&#062;
  &#060;h1&#062;Want to use this?&#060;/h1&#062;
  &#060;p&#062;
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
  &#060;/p&#062;
  &#060;br&#062;
  &#060;div class="exit" onclick="Exit()"&#062;EXIT&#060;/div&#062;
  &#060;/div&#062;

  &#060;div id="material-dark"&#062;
  &#060;h1&#062;Want to use this?&#060;/h1&#062;
  &#060;p&#062;
  -- the content --
  &#060;/p&#062;
  &#060;br&#062;
  &#060;div class="exit" onclick="exitDark()"&#062;EXIT&#060;/div&#062;
  &#060;/div&#062;
  &#060;div id="material-light-anime"&#062;
  &#060;h1 id="head-anime"&#062;Want to use this?&#060;/h1&#062;
  &#060;p id="text-anime"&#062;
   -- the content --
  &#060;/p&#062;
  &#060;br&#062;
  &#060;div class="exit" onclick="exitLightAnime()"&#062;EXIT&#060;/div&#062;
  &#060;/div&#062;
  &#060;div id="material-dark-anime"&#062;
  &#060;h1 id="head-anime-dark"&#062;Want to use this?&#060;/h1&#062;
  &#060;p id="text-anime-dark"&#062;
  -- the content --
  &#060;/p&#062;
  &#060;br&#062;
  &#060;div class="exit" onclick="exitDarkAnime()"&#062;EXIT&#060;/div&#062;
  &#060;/div&#062;

  &#060;!-- ios --&#062;
  &#060;div id="ios-light"&#062;
  &#060;center&#062;&#060;h1&#062;Want to use this?&#060;/h1&#062;
  &#060;p&#062;
    -- the content --
  &#060;/p&#062;
  &#060;br&#062;
  &#060;div class="exit" onclick="iosLightExit()"&#062;OK&#060;/div&#062;
&#060;/center&#062;
  &#060;/div&#062;
  &#060;div id="ios-dark"&#062;
  &#060;center&#062;&#060;h1&#062;Want to use this?&#060;/h1&#062;
  &#060;p&#062;
  -- the content --
 &#060;/p&#062;
  &#060;br&#062;
  &#060;div class="exit" onclick="iosDarkExit()"&#062;OK&#060;/div&#062;
&#060;/center&#062;
  &#060;/div&#062;
  &#060;div id="modern-light"&#062;
  &#060;h1&#062;Want to use this?&#060;/h1&#062;
  &#060;p&#062;
   -- the content --
  &#060;/p&#062;
  &#060;br&#062;
  &#060;div class="exit" onclick="modernExit()"&#062;EXIT&#060;/div&#062;
  &#060;/div&#062;
  &#060;div id="modern-dark"&#062;
  &#060;h1&#062;Want to use this?&#060;/h1&#062;
  &#060;p&#062;
   -- the content
  &#060;/p&#062;
  &#060;br&#062;
  &#060;div class="exit" onclick="modernDarkExit()"&#062;EXIT&#060;/div&#062;
  &#060;/div&#062;
  &#060;div id="modern-light-anime"&#062;
  &#060;h1 id="modernlight-head"&#062;Want to use this?&#060;/h1&#062;
  &#060;p id="modernlight-text"&#062;
    -- the content --
  &#060;/p&#062;
  &#060;br&#062;
  &#060;div class="exit" onclick="modernlightanimatedExit()"&#062;EXIT&#060;/div&#062;
  &#060;/div&#062;
  &#060;div id="modern-dark-anime"&#062;
  &#060;h1 id="moderndark-head"&#062;Want to use this?&#060;/h1&#062;
  &#060;p id="moderndark-text"&#062;
   -- the content --
  &#060;/p&#062;
  &#060;br&#062;
  &#060;div class="exit" onclick="moderndarkanimatedExit()"&#062;EXIT&#060;/div&#062;
  &#060;/div&#062;
&#060;!-- windows end here --&#062;
</code>
<p>
<h3>// The Triggers</h3>
<p>
<code>
&#060;div class="button" id="material-dark-anime-button" onclick="modernDarkAnime()"&#062;
              -- the button text --
            &#060;/div&#062;
            </code>
            <br>
            The <b>onclick=""</b> trigger above can have the following methods:-
            <p>
            materialLight() for material light theme
            <p>
            materialDark() for material dark theme
            <p>
            materialLightAnime() for animated material dark theme
            <p>
            iosLight() for iOS light theme
            <p>
            iosDark() for iOS dark theme
            <p>
            modernLight() for light modern theme
            <p>
            modernDark() for dark modern theme
            <p>
            modernLightAnime() for light modern animated theme
            <p>
            modernDarkAnime() for dark modern animated theme
            <p>
            
