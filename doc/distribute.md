# Distributed-Mnist

## Instructions
1. Simple Usage: 
 * for Parameter Server 0, ```python distributed_mnist.py --job_name='ps' --task_index=0```
 * for Parameter Server 1, ```python distributed_mnist.py --job_name='ps' --task_index=1```
 * for Client 0          , ```python distributed-mnist.py --job_name='worker' --task_index=0```
 * for Client 1          , ```python distributed-mnist.py --job_name='worker' --task_index=1```

 > Remember to edit flag ps_hosts/worker_hosts inside the python sript before running th program  
 > Inside the script, flag num_workers/num_parameter_servers should be consistent with length of flag ps_hosts/worker_hosts

2. Optional Arguments:
 * --ps_hosts: list of [hostname:port] for ps jobs
 * --worker_hosts: list of [hostname:port] for ps jobs
 * --num_workers: length of workers_hosts
 * --num_parameter_servers: length of ps_hosts
 * --train_steps: number of training steps to perform
 * --batch_size: training batch size

 > Also see ```python distributed_mnist.py -h``` for more info
