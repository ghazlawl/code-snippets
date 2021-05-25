### Formatting

#### Format Node Created Date

`\Drupal::service('date.formatter')->format($node->getCreatedTime(), 'article_teaser');`

### Getting

#### Get Node Path Alias

`$alias = \Drupal::service('path.alias_manager')->getAliasByPath('/node/' . $nid);`

#### Get Node Image Field URL (w/ Style)

`$url = \Drupal\image\Entity\ImageStyle::load('my_image_style')->buildUrl($node->get('field_my_image')->entity->getFileUri());`
