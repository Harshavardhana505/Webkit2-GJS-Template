# Webkit2-GJS-Template<br>
In line 47 of template.js, there is a line: <br><br>

>  this._webView.load_uri (GLib.filename_to_uri (GLib.get_current_dir() +
            "/index.html", null));
           
There you can add your index.html in the same current folder of template.js
After that you just run 
> gjs template.js
