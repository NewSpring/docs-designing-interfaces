# Exporting Assets

Now you have incorporated a systematic approach to naming the elements and artboards, it is time to get down to the nitty gritty of exporting. 

#### Getting Started
When you create a new artboard ensure it is set to export with a background color. This will save you having to go back through every artboard later.

![](https://s3.amazonaws.com/uploads.hipchat.com/21097/1894791/0mY8H3Sc5GW4Gw7/upload.png)


#### The Files Are Inside The Computer
Our current structure for saving and exporting files within Dropbox is as follows:

	Apollos - the root directory
		01. desktop
		02. mobile
		03. research
		04. misc
		05. resources

- Sketch files live inside the source files folder.
- Exported assets are separated by kind within the exports folder.

For the purpose of this guide we’ll use mobile as our example:

		02. mobile
				- assets
					- source files
							newspring-ios.sketch
				- exports
					- icons
						icon-bank_account.svg
						icon-calendar.svg
						icon-history.svg
					- pages 
						iphone_6-article-2.png
						iphone_6-profile-edit_credit_card.png
						iphone_6-search_results-1.png



#### Step 1: Pages
Generally the first phase of exporting is sharing the pages you’ve completed. If you have kept your artboards accurately named this is as simple as using the batch export feature in Sketch.

![](https://s3.amazonaws.com/uploads.hipchat.com/21097/1894791/umdKC1RwCFM6vqT/upload.png)


As you can see, a lot of other elements show up in the batch export, as it is showing you anything in the document that has been giving export properties. If it gets too time consuming trawling through the elements to find the artboards you can do a manual export. You perform the manual export by selecting all the artboards and using the export function in the side panel.


![](https://s3.amazonaws.com/uploads.hipchat.com/21097/1894791/JAcdWPwLXthsFLB/upload.png)


#### Step 2: Spec Pages
This is step is by far the most time consuming of the export process, but inevitably is the most important. It is this step that prevents the development team from having to guess and sets them up for success in implementing your designs. I previously mentioned the Sketch Measure plugin and this is where it will become familiar. 

The goal of the spec page is to take the guess work out of your design. We annotate the design with distances, sizes, padding and typography styles. There are keyboard shortcuts for the plugin, which are useful to learn in order to speed up your workflow.

![](https://s3.amazonaws.com/uploads.hipchat.com/21097/1894791/ACrOeRjxzQMsmsH/upload.png)

- The hierarchy of any text is shown, e.g. h2.
- Padding/margin is illustrated using the Sketch Measure plugin.
- Sizes of elements such as images or buttons are illustrated using the Sketch Measure plugin.


#### Step 3: Elements
The final step is to hand off any page specific elements that are needed to re-create the design. Oftentimes we are using content that will eventually be replaced with dynamic content on the live site. While this will be replaced, it is still important to export the static elements for the development team to use in creating the initial page. Typically these elements end up being images and icons. 

Having nicely organized your files with the naming conventions when handing off these assets you can simply send over the dropbox link.


