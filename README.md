# drupal-notes

## Menu başlıkları (admin toolbar)
* content: içerik crud işlemleri
* structure: ekranda görünecek block verileri ve içerik türlerinin (entity) oluşturulması ve yapılandırılması 
* appearence: görünümün özelleştirilmesi
* extend: yeni modül kurma ve kaldırma
* configuration: sistemdeki birçok ayar, yeni kurulan modüllerin ayarları burada çıkar.
* people: kullanıcı, role ve yetkiler
* reports: sistem raporları
* help



https://www.drupal.org/docs/develop/using-composer/starting-a-site-using-drupal-composer-project-templates

* composer kurulu olması gerek

composer create-project drupal/recommended-project drupal  && cd drupal

* modülleri kurmak için

composer require 'drupal/workflow:^1.5'

composer require drupal/pathauto

* drush kurmak için

composer require drush/drush


## workflow modülü 


https://www.drupal.org/project/workflow

The workflow module enables you to create arbitrary workflows in Drupal and associate them with entities. A Workflow is made up of workflow states. Moving from one state to another is called a transition.


* bak

* https://www.drupal.org/node/1027546

* https://www.drupal.org/project/rules

* https://www.drupal.org/project/workflow
