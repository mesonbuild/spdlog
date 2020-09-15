src = [
    'spdlog.cpp',
    'stdout_sinks.cpp',
    'color_sinks.cpp',
    'file_sinks.cpp',
    'async.cpp',
    'cfg.cpp',
    'fmt.cpp'
]

spdlog_lib = library('spdlog',src,include_directories : inc,dependencies : thread_dep, cpp_args : '-DSPDLOG_COMPILED_LIB')
