=====
Adyen
=====

`Adyen <https://www.adyen.com/>`_ is a Dutch-based company that offers several online payment
possibilities.

Configuration
=============

.. seealso::
   - :ref:`payment_acquirers/add_new`

Credentials tab
---------------

Odoo needs your **API Credentials** to connect with your Adyen account, which comprise:

- **Merchant Account**: The code of the merchant account to use with Adyen.
- :ref:`API Key <adyen/api_and_client_keys>`: The API key of the webservice user.
- :ref:`Checkout API URL <adyen/urls>`: The base URL for the Checkout API endpoints.

You can copy your credentials from your Adyen account, and paste them in the related fields under
the **Credentials** tab.

.. important::
   If you are trying Adyen as a test, with a *test account*, change the **State** to *Test Mode*. We
   recommend doing this on a test Odoo database, rather than on your main database.

.. _adyen/api_and_client_keys:

API Key and Client Key
~~~~~~~~~~~~~~~~~~~~~~

In order to retrieve the API Key and the Client Key, log into your Adyen account, go to
:menuselection:`Developers --> API Credentials`.
- If you already have an API user, open it.
- If you don't have an API user yet, click on **Create new credential**.
Go to :menuselection:`Authentication` and get or generate your **API Key** and **Client Key**. Be
careful to copy your API key as you'll not be allowed to get it later without generating a new one.

.. _adyen/urls:

URLs
~~~~

To retrieve the URLs, log into your Adyen account, go to :menuselection:`Developers --> API URLs`.
Pick one of the URLs listed next to **Recurring** as your **Recurring API URL** and one of the URLs
listed next to **Checkout API** as your **Checkout API URL**.

.. image:: media/adyen_api_urls.png
   :align: center
   :alt: Get the links for the different API.