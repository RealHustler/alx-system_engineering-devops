#shows the absolute path of the current working directory
pwd
#list files in directory
ls
#changes working directory to home directory
cd ~
#display files in long format
ls -l
#display files even hidden ones n long format
ls -la
#display
ls -lna
#create directory
mkdir /tmp/my_first_directory
#moving files
mv /tmp/betty /tmp/my_first_directory
#removing files
rm /tmp/my_first_directory/betty
#delete directory
rmdir /tmp/my_first_directory
#back
cd -
#all files
ls -al . .. /boot
#file type
file /tmp/iamafile
#symbolic link
ln -s /bin/ls _ls_
