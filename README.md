# Homelab

## Parts
1. UniFi Dream Machine Pro
2. 2x UniFi PRO Access Points
3. Antsle one XD:
    - 4 Cores (8 Threads)
    - 32GB DDR4 ECC RAM
    - 2 x 250GB SSD
    - ZFS
4. Monoprice 9U 450mm Depth Server Cabinet
5. QNAP 2 Bay NAS with 4TB Seagate IronWolf Drives
6. NETGEAR Cable Modem CM1000
7. 3x 8GB Raspberry Pi 4
8. 3x [S2PI ice tower CPU cooling fans](https://www.seeedstudio.com/ICE-Tower-CPU-Cooling-Fan-for-Raspberry-Pi-Support-Pi-4-p-4097.html)

**3/7/20** - Set up disk mirroring (RAID 1) on the QNAP between the 2 4TB Seagate drives

**3/8/20** - Spin up an s3 compatible object store on the QNAP and test that I can communicate through Go & Rust programs

**3/21/20** - Set up Antsle one XD

**6/9/20** - Add 3x 8GB Raspberry Pi 4 (k8s cluster) to the network

**10/16/20** - Remove k8s from the raspberry pis in favor of starting to create my own personal cloud. Starting to research what it would look like to build with Go & libvirt... Then even further out, I'd love to build GUI for it.

## Homelab
![homelab](img/homelab_v1.jpeg)

## Kubernetes cluster
Just got these CPU cooling fan heatsinks for the pis and they are awesome!
Dropped temps ~25 degrees during a quick test.

![new k8s cluster](img/k8s_cluster.jpg)