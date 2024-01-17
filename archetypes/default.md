+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
+++

{{< chat {{.File.ContentBaseName}} >}}
