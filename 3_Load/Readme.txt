The Open Source Dashboard for Salesforce uses a Combined Purpose QVF/QVW; therefore, this directory is empty.

A Combined Purpose QVF/QVW serves 2 roles or purposes from a 4-stage ETL architecture: DataModel LOADer and front-end user interface APP.
Combining these 2 purposes into 1 QVF/QVW avoids the need to BINARY LOAD a separate DataModel QVF/QVW. As such, a Combined Purpose QVF/QVW 
implements the 3rd stage of a 3-stage ETL Architecture. Please see the TSEEQ Documentation PDF for additional discussion of 3-stage
and 4-stage ETL architectures: https://github.com/qlikperf/TSEEQ/blob/master/TSEEQ%20Documentation.pdf