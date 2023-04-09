project('common', 'cpp',
    version: 'latest',
    default_options: ['cpp_std=c++20']
)

windows    = build_machine.system() == 'windows'
linux      = build_machine.system() == 'linux'

fmt_dep    = dependency('fmt', static: true)
glm_dep    = dependency('glm', static: true)

subdir('src')
