# AMQ Streams Drain Cleaner

AMQ Streams Drain Cleaner is a utility which helps with moving the Kafka pods deployed by AMQ Streams from Kubernetes nodes which are being drained.
It is useful if you want the AMQ Streams operator to move the pods instead of Kubernetes itself.
The advantage of this approach is that the AMQ Streams operator makes sure that no Kafka topics become under-replicated during the node draining.

For more information and installation guide, see [documentation for AMQ Streams on OpenShift](https://access.redhat.com/documentation/en-us/red_hat_amq_streams/).
