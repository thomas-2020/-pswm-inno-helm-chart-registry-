# Deployment with post init action 

This example shows how to perform post init actions after the startup has been performed. Post init is mainly used to perform actions like databse upgrades or (like in this case) synchronize the Universal Messaging publishable document types (channels, queues in Universal Messaging).


## Prerequisites

This deployment depends on universal messaging. Make sure that UM is up and running before deploying this MSR example.