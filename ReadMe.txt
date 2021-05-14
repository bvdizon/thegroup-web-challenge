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

addCss('https://fonts.googleapis.com/css2?family=Jost:wght@300;500;700&display=swap');
addCss('https://thegroup-resource.netlify.app/bvd-styles1.css');

addCss('{my-url}');
