Generally the reporting tools do not allow modifying data in the source as they are read-only. The write-back function in Power Apps is available to accommodate this. Write-back enables end users to change and update the values in the data source directly from the Power BI report. 

To do write-back, the connection with the data source should be done by DirectQuery mode as the results will be immediately noticed without a hard refresh on the Power BI dataset.
