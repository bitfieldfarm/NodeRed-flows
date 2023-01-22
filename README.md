# NodeRed-flows
NodeRed flows for FarmOS

### Growth measuring.json
Flow to help tracking pig growth.
Adds a form to register weight, and store it in farmOS as observation log to the respective pig batch asset.
It also makes use of the batches created in the activities_and_batches flow.

![bilde](https://user-images.githubusercontent.com/98184919/210180958-d5236bb3-5368-40c7-ba39-b106c3861f32.png)

### Activities and batches
Displays upcoming events on the dashboard and helps create farrowing and weaning batches.
Batches are animal assets in farmOS, designed to be archived after the batch is passed on to the next stage.
So, the batch is an asset to collect all events happeing during that period.

2 events are currently supported. Weaning and farrowing.

See comments within flow for details
![bilde](https://user-images.githubusercontent.com/98184919/213906746-73305f49-fd3b-4bb1-96e2-93dea336c395.png)


### Add_Activity.json 
Subflow to provide visual feedback of result when making a request to farmOS

