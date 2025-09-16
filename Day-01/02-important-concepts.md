# Vocabulary in Cloud Computing

## Virtualization

Virtualization means creating a fake (virtual) version of something that usually exists physically — like a computer, storage, or network.

Instead of buying 10 separate computers (hardware), we can create 10 virtual computers inside one real computer using software.

  ## Why is it Useful?

Saves money (no need to buy extra machines)

Easier to manage and scale

Great for testing, development, and cloud computing

## Virtual Machine

A Virtual Machine (VM) is software that acts like a real computer, so you can run other operating systems inside your existing one.

## API (Application Programming Interface)

API (Application Programming Interface) is a set of rules that allows two software programs to talk to each other and share information.

## Regions

In cloud computing, a Region means a geographic area (like India, US, UK) where cloud companies (like AWS, Azure, GCP) have data centers.

Each Region will have multiple data centers (called Availability Zones).

You can choose a Region closest to your users to get better speed and performance.

## ✅ Example:

Azure "Central India" Region → Data centers located in Pune.

AWS "us-east-1" Region → Data centers in North Virginia, USA.

When you deploy an app or server to a cloud, you choose a Region.

## Availability Zones

An Availability Zone is:
-----------------------

A separate data center inside a Region

Has its own power, cooling, networking

Is physically isolated from other zones in the same region

But they all work together to keep your applications running

💡 Why are AZs important?
----------------------------

If one zone fails (power outage, fire, etc.), the other zones can still run your app

This gives you high availability and fault tolerance

✅ Real-Life Example:
----------------------

You deploy your app in 2 Availability Zones in the same region.

If one zone crashes, your app still works from the other zone.


## Scalability

Scalability = System can grow or handle more users without breaking or slowing down.

💡 Example 1: Website Traffic
-------------------------------

Imagine your website has 100 visitors today.
Next week, 1,000 people visit it at the same time.

If your system can still work smoothly, without slowing down or crashing —
✅ That means your system is scalable.

## Elasticity

Elasticity means a system can automatically increase or decrease resources depending on how much you need at that time.

💻 In Cloud Computing:
------------------------
When your website has a lot of visitors, cloud adds more servers to handle the load.

When visitors reduce, cloud removes the extra servers to save cost.

This automatic adjusting is called Elasticity.

## Agility

Agility means being able to change or adapt quickly and easily.

💻 In Cloud Computing:
-----------------------
You can quickly launch new servers or apps when needed.

If requirements change, you adapt fast without delays.

## High Availability

High Availability means your system or app is always working and available most of the time — usually 99.9% or more.

💻 In Cloud Computing:
-----------------------
Systems are designed so they rarely go down.

Even if one part fails, others take over, so users don’t notice any downtime.


## Fault Tolerance

Fault Tolerance means a system can keep working without stopping, even if something breaks or goes wrong.

💻 In Cloud Computing:
-------------------------
If a server or part of the system fails, other servers take over immediately.

Users don’t notice any problem or downtime.

## Disaster Recovery

When something bad happens (like fire, flood, or a big problem with your computer or system),

You have a plan to save your important data and programs,

So you can bring everything back quickly and keep working.

💻 In Cloud Computing:
----------------------
Cloud providers help you backup your data regularly.

If something goes wrong, you can recover your applications and data fast to avoid long downtime.

## Load Balancing

Instead of sending all visitors to 1 server, visitors are sent to many servers.

This way, no server is overloaded.

Website or app works fast and smoothly.

