<script>
    function scrollTitle() {
      var title = document.title;
      var newTitle = title.substring(1) + title.charAt(0);
      document.title = newTitle;
    }
  
    setInterval(scrollTitle, 5);
  </script>