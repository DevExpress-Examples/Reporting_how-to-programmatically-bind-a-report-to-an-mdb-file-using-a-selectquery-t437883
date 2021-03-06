<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/RuntimeBindingToMdbDatabase/Form1.cs) (VB: [Form1.vb](./VB/RuntimeBindingToMdbDatabase/Form1.vb))
* [Program.cs](./CS/RuntimeBindingToMdbDatabase/Program.cs) (VB: [Program.vb](./VB/RuntimeBindingToMdbDatabase/Program.vb))
<!-- default file list end -->
# How to programmatically bind a report to an MDB file using a SelectQuery


<p>This example demonstrates how to create a new blank report (an instance of the <a href="https://documentation.devexpress.com/#XtraReports/clsDevExpressXtraReportsUIXtraReporttopic">XtraReport</a> class), bind it to an MDB file, and then, fill the report with a <a href="https://documentation.devexpress.com/#XtraReports/clsDevExpressXtraReportsUIDetailBandtopic">DetailBand</a> containing <a href="https://documentation.devexpress.com/#XtraReports/clsDevExpressXtraReportsUIXRLabeltopic">XRLabels</a> to show obtained data. <br><br>To bind the report to an MDB file, create a <a href="https://documentation.devexpress.com/#CoreLibraries/clsDevExpressDataAccessSqlSqlDataSourcetopic">SqlDataSource</a> class instance with the required connection parameters. Then, create a <a href="https://documentation.devexpress.com/#CoreLibraries/clsDevExpressDataAccessSqlSelectQuerytopic">SelectQuery</a> to select columns from two data tables using an inner join relation as well as apply sorting, grouping, filtering and aggregation to data. To assign the created data source to the report, use the report's <a href="https://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXtraReportBase_DataSourcetopic">DataSource</a> and <a href="https://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXtraReportBase_DataMembertopic">DataMember</a> properties.<br><br>Starting with v.17.2, the report uses <a href="https://documentation.devexpress.com/XtraReports/119236/Creating-Reports-in-Visual-Studio/Detailed-Guide-to-DevExpress-Reporting/Providing-Data-to-Reports/Data-Binding-Overview/Data-Binding-Modes">expression bindings</a> to provide data to controls. You can switch to the legacy binding mode by setting the <a href="https://documentation.devexpress.com/XtraReports/DevExpress.XtraReports.Configuration.UserDesignerOptions.DataBindingMode.property">UserDesignerOptions.DataBindingMode</a> property to <strong>Bindings </strong>at the application startup.<br><strong><br>See Also</strong></p>
<p><a href="https://www.devexpress.com/Support/Center/Example/Details/E1357">How to programmatically bind a report to an MDB file using a CustomSqlQuery </a></p>

<br/>


