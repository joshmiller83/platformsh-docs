Install your Master site
========================

Once you've purchased a Platform package, you will be automatically redirected to your new Platform account. You can access your existing Platform accounts through your `Commerce Guys Marketplace account <https://marketplace.commerceguys.com/user>`_. Once you've logged in, click on the "Platforms" tab on your user account page. You will find a list of platform projects with links to each of them.

Install Kickstart / Drupal / Empty Git
--------------------------------------

.. figure:: /quick-start-guide/images/ui-setup.png
  :alt: Platform Setup

  The first time you access the :ref:`platform_ui`, you'll see the project setup wizard which helps you to configure your project.

Choose a name for your project (this could be the domain of the site you are working on) and then choose a starting point:

* **Commerce Kickstart**: The quickest way to get up and running with Drupal Commerce.
* **Drupal 7**: Standard Drupal 7 installation profile.
* **From scratch**: Empty Git repository. Choose this option if you are migrating an existing site.

Once you’re done, Platform will build your project and provide you a default :term:`environment` called :term:`Master`.

.. note::
   Choosing either 'Commerce Kickstart' or 'Drupal 7' will cause Platform to generate a :term:`make file` in the root of your repository. This :term:`make file` will be used to build your site.

First look at Platform
----------------------

.. figure:: /quick-start-guide/images/ui-intro.png
  :alt: Platform UI

  Once you've completed your project setup, you will be sent to your new project page. Now you can start working with Platform!

  1. **Project selection and configuration -** Switch between projects, or manage the configurations of the current project. Changing the project here will update everything below it to the current project.
  2. **Account administration, support, and documentation-** Use these quick access links to documentation resources, support options, or your current user account information.
  3. **Environment indicator, access information, and configuration-** This will tell you which environment (or branch) you are currently working in. The configuration icon and website link will apply specifically to this environment.
  4. **Git branch, synchronize, merge, and backups-** These primary actions are used for your regular development workflow for the specific environment. Read more about these actions in the :ref:`platform_ui` section.
  5. **Environment selector-** Switch between environment contexts. When you create a new branch by clicking the branch action link, those environemtns will appear here. Selecting an environment here will change everything to the right of this to that environment's context.
  6. **Environment activity stream-** Follow the latest activity for the current environment.


---------

.. image:: /quick-start-guide/images/icon-configure.png
  :alt: Configure icon
  :align: left

The **configuration icon** is a contextual link. It will direct you to the configuration settings for either the current :term:`project` or :term:`environment` that you are viewing.

--------

.. seealso::
  * :ref:`platform_ui`

Access Your Site
----------------

Each :term:`environment` has its own URL that you can access by clicking *View this website* under its name.

.. figure:: images/platform-getting-started-01.png
   :alt: Accessing an environment from the UI.

---------

.. image:: /quick-start-guide/images/icon-configure.png
  :alt: Configure icon
  :align: left

You can administer the Settings, Variables, Routes, and Users specifically for each :term:`environment` by clicking the **configuration icon** here.
