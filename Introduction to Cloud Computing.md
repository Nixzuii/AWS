# History of AWS

In the early 2000s, Amazon was an online store where people bought books and other goods. As more customers arrived, Amazon’s IT team had to keep adding servers, storage, and computing power to keep the site running smoothly. Along the way, they built standard tools and processes that made this work faster and easier to scale.

These methods worked so well that in 2003 Amazon realized other companies might need them too. The idea was to let businesses rent computing power, storage, and other resources on demand, with no big upfront spending on hardware. In November 2004, AWS launched its first public service, Amazon Simple Queue Service (SQS). Two years later came Simple Storage Service (S3) for storing data and Elastic Compute Cloud (EC2) for scalable computing.

At first, AWS was mostly used by startups and individual developers. Its scalability, low cost, and ease of use soon drew in larger companies too. Over the years, AWS added databases, networking, analytics, and many other services. Today it powers a large part of the internet and serves millions of customers, from small startups to big corporations and government agencies. What began as a way to solve Amazon’s own IT problems became a global leader in cloud computing. With that background, here’s a simple definition of cloud computing.

**Cloud computing is the on-demand delivery of IT resources over the internet with pay-as-you-go pricing.**

<img width="1680" height="775" alt="image" src="https://github.com/user-attachments/assets/5c3f0256-a42f-4a90-a006-865e2a4152c2" />

- **On demand** means you use only what you need. For example, if your business needs 2,000 TB of storage, you can create an AWS account, upload your files to Amazon S3, and get started. When you no longer need those files, delete them and stop paying right away.
- **Over the internet** means you can reach your resources from anywhere, whether at home, at the office, or traveling. All you need is an internet connection and a web browser to log in and manage your infrastructure.
- **Pay-as-you-go** means that if you no longer need part of your setup, you can shut it down and stop paying for it.

To see why this matters, consider what any application needs: somewhere to run, store content, and analyze data. All of this lives in a data center, a building (or group of buildings) full of servers, built with backup power, cooling, and security to keep things running safely around the clock.

Before AWS, businesses had only two options: run their own data centers or rent space in a shared facility. With AWS, companies can run applications in data centers they don’t own or manage. That means less time spent on repetitive maintenance and more time spent on innovation.

## Cloud deployment types

We can an deploy cloud resources in multiple ways: cloud, on-premises, and hybrid. Each type offers unique benefits and considerations, and exploring these options can help us make informed decisions about our cloud strategy.

- **Cloud Based Deployment**: In a cloud-based deployment model, we have the flexibility to migrate our existing resources to the cloud, design and build new applications within the cloud environment, or use a combination of both. For instance, a company might migrate data resources to the cloud, then develop an application comprised of virtual servers, databases, and networking components entirely hosted in the cloud.
- **On-premises**: Deploying resources on premises using virtualization and resource management tools does not provide many of the benefits of cloud computing. However, it is sometimes sought for its ability to provide dedicated resources and low latency. In most cases this deployment model is the same as legacy IT infrastructure while using application management and virtualization technologies to try increasing resource utilization.
- **Hybrid**: In a hybrid deployment, cloud-based resources and on-premises infrastructure work together. This approach is ideal for situations where legacy applications must remain on premises due to maintenance preferences or regulatory requirements. For instance, a company might choose to retain certain regulated legacy applications on-premises while using cloud services for advanced data processing and analytics. Multi-cloud deployments can also be considered hybrid deployments.
