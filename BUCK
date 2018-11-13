prebuilt_cxx_library(
  name = 'static-assert', 
  header_namespace = 'boost', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
    'buckaroo.github.buckaroo-pm.boost-config//:config', 
    'buckaroo.github.buckaroo-pm.boost-detail//:detail', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
