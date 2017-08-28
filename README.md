# RadiusShapeView

A view for view shape

----

As [setClipToOutline](https://developer.android.com/reference/android/view/View.html?hl=zh-cn#setClipToOutline(boolean)) only support Android 5.0(Api >= 21).

There has other new way (Maybe not the best way) compat below Android 5.0.

## How To Use

This view need cover whole view and reset radius color from background color.

``` java
<com.wt.radiusshapeview.RadiusShapeView
            android:id="@+id/activity_main_shape"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignBottom="@+id/activity_main_content"
            android:layout_alignLeft="@+id/activity_main_content"
            android:layout_alignRight="@+id/activity_main_content"
            android:layout_alignTop="@+id/activity_main_content" />
```

``` java 
// init shape view
activity_main_shape.setRadius(20)
activity_main_shape.setRadiusColor(resources.getColor(R.color.colorAccent))
```

### Demo

![gif](https://github.com/wt1098078873/RadiusShapeView/blob/master/gifs/device-2017-08-28-175349.mp4)

## License

```
  Copyright 2017 wt (wt1098078873@gmail.com)

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.
```