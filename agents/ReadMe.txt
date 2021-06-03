<script>
  function addCss(fileName) {

    var head = document.head;
    var link = document.createElement("link");

    link.type = "text/css";
    link.rel = "stylesheet";
    link.href = fileName;

    head.appendChild(link);
  }

  addCss('https://thegroup-resource.netlify.app/agents/css/styles.css');
</script>