# GoogleMapSample
Playing around with the <a href="https://developers.google.com/maps/documentation/android/start">Google Maps Android API</a>


<strong>For setup you need to do the following:</strong>
<ol>
 <li>Get a google map api key from the developer console. https://developers.google.com/maps/documentation/android/start#get_an_android_api_key</li>
 <li>Then create a resource file under app/src/main/res/values/api_keys.xml with a string with your key.</li>
</ol>
    
The reason for this is that as best practice we don't want our api keys to be shared publicly. See:
<ul>
 <li>https://developers.google.com/console/help/new/#apikeybestpractices</li>
 <li>https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/</li>
</ul>

I found a nice solution on <a href="http://stackoverflow.com/questions/13979049/edit-an-androidmanifest-when-compiling-to-remove-api-key">StackOverflow</a>.
