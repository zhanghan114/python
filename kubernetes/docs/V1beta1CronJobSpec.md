# V1beta1CronJobSpec

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**concurrency_policy** | **str** | Specifies how to treat concurrent executions of a Job. Defaults to Allow. | [optional] 
**failed_jobs_history_limit** | **int** | The number of failed finished jobs to retain. This is a pointer to distinguish between explicit zero and not specified. Defaults to 1. | [optional] 
**job_template** | [**V1beta1JobTemplateSpec**](V1beta1JobTemplateSpec.md) | Specifies the job that will be created when executing a CronJob. | 
**schedule** | **str** | The schedule in Cron format, see https://en.wikipedia.org/wiki/Cron. | 
**starting_deadline_seconds** | **int** | Optional deadline in seconds for starting the job if it misses scheduled time for any reason.  Missed jobs executions will be counted as failed ones. | [optional] 
**successful_jobs_history_limit** | **int** | The number of successful finished jobs to retain. This is a pointer to distinguish between explicit zero and not specified. Defaults to 3. | [optional] 
**suspend** | **bool** | This flag tells the controller to suspend subsequent executions, it does not apply to already started executions.  Defaults to false. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


