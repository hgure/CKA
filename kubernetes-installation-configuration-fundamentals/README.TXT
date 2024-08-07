***All demos have been tested against Ubuntu 22.04 and Kubernetes 1.29.1***

There may be slight differences in the code from what's in the video course, but the concepts are all the same.
* Update 23 Feb 2023
  * Changed Kubernetes version to 1.29.1

* Key updates
  * Update Kubernetes package repositories
  * Setting the systemd cgroup driver in config.toml...the two lines I added in the video are now there by default. You just have to change SystemdCgroup = false to SystemdCgroup = true
  * You no longer need to create and edit ClusterConfiguration.yaml 
  * kubeadm 1.22 removed the need to use the parameters --config=ClusterConfiguration.yaml and --cri-socket /run/containerd/containerd.sock these parameters are no longer needed

If you have any issues please feel free to reach out in the course discussion page.

aen@centinosystems.com or in the course discussion page at www.pluralsight.com

