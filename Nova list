#Basic script to map the instances with host . 


#!/bin/bash

for i in $(nova list | awk '{print $2}')
do
nova show $i | egrep "description|hostId"
done
