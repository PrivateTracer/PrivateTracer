# PrivateTracer (Still figuring out under what open source license the code should be published)

From global intelligent lockdown to a global intelligent opening. We must all do this together.

The goal is to enable citizens to track who they have been in contact with, and then to receive notifications when contacts are later diagnosed as infected. This breaks the chain of transmission - thus empowering them to take appropriate actions. And to do this while preserving privacy. 

Context
Tracking of connections between citizens in the context of tracking the spread of infections is a critical tool as societies adapt to the impact of Covid 19. This applies both during the suppression phase where large parts of society are shut down to reduce social connections which while reducing interactions does not fully eliminate them, but even more so as society ramps back up after it is clear that the peak of virus infections has been sufficiently flattened.
Information is key - both at the micro scale to understand who has interacted with who, as well as at the macro scale whereby trends and social patterns as well as hot spots can be identified. The data is available, or readily obtainable with additional measures - but as has been repeatedly shown from history measures implemented in a crisis often remain long term.
In responding to the crisis many of the options are framed as balancing the economic impact with the health impact for society - but there critically needs to be a third angle to the discussion: privacy. The challenge for us is how to enable the citizens in our society to effectively respond to the crisis, supporting the government and stimulate citizen empowerment both in terms of actions and information while also retaining protection on the data that is shared and how it is used. 

Our Dream: Empower the citizens in their dealing with the spread of the virus, re-invigorating our democratic societies. This would be a victory not only against the coronavirus, but against all future epidemics and crises that might assail humankind in the 21st century. 

Our Nightmare: the measures we put in place erode further privacy in society, ultimately leading to totalitarian surveillance type of society. Citizens lose their freedom and privacy. 

Tracking the spread of the virus
The ability to know who an infected person has interacted with is key to being able to minimise the further spread of the virus. The visual below, from epidemiologist Marcel Salathé, explains this proven approach: 

The current approaches to tracking connections break down into two main areas:, PrivateTracer believes in the interaction tracking approach as the way to go. 
Location Tracking: in particular the GPS data from mobile phones is already being used in many countries, and is being considered much more widely e.g. across europe. This data is certainly useful for macro analysis, but we would argue is not the best way to track actual interactions as it is a proxy for the interaction e.g. what if someone walks by 1 second earlier or if the location data does not have sufficient resolution.

Interaction tracking: whereby on a local scale and in near real time a record is captured of nearby persons. The set of data is richer than simple location data, and more accurate.
In both situations above the smartphone, now ubiquitous in society, is being used as a proxy for individuals. 

Solution 
The chosen approach has the following key aspects
Interaction Tracking: the solution focuses on local interactions. Location data can also be captured but would only be shared on an opt-in basis and would then be anonymized
Private storage of data: all data captured is stored securely on peoples mobile phones and not on a central server.

Notifications: devices would access public data sources to receive notifications as to the health status of the owners of devices they have had interactions with (so pull based). The public data would only be correlatable and usable using the data on the users own device. 

Graded: the warning level shared for each individual user would be graded, taking into account the risk profile of those they have interacted with as well as the users own profile. 

Open source: all code created from the solution would be open source, thereby helping to build a wider community to develop the approach further and make it accessible to every country.

For interaction tracking, the target approach is to leverage Bluetooth to detect and record devices close by. This approach has already been proven to work via the TraceTogether application currently deployed in Singapore. Once they will go opensource we will review their code and post it here. 

For the storage of interactions, this would be done in a secure repository on the device. The information that is exchanged in an interaction would leverage recent advances in Self Sovereign Identity to generate a unique set of data for each interaction, so that interactions could not be later correlated without the explicit consent of the user. 

For the notifications, when a user is informed that the risk of them having the virus has increased, this will trigger the publishing of a set of data to publicly accessible sources. This data can then be used by other users to unlock additional information related to those interactions on their own device. This empowers citizens to give consent and have ownership over their own data, because we focus on keeping the data on the edge of the network. 

The user remains at all times in full control of their data, and they can on a granular basis choose to share elements of their data to support wider efforts e.g. macro scale analysis, their name to people they have interacted with. 

The above approach we believe, because we focus on citizen empowerment driven by technology designed with privacy and data sovereignty in mind. We do this by using a distributed identity privacy protocol and stimulating governments worldwide to strengthen their relationship with their citizens. 




