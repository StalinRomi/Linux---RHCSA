## if loop

if [$a -gt $b]
then
echo "a is greater than b"
else
echo "b is greater than a"  
fi

## for loop

read Path_to_Fix

for i in $(find $Path_to_Fix -type d -not -perm 755)
do
echo 'Fixing $i'
chmod 755 $i

### (Above for loop fixes permissions of all the files inside the mentioned directory)

## test

if test $a -gt $b
(same as if loop)
