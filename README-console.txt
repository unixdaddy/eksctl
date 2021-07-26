

eks-role role with attachedf policy - AmazonEKSClusterPolicy <-- used when creating the cluster 
eks-nodepolicy role with attached policies - AmazonEKSWorkerNodePolicy, AmazonEC2ContainerRegistryReadOnly, AmazonEKS_CNI_Policya <-- used when creating the node pole (after cluster creation on configuration tab --> compute (add node group)
https://docs.aws.amazon.com/eks/latest/userguide/create-kubeconfig.html <-- note manual
https://github.com/aws/amazon-vpc-cni-k8s/issues/1278
create a keypair
