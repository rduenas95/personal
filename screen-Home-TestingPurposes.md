# Power App Documentation \- TestingPurposes

| Property                   | Value                             |
| -------------------------- | --------------------------------- |
| App Name                   | TestingPurposes                   |
| Documentation generated at | Monday, February 17, 2025 2:36 PM |

- [Overview](index-TestingPurposes.md)
- [App Details](appdetails-TestingPurposes.md)
- [Variables](variables-TestingPurposes.md)
- [DataSources](datasources-TestingPurposes.md)
- [Resources](resources-TestingPurposes.md)
- [Controls](controls-TestingPurposes.md)

## Home

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![screen](resources/screen.png) | Type: screen |

### Design

| Property            | Value                                                                                                                                                                                  |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.MinScreenHeight)                                                                                                                                                   |
| ImagePosition       | ImagePosition.Fit                                                                                                                                                                      |
| LoadingSpinner      | LoadingSpinner.None                                                                                                                                                                    |
| LoadingSpinnerColor | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">App.Theme.Colors.Primary<td style="background-color:#ffcccc; width:50%;">RGBA(56, 96, 178, 1)</td></tr></table> |
| Orientation         | If(Self.Width \< Self.Height, Layout.Vertical, Layout.Horizontal)                                                                                                                      |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= Self.Width)                                                                                              |
| Width               | Max(App.Width, App.MinScreenWidth)                                                                                                                                                     |

### Color Properties

| Property | Value       |
| -------- | ----------- |
| Fill     | Color.White |

### Child & Parent Controls

| Property      | Value      |
| ------------- | ---------- |
| Child Control | Header1    |
| Child Control | Container1 |

## ButtonCanvas3

| Property                                                                                    | Value                                       |
| ------------------------------------------------------------------------------------------- | ------------------------------------------- |
| ![PowerApps\_CoreControls\_ButtonCanvas](resources/PowerApps_CoreControls_ButtonCanvas.png) | Type: PowerApps\_CoreControls\_ButtonCanvas |

### Behavior

| Property | Value                                                                                                                                                       |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Navigate(Screen2)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                            |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"List"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property    | Value                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">57<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">219<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X           | 76                                                                                                                                                         |
| Y           | 56                                                                                                                                                         |
| ZIndex      | 1                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | Container1 |

## Container1

| Property                                                      | Value                       |
| ------------------------------------------------------------- | --------------------------- |
| ![manualLayoutContainer](resources/manualLayoutContainer.png) | Type: manualLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">665<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Manual<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1366<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| X                    | 0                                                                                                                                                                    |
| Y                    | 103                                                                                                                                                                  |
| ZIndex               | 2                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value         |
| -------------- | ------------- |
| Child Control  | ButtonCanvas3 |
| Parent Control | Home          |

## Header1

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![Header](resources/Header.png) | Type: Header |

### Behavior

| Property     | Value                                                                                                                                           |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelectLogo | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property                | Value                                                                                                                                                           |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| IsLogoVisible           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| IsProfilePictureVisible | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| IsTitleVisible          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Title                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">App.ActiveScreen.Name<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| UserEmail               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">User().Email<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| UserImage               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">User().Image<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| UserName                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">User().FullName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |

### Design

| Property    | Value                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">103<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| X           | 0                                                                                                                                                          |
| Y           | 0                                                                                                                                                          |
| ZIndex      | 1                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value |
| -------------- | ----- |
| Parent Control | Home  |
