<h1>Author: Wyatt McCurdy</h1>

<h2>Description</h2>

<p></p>

<p>My Geolocation Repo is a webpage that will check to see if the current browser supports the <strong>navigator.geolocation</strong> object. If the browser does not support geolocation then the page displays an appropriately styled feedback message to the user.</p>

<p>If geolocation is supported then the page tries to fetch the user's current location and then loads a google STATIC map that includes a marker at the center of the map. The map image is loaded at zoom level 14 and the map image is be 400px by 400px.</p>  

<h2>Instructions</h2>

<p>When the page loads all the user needs to do is allow the browser to use their location. There will most likely be a prompt message asking for permission automatically. If no message appears the user may need to adjust their browser settings.</p>

<p>When the code Operates a Canvas element is created dynamically and appended to the page. The Canvas will only be added to the page if the browser supports geolocation.</p>

<p>There will be no content in the <code>&lt;body&gt;</code> tag when the page loads. The JavaScript will determine what gets built on the page.</p>

