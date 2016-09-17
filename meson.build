project('spdlog', 'cpp', version : '0.10.0',
		default_options : ['cpp_std=c++11'])

inc = include_directories('include')

thread_dep = dependency('threads')

# subdir('example')
subdir('tests')

run_command('mkdir', '-p', meson.build_root() + '/logs')

spdlog_dep = declare_dependency(include_directories : inc, dependencies : thread_dep)
