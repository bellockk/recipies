#!/usr/bin/python
Import('env')
VariantDir('build','code',duplicate=0)
dst = env.PDF('build/Recipies.tex')
inst = env.Install('doc',dst)
Default(inst)