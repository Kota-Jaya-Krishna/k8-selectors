## selectors

taint node

kubectl taint nodes ip-192-168-15-246.ec2.internal hardware=gpu:NoSchedule

untaint node

kubectl taint nodes node1 key1=value1:NoSchedule-