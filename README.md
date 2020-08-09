# Activitybar Separator

add up to 5 seperators to your activity bar, so you can easily separate/categories your views shortcuts.

<br>

<p align="center">
    <a href="https://user-images.githubusercontent.com/7388088/89729382-71777f00-da35-11ea-9d8b-a949417f1f28.png"><img src="https://user-images.githubusercontent.com/7388088/89729382-71777f00-da35-11ea-9d8b-a949417f1f28.png" alt="Browser Status"/></a>
</p>

<br>

## # How To

we use [viewsContainers](https://code.visualstudio.com/api/references/contribution-points#contributes.viewsContainers) to add the seprators to the activity-bar list which also means that we'll have to create an empty view for that item.

it doesn't affect the usage in anything, except when u press on any of the seperator items, you will open an empty view.
