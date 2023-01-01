cat > file name

### Standard Error 2>

./hello.sh **2>** error.txt ( To get the **Error** in the file )

### Standard Output 2>&1

./hello.sh > script.log **2>&1** ( To get **Error + Output** in the file)

### Switch Users

sudo **su -s** /bin/bash username ( -s -> shell)

Creating Home Directory for the User ->

sudo **mkhomedir_helper** username
