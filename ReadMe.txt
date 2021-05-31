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


# uploaded urls:
/uploads/agent-1/the-group/svg-icons/bathtub.svg
https://www.calgary-real-estate.com/uploads/agent-1/the-group/svg-icons/bathtub.svg

/uploads/agent-1/the-group/community/woodlands/sm/woodlands_wm__10_.jpg
https://www.calgary-real-estate.com/uploads/agent-1/the-group/community/woodlands/sm/woodlands_wm__10_.jpg


/uploads/agent-1/the-group/12512-17-street-sw/12512-17-street-sw-hero-bg.jpg

###===============================================================================

## hero image:
  Photo by Kaboompics .com from Pexels

## newspaper folded svg:
  <div>Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>

## Script to add custom styles:
  </section>
  <script>// <![CDATA[
  function addCss(fileName) {

    var head = document.head;
    var link = document.createElement("link");

    link.type = "text/css";
    link.rel = "stylesheet";
    link.href = fileName;

    head.appendChild(link);
  }

  addCss('https://thegroup-resource.netlify.app/media-styles.css');
  // ]]></script>