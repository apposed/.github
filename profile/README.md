Appose is a library for interprocess cooperation with shared memory.
The guiding principles are *simplicity* and *efficiency*.

Appose was written to enable **easy execution of Python-based deep learning
from Java without copying tensors**, but its utility extends beyond that.

The steps for using Appose are:

* Build an Environment with the dependencies you need.
* Create a Service linked to a *worker*, which runs in its own process.
* Execute scripts on the worker by launching Tasks.
* Receive status updates from the task asynchronously via callbacks.

See the repositories below for individual language implementations of Appose.
