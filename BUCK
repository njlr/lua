cxx_library(
  name = 'lua',
  header_namespace = 'lua',
  srcs = glob([
    '*.c',
  ]),
  exported_headers = glob([
    '*.h',
  ]),
  compiler_flags = [
    '-x c',
    '-pedantic', 
    '-Wextra', 
    '-Wshadow', 
    '-Wsign-compare', 
    '-Wundef', 
    '-Wwrite-strings', 
    '-Wredundant-decls', 
    '-Wdisabled-optimization', 
  ],
  visibility = [
    'PUBLIC',
  ],
)
