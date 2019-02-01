load('//:subdir_glob.bzl', 'subdir_glob')
load('//:buckaroo_macros.bzl', 'buckaroo_deps')

prebuilt_cxx_library(
  name = 'static-assert',
  header_namespace = 'boost',
  header_only = True,
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  deps = [
    'buckaroo.github.buckaroo-pm.boost-config//:config',
    'buckaroo.github.buckaroo-pm.boost-detail//:detail',
  ],
  visibility = [
    'PUBLIC',
  ],
)
