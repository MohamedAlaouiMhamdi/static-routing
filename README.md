# static-routing
Static routing is a type of routing in which network administrators manually configure the network routes on a router, rather than relying on a routing protocol to dynamically learn and distribute the routes.
With static routing, the network administrator manually specifies the next-hop router or the exit interface for each destination network.
Static routing can be useful in small networks with a simple network topology, where the network administrator has a good understanding of the network and its traffic patterns.
Static routing is also commonly used for default routes, where all traffic that is not explicitly matched by a more specific route is sent to a default gateway.
The main advantage of static routing is that it is simple to configure and does not require any overhead from routing protocols. 
Static routes can also be used to override routing decisions made by a routing protocol, allowing the network administrator to have more control over the network.
However, static routing has several limitations. One of the main limitations is that it does not provide any automatic failover in case of a link or router failure. 
If a static route points to a next-hop router that is unreachable, traffic will not be able to reach its destination. Additionally, static routing does not scale well in large networks with complex topologies,
as it can become difficult to manually configure and maintain all of the necessary routes.
In summary, static routing can be a useful tool for simple networks or specific routing scenarios, but dynamic routing protocols are typically preferred for larger networks and more complex topologies due to their scalability and ability to automatically adapt to changes in the network.
