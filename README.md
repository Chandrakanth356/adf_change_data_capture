# adf_change_data_capture

Change Data Capture in adf enables you to configure source and sink where you want to transfer delta data in realtime without creating any pipelines, datasets and triggers.

Two ways to do CDC 1. using CDC resource
                  2. using CDC capability in activities and dataflows
Currently it supports sources - Azure cosmos db, Azure sql db, Azure sql db managed instance; sql and snowflacke databases; and different file formats where adf cdc can capture these file changes in a folder.

In this section I have implemented CDC using resource in ADF.
1. From a folder where csv file changes captured in realtime to sqldatabase
2. From a folder where parquet file changes captured in realtime to sqldatabase

Note: Can implement cdc from sql db, but in free tier sql db we cant enable cdc capability, So I have implemented for files only.
