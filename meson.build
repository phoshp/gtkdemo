project('gtkdemo', 'c',
  version : '0.1',
  default_options : ['warning_level=3'])

gtkdep = dependency('gtk+-3.0')

executable('gtkdemo',
           'main.c',
           install : true,
           dependencies: gtkdep)
