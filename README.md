# RancherOS alternative consoles
Alternative consoles for RancherOS

# Adding this repository in Cloud Config

    rancher:
      repositories:
        consoles:
          url: https://raw.githubusercontent.com/jpmsb/rancheros-consoles/v1.5.x
      services_include:
        kernel-extras: true
        kernel-headers: true
        kernel-headers-system-docker: true
