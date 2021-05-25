### Formatting Things

Format the created date of a node:

`\Drupal::service('date.formatter')->format($node->getCreatedTime(), 'article_teaser');`

### Getting Things

Get the path alias of a node:

`$alias = \Drupal::service('path_alias.manager')->getAliasByPath('/node/' . $node->id());`

Get the URL of an image field and apply an image style:

`$url = \Drupal\image\Entity\ImageStyle::load('my_image_style')->buildUrl($node->get('field_my_image')->entity->getFileUri());`
