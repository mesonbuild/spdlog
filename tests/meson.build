test_inc = include_directories('.')

prog_src = ['errors.cpp', 'file_helper.cpp', 'file_log.cpp', 'format.cpp',
			'main.cpp', 'registry.cpp', 'utils.cpp']

tests_exe = executable('tests_exe', prog_src, include_directories : [inc, test_inc], dependencies : thread_dep)
test('tests', tests_exe)
