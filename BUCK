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
    '-std=c11',
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
