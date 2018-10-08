# CiviCRM Developer training

=

# Hello

-   Name
-   Organisation
-   One specific thing

=


# Approach

* Six different teachers
* Tailored to your needs (inc. exercises)
* Shout if you are not feeling productive
* We are not trying to learn *everything*

=

# Flexible plan

| Day one         | Day two          |
| :-------------- | :--------------- |
| Developer tools | Hooks            |
| Extensions      | Testing          |
| API             | UI & PR workflow |

*Review after day one*

=

# Developer environment

Recommend [buildkit](https://docs.civicrm.org/dev/en/latest/tools/buildkit/) on ubuntu 16.04 / 18.04

Alternatives:
* Vagrant
* Docker

=

# Tools

Buildkit ~20 tools for CiviCRM development

The highlights:

```bash
$ civibuild  # create and destroy sites
$ cv         # administer sites
$ civix      # create extensions
```

=

# More tools

```bash
$ git       # for version control and collaboration
$ amp       # apache, mysql and php admin
$ phpunit   # for running tests
$ civilint  # esnure you are following the CiviCRM style
```

=

# Code layout

The *most important* directories...

```bash
civicrm/
  ang           # Angular files
  api/          # API
  CRM/          # PHP code
    DAO/        # Auto-generated 'data access objects'
    BAO/        # Business logic that builds on the BAO (the 'model')
    Form/       # Logic for form creation and submission (the 'controller')
    Page/       # Logic for page creation
    xml         # Metadata to generate DAOs (and some other stuff)
    ...         # More files ...
  packages/     # Packages and libraries (third party software)
  templates/CRM # template files (CRM/{Form,Page}) (the 'view')
  ...           # More files ...
```

=

# Configuration pages

Some CiviCRM settings pages:

* [Admin / Settings / Debug](https://dmaster.demo.civicrm.org/civicrm/admin/setting/debug?reset=1)
* [Admin / Settings / Path ](https://dmaster.demo.civicrm.org/civicrm/admin/setting/path?reset=1)
* [Admin / Settings / URL ](https://dmaster.demo.civicrm.org/civicrm/admin/setting/url?reset=1)

=

# Logs and Debugging

* `smartyDebug=1`
* Printing errors to the screen
* Logs (PHP, Apache, Drupal, MySQL)

=

# Exercises

1. Install the latest Drupal
2. Install WordPress
3. Check 'Debugging and Error Handling' config

=

# Exercises +

1. Git install the extended reports extension.
2. Explore civibuild destroy and recreate

=

# Recap
