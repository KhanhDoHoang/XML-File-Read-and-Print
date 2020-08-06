# XML-File-Read-and-Print
Using JavaScript reading XML file and print

### JQuery link: https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js

** Get data from XML FILE:  **
``var xhttp = new XMLHttpRequest();
        xhttp.onreadystatechange = function () {
          if (this.readyState == 4 && this.status == 200) {
            myFunction(this);
          }
        };
        xhttp.open("GET", "Books.xml", true);
        xhttp.send();``
 ** Toggle **
 ``var demo = document.getElementById("demo");
        panel.style.display = panel.style.display == "none" ? "block" : "none";``
