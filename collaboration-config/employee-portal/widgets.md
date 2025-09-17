# Collaboration widgets
Widgets are small, stand-alone applets that can be embedded into the Employee Portal pages to add interactivity and additional features. Widgets enhance the usability and provide quick access to information.

The **Collaboration** widgets are provided with the Collaboration app. Each installed application can provide additional widgets. For more information on these widgets, see the application-specific documentation.

## Before you begin
* Understand how the [page visibility versions](/esp-config/customize/employee-portal/employee-portal-design#edit-page-details) work.

    ::: note
    Some widgets can only be added to a page where the visibility has been set to [Full User](/esp-config/customize/employee-portal/employee-portal-design#edit-page-details).
    :::

## Workspace widget
Add this widget to display the user's News Feed which shows the latest updates to all the workspaces that they follow. Or select a specific Workspace.

::: note
This widget can only be added to pages where the visibility has been set to [Full User](/esp-config/customize/employee-portal/employee-portal-design#edit-page-details).
:::

#### Configure
* **Show News Feed.** This option lets you show the users news feed. When not selected, you can select an individual workspace to show instead.

#### Style
* **Use Content Height.**
* **Hide if no data is available** This option hides the widget from the page if there is nothing to display.
* **Header.** Define the top banner of the widget.
    * **Header Type.** Choose from Basic, Custom, or No Header.
    * **Label.**
    * **Link.**
* **Body.** Configure the text and background colors of the widget. If no specific color preferences are set in the widget configuration, the style defined in the Employee Portal settings is applied.


## Post widget
Add this widget to display a particular post or the last post from a selected workspace.

::: note
This widget can only be added to pages where the visibility has been set to [Full User](/esp-config/customize/employee-portal/employee-portal-design#edit-page-details).
:::

#### Configure
* **Show specific post.** If you have an important post that you want to always be displayed, select this option and specify the ID of the post.
* **Last post in a workspace.** This option displays only the last post in the selected workspace. There is no option to scroll through previous posts.
* **Post ID.** Add the activity ID of the post you would like to display. To get the post's ID, right-click on the timestamp (e.g.: *1 day ago*) displayed on a post and get a copy of the link. Add this to the Post ID field, removing the leading domain name, up to the URN.
* **Public Workspace.** Select the public workspace you want to use.

#### Style
* **Use Content Height.**
* **Header.** Define the top banner of the widget.
    * **Header Type.** Choose from Basic, Custom, or No Header.
    * **Label.**
    * **Link.**
* **Body.** Configure the text and background colors of the widget. If no specific color preferences are set in the widget configuration, the style defined in the Employee Portal settings is applied.