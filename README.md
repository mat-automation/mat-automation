<h1 align="center">Hi 👋, I'm Mat (Mathias) Lemke</h1>
<h3 align="center">A bi-lingual (Brit. English & German) tech enthusiast with two decades of experience focused on GNU/Linux, virtualisation, storage and backup solutions.</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=mat-automation&label=Profile%20views&color=0e75b6&style=flat" alt="mat-automation" /> </p>

Storage Engineer, Storage Admin. I work mainly with Linux as well as w/ NetApp & DELL-EMC PowerScale.

🌱 I’m currently learning to become an **DevOps Engineer** specialiast for Storage Systems

Also I'm an open source enthusiast #Arch #Linux 🐧

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/mat-lemke-b156a121" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="mat-lemke-b156a121" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> </p>



## Things I've Built

I'm in love with my HomeLab because there is always something exciting and new to learn.
At the core runs Proxmox and Docker (LXC Container, soon to be run by Kubernetes) to serve several basic IT needs:

- PVE x2 (Minis Forum MS-01 & HUNSN RJ03)
- PBS (HUNSN RJ42)

Routing and firewall is handled by an virt OPNsense and 3x multi-gig switches.

I host these services:
- OPNsense Firewall
- AdGuard/ Pi-hole & Win Srv (DC/DNS)
- phpIPAM
- Heimdall, a bookmark manager
- virt NAS (incl. the media server Jellyfin)
- Nextcloud
- Vaultwarden, a private hosted password manager based on Bitwarden
- Immich, an automatic private photo & video backup for all mobile devices
- home assistant
- audiobookshelf, a web app to manage my audiobooks and podcasts
- Paperless ngx
- Uptime Kuma, CheckMK & Pulse, simple monitoring of all services and IT appliances

🔭 I’m currently working on
- a few Linux VM to catch up with their latest developments
- 2x Kubernetes cluster: Talos & K3S on Debian 13
- virt 3x node PVE cluster w/ ceph storage

Further projects in the near future:
- VMware 9 & Veeam BR trials
- Prometheus, Grafana
- Helm, Terraform, Ansible 

The QNAP hosts all my personal data as well as the 2nd PBS weekly backups on to an all flash based NFS share. It runs daily snapshots and weekly backups on to a Terramaster nested DSM7 🤫

Monthly backups are send to TrueNAS Scale hosted on an aging DELL T320. Quarterly dumps (in case I do remember) go on to LTO tapes via Acronis which are swapped over regularly and stored externally.
