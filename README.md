# SortableColumns
SortableColumns is a Zikula component to help manage data table column headings that can be clicked to sort the data.
The collection is an `Doctrine\Common\Collections\ArrayCollection` of `Zikula\Component\SortableColumns\Column` objects.
Use `SortableColumns::generateSortableColumns` to create an array of attributes (url, css class) indexed by column name
which can be used in the generation of table headings/links.
