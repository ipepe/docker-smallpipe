# docker-smallpipe
Smallpipe is docker container/image that is focused on running simple CI/CD pipelines directly on Your docker host. It is targetted at small companies, startups, development and staging enviroments.

# Fatures/TODO list
 * Email notifications (build failed, tests in progress, deploy succeded, git polling failed)
 * Ability to define *smallpipe* as linked container in docker-compose for ie. react projects
 * Git polling (github/gitlab)
   * with ssh keys?
   * cron based
 * Programmable pipelines, preferably from docker labels or files
