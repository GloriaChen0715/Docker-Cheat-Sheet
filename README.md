# Docker-Cheat-Sheet

Monitoring/Removing Images
task	command
list images	docker images
remove specific image(s)	docker rmi <image_id> <image_id> ...
remove dangling images	docker image prune
remove all unused images	docker image prune --all
remove all images	docker rmi -f $(docker images -q)
