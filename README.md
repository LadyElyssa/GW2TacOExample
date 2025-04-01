# GW2TacOExample
A basic working example of some XML.

You can find a written guide here: https://wiki.guildwars2.com/wiki/User:Lady_Elyssa/Guide_to_GW2_TacO_Markers_and_Trails

```
<OverlayData>

   <MarkerCategory Name="mymarkers" DisplayName="My Markers" fadeNear="2500" fadeFar="5000">
      <MarkerCategory Name="example" DisplayName="Example Trail" texture="Data/Images/trail.png"/>
      <MarkerCategory name="circle" DisplayName="Toggle Circle" iconFile="Data/Images/circle.png"/>
      <MarkerCategory name="heart" DisplayName="Toggle Heart" iconFile="Data/Images/heart.png"/>
      <MarkerCategory name="square" DisplayName="Toggle Square" iconFile="Data/Images/square.png"/>
      <MarkerCategory name="triangle" DisplayName="Toggle Triangle" iconFile="Data/Images/triangle.png"/>
   </MarkerCategory>

   <POIs>
      <Trail type="mymarkers.example" trailData="Data/example.trl"/>
      <POI MapID="15" xpos="-200.086" ypos="28.6689" zpos="331.556" type="mymarkers.triangle" GUID="AVE8BmBQdkG32qvKSxkm6w=="/>
      <POI MapID="15" xpos="-194.003" ypos="28.6396" zpos="338.98" type="mymarkers.circle" GUID="RT3v6Tr5gE6yyav0dFO4uQ=="/>
      <POI MapID="15" xpos="-186.742" ypos="28.6003" zpos="331.901" type="mymarkers.heart" GUID="As9RB0soykqn4NsqA1abvA=="/>
      <POI MapID="15" xpos="-193.448" ypos="28.6712" zpos="324.628" type="mymarkers.square" GUID="BV3HKuCr6UapNoZMT2R1JQ=="/>
   </POIs>

</OverlayData>
```
