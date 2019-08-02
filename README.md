# metrics-server
metrics-server
```
# kubectl top node 
NAME   CPU(cores)   CPU%   MEMORY(bytes)   MEMORY%   
k8s1   262m         6%     1333Mi          8%        
k8s2   203m         5%     1384Mi          8%        
k8s3   206m         5%     1269Mi          8%        
k8s4   232m         5%     9017Mi          56%       
k8s5   260m         6%     10104Mi         31%       
k8s6   143m         3%     10903Mi         34%  
```
-----
```
kubectl top pod -n logging  
NAME               CPU(cores)   MEMORY(bytes)   
es-cluster-1       19m          1031Mi          
es-cluster-2       24m          1053Mi          
fluentd-es-9tcfz   3m           90Mi            
fluentd-es-b5252   2m           88Mi            
fluentd-es-v89xc   2m           87Mi            
fluentd-es-wlf2q   4m           90Mi
```
