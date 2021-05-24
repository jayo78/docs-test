************************
Introduction to Graphene
************************

Towards programmable anonymity networks

Anonymity systems are critical in achieving free, open communication on today's Internet. In particular, Tor, a popular peer-to-peer anonymous system, has become a staple in resisting online censorship by rogue nations and allowing journalists to safely communicate with sources world-wide. However, it is surprisingly difficult to create a robust, efficient service that runs on top of a system like Tor. Today, the use of Tor is largely relegated to web proxies and hidden services, and unfortunately, neither of these applications have the ability to scale to handle dynamic workloads or attacks by automated bots. Conversely, in the "non-anonymous" Internet, services are thriving like never before due to innovations in software-defined networking (SDN), network function virtualization (NFV), and content delivery networks (CDNs). The present and future Internet is comprised of programmable networks, but there do not exist the basic primitives to achieve such features in anonymous networks.
Bento

We present programmable anonymity networks—extensions of Tor - Bento that allow users to install and run small snippets of code on Tor routers—and are using them to build more sophisticated, more secure anonymous services.

Bento, allows users to write functions and upload them to willing Tor relays. The architecture protects relays from the functions they are running on behalf of other users, and protects the users from the relays running their functions. We also present a myriad of functions that demonstrate that a programmable Tor can be a more secure, robust, and anonymous Tor.
This website serves as the tutorial & documentation for working with Bento. 

Building and running Graphene
=============================

See :doc:`quickstart` for instructions how to quickly run Bento.

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
