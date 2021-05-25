### Formatting

#### Format Node Created Date

`\Drupal::service('date.formatter')->format($node->getCreatedTime(), 'article_teaser');`

### Getting

#### Get Image Field URL w/ Style

`$url = ImageStyle::load($style)->buildUrl($node->get($field)->entity->getFileUri());`
