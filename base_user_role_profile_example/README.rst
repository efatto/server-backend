=====================
User profiles example
=====================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:c7b51eebd8235efc75de0c156d3b37b66806a04c0e9348485801b0d054157fb5
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fserver--backend-lightgray.png?logo=github
    :target: https://github.com/OCA/server-backend/tree/12.0/base_user_role_profile_example
    :alt: OCA/server-backend
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/server-backend-12-0/server-backend-12-0-base_user_role_profile_example
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/server-backend&target_branch=12.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This shows an example of base_user_role_profile in use.


**Table of contents**

.. contents::
   :local:

Configuration
=============

Nothing to configure, just check the demo user.

Usage
=====

Log in as the demo user, and observe on the upper right of the screen the widgets for profile selection and company selection.
Use the widgets to manipulate user profile and companies for dynamic permissions/roles editing.

Note: "Merchant Profile" means the user is interested in sales and purchases, and thus has access only to those menus. Note that through configuration of roles and role lines, a merchant can be a sales user AND a purchase user in one company, or just a sales user (NOT a purchase user) in another company.

Here is a walkthrough:

* Demo user starts in "YourCompany" company. Observe permissions and access to the root menus for sales and purchases.
* Switch profile to HR profile, which gives access only to HR permissions. Observe that you can create new employees.
* Switch company to "Company, The Second". Observe the menu has been reset, profile options have changed, one has been picked automatically from the available ones.
* Switch profile to "Merchant Profile". Observe that for this company, you can only access Sales, because only a Sales role line has been defined for this company and user.
* Switch profile to "ERP Settings profile". Observe that as expected you have ERP manager permissions.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/server-backend/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/server-backend/issues/new?body=module:%20base_user_role_profile_example%0Aversion:%2012.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Akretion

Contributors
~~~~~~~~~~~~

* Kevin Khao <kevin.khao@akretion.com>
* Sébastien Beau <sebastien.beau@akretion.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/server-backend <https://github.com/OCA/server-backend/tree/12.0/base_user_role_profile_example>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
