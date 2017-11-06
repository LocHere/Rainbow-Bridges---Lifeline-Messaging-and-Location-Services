# Rainbow-Bridges: Lifeline-Messaging-and-Location-Services
A solution to provide timely and reliable messaging  and location services to the individuals in the situation of immediate aftermath of a disaster. 

# Target Problem:

It is crucial to provide timely and reliable messaging  and location services to the individuals in the situation of immediate aftermath of a disaster. This project particularly targets on the problem with the following objectives and constraints:

Objectives: (i) Individuals can use their smartphones to  send messages and their locations to first responders and whom they care; (ii)  Message receivers can understand senders' locations; (iii) Smartphone energy consumption is minimized.

Constraints: (i) No communication infrastructure available; (ii) GPS may be unavailable such as in indoor environments; (iii) Smartphones still don't support multi-hop ad-hoc mode; (iv) Smartphone rooting is not always available. 

# Proposed Solution:

The solution is based on ad-hoc networks consisted of smartphones and portable relays. Smartphones form local small-world ad-hoc networks, whose diameter is less than 5 hops, via application level implementations over WiFi Direct. Message forwarding service is enabled on smartphones. Multi-hop route discovery within adjacent small-worlds is based on unicast. Portable relays are used for cross non-adjacent small-worlds route discovery. Locations (if necessary) are translated to the ones that can be understood by their receivers during message forwarding.       

# Target Users:

Individuals and first responders are the users of this solution in the situation of the immediate aftermath of a major disaster, where infrastructure based communication and networking services are no longer available. Individuals have the needs of sending messages to seek for help, notifying first responders (and/or other individuals) their locations, and receiving messages. First responders need to know the existences of individuals, communicate with them, and physically reach them if necessary.   

The solution will provide an Off-the-Grid wireless network to connect individuals and first responders together. They can efficiently message and share locations without the need of rooting individuals' smartphones and consuming a large amount of energy. We had interviewed more 100 potential customers including firefighters, police officers, event organizers, and individuals during our NSF I-Corps training. According to their feedbacks, we design the application level small-world ad-hoc networks, the unicast-based route discovery, and the portable relays for our easy, reliable, energy efficient, and low-cost solution. The solution can also serve Off-the-Grid event participants and smart communities, where Internet services may be intentionally avoided due to the considerations of economy, security, and privacy.

# Target Enviorments:
The solution is most useful in the environments, whose scale is relatively small (building/block/community level) and whose user density is not too small (more than 3 nearby individuals for non-GPS based location service). Particularly, the solution will fit the users' needs in following environments:

1. Buildings with a large number of individuals such as apartments, shopping malls, office buildings, schools, convention centers, and museums, where individuals have the needs of contacting relatives/friends and finding exits/first responders.  

2. Residential communities, where individuals have the needs of being aware of the situations inside/outside their communities when their families are isolated due to disasters such as flooding.

3. Refugee camps and temporary shelters, where individuals need to know family members' locations and receive/send updates.

4. Events such as shows, sports, and exhibitions, where participants have the needs of finding the right persons/products and delivering messages to customers.  
