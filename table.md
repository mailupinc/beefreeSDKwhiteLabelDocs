# Table

## Overview

The Table content block is now available through the Beefree SDK Builder. This feature allows you to add tables to emails, pages, and popups. Continue reading to learn more about how to use the table content block within the builder.&#x20;

## How to Use

To use the Table content block, take the following steps:

1. Log in to the application
2. Open one of your Beefree SDK builders (email, popup, page)
3. Navigate to your builder
4. Identify the Table content block inside panel with your content block options
5. Drag and drop the Table content block inside the stage of the builder
6. Edit your table accordingly

### Customizable Table Settings

You can customize various settings of the table content block. In this section, we will explore the different customizable settings and what they enable you to do.&#x20;

#### Header Section

The Table content block includes the option to add headers to the first row of the table. These headers behave as column titles and enable you to associate each column with a category.

You can choose to make your table with or without a header row. If you initially create the table with a header, delete it, and then decide to add it back later, any formatting or styles from the original header will be lost. You'll have to start designing the header row from scratch again.

#### Structure

You’ll have the following options for customizing the structure of your table content block:

* **Columns:** Add or remove columns to the right of your table. The maximum number of columns you can add is eight.
* **Rows:** Add or remove rows to the bottom of the table. There is no maximum number of rows you can add to the bottom of your table.
* **Background color:** Edit your table’s background color.
* **Border:** Customize your border style. You have the option to choose from solid, dotted, and dashed. You can also select a custom border color and size.

**Note:** For dotted and dashed border styles, a thickness greater than five results in large circles or rectangles as the border. For the best results, use a border thickness of five or less for those border style types.

#### Striped Rows

You can use the Striped Rows content property to create rows with alternating colors.

To add Striped Rows to your table, take the following steps:

1. Navigate to the builder
2. Identify the Table content block
3. Drag and drop the Table content block on to the builder stage
4. Click the Table
5. Navigate to Striped Rows under Content Properties inside the panel on the right hand side of the screen
6. Toggle Striped Rows to on
7. Select the background color you want to apply for the alternating rows

**Note:** The initial table background color you select will be the other alternating color in your table.

The following GIF demonstrates an example of what this content property enables you to do.

<figure><img src="https://lh7-eu.googleusercontent.com/lw8gaZg0W4E0WpHLDTtqFgFEWUMxK8GZGpibHFplQLYgLXos5MtrLF6wamJCUt5GrQcRu8IFwP3V_B6lPBsVuU1FMfkQ-K1dckMLr3uXf6BK5aZw9cXBV0JrRr0EdGyOzPIn_H9zG9EQ-e75YAK-Wsw" alt=""><figcaption></figcaption></figure>

#### Content

You’ll have the following options for customizing the content of your table content block:

* Font Family
* Font Weight
* Font Size
* Text Color
* Link Color
* Align
* Line Weight
* Letter Spacing
* Text direction

**Note:** These settings are applied to all the content within the table content block.

## Accessibility Keys

For keyboard accessibility, we followed the aria grid pattern. To learn more about what the ARIA Grid Pattern is, visit the [ARIA Grid Pattern article](https://www.w3.org/WAI/ARIA/apg/patterns/grid/).

The ARIA Grid Pattern is a set of guidelines outlined by the W3C's Accessible Rich Internet Applications (ARIA) specification to enhance keyboard accessibility within web applications. It provides a structured approach for developers to create accessible grids, tables, and similar components, ensuring users can navigate and interact with them efficiently using keyboard controls alone. By adhering to the ARIA Grid Pattern, developers can ensure that all users have access to an inclusive application experience.

### Setting Your Focus

To set your focus for using navigation keys, take the following steps:

1. Navigate in Rows: Move through rows using your arrow keys. When focused on the table, pressing Enter will direct the focus to the first cell, enabling grid navigation.
2. Grid Navigation: Once in grid navigation mode, press Enter or start typing to shift focus to the builder inside the cell you're currently focused on.
3. Move Between Builders: While using the builder in a cell, if you wish to move directly to another builder in an adjacent cell:
   1. To move forwards, press Enter or Tab.
   2. To move backwards, use Shift + Enter or Shift + Tab.

By following these steps, you can set the focus for your navigation.

In addition to the ARIA Grid Pattern, we also included the following custom behaviors:

* **Enter Key to navigate vertically through cells:** The Enter key has different functions depending on your current focus. The following list shows the different functions of the Enter key for each focus:
  * **When focus is on the module:** Pressing Enter sets focus to the first cell of the grid selection.
  * **When focus is on a cell:** Pressing Enter while editing the content of the cell sets focus to the builder inside the cell.&#x20;
  * **When focus is in the builder inside a cell:** Pressing Enter while editing the content of the cell sets focus to the builder in the cell above or below, depending on the direction.&#x20;
  * **Shift+Enter combination:** Clicking Shift+Enter inverts the direction of the Enter key behavior.
* **Tab Key to navigate horizontally between cells:** Use the tab key to navigate between cells horizontally. If you are in a cell in the final column on the right side of the table, you will be navigated to the same level cell in the first column of the table.&#x20;
* **Delete cell contents:** To delete a cell’s contents, use the backspace key when you are in the grid section.
* **Line break:** To perform a line break while in a cell, click alt, ctrl, or metakey + Enter. For example, on a Mac keyboard, you would click command, plus sign (+), and then enter to perform a line break within a cell.

## Additional Considerations

It is important to understand that this is a developing feature. While most customizable settings work as expected, a few combinations can result in odd-looking tables.

Here is a list of combinations to avoid for the best possible table results:

* Border thickness of five or higher for dashed and dotted border styles
* Removed header will permanently lose their styles

Another consideration to keep in mind when using the Table Content Block is to ensure you verify how your design with the table looks in mobile mode. At times, too many columns within a table can result in a mobile design view that is not ideal or presents as intended.&#x20;

We do not yet have Mobile Style Properties for the Table Content Block. In the event you preview the mobile version of your table design, and it does not look ideal, you can move forward with one of the two options:

* Use the Hide On Desktop/Mobile feature
* Edit your table within your design and test the mobile preview again

For more information on how to ensure your table is compatible on mobile devices, visit our [Mobile Design Mode article](https://devportal.beefree.io/hc/en-us/articles/10679589051154-Mobile-design-mode).
