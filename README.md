只运行分布式：
python -m torch.distributed.launch --nproc_per_node 2 --master_port 8005 run.py --device_ids=0,1(2张卡)
python -m torch.distributed.launch --nproc_per_node 4 --master_port 8005 run.py --device_ids=0,1,2,3（4张卡）

[数据集](链接：https://pan.baidu.com/s/1HrbOC8nNaCFuCPEmIPWQqw 
提取码：gclo )
