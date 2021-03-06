# Importing a Heightmap<a name="importing-height-map"></a>

You can import a prebuilt heightmap to quickly place mountains and valleys in your level\. Lumberyard supports using heightmaps generated by third party tools such as World Machine\. A heightmap is a raster image that stores values, such as surface elevation data, for display in your Lumberyard game levels\.

Lumberyard uses heightmaps in the following ways:
+ Bump mapping – Uses 3D data to create shadows in materials
+ Displacement mapping – Determines the geometric position of points over the textured surface
+ Terrain mapping – Converts heightmap into a terrain [mesh](http://docs.aws.amazon.com/lumberyard/latest/userguide/ly-glos-chap.html#mesh)\.

Lumberyard also has a set of [terrain generation and manipulation tools](http://docs.aws.amazon.com/lumberyard/latest/userguide/terrain-landforms-intro.html) that you can use to create terrain from scratch\. 

For this tutorial, you'll create terrain by importing a heightmap\.

**To import a heightmap**

1. Open the **Terrain Editor** by choosing **Tools**, **Terrain Editor**\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/importing-height-map-open.png)

1. Set the maximum height of your terrain by choosing **Modify**, **Set Terrain Max Height**\.

   Enter **128**\.

   This means that the tallest point in your terrain will be no more than 128 meters\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/importing-height-map-set-max.png)

1. Choose **File**, **Import Heightmap**\.   
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/importing-height-map-import.png)

   Navigate to `\dev\StarterGame\Textures\Heightmaps` and select `FTUE_heightmap_test.tif`\.

   In your viewport, you see the initial creation of valleys and mountains as determined by the heightmap\.

1. Press **Ctrl\+S** to save your level\.

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/lumberyard/latest/gettingstartedguide/images/importing-height-map.png)

[Next: Removing the Ocean](importing-remove-ocean.md)