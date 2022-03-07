===========
Flutterwave
===========

`Flutterwave <https://flutterwave.com/>`_ is a payment service provider established in Nigeria.

Configuration
=============

.. seealso::
   - :ref:`payment_acquirers/add_new`

Credentials tab
---------------

Odoo needs your **API Credentials** to connect with your Flutterwave account, which comprise:

- **API Key**: The test or live API Key depending on the configuration of the acquirer.

You can copy your credentials from your Mollie account, and paste them in the related fields under
the **Credentials** tab.

To retrieve your API key, log into your Mollie account, go to
:menuselection:`Developers --> API keys`, and copy your Test or Live **API Key**.

.. important::
   If you are trying Flutterwave as a test, with the Test API key, change the **State** to *Test
   Mode*. We recommend doing this on a test Odoo database, rather than on your main database.

.. seealso::
   - :doc:`../payment_acquirers`
