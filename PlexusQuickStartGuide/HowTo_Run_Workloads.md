1.	Login to https://aac.amd.com/.
 
![image](https://github.com/amddcgpuce/AMDAcceleratorCloudGuides/assets/137475255/6bd47699-5627-4c93-abd0-780851d9f27e)

2.Go to workloads, Select new workload.
 

2. Select the desired TensorFlow version with desired container type as docker
Note: In this case, we have selected TensorFlow 2-10 ROCm 5-4-1 version and container as docker.
 



3.Click on Next, available in top-right corner
 
4.  Click Next to continue 
 
5. Select Number of GPU’s as 8 and Click on Next
 
6. Select the desired queue. Click Next.
Note: Here, we selected  queue as CirraScale:1CN128C8G1H_4RoCE_MI250_Ubuntu22 (gpu:mi250:8(S:0-1))
 

7.Review workload and Click on Run Workload.
 

