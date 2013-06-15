#!/usr/bin/python
import os
VariantDir('build','code',duplicate=0)
env = Environment(ENV=os.environ)
dst = env.PDF('build/Recipies.tex')
inst = env.Install('doc',dst)
Default(inst)