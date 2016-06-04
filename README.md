# Material Design Dimens
[![GitHub license](https://img.shields.io/crates/l/rustc-serialize.svg)](https://github.com/DmitryMalkovich/material-design-dimens/blob/master/LICENSE.md) [![Maven Central](https://img.shields.io/maven-central/v/org.apache.maven/apache-maven.svg)]() [![Bintray](https://img.shields.io/bintray/v/asciidoctor/maven/asciidoctorj.svg?maxAge=2592000)]()

Default colors and dimens per [Material Design guidelines](https://www.google.com/design/spec/material-design/introduction.html) and [Android Design guidelines](https://developer.android.com/design/index.html) inside one library. 
 
## Dimens

**Pattern:**
```
R.dimen.material_[layout|component]_[keylines|button|...]

R.color.material_[red|blue|...]_[500|800|...]
```
 
## Usage
Just add the dependency to your `build.gradle`:
```
compile 'com.dmitrymalkovich.android:material-design-dimens:1.0'
```

**Examples**
```xml
R.dimen.material_layout_keylines_screen_edge_margin 16dp
R.dimen.material_layout_keylines_content_left_margin_from_screen_edge 72dp
R.dimen.material_layout_vertical_spacing_between_content_areas 8dp
R.dimen.material_layout_horizontal_spacing_between_content_areas 16dp
```

```xml
R.dimen.material_component_floating_action_button_margin 16dp
R.dimen.material_component_button_height 36dp
R.dimen.material_component_button_touchable_target_height 48dp
```

```xml
R.color.material_blue_500 #2196F3
R.color.material_blue_accent_100 #82B1FF
```

#### Layout

* Keylines
* Spacing
* ... (More comming soon)

#### Components

* Bottom sheet
* Button
* Floating Action Button
* Card
* Dialog
* Grid list
* List
* Progress & activity
* Text field
* Toolbar
* ... (More comming soon)

## Contributing

Want to add your favorites dimens, just make pull request! 

## License

Copyright 2016 Dmitry Malkovich

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
