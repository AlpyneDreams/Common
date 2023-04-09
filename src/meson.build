fs = import('fs')

common_args = windows ? [] : [
    '-Wno-shadow',
    '-Wno-volatile' # for GLM
]

common_src = files(
    'console/ConsoleCommands.cpp',
)

common_deps = [
    fmt_dep,
    glm_dep,
]

'''
common = executable('common', common_src,
    dependencies    : common_deps,
    win_subsystem   : 'console',
    cpp_args        : common_args,
)
'''
