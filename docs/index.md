# WKS Documentation

Welcome to the new edition of Dogtec Web Kennel System, an online kennel social networking service, operated by Dogtec, LLC. Here is information on how to use the site. *Note that a few things are different from the previous edition.*

**If you you want to report a bug or an issue please do so [here](https://github.com/jphilip/wks-documentation/issues).**

## New Features based on user feedback

* Ad listing (PRO only)
* Present images as Short Stories
* Upload images up to 2.5 MB
* Search engine base on Kennel, Ads, Dogs, Groups or Stories
* Facebook and Google login
* Facebook Like and Share buttons
* Link kennel and dogs to videos from YouTube, Vimeo or Facebook
* Easier way to delete items

## Unpopular Features Removed

* Posts
* Comments
* Events
* Tags
* Favorites
* Health records (may be back later)

## Registration and Login

When you register as a user, your kennel is now automatically registered, but there can only be one user for a kennel, which is different from the previous version. You can now log in with Facebook or Google in addition to the regular WKS login, however, you must first be registered on WKS before you can do that. There are still free and PRO accounts, free accounts are limited to 100 items (dogs or images); more details on the differences between free and pro accounts [here](https://www.dogtec.com/registration/). After you are logged in, you can access the admin interface from the menu under you user name on the top right of the page. From there, you can also request a password reset, edit your profile (name or email). The admin section is divided into the following modules:

## Kennel Administration

On all the Admin Sections listings, you can search by fields relevant to the topic, for example first or last name for mushers. You can also perform operations in bulk (mostly delete at this time). *Note that some items like dogs have identifiers based on the name or title of the items.* These are used in the URL. WKS will let you change it after you created the item, however keep in mind that if you change the identifier after some time, the item URL will change, which could affect for example the number of Facebook Likes that the item received.

### Ad Admin Section

Ads are only for PRO kennels. They will appear in the kennel’s ads and in the overall marketplace page, as well as in searches and on the WKS front page for the latest ones. You need to enter a title and a description in an HTML editor. If you do not check the published box, the ad will not show in pages. You can optionally select an image for the add a dog if the ad is for a dog. *Note that you can also embed images in the description.*

### Image Admin Section

In the Images Admin listing page, you can upload images up to 3 MB in size. If the image is over 1600 pixels wide, it will be reduced to 1600. You can upload up to 5 images at a time by dropping them on the drop zone indicated, or by clicking on the “Upload multiple photos” button. In this case, WKS will assign a temporary title to the image and you will have to go to each image’s record to customize it. You can also add one image at a time by clicking on the “Add image” button which takes you directly to the image add/edit page. There, you can enter title, description and if you want that image record to be used as a short story. Short stories appear on your kennel stories page and latest stories on your kennel as well as WKS front page for PRO kennel. You can also check the Pin story box to keep it on top of the list regardless of when it was updated. The text of the story is the description of the picture which is limited to 200 words. Finally, before saving the image, you can associate it to one or more dogs by selecting them in the “Dogs to associate to this image” section. Once the image record is saved, you are able to customize how the thumbnails and the image look by dragging the cropping box in the “Crop thumbnail” and “Crop Image” sections. *Note that the image ratio for the thumbnails is fixed at 4x3, but it is free for the image.* After you save the record again, you can see what thumbnails and image look like by expanding the “What image and thumbs will look like” section. *Note that  a medium and a small thumbnails  as well as a smaller image are generated and that the original image is always kept.*
In the Image sets admin listing, you can add/edit/delete image sets (albums). In the Image set edit page, you can ad and remove images from the set.

### Kennel Admin Section

#### Breeds

In the Breeds Admin, you can simply add/edit or delete the breeds you need for your kennel.

#### Dog Groups

The Dog Groups Admin is slightly more complicated because the groups are organized in a hierarchical fashion. For example, you may decide to group your dogs in race teams by year in which case for example the 2021 group may have sub-group like 2021 Rondy team, 2021 North American team… In the group listing, you can expand/retract the different sub-groups by clicking on the arrow before the group name and you can reorder/re-parent them by dragging the cross next to the arrow. You can also re-parent a group by selecting a different parent group in the Group Edit page. There, you can also select an image for the group by clicking on the magnifier icon in the image section of the group. In the "Dogs in Group" section, you can add/change/remove the dogs in the group. In this section you can add/change a dog by typing the dog’s name, year or breeder and selecting from the auto-suggest list. You can also add a comment for that dog pretending to its participation in the group, and if you want to display the dog thumbnail in the group page. *Note that the changes will only take effect when you save the group.* To remove a dog from the group, you check the Delete box on the right side of the table and save the group for the removal to take effect. *Note that this does not delete the dog, just removes it from the group.* You can combine more than one of these operations (add, remove modify) and save the group only once.

#### Dogs

In the dog admin listing, you can filter dogs by leader, active, sex, breed and birth year. You can edit a dog’s details, including name, sex, birth year, weight, leader, active status and description. You can choose a breed among the breeds you have added for your kennel. Similarly, for father and mother, you can also choose among the dogs that you already entered, but you can also select dogs that other kennels have entered by selecting the “Search among all kennels” box. *Note that only the relevant dogs should appear in the choices to select from, for example females for mother, not younger that the current dog…* The dog edit page also gives you an option to select multiple images for a dog and sort them by dragging the handle in the sort column. *Note that only the first image will appear picture pedigrees or searches.* Similarly to images, you can associate multiple videos to a dog. Like in the group edit form, all those changes will only take effect after you save the dog record. Finally, in the littermates section, you can select littermates from dogs that you already entered and you can remove dogs from the litter if needed. *Note that you do not need to save the dog record for those changes to take effect.*

#### Kennel

In the kennel admin you can set the name of your kennel and its active status. Active means that it will show on the frontend of the site. In addition, you can select a kennel image among images that you uploaded, edit the description that will appear in your kennel front page, using a visual HTML editor. You can also edit the address, including country and state or province. *Note that you can associate videos to your kennel as well, but you do this by checking the “Show on my kennel front page” box in the video’s edit page (see below).*

#### Mushers

The Mushers Admin is very similar to the breeds and is used to add/edit first and last names of dog breeders.

#### Videos

The Videos admin allows you to link videos from YouTube, Vimeo or Facebook to WKS pages. To link a video, you need to find its URL by either copying the URL from the video’s page or clicking on the share button in YouTube and copying it there. You also need to find the aspect ratio of the video. Most videos now are in the 16x9 ratio, so it is the default. 4x3 is another common ratio, like the old televisions used to be. 1x1 is square and 21x9 is like cinemascope and not as frequently used. If you do not select the right ration, the video will not display correctly on the page. You also have to enter a title and if you want the video to appear on your kennel’s front page.