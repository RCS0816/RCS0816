+++
author = ''
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
generation = 3
image = '/coe-assets/foobar.jpg' # Your cover image here (can be removed & path may be changed)
tags = [ 'coe-post' ]            # can be altered
summary = ''                     # If the default summary is too long, put
                                 # something shorter here. if not, remove this line.
draft = true                     # Don't forget to change this before publishing!
+++
