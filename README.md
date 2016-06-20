patch-dartsdk-linux
===================

Actually, Dart SDK is only dynamically compiled on Ubuntu 12.04 LTS.
As a result, Dart SDK could run only on compatible Ubuntu distributions.

In order to use it on every Linux distributions, the patch consists on adding Ubuntu libraries in the regular Dart SDK.

To patch a Dart SDK (default ``latest``), launch either ``patch-dartsdk-32 [release]`` or ``patch-dartsdk-64 [release]``.
