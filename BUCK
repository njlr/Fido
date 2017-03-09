cxx_library(
  name = 'fido',
  header_namespace = 'Fido',
  exported_headers = subdir_glob([
    ('include', '**/*.h'),
  ]),
  srcs = glob([
    'src/**/*.cpp',
  ]),
  compiler_flags = [
    '-std=c++14',
  ],
  visibility = [
    'PUBLIC',
  ],
)
