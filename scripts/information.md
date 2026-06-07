Bronze Bucket Name - yt-data-pipeline-brozne-ap-southeast-2-dev 
Silver Bucket Name - yt-data-pipelines-silver-ap-southeast-2-dev 
Gold Bucket Name - yt-data-pipelines-gold-ap-southeast-2-dev

Script Bucket Name - yt-data-pipelines-script-ap-southeast-2-dev

SNS ARN - arn:aws:sns:ap-southeast-2:<ACCOUNT_ID>:yt-data-pipeline-alerts-dev

Glue Bronze - yt_pipeline_bronze_dev 
Glue Silver - yt_pipeline_silver_dev 
Glue Gold - yt_pipeline_gold_dev

--bronze_database yt_pipeline_bronze_dev 
--bronze_table raw_statistics 
--silver_bucket yt-data-pipelines-silver-ap-southeast-2-dev 
--silver_database yt_pipeline_silver_dev 
--silver_table clean_statistics

--silver_database yt_pipeline_silver_dev 
--gold_bucket yt-data-pipelines-gold-ap-southeast-2-dev 
--gold_database yt_pipeline_gold_dev