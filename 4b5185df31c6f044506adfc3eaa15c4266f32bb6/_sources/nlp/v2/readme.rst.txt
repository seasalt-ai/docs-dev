.. _nlp_readme_v2:

=======================
SeaWord NLP v2 Overview
=======================

.. contents:: Table of Contents
    :local:
    :depth: 3

The purpose of this tutorial is to demonstrate how the SeaWord APIs can be used to extract information from text. In this tutorial we will walk-through the use of the unified NLP API to generate the following insights from a meeting transcript:
    - Summarization of individual utterances and entire meetings
    - Salient topic
    - Action items
    - Emotion and sentiment

| These APIs are protected by an access token. Please send an email to info@seasalt.ai to get yours!
| For these endpoints, please use ``access_token={token}`` either in the request webhook or the request header.

Unified NLP API
=================

We have unified all of our meeting analytic services into a single API:

:ref:`NLP API Tutorial ---> <nlp_api_v2>`

Cross Lingual NER API
=====================

The Cross Lingual NER API uses one model to extract 30+ common entities from over 100 languages.

Nothing changed - see v1 docs.

:ref:`Cross Lingual NER Tutorial ---> <xlingualNER_tutorial>`

Machine Reading API
===================

The Machine Reading API performs extractive machine reading to answer questions given a context text.

Nothing changed - see v1 docs.

:ref:`Machine Reading Tutorial ---> <mr_tutorial>`

Redaction Service
===================

The Redaction Service performs personally identifiable and sensitive information classification and redaction given a context text.

Nothing changed - see v1 docs.

:ref:`Redaction Tutorial ---> <redaction_tutorial>`