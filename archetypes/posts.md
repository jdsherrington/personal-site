+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
+++

{{< chat {{.File.ContentBaseName}}-{{ time.Format "15040502012006" .Date }} >}}
