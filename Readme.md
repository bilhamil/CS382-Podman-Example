This is a sample podman compose project for starting a node application with mongodb.

To start these containers you can run:

`podman-compose -f compose.yml up`

This will build your containers, start them, and show you their output output.
If this has all gone to plan, your container should be reachable at the specified port
number in the compose file.

---

To stop these container you can run:

`podman-compose -f compose.yml down`

---

To start your containers in the background, you can run:

`podman-compose -f compose.yml  up --detach`

---

To see all running containers you can run:

`podman ps`

---

To stop a specific container you can run:

`podman stop <CONTAINER ID>`
