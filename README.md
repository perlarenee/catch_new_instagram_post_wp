# catch_new_instagram_post_wp
PHP function to catch new posts (in this case from IFTTT Instagram chanel), check if the first image attached is in the current uploads dir (year/month), and if not, upload it, add it to the media library and set it as the posts featured image. Then remove the image tag from the post content, depending on the new featured image instead.
