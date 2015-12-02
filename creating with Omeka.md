# Getting started with Omeka

Now that you've thought about how to organise your data usefully, it's time to get started with Omeka itself. 

### Sign Up
The first step is to sign up for an account. Go to [Omeka.net](omeka.net) and sign up. Choose the free, basic plan, which lets you create one site and gives you 500 MB of storage.

<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/signup.png" alt="Signup screenshot" height="400" width="600"/></div>

When you sign up, you'll be prompted for a username, password and email address. Once you've supplied these details, you'll be emailed a link to activate your account. 

Clicking the link will take you to a dashboard for your new account. Click on 'Add a site' to start creating your Omeka site.
<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/add%20site.png" alt="addsite" height="200" width="600"/></div>
Give your site a name. It will have the format [name].omeka.net. You must use alphanumeric characters only - no special characters! Give it a title. The description field is optional. Once you've completed these details, you'll be taken to the dashboard for your account.

You can see how much of your storage you have used, edit your personal information, change your password, upgrade your plan to add more sites or storage, and deactivate your account from the 'My Account' page. For now though, let's get started!

## Adding content
Click on 'manage site' from the dashboard. This will take you to the interface where you can start adding content.

### Exercise - Add an item
* Add an item to your Omeka
* Describe it with metadata - use both the Dublin Core and Item Type metadata
* Attach a file to your item
* Choose whether it is public or not (items are private by default)
* Choose whether it is a 'featured' item (this means it will be displayed prominently on your site)
* Save by clicking Add Item

<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/AddInput.png" alt="Screenshot add item" height="300" width="600"/></div>

And that's your first item!

*Please note*
* You can add multiple entries for each metadata field by clicking 'Add Input' 
* You can add multiple files to an item (but be sure that they really do relate to the same item)

**Item types**

Omeka comes with a number of pre-set Item Types. If none of them is applicable to your collection, you can add a new one by clicking on 'Add an Item Type'

<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/additem.png" alt="Item Type" height="200" width="600"/></div>

You can customise the Item Type metadata by clicking Edit. From this page, you can add custom comments and new elements. You can also change the order in which the elements appear. Neat, eh?

## Customising

Now you've got an item into Omeka and know how to describe it, it's time to take control of your Omeka! 

Click on the name of your site in the top left of the menu bar to see what the front-end of your site looks like. Omeka comes with a number of pre-set themes, and the default one will be enabled. 

<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/viewsite.png" alt="View Site" height="200" width="600"/></div>

Now, go back to the dashboard and click on Appearance. You can pick from a few other themes that Omeka offers. 

### Exercise: Change and customise the theme
* Change the theme
* Add content to your homepage
* Add a navigation link
* Change how your images and data display


Change the theme, then click on 'Configure Theme' for more options.

<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/theme.png" alt="Theme" height="300" width="600"/></div>

The 'Themes' tab lets you customise the information that appears on your site, such as adding a logo, footer text, or licence information. If you've selected a *Featured Item* from among your items, you can choose to put it on the homepage of your site. Try changing a few things. If you have the front end view of your Omeka open in another tab, you can hit refresh once you've saved your changes to see how it looks.

<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/ConfigureTheme.png" alt="Configure Theme" height="320" width="600"/></div>

The **Navigation** tab will let you change which search options appear on your site. You can add custom links to this section, to direct users to items or collections within your Omeka or to resources elsewhere on the web. Note you need the full url of any external page. You can set any of these Navigation links to be your homepage.

<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/Navigation.png" alt="Navigation" height="330" width="600"/></div>

The **Settings** tab will let you customise the size of your images and how they display. You can also choose to hide empty elements, so metadata fields you're not using don't show up.

This will make more sense once you have more content in your site.

<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/settings.png" alt="Settings" height="350" width="600"/></div>

#### Users
By default, you're the only user on your Omeka and you have super powers (no, really!), meaning that you have full control of your site. You can choose to add new users if you want to invite a collaborator on your project. You can decide how much control to give them, from Super User, who can do everything, to contributor, who can only view your site without making changes.
<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/users.png" alt="Users" height="200" width="600"/></div>

#### Plugins
Omeka is highly customisable by means of plugins. You get a few choices with your free account. 
Go to the **Plugins** tab and install the CSV Import and Exhibit Builder plugins

**Importing a CSV**
Once you have installed the CSV Import plugin, you can import a csv into Omeka.
Each line in the csv will be one item in your Omeka. You'll map the column headings in the csv to the metadata fields in Omeka. You can apply one Dublin Core metadata field to more than one column (for example, you can have two 'description' fields). 

You need to make sure that any custom metadata fields that you want to use have been created *before* you start importing your csv. It's not possible to create additional metadata fields once you have started importing your CSV. 

## Organising your items

#### Collections
You can group items in Omeka into Collections. Each item may belong to only one collection. 
You can create collections from the collections tab in your dashboard. Omeka will prompt you to provide metadata about your collection. 

You can assign items to a collection as you add them or you can move items into a collection in bulk. Once you have created your collection, click the checkboxes next to the items you wish to add in the 'Items' menu. Click on the Edit button, and then select the collection to which you're adding your items from the dropdown menu in the next screen. You can change the type and visibility of items and assign tags to multiple items using this technique.

#### Tags
Use tags to add keywords to items. You can use tags to help draw connections between items in different collections. Unlike the core metadata, which conforms to a standard and can't be edited, tags are entirely up to you.
You can tag items as you add them or you can assign tags to multiple items at once by selecting them from the Item menu and clicking edit.

#### Build an exhibit
Once you have install the Exhibit Builder plugin, click on 'Exhibits' and start creating!
<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/Exhibits.png" alt="Exhibits" height="320" width="600"/></div>

First, you'll be prompted for some information about your exhibit. 'Slug' is the exhibit name as it will show up in the URL, in the format sitename.omeka.net/exhibits/show/slug

Once you've added this basic information, start adding pages to your exhibition. You'll be prompted for a page title and slug again, and then you can start adding items. Choose a layout for each block. You'll have space to add narrative or explanatory text to each item, as well as a caption. There's a basic WYSIWYG editor, or you can edit the HTML if you feel confident to do so. You can re-order the blocks on a page once you get underway. Visitors to your exhibit will be able to see your items arranged in an exhibit and click on each item to view its full record.

## Advanced uses - using Settings
The Settings tab lets you make some some further customisations to your Omeka. The **General** tab lets you change your email address and site name, as well as some basic information about your site.

<div align="center"><img src="https://github.com/FCTweedie/omeka/blob/master/OmekaScreenshots/GeneralSettings.png" alt="General Settings" height="250" width="550"/></div>

#### Search
The Search tab lets you choose which types of records will be searchable in Omeka. If you change the types of records that are searchable, you'll need to click the 'Index Records' button, so that search within your site updates to your new preferences.

#### Element sets
Omeka doesn't permit you to edit the Dublin Core Metadata fields for the good reason that, once you edited them, they would no longer comply with the international standard. You can, however, change the order in which the elements display by dragging and dropping so that the ones you use most are at the top. You can also add custom comments to each element by clicking on the arrow at the end of the end of each element. Similarly, you can add your own descriptions to the item-type metadata from the **Item Type Elements** tab.

#### Leave Omeka
There are a number of ways to get content out of Omeka. You can delete single items from the Items menu, or use the bulk edit function to delete multiple items.
If you imported the items from a csv, the 'Status' tab of the CSV Import menu has the option to undo an upload, which will remove the contents of a whole csv.
If you want to move the contents of your small Omeka.net site over to another Omeka instance (for example, if your institution offers a hosted version), install the 'Omeka API Import' plugin. You can then migrate all your data over to your new site.
It is also possible to export items as xml or json.


### Final Challenge
* Inspect the provided csv and create any additional metadata fields that you will need in order to import it
* Import the csv into your Omeka
* Add the items into two collections
* Tag the items with at least four tags
* Add image files to the items
* Build an exhibit displaying a selection of items from each collection
* Enable search by tag




