import os
path = ['/nfs/msdev/texlive/2013/bin/x86_64-linux',
        '/bin',
        '/usr/bin',
        '/opt/bin',
        '/usr/local/bin']
env = Environment(ENV={'PATH':path})
SConscript('SConscript', exports = ['env'])
