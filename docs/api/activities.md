---
layout: page
---

# `activities` resource

Base endpoint:

```shell

{server_url}/activities
```

Contains information about tasks stored for the users of the service.

To have a task in the service, the user must be added to
the service first. Learn more about the [user resource](user.md).

## Resource properties

Sample `activities` resource

```js

{
    "activityId": "run001",
    "type": "running",
    "durationMinutes": 30,
    "distanceKm": 5,
    "caloriesBurned": 300,
    "startTime": "2023-10-09T07:30:00Z",
    "endTime": "2023-10-09T08:00:00Z",
    "notes": "Morning run in the park",
    "userId": 1
}
```

| Property name | Type | Description |
| ------------- | ----------- | ----------- |
| `activityId` | number | The ID of the activity reference to which this activity is assigned |
| `type` | string | The name of the activity |
| `durationMinutes` | number | The time it took to complete this activity |
| `distanceKM` | number | The distance relative to the `durationMinutes` that the activity took to complete. This should be in kilometeres (KM).
| `caloriesBurned` | number | The amount of calories burned during the activity.
| `startTime` | number | The date and time the user started the activity.
| `endTime` | number | The date and time you completed the activity.
| `notes` | string | Any details about the activity.
| `userId` | number | The ID of the activity resource to which this task is assigned.

## Read

* [Get all tasks _(coming soon)_](#resource-properties)
* [Get task by ID _(coming soon)_](#resource-properties)

## Create

* [Add an activity resource] (_coming soon_)

## Update

* [Put task by ID] (_coming soon_)
