project('spdlog', 'cpp', version : '1.1.0', license: 'MIT',
        default_options : ['cpp_std=c++11'])

inc = include_directories('include')

thread_dep = dependency('threads')

if get_option('tests')
	subdir('tests')
endif

spdlog_dep = declare_dependency(include_directories : inc, dependencies : thread_dep)
