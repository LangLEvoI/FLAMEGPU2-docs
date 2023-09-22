User Guide
==========

This user guide provides a clear introduction to the core features of FLAME GPU 2, by the end of the user guide you should have the skills necessary to implement a multi-agent simulation using FLAME GPU 2.

.. mermaid::

   sequenceDiagram
      participant Alice
      participant Bob
      Alice->John: Hello John, how are you?
      loop Healthcheck
          John->John: Fight against hypochondria
      end
      Note right of John: Rational thoughts <br/>prevail...
      John-->Alice: Great!
      John->Bob: How about you?
      Bob-->John: Jolly good!

.. toctree::
   :maxdepth: 1   
   :caption: Chapters:
   
   creating-a-model/index.rst
   environment/index.rst
   defining-agents/index.rst
   defining-messages-communication/index.rst
   agent-functions/index.rst
   host-functions/index.rst
   defining-execution-order/index.rst
   running-a-simulation/index.rst
   running-multiple-simulations/index.rst
   visualisation/index.rst
   debugging-models/index.rst
   performance-troubleshooting/index.rst
   flamegpu2-source/index.rst
   telemetry/index.rst