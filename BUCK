include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'lambda',
  header_only = True,
  header_namespace = 'boost/lambda',
  exported_headers = subdir_glob([
    ('include/boost/lambda', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
