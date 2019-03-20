cxx_library(
  name = 'fcpp',
  header_namespace = '',
  exported_headers = glob([
    '*.h',
  ]),
  preprocessor_flags = [
    '-Dunix',
    '-Dpdc',
    '-DUNIX',
    # '-DDEBUG',
  ],
  srcs = glob([
    '*.c',
  ]),
  licenses = [
    'COPYING',
  ],
  visibility = [
    'PUBLIC',
  ],
)
