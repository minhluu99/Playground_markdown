<!DOCTYPE html>
<html>
<head>
    <title>My Document</title>
</head>
<body>
    <!-- This part is generated from your Markdown -->
    <h1>My Interactive Document</h1>
    <p>Here is some text.</p>
    <button id="my-button">Click Me!</button>
    <!-- End of generated content -->

    <!-- This is the part you add to make it interactive -->
    <script>
      const myButton = document.getElementById('my-button');

      // The function passed to addEventListener is the "callback"
      myButton.addEventListener('click', () => {
        alert('Button was clicked!');
      });
    </script>
</body>
</html>
