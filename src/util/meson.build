util_src = files([
  'util_env.cpp',
  'util_string.cpp',
  'util_fps_limiter.cpp',
  'util_gdi.cpp',
  'util_luid.cpp',
  'util_matrix.cpp',
  'util_monitor.cpp',
  'util_shared_res.cpp',

  'com/com_guid.cpp',
  'com/com_private_data.cpp',

  'config/config.cpp',

  'log/log.cpp',
  'log/log_debug.cpp',

  'sha1/sha1.c',
  'sha1/sha1_util.cpp',

  'sync/sync_recursive.cpp',
])

util_lib = static_library('util', util_src,
  include_directories : [ dxvk_include_path ],
)

util_dep = declare_dependency(
  link_with           : [ util_lib ],
)
