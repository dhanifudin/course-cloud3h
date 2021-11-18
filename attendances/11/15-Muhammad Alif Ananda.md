WEEK #11

Five years ago, Solomon Hykes helped found a business, Docker, which sought to make containers easy to use. With the release of Docker 1.0 in June 2014, the buzz became a roar. And, over the years, it's only got louder.

All the noise is happening because companies are adopting Docker at a remarkable rate. In July 2014 at OSCon, I ran into numerous businesses that had already moved their server applications from virtual machines (VM) to containers.

Indeed, James Turnbull, then Docker's VP of services and support, told me at the conference that three of its largest beta bank customers were moving it into production. That's a heck of a confident move for any 1.0 technology, but it's almost unheard of in the safety-first financial world.

Today, Docker, and its open-source father now named Moby, is bigger than ever. According to Docker, over 3.5 million applications have been placed in containers using Docker technology and over 37 billion containerized applications have been downloaded.

It's not just Docker who thinks they're on to something big. 451 Research also sees Docker technology being wildly successful. It predicts "the application container market will explode over the next five years. Annual revenue is expected to increase by 4x, growing from $749 million in 2016 to more than $3.4 billion by 2021, representing a compound annual growth rate (CAGR) of 35 percent."

Real-world data backs up the conclusion that Docker is being widely adopted. DataDog, a cloud-monitoring system, found that by March 2016, "13.6 percent of Datadog's customers had adopted Docker. One year later that number has grown to 18.8 percent. That's almost 40 percent market-share growth in 12 months." RightScale observed in its RightScale 2018 State of the Cloud report that Docker's adoption by the industry has increased to 49 percent from 35 percent in 2017.

Docker, an open-source technology, isn't just the darling of Linux powers such as Red Hat and Canonical. Proprietary software companies such as Oracle and Microsoft have also embraced Docker. Today, almost all IT and cloud companies have adopted Docker.

Why companies embrace Docker containers

So why does everyone love containers and Docker? James Bottomley, formerly Parallels' CTO of server virtualization and a leading Linux kernel developer, explained VM hypervisors, such as Hyper-V, KVM, and Xen, all are "based on emulating virtual hardware. That means they're fat in terms of system requirements."

What is DevOps? An executive guide to agile development and IT operations
What is DevOps? An executive guide to agile development and IT operations

To make the most of today's containers, servers, virtual machines, and clouds, you need to deploy DevOps in your enterprise. Or, you can let your rivals put you out of business. It's your choice.

Read More

Containers, however, use shared operating systems. This means they are much more efficient than hypervisors in system resource terms. Instead of virtualizing hardware, containers rest on top of a single Linux instance. This means you can "leave behind the useless 99.9 percent VM junk, leaving you with a small, neat capsule containing your application," said Bottomley.

Therefore, according to Bottomley, with a perfectly tuned container system, you can have as many as four-to-six times the number of server application instances as you can using Xen or KVM VMs on the same hardware.

Another reason why containers are popular is they lend themselves to Continuous Integration/Continuous Deployment (CI/CD). This a DevOps methodology designed to encourage developers to integrate their code into a shared repository early and often, and then to deploy the code quickly and efficiently.

Docker enables developers to easily pack, ship, and run any application as a lightweight, portable, self-sufficient container, which can run virtually anywhere. As Bottomley told me, "Containers gives you instant application portability."

Containers do this by enabling developers to isolate code into a single container. This makes it easier to modify and update the program. It also lends itself, as Docker points out, for enterprises to break up big development projects among multiple smaller, Agile teams using Jenkins, an open-source CI/CD program, to automate the delivery of new software in containers.

Jay Lyman, senior analyst at 451 Research, added: "Enterprise organizations are seeking and sometimes struggling to make applications and workloads more portable and distributed in an effective, standardized, and repeatable way. Just as GitHub stimulated collaboration and innovation by making source code shareable, Docker Hub, Official Repos, and commercial support are helping enterprises answer this challenge by improving the way they package, deploy, and manage applications."

In addition, Docker containers are easy to deploy in a cloud. As Ben Lloyd Pearson wrote in Opensource.com: "Docker has been designed in a way that it can be incorporated into most DevOps applications, including Puppet, Chef, Vagrant, and Ansible, or it can be used on its own to manage development environments."

Specifically, for CI/CD Docker makes it possible to set up local development environments that are exactly like a live server; run multiple development environments from the same host with unique software, operating systems, and configurations; test projects on new or different servers; and allow anyone to work on the same project with the exact same settings, regardless of the local host environment. This enables developers to run the test suites, which are vital to CI/CD, to quickly see if a newly made change works properly.

By using CI/CD, according to a 2016 Puppet survey of 4,600 IT professionals, IT departments with a strong DevOps workflow deployed software 200 times more frequently than low-performing IT departments. Moreover, they recovered 24 times faster, and had three times lower rates of change failure. Simultaneously, these businesses are spending 50 percent less time overall addressing security issues, and 22 percent less time on unplanned work.

All this comes as no surprise that the most popular way to deliver applications via CI/CD are containers.

What's not to like? You get a lot more application bang for your server buck and you improve and deploy your software quicker than ever before. So, why hasn't anyone done it before? Well, actually they have. Containers are an old idea.