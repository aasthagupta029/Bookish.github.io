import os
import shutil
path=input("path name=")
files=os.listdir(path)
for file in files:
    filename,extension=os.path.splitext(file)
    extension=extension[1:]
    if os.path.exist(path+'/'+extension):
        shutil.move(path+'/'+file,path+'/'+extension+'/'+file)
    else:
        os.makedirs(path+'/'+extension)
        shutil.move(path+'/'+file,path+'/'+extension+'/'+file)
