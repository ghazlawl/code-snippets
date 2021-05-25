### Formatting

#### Format Node Created Date

`\Drupal::service('date.formatter')->format($node->getCreatedTime(), 'article_teaser');`

### Getting

#### Get Image Field URL w/ Style

`$url = ImageStyle::load('my_image_style')->buildUrl($node->get('field_my_image')->entity->getFileUri());`
