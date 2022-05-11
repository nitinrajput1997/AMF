# AMF

 It is a control plane function in a 5G core network. AMF's main function is as follows
 Registration Management 
	   When the device is turned on, the device has to try to connect to the network, and then due-process it has to verify and validate that it is connecting to a genuine network that is intended to connect. Similarly, the network has to validate the device has the right privilege and credentials to connect to the network and access 5G services. This is handled by registration management.
It refers to the collection of different principles that supports the device registration or deregistration with the network and when the registration is successful, registration management establishes the user context.
User Context is the combination where the core network understands the identity of devices, and the identity of subscriptions and establishes the necessary encryption parameters for further communication between devices and the core network.
There are two states in registration management as follows:-
Registered
Deregistered

Initial when the device is powered on, it is in the de-registered state. And when the registration procedure is accepted, then it enters the registered state. When the device is in a registered state it still has to perform a registration update once in a while. Now the registration update happens on a few different occasions as follows:-
Periodically
Mobility
Update Capabilities
In some cases, registration acceptance is not successful and if it is detected, then the device goes back to de-registered. 
Finally, when the registration is successful then it means the core network knows what is the identity of the device that's trying to communicate with the network, what are the capabilities of that device and what services it wants to access.
And it also establishes the encryption parameters that both the device and the core network use to communicate with each and that makes the registration successful.
