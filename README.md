CutIntoLayout
=============

CutIntoLayout allows you to create clear effect on your background.

[![Android Arsenal](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScekxiT3M5aFlELXc)](http://android-arsenal.com/details/1/3316)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Android](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wSccEZaclNGN0R5OWc)](https://github.com/DevLight-Mobile-Agency)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Download](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScVGZQUVlrM21Belk)](https://bintray.com/gigamole/maven/cutintolayout/_latestVersion)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![License](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScU0tmeFpGMHVWNWs)](https://github.com/DevLight-Mobile-Agency/CutIntoLayout/blob/master/LICENSE.txt)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Codacy](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScSHhmckZyeGJDcXc)](https://www.codacy.com/app/gigamole53/CutIntoLayout?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=DevLight-Mobile-Agency/CutIntoLayout&amp;utm_campaign=Badge_Grade)

<br/>

<p align="center">
    <img src="https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScUHJxOGNMd3pmckU"/>
</p>

You can check the sample app [here](https://github.com/DevLight-Mobile-Agency/CutIntoLayout/tree/master/app).

Warn
====
```
This library is not more supported. 
If you want to add new feature or fix a bug, grab source code and do it. 
If you think your fix or feature would be useful to other developers, 
I can add link of your repository to this README file. 
Thank you for using our libraries.
```

Download
========

You can download a `.aar` from GitHub's [releases page](https://github.com/DevLight-Mobile-Agency/CutIntoLayout/releases).

Or Gradle:  
```groovy
compile 'devlight.io:cutintolayout:1.0.2'
```

Or Maven:  
```xml
<dependency>
  <groupId>devlight.io</groupId>
  <artifactId>cutintolayout</artifactId>
  <version>1.0.2</version>
  <type>pom</type>
</dependency>
```

Or Ivy:  
```groovy
<dependency org='devlight.io' name='cutintolayout' rev='1.0.2'>
  <artifact name='$AID' ext='pom'></artifact>
</dependency>
```

Android SDK Version
===================

`CutIntoLayout` requires a minimum SDK version of 11.

Sample
======

`CutIntoLayout` must have child. Only one child.  
You can put any view into layout.

`XML` init:

```xml
<com.gigamole.cutintolayout.lib.CutIntoLayout
    android:id="@+id/cut_into_layout"
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_gravity="center"
    app:cil_mask="@drawable/sample_bg">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:gravity="center"
        android:text="@string/sample_title"
        android:textColor="@color/white" />

</com.gigamole.cutintolayout.lib.CutIntoLayout>
```

Getting Help
============

To report a specific problem or feature request, [open a new issue on Github](https://github.com/DevLight-Mobile-Agency/CutIntoLayout/issues/new).

Author
======

Created by [Basil Miller](https://github.com/GIGAMOLE) - [@gigamole](mailto:gigamole53@gmail.com)
