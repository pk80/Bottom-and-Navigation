# Navigation and Bottom

- Reference video link : https://youtu.be/3VIzc_uhUCQ
- Reference for floating action button on bottom app
  bar : https://www.geeksforgeeks.org/how-to-add-a-floating-action-button-to-bottom-navigation-bar-in-android/

## Prerequisites

- colors
- strings
- themes (make sure parent is set to no action bar)
- build gradle app (add viewBindings under buildFeatures)
- drawable resources
    - image (logo)
    - vector assets (home,add,search,delete,menu,person,trending_up,auto_fix_high,devices,fast
      food,shopping_cart,wc,weekend and border)

## Menus

As we are creating two menus:

1. Bottom navigation menu (bottom_menu)
2. Navigation drawer menu (nav_menu)
    - For this we require menu directory with respective menus
    - android resource directory -> menus
3. A layout (nav_header) which is a linear layout

## Main Activity

- Assemble all above in main activity by using drawer layout as parent

## Add fragments
- all click item fragments (Home,Fashion,Electronics,Prime,Cart, etc...)
- 