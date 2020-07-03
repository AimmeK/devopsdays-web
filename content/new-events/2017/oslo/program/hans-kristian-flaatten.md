+++
description = ""
title = "Ignite: \"A container’s journey from push to production - how Fiskeridirektoratet deploys applications\""
type = "new-talk"
speakers = [
        "hans-kristian-flaatten",
]
pdf = "https://assets.devopsdays.org/events/2017/oslo/slides/hans-kristian-flaatten.pdf"
+++
In this talk I will take the audience on a journey a single commit takes when it first leave the developer's machine, and how it ends up in a production environment at the Directorate of Fisheries (Fiskeridirektoratet).

When a developer commits and pushes their changes the change is automatically picked up by the CI system that starts tugging along. Building, testing, more tests, and security scans are all run on the code before it continues it's path to a running state. A container image is built and stored in a registry before the application is deployed to one of several Kubernetes environments. From here logging and monitoring are all picked up automatically for the fresh application.

This is how all of the actively maintained applications at the Directorate are deployed, and we completed the transformation from a completely manual process in little less then a year!