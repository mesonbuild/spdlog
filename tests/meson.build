prog_src = [
    'errors.cpp',
    'file_helper.cpp',
    'file_log.cpp',
    'test_misc.cpp',
    'test_pattern_formatter.cpp',
    'test_async.cpp',
    'registry.cpp',
    'test_macros.cpp',
    'utils.cpp',
    'main.cpp'
]

tests_exe = executable('tests_exe', prog_src, include_directories : inc, dependencies : thread_dep)
test('tests', tests_exe)
