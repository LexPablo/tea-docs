# TL;DR

Watch the demo video before get your hands dirty...

[![](../res/start-demo-video.jpg)](http://www.youtube.com/watch?v=6GYwrITSfJo "")

# The background
![Story time](../res/demostory2.jpg)

Let’s demonstrate how Tea’s decentralised trusted computing works with the help of Alice, Bob, Charlie, and Dave.
 
![Story time](../res/blog/demo-alice.jpg)
Alice, a wildlife photographer, has recently captured some magnificent images of a lion. Hoping to earn a couple of bucks, she makes the images available for use on a research platform—while maintaining ownership of the actual pictures.

![Story time](../res/blog/demo-bob.jpg)
Bob is a hardcore developer that works on image recognition models. His most recent application is a Tensorflow image recognition model compiled to web-assembly. He would like to open up his application for use, without creating the opportunity for others to copy his code.

![Story time](../res/blog/demo-charlie.jpg)
Charlie is an IPFS miner. He’s recently added a TEA module to his device, allowing him to mine both FIL and TEA tokens with the same mining machine. He wonders how the TEA module is able to receive sensitive information from clients and run computations securely and privately.

![Story time](../res/blog/demo-dave.jpg)
Dave is a seasoned scientist. He’s currently researching wild animal behaviour by analysing images. While he cannot analyse every picture manually, he can run an AI algorithm on wildlife pictures he’s collected from photographers.

![Story time](../res/blog/demo-no-trust.jpg)
The four characters each play a different role in this story. One common thread is that to do business with each other they require a level of trust that is currently not available.

This where Tea comes in: a decentralised trusted computing platform.

![Story time](../res/blog/demo-four.jpg)

Of course, they cannot make deals by themselves; they have never even heard of each other. 

![Story time](../res/demostory4.jpg)
Alice simply uploads her pictures to the Tea platform, which returns Deployment_ids for it. Bob does the same with the code for his image recognition application.

Charlie is one of the many IPFS+TEA miners in the Tea network, bringing trusted computation services to the rest of the gang.

Dave has been running Bob’s application for a while and needs some new material to scan. He soon finds Alice’s images and purchases some for analysis.

![Story time](../res/demostory5.jpg)

For Dave the experience is as simple as paying for the task and receiving the result along with a series of Proof of Trust verifications. And, Alice, Bob, and Charlie receive their payment.

![Story time](../res/demostory6.jpg)

The execution of Dave’s task only takes place inside or between TEA nodes. A TEA node is an HSM, Hardware Secure Module, that is protected by both hardware and consensus. No one, including Charlie (a miner and TEA node owner), can access the information on the module-let alone a hacker.

Alice gets paid for her pictures, without giving away any files. Bob, Charlie, and even Dave do not own a copy of her picture.

Bob gets paid for his Tensorflow algorithm without giving Alice, Charlie and Dave a single line of code.

Charlie is clueless about any of these activities, and simply gets paid for the hardware and services. He has zero knowledge about the tasks and data.

Dave gets the output he requested, and can verify through the Proof of Trust that the result is based on the correct code/algorithm and data input.

This is one of many examples of how decentralised trusted computing with a cup of Tea works!
