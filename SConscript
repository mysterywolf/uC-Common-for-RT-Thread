Import('rtconfig')
from building import *

cwd = GetCurrentDir()
src	= Glob('*.c')

CPPPATH = [cwd]

group = DefineGroup('uC-Common', src, depend = ['PKG_USING_UC_COMMON'], CPPPATH = CPPPATH)

Return('group')
