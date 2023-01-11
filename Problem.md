# 1(a)

The initial difficulties of utilising IGMPv1 as a configuration lie within the
mechanism of its predecessors that struggle to maintain the capabilities of
features. IGMPv1 provides querying and a designated network response that is
transferred from a particular multicast route and its response is activated by a
group reply. The concurrent streams that are actively playing invoke a large waste
of resources due to imprecise IGMPv1 configurations. The infrastructure of
IGMPv1 within this specific scenario is computationally ineffective due to the
limitations of the performance while utilising this protocol. The active streams
disorient the details of the route, as IGMPv1 lacks the ability to be efficient within
this particular network environment. Complications further arise with the
company’s inability to configure the protocol properly. Within this scenario,
IGMPv1 behaves by introducing problems to the network because of the way
groups have the ability to leave in any instance. The manageability of active
groups is poorly maintained by this protocol and furthermore, IGMPv1 lacks the
essential features to support multicast groups and is fundamentally a disallowed
version of IGMP within an enterprise environment. The leave mechanism is an
underlying problem with this protocol and outlines potential complications from
utilising high bandwidth on eight channels.

# 1(b)

The drawbacks of DVMRP can reduce the efficiency of its operations. A major
hindrance of the routing protocol is that it can construct strenuous amounts of
traffic in the instance of a separate router transferring datagram units to
connected nodes. If a DVMRP is not allocated upon dense transmissions on high
bandwidth connections, its ability to be efficient is halted, thereby relying on that
particular connection. The overall scalability of DVMRP is very constrained due to
information being staggering over the shortest path tree being established via
group identification; this restrains its capacity to be a scalable protocol in its own
right. A dedicated protocol approach is the reverse-path multicast algorithm, also
known as the flood-and-prune method where DVMRP lacks the ability to avoid
local networks not contained within multicast segments. The limitation of this
approach is its capacity to flood the network. A given packet that is forwarded
over a Local Area Network is a limitation to the protocol due to the arrival of
packets being subdued by flooded links. Significantly, the thirty-two max hop
count ensures complications with its scalability where the protocol is too large of a
configuration via networks.

The user as well as the server decides the sequence number, which is in the first
frame of the packet. Within each packet, they acknowledge the sequence number
by incrementing it. This is the value of the respective ACK number. The usage of
these numbers offers the capability of detecting absent segments within the
packet. The initial frame begins with both sequence and acknowledgements
numerals with zero. This is due to the absence of communication being
acknowledged. Within the frame occurring after the first sequence, the
acknowledgement has been set and displays the success of the SYN receiving
the flag packet. The remaining frames infer the establishment of the TCP session.
Once these connections are properly established, the acknowledgment follows
each segment and finishes with a connection halt or reset. The initial state is shut
and goes into a state where it sends a packet with SYN and indicates the
sequence number. The received state shows the TCP packet with its
corresponding segments and usually after the third packet has occurred, the
transfer of data is carried. The frame before the handshake is stopped involves
the acknowledgment being sent and an impact on the server occurs.

# 2(a)

Selecting AH and ESP on packets is determined by multiple facets that support
the usefulness of opting for both protocols. AH succinctly delivers authentication
for the entirety of the packet and the IP header while the authentication of the
data payload only lies within the capacity of the ESP.

An AH can detect modification of the IP header within transit, whilst ESP cannot emulate that action. It is vital to retain both protocols, as one's usage benefits certain aspects while
the other cannot operate within those means. The level of security provided for
AH and ESP allows them to ascertain different secure authentication levels. Due
to the increased complexity of an ESP's authentication process, its security is
more robust as it encapsulates both elements of data integrity and secrecy. The
combination of both protocols enables a more robust level of security; this ties in
with the enabled usage of confidentiality and authentication for a single packet to
maximise efficiency. This allows protocols to operate synchronously, whereby the
ESP is significantly used for authentication and AH for IP header authentication.
When both protocols are operated within tunnel mode, refer to fig 1.1, they
inexplicably ensure both authenticity and confidentiality via transportation. AH is
particularly important for the delivery of data as the IP header is not covered
entirely by the authentication of the ESP. While the AH cannot retain essential
confidentiality and encryption, ESP is fundamental for providing data
confidentiality and an altered coverage of authentication.

# 2(b)

The combination of SSL and IPsec is necessary to develop the usage of
encrypted HTTP traffic. The internet is a significantly exposed network with
underlying security infrastructures. This hindered framework requires IPsec as an
additional barrier of secure authentication. SSL contains standard encryption
utilised to protect applications within the system. The essential usage of both
security methods increases the overall encryption over the transport and network
layer. The constraints of utilising both involve performance problems in
conjunction with cost. This barrier creates complications with the potential
exposure of assets and the detonation of confidentiality when transferring data
between networks or the possession of data. The factors of cost do not outweigh
the vulnerability of a system that can cause damage to financial assets, thus
IPsec offers a level of security that enables stronger encryption of data. IPsec
offers the ability to operate secure services in tunnel mode, whereby the flow of
traffic is securely encrypted to the IP layer, whilst the singular use of SSL is
neutral within the third and fourth layers of the network. IPsec combines both
symmetric and asymmetric encryption to deliver enhanced security while
maintaining speed provide security while keeping speed. Symmetric encryption
applied by SSL offers a shared single key between users, whereas asymmetric
encryption is authenticated with public and private keys. The extra encryption is
an expensive addition to security, however, is a scalable solution that is
significantly vital to protect sensitive information and to initialise secure
connections within networks. The implementation of IPsec above the widely
utilised standard SSL authentication is necessary for enterprises that prioritise
encrypted connections and are retentive about security and data integrity. The
operation of IPsec at the network layer is imperative for encrypting data between
two processes and lowers the likely outcome of an exposed network and relays
information in a secure way.
