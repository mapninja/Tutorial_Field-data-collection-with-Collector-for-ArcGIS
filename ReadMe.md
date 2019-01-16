# Creating a field data collection app with your Stanford ArcGIS Online account and Collector for ArcGIS.

## Overview  

This tutorial will introduce the basics of creating a field data collection application using your Stanford ArcGIS Online account and the Collector for ArcGIS apps for iOS and Android.

Topics include:  


## Tutorial
### Login to your ArcGIS Online Account  
1. Go to [https://stanford.maps.arcgis.com/home/signin.html](https://stanford.maps.arcgis.com/home/signin.html) and **Login** using your **SUNetID & Password** using the Stanford University option.  

  ![Stanford SSO](./images/stanford_sso.png)


  ## Part 1: Create a Feature Layer  

2. Go to **Content**, and in **My Content** click **Create** and choose **Feature Layer** to open the **Create a feature layer** dialog.  
  ![Create a feature layer](./images/??.gif)
3. Select the **Build a layer** category, select **Points, lines, and polygons**, and click **Create**.  
  ![Create a point, line and polygon layer](./images/??.gif)
4. **Rename** the individual **point, line and polygon layers**.  
  ![Create a point, line and polygon layer](./images/??.gif)  
5. Set the **extent** for your layer and click **Next**.  
  ![Create a point, line and polygon layer](./images/??.gif)  
6. Provide a **title**, like "**Walking Tour**".  ***Since this must be a unique name in your organization, you might need to include your initials if others have followed these same steps***. Click **Done**.  
  ![Create a point, line and polygon layer](./images/??.gif)  


  Your **Walking Tour layer** is created and its item details page should open. In the following steps you’ll create the fields that define the form for the Places layer.

7. Go to the **Data tab** of the item page and go to **Fields**. If you created layers for points, lines, and polygons, verify that ***Places*** is chosen in the list of layers.  
  ![Create a point, line and polygon layer](./images/??.gif)  
8. Click **Add**. Give a name ***POI*** and an alias ***Point of Interest***. Choose type **String** – you’ll create a list of choices later. Accept the other defaults and click **Add New Field**.  
![Create a point, line and polygon layer](./images/??.gif)  
9. Click ***Point of Interest*** in the Display Name list and click **Create List** to create a list of choices for the type of amenity.
Type a label of Water fountain with a code of 0.  
  ![Create a point, line and polygon layer](./images/??.gif)  
10. Add entries for Restroom (code 1) and Picnic table (code 2).
*The sample map has more options for the type of POI — add as many here as you want.*  
  ![Create a point, line and polygon layer](./images/??.gif)  
11. Click **Save**.
12. Create another field named ***Notes*** that is a **String**.

  Since you want your mobile workers to be able to attach pictures showing the things in the parks, enable attachments:  

13. Go to the **Overview tab** of the item details page, scroll to the **layers list**, and click **Enable Attachments** for the Places layer.  
  ![Create a point, line and polygon layer](./images/??.gif)  

## Part 2: Make a map

1. Still on the **item page** of your layer, in the drop-down list for **Open in Map Viewer** pick **Add to new map** to start making your map.  
2. **Save** your map, giving it a title Walking Tour [Your initials] and a tag.  
3. In the **Contents pane**, hover over the layer of places, click **More Options**, choose **Rename**, and rename the layer of places to Places.  
4. Click **Change Style** for the **Places layer**, Choose to show the **POI Type** attribute.  
  ![Create a point, line and polygon layer](./images/??.gif)  
5. Click Options for the Types (Unique symbols) drawing style.
6. Click the symbol next to picnic table, click Shape, choose the Local Government category, and click the picnic table picnic table. Set it to a size of 30 and click OK.
  ![Create a point, line and polygon layer](./images/??.gif)  
7. Configure the symbols for the Restroom Restroom and Water fountain Water fountain types, also in the Local Government category.
Click OK and click Done.
  ![Create a point, line and polygon layer](./images/??.gif)  
8. Click Edit, click Manage, and click Save Changes.  

  ![Create a point, line and polygon layer](./images/??.gif)  
  This creates feature templates that Collector will use as the types of assets you can add to the map.
9. Save and name the map.  


## Part 3: Capture park assets in Collector
Open Collector, using "stanford" as your organization, and your SUNetID and password. 

1. Choose the map you just made.
Note: Either sign in with the same account you used to make the map, or share the map with a group and sign in as a user that is a member of that group.
Walk around your local park, adding picnic tables, restrooms, and water fountains. If you aren’t sure how to add them, see the blog on capturing your local park.
Now you’ve prepared and used your own layer in Collector. Think about what assets and observations your organization would like to bring into its GIS, and how you’ll design layers for those data collection projects.

