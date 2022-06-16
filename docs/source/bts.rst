Behind the Scenes
=================

.. autosummary::
   :toctree: generated

   lumache

Data Storage
------------
Doubloons2 uses **MongoDB** to store data efficiently. The bot communicates with MongoDB using the `pymongo` python
package. It also makes use of the "Charts"-feature of MongoDB to generate some wacky looking charts. The charts can
be found over `here <https://charts.mongodb.com/charts-project-0-iravi>`_.

Doubloons2 clones the cloud database every 60 seconds. All transactions are stored in the cloned database. So every 60
seconds, the bot will push changes to the original database.

