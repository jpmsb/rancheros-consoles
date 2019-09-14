# RancherOS alternative consoles
Alternative consoles for RancherOS which provides extra tools and even a Desktop Environment out of the box.

# Adding this repository in Cloud Config

    rancher:
      repositories:
        consoles:
          url: https://raw.githubusercontent.com/jpmsb/rancheros-consoles/stable
      services_include:
        kernel-extras: true
        kernel-headers: true
        kernel-headers-system-docker: true
