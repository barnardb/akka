.. _-mapResponseEntity-:

mapResponseEntity
=================

Signature
---------

.. includecode2:: /../../akka-http/src/main/scala/akka/http/scaladsl/server/directives/BasicDirectives.scala
   :snippet: mapResponseEntity

Description
-----------

The ``mapResponseEntity`` directive is used as a building block for :ref:`Custom Directives` to transform a
response entity that was generated by the inner route.

See :ref:`Response Transforming Directives` for similar directives.

Example
-------

.. includecode2:: ../../../../code/docs/http/scaladsl/server/directives/BasicDirectivesExamplesSpec.scala
   :snippet: mapResponseEntity
