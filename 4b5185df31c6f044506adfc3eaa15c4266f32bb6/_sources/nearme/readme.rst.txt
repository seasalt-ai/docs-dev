.. _nearme_readme:

====================
NearMe 
====================

.. contents:: Table of Contents
    :local:
    :depth: 3

NearMe Product Overview
====================

NearMe Messaging is a product that aims to make conversational AI accessible to small business owners.
It is built with a deep integration with `Google Business Messages <https://businessmessages.google/>`_ and `Google Business Profile <https://www.google.com/business/>`_, 
which allows us to generate a bot based on existing business information and make it accessible to customers via Google Maps.

After logging into the NearMe site with their Google Account, users are shown a list of their business listings on GBP.
For each one, they can create a new bot.

.. image:: images/nearme_locations.png
   :width: 600

Once they start the bot generation process, it will grab all the business information from GBP and use that data to create a new bot from a template.

.. image:: images/nearme_profile.png
   :width: 600

After the initial version of the bot is generated, the business owner can add custom FAQs and additional data to the knowledge base to improve the bot's answers.

.. image:: images/nearme_faq.png
   :width: 600

The business owner can test the bot locally and then deploy it publicly to Google Maps.

.. image:: images/nearme_launch.png
   :width: 600

Once deployed, they can check customer conversations and even join the conversation.
They also have access to analytics that track user interactions.

.. image:: images/nearme_conversation.png
   :width: 600


NearMe Bots 
===========

:ref:`Bot Architecture ---> <nearme_bot_architecture>`

:ref:`Bot Generation ---> <nearme_bot_generation>`

:ref:`Message Routing ---> <nearme_bot_message_routing>`

:ref:`Conversation Analytics ---> <nearme_bot_analytics>`


Data Analytics with Google Data Studio
=================

:ref:`Data Studio Analytics Tutorial ---> <data_analytics_tutorial>`