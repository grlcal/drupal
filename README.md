# drupal
error during install using composer command line in ubuntu on azure
i checked the php -m to see it has all the required extension

composer create-project drupal-composer/drupal-project:8.x-dev drup1 --stability dev --no-interaction
> DrupalProject\composer\ScriptHandler::checkComposerVersion
Loading composer repositories with package information
Updating dependencies (including require-dev)
Your requirements could not be resolved to an installable set of packages.

  Problem 1
    - webflo/drupal-core-require-dev 8.8.x-dev requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.x-dev requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.6 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.5 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.4 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.3 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.2 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.1 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.0-rc1 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.0-beta2 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.0-beta1 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.0-alpha2 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.0-alpha1 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - webflo/drupal-core-require-dev 8.7.0 requires behat/mink-selenium2-driver 1.3.x-dev -> no matching package found.
    - Installation request for webflo/drupal-core-require-dev ^8.7.0 -> satisfiable by webflo/drupal-core-require-dev[8.7.0, 8.7.0-alpha1, 8.7.0-alpha2, 8.7.0-beta1, 8.7.0-beta2, 8.7.0-rc1, 8.7.1, 8.7.2, 8.7.3, 8.7.4, 8.7.5, 8.7.6, 8.7.x-dev, 8.8.x-dev].
