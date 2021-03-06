# DAXDUTIL
Microsoft Dynamics AX Utilities for developers

This is a list with some utilities and tools that might be useful at DAX development process. Each file represents a single project and were written in a clean AX enviroment.
 
You are more than welcome to contribute with your awsome utility/tool.

### DAX 2012 tools
* [Tables](https://github.com/anderson-joyle/DAXDUTIL/tree/master/Tables)
  * [Find method](https://github.com/anderson-joyle/DAXDUTIL/blob/master/Tables/DAXD_TableFindMethod.xpo) - Creates the method finds based on table's key/index properties. In order of relevance: *ReplacementKey* and *PrimaryIndex*. To use it, create a new table method and *right click > Scripts > template > table > find*
  * [Table 2 Form](https://github.com/anderson-joyle/DAXDUTIL/blob/dev/Tables/DAXD_Table2Form.xpo) - Creates a form based on a table. Its considered the table group property to define witch form template will be used. To use it, follow the [manual](http://andersonjoyle.com/2016/06/08/daxdutil-table-2-form-manual).

* [Queries](https://github.com/anderson-joyle/DAXDUTIL/tree/master/Queries)
  * [Build query](https://github.com/anderson-joyle/DAXDUTIL/blob/master/Queries/DAXDUtil_QueryBuildQuery.xpo) - Creates x++ query code. By default, declares two query datasources using {TABLE_NAME#} notation, wich you can replace with any table name. Also, two query range are declared with {FIELD_NAME#} notation. Note that by definition, the {FIELD_NAME1} refers to {TABLE_NAME1} and {FIELD_NAME2} refers to {TABLE_NAME3}.To use it, *right click > Scripts > template > database > buildQuery* or simply type *buildQuery* on code editor.

* [Projects](https://github.com/anderson-joyle/DAXDUTIL/tree/master/Projects)
  * [Multi project export](https://github.com/anderson-joyle/DAXDUTIL/blob/master/Projects/DAXD_MultiProjectExport.xpo) - Enable the developer to export multiple projects at once, filtering by prefix, suffix and/or layer. To use it, follow the [manual](http://andersonjoyle.com/2016/08/02/daxdutil-multiple-project-export-manual).



