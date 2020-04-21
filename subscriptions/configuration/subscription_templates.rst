==========================
Use subscription templates
==========================

The subscription business model is becoming more and more popular. Are you wondering why? Because a
subscription model simplifies the business process and makes it very easy for both customers and the
business. It ensures that the business retains more customers on a consistent basis and that clients
can be reached out to and engaged with regularly. A business model like this makes it easy to
anticipate demand and supply. Finally, this model offers much higher payment security for your
business.

.. raw:: html

   <div align="center" style="color:#AD5E99; font-size: 2rem ;margin: 20px 0"> <b>Simplicity.
   Higher customer retention. Opportunities for marketing. Business consistency. Better cash flow
   management.</b> </div>

Odoo subscription templates will help you save a lot of time and money. Indeed, these templates will
help you generate recurring invoices and manage renewals at a fast pace. With Odoo you have the
possibility to create, edit and manage your own subscription templates.

Configuration
=============

Go to :menuselection:`Subscriptions → Configuration → Subscription templates`. By default, Odoo
suggests you two types of subscription (MON - Monthly subscription *vs* YEA - Yearly subscription).
Of course, you can create your own ones.

.. image:: media/subscription_templates_1.png
  :align: center
  :alt: Default subscription templates on Odoo Subscriptions

.. important::
   The **Subscriptions** application automatically installs **Sales** and **Invoicing** as they work
   integrated.

Create your first template
==========================

You can create a new template or edit an existing one. The first thing you need to do is give your
template a name. After that, choose an *Invoicing period* and specify whether you would like to
invoice your customers per *Days*, *Weeks*, *Months* or *Years*. On *Duration* determine if
the subscription must go on *Forever* (until it’s manually closed) or for a *Fixed amount* of time.
Among the payment options, an additional field called *Invoice email* appears when you choose
*Send*, *Send & try to charge* or *Send after successful payment*. This field allows you to add an
invoice email template to your subscription templates.

.. image:: media/subscription_templates_2.png
  :align: center
  :alt: Create your own subscription templates on Odoo Subscriptions

For each template, you can also choose if you want your customers to be able to close their
subscriptions or not. If enabled, you can set an *Automatic closing* limit and you can specify the
*Group of subscription* and the *Journal* options.

.. note::
   On each template, you can add your **Terms and Conditions**. Specifying terms and conditions is
   essential to set out important contractual points between the customers and the sellers (payment,
   refund policy, cancellation, complaints, etc.).

   .. image:: media/subscription_templates_3.png
     :align: center
     :alt: Terms & conditions on Odoo Subscriptions

   Finally, if you want to know the basic running health status of your subscriptions, you also have
   access to a specific tab called **Health Check**. There, you can edit and create your own
   filters to define what is a subscription in good health *vs* bad health. The system will
   automatically summarize all the records corresponding to these filters and you will be able to
   manage them in one click.

   .. image:: media/subscription_templates_4.png
     :align: center
     :alt: Health check on Odoo Subscriptions

.. important::
   After creating your own subscription templates, be sure to check out our documentation on how to
   create, edit and manage your own subscription products: :doc:`subscription_products`, to complete
   the sales flow.

.. seealso::
   - :doc:`subscription_products`
