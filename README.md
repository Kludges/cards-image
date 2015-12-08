# nibbleblog-plugin-cards-image

This Plugin for Nibbleblog allows, to show a picture, that is uploaded with the cms upload manager, if a specific page, post or category is displayed.

1. Download the ZIP-Archive,
2. Extract,
3. Upload the folder 'cards_image' with all contents to the Nibbleblog plugin folder,
4. Install 'Cards Image' by using the dashboard,
5. Use the Upload manager to upload image files.
6. If not a plugin container is used to display all plugins e. g. in a sidebar, edit the theme file:
   place <?php echo $plugins_by_name['cards_image']->blog_body();?> there, where an image should be displayed.

What this plugin makes:

A picture file 'image.png' in the THEMES/YOURTHEME/css/img/ directory is displayed instead of Nibbleblogs default theme image "Mr. Nibbler". This is a cute logo, but i think, it's not matching all needs. So, a default image for every theme could be installed. The 'imgage.png' couldn't be installed by using the upload manager; it must be uploaded with FTP.

A uploaded picture file 'a.png' is displayed instead of the default and the default theme image.

A uploaded picture file 'apa1.png' is displayed instead of all other for the page with the id 1.

A uploaded picture file 'aca0.png' is displayed instead of all other for the category with the id 0.

A uploaded picture file 'apo1.png' is displayed instead of all other for the post with the id 1.

File Name Requirements for image files:

a.png, t.png, o.png, apa1.png, apa2.png ..., tpa1.png, tpa2.png ..., opa1.png, opa2.png ..., aca0.png, aca1.png ..., tca0.png, tca1.png ..., oca0.png, oca1.png ..., apo1.png, apo2.png ..., tpo1.png, tpo2.png ..., opo1.png, opo2.png ...
