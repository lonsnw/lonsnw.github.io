<h1>README</h1>
When/if the level-up branch is merged, it will remove the application responses.

This branch is following the changes that I'm making for the Level Up Tutorial that's encouraged as prework for the program.

    https://levelup.video/tutorials/how-to-make-your-first-website/how-to-make-your-first-website

<h2>Notes from Level Up Tuts videos</h2>

<h3>html notes</h3>

* We name the file index.html because that is the default file that sites will load first.
     * *Not sure why this is true; perhaps this is a question worth asking.*
* You can only have one h1 per page because of SEO.  It won't be prevented or whatever but the search engine will look for that tag/heading and therefore you want to prioritize a single heading per page in order to take advantage of that.
* 

<h3>css notes</h3>

* You can write the CSS in the html file by adding the following: 

    <style>
         h1 {

         }
    </style>
And essentially just embedding the CSS in the same way that it's written in the CSS file but tagged as style.

* The reason to not do this is essentially that you can reuse a stylesheet for multiple pages if you have the CSS in a file instead of embedding it into the html.
     * The href is a hypertext reference.  The path ("resume-style.css") works because the CSS file is in the same folder.  If it were in a different folder, like a folder named styles, it would need to have the path as well; without more of the path, it's read as referring to the current directory.

<h3>general notes</h3>

* If you make changes in the inspect element, they're not going to remain there.
* 
