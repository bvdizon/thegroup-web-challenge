# Netlify Resource:
https://thegroup-resource.netlify.app/

# CSS Resource:
https://thegroup-resource.netlify.app/bvd-styles.css

# StackOverflow Source:
https://stackoverflow.com/questions/11833759/add-stylesheet-to-head-using-javascript-in-body

# Script to add
function addCss(fileName) {

  var head = document.head;
  var link = document.createElement("link");

  link.type = "text/css";
  link.rel = "stylesheet";
  link.href = fileName;

  head.appendChild(link);
}

addCss('{my-url}');