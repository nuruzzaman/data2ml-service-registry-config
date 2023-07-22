# service-discovery-config
JGit library used by Spring Cloud Config Server uses SSH configuration files. 

When running the Service Registry with the git profile, it uses this sample repository by default, and will serve the application.yml file that is located at the root directory.

For real-world usage, you should replace this repository by your own repository, where you can manage your own Yaml configuration files.
