This page walks you through the various sections of creation.



### Image Editor
AdWyze has an inbuilt Image Editor you can use to create templates and apply them while creating your ads - be it single image ads, MPA dynamic product ads (DPA) or Static Product Ads (SPA).


![Screenshot](http://res.cloudinary.com/depce28yo/image/upload/v1457608640/email-assets/pudates/output_eHYrna.gif)


Let's see how to create a template using Image Editor. It's simple to use with almost no learning curve.

- Go to creation → Image Templates
- Click on “Create Template”
- Choose from the set of base images - either from one of your recent images or from the feed. These just act as the base image for the template. When you apply a template to any product image (during ad creation), that product image gets replaced here in the place of the base image.
- You can add text, change font, font size & color, add border of the image, resize image or even add one more image on top of the base image.
- Image editor also supports dynamic texts that gets replaced with the actual value from the feed
e.g: You can add a text, "Get {{product.title}} for 30% OFF" and while creating a DPA ad, it automagically replaces with the right product tile and price from your feed.


### Product Feed

You can create a product feed by going to Creation -> Product feeds section.

1. Give a name for your feed
2. Enter your hosted feed URL or upload your feed file
3. Choose the file type that you used in the step2 (either xml or csv)
4. Set update interval (in hours) - how often do you want us to fetch the updates from your hosted feed

After you fill the form and hit 'save', we will notify you once the feed is processed and ready to be used in your DPA or SPA

### Product Catalog

By default we create a product catalog once the feed is ready. But if your feed has any custom columns, you need to map them with the custom label fields to use them during DPA/SPA ad creation.

You can create a product catalog by going to Creation -> Product Catalog section.

1. Click on 'create product catalog'
2. Choose the product feed from the dropdown from which you want to create a catalog
3. Map the custom labels (0 to 4) to the additional fields you have in your feed and 'save'

Once the product catalog is created, to use these custom label fields during ad creation, you need to choose this product catalog at ad creation.


### DPA - Dynamic Product Ads

To run dynamic product ads, you need to have atleast one product feed. Once you have the feed uploaded and is ready to use, navigate to Creation -> DPA

1. Fill in the campaign details. Select a Product feed and Product catalog
2. In the Targeting section, choose a product set. You can also create a product set here. A product set is a collection of items from your feed chosen by the filter conditions you apply. Once the product set is chosen, proceed with the other targeting options
3. In the Ads section, you get to choose the image field (from which column of the feed should we take up the ad image) and also specify the number of products per ad. If more than 1 product per ad is chosen, carousel ads (MPA) get created.
4. In the text, headline and description fields, you can dynamically choose the fields from your feed by clicking on the "+" button. If you have trouble with editing the headline after choosing tokens from "+" button, it's mostly to with the character limit of the field. 
5. Apply an image template by clicking on the "Edit Image" on the top of the ad preview. Please wait a while for the preview to get updated with the image template. Modified images for your ads are created with just a click :)


The live ad preview in the right gets instantly updated with the real values of the tokens from your feed too. 
You now have your dynamic product ads ready. Go head with pricing & scheduling and publish the ads. 

Pro tip: You can use token (a placeholder to replace with the actual value) from your feed in the text area of image editor while creating an image template.
e.g: If you have {{product.brand}} as text on your image (with the double flower brackets), it actually prints in the brand's name (fetched from brand field in your feed) on the image. If you apply this template in the DPA/SPA you can see the brand name on the preview images too.


### SPA - Static Product Ads
Static Product Ads (SPA) is a way AdWyze helps you create regular ads in bulk by using your product feed. The targeting still remains the same as the one you use for creation of regular facebook ads.


1. Go to Creation → Static Product Ads
2. Fill out the campaign and targeting sections (as you'd fill out for normal facebook ad creation) and go to Ads section
3. In Ads section, choose the product feed and product set. You can also create new product set on the chosen product feed here in this section. by applying filters to the feed.
4. Once you finish choosing your product feed, catalog and product set, go ahead and fill out other details for your ad. These ad details can be dynamically obtained from your feed by clicking on the "+" button beside each field and choosing which column title from your feed.
5. You can create upto 20 ads, can choose how many images an ad should have (If you select more than 1 image per ad, MPA carousel ad gets created) and even select which column to fetch from the feed for the base image. 
6. Now in the preview, select the Image template you have already created. The template gets applied to all the image. Wait a while for the preview to get updated with the image template. 


Click "next", fill the pricing & schedule sections to publish your new ads with modified images. 


### Product Sets
Go to "Creation" and select DPA ads (either DPA or SPA). In the ads section, select the feed and proceed to create product sets by applying filters on the feed.


### Custom Audience
In addition to creating templates for audience based on the targeting & split rules you have while creating a campaign, you can also create new audience set and choose this audience set while creating campaigns.


Types of custom audience currently supported
- Emails
- Phone numbers
- Advertiser ids (coming soon!)
	
To create custom audience, click on creation → custom audience.
Give a name for the audience group, choose whether these are emails or phone numbers and copy/paste the list to create new audience group. 


### Instagram Ads
To create Instagram ads ** Go to creation → create ads → create new instagram ads **

You do not need to have any special instagram ad account to start running ads on Instagram. Once you have a facebook account linked (and have a user account in Instagram), you can directly start creating Instagram campaigns.


### Edit campaigns
Right now, the platform doesn't allow you to edit campaigns. However, you can edit a saved template or add more ads 
into adsets of any existing campaign.

### Campaigns history
You can see the “History” of the campaigns you created. Go to **Stats → History**

### FAQs
**What are global templates?**
You campaign settings can be reused (cloned to save time) allowing you to modify only the fields that you want to change while creating a new campaign.


**How to create global templates?**
At the final step of campaign creation, you can save the entire template - campaign, targeting, ads, pricing & schedule as a single global template. The next time you want to create a campaign, you can directly choose this global template from the dropdown and all the entire template loads. Proceed with necessary changes (in campaign, targeting, ad or scheduling sections) and publish. You can also save this modified template as a new global template again.

**How to add more ads to existing adset in a campaign?**
- Go to stats → adsets
- Click on the adset in which you want to add more ads
- In the adset stats, scroll down to find “Ads” section.
- Click on “Create new ad in adset” tab. You shall be redirected to a new browser tab through which you can proceed to create your new ad. 

This ad gets saved in the adset.


**What are image templates?**
To edit images, you first need to create a template (with all edits you'd want to perform on an image), save it and while creating ads, just need to select this already created template. The live preview instantly gets updated with the applied changes. Templates can be applied to any number of ads.

**What's the 'Base Image' in Image editor popup?**
Base image acts as a place holder for your actual image in the creative. 
Select any recent image or one from your feed or leave the default one as your base image and proceed to make edits. Save it as a template and when you apply this template during ad creation, this base image gets replaced with the one your actually uploaded for the ad.

**Why don't I see some of the templates I created?**
You can choose either 1200x628 or 600x600 (for multi product ads) template and the corresponding size templates will only be shown depending on whether you are creating a regular ad or MPA ad

**Can I use dynamic field values (from the feed) in my image template?** 
Yes! e.g: If you have a column name as "Brand" in your feed, you can use {{product.brand}} in your text on the image and during ad creation it gets replaced with the actual brand name fetched from the feed item. 



