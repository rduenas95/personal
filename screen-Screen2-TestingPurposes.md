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

## Screen2

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

| Property      | Value            |
| ------------- | ---------------- |
| Child Control | ScreenContainer1 |

## AddNewButton1

| Property                                                                                    | Value                                       |
| ------------------------------------------------------------------------------------------- | ------------------------------------------- |
| ![PowerApps\_CoreControls\_ButtonCanvas](resources/PowerApps_CoreControls_ButtonCanvas.png) | Type: PowerApps\_CoreControls\_ButtonCanvas |

### Behavior

| Property | Value                                                                                                                                                                                      |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">NewForm(Form1); UpdateContext({ newMode: true })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property      | Value                                                                                                                                                                           |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Left<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Appearance    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'ButtonCanvas.Appearance'.Transparent<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| FontSize      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">14<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| Icon          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Add"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Text          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"New"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| VerticalAlign | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">VerticalAlign.Middle<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |

### Design

| Property    | Value                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X           | 0                                                                                                                                                          |
| Y           | 0                                                                                                                                                          |
| ZIndex      | 15                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | AddNewContainer1 |

## AddNewContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                                    |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                           |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                             |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                              |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Visible              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Screen2.Size = ScreenSize.Small,true,false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                            |
| X                    | 0                                                                                                                                                                                        |
| Y                    | 0                                                                                                                                                                                        |
| ZIndex               | 14                                                                                                                                                                                       |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | AddNewButton1     |
| Parent Control | SidebarContainer1 |

## Assigned to\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                                          |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AssignedTo0"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                        |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Assigned to'<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                               |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'],DataSourceInfo.DisplayName,'AssignedTo0')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue7.Selected<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                              |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">459<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 0                                                                                                                                                            |
| Y           | 3                                                                                                                                                            |
| ZIndex      | 26                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | App.Theme.Colors.Darker40                                                                                                                                                                                                                                                                                                            |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible7   |
| Child Control  | DataCardKey7   |
| Child Control  | DataCardValue7 |
| Child Control  | ErrorMessage7  |
| Parent Control | Form1          |

## Assigned to1

| Property                                                                                 | Value                                     |
| ---------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerAppsOneGridTemplate\_dataField](resources/PowerAppsOneGridTemplate_dataField.png) | Type: PowerAppsOneGridTemplate\_dataField |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Assigned to"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AssignedTo0"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| FieldType        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"E"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |

### Design

| Property | Value                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| X        | 0                                                                                                                                             |
| Y        | 0                                                                                                                                             |
| ZIndex   | 35                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value  |
| -------------- | ------ |
| Parent Control | Table1 |

## BackIcon1

| Property                                                                                    | Value                                       |
| ------------------------------------------------------------------------------------------- | ------------------------------------------- |
| ![PowerApps\_CoreControls\_ButtonCanvas](resources/PowerApps_CoreControls_ButtonCanvas.png) | Type: PowerApps\_CoreControls\_ButtonCanvas |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                           |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ResetForm(Form1); UpdateContext({ newMode: false, editMode: false, CurrentItem: First(Table1.SelectedItems), isItemSelected:false });<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property   | Value                                                                                                                                                                           |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Appearance | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'ButtonCanvas.Appearance'.Transparent<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Icon       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ArrowLeft"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Layout     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'ButtonCanvas.Layout'.IconBefore<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Text       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Back"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |

### Design

| Property    | Value                                                                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                   |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                 |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(And(Screen2.Size = ScreenSize.Small, !deleteMode), true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Screen2.Size = ScreenSize.Small, 75, 96)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X           | 0                                                                                                                                                                                                            |
| Y           | 0                                                                                                                                                                                                            |
| ZIndex      | 20                                                                                                                                                                                                           |

### Color Properties

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | Container21 |

## BodyContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingBottom        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| PaddingTop           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 4                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                         |
| -------------- | ----------------------------- |
| Child Control  | DeleteConfirmDialogContainer1 |
| Child Control  | SidebarContainer1             |
| Child Control  | RightContainer1               |
| Parent Control | ScreenContainer1              |

## ButtonContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.End<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Scroll<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">24<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 26                                                                                                                                                                   |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | CancelButton1  |
| Child Control  | SubmitButton1  |
| Parent Control | MainContainer1 |

## CancelButton1

| Property                                                                                    | Value                                       |
| ------------------------------------------------------------------------------------------- | ------------------------------------------- |
| ![PowerApps\_CoreControls\_ButtonCanvas](resources/PowerApps_CoreControls_ButtonCanvas.png) | Type: PowerApps\_CoreControls\_ButtonCanvas |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                           |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ResetForm(Form1); UpdateContext({ newMode: false, editMode: false, CurrentItem: First(Table1.SelectedItems), isItemSelected:false });<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property   | Value                                                                                                                                                                         |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Appearance | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'ButtonCanvas.Appearance'.Secondary<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Cancel"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |

### Design

| Property    | Value                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">96<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X           | 0                                                                                                                                                          |
| Y           | 0                                                                                                                                                          |
| ZIndex      | 27                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | ButtonContainer1 |

## CancelDeleteButton1

| Property                                                                                    | Value                                       |
| ------------------------------------------------------------------------------------------- | ------------------------------------------- |
| ![PowerApps\_CoreControls\_ButtonCanvas](resources/PowerApps_CoreControls_ButtonCanvas.png) | Type: PowerApps\_CoreControls\_ButtonCanvas |

### Behavior

| Property | Value                                                                                                                                                                          |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ deleteMode: false })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                                         |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Cancel"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Appearance      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'ButtonCanvas.Appearance'.Secondary<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Cancel"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |

### Design

| Property    | Value                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">96<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X           | 0                                                                                                                                                          |
| Y           | 0                                                                                                                                                          |
| ZIndex      | 11                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value                            |
| -------------- | -------------------------------- |
| Parent Control | ConfirmDeleteButtonBarContainer1 |

## ConfirmDeleteButton1

| Property                                                                                    | Value                                       |
| ------------------------------------------------------------------------------------------- | ------------------------------------------- |
| ![PowerApps\_CoreControls\_ButtonCanvas](resources/PowerApps_CoreControls_ButtonCanvas.png) | Type: PowerApps\_CoreControls\_ButtonCanvas |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                                                                                                   |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Remove( Table(), 'Work tracker / Testing' ); If( IsEmpty( Errors( Table(), selectedRecord ) ), UpdateContext( { CurrentItem: First(Table()), isItemSelected: false, newMode: false, deleteMode: false } ) ); <td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                              |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Delete"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Delete"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property    | Value                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">96<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X           | 0                                                                                                                                                          |
| Y           | 0                                                                                                                                                          |
| ZIndex      | 10                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value                            |
| -------------- | -------------------------------- |
| Parent Control | ConfirmDeleteButtonBarContainer1 |

## ConfirmDeleteButtonBarContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                 |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| X                    | 0                                                                                                                                                                     |
| Y                    | 0                                                                                                                                                                     |
| ZIndex               | 9                                                                                                                                                                     |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                         |
| -------------- | ----------------------------- |
| Child Control  | ConfirmDeleteButton1          |
| Child Control  | CancelDeleteButton1           |
| Parent Control | DeleteConfirmDialogContainer1 |

## ConfirmDeleteLabelContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.End<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingBottom        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">20<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 7                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                         |
| -------------- | ----------------------------- |
| Child Control  | TextCanvas1                   |
| Parent Control | DeleteConfirmDialogContainer1 |

## Container2

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">60<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 18                                                                                                                                                                   |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Child Control  | Container21     |
| Parent Control | RightContainer1 |

## Container21

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                              |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                        |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Screen2.Size = ScreenSize.Small,8,12)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X                    | 0                                                                                                                                                                                  |
| Y                    | 0                                                                                                                                                                                  |
| ZIndex               | 19                                                                                                                                                                                 |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | BackIcon1        |
| Child Control  | NewRecordButton1 |
| Child Control  | EditButton1      |
| Child Control  | DeleteButton1    |
| Parent Control | Container2       |

## DataCardKey1

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Weight   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Weight'.Semibold<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |

### Design

| Property    | Value                                                                                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X           | 24                                                                                                                                                          |
| Y           | 10                                                                                                                                                          |
| ZIndex      | 1                                                                                                                                                           |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | Title\_DataCard1 |

## DataCardKey2

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Weight   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Weight'.Semibold<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |

### Design

| Property    | Value                                                                                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X           | 24                                                                                                                                                          |
| Y           | 10                                                                                                                                                          |
| ZIndex      | 1                                                                                                                                                           |

### Color Properties

### Child & Parent Controls

| Property       | Value                  |
| -------------- | ---------------------- |
| Parent Control | Description\_DataCard1 |

## DataCardKey3

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Weight   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Weight'.Semibold<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |

### Design

| Property    | Value                                                                                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X           | 24                                                                                                                                                          |
| Y           | 10                                                                                                                                                          |
| ZIndex      | 1                                                                                                                                                           |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Progress\_DataCard1 |

## DataCardKey4

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Weight   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Weight'.Semibold<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |

### Design

| Property    | Value                                                                                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X           | 24                                                                                                                                                          |
| Y           | 10                                                                                                                                                          |
| ZIndex      | 1                                                                                                                                                           |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Priority\_DataCard1 |

## DataCardKey5

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Weight   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Weight'.Semibold<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |

### Design

| Property    | Value                                                                                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X           | 24                                                                                                                                                          |
| Y           | 10                                                                                                                                                          |
| ZIndex      | 1                                                                                                                                                           |

### Color Properties

### Child & Parent Controls

| Property       | Value                 |
| -------------- | --------------------- |
| Parent Control | Start date\_DataCard1 |

## DataCardKey6

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Weight   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Weight'.Semibold<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |

### Design

| Property    | Value                                                                                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X           | 24                                                                                                                                                          |
| Y           | 10                                                                                                                                                          |
| ZIndex      | 1                                                                                                                                                           |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Due date\_DataCard1 |

## DataCardKey7

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Weight   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Weight'.Semibold<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |

### Design

| Property    | Value                                                                                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X           | 24                                                                                                                                                          |
| Y           | 10                                                                                                                                                          |
| ZIndex      | 1                                                                                                                                                           |

### Color Properties

### Child & Parent Controls

| Property       | Value                  |
| -------------- | ---------------------- |
| Parent Control | Assigned to\_DataCard1 |

## DataCardKey8

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Weight   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Weight'.Semibold<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |

### Design

| Property    | Value                                                                                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X           | 24                                                                                                                                                          |
| Y           | 10                                                                                                                                                          |
| ZIndex      | 1                                                                                                                                                           |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | Notes\_DataCard1 |

## DataCardValue1

| Property                                                                                          | Value                                          |
| ------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| ![PowerApps\_CoreControls\_TextInputCanvas](resources/PowerApps_CoreControls_TextInputCanvas.png) | Type: PowerApps\_CoreControls\_TextInputCanvas |

### Data

| Property        | Value                                                                                                                                                                                      |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Mode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"'TextInputCanvas.Mode'.TextInputModeSingleLine"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Required<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| ValidationState | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(IsBlank(Parent.Error), "None", "Error")<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| Value           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Default<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| X           | 24                                                                                                                                                           |
| Y           | DataCardKey1.Y + DataCardKey1.Height + 4                                                                                                                     |
| ZIndex      | 2                                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | Title\_DataCard1 |

## DataCardValue2

| Property                                                                                          | Value                                          |
| ------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| ![PowerApps\_CoreControls\_TextInputCanvas](resources/PowerApps_CoreControls_TextInputCanvas.png) | Type: PowerApps\_CoreControls\_TextInputCanvas |

### Data

| Property        | Value                                                                                                                                                                                      |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Mode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"'TextInputCanvas.Mode'.TextInputModeSingleLine"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Required<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| ValidationState | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(IsBlank(Parent.Error), "None", "Error")<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| Value           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Default<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| X           | 24                                                                                                                                                           |
| Y           | DataCardKey2.Y + DataCardKey2.Height + 4                                                                                                                     |
| ZIndex      | 2                                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value                  |
| -------------- | ---------------------- |
| Parent Control | Description\_DataCard1 |

## DataCardValue3

| Property                                                                                        | Value                                         |
| ----------------------------------------------------------------------------------------------- | --------------------------------------------- |
| ![PowerApps\_CoreControls\_ComboboxCanvas](resources/PowerApps_CoreControls_ComboboxCanvas.png) | Type: PowerApps\_CoreControls\_ComboboxCanvas |

### Data

| Property             | Value                                                                                                                                                                                     |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| DefaultSelectedItems | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">[Parent.Default]<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Items                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Choices([@'Work tracker / Testing'].'Progress')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Required<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| ValidationState      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(IsBlank(Parent.Error), "None", "Error")<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| X           | 24                                                                                                                                                           |
| Y           | DataCardKey3.Y + DataCardKey3.Height + 4                                                                                                                     |
| ZIndex      | 2                                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Progress\_DataCard1 |

## DataCardValue4

| Property                                                                                        | Value                                         |
| ----------------------------------------------------------------------------------------------- | --------------------------------------------- |
| ![PowerApps\_CoreControls\_ComboboxCanvas](resources/PowerApps_CoreControls_ComboboxCanvas.png) | Type: PowerApps\_CoreControls\_ComboboxCanvas |

### Data

| Property             | Value                                                                                                                                                                                     |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| DefaultSelectedItems | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">[Parent.Default]<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Items                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Choices([@'Work tracker / Testing'].'Priority')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Required<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| ValidationState      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(IsBlank(Parent.Error), "None", "Error")<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| X           | 24                                                                                                                                                           |
| Y           | DataCardKey4.Y + DataCardKey4.Height + 4                                                                                                                     |
| ZIndex      | 2                                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Priority\_DataCard1 |

## DataCardValue5

| Property                                                                                            | Value                                           |
| --------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| ![PowerApps\_CoreControls\_DatePickerCanvas](resources/PowerApps_CoreControls_DatePickerCanvas.png) | Type: PowerApps\_CoreControls\_DatePickerCanvas |

### Data

| Property        | Value                                                                                                                                                                                |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| EndDate         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Date(Year(Today())+100, 12, 31)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Required        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Required<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| SelectedDate    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Default<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| StartDate       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Date(1900, 1, 1)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| ValidationState | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(IsBlank(Parent.Error), "None", "Error")<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| X           | 24                                                                                                                                                           |
| Y           | DataCardKey5.Y + DataCardKey5.Height + 4                                                                                                                     |
| ZIndex      | 2                                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value                 |
| -------------- | --------------------- |
| Parent Control | Start date\_DataCard1 |

## DataCardValue6

| Property                                                                                            | Value                                           |
| --------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| ![PowerApps\_CoreControls\_DatePickerCanvas](resources/PowerApps_CoreControls_DatePickerCanvas.png) | Type: PowerApps\_CoreControls\_DatePickerCanvas |

### Data

| Property        | Value                                                                                                                                                                                |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| EndDate         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Date(Year(Today())+100, 12, 31)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Required        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Required<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| SelectedDate    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Default<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| StartDate       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Date(1900, 1, 1)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| ValidationState | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(IsBlank(Parent.Error), "None", "Error")<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| X           | 24                                                                                                                                                           |
| Y           | DataCardKey6.Y + DataCardKey6.Height + 4                                                                                                                     |
| ZIndex      | 2                                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Due date\_DataCard1 |

## DataCardValue7

| Property                                                                                        | Value                                         |
| ----------------------------------------------------------------------------------------------- | --------------------------------------------- |
| ![PowerApps\_CoreControls\_ComboboxCanvas](resources/PowerApps_CoreControls_ComboboxCanvas.png) | Type: PowerApps\_CoreControls\_ComboboxCanvas |

### Data

| Property             | Value                                                                                                                                                                                        |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| DefaultSelectedItems | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">[Parent.Default]<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| Items                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Choices([@'Work tracker / Testing'].'AssignedTo0')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Required<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| ValidationState      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(IsBlank(Parent.Error), "None", "Error")<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| X           | 24                                                                                                                                                           |
| Y           | DataCardKey7.Y + DataCardKey7.Height + 4                                                                                                                     |
| ZIndex      | 2                                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value                  |
| -------------- | ---------------------- |
| Parent Control | Assigned to\_DataCard1 |

## DataCardValue8

| Property                                                                                          | Value                                          |
| ------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| ![PowerApps\_CoreControls\_TextInputCanvas](resources/PowerApps_CoreControls_TextInputCanvas.png) | Type: PowerApps\_CoreControls\_TextInputCanvas |

### Data

| Property        | Value                                                                                                                                                                                      |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayName<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Mode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"'TextInputCanvas.Mode'.TextInputModeSingleLine"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Required<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| ValidationState | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(IsBlank(Parent.Error), "None", "Error")<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| Value           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Default<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| X           | 24                                                                                                                                                           |
| Y           | DataCardKey8.Y + DataCardKey8.Height + 4                                                                                                                     |
| ZIndex      | 2                                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | Notes\_DataCard1 |

## DeleteButton1

| Property                                                                                    | Value                                       |
| ------------------------------------------------------------------------------------------- | ------------------------------------------- |
| ![PowerApps\_CoreControls\_ButtonCanvas](resources/PowerApps_CoreControls_ButtonCanvas.png) | Type: PowerApps\_CoreControls\_ButtonCanvas |

### Behavior

| Property | Value                                                                                                                                                                                                          |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ deleteMode: true, selectedRecord: Table1.Selected })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property   | Value                                                                                                                                                                           |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Appearance | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'ButtonCanvas.Appearance'.Transparent<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Icon       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Delete"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Text       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Delete"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |

### Design

| Property    | Value                                                                                                                                                                                 |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!newMode, !deleteMode)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Screen2.Size = ScreenSize.Small, 75, 70)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X           | 0                                                                                                                                                                                     |
| Y           | 0                                                                                                                                                                                     |
| ZIndex      | 23                                                                                                                                                                                    |

### Color Properties

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | Container21 |

## DeleteConfirmDialogContainer1

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                 |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(deleteMode, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| X                    | 0                                                                                                                                                                     |
| Y                    | 0                                                                                                                                                                     |
| ZIndex               | 6                                                                                                                                                                     |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                            |
| -------------- | -------------------------------- |
| Child Control  | ConfirmDeleteLabelContainer1     |
| Child Control  | ConfirmDeleteButtonBarContainer1 |
| Parent Control | BodyContainer1                   |

## Description\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                                          |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Description"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                        |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Description<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                 |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'],DataSourceInfo.DisplayName,'Description')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| MaxLength   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'], DataSourceInfo.MaxLength, 'Description')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue2.Value<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                 |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">459<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 1                                                                                                                                                            |
| Y           | 0                                                                                                                                                            |
| ZIndex      | 26                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | App.Theme.Colors.Darker40                                                                                                                                                                                                                                                                                                            |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible2   |
| Child Control  | DataCardKey2   |
| Child Control  | DataCardValue2 |
| Child Control  | ErrorMessage2  |
| Parent Control | Form1          |

## Due date\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                                      |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"DueDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                        |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Due date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                              |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'],DataSourceInfo.DisplayName,'DueDate')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                            |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue6.SelectedDate<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                      |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">459<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 1                                                                                                                                                            |
| Y           | 2                                                                                                                                                            |
| ZIndex      | 26                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | App.Theme.Colors.Darker40                                                                                                                                                                                                                                                                                                            |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible6   |
| Child Control  | DataCardKey6   |
| Child Control  | DataCardValue6 |
| Child Control  | ErrorMessage6  |
| Parent Control | Form1          |

## Due date1

| Property                                                                                 | Value                                     |
| ---------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerAppsOneGridTemplate\_dataField](resources/PowerAppsOneGridTemplate_dataField.png) | Type: PowerAppsOneGridTemplate\_dataField |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Due date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"DueDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldType        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"D"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">7<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |

### Design

| Property | Value                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| X        | 0                                                                                                                                             |
| Y        | 0                                                                                                                                             |
| ZIndex   | 34                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value  |
| -------------- | ------ |
| Parent Control | Table1 |

## EditButton1

| Property                                                                                    | Value                                       |
| ------------------------------------------------------------------------------------------- | ------------------------------------------- |
| ![PowerApps\_CoreControls\_ButtonCanvas](resources/PowerApps_CoreControls_ButtonCanvas.png) | Type: PowerApps\_CoreControls\_ButtonCanvas |

### Behavior

| Property | Value                                                                                                                                                                                                        |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ editMode: true, selectedRecord: Table1.Selected })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property   | Value                                                                                                                                                                           |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Appearance | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'ButtonCanvas.Appearance'.Transparent<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Icon       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Edit"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Text       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Edit"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |

### Design

| Property    | Value                                                                                                                                                                                 |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!newMode, !deleteMode)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Screen2.Size = ScreenSize.Small, 75, 90)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| X           | 0                                                                                                                                                                                     |
| Y           | 0                                                                                                                                                                                     |
| ZIndex      | 22                                                                                                                                                                                    |

### Color Properties

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | Container21 |

## ErrorMessage1

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property    | Value                                                                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                 |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                               |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!IsBlank(Parent.Error), Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                |
| X           | 24                                                                                                                                                                                                         |
| Y           | DataCardValue1.Y + DataCardValue1.Height                                                                                                                                                                   |
| ZIndex      | 3                                                                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | Title\_DataCard1 |

## ErrorMessage2

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property    | Value                                                                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                 |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                               |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!IsBlank(Parent.Error), Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                |
| X           | 24                                                                                                                                                                                                         |
| Y           | DataCardValue2.Y + DataCardValue2.Height                                                                                                                                                                   |
| ZIndex      | 3                                                                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value                  |
| -------------- | ---------------------- |
| Parent Control | Description\_DataCard1 |

## ErrorMessage3

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property    | Value                                                                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                 |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                               |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!IsBlank(Parent.Error), Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                |
| X           | 24                                                                                                                                                                                                         |
| Y           | DataCardValue3.Y + DataCardValue3.Height                                                                                                                                                                   |
| ZIndex      | 3                                                                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Progress\_DataCard1 |

## ErrorMessage4

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property    | Value                                                                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                 |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                               |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!IsBlank(Parent.Error), Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                |
| X           | 24                                                                                                                                                                                                         |
| Y           | DataCardValue4.Y + DataCardValue4.Height                                                                                                                                                                   |
| ZIndex      | 3                                                                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Priority\_DataCard1 |

## ErrorMessage5

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property    | Value                                                                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                 |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                               |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!IsBlank(Parent.Error), Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                |
| X           | 24                                                                                                                                                                                                         |
| Y           | DataCardValue5.Y + DataCardValue5.Height                                                                                                                                                                   |
| ZIndex      | 3                                                                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value                 |
| -------------- | --------------------- |
| Parent Control | Start date\_DataCard1 |

## ErrorMessage6

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property    | Value                                                                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                 |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                               |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!IsBlank(Parent.Error), Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                |
| X           | 24                                                                                                                                                                                                         |
| Y           | DataCardValue6.Y + DataCardValue6.Height                                                                                                                                                                   |
| ZIndex      | 3                                                                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Due date\_DataCard1 |

## ErrorMessage7

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property    | Value                                                                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                 |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                               |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!IsBlank(Parent.Error), Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                |
| X           | 24                                                                                                                                                                                                         |
| Y           | DataCardValue7.Y + DataCardValue7.Height                                                                                                                                                                   |
| ZIndex      | 3                                                                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value                  |
| -------------- | ---------------------- |
| Parent Control | Assigned to\_DataCard1 |

## ErrorMessage8

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Error<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Wrap     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |

### Design

| Property    | Value                                                                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                 |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                               |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(!IsBlank(Parent.Error), Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                |
| X           | 24                                                                                                                                                                                                         |
| Y           | DataCardValue8.Y + DataCardValue8.Height                                                                                                                                                                   |
| ZIndex      | 3                                                                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | Notes\_DataCard1 |

## Form1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![form](resources/form.png) | Type: form |

### Behavior

| Property  | Value                                                                                                                                                                                                                                                                        |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnFailure | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Notify("Cannot save. Please check if there are errors in the form.", NotificationType.Error)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                       |
| OnSuccess | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ CurrentItem: Self.LastSubmit, isItemSelected: false});Notify("Success",NotificationType.Success);ResetForm(Form1) <td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property         | Value                                                                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DataSource       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'Work tracker / Testing'<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                       |
| DefaultMode      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(newMode, FormMode.New, editMode, FormMode.Edit, FormMode.View)<td style="background-color:#ffcccc; width:50%;">FormMode.Edit</td></tr></table> |
| Item             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">CurrentItem<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                    |
| UseFluentV9Cards | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                           |

### Design

| Property        | Value                                                                                                                                                                       |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| Height          | 500                                                                                                                                                                         |
| NumberOfColumns | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Width           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;">800</td></tr></table>                   |
| X               | 0                                                                                                                                                                           |
| Y               | 0                                                                                                                                                                           |
| ZIndex          | 25                                                                                                                                                                          |

### Color Properties

| Property           | Value                                                                                                           |
| ------------------ | --------------------------------------------------------------------------------------------------------------- |
| BorderColor        | App.Theme.Colors.Darker40                                                                                       |
| Fill               | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table> |
| FocusedBorderColor | Self.BorderColor                                                                                                |

### Child & Parent Controls

| Property       | Value                  |
| -------------- | ---------------------- |
| Child Control  | Title\_DataCard1       |
| Child Control  | Description\_DataCard1 |
| Child Control  | Progress\_DataCard1    |
| Child Control  | Priority\_DataCard1    |
| Child Control  | Start date\_DataCard1  |
| Child Control  | Due date\_DataCard1    |
| Child Control  | Assigned to\_DataCard1 |
| Child Control  | Notes\_DataCard1       |
| Parent Control | MainContainer1         |

## Header2

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![Header](resources/Header.png) | Type: Header |

### Behavior

| Property     | Value                                                                                                                                           |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelectLogo | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property                | Value                                                                                                                                                     |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| IsLogoVisible           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| IsProfilePictureVisible | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| IsTitleVisible          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Title                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Work"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| UserEmail               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">User().Email<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| UserImage               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">User().Image<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| UserName                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">User().FullName<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property    | Value                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">75<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| X           | 0                                                                                                                                                          |
| Y           | 0                                                                                                                                                          |
| ZIndex      | 3                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | HeaderContainer1 |

## HeaderContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">68<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">6<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 2                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | App.Theme.Colors.Primary                                                                                                                                                                                                                                                                                                             |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | Header2          |
| Parent Control | ScreenContainer1 |

## MainContainer1

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Scroll<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingTop           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">8<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 24                                                                                                                                                                   |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | Form1            |
| Child Control  | ButtonContainer1 |
| Parent Control | RightContainer1  |

## NewRecordButton1

| Property                                                                                    | Value                                       |
| ------------------------------------------------------------------------------------------- | ------------------------------------------- |
| ![PowerApps\_CoreControls\_ButtonCanvas](resources/PowerApps_CoreControls_ButtonCanvas.png) | Type: PowerApps\_CoreControls\_ButtonCanvas |

### Behavior

| Property | Value                                                                                                                                                                                      |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">NewForm(Form1); UpdateContext({ newMode: true })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property   | Value                                                                                                                                                                       |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Appearance | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'ButtonCanvas.Appearance'.Primary<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Icon       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Add"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| Text       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"New"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |

### Design

| Property    | Value                                                                                                                                                                                                            |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                       |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                     |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Screen2.Size = ScreenSize.Small, false, And(!newMode, !deleteMode))<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Screen2.Size = ScreenSize.Small, 75, 96)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| X           | 0                                                                                                                                                                                                                |
| Y           | 0                                                                                                                                                                                                                |
| ZIndex      | 21                                                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | Container21 |

## Notes\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                                    |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Notes"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                        |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Notes<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                 |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'],DataSourceInfo.DisplayName,'Notes')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| MaxLength   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'], DataSourceInfo.MaxLength, 'Notes')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                          |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue8.Value<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                           |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">459<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 1                                                                                                                                                            |
| Y           | 3                                                                                                                                                            |
| ZIndex      | 26                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | App.Theme.Colors.Darker40                                                                                                                                                                                                                                                                                                            |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible8   |
| Child Control  | DataCardKey8   |
| Child Control  | DataCardValue8 |
| Child Control  | ErrorMessage8  |
| Parent Control | Form1          |

## Notes1

| Property                                                                                 | Value                                     |
| ---------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerAppsOneGridTemplate\_dataField](resources/PowerAppsOneGridTemplate_dataField.png) | Type: PowerAppsOneGridTemplate\_dataField |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Notes"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Notes"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldType        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"s"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">8<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |

### Design

| Property | Value                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| X        | 0                                                                                                                                             |
| Y        | 0                                                                                                                                             |
| ZIndex   | 36                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value  |
| -------------- | ------ |
| Parent Control | Table1 |

## Priority\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Priority"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                        |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Priority<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                 |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'],DataSourceInfo.DisplayName,'Priority')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                             |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue4.Selected<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                           |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">459<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 1                                                                                                                                                            |
| Y           | 1                                                                                                                                                            |
| ZIndex      | 26                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | App.Theme.Colors.Darker40                                                                                                                                                                                                                                                                                                            |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible4   |
| Child Control  | DataCardKey4   |
| Child Control  | DataCardValue4 |
| Child Control  | ErrorMessage4  |
| Parent Control | Form1          |

## Priority1

| Property                                                                                 | Value                                     |
| ---------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerAppsOneGridTemplate\_dataField](resources/PowerAppsOneGridTemplate_dataField.png) | Type: PowerAppsOneGridTemplate\_dataField |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Priority"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Priority"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| FieldType        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"E"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |

### Design

| Property | Value                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| X        | 0                                                                                                                                             |
| Y        | 0                                                                                                                                             |
| ZIndex   | 32                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value  |
| -------------- | ------ |
| Parent Control | Table1 |

## Progress\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Progress"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                        |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Progress<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                 |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'],DataSourceInfo.DisplayName,'Progress')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                             |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue3.Selected<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                           |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">459<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 0                                                                                                                                                            |
| Y           | 1                                                                                                                                                            |
| ZIndex      | 26                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | App.Theme.Colors.Darker40                                                                                                                                                                                                                                                                                                            |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible3   |
| Child Control  | DataCardKey3   |
| Child Control  | DataCardValue3 |
| Child Control  | ErrorMessage3  |
| Parent Control | Form1          |

## Progress1

| Property                                                                                 | Value                                     |
| ---------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerAppsOneGridTemplate\_dataField](resources/PowerAppsOneGridTemplate_dataField.png) | Type: PowerAppsOneGridTemplate\_dataField |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Progress"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Progress"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| FieldType        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"E"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">3<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |

### Design

| Property | Value                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| X        | 0                                                                                                                                             |
| Y        | 0                                                                                                                                             |
| ZIndex   | 31                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value  |
| -------------- | ------ |
| Parent Control | Table1 |

## RightContainer1

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                                                                                      |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                             |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                 |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                  |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                              |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Stretch<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                         |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                         |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                               |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                       |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                  |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                              |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                              |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                            |
| PaddingBottom        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                |
| Visible              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Or(deleteMode, And(Screen2.Size = ScreenSize.Small, !newMode, !isItemSelected)), false, true)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                |
| X                    | 0                                                                                                                                                                                                                                          |
| Y                    | 0                                                                                                                                                                                                                                          |
| ZIndex               | 17                                                                                                                                                                                                                                         |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | Container2     |
| Child Control  | MainContainer1 |
| Parent Control | BodyContainer1 |

## ScreenContainer1

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Stretch<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingBottom        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| PaddingTop           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 1                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | HeaderContainer1 |
| Child Control  | BodyContainer1   |
| Parent Control | Screen2          |

## SearchContainer1

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 12                                                                                                                                                                   |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(245, 245, 245, 1)</td></tr><tr><td style="background-color:#F5F5F5"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | SearchInput1      |
| Parent Control | SidebarContainer1 |

## SearchInput1

| Property                                                                                          | Value                                          |
| ------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| ![PowerApps\_CoreControls\_TextInputCanvas](resources/PowerApps_CoreControls_TextInputCanvas.png) | Type: PowerApps\_CoreControls\_TextInputCanvas |

### Data

| Property    | Value                                                                                                                                              |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Placeholder | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Search"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property    | Value                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">320<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X           | 0                                                                                                                                                          |
| Y           | 0                                                                                                                                                          |
| ZIndex      | 13                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | SearchContainer1 |

## SidebarContainer1

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                                                                        |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                  |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                               |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                   |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.Light<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                   |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                             |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                           |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                 |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                         |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                    |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                              |
| PaddingBottom        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                 |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                 |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                 |
| PaddingTop           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                 |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                  |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                  |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                  |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                  |
| Visible              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(And(Screen2.Size = ScreenSize.Small, Or(newMode, isItemSelected)), false, true)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| X                    | 0                                                                                                                                                                                                                            |
| Y                    | 0                                                                                                                                                                                                                            |
| ZIndex               | 5                                                                                                                                                                                                                            |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | AddNewContainer1 |
| Child Control  | SearchContainer1 |
| Child Control  | Table1           |
| Parent Control | BodyContainer1   |

## Start date\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                                        |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"StartDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                        |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Start date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                              |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'],DataSourceInfo.DisplayName,'StartDate')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                              |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue5.SelectedDate<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">459<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 0                                                                                                                                                            |
| Y           | 2                                                                                                                                                            |
| ZIndex      | 26                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | App.Theme.Colors.Darker40                                                                                                                                                                                                                                                                                                            |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible5   |
| Child Control  | DataCardKey5   |
| Child Control  | DataCardValue5 |
| Child Control  | ErrorMessage5  |
| Parent Control | Form1          |

## Start date1

| Property                                                                                 | Value                                     |
| ---------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerAppsOneGridTemplate\_dataField](resources/PowerAppsOneGridTemplate_dataField.png) | Type: PowerAppsOneGridTemplate\_dataField |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Start date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"StartDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| FieldType        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"D"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">6<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |

### Design

| Property | Value                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| X        | 0                                                                                                                                             |
| Y        | 0                                                                                                                                             |
| ZIndex   | 33                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value  |
| -------------- | ------ |
| Parent Control | Table1 |

## StarVisible1

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                               |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Align'.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |

### Design

| Property    | Value                                                                                                                                                                                               |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| X           | 0                                                                                                                                                                                                   |
| Y           | DataCardKey1.Y                                                                                                                                                                                      |
| ZIndex      | 4                                                                                                                                                                                                   |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | Title\_DataCard1 |

## StarVisible2

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                               |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Align'.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |

### Design

| Property    | Value                                                                                                                                                                                               |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| X           | 0                                                                                                                                                                                                   |
| Y           | DataCardKey2.Y                                                                                                                                                                                      |
| ZIndex      | 4                                                                                                                                                                                                   |

### Color Properties

### Child & Parent Controls

| Property       | Value                  |
| -------------- | ---------------------- |
| Parent Control | Description\_DataCard1 |

## StarVisible3

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                               |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Align'.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |

### Design

| Property    | Value                                                                                                                                                                                               |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">20<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| X           | 0                                                                                                                                                                                                   |
| Y           | DataCardKey3.Y                                                                                                                                                                                      |
| ZIndex      | 4                                                                                                                                                                                                   |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Progress\_DataCard1 |

## StarVisible4

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                               |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Align'.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |

### Design

| Property    | Value                                                                                                                                                                                               |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">20<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| X           | 0                                                                                                                                                                                                   |
| Y           | DataCardKey4.Y                                                                                                                                                                                      |
| ZIndex      | 4                                                                                                                                                                                                   |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Priority\_DataCard1 |

## StarVisible5

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                               |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Align'.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |

### Design

| Property    | Value                                                                                                                                                                                               |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| X           | 0                                                                                                                                                                                                   |
| Y           | DataCardKey5.Y                                                                                                                                                                                      |
| ZIndex      | 4                                                                                                                                                                                                   |

### Color Properties

### Child & Parent Controls

| Property       | Value                 |
| -------------- | --------------------- |
| Parent Control | Start date\_DataCard1 |

## StarVisible6

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                               |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Align'.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |

### Design

| Property    | Value                                                                                                                                                                                               |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| X           | 0                                                                                                                                                                                                   |
| Y           | DataCardKey6.Y                                                                                                                                                                                      |
| ZIndex      | 4                                                                                                                                                                                                   |

### Color Properties

### Child & Parent Controls

| Property       | Value               |
| -------------- | ------------------- |
| Parent Control | Due date\_DataCard1 |

## StarVisible7

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                               |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Align'.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |

### Design

| Property    | Value                                                                                                                                                                                               |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">20<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| X           | 0                                                                                                                                                                                                   |
| Y           | DataCardKey7.Y                                                                                                                                                                                      |
| ZIndex      | 4                                                                                                                                                                                                   |

### Color Properties

### Child & Parent Controls

| Property       | Value                  |
| -------------- | ---------------------- |
| Parent Control | Assigned to\_DataCard1 |

## StarVisible8

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                               |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Align'.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"*"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |

### Design

| Property    | Value                                                                                                                                                                                               |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                          |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| Visible     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">And(Parent.Required, Parent.DisplayMode=DisplayMode.Edit)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                        |
| X           | 0                                                                                                                                                                                                   |
| Y           | DataCardKey8.Y                                                                                                                                                                                      |
| ZIndex      | 4                                                                                                                                                                                                   |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | Notes\_DataCard1 |

## SubmitButton1

| Property                                                                                    | Value                                       |
| ------------------------------------------------------------------------------------------- | ------------------------------------------- |
| ![PowerApps\_CoreControls\_ButtonCanvas](resources/PowerApps_CoreControls_ButtonCanvas.png) | Type: PowerApps\_CoreControls\_ButtonCanvas |

### Behavior

| Property | Value                                                                                                                                                       |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">SubmitForm(Form1)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property   | Value                                                                                                                                                                       |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Appearance | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'ButtonCanvas.Appearance'.Primary<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Submit"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |

### Design

| Property    | Value                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">96<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X           | 0                                                                                                                                                          |
| Y           | 0                                                                                                                                                          |
| ZIndex      | 28                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Parent Control | ButtonContainer1 |

## Table1

| Property                                            | Value                  |
| --------------------------------------------------- | ---------------------- |
| ![PowerAppsOneGrid](resources/PowerAppsOneGrid.png) | Type: PowerAppsOneGrid |

### Behavior

| Property          | Value                                                                                                                                                                                                                          |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| onCellValueChange | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| onFilter          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| onNavigate        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| onRowSelect       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| onSave            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                |
| OnSelect          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">UpdateContext({ isItemSelected: true, newMode: false, CurrentItem:Table1.Selected })<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property             | Value                                                                                                                                                                                     |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DateOnlyFormat       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'PowerAppsOneGrid.DateOnlyFormat'.ShortDate<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| DateTimeFormat       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'PowerAppsOneGrid.DateTimeFormat'.ShortDateTime<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| EnableRangeSelection | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'PowerAppsOneGrid.EnableRangeSelection'.Enable<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| EnableSorting        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'PowerAppsOneGrid.EnableSorting'.Enable<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| Items                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'Work tracker / Testing'<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| ReflowBehavior       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'PowerAppsOneGrid.ReflowBehavior'.ListOnly<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |

### Design

| Property    | Value                                                                                                                                                                                                   |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                              |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Self.Y + 500 > Parent.Height, Parent.Height - Self.Y, 500)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Self.X + 800 > Parent.Width, Parent.Width - Self.X, 800)<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| X           | 0                                                                                                                                                                                                       |
| Y           | 0                                                                                                                                                                                                       |
| ZIndex      | 16                                                                                                                                                                                                      |

### Color Properties

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | Title1            |
| Child Control  | Progress1         |
| Child Control  | Priority1         |
| Child Control  | Start date1       |
| Child Control  | Due date1         |
| Child Control  | Assigned to1      |
| Child Control  | Notes1            |
| Parent Control | SidebarContainer1 |

## TextCanvas1

| Property                                                                                | Value                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerApps\_CoreControls\_TextCanvas](resources/PowerApps_CoreControls_TextCanvas.png) | Type: PowerApps\_CoreControls\_TextCanvas |

### Data

| Property | Value                                                                                                                                                                                    |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'TextCanvas.Align'.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Size     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                             |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Are you sure you want to delete this record?"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property    | Value                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">96<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X           | 0                                                                                                                                                          |
| Y           | 0                                                                                                                                                          |
| ZIndex      | 8                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value                        |
| -------------- | ---------------------------- |
| Parent Control | ConfirmDeleteLabelContainer1 |

## Title\_DataCard1

| Property                                      | Value               |
| --------------------------------------------- | ------------------- |
| ![typedDataCard](resources/typedDataCard.png) | Type: typedDataCard |

### Data

| Property    | Value                                                                                                                                                                                                                    |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| DataField   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Title"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                        |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Title<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                 |
| DisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'],DataSourceInfo.DisplayName,'Title')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| MaxLength   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataSourceInfo([@'Work tracker / Testing'], DataSourceInfo.MaxLength, 'Title')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Required    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                          |
| Update      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DataCardValue1.Value<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                           |

### Design

| Property    | Value                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| DisplayMode | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.DisplayMode<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">459<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| X           | 0                                                                                                                                                            |
| Y           | 0                                                                                                                                                            |
| ZIndex      | 26                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | App.Theme.Colors.Darker40                                                                                                                                                                                                                                                                                                            |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Child Control  | StarVisible1   |
| Child Control  | DataCardKey1   |
| Child Control  | DataCardValue1 |
| Child Control  | ErrorMessage1  |
| Parent Control | Form1          |

## Title1

| Property                                                                                 | Value                                     |
| ---------------------------------------------------------------------------------------- | ----------------------------------------- |
| ![PowerAppsOneGridTemplate\_dataField](resources/PowerAppsOneGridTemplate_dataField.png) | Type: PowerAppsOneGridTemplate\_dataField |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Title"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Title"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldType        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"s"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |

### Design

| Property | Value                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Height   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| X        | 0                                                                                                                                             |
| Y        | 0                                                                                                                                             |
| ZIndex   | 29                                                                                                                                            |

### Color Properties

### Child & Parent Controls

| Property       | Value  |
| -------------- | ------ |
| Parent Control | Table1 |
