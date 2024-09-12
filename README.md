# GSO-Service-Titan-Portal
  Install Web Scheduler

1. Please paste this code at the end in the <body>:

    <script>
      (function(q,w,e,r,t,y,u){q[t]=q[t]||function(){(q[t].q = q[t].q || []).push(arguments)};
        q[t].l=1*new Date();y=w.createElement(e);u=w.getElementsByTagName(e)[0];y.async=true;
        y.src=r;u.parentNode.insertBefore(y,u);q[t]('init', '1e8344c9-797d-4f2b-8388-8e261613d2dd');
      })(window, document, 'script', 'https://static.servicetitan.com/webscheduler/shim.js', 'STWidgetManager');
    </script>

2. Please add the following onclick attribute to your desired html element:

  onclick=STWidgetManager("ws-open")
