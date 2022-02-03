# Steal or Forge Kerberos Tickets

Adversaries may attempt to subvert Kerberos authentication by stealing or forging Kerberos tickets to enable Pass the Ticket. Kerberos is an authentication protocol widely used in modern Windows domain environments. In Kerberos environments, referred to as "realms", there are three basic participants: client, service, and Key Distribution Center (KDC). Clients request access to a service and through the exchange of Kerberos tickets, originating from KDC, they are granted access after having successfully authenticated. The KDC is responsible for both authentication and ticket granting. Attackers may attempt to abuse Kerberos by stealing tickets or forging tickets to enable unauthorized access.

[[T1558.001 - Golden Ticket]]
[[T1558.002 - Silver Ticket]]
[[T1558.003 - Kerberoasting]]
[[T1558.004 - AS-REP Roasting]]