# YPP test plan

The YPP test plan document covers details of the tests we want to carry out, how we'll do them, what the steps are, who's involved and what we're aiming for. If all goes well, WPP should launch on the mainnet Gleev without delay.

## Scope

- Storage system under high load

**Out of scope**

- YPP user interface
- YPP rewards distribution
- Distribution system <->  Storage system

## Plan & Roles

It should take about two weeks for the testing to go smoothly, and the five SP nodes should take around a week to keep their nodes active. If we get going quickly, the test should wrap up by the start of March.

1. Council, SP Lead, JSG: agree on the test requirements and success criteria - Days 1-2
2. JSG: setup staging network - Days 3-4
3. Council, SP Lead: Council elected and SP Lead hired on staging network - Days 5-6
4. SP Lead: setup 5 SP servers - Days 7-8
5. BWG Lead: test scripts development -  Days 3-8
6. SP Lead, JSG: Testing - Days 9-13
7. Council, SP Lead, JSG: Results and next steps - Day 14

## **Tests**

**Simultaneous upload -1**

- Requirements
    - 1000 videos
    - 1000 channels (1 video per channel)
    - 100 MB each video
    - Simultaneous upload
- Success criteria
    - Failed uploads: <10%
    - Logs errors: no errors in the SP node logs
    - Sync: each file synced across all nodes within 30 min after upload
- Measurements
    - After 30 min after upload completion each node operator should provide to SP WG Lead (1) log file and (2) list of all objects that are currently on his hard drive
- Comment
    - Total upload is 100 GB
    - Each node will keep up with uploading 200 videos at once

**Simultaneous upload -2**

- Requirements
    - 50 videos
    - 50 channels (1 video per channel)
    - 1 GB each video
    - Simultaneous upload
- Success criteria
    - Failed uploads: <10%
    - Logs errors: no errors in the SP node logs
    - Sync: each file synced across all nodes within 30 min after upload
- Measurements
    - After 30 min after upload completion each node operator should provide to SP WG Lead (1) log file and (2) list of all objects that are currently on his hard drive
- Comment
    - Total upload is 50 GB
    - Each node will keep up with uploading 10 videos each 1 GB at once

**Simultaneous channel creation** 

- Requirements
    - Simultaneously create 1000 channels
- Measurements
    - Channels have been set up successfully - double check in GraphQL
- Success criteria
    - All 1000 channels exists

**Subsequent upload**

- Requirements
    - 100 videos
    - 500 MB each video
    - 1 channel
    - Subsequent upload
- Success criteria
    - Failed uploads: <10%
    - Logs errors: no errors in the SP node logs
    - Sync: each file synced across all nodes within 30 min after upload
- Measurements
    - After 30 min after upload completion each node operator should provide to SP WG Lead (1) log file and (2) list of all objects that are currently on his hard drive
- Comment
    - Total upload is 50 GB
    - Each node will keep up with uploading 10 videos each 1 GB at once

## Pre-requisite

- Setup staging network
    - Get the same setup as mainnet, but make the council election super speedy so the SP lead can be chosen quickly.
- Testing tools
    - Create automated tools that perform tests in line with the stated needs.
- Setup SP servers
    - Storage workers should set up a similar storage system config to what we use in the mainnet with 5 server in operation. Though config may not be exactly the same. Storage workers can use daily server rental to minimize their costs and should get servers from different hostings. Storage workers need at least 400GB of space.

> I believe it can be challenging to obtain the exact server configuration for the test network. For example, the hosting I use offers generous discounts for long-term contracts, and I have used this tariff for the mainnet. However, for a short-term test, this is not a viable option due to high one-time install payment.
Additionally, from my experience, even if you rent two identical server configurations from the same hosting provider, the performance of these two servers may still differ (I have experienced this issue multiple times in the last few months)
> 
