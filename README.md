<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

TODO: You can create tabs and sub_tabs using the TabBar widget and you can use this widget for custom your tab-slide-box with your requirement.

## Features

TODO: Create beautiful TabSlideBox.

## Getting started

TODO: You can use TabBar Function.

## Usage

TODO: You can create tabs sub tabs. 

##  How to use it.

the usage is very simple, just use the following

```dart
 RoundedTabbarWidget(
      tabIcons: [
        Icons.home,
        Icons.favorite,
        Icons.chat,
        Icons.person,
      ],
      pages: [
        HomePageWidget(),
        FavoritePageWidget(),
        MessagesPageWidget(),
        ProfilePageWidget(),
      ],
      selectedIndex: 0,
      onTabItemIndexChanged: (int index) {
        print('Index: $index');
      },
    ),
```

## parameters

| parameter                  | description                                                                           | default                                                                                                                                                                               |
| -------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| onTabItemIndexChanged                       | Completion Handler which returns index of current tab page                                                                  |     (int index) {}                                                                                                                                                                              |
| tabIcons          | List of Tab Icons                                            | Pass List of IconData parameter                                                                                                                                                    |
| pages          | List of Tab Pages                                            | Pass List of Tab widgets parameter                                                                                                                                                    |
| selectedIndex          | Index of tab page to be shown selected initially                                            | This is a optional parameter                                                                                                                                                    |
| itemNormalColor          | Color of Tabbar item for normal state                                            | This is a optional parameter                                                                                                                                                    |
| itemSelectedColor          | Color of Tabbar item for selected state                                            | This is a optional parameter                                                                                                                                                    |
| tabBarBackgroundColor          | Background color of Tabbar                                            | This is a optional parameter                                                                                                                                                    |

## Additional information

TODO: You can create tabs and sub_tabs using the TabBar widget and you can use this widget for custom your tab-slide-box with your requirement.
