<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }} | {{ site.title }}</title>
  <meta name="description" content="{{ page.description | default: site.description }}">

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet">

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <!-- Stylesheet -->
  <link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">
</head>
<body>
  {% include header.html %}
  <main>
    {{ content }}
  </main>
  {% include footer.html %}

  <script>
    // Mark active nav link
    (function() {
      var path = window.location.pathname.replace(/\/$/, '') || '/';
      document.querySelectorAll('.nav-links a').forEach(function(a) {
        var href = a.getAttribute('href').replace(/\/$/, '') || '/';
        if (path === href || (href !== '/' && path.startsWith(href))) {
          a.classList.add('active');
        }
      });
    })();
  </script>
</body>
</html>
