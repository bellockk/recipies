env = Environment()
env.Append(PDFLATEXFLAGS=['-halt-on-error', '-shell-escape'])
SConscript('src/SConscript', variant_dir='build', duplicate=1,
           exports=['env'])
