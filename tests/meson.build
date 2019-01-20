prog_src = [
    'test_errors.cpp',
    'test_file_helper.cpp',
    'test_file_logging.cpp',
    'test_misc.cpp',
    'test_pattern_formatter.cpp',
    'test_async.cpp',
    'includes.h',
    'test_registry.cpp',
    'test_macros.cpp',
    'utils.cpp',
    'utils.h',
    'main.cpp',
    'test_mpmc_q.cpp',
    'test_sink.h',
    'test_fmt_helper.cpp'
]

tests_exe = executable('tests_exe', prog_src, include_directories : inc, dependencies : thread_dep)
test('tests', tests_exe)
