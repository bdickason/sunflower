sunflower
=========

We aim to empower everyday people to cut out the carriers via a distributed mesh network that connects directly to backbone providers, distributing the cost of bandwidth across the entire network.

# Why?

Carriers are charging huge monthly fees and intent on controlling and throttling the internet, ultimately creating a service you don't want. We believe that by distributing the transportation of bandwidth, we can bring costs down dramatically until they approach free.

The internet is a fundamental right/utility that all humans should control. Because of regulation and legislation, carriers have exclusivity in most residential and business areas, making them hard to displace. As more of day-to-day life moves online, carriers will increasingly attempt to monetize and constrict control of their pipes.

You should be able to access broadband connectivity on your terms, not theirs.


# How?

## The Device - Sunflower

We will design and help distribute a device that allows users to easily build and extend mesh networks in their homes, offices, and anywhere else they want connectivity. The device will connect to your existing wifi network and should be placed near a window to receive a clear signal to the rest of the mesh network.

![Sunflower device sketch](http://cl.ly/image/3b2d2J0z2A1O/sunflower%20sketch.jpg)

## Nodes/Routing

Everyone becomes a 'mini-carrier' connected together via a wireless mesh network.  As the nodes in the network grow more numerous and dense, the network grows more powerful. We are looking into the [OpenGarden](https://opengarden.com/) protocol as a base for mesh networking.

## Scale

Samll neighborhoods and other loosely connected groups will buy/build devices to join and extend the network. We hope to start with neighborhoods that are near backbone providers to avoid paying money to entrenched carriers. 

## Bandwidth Usage

Over time, as the network strengthens, we hope to mitigate bandwidth waste by implementing a bittorrent-like cdn system to avoid senidng unnecessary traffic outside of the network to backbone providers. The device could have a small storage unit embedded into it to facilitate caching, or the users' computers could have a small amount of storage allocated regularly to store parts of files and other heavy objects.

We could also see Netflix or other high bandwidth-consuming services placing peering machines at points within the network to avoid paying carriers to carry their content.

## Costs

Initially, users will pay backbone providers for bandwidth to immediately connected nodes. At first, these 'last-mile' nodes will most likely have to be installed and maintained by us, but we hope that eventually backbone providers or users will purchase and install them to boost the strength of their network. 

## Security

The device will be security agnostic but support encrypted transport if requested by the user or the user's application.  In the case where we are using our bittorrent-style CDN to cache private (secure) content, we will need software similar to Tor to mask the content, entry point, and destination.

## Network effects

Aside from the obvious network effect of the network growing stronger as it becomes more dense, we suspect that small groups of citizens will band together to improve the density and quality of the network in their vicinity if we make the geographic distribution, density, and quality of connection publicly available. If your network just needs 2-3 additional nodes to reach a backbone provider, that would be a strong incentive to go recruit other users in the area who fall into that path.

## Licensing

All software will be available for free and open source and we will do our best to offer the service as close to free as possible.

All hardware will be available both for sale and all designs will be available for free via the internet so anyone can download, modify, 3D print, or manufacture them.


# How will we launch it?

With absolute transparency, we hope to start a funding campaign in a few small neighborhoods that are close to backbone providers or other independent service providers. We will ask users to pay for the bandwidth with the promise that costs will become dramatically lower over time.

I believe we can offer a clear value proposition which takes into account how much bandwidth we need in an area to mimic a dialup connection, cable modem, etc. Makers and early prototypers can help spread the devices resulting in a low upfront cost to manufacture them.

I'm currently building a small prototype with an arduino system to test how the network scales and performs within a neighborhood. I will ask a few of my neighbors to share their internet connection and experiment with different ranges and forms of wireless technology.


# FAQ

## Will the mesh network actually grow stronger with more nodes and not just become slower?

In theory, but we need a prototype to verify this.

## Will anyone actually use a mesh network?

There are numerous mesh networks currently operating today. [The Red Hook Initiative](http://rhicenter.org/redhookwifi/) (in Brooklyn) came about when the area was battered by a hurricane. Seattle has [Hyperboria](http://tkbr.ccsp.sfu.ca/pub802/2014/01/dakrnet-the-slow-internet-movement/) which contains hundreds of active nodes that are not connected to the internet.

## Why are you just rolling it out in neighborhoods near broadband? Will this even work?

Carriers in Dallas rolled out DSL this way - with a zip code system calculating how close they your home was to their central office.



# [Helpful Links](helpful_links.md)
