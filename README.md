# High Performance Computing

ThoughtRender provides image and video processing services to many industries -- marketing and advertising, retail, medical, and media and entertainment. You know those furniture magazines you love to look at? Most of the pictures in these magazines are generated by the HPC compute clusters at ThoughtRender. Their unique ability to tie together industry solutions into a reliable service for their customers (e.g., furniture magazine designers! 3D animated movie makers!), together with their in-house knowledge on image and video, is a quality service that sets them apart from competitors.

They currently operate their own, on-premises services (with their own on-premises HPC clusters, and other IT infrastructure), but their success has led to challenges in terms of their growth, and ability to scale to new jobs, and new industries. They are curious about cloud and think that not only could it help them scale, but help them improve costs and pass savings to customers, address the seasonality of rendering demand (by only paying for resources when actually used) and to take advantage of new technologies, such as the latest GPUs.

They believe that bursting jobs to the cloud could help them deliver bigger jobs, or regular jobs quicker for their customers (e.g., in 1 day, instead of 5 days). They intend to pilot a solution to address this.

## Target audience

- Cloud Architects
- Developers
- HPC Engineers

## Abstract

### Workshop

In this workshop, you will setup and configure a scale-out media processing architecture using Azure Batch. You'll discover how to use High Performance Computing (scale out compute, embarrassingly parallel processing) techniques without having to write a lot of code, and learn how these tasks can be accomplished declaratively.

At the end of this workshop, you will have a deeper understanding of how to use the core capabilities of Azure Batch, understand how to author Custom Pool and Job templates, work with Job input and output files, author Batch auto-scale formulas, leverage Batch Explorer and the Azure Portal for management and monitoring, and use Marketplace applications to simplify common big compute tasks, such as 3D rendering.

### Whiteboard design session

In this whiteboard design session, you will work with a group to design a scale-out media processing solution using High Performance Computing (HPC) techniques in Azure.

At the end of this session, you will be better able to design and recommend High Performance Computing solutions that are highly scalable, and can be configured through declarative means as opposed to large amounts of complicated application code. You will also learn how to effectively manage and monitor these solutions to ensure predictable outcomes.

### Hands-on lab

In this hands-on lab, you will implement High Performance Computing (HPC) workloads targeted at 3D rendering and media processing in Azure using Azure Batch and Azure Storage.

At the end of this hands-on lab, you will be better able to deploy Azure Batch and an Azure Batch Pool consisting of Linux Virtual Machines. You will be able to configure the pool of VMs to run the FFmpeg app to process videos across the VM nodes in the pool. You will be able to do this using Batch templates and files, which enable you to perform scale-out execution of command line executables (in this case FFmpeg) without having to write any code.

## Azure services and related products

- Azure Batch
- Azure Batch Explorer
- Virtual Machines
- Azure Storage
- Azure Storage Explorer
- Import/Export Service

## Related references

- [MCW](https://microsoftcloudworkshop.com)
