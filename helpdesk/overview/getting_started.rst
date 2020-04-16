===============
Getting Started
===============

Helpdesk teams provide your customers with support to queries or errors they might encounter while
using your product/service. Therefore, a successful scheme where you can organize multiple teams
with their customized pipeline and visibilities settings, along with the ability to track and manage
tickets in a centralized way, is essential.

Set up teams
============

| To modify or create teams, go to :menuselection:`Helpdesk --> Configuration --> Helpdesk Teams`.
| Setting up multiple teams allows you to group tickets by your channels (example: BE/US), or by
  your different types of support services (example: IT, accounting, admin, etc.).

.. image:: media/helpdesk_teams_view.png
   :align: center
   :alt: View of the helpdesk teams page in Odoo Helpdesk

Team’s productivity and visibility
----------------------------------

| Teams can have individual *Assignment Methods* to ensure tickets get redirected to the right
  person:

- *Manually*: tickets are manually assigned allowing employees to manage their own workload and
  target tickets they are experts at;
- *Random*: tickets are randomly assigned and everyone gets the same amount. This method ensures
  that all tickets are handled as the assignment happens automatically;
- *Balanced*: tickets are assigned to the person with the least amount of tickets so that everyone
  fairly gets the same amount. Thereby, you ensure that all tickets get to be taken care of, as
  the assignment is automatic.

.. image:: media/productivity_visibility.png
   :align: center
   :alt: View of a helpdesk team settings page emphasizing the productivity and visibility features
         in Odoo Helpdesk

| For the *Random* and *Balanced* assignment methods, you are able to set the *Team Members* among
  whom tickets are assigned. Leave the field empty to include all employees (with the proper
  access rights).
| The *Team Visibility* feature allows you to specify who can see and access the team’s tickets.
  Therefore, ticket’s with sensible information, for example, are only seen by the right people.
  Leave the field empty to include all employees (with the proper access rights).

Set up stages and share it among teams
======================================

Go to :menuselection:`Helpdesk --> Configuration --> Stages`. Create and/or edit stages as you need,
and set specific teams to use certain stages under *Team*.

.. image:: media/stages_teams.png
   :align: center
   :alt: View of a stage’s setting page emphasizing the option to add teams in Odoo Helpdesk

Stages can be shared between one or multiple teams, allowing you to adapt the pipeline to your
individual needs. They also apply a visibility and access rule, as other teams are not able to see
or use the stage.

.. image:: media/helpdesk_kanbanview.png
   :align: center
   :alt: View of a team’s kanban view in Odoo Helpdesk

.. seealso::
   - :doc:`../../general/odoo_basics/add_user`

