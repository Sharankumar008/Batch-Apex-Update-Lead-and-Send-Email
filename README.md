# Batch-Apex-Update-Lead-and-Send-Email

Lead created 7 days before and still not started(open - not contacted), update the lead status as closed - not converted

//Anonymous window

Database.executeBatch(new LeadUpdateStatusBatch());
