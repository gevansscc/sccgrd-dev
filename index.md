---
layout: default
title: Home
---
  <script>
    window.dataLayer = window.dataLayer || [];
    window.dataLayer.push({
      event: "homepage_redirect",
      redirect_target: "/grad-show/2026/"
    });

    setTimeout(function () {
      window.location.replace("/grad-show/2026/");
    }, 600); // 600ms delay ensures GTM loads
  </script>

</head>
<body>
  <p>Redirecting…</p>
</body>
</html>

