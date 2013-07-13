#!/usr/bin/python
Import('env')
VariantDir('build','src',duplicate=0)
dst = env.PDF('build/Recipies.tex')
inst = env.Install('dist',dst)
env.NoClean(inst)
Alias('recipies',dst)
