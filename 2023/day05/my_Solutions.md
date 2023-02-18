```Task 1```

#!/usr/bin/bash  


echo "you have asked for $1, $2, $3"  

for (( i=$2 ; i<=$3 ; i++ ));  
do  
             mkdir $1$i  
    done  
