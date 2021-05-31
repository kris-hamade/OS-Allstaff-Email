<script>
  import { link } from "fs";
</script>

<main>
  <html>
    <head>
      <script src="jquery.js"></script>
      <script>
        $(function () {
          $("#includedContent").load("b.html");
        });
      </script>
    </head>

    <body>
      <div id="includedContent" />
    </body>
  </html>
</main>
