+++
title = "About"
id = "about"

<html>
{{< gallery dir="/img/" />}} {{< load-photoswipe >}}
what!!!!
</html>
{{ % highlight html %}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{ % /highlight %}}
+++
